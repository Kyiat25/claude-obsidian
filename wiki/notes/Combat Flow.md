---
type: concept
title: "Combat Flow"
address: c-000078
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
status: mature
mocs:
  - "[[FEARS MOC]]"
complexity: advanced
domain: fears
related:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Evasion]]"
  - "[[Damage Reduction]]"
  - "[[Called Shot]]"
  - "[[Tactical Reactions]]"
  - "[[Momentum]]"
  - "[[Injury System]]"
  - "[[Bloodied and Bruised]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Combat Flow.md"
confidence: high
key_claims:
  - "The master 12-step sequence every DCS attack follows, expanding DCS.md's own 9-step summary into full granularity — notably splitting 'Damage Roll + Apply DR' into distinct steps and adding an explicit Momentum Update as the final step."
  - "Confirms every formula and table from Evasion, Damage Reduction, Called Shot, Momentum, and Injury System with zero drift — this is the strongest cross-source consistency seen anywhere in the FEARS cluster so far."
  - "Splits DCS.md's combined 'Trap / Disarm' Tactical Reaction into two genuinely distinct reactions: Trap Weapon (lock the attacker's weapon) and Disarm (knock it away) — a real correction, not just added detail."
---

# Combat Flow

> Editorial note: no separate source page was created for this ingest. `.raw/Combat Flow.md`'s filename collides with this page's own title, and its content is a direct, deeper elaboration of exactly what this page already summarized (from [[Dynamic Combat System (DCS)]]) — so the existing page was upgraded in place rather than duplicated. This mirrors how the vault already treats [[Called Shot]] (upgraded from stub to full tables under [[FEARS Character Framework]] and DCS) rather than splitting into parallel pages.

The master sequence reference for every DCS attack. Both attacker and defender have clear decision points at each step — the order matters most around when damage resolves relative to reactions.

## The 12-step sequence

| Step | Actor | What happens |
|---|---|---|
| 1. Declare Attack | Attacker | Standard or [[Called Shot]] (name the body part). Called Shot penalty applies immediately. |
| 2. Called Shot Detection | Automatic | Called Shots only. Passive Perception vs. Detection DC (`10 + Attack Bonus − Called Shot Penalty`), free, no roll. |
| 3. Attack Roll | Attacker | `1d20 + attack bonus`, minus Called Shot penalty. Advantage/Disadvantage applies here. |
| 4. Critical Hit Check | — | Nat 20: auto-lands, skips [[Evasion]] entirely, targeted DR halved, Called Shot save at disadvantage, **defender loses −2 Momentum**. Proceed to step 7. |
| 5. Evasion Roll (or Take the Hit) | Defender | Dodge (`1d20+DEX+PB`) or Brace (`1d20+STR+PB`), or forgo entirely for a free reaction — see [[Tactical Reactions]] (−1 Momentum, once per attacker per round). |
| 6. Evasion Outcome | — | Compare rolls: clean defence / glancing blow / full hit, each with its own Momentum change (see table below). |
| 7. Damage Roll | Attacker | Full damage, or halved first on a glancing blow. |
| 8. Apply DR | Defender | Targeted location's DR (Called Shot) or Total DR (standard attack); halved on a crit; floor of 0. |
| 9. Damage Applied | — | Subtract from HP; check injury thresholds. Mitigation choice (Constitution Save vs. Grit Save) is made **blind**, before the injury roll. |
| 10. Tactical Reaction | Defender | If Evasion was foregone in step 5, the pre-declared reaction executes now. |
| 11. Resolve Effects | — | In order: Called Shot saves → Injury table → Bloodied (enemies only) → Weapon Skill effects → conditions. |
| 12. Momentum Update | Both | Any remaining Momentum changes apply. Optional Swing Guardrail caps ±2 MS/turn (before injury resets). |

## Evasion outcome table (step 6)

| Result | Outcome | Momentum |
|---|---|---|
| Nat 20 (Defender) | Perfect Defence — miss, free reaction, light armor may shift 5 ft | +2 MS (light) / +1 MS (other) |
| Defender > Attacker | Clean Defence — miss, no damage | +2 MS (light) / +1 MS (other) |
| Defender = Attacker | Glancing Blow — halve damage, then DR | 0 (medium armor) / −1 MS (other) |
| Defender < Attacker | Full Hit — DR applies normally | −1 MS |

## Injury mitigation (step 9)

Chosen blind, before the injury table is rolled:

| Option | Cost | Effect |
|---|---|---|
| Constitution Save | none | DC = 10 + (damage ÷ 10), min 12. Success reduces injury one tier. |
| Grit Save | 1 level Exhaustion | Ignore the injury and its Momentum effects entirely. Exhaustion reduces all future Momentum gains by 1/level. |

Full detail: [[Injury System]].

## Tactical Reactions correction

[[Dynamic Combat System (DCS)]]'s summary combined "Trap / Disarm" into one Tactical Reaction row. This source splits them into two distinct reactions — **Trap Weapon** (contested roll to lock the attacker's weapon) and **Disarm** (contested roll to knock it away) — now corrected on [[Tactical Reactions]].

## Common questions (from the source)

- **Tactical Reaction timing**: declared immediately on foregoing Evasion, before damage is rolled — this is what lets Shield Block modify incoming damage. Other reactions (Counterattack, etc.) are declared at the same moment but execute after damage resolves.
- **Shield Block as a Tactical Reaction**: yes — sequence is forgo Evasion → declare Shield Block → roll damage with +3 DR already applied.
- **Forgoing Evasion twice in one round**: yes, against two different attackers. A single attacker's multi-attack is one window unless a new action (Action Surge) opens another.
- **Called Shot on a glancing blow**: the effect still applies if any damage gets through DR after halving; if DR zeroes it out, no effect.
- **Tactical Reaction vs. normal reaction**: a Tactical Reaction (from forgoing Evasion) does not consume the normal reaction for the round.

## Worked example (Called Shot + Critical Hit)

A Barbarian targets an ogre's arm (−2 penalty) and rolls a natural 20. The attack auto-lands, skips Evasion, and the ogre's Arm DR (3) is halved to 1 before applying — 17 damage gets through. Crossing the 50% threshold triggers the Injury table first (result: dropped weapon), then Bloodied effects second; the ogre also fails a disadvantaged STR save against the Called Shot's own disarm effect — both systems independently confirm the same outcome. Momentum: Barbarian gains +2 (crit) +2 (Called Shot with failed save), capped at +3 if the optional Swing Guardrail is in use.

## See also

- [[Dynamic Combat System (DCS)]]
- [[Evasion]]
- [[Damage Reduction]]
- [[Called Shot]]
- [[Tactical Reactions]]
- [[Momentum]]
- [[Injury System]]
- [[Bloodied and Bruised]]
- [[FEARS MOC]]
