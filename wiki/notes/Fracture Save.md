---
type: concept
title: "Fracture Save"
address: c-000100
created: "2026-07-12"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - mental-triad
status: developing
mocs:
  - "[[FEARS MOC]]"
complexity: intermediate
domain: fears
related:
  - "[[Sanity]]"
  - "[[Focus]]"
  - "[[Spell Critical]]"
  - "[[Sanity & Focus in Combat]]"
  - "[[Eldritch Moons in Combat]]"
  - "[[Fracture Whispers]]"
  - "[[Whisper Points]]"
sources:
  - "[[Spell Critical]]"
  - "[[Sanity & Focus in Combat]]"
  - "[[Eldritch Moons in Combat]]"
  - "[[Fracture Whispers]]"
confidence: high
---

# Fracture Save

"Fracture Save" names **two distinct mechanics that share a label**, not one formula stated two conflicting ways. **Resolved by user ruling (2026-07-14)**: one variant is witnessed mid-combat off a [[Spell Critical]]'s Fear Effect; the other is driven by a character's own accumulated [[Whisper Points]]. Previously logged as an open DC-formula contradiction — see the resolution note under each variant below.

## Whisper Fracture Save (general-purpose)

The save a character makes against their own accumulating instability. Named independently by three confirmed-canon sources — [[Sanity & Focus in Combat]], [[Eldritch Moons in Combat]], and [[Fracture Whispers]] (the source that finally defines the mechanic in full).

**Triggers**: failing this save itself rolls on the Fracture Table below; reaching the Whisper Point cap (`1 + Sanity Modifier`, minimum 1) forces an automatic Whisper Fracture Save; consecutive failed Sanity Saves impose it at Disadvantage; the GM may also call for one at full Sanity after exposure to Eldritch Truths.

**DC**: `13 + Whisper Points` — the character's own current Whisper Point total at the time of the roll, confirmed identically by [[Sanity & Focus in Combat]] and [[Fracture Whispers]].

**Roll (confirmed, from Fracture Whispers)**: `1d20 + Constitution Modifier + Sanity Modifier`. **Success**: regain 1 Sanity and purge a Whisper Point. **Failure**: gain a Fracture Condition — roll on the Fracture Table:

| d8 | Fracture Effect |
|---|---|
| 1 | Catatonia — cannot act until struck or healed |
| 2 | Hallucination — sees one ally as an enemy |
| 3 | Compulsion — must repeat last action until restrained or forced out |
| 4 | Panic — drops items and flees next round |
| 5 | Fugue — loses memory of the last 10 minutes; −2 to INT/WIS checks |
| 6 | Weep Unseen — loses all [[Focus]]; can't gain Focus for 1 minute |
| 7 | Awakened Insight — gains a random truth about an enemy or Glyph, but takes 1d6 psychic damage |
| 8 | Eldritch Hunger — must move toward an unnatural source each turn until resisted |

GM may modify or assign custom effects. This closes the "no full Fracture Effect table exists" gap flagged since [[Spell Critical]]'s ingest.

## Spell Critical Fracture Save (narrow variant)

A separate, narrower save triggered mid-combat by [[Spell Critical]]'s Fear Effect step: when a creature already Frightened by a caster's Spell Critical fails its follow-up Sanity or Wisdom save, it rolls this save instead of simply remaining Frightened.

**DC**: `10 + the casting creature's Proficiency Bonus` — scaled to the caster who triggered the Fear Effect, not the target's own Whisper Points, since it's an externally-inflicted shock rather than self-accumulated instability.

**Failure**: suffers a Fracture Effect ("from the Sanity system" per Spell Critical's own text, which doesn't detail it) — ruled to use the same Fracture Table above, since [[Fracture Whispers]] is the only source to supply a full table.

> [!resolved] Previously flagged as a DC-formula contradiction
> [[Spell Critical]] states this variant's DC as `10 + PB`; [[Sanity & Focus in Combat]] and [[Fracture Whispers]] independently state the Whisper Fracture Save's DC as `13 + Whisper Points`. Both are confirmed canon, and for a time this read as one formula disputed two ways.
> **Resolved by user ruling**: they're two different mechanics, not competing versions of one save — one witnessed off a Spell Critical's Fear Effect (scaled to the caster's PB), the other driven by a character's own Whisper Point accumulation (scaled to their own total). No further reconciliation needed.

## Whisper Point cap (confirmed, from Fracture Whispers)

`1 + Sanity Modifier` (minimum 1). Gain triggers: failing a Sanity Save, viewing an Eldritch Moon, using Eldritch Magic/Glyphs (GM discretion), recalling a traumatic memory. Reaching the cap is itself a Fracture Save trigger — see [[Whisper Points]] for the reasoning on why this is treated as the same resource as the narrative currency, not a coincidentally-named separate one.

## See also

- [[Sanity]]
- [[Focus]]
- [[Spell Critical]]
- [[Sanity & Focus in Combat]]
- [[Eldritch Moons in Combat]]
- [[Fracture Whispers]]
- [[Whisper Points]]
- [[FEARS MOC]]
