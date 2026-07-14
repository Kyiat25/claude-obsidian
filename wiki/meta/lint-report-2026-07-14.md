---
type: meta
title: "Lint Report 2026-07-14"
created: 2026-07-14
updated: 2026-07-14
tags: [meta, lint]
status: developing
---

# Lint Report: 2026-07-14

Full filesystem scan (no CLI/MCP transport available this pass — filesystem floor used). Semantic tiling (DragonScale Mechanism 3) skipped: `scripts/tiling-check.py` requires a local ollama endpoint not reachable in this environment. Everything else below ran to completion.

## Summary

- Pages scanned: 628 (`wiki/**/*.md`)
- Address-tracked pages (DragonScale Mechanism 2, active — `.vault-meta/address-counter.txt` present): counter = 577, highest observed `c-` address = `c-000577`
- Genuine issues found: ~24 fixable dead-link occurrences across 15 files, 1 address-counter drift, 6 candidate missing pages, 1 table-escaping bug (6 links)
- Noise ruled out after investigation: 2 apparent orphans (false alarm — intentionally doc-linked, not wiki-internal), ~70 "empty section" false positives (header immediately followed by a deeper subheading, or heading-regex matching `#` inside a fenced shell-command block), 1 "duplicate filename" that's an intentional convention (`_index.md` × 3, one per top-level folder)
- Needs review, not auto-fixed: everything below is presented for a decision before any write happens

---

## Address Validation (DragonScale Mechanism 2)

- Counter state: `577` (from `.vault-meta/address-counter.txt`)
- Highest `c-` address observed on any page: `c-000577` ([[Natural Philosophy of Elarion]])
- Format check: 0 malformed addresses (`c-NNNNNN`/`l-NNNNNN` regex — all pass)
- Uniqueness check: 0 collisions
- Manifest consistency (`.raw/.manifest.json` `address_map`): 0 mismatches, 0 dangling entries

### Errors

- **Counter drift**: the counter file reads `577`, but a page already holds `c-000577`. `allocate-address.sh` treats the counter value as "next address to issue" (confirmed from its own recovery-mode comment: `set to $((max_c + 1))`). The very next `allocate` call will re-issue `c-000577`, colliding with [[Natural Philosophy of Elarion]]. **Fix**: bump `.vault-meta/address-counter.txt` from `577` to `578`. One-line, mechanical, no content risk — flagging for confirmation before I touch it since it's a shared coordination file, not vault content.

---

## Dead Links (real, fixable)

Wikilink text that doesn't match any actual page's filename. Grouped by cause.

### A. Missing "The" prefix mismatch — pantheon hub pages

Actual pages are titled without "The" ([[Air Pantheon]], [[Earth Pantheon]], [[Fire Pantheon]], [[Spirit Pantheon]], [[Water Pantheon]]), but several links use a "The X Pantheon" form that doesn't resolve:

- `[[The Air Pantheon]]` — in `wiki/index.md` (×1), `wiki/notes/Fire Pantheon.md`, `wiki/notes/Xethar.md`
- `[[The Water Pantheon]]`, `[[The Spirit Pantheon]]`, `[[The Earth Pantheon]]`, `[[The Fire Pantheon]]` — each ×1, all in `wiki/index.md`

**Fix**: drop "The " from all 7 occurrences to match the real page names. Safe, mechanical.

### B. Missing "The" prefix mismatch — reverse case

- `[[Faith of the Bound Pattern]]` in `wiki/notes/Glyph of Threads.md` and `wiki/notes/Three Pillars of Magical Flow.md` — actual page is [[The Faith of the Bound Pattern]] (has the prefix). **Fix**: add "The ".

### C. Singular/plural or short-title mismatches

- `[[Called Shots]]` in `wiki/notes/Converting Monsters to DCS.md` → actual page is [[Called Shot]] (singular).
- `[[Wild Magic Zones]]` in `wiki/notes/Form Glyphs.md` → actual page is [[Wild Magic Zone]] (singular).
- `[[Eldritch Forces]]` in `wiki/notes/Styles of Magic.md` → actual page is [[Guide to the Eldritch Forces]].

### D. "Fall of Ashkarra" — no such page exists; only [[Ashkarra]] does

- `[[Fall of Ashkarra]]` in `wiki/notes/Cross-Relationships of the Eldritch.md`, `wiki/notes/The Faith of the Bound Pattern.md`, `wiki/notes/The Woven Reverence.md`
- `[[The Fall of Ashkarra]]` in `wiki/notes/The Burning Concord.md`

All four are almost certainly meant to point at [[Ashkarra]] (the source file `Fall of Ashkarra.md` was folded into that page, not given its own wiki page). **Needs a quick content check per occurrence before repointing** — flagging as fixable but not blindly automatic, since "Fall of Ashkarra" the event and "Ashkarra" the city page aren't strictly identical.

### E. Lineage links missing their disambiguator

- `[[Dragonborn]]` in `wiki/notes/Cross-Pantheon Relationships (Fire).md` — could mean [[Dragonborn (Lineage)]] or the dragonborn people/empire generally (no general page exists). **Needs review**, not auto-fixed.
- `[[Aasimar]]` in `wiki/notes/Tiefling (Lineage).md` — likely means [[Aasimar (Lineage)]]. Same ambiguity, lower risk.

### F. Raw-source filenames wrapped in `[[wikilinks]]` instead of code formatting

These are `.raw/` source filenames (underscore-variant), not wiki pages — they were probably meant as \`code\`-formatted source citations, not links:

- `[[The_Air_Pantheon]]` in `wiki/hot.md`
- `[[FEARS_Corrected_Lineage_Analysis]]` in `wiki/notes/FEARS Lineages.md`, `wiki/notes/Hobgoblin (Lineage).md`, `wiki/notes/Human (Lineage).md`
- `[[Guide to Vel Zyren The Web Spinner]]` in `wiki/index.md` — same issue, the real page is [[Vel'Zyren]] plus its own rewrite; this was the raw source title.

**Fix**: convert each to plain backtick-formatted text (`` `The_Air_Pantheon.md` ``) rather than a wikilink, matching how other raw-source citations are formatted elsewhere in the vault.

### G. Markdown-table pipe-escaping bug (needs manual rework, not a text swap)

`wiki/notes/The Lie of Godhood.md` line 64 (and presumably its sibling rows) uses `[[Fire Pantheon\|Fire]]` inside a markdown table cell. The `\|` needed to keep the table column from breaking swallows into the wikilink's own alias-pipe syntax, so Obsidian resolves the link target as literally `Fire Pantheon\` (trailing backslash) instead of `Fire Pantheon` with alias `Fire`. Confirmed broken the same way for:

- `Fire Pantheon\`, `Water Pantheon\`, `Earth Pantheon\`, `Air Pantheon\`, `Spirit Pantheon\`, `The Hollow Thread\` — all in the same table on this page.

**Fix requires restructuring**, not a straight substitution — likely either drop the alias (`[[Fire Pantheon]]` with the pantheon name as the visible text) or use an HTML entity for the pipe (`&#124;`). Flagging for a decision rather than guessing which the table's layout can tolerate.

### H. Question mark not valid in the real filename

- `[[How does the LLM Wiki pattern work?]]` in `wiki/hot.md`, `wiki/log.md` (and inside the prior lint report, ignored below) — the real page is [[How does the LLM Wiki pattern work]] (no `?`, since `?` isn't legal in Windows filenames). **Fix**: drop the trailing `?` from both occurrences.

### I. Likely stub-worthy but low-priority single mentions

- `'Charmed'` in `wiki/notes/Disposition.md` — a generic status-condition term, probably shouldn't be a wikilink at all (no dedicated page needed).
- `'wikilinks'` in `wiki/concepts/cherry-picks.md` — reads like a generic word accidentally wrapped in brackets.
- `'Three laws of motion'` in `wiki/concepts/Persistent Wiki Artifact.md` — likely an analogy reference, not a real target.
- `'Skyreach'` in `wiki/notes/Cross-Pantheon Relationships (Fire).md` — single mention, unclear if meant to be its own page.
- `'The 9 Fundamental Forces'` in `wiki/notes/The Weave Unbroken.md` — no hub page currently ties this exact phrase together; possibly should point at [[Astralor]]/[[Aeloria]]/cosmology cluster instead.

Low priority — none of these block anything; listed for completeness.

---

## Missing Pages (mentioned across multiple pages, no dedicated page yet)

| Candidate | Mentions | Notes |
|---|---|---|
| **Kerythra** | 8 pages | "The Wild Continent" — named constantly across the Second Age history, regional-variation sections of the just-finished Class Lore Compendium pass, and pantheon material, but has no page of its own. Highest-value gap here by far. |
| **The Fractured Pillar** | 3 pages | Referenced from [[Vatharun]] and [[Gaeldros]] (Earth Pantheon deities). |
| **Varlen** | 3 pages | Referenced from [[Earth Pantheon]] and [[Torvax]]. |
| **The Lock That Holds the World** | 2 pages | Referenced from [[Earth Pantheon]]. |
| **The Nameless One Below** | 2 pages | Referenced from [[Earth Pantheon]]. |
| **Iriveth Orre** | 1 page (2 mentions within it) | A named continent housing [[Aeravae]], described in [[Dór-o Estel]] with an already-flagged internal contradiction (ice/aurora vs. jungle/aquifer across two sources). Worth a dedicated page given the contradiction alone. |

Not created this pass — flagged for a future ingest/write session rather than rushed stubs, consistent with this vault's established convention.

---

## Orphan Pages — investigated, not real issues

Initial scan flagged 2 pages with zero *wiki-internal* inbound links:

- [[methodology-modes-guide|wiki/references/methodology-modes.md]] and `wiki/references/transport-fallback.md` — both are linked from `CLAUDE.md` (project root) via plain markdown links, not wikilinks, and both are cross-referenced from `docs/methodology-modes-guide.md` / skill files outside `wiki/`. Not orphaned in practice — just outside this scan's inbound-link graph. No action needed.

---

## Duplicate Filenames — investigated, not a bug

- `_index.md` exists in `wiki/concepts/`, `wiki/entities/`, `wiki/sources/` — one per top-level folder, by design (folder-scoped index pages). Wikilinks to these use folder-qualified paths (`[[concepts/_index]]` etc.), which Obsidian resolves correctly; my flat-basename check initially mis-flagged these as dead links until corrected for folder-qualified targets. No action needed.

---

## Empty Sections — mostly false positives, re-checked

Initial naive check (heading → immediately next heading, any level) flagged 67 "empty" sections. Nearly all were headers immediately followed by a *deeper* subheading with real content underneath (e.g. `## Recent Context` → `### Last Updated`) — normal document structure, not a bug. Re-running with a same-or-shallower-level definition drops this to **4 real hits**, all trivial:

- `wiki/concepts/_index.md`, `wiki/entities/_index.md`, `wiki/sources/_index.md` — each has a placeholder line ("Add new concepts here as they are extracted from sources.") formatted as a heading rather than body text. Cosmetic only.
- `wiki/meta/full-audit-and-system-setup-session.md` — a false positive from a fenced shell-command block containing lines starting with `#` (shell comments, e.g. `# Registered as marketplace`), which my heading-regex mistook for a markdown heading since it doesn't exclude code-fence content. Not a real issue.

No action needed.

---

## Frontmatter Gaps

0 found. Every content page carries `type`, `status`, `created`, `updated`, `tags`.

---

## Meta-noise, informational only (not part of today's FEARS content)

Several dead-link and orphan-adjacent hits point outside this session's scope — pre-existing plugin/meta-history content or cross-repo references, not FEARS wiki content:

- `wiki/meta/lint-report-2026-07-12.md` — the *previous* lint report. Its own dead-link/example placeholders (`notes/Foo`, `.raw/X.md`, `SKILL`, `dashboard.base`, etc.) are literal template text copied from this skill's own report-format example, not real content bugs. Safe to ignore permanently; consider excluding `wiki/meta/lint-report-*.md` files from future dead-link scans the way `wiki/meta/` is already excluded from orphan/tiling scans.
- `wiki/meta/2026-04-10-backlink-empire-session.md`, `wiki/meta/2026-04-14-claude-seo-v190-session.md` — reference pages (`Claude Obsidian`, `Rankenstein`, `Claude Canvas`, `Karpathy LLM Wiki Pattern`, `E-commerce SEO`, `AI Marketing Hub Cover Images Canvas`) belonging to the plugin/marketing side of this repo's history, unrelated to the FEARS domain. Not evaluated further this pass.
- `wiki/references/methodology-modes.md` → `methodology-modes-guide`, `wiki/references/transport-fallback.md` → `mcp-setup` — both intentionally point at files under `docs/` and `skills/`, outside `wiki/`'s own resolution scope. Expected, not broken.

---

## Fixes Applied (2026-07-14, same day)

User confirmed applying the safe, mechanical fixes. Done:

1. **Address-counter drift**: `.vault-meta/address-counter.txt` bumped `577` → `578`. Re-verified: 0 drift on re-scan.
2. **Categories A/B/C** (mistyped wikilinks): all fixed and re-verified as resolved —
   - Pantheon "The " prefix mismatches (7 occurrences: `wiki/index.md` ×5, `wiki/notes/Fire Pantheon.md`, `wiki/notes/Xethar.md`). The two prose occurrences were re-pointed with an alias (`[[Air Pantheon|The Air Pantheon]]`) rather than blindly stripped, to preserve the original phrasing.
   - `wiki/index.md`'s 5 pantheon-hub instances turned out to be a different bug than first diagnosed on closer read (category F, not A) — they were citing the underscore-variant `.raw/` source filenames alongside the real page links in the same sentence, not simple typos. Converted to backtick source citations (`` `The_Earth_Pantheon.md` `` etc.) instead of stripping "The", so the source/page distinction the original sentence was making is preserved rather than collapsed into a duplicate link.
   - `[[Faith of the Bound Pattern]]` → `[[The Faith of the Bound Pattern]]` (`wiki/notes/Glyph of Threads.md` frontmatter + body, `wiki/notes/Three Pillars of Magical Flow.md` frontmatter).
   - `[[Called Shots]]` → `[[Called Shot]]` (`wiki/notes/Converting Monsters to DCS.md`, 3 occurrences: frontmatter, body, See also).
   - `[[Wild Magic Zones]]` → `[[Wild Magic Zone|Wild Magic Zones]]` (`wiki/notes/Form Glyphs.md`).
   - `[[Eldritch Forces|Great Ones]]` → `[[Guide to the Eldritch Forces|Great Ones]]` (`wiki/notes/Styles of Magic.md`).
   - `[[The_Air_Pantheon]]` → `` `The_Air_Pantheon.md` `` (`wiki/hot.md`).
   - `[[Guide to Vel Zyren The Web Spinner]]` → `` `Guide to Vel Zyren The Web Spinner.md` `` (`wiki/index.md`, part of the same sentence as the pantheon-source fix above).
3. **Category H** (stray `?`): fixed in `wiki/hot.md`. **Not fixed in `wiki/log.md`** (2 occurrences, lines ~695/701) — that file's own header states "Append-only... Never edit past entries," so the historical entries were left as-is rather than overridden.

Re-scan confirms: address drift 0, all targeted link strings resolved except the two log.md instances (expected — intentionally skipped).

## Still open (needs a decision, not auto-fixed)

1. Categories D/E/F(remaining)/G — Fall of Ashkarra redirects, lineage disambiguators (`[[Dragonborn]]`, `[[Aasimar]]`), the remaining raw-source-as-wikilink citation (`FEARS_Corrected_Lineage_Analysis`, 3 occurrences in `wiki/notes/FEARS Lineages.md`, `Hobgoblin (Lineage).md`, `Human (Lineage).md`), and the table-pipe-escaping rework in `The Lie of Godhood.md` — each needs a small judgment call rather than a blind find-replace.
2. Optionally write [[Kerythra]] as a new page (8 mentions, "The Wild Continent," the highest-value gap found) in a future ingest pass rather than as a rushed stub here.
3. Minor process note: future lint passes should exclude `wiki/meta/lint-report-*.md` files from the dead-link scan — this report's own worked examples (quoting broken link strings as text) register as new "dead links" against itself otherwise.

## See also

- [[log]]
- [[hot]]
- [[index]]
- [[lint-report-2026-07-12]]
