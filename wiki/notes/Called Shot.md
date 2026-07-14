---
type: concept
title: "Called Shot"
address: c-000041
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
status: mature
mocs:
  - "[[FEARS MOC]]"
complexity: intermediate
domain: fears
aliases:
  - "Called Shots"
related:
  - "[[FEARS Character Framework]]"
  - "[[FEARS Combat System]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Damage Reduction]]"
  - "[[Combat Flow]]"
  - "[[Enemy Rally]]"
  - "[[Called Shot Subclass Features]]"
  - "[[Called Shot Feats]]"
  - "[[Cleric]]"
  - "[[Fighter]]"
  - "[[Investigator]]"
  - "[[Monk]]"
  - "[[Paladin]]"
  - "[[Reaper]]"
  - "[[Rogue]]"
  - "[[Shaman]]"
  - "[[Tattooist]]"
  - "[[Warden]]"
  - "[[Warlock]]"
sources:
  - "[[FEARS Character Framework]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Bloodied Breaking Points Rally]]"
  - ".raw/Called Shots.md"
  - "[[The Dynamic Combat System (Excluded Draft)]]"
confidence: high
---

# Called Shot

> Editorial note: no separate source page was created for this ingest — `.raw/Called Shots.md` deepens exactly this page's existing content (same pattern as [[Combat Flow]]'s ingest), so it was merged in rather than duplicated.

Targets a specific body part in combat for tactical effects, trading an attack penalty for bypassing most of the target's [[Damage Reduction]] and imposing an effect on a failed save. Full mechanics given by [[Dynamic Combat System (DCS)]]. Every formula below is confirmed identically across three independent sources ([[FEARS Character Framework]], [[Dynamic Combat System (DCS)]], and this deeper source) — the strongest cross-source consistency in the cluster.

## Core rules

1. Declared **before** the attack roll.
2. Flat attack penalty by location (see tables below).
3. **Passive Perception detection** is automatic: Detection DC = 10 + Attacker's Attack Bonus − Called Shot Penalty. If the defender's Passive Perception ≥ DC, they get Advantage on Evasion and know the target location.
4. On a hit, the target makes a saving throw to resist the effect. Glancing blow: halve damage then apply DR — if any damage remains, the effect applies; if DR zeroes it out, no effect.
5. Critical hit: the saving throw is made at disadvantage.
6. Only **one** Called Shot effect per attacker per turn, regardless of how many attacks land.
7. Creatures without relevant anatomy may be immune or have effects reflavored, at GM discretion.
8. Unarmored targets: the save is made at disadvantage (except creatures with Unarmoured Defence).
9. Called Shot penalties still apply even if the attacker already has disadvantage.

## Basic areas (any proficient character)

| Target | Penalty | Save | Effect |
|---|---|---|---|
| Head | −5 | CON | Stunned: disadvantage on attacks + lose Reaction until end of next turn |
| Arms | −2 | STR | Disarm, or −2 to attacks for 1 round |
| Legs | −2 | DEX | Speed to 0, or fall Prone |
| Torso | 0 | — | Standard damage, no extra effect |

## Advanced areas (requires weapon/spell proficiency)

| Target | Penalty | Save | Effect |
|---|---|---|---|
| Eye | −7 | CON | Blinded until end of next turn |
| Hand | −4 | DEX | Drop held object / fail somatic component |
| Throat | −6 | INT | Silenced 1 turn |
| Wing | −3 | DEX | Fall if airborne, or lose flight 1d4 rounds |
| Tail | −3 | DEX | Lose balance, fall prone on failed save |

## Interactions

- A Weapon Mastery Skill and a Called Shot on the same attack share **one** saving throw (attacker's choice which effect it resists); the other applies automatically.
- Momentum on a hit: **+2** if the target fails its save, **+1** if it succeeds, **−1** on a miss.
- **Optional — Insightful Combatant**: use Insight instead of Passive Perception against a humanoid fought 2+ rounds, or attempting feints/disinformation. Rangers get this against favoured enemies; Investigators against any humanoid.
- Targeting an **enemy leader's** head, throat, or hand can fast-track their morale collapse — see [[Enemy Rally]]'s player-counterplay note.

## Momentum integration

At **+3 [[Momentum]]**, defenders roll Called Shot saves with **advantage**. At **−2 Momentum**, saves are made with **disadvantage** — a struggling target is easier to exploit precisely.

## Injury System stacking

If a Called Shot drops a target through an HP threshold, both systems trigger and stack: the Called Shot save resolves first, then the [[Injury System]] roll. A leg shot can knock a target prone *and* independently roll a Broken Bone result — the two don't override each other.

## Damage Reduction bypass (worked)

| Armor | Total DR (standard attack) | Arm DR (Called Shot) | DR bypassed | Worth the −2 penalty? |
|---|---|---|---|---|
| Light | 5 | 1 | 4 | Situational |
| Medium | 10 | 2 | 8 | Usually |
| Heavy | 15 | 3 | 12 | Almost always |

Against Total DR 10+, arm/leg Called Shots commonly out-damage a standard attack despite the penalty — confirms [[Damage Reduction]]'s design-intent note from the other direction, with concrete numbers.

## Subclasses and feats (new discovery)

This source revealed two previously-unseen systems, each visible only through their Called Shot interaction: a **subclass** layer (Assassin, Battle Master, Champion, and 8 more — see [[Called Shot Subclass Features]]) and a **feat** layer (14 feats — see [[Called Shot Feats]]). Neither is documented beyond this narrow lens; flagged on [[FEARS MOC]] as a real gap, not filled in with speculation.

## Class access routes

- [[Cleric]]'s **Judgment** (bonus action via Channel Divinity, 2nd level): the Cleric's next weapon or spell attack this turn counts as a Called Shot with **no attack-roll penalty** — a new access route that bypasses the normal penalty tables above entirely, distinct from every other class hook seen so far. Wasted if the Cleric doesn't attack before end of turn. **Confirmed word-for-word on [[Paladin]]** — same feature, same Channel Divinity delivery, same wasted-if-unused clause.
- [[Paladin]]'s **Holy Precision** (3rd level): once per turn on a Called Shot, reduce the penalty by CHA modifier (min 1) — the same access-route shape as Fighter's/Investigator's/Monk's hooks, this time CHA-scaled.
- [[Reaper]]'s **token-based access route**: spend 2 Soul Tokens to ignore a Called Shot penalty entirely, or 3 to auto-hit and count it as a critical hit if the target is bloodied — the first Called Shot hook costing a class resource pool rather than being scaled by an ability modifier or PB.
- [[Rogue]]'s **Perfect Shot** (13th level): once per long rest, a Called Shot with no penalty at all, auto-maxing Sneak Attack damage if it qualifies — a full penalty waiver rather than a scaled reduction, the first hook gated to once-per-long-rest instead of once-per-turn. Also confirms Sneak Attack's own qualifying-Called-Shot penalty reduction is a flat **−2**.
- [[Shaman]]'s **Ancestral Precision** (7th level): marks a target for 1 minute, granting the Shaman and allies advantage on Called Shots against it (rather than a penalty reduction), plus +2d6 spirit damage on Called Shots if the target is within an active Totem's range — the first Called Shot hook to grant advantage on the roll itself instead of adjusting the penalty number.
- [[Tattooist]]'s **Anatomical Precision** (5th level): Tattoo Exploitation reduces the penalty by 1 against a target with a visible magical effect/tattoo/enchantment at the targeted location — modest but stackable with other hooks. The same feature also runs the interaction in reverse: Called Shot Awareness grants the Tattooist advantage on Evasion against a Called Shot targeting one of their own tattooed locations, and Ally Protection grants a tattooed ally +1 Evasion against the same.
- [[Warden]]'s **Predator's Mark / Predator's Pursuit** (Apex Predator, 1st and 6th level): Called Shot penalties against the Warden's marked Prey are reduced by 1 (1st), cumulative to 2 total (6th) — a subclass-gated, target-restricted version of the flat penalty-reduction shape seen on several other classes.
- [[Warlock]]'s **Chaos Shot** invocation: reduces the Called Shot penalty by 1 when delivered via Eldritch Blast specifically; on success, the target also takes disadvantage on its next Evasion roll or area-effect save — an invocation-gated route distinct from the already-documented Hexblade subclass hook.
- [[Fighter]]'s **Surgical Precision** (5th level): once per turn on a Called Shot attempt, reduce the attack-roll penalty by PB. At 5th level (PB +3), an arm shot's normal −2 penalty becomes a **+1 bonus** — the first class hook that can flip a Called Shot penalty into a net-positive roll rather than merely softening it.
- [[Investigator]]'s **Forensic Called Shot** (5th level): the same penalty-reduction shape as Fighter's Surgical Precision (reduce by PB, an arm shot's −2 becomes +1 at PB +3), but restricted to Called Shots against the Investigator's designated Quarry specifically rather than any target.
- [[Monk]]'s **Deadeye Strike** (15th level): once per turn, reduce the Called Shot penalty by DEX modifier (minimum reduction of 1) — the same access-route shape as Fighter's and Investigator's hooks, but scaled by an ability modifier instead of PB.

## Save DC (resolved by user ruling)

`DC = 8 + Proficiency Bonus + attacker's ability modifier` (the same ability used for the attack roll — STR/DEX for a weapon Called Shot, the caster's spellcasting ability for a spell-delivered one). Matches the house `8 + PB + ability` shape used everywhere else in FEARS (every confirmed caster spell-DC sighting).

This number was previously only sourced from [[The Dynamic Combat System (Excluded Draft)]] — an explicitly non-canonical, low-confidence source — and flagged as an open gap on [[FEARS MOC]]. **Resolved by user ruling**: the real risk of a Called Shot was never the target's save DC anyway — it's the attack-roll penalty itself (−2 to −7, confirmed identically across three sources), which is already a fully realized, well-tuned risk/reward trade against [[Damage Reduction]] bypass (see the worked table above). The save DC only governs whether the *bonus rider effect* also lands on top of an already-risky hit, so adopting the excluded draft's formula here doesn't change that risk/reward balance — it just resolves the one number nothing else in canon supplied. Promoted to confirmed canon on this basis.

## See also

- [[FEARS Character Framework]]
- [[FEARS Combat System]]
- [[Dynamic Combat System (DCS)]]
- [[Damage Reduction]]
- [[Combat Flow]]
- [[Enemy Rally]]
- [[Called Shot Subclass Features]]
- [[Called Shot Feats]]
- [[The Dynamic Combat System (Excluded Draft)]]
- [[FEARS MOC]]
