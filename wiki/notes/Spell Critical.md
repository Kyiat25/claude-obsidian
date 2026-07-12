---
type: entity
title: "Spell Critical"
address: c-000097
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - magic-system
status: developing
mocs:
  - "[[FEARS MOC]]"
entity_type: source-document
related:
  - "[[Unstable Magic Zones]]"
  - "[[Sanity]]"
  - "[[Warlock]]"
  - "[[Witch]]"
  - "[[Inventor]]"
sources:
  - ".raw/Spell Critical.md"
confidence: high
---

# Spell Critical

`.raw/Spell Critical.md`'s own frontmatter reads `status: excluded`, and this page was originally filed as a design-history-only, unconfirmed preview on that basis (following the same treatment given to [[The Dynamic Combat System (Excluded Draft)]]). **Corrected by explicit user instruction**: this content is confirmed canon, not excluded — the frontmatter marker was not a reliable signal here. Note: [[The Dynamic Combat System (Excluded Draft)]] itself was *not* reclassified by this correction and remains treated as excluded; this is a source-specific correction, not a blanket policy change.

Titled "Disruptions of the Structured Weave." Defines the full **Critical Spell Hit** mechanic, superseding [[Unstable Magic Zones]] (from [[Welcome to FEARS]], the very first FEARS source)'s prior "no table or DC governs the outcome" statement with a real resolution table.

## Trigger conditions

A Spell Critical fires on a natural 20 on a spell attack roll, a target's natural 1 on a saving throw against the caster's spell, or rare forced triggers (leyline pulses, corrupted glyph structures).

## Resolution order (six steps)

1. **Critical Hit Damage Tables** — roll per damage type, separately for multi-type spells.
2. **Spell Upcast** — the spell resolves as if cast one level higher (cantrips as if the caster were one level higher).
3. **Fear Effect** — enemies within 60 ft make a Sanity or Wisdom save (their choice) vs. the caster's spell save DC or become Frightened 3 rounds; if already Frightened, they additionally roll a **Fracture Save** (DC 10 + caster's PB) or suffer a **Fracture Effect** "from the Sanity system."
4. **Focus Check** — a d6 gates whether anything happens at all (even = nothing, odd = the table below applies); if triggered, a Focus Check (`d20 + Focus mod`) vs. the caster's own spell save DC determines the outcome:

| Focus Check result | Effect |
|---|---|
| Natural 20 | Enhanced Arcane Rift forms — amplifies all spells of that school, surges unpredictably |
| Success | Standard Arcane Rift appears — empowers similar magic, destabilizes oppositional schools |
| Failure | A Wild Magic Zone forms — roll on a school-linked Wild Magic Surge table |
| Natural 1 | A Dead Magic Zone forms — concentration spells fail, spellcasting impossible until the Weave stabilizes |

5. **Wild Magic Surge Roll** — if a Wild Magic Zone formed, roll immediately on its school table; Echo Glyphs/class features used inside may cause glyph flares or "Echo Fragmentation," requiring further rolls.
6. **Echo Glyph Surge** — if the spell is Echo-Glyph-eligible, a Glyphcraft check (`d20 + spellcasting ability + proficiency`, DC = `10 + spell level`) lets the caster learn, swap, or imprint an Echo Glyph. [[Warlock|Warlocks]], [[Witch|Witches]], and some [[Inventor|Inventors]] reportedly have modified learning rules — not detailed in this source, so not added to those class pages.

## Consequences

- **Instability**: Arcane Rifts can permanently alter an area; leylines may record events and destabilize future spellcasting there. Wild Magic Zones can spread if uncontained; creatures caught inside risk becoming "Glyphburned."
- **Concentration Stress**: maintaining concentration through a Spell Critical means rolling Concentration checks at disadvantage; failure reverts the spell to its normal (non-upcast) level. Inside a Dead Magic Zone, concentration is lost immediately for all active spells.

## Resolves: Unstable Magic Zones' missing resolution table

[[Unstable Magic Zones]] previously stated no table or DC existed for which of Arcane Rift / Wild Magic Zone / Dead Magic Zone results from a Critical Spell Hit — pure GM adjudication. This source supplies that table (the Focus Check above), plus a fourth "Enhanced Arcane Rift" outcome not previously documented. [[Unstable Magic Zones]] updated accordingly.

## Fracture Save / Fracture Effect (partially confirmed)

Confirms a **Fracture Save** (DC 10 + PB) exists and is tied to the Sanity system. The full **Fracture Effect** itself — what actually happens on a failed save — is not detailed by this source ("from the Sanity system" is a pointer, not a definition). `Fracture Whispers.md`, still uningested, is expected to supply the actual effect table. [[Sanity]] updated to reflect the Save formula as confirmed while flagging the Effect as still pending.

## New terminology

Echo Glyph, Glyphcraft, Echo Journal, Echo Fragmentation, Spirit Thread resonance, leyline, Glyphburned, Circle of Echoes Druids, Moonscribes — confirmed to exist by this source but not detailed enough for dedicated pages yet. Not filed as separate stub pages per the no-thin-filler-pages convention; listed here for searchability until a source with enough detail justifies dedicated pages.

## See also

- [[Unstable Magic Zones]]
- [[Sanity]]
- [[Warlock]]
- [[Witch]]
- [[Inventor]]
- [[FEARS MOC]]
