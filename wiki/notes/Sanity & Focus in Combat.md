---
type: entity
title: "Sanity & Focus in Combat"
address: c-000099
created: "2026-07-12"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - mental-triad
  - combat
status: developing
mocs:
  - "[[FEARS MOC]]"
entity_type: source-document
related:
  - "[[Sanity]]"
  - "[[Focus]]"
  - "[[Fracture Save]]"
  - "[[Momentum]]"
  - "[[Whisper Points]]"
  - "[[Whisper Engine]]"
  - "[[Tactical Reactions]]"
sources:
  - ".raw/Sanity & Focus in Combat.md"
confidence: high
---

# Sanity & Focus in Combat

`.raw/Sanity & Focus in Combat.md`'s own frontmatter reads `status: excluded` with a bare `template` tag — the same weak-provenance shape as [[Spell Critical]] and [[Eldritch Moons in Combat]]. Per the same explicit user correction extended to those two sources, this is treated as confirmed canon. [[The Dynamic Combat System (Excluded Draft)]] remains the one source-specific exception that was **not** reclassified.

Supplies the first combat-specific roll formulas for both [[Sanity]] and [[Focus]], which until now were defined only in terms of thresholds and narrative consequences.

## Sanity Save formula (confirmed)

`1d20 + Sanity Modifier + Proficiency` — the first roll formula given for a Sanity Save anywhere in this wiki. [[Sanity]] updated accordingly.

### Sanity trigger table

| Trigger | Save DC | On failure |
|---|---|---|
| Witnessing eldritch transformation | 10 + CR | Roll on Short-Term Madness table |
| Seeing an ally vaporized | 15 | Stunned 1 round |
| Memory Glyph backlash | 10 + spell level | Lose 1 Focus, gain 1 Whisper Point |
| Encountering a Hollow-Eyed Entity | 8-18 (varies) | Roll a Fracture Save + gain a temporary condition |

"Memory Glyph" and "Hollow-Eyed Entity" are both first sightings in this wiki — no other source names either. Not filed as separate stub pages per the no-thin-filler-pages convention.

## Focus Pool (confirmed)

Focus is FEARS's primary reaction and tactical currency — spent to power Reactions, class abilities, or resist certain effects; regained through resting, abilities, or regaining control of a fight. **Max Focus = 3**, unless modified by class/feat/trait — the first concrete cap given for this resource.

### Gaining Focus

| Condition | Focus gain |
|---|---|
| Dropping an enemy | +1 |
| Critical Hit | +1 |
| Regaining a Momentum tier | +1 |
| Passing a Fracture Save | +1 |
| Sanity Stabilization | +1 |

## Sanity & Focus interaction

Losing Sanity can cause Focus loss, especially during eldritch or psychic events. Certain abilities may spend Focus to resist a Fracture. Low Sanity lowers max Focus during long rests. Worked example from the source: a Cleric fails a Sanity Save against a Howling Moon cultist, loses 1 Focus, rolls a [[Fracture Save]], passes, and regains the 1 Focus for resisting.

## Optional toggles

| Toggle | Description |
|---|---|
| Focus Fragility | Taking damage may cause Focus loss (DC 12 CON save to resist) |
| Momentum Synergy | For every 3 [[Momentum]], increase Focus max by +1 |
| Eldritch Sway | Sanity failures slowly convert into usable but corrupting Focus |
| Mental Reserves | Focus = Sanity modifier + 2, instead of the static cap |

## Integration hooks

Combat Flow (Sanity saves and Focus use interrupt turns/reactions), Reaction System ([[Focus]] is the main currency to trigger [[Tactical Reactions|Reactions]]), Fracture System (builds over time with Sanity failures), [[Whisper Engine]] (Whisper Points gained when Sanity breaks under eldritch stress — the Memory Glyph backlash row above is a concrete instance of this).

## Fracture Save formula — resolved as a distinct variant, not a conflict

This source states the (Whisper Point-driven) [[Fracture Save]] DC as `13 + number of Whisper Points`. [[Spell Critical]] separately gives `10 + PB` for its own narrower, Fear-Effect-triggered variant. Both are confirmed canon; previously flagged as a genuine contradiction. **Resolved by user ruling**: they're two different mechanics sharing a name — one witnessed via a Spell Critical, one driven by a character's own Whisper Point accumulation — not one formula stated two ways. Full breakdown on [[Fracture Save]].

## See also

- [[Sanity]]
- [[Focus]]
- [[Fracture Save]]
- [[Momentum]]
- [[Whisper Points]]
- [[Whisper Engine]]
- [[Tactical Reactions]]
- [[FEARS MOC]]
