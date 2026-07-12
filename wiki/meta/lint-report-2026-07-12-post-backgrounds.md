---
type: meta
title: "Lint Report 2026-07-12 (post FEARS Advanced Backgrounds)"
created: 2026-07-12
updated: 2026-07-12
tags: [meta, lint]
status: developing
---

# Lint Report: 2026-07-12 (post FEARS Advanced Backgrounds)

Follow-up lint pass after ingesting all 3 batches of the FEARS Advanced Backgrounds system (62 new pages: 61 backgrounds + 1 hub). Compares against the previous [[lint-report-2026-07-12|2026-07-12 lint report]], which covered the 24-class FEARS pass and its lint cleanup.

## Summary

- Pages scanned: 214 (up from 151 pre-backgrounds)
- New issues introduced by this ingest: **0 genuine bugs**
- Address validation: clean
- Frontmatter: clean
- Empty sections: 0 across all of `wiki/notes/`, including all 62 new pages
- Semantic tiling: still skipped (platform incompatibility, unchanged from last report)

This is a clean result — the 61-background ingest didn't introduce any of the systemic issues the first lint pass found (no `.raw/`-bracket wikilinks this time, since the fix for that pattern was already established before this ingest began).

## Address Validation (DragonScale Mechanism 2)

- 164 addressed pages, all matching `^c-\d{6}$` format. **Zero format errors, zero collisions.**
- Highest address observed: `c-000165`. Counter (`166`) is one past it — consistent, no drift, despite 62 new pages allocated across 3 separate ingests.

## Frontmatter Gaps

**Zero gaps** among all 214 scanned pages (the frontmatter script's required-field check: `type`, `status`, `created`, `updated`, `tags`). The only exception is the same one already known and accepted: `wiki/meta/tiling-report-2026-04-24.md` has no frontmatter at all, because it's an auto-generated report, not hand-authored content — unchanged from the previous lint report's conclusion.

## Dead Links

### New: 3 intentional forward-references (not bugs)

`[[Sailor]]`, `[[Urchin]]`, `[[Outlander]]` (5 references each, in `hot.md`, `log.md`, `FEARS MOC.md`, `FEARS Advanced Backgrounds.md`) — these are the three PHB backgrounds explicitly flagged as never developed across all 3 batches. The links are deliberate forward-references documenting a known gap, consistent with this vault's existing convention of linking to not-yet-created pages (e.g., `FEARS Class Roster.md`'s pre-existing links to retired classes). Not something to fix — they're supposed to stay "broken" until/unless someone writes those three backgrounds.

### Everything else: already known from the previous report

Every other dead link found (`.raw/Cleric.md`, `.raw/X.md`, `AI Marketing Hub Cover Images Canvas`, `Claude Canvas`, `Claude Obsidian`, `E-commerce SEO`, `Foo`, `How does the LLM Wiki pattern work?`, `Karpathy LLM Wiki Pattern`, `Rankenstein`, `SKILL`, `Short Rest`, `Spell Critical (Excluded Draft)`, `Wiki Map`, `claude-obsidian-presentation`, `dashboard.base`, `fold-template`, `mcp-setup`, `methodology-modes-guide`, `notes/Foo`, `wiki-cli`, `wiki-fold`, `wiki-mode`, `wikilinks`) is either:
- a false positive from the lint script's `wiki/`-only scope or its inability to see inside code spans (`Wiki Map`/`dashboard.base` are `.canvas`/`.base` files; `Foo`, `notes/Foo`, `Three laws of motion` (new sighting, `wiki/concepts/Persistent Wiki Artifact.md`) are syntax-illustration examples inside backticks, not live links; `mcp-setup`/`methodology-modes-guide` resolve fine outside `wiki/`), or
- already documented as a known, low-priority legacy issue in the previous report (old April session-log dead links, the `.raw/` and `?`-filename patterns still shown only as historical/documentation examples inside `lint-report-2026-07-12.md` itself and append-only `log.md`/`hot.md` entries).

No action needed beyond what the previous report already recommended.

## Orphan Pages

Same 6 as the previous report, unchanged — no new orphans among the 62 new pages (all of them link back to `FEARS Advanced Backgrounds.md` and `FEARS MOC.md`, and are linked from at least the hub's tables): `2026-04-10-backlink-empire-session.md`, `retrieval-benchmark-v1.7.md`, `tiling-report-2026-04-24.md`, `methodology-modes.md`, `transport-fallback.md`, plus this report and the previous one (both naturally orphaned meta artifacts).

## Known, already-flagged content overlap (not a new finding)

[[Minstrel]] (Batch 3) and [[Entertainer]] (Batch 1) are both performance/fame progression tracks with no source text distinguishing them — already flagged on `Minstrel.md` itself at ingest time, not a new lint finding, just noting it's still unresolved.

## Conclusion

Nothing to auto-fix. The 61-background ingest is clean — the discipline established during the class-pass lint cleanup (backtick-wrapped `sources:` paths instead of bracketed wikilinks, complete frontmatter on every new page, address allocation via the counter) held up perfectly across 3 separate large batches. No action needed unless you want to develop Sailor/Urchin/Outlander or resolve the Minstrel/Entertainer overlap.
