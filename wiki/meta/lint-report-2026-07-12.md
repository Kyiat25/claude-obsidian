---
type: meta
title: "Lint Report 2026-07-12"
created: 2026-07-12
updated: 2026-07-12
tags: [meta, lint]
status: developing
---

# Lint Report: 2026-07-12

Run after the full 24-class FEARS per-class deep-dive pass (Barbarian → Wizard), the largest single ingest run this vault has seen. 151 wiki pages scanned.

## Summary

- Pages scanned: 151 (wiki/), cross-referenced against the full repo tree for link resolution
- Issues found: ~30 distinct findings across 6 categories
- Auto-fixed: 0 (all findings below, none applied yet — awaiting your go-ahead)
- Needs review: all of them; see priority notes per section

**Headline finding**: a systemic, vault-wide dead-link pattern — every FEARS per-class page's `sources:` frontmatter cites its raw source as a wikilink (e.g. `"[[.raw/Cleric.md]]"`), but `.raw/` files are outside `wiki/` and were never meant to resolve as wiki pages. This predates this session (established during the 2026-07-11 FEARS ingests) and was continued through the 24-class pass just completed. ~100 instances. See **Dead Links** below for the fix recommendation.

## Dead Links

### Systemic: `.raw/*.md` wikilinks in `sources:` frontmatter (HIGH priority, ~100 instances)

Every page with a `sources:` frontmatter field that cites a raw ingest file uses wikilink brackets around a path outside `wiki/`:

```yaml
sources:
  - "[[.raw/Cleric.md]]"
```

This never resolves (`.raw/` isn't part of the wiki tree, and creating stub pages there would violate `.raw/`'s immutability convention). Affects roughly every FEARS source and per-class page — Barbarian through Wizard, plus the earlier non-per-class ingests (Welcome to FEARS, A World that Watches, DCS, Combat Flow, Called Shots, Momentum, Evasion, Injury System, Weapon Mastery System, Initiative, Reaction-based Opportunities, Spell Critical, Eldritch Moons in Combat, Sanity & Focus in Combat, Fracture Whispers, Classes_Summary, Class_breakdown, Narrative Identity, Bloodied Breaking Points Rally).

**Recommended fix**: replace `"[[.raw/X.md]]"` with a plain string `".raw/X.md"` (no brackets) in every `sources:` list — matching the convention already used correctly in prose elsewhere in this vault (e.g. log.md's `` `.raw/Cleric.md` `` in backticks). This is a mechanical, low-risk find-and-replace across frontmatter blocks, but touches ~40+ files, so flagging for your go-ahead rather than auto-fixing.

### Real dead links, non-systemic (MEDIUM priority)

- `[[How does the LLM Wiki pattern work?]]` (5 refs: Persistent Wiki Artifact, Query-Time Retrieval, Source-First Synthesis, hot.md, log.md) — actual file is `wiki/questions/How does the LLM Wiki pattern work.md` (no trailing `?`; Windows filenames can't contain `?`). Fix: either drop the `?` from all 5 links, or add `aliases: ["How does the LLM Wiki pattern work?"]` to the page's frontmatter (Obsidian aliases still don't help plain-text wikilink resolution per this vault's own filename-stem-only resolution rule documented in DragonScale Memory.md, so the safer fix is updating the 5 links to match the real filename).
- `[[wiki-cli]]`, `[[wiki-fold]]`, `[[wiki-mode]]` (in `wiki/references/transport-fallback.md` and `wiki/references/methodology-modes.md`) — these skills live at `skills/wiki-cli/SKILL.md`, `skills/wiki-fold/SKILL.md`, `skills/wiki-mode/SKILL.md`; a bare `[[wiki-cli]]` link needs a file literally named `wiki-cli.md`, which doesn't exist. Fix: point the link at the actual filename, e.g. `[[SKILL|wiki-cli]]` won't work either since multiple `SKILL.md` files exist (ambiguous stem) — recommend converting these three to plain-text paths instead of wikilinks, same as the `.raw/` fix above.
- `[[Claude Canvas]]`, `[[Claude Obsidian]]`, `[[Karpathy LLM Wiki Pattern]]`, `[[Rankenstein]]` (all in `wiki/meta/2026-04-10-backlink-empire-session.md`) — no matching page anywhere in the repo. Pre-dates this session; likely informal shorthand in an old session log rather than intended links. Low priority (orphaned meta/session file, see Orphans below).
- `[[E-commerce SEO]]` (2 refs: entities/Claude SEO.md, meta/2026-04-14-claude-seo-v190-session.md) — no matching page. Possibly a planned-but-never-created concept page.
- `[[AI Marketing Hub Cover Images Canvas]]` (wiki/overview.md) — no matching file of any type.

### False positives (no action needed)

- `[[Wiki Map]]` and `[[dashboard.base]]` resolve fine — they're `.canvas`/`.base` files, not `.md`, which my scan (built for markdown pages) initially missed. Confirmed both exist.
- `[[Foo]]` / `[[notes/Foo]]` in DragonScale Memory.md and `[[Short Rest]]` in log.md's own historical entry — these appear inside inline code spans (`` `[[Foo]]` ``) as *documentation of the linking syntax itself*, not live links. Obsidian's own quirk (backticks don't escape wikilinks) means they may still render as broken links visually, but they're intentional illustrative examples, not content errors.
- `[[Spell Critical (Excluded Draft)]]` (hot.md, log.md) — the page was later renamed to `Spell Critical.md`; these references live inside **historical, append-only log entries** describing the rename itself. Per this vault's own append-only convention (never edit past log/hot entries), these are expected to stay "broken" as a historical record, not bugs to fix.

## Orphan Pages

5 pages with no inbound resolved link:

- `wiki/meta/2026-04-10-backlink-empire-session.md` — old session note, likely intentionally standalone (session logs aren't usually cross-linked from content pages).
- `wiki/meta/retrieval-benchmark-v1.7.md` — benchmark artifact from the v1.7 audit, same pattern.
- `wiki/meta/tiling-report-2026-04-24.md` — auto-generated tiling report; also has no frontmatter (see below).
- `wiki/references/methodology-modes.md` — referenced by CLAUDE.md (outside `wiki/`, so not counted by this scan) but not from any wiki page.
- `wiki/references/transport-fallback.md` — same pattern as above.

None of these look accidental — they're all meta/reference material that's reached via CLAUDE.md or skill files, not the content graph. Recommend: no action, or optionally add a one-line cross-link from `wiki/overview.md` if you want them discoverable from inside the vault too.

## Frontmatter Gaps

7 pages missing one or more of `type/status/created/updated/tags`:

- **`wiki/mocs/FEARS MOC.md`** — missing `status` and `updated`. Worth fixing given this page has been edited in nearly every FEARS ingest this session and is the primary navigation hub for the whole domain.
- `wiki/references/methodology-modes.md` — missing `created`, `updated`.
- `wiki/references/transport-fallback.md` — missing `created`, `tags`.
- `wiki/meta/retrieval-benchmark-v1.7.md` — missing `created`, `tags`.
- `wiki/meta/2026-04-15-release-report-session.md`, `wiki/meta/2026-04-15-slides-and-release-session.md`, `wiki/meta/boundary-frontier-2026-04-24.md` — each missing `created`.
- `wiki/meta/tiling-report-2026-04-24.md` — **no frontmatter block at all** (auto-generated report; may be intentional for this file type).

## Address Validation (DragonScale Mechanism 2)

DragonScale addressing is active (`allocate-address.sh` present, `.vault-meta/address-counter.txt` exists) — full validation ran.

- Counter state: `104` (read directly from `.vault-meta/address-counter.txt`; `allocate-address.sh --peek` itself can't run in this environment — it requires `flock`, unavailable on Windows Git Bash, a known platform gap already documented in `hot.md`).
- Highest `c-` address observed in frontmatter: `c-000103`. Consistent with counter state (no drift).
- Addressed pages: 102, all matching the `^c-\d{6}$` format. **Zero format errors, zero collisions.**
- `address_map` in `.raw/.manifest.json`: 102 entries, all 102 resolve to an existing file with a matching frontmatter `address:` value. **Zero mismatches.**
- Post-rollout pages missing an address: none found in this pass (would need a dedicated per-page rollout-date check to be exhaustive, but no gaps surfaced during the frontmatter scan).

This is the cleanest section of the report — the DragonScale addressing system held up perfectly across 24 rapid-fire class ingests with zero collisions or drift.

## Semantic Tiling (DragonScale Mechanism 3)

Skipped: `scripts/tiling-check.py` requires the `fcntl` module, which doesn't exist on Windows. Same platform gap as the `flock`-based address script above — already known and documented in `hot.md`, not a new finding.

## Empty Sections

Checked every heading in `wiki/` for same-or-higher-level headings immediately following with no content between them. Only 4 hits, 3 of which are intentional scaffolding placeholders (`_index.md` files' "Add new X here" stub text) and 1 in an unrelated old session file (`full-audit-and-system-setup-session.md`, a stray `#` used as a log-line prefix rather than a real heading). **No real empty sections found** — the "full ability detail, not condensed bullets" standard held up structurally across all 24 class pages.

## Stale Claims / Cross-Reference Gaps

Not exhaustively checked this pass — with 24 classes' worth of cross-links added in one session, a full stale-claims sweep would need to re-read every hub page (Momentum, Damage Reduction, Called Shot, Injury System, Evasion, Weapon Mastery, Last Stand, Class Reactions) end-to-end rather than spot-checking. Worth a dedicated follow-up lint focused just on those 8 hub pages, since they're now each 200-300+ lines of accumulated cross-class findings and are the highest-risk pages for internal contradiction as they keep growing.

## Naming Conventions

No violations found — all new FEARS pages follow Title Case filenames, `wiki/notes/` flat structure per LYT mode, and wikilinks matching filenames exactly.

## Recommended Next Steps (priority order)

1. **Fix the `.raw/` wikilink pattern** (HIGH, ~100 instances, ~40 files) — convert `"[[.raw/X.md]]"` to `".raw/X.md"` in `sources:` frontmatter blocks.
2. **Add `status`/`updated` to FEARS MOC** (MEDIUM, 1 file) — it's the domain's primary hub and currently fails its own frontmatter completeness bar.
3. **Fix the 5 `How does the LLM Wiki pattern work?` links** (LOW, 5 refs, 5 files) — cosmetic but a genuine dead link.
4. **Decide on `wiki-cli`/`wiki-fold`/`wiki-mode` links** (LOW, 2 files) — convert to plain-text paths.
5. Everything else (orphans, old-session dead links, missing frontmatter on pre-2026-07 meta files) is low-priority legacy debt, not something this session introduced — fine to leave as-is or batch into a future cleanup pass.

## Resolution (2026-07-12, later same day)

All content-level findings (Damage Reduction, Weapon Mastery, Evasion, Last Stand, Class Reactions contradictions) were resolved through a separate rulings pass — see `wiki/log.md` for the full sequence of ruling entries.

The technical lint items above were then cleaned up:
- **`.raw/` wikilink pattern** (~100 instances, 54 files): fixed — stripped to plain-text paths (`".raw/X.md"`, no brackets).
- **`How does the LLM Wiki pattern work?` mismatch**: fixed on the 3 live frontmatter references (concepts pages); left untouched in `log.md`/`hot.md` (append-only historical entries) and in `boundary-frontier-2026-04-24.md` (plain-text table cell, not a live link — no fix needed).
- **`wiki-cli`/`wiki-mode` directory-vs-file mismatches**: fixed in `transport-fallback.md` and `methodology-modes.md` (converted to plain-text paths); left untouched in the old `wiki/folds/` rollup file (frozen historical artifact, same treatment as fold content generally).
- **FEARS MOC frontmatter gap**: fixed (`status`, `updated` added).
- **Other frontmatter gaps**: fixed on `retrieval-benchmark-v1.7.md`, `2026-04-15-release-report-session.md`, `2026-04-15-slides-and-release-session.md`, `boundary-frontier-2026-04-24.md`, `transport-fallback.md`, `methodology-modes.md` (all missing `created`/`tags` added). `tiling-report-2026-04-24.md` left without frontmatter intentionally — it's an auto-generated report, not hand-authored content.
- **Orphan pages, old non-FEARS dead links**: left as-is per the original report's recommendation — none were accidental, and fixing them wasn't worth the churn.

Everything flagged as "safe to auto-fix" in the original report is now fixed. No further action pending from this lint pass.
