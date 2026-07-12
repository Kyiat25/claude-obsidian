---
type: concept
title: "Tactical Reactions"
address: c-000076
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
status: developing
mocs:
  - "[[FEARS MOC]]"
complexity: intermediate
domain: fears
related:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Evasion]]"
  - "[[FEARS Combat System]]"
  - "[[Momentum]]"
  - "[[Combat Flow]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Combat Flow]]"
  - ".raw/Reaction-based_opportunities.md"
---

# Tactical Reactions

> Editorial note: no separate source page was created for this ingest — `.raw/Reaction-based_opportunities.md` deepens exactly this page's existing content (same in-place-upgrade pattern as [[Combat Flow]], [[Called Shot]], [[Damage Reduction]], [[Momentum]], [[Evasion]], and [[Injury System]]'s ingests), so it was merged in rather than duplicated.

The full mechanic behind what [[FEARS Combat System]] originally called (without detail) "Active Defense" and "Counterattack Opportunities." A defender may deliberately fail Evasion to gain a free Tactical Reaction — once per attack, per attacker, per round. Doesn't consume the normal reaction. The reaction is declared *before* damage is rolled (so it can modify incoming damage, e.g. Shield Block). Full damage (post-DR) is still taken, and the defender loses 1 [[Momentum]]. Every element below was confirmed identical to the prior summary — the eighth consecutive DCS-companion source to check out with zero drift on shared content (after [[Combat Flow]], [[Bloodied Breaking Points Rally]], [[Called Shot]], [[Damage Reduction]], [[Momentum]], [[Evasion]], [[Injury System]]) — plus substantial new detail this source alone provides.

## Two reaction categories

FEARS distinguishes two kinds of reaction, not previously named as separate categories on this page:

- **Standard Reactions** — used at any point in the round when a valid trigger occurs (opportunity attacks, readied actions, class features). Consume the normal reaction.
- **Tactical Reactions** (below) — gained by deliberately forgoing Evasion. Do not consume the normal reaction.

### Standard Reaction triggers

| Trigger | Reaction available |
|---|---|
| Enemy moves through your reach | Opportunity Attack |
| Ally is attacked within reach | Intercept (class features only, e.g. Paladin Interpose) |
| Enemy attempts to grapple or shove you | Contested response (part of the grapple/shove resolution) |
| Defender rolls a Nat 20 on Evasion | Free attack or action (no reaction cost) |
| Class feature trigger (Riposte, Primal Defiance, etc.) | As specified by the feature |

## Options

| Reaction | Effect |
|---|---|
| Counterattack | Melee/ranged attack against the attacker, with advantage |
| Magic Attack | Touch spell at advantage, or ranged spell normally; cantrip only if a levelled spell was already cast this turn |
| Trap Weapon | Contested Strength (Athletics) or Dexterity (Acrobatics) roll to lock the attacker's weapon; on success, they can't use it again until they pass a Strength check (DC = 8 + PB + STR or DEX mod) as an action |
| Disarm | Contested Strength (Athletics) or Dexterity (Acrobatics) roll to knock the weapon to a space within 5 ft of the attacker |
| Shield Reaction | Free use of a [[Shields|Shield Reaction]] (Block/Bash/Deflect) |
| Grapple Back | Immediate Athletics-vs-Acrobatics/Athletics grapple |
| Trip / Sweep | Attacker makes a Dexterity save (DC = 8 + PB + STR mod) or falls prone |
| Tactical Retreat | Move 5 ft without provoking (needs open space) |
| Weapon Bind | Both combatants at −2 to attacks until the bind breaks (opposed STR) |
| Intimidating Glare | Attacker WIS save (DC 8+PB+CHA mod) or disadvantage on next attack + lose 1 Momentum; once per encounter per target |

Landing a Counterattack or Disarm this way grants +2 Momentum instead of +1 — an explicit reward for the high-risk play of taking a hit to strike back. New this ingest: the exact DC formulas for freeing a trapped weapon and for the Trip/Sweep save, neither of which the original DCS summary specified.

### Correction (from Combat Flow)

[[Dynamic Combat System (DCS)]]'s original summary combined "Trap / Disarm" into a single row. [[Combat Flow]]'s fuller sequence reference makes clear these are **two distinct reactions** — Trap Weapon locks the attacker's weapon in place, Disarm knocks it away entirely. Table corrected above.

## Reaction economy (new)

How the different reaction types stack within a single round:

| Reaction type | Uses per round | Costs normal reaction? |
|---|---|---|
| Standard Reaction (OA, class features) | 1 | Yes |
| Tactical Reaction (forgoing Evasion) | Once per attack, per attacker | No |
| Shield Reaction (used as standard reaction) | 1 (shares with Standard) | Yes |
| Shield Reaction (used as Tactical Reaction) | Once per attack, per attacker | No |
| Nat 20 Defender (free attack on perfect defence) | 1 per occurrence | No |

This means a character attacked twice in a round by two different enemies can forgo Evasion against one attacker (free Tactical Reaction) while keeping their normal reaction available for the second attacker, an opportunity attack, or a Shield Reaction. At **+4 Momentum (level 17+)**, PCs gain 1 extra reaction usable for any Standard or Shield Reaction — this confirms, rather than adds to, [[Momentum]]'s existing Epic expansion table.

## Combat flow with reactions (new)

**Tactical Reaction (forgoing Evasion):** attack lands → declare the Tactical Reaction immediately, before damage is rolled (this is what lets Shield Block modify the incoming damage) → damage resolves → the declared reaction executes → normal reaction remains available.

**Shield Reaction (as a standard reaction):** attacker rolls → defender rolls Evasion normally → if the attack would land, declare Block or Deflect before damage is rolled → resolve → normal reaction is consumed.

> **Worked example:** A Fighter (medium armor, Torso DR 4) forgoes Evasion against a hobgoblin's hit and declares Counterattack immediately. Damage resolves first (13 raw − 4 DR = 9 taken, −1 MS), then the Counterattack executes (`1d20+6` with advantage, hits, 9 damage, +2 MS). Net: 9 damage each way, +1 net Momentum, normal reaction still available for a second attacker.

## Reaction class features and feats (new)

A fourth independent feat-system sighting (after [[Called Shot Feats]] 14, [[Evasion Feats]] 4, [[Weapon Mastery Feats]] 2) and the second subclass-system sighting (after [[Called Shot Subclass Features]]) — this time seen only through the reaction lens. See [[Reaction Subclass Features]] and [[Reaction Feats]].

## See also

- [[Dynamic Combat System (DCS)]]
- [[Evasion]]
- [[FEARS Combat System]]
- [[Momentum]]
- [[Combat Flow]]
- [[Reaction Subclass Features]]
- [[Reaction Feats]]
- [[FEARS MOC]]
