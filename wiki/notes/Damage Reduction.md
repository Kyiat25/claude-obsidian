---
type: concept
title: "Damage Reduction"
address: c-000074
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
  - "DR"
related:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Evasion]]"
  - "[[Called Shot]]"
  - "[[Shields]]"
  - "[[Called Shot Feats]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Damage Reduction.md"
confidence: high
---

# Damage Reduction (DR)

> Editorial note: no separate source page was created for this ingest — `.raw/Damage Reduction.md` deepens exactly this page's existing content (same pattern as [[Combat Flow]] and [[Called Shot]]'s ingests), so it was merged in rather than duplicated.

"Armour does not make you harder to hit — it makes you harder to kill." Armor no longer affects hit chance — it absorbs damage after a blow lands, per body part, working alongside [[Evasion]] rather than replacing it. Unarmored locations provide 0 DR. Applies to physical damage only (slashing/piercing/bludgeoning); magical/elemental/psychic bypass DR unless the armor specifically resists it. **Universal rule: DR cannot go below 0** — it can zero out damage entirely, but never becomes bonus damage in reverse.

Every table below is confirmed identical to the original [[Dynamic Combat System (DCS)]] summary — zero drift, the fourth consecutive DCS-companion source to check out this way (after [[Combat Flow]], [[Bloodied Breaking Points Rally]], [[Called Shot]]).

## Armor types

| Type | Torso | Head | Arms | Legs | Total DR | Defence Mode | Special |
|---|---|---|---|---|---|---|---|
| Light | 2 | 1 | 1 | 1 | 5 | Dodge (Dex) | 5 ft shift on dodge; +2 Momentum on clean dodge |
| Medium | 4 | 2 | 2 | 2 | 10 | Dodge (Dex) | No Momentum loss on tie |
| Heavy | 6 | 3 | 3 | 3 | 15 | Brace (Str) only | −5 ft speed unless STR ≥ 15; highest DR, no dodge-step |

## Standard attacks vs. Called Shots

- **Standard attack**: reduced by **Total DR** (sum of all four locations). A heavy-armor target (Total DR 15) takes only 5 from a 20-damage hit.
- **[[Called Shot]]**: reduced by **only the targeted location's DR**. The same heavy-armor target hit in the arm (DR 3) takes 17 — the tradeoff being a −2 attack penalty. Design intent: Called Shots are meant to be the answer to heavily-armored enemies, not an afterthought — "the accuracy penalty is outweighed by bypassing the majority of the armour's protection" against Total DR 10+.
- **Critical hit**: automatically lands, halves the targeted location's DR (e.g. a torso crit against heavy armor: DR 6 → 3, a 20-damage hit deals 17).

## Shields

Matches [[Shields]] exactly: Small (+2 DR arm, +2 Evasion), Standard (+3 DR arm), Great (+5 DR all locations via Block, Brace only). No drift.

## Layered armor

Lighter armor stacks under heavier armor (max 2 layers per location, one per armor type): DR adds, but each layer costs −5 ft movement. A non-proficient piece of non-torso armor doesn't impose non-proficiency penalties.

## Magical and natural DR (new)

| Source | Effect |
|---|---|
| Magic-enhanced armor (+1/+2/+3) | Adds to DR at all covered locations |
| Resistant armor | +2 DR against a chosen damage type |
| Dragonborn natural resistance | +2 DR against their breath weapon's element |
| Tough feat | +1 DR to all body parts — see [[Called Shot Feats]] for other feat interactions (this one has no called-shot tie, evidence the feat system extends beyond that narrow lens) |
| Elemental Runes | +2 DR against a chosen element |
| Reinforced Seams (light armor upgrade) | +1 to Evasion rolls |
| Hardened Plates (medium/heavy upgrade) | +1 DR to torso |
| Spiked Harness | 1d4 piercing to anyone who grapples or strikes you unarmed |

First mention of a playable race (Dragonborn) anywhere in this cluster — noted, not otherwise explored.

## Class and subclass DR features

Confirms existing class-page hooks with zero drift: [[Rogue]] (Sneak Attack ignores DR), [[Magus]] (Arcane Guard scaling DR — see clarification below), [[Investigator]] (studied targets' DR reduced), [[Witch]] (Hex of Frailty — resolved, see [[Witch]]). Adds genuinely new formulas, applied to the relevant class pages:

- **Barbarian (Unarmored)**: ~~DR = Constitution modifier (min 1), doubled while Raging~~ — **superseded**. Ruled: the per-class deep-dive is authoritative over the old DCS-era summary wherever they conflict. Current rule is [[Barbarian]]'s deep-dive formula: flat level-based Rage DR (1 at 1st, 2 at 10th, 3+CON mod max 5 at 20th), no doubling mechanic. See [[Barbarian]] for the full writeup.
- **Monk (Unarmored)**: ~~DR = ½ Dexterity modifier; may spend a Technique Point for +2 DR to all locations until their next turn~~ — **superseded**. Current rule is [[Monk]]'s deep-dive formula: flat, level-gated Unarmoured Resilience (1 at 3rd, 2 at 9th, 3 at 15th), no DEX-mod scaling, no Technique-Point-spend option. See [[Monk]] for the full writeup.
- **Paladin (Aura)**: ~~Aura = CHA mod DR to allies~~ — **superseded, and removed**. [[Paladin]]'s deep-dive defines Aura of Protection entirely as a saving-throw bonus (CHA mod, min +1, to saves within range) — no Damage Reduction component exists anywhere in the document. The old summary's DR claim doesn't survive the ruling; Aura of Protection is a saves-only feature. See [[Paladin]] for the full writeup.
- **Shaman (Totemic Resilience)**: ~~Totemic Wards elemental DR to allies~~ — **superseded**. Current rule is [[Shaman]]'s deep-dive formula: flat, non-elemental **+1 DR to the Shaman only**, and only while a Guardian-category Totem (Bear/Ox/Turtle) is active — the other two Totem categories grant Evasion or save-advantage instead, not DR. No ally-targeted or elemental-typed DR mechanic exists. See [[Shaman]] for the full writeup.
- **Druid — Circle of the Moon**: Beast forms gain DR = ½ level; using Wild Shape as an action grants +1 DR to all locations. **Baseline Beast Form DR** (from [[Druid]]'s per-class deep-dive, applies to every Druid regardless of Circle): `(Beast's AC − 10) + Beast's CON modifier + Beast's STR modifier (Large or larger only)`, negative modifiers treated as 0 — the Circle of the Moon bonus above stacks on top of this baseline rather than replacing it. Called Shots reduce Beast Form DR by 2, a Beast-Form-specific penalty not seen on any other class's DR interactions.
- **Fighter — Battle Master**: a Precision maneuver bypasses ½ the target's DR on one attack.
- **Ranger — Colossus Slayer**: reduces target DR by 2 against already-injured creatures (distinct from Hunter's Mark's Wisdom-modifier DR reduction, already on [[Ranger]]'s page — see contradiction below).
- **Ranger — Fleet Guard** (5th level, from [[Ranger]]'s per-class deep-dive): moving at least 10 ft on the Ranger's turn grants +1 DR until the start of their next turn, stacking with armour DR.
- **Reaper — Death's Resilience** (from [[Reaper]]'s per-class deep-dive): while holding 3+ Soul Tokens, +1 DR at 5th level, +2 at 11th, +3 at 17th — a token-count-conditional DR hook, a new shape distinct from every other class's DR formula this session.
- **Tattooist — Inscribed Ward** (from [[Tattooist]]'s per-class deep-dive): +1 DR at any tattooed body location (self-only until 14th-level Deep Inscription extends it to tattoos made for others), mapped directly onto the DCS body-location system (Head/Neck→Head DR, Chest/Back→Torso DR, Arms→Arm DR, Legs→Leg DR). A clean, uncontested new class hook — no conflict with any prior claim.
> [!note] Hex of Frailty — resolved and designed as a 6th-level Coven Feature
> [[Witch]]'s per-class deep-dive never detailed Coven-specific features (only two example Covens were named, neither fleshed out). Ruled: a genuine feature, not a documentation gap — Hex of Frailty is now written as a 6th-level Coven of the Hidden Moon feature: a hexed/marked target's DR is reduced by 2 for as long as the hex/mark persists, matching the flat −2 magnitude of [[Ranger]]'s Hunter's Mark/Colossus Slayer and [[Inventor]]'s Overclock. See [[Witch]] for the full writeup.

- **Warden — Prime Element Resonances and stance-gated DR** (from [[Warden]]'s per-class deep-dive): Earthen Bulwark's Stone Skin (+1 DR vs. physical while in medium/heavy armour), the Heroic Boon Unyielding Terrain (+3 DR, stacking, while stationary), and Sentinel's Sentinel's Anchor (+2 armour DR, stacking, while stationary) are three more clean, uncontested hooks — no conflicts, but notable for how many distinct DR sources one class accumulates across its Prime Element choice, Heroic Boon, and Discipline.

- **Ranger — Hunter's Mark**: ~~reduces the marked target's DR by the Ranger's Wisdom modifier~~ — **superseded**. Ruled: the per-class deep-dive is authoritative. Current rule is [[Ranger]]'s deep-dive formula: flat **−2 DR**, no WIS-mod scaling. Stacks additively with Colossus Slayer's own flat −2 (total −4 against already-injured, marked creatures) rather than restating the same number. See [[Ranger]] for the full writeup.
- **Inventor — Engineered Guard**: +1 DR to all locations while wearing armour the Inventor has modified/created (including anything bearing their infusions or upgrades). Stacks with base armour DR, but not with other Inventor features that explicitly grant DR. Inventor's Overclock (a Class Reaction) separately reduces a target's DR by 2 on a hit — a temporary enemy-side reduction, not a self-buff, joining Weapon Skills like Shatter Guard as another DR-reduction lever.
- **Magus — Arcane Guard clarification** (from [[Magus]]'s per-class deep-dive): bonus action, spend 1 point from the Arcane Reservoir for **+1 DR** until the start of the Magus's next turn — a flat, single-point-spend value, not explicitly "scaling" as the older DCS-summary framing implied. Not a contradiction (nothing rules out spending multiple points for cumulative DR), but the flat-DR wording here is the more precise of the two sources.

## DR reduction stacking

Multiple effects (Weapon Skills, class features, Hunter's Mark, Shatter Guard) can stack, but **DR cannot be reduced below 0 at any location** — reduction never becomes bonus damage.

## Optional rules

- **Armor Degradation**: >10 damage to a location after DR → roll d6, on a 1 that piece's DR drops by 1 until repaired. Magical armor only degrades on a 1 from a magical weapon or crit.
- **Weight Threshold Fatigue**: if total DR exceeds Strength score, gain Exhaustion at combat start unless a CON save succeeds (DC 10 + armor layers; only applies if unproficient or over-threshold).

## See also

- [[Dynamic Combat System (DCS)]]
- [[Evasion]]
- [[Called Shot]]
- [[Shields]]
- [[Called Shot Feats]]
- [[Druid]]
- [[Fighter]]
- [[Inventor]]
- [[Magus]]
- [[Monk]]
- [[Barbarian]]
- [[Paladin]]
- [[Ranger]]
- [[Reaper]]
- [[Shaman]]
- [[Tattooist]]
- [[Warden]]
- [[Witch]]
- [[FEARS MOC]]
