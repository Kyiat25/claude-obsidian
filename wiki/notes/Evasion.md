---
type: concept
title: "Evasion"
address: c-000073
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
  - "[[Damage Reduction]]"
  - "[[FEARS Combat System]]"
  - "[[Momentum]]"
  - "[[Shields]]"
  - "[[Evasion Feats]]"
  - "[[Called Shot Feats]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Evasion.md"
confidence: high
---

# Evasion

> Editorial note: no separate source page was created for this ingest — `.raw/Evasion.md` deepens exactly this page's existing content (same pattern as [[Combat Flow]], [[Called Shot]], [[Damage Reduction]], and [[Momentum]]'s ingests), so it was merged in rather than duplicated.

"Defence is not a wall — it is a choice, a rhythm, a stance." Replaces static Armor Class. When attacked, the defender chooses a mode:

- **Dodge** (`1d20 + DEX + PB`) — available with light/medium armor proficiency, shields, or unarmored defense.
- **Brace** (`1d20 + STR + PB`) — available with heavy armor or shield proficiency. Heavy armor and great shields *require* Brace — Dodge isn't an option.
- **Take the Hit** — deliberately fail Evasion for a free [[Tactical Reactions|Tactical Reaction]].

Momentum score and situational modifiers apply after the base roll. Every table below is confirmed identical to the original [[Dynamic Combat System (DCS)]] summary — the sixth consecutive DCS-companion source to check out with zero drift.

## Outcomes

| Result | Effect |
|---|---|
| Nat 20 (Defender) | Perfect Defence — miss entirely, free reaction, light armor may shift 5 ft |
| Defender > Attacker | Clean Defence — miss, no damage |
| Defender = Attacker | Glancing Blow — half damage, then DR |
| Defender < Attacker | Full Hit — DR applies normally |
| Nat 20 (Attacker) | Critical Hit — always lands, bypasses Evasion, targeted DR halved, defender loses −2 [[Momentum]] |

## Momentum interaction

| Result | Momentum |
|---|---|
| Perfect Defence (light armor) | +2 MS + free reaction |
| Perfect Defence (other armor) | +1 MS + free reaction |
| Clean Dodge/Brace (any armor) | +1 MS |
| Clean Dodge in light armor | +2 MS |
| Glancing Blow in medium armor | no change |
| Glancing Blow (light/heavy) | −1 MS |
| Full Hit | −1 MS |
| Critical Hit received | −2 MS |

Light armor's +2 MS on a clean dodge represents "precise, fluid movement — slipping an attack entirely through skill and timing," the mark of a combatant fully in rhythm.

## Armor identity

| Armor | DR (Torso/Head/Arms/Legs) | Mode | Special |
|---|---|---|---|
| Light | 2/1/1/1 | Dodge | +2 MS on clean dodge; shift 5 ft on any successful dodge |
| Medium | 4/2/2/2 | Dodge | No Momentum loss on a tie |
| Heavy | 6/3/3/3 | Brace only | Highest DR, no reposition |

## Area of Effect

Roll Evasion vs. the spell/ability DC: Nat 20 or success = no damage (light armor may shift 5 ft on a Nat 20); tie = half damage then DR; failure = full damage then DR. Same armor-identity perks apply (light repositions on a Nat 20, medium takes no Momentum hit on a tie).

## Conditions affecting Evasion

Cover (+2 to +5), Blinded/Surprised/Flanked (disadvantage), Prone (disadvantage vs. melee, advantage vs. ranged), Restrained/Grappled (disadvantage, can still Brace), moved ≥ half speed (+1 in Dodge mode).

## Shields

Small (+2 DR arm, +2 Evasion, Dodge or Brace), Standard (+3 DR arm, no Evasion bonus), Great (+5 DR all locations via Block, Brace only — cannot Dodge). Matches [[Shields]] exactly.

## Monster Evasion (new)

| Monster type | Formula |
|---|---|
| Humanoids | Base + DEX modifier |
| Giants | Base + DEX modifier + 1 |
| Dragons | Base + DEX modifier + 3 |
| Legendary creatures | May auto-succeed one Evasion roll per round (Legendary Resistance) |

## Naming collision with Rogue's own "Evasion" class feature

[[Rogue]]'s 6th-level class feature is also named **Evasion** — but it's the classic D&D-legacy ability (no damage on a successful DEX save, half on a failed one), an entirely different mechanic from this page's Dodge/Brace defense-roll system. The shared name is coincidental terminology inherited from 5E, not a cross-reference; nothing in [[Rogue]]'s own deep-dive treats the two as related.

## Class hooks

Confirms existing pages with zero drift: [[Rogue]] (tie = clean dodge, Sneak Attack bypasses DR), [[Barbarian]] (Brace advantage while Raging), [[Paladin]] (CHA-mod DR aura, Shield Reactions integrate with Brace), [[Fighter]] (Shield Reactions integrate with Brace), [[Magus]] (Arcane Guard scaling DR), [[Investigator]] (studied targets' DR reduced), [[Shaman]] (Totemic Wards), [[Witch]] (Hex of Frailty). New detail: **Monk** may, at higher levels, teleport and counterattack on a successful defence — beyond the already-known Technique Point reroll; [[Monk]]'s own per-class deep-dive now supplies the actual formula (see below). **[[Druid]]** (from its per-class deep-dive): Beast Form Evasion = `1d20 + Beast's DEX modifier + PB`, with Small/Tiny forms rolling with advantage — a separate formula from the Druid's own out-of-Beast-Form Dodge/Brace roll, tracked only while transformed. **[[Fighter]]** (from its per-class deep-dive): two Fighting Styles feed directly into Evasion — **Agile Defence** adds DEX modifier to Evasion regardless of armour type (removing the usual armour-proficiency gating), and **Shield Master** adds the shield's DR bonus to the Evasion roll itself rather than just DR; **Dueling** separately grants advantage on the Evasion roll once per turn while wielding a single one-handed weapon with no other weapon or shield. **[[Monk]]** (from its own per-class deep-dive): Unarmoured Defence adds **Wisdom modifier** (not DEX) to all Evasion rolls while unarmoured/shieldless — the first exact formula confirmed for Monk's base Evasion bonus. **[[Shaman]]** (from its own per-class deep-dive): a Soul Sacred Focus replaces the standard Evasion formula entirely with a flat **10+DEX mod+WIS mod** DC while unarmoured/shieldless; a Totem of the Mountain grants a further alternate **13+CON mod** DC. Neither ties to the base Dodge/Brace roll — both are Shaman-specific alternate Evasion DC formulas, not modifiers on top of the existing system.

> [!note] Ranger's Favoured Enemy Evasion bonus — resolved, deep-dive wins
> This page stated Rangers add ~~"Wisdom modifier to Evasion rolls against marked or favoured targets"~~. Ruled: [[Ranger]]'s per-class deep-dive is authoritative over the old summary. Current rule: **advantage** on Evasion rolls against Favoured Enemies (Favoured Enemy Agility), no WIS-mod scaling.

**[[Tattooist]]'s Inkguard** (2nd-level Class Reaction): a genuinely novel Evasion interaction — gaining a bonus to Evasion equal to PB *after* being hit, and if that retroactively raises Evasion above the attack roll, the attack is treated as having missed all along. No other class's reaction converts a confirmed hit into a miss after the fact; every other defensive reaction reduces or prevents damage instead of rewriting the roll's outcome.

**[[Warden]]** (from its own per-class deep-dive): several Prime-Element-conditional Evasion bonuses rather than one fixed formula — Earthen Bulwark's Prime Elemental Shield grants advantage on Evasion vs. ranged attacks/DEX saves; Sentinel's Territorial Claim grants allies in the Claimed Zone +WIS mod to Evasion; the Heroic Boon Unyielding Terrain grants advantage on Evasion vs. melee while stationary. None modify the base Dodge/Brace formula itself — all are situational bonuses layered on top.

## Optional feats (new)

Four Evasion-specific feats exist, distinct from [[Called Shot Feats]] — see [[Evasion Feats]] for the full table. Second independent confirmation (after Called Shot Feats) that FEARS has a real feat system, not just a Called-Shot-specific mechanic.

## See also

- [[Dynamic Combat System (DCS)]]
- [[Damage Reduction]]
- [[FEARS Combat System]]
- [[Momentum]]
- [[Shields]]
- [[Evasion Feats]]
- [[Called Shot Feats]]
- [[Druid]]
- [[Fighter]]
- [[Monk]]
- [[Ranger]]
- [[Rogue]]
- [[Shaman]]
- [[Tattooist]]
- [[Warden]]
- [[FEARS MOC]]
