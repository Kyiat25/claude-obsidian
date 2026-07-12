---
type: entity
title: "Fracture Whispers"
address: c-000101
created: "2026-07-12"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - mental-triad
status: developing
mocs:
  - "[[FEARS MOC]]"
entity_type: source-document
related:
  - "[[Fracture Save]]"
  - "[[Whisper Points]]"
  - "[[Whisper Engine]]"
  - "[[Sanity]]"
  - "[[Focus]]"
  - "[[Spell Critical]]"
  - "[[Sanity & Focus in Combat]]"
sources:
  - ".raw/Fracture Whispers.md"
confidence: high
---

# Fracture Whispers

`.raw/Fracture Whispers.md`'s own frontmatter reads `status: excluded` with a bare `template` tag — the fourth and final source in this cluster with that exact shape, after [[Spell Critical]], [[Eldritch Moons in Combat]], and [[Sanity & Focus in Combat]], all three of which the user corrected to confirmed canon. Treated as canon here too, consistent with that pattern (not re-asked this time given 3/3 precedent on an identical frontmatter shape). [[The Dynamic Combat System (Excluded Draft)]] remains the sole exception, unaffected by any of these corrections.

This is the source every prior Fracture/Whisper thread in this cluster has been waiting on. It resolves most of what was still open on [[Fracture Save]] and closes the long-running [[Whisper Engine]] question.

## What is a Fracture?

A mental or spiritual break when Sanity fails under stress — the cost of witnessing horrors beyond mortal comprehension (Eldritch forces, death trauma, memory-shattering events). Leads to temporary or permanent psychological effects, the acquisition of Whisper Points, and unpredictable behaviors (hallucinations, compulsions, memory loss).

## When Fractures occur

| Trigger | Effect |
|---|---|
| Failing a Fracture Save | Roll on the Fracture Table |
| Reaching max Whisper Points | Automatically Fracture |
| Consecutive failed Sanity Saves | Fracture Save at Disadvantage |
| Exposure to Eldritch Truths | GM may call for a Fracture even at full Sanity |

## Whisper Points, reframed

Described here as "a mechanical measure of how close a character is to mental instability or revelation" — see [[Whisper Points]] for the reasoning on why this is treated as the same resource as the narrative currency, not a separate mechanic sharing a name.

| Source | Gain a Whisper Point? |
|---|---|
| Failing a Sanity Save | Yes |
| Viewing an Eldritch Moon | Yes |
| Using Eldritch Magic or Glyphs | Maybe (GM discretion) |
| Recalling a traumatic memory | Yes |

**Whisper Point Cap = `1 + Sanity Modifier` (minimum 1)**. Reaching the cap immediately triggers a Fracture Save.

## Fracture Save (confirms and extends Fracture Save)

`DC = 13 + Whisper Points` at the time of the roll — matches [[Sanity & Focus in Combat]]'s formula exactly. Roll: `1d20 + Constitution Modifier + Sanity Modifier` (the first full roll formula given for this save). Success: regain 1 Sanity and purge a Whisper Point. Failure: gain a Fracture Condition, rolled on the table below. Full writeup and the still-unresolved conflict with [[Spell Critical]]'s `10 + PB` formula on [[Fracture Save]].

## Fracture Table (d8)

| d8 | Fracture Effect |
|---|---|
| 1 | Catatonia — cannot act until struck or healed |
| 2 | Hallucination — sees one ally as an enemy |
| 3 | Compulsion — must repeat last action until restrained or forced out |
| 4 | Panic — drops items and flees next round |
| 5 | Fugue — loses memory of the last 10 minutes; −2 to INT/WIS checks |
| 6 | Weep Unseen — loses all Focus; can't gain Focus for 1 minute |
| 7 | Awakened Insight — gains a random truth about an enemy or Glyph, but takes 1d6 psychic damage |
| 8 | Eldritch Hunger — must move toward an unnatural source each turn until resisted |

GM may modify or assign custom effects. This is the first full Fracture Effect table in any confirmed source — closes the gap flagged since [[Spell Critical]]'s ingest.

## Optional toggles

| Toggle | Description |
|---|---|
| Residual Fracture | Fracture effects linger 1d4 hours even after Sanity stabilizes |
| Compounding Whispers | Each Whisper Point over the cap gives disadvantage on Fracture Saves |
| Silent Madness | The player doesn't know the exact Fracture effect — must roleplay symptomatically |
| Glyph Feedback | Using secondary Glyphs under high stress may add Whisper Points |

## Integration hooks

Sanity/Fear (core driver — Fractures are consequences of Sanity failure), [[Focus]] (Fractures drain or block Focus — see the Weep Unseen effect above), [[Whisper Engine]] ("tied directly — Fracture is the primary danger of building Whisper"), Magic & Glyphs (Eldritch or Unstable Glyphs may trigger Whisper gain or Fracture — echoes [[Spell Critical]]'s Echo Glyph content).

## See also

- [[Fracture Save]]
- [[Whisper Points]]
- [[Whisper Engine]]
- [[Sanity]]
- [[Focus]]
- [[Spell Critical]]
- [[Sanity & Focus in Combat]]
- [[FEARS MOC]]
