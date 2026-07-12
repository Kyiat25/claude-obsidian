---
type: entity
title: "Barbarian"
address: c-000060
created: "2026-07-11"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - archetype
  - contradiction
status: developing
mocs:
  - "[[FEARS MOC]]"
entity_type: character-class
role: "archetype"
first_mentioned: "[[Narrative Identity]]"
related:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Damage Reduction]]"
  - "[[Weapon Mastery]]"
  - "[[Reaction Subclass Features]]"
  - "[[Tactical Reactions]]"
  - "[[Initiative System]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Barbarian.md"
confidence: high
---

# Barbarian — Fury Made Flesh

**Martial tier** (no spellcasting). "You are not trained—you are unleashed." The only class that gets stronger as it gets hurt — damage is fuel, not just a threat. Complexity self-rated LOW (2/10) by its own per-class deep-dive — recommended for new players and players who prefer decisive action over complex resource decisions.

> "Battle is not war against an enemy. It is a war against your own limits. The rage simply shows you where they were."

## Signature abilities

- **Rage** — heightened power and resilience
- **Resilient Flow** — maintains momentum even when injured
- **Overwhelming Presence** — forces enemies to deal with you

**Gameplay style**: frontline chaos engine, absorbing pressure and converting it into damage and control.
**Core loop**: take damage → gain power → hit harder → stay standing → repeat. Excels when enemies cluster around them; struggles when fights require patience, distance, or deception.

## Class basics (from Barbarian.md deep-dive)

- **Hit Dice**: 1d12/level. HP at 1st: 12 + CON mod. HP at higher levels: 1d12 (or 7) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium, shields. Weapons — simple, martial. Tools — none. Saves — Strength, Constitution. Skills — choose two from Athletics, Intimidation, Nature, Perception, Skinning, Survival.
- **Starting Equipment**: (a) greataxe or (b) any martial melee weapon; (a) two handaxes or (b) any simple weapon; an explorer's pack and four javelins.
- **Quick Build**: Strength highest, then Constitution. Any lineage works (Orc, Half-Orc, Goliath, Dwarf thematic but not required). Outlander/Soldier or any Athletics/Survival background. Enter Rage immediately, choose a stance, move into the fight and stay there.

## Level progression (1st-20th)

| Level | PB | Features | Rages | Rage Damage |
|---|---|---|---|---|
| 1 | +2 | Rage, Unarmoured Defence, Weapon Mastery | 2 | +2 |
| 2 | +2 | Reckless Attack, Danger Sense | 2 | +2 |
| 3 | +2 | Primal Path, Rage Stances | 3 | +2 |
| 4 | +2 | Ability Score Improvement | 3 | +2 |
| 5 | +3 | Multiattack, Fast Movement | 3 | +2 |
| 6 | +3 | Feral Instinct, Primal Awareness, Primal Path feature | 4 | +2 |
| 7 | +3 | Primal Defiance (Reaction) | 4 | +2 |
| 8 | +3 | Ability Score Improvement | 4 | +2 |
| 9 | +4 | Brutal Critical (1 die) | 4 | +3 |
| 10 | +4 | Heroic Boon | 4 | +3 |
| 11 | +4 | Enhanced Rage, Primal Path feature | 5 | +3 |
| 12 | +4 | Ability Score Improvement | 5 | +3 |
| 13 | +5 | Brutal Critical (2 dice) | 5 | +3 |
| 14 | +5 | Relentless Rage, Primal Path feature | 5 | +3 |
| 15 | +5 | Relentless Fury | 5 | +3 |
| 16 | +5 | Ability Score Improvement | 5 | +4 |
| 17 | +6 | Brutal Critical (3 dice) | 6 | +4 |
| 18 | +6 | Unyielding Might | 6 | +4 |
| 19 | +6 | Ability Score Improvement | 6 | +4 |
| 20 | +6 | Epic Boon | Unlimited | +4 |

## Core class features (full text)

### Rage (1st level)

Bonus action, 1 minute duration. While Raging: advantage on Strength checks and saves; add Rage Damage bonus to melee weapon attacks using Strength; gain Damage Reduction per attack (see contradiction below). Ends early if knocked unconscious or if you neither attack nor take damage since your last turn. Uses per the table above, all regained on a long rest.

**Momentum interactions while Raging** — confirmed, zero drift against [[Momentum]]'s existing "Barbarian exception" section: Resilient Flow (a Major Injury drops MS to −1 instead of resetting to 0), Fury Threshold (starting a turn Raging at −2 MS grants +2 MS immediately), Level 7 Primal Defiance (reaction, reduce a Momentum loss by 1 min 0 and gain +1 MS, PB uses/short rest), Level 11 Enhanced Rage (MS can't drop below 0 while Raging, interacts with Resilient Flow by keeping you at 0 instead of −1).

### Rage DR: resolved — deep-dive wins

> [!note] Two different Rage DR formulas — resolved
> The old DCS-companion source stated: ~~Unarmored DR = Constitution modifier (min 1), doubled while Raging~~.
> Ruled: this per-class deep-dive is authoritative whenever it conflicts with the older summary. Current rule: **Rage grants flat DR per attack — DR 1 at 1st level, DR 2 at 10th level, DR 3 + Constitution modifier (max 5) at 20th level**, no doubling mechanic, not unarmored-specific. See [[Damage Reduction]] for the cross-class picture.

### Unarmoured Defence (1st level)

While not wearing armour: +2 to Evasion Rolls, and may use Constitution modifier instead of Dexterity for Evasion Rolls.

### Weapon Mastery (1st level)

One mastered weapon of choice (simple or martial) — matches [[Weapon Mastery]]'s "most others start with one" rule. Hit with a mastered weapon → apply one Weapon Skill once per turn. **Rage Synergy**: Weapon Skills that deal extra damage (Bleed, Cleave) combine well with Rage Damage. Unlocks new masteries after 1 week of downtime training post-crits: 2 crits for simple weapons, 3 for martial — exactly matches [[Weapon Mastery]]'s "Full Martials" progression table. Confirmed zero drift on both counts.

### Reckless Attack (2nd level)

Advantage on melee Strength attack rolls during your turn; until your next turn, all attack rolls against you also gain advantage.

### Danger Sense (2nd level)

Advantage on Evasion Rolls against visible effects such as traps and spells.

### Primal Path (3rd level, and 6th, 11th, 14th)

Choose a subclass reflecting fighting philosophy and spiritual heritage. Features at 3rd, 6th, 11th, 14th level. See the subclass note below — the source's own example list is illustrative, not exhaustive.

### Rage Stances (3rd level)

Chosen on entering Rage, held until it ends, re-chosen each time: **Fury** (+2 melee damage, +3 at 9th, +4 at 16th), **Endurance** (+1 DR for the Rage's duration — a second, additive DR source on top of the contradiction above), **Predator** (Called Shot attack roll penalty reduced by 1 while Raging — stacks with the arm/leg-penalty-removal in the DCS hook below).

### Multiattack (5th level)

Two attacks whenever you take the Attack action.

### Fast Movement (5th level)

+10 ft speed. On rolling initiative, may move up to half speed as a free action without provoking opportunity attacks.

### Feral Instinct (6th level)

Add Proficiency Bonus to initiative rolls. If surprised, can act normally on the first turn by using a reaction to enter Rage. Ties directly into [[Initiative System]], not previously cross-linked from this page.

### Primal Awareness (6th level)

Advantage on Survival and Nature checks to track creatures or forage. Bonus action: detect hostile creatures (fiends, undead, beasts) within 30 ft — penetrates light cover, not full cover or walls.

### Primal Defiance (7th level, reaction)

When about to lose Momentum from taking damage: unleash a primal roar, reduce the Momentum loss by 1 (min 0), gain +1 Momentum. Usable PB times per short rest.

### Brutal Critical (9th, 13th, 17th level)

Critical hits bypass half the target's DR. +1 extra damage die at 9th, +2 at 13th, +3 at 17th.

### Heroic Boon (10th level)

Choose: **Instant Rage** (auto-enter Rage at combat start, no bonus action) or **Stubborn Rage** (Rage doesn't end except by duration, choice, or unconsciousness).

### Enhanced Rage (11th level)

While Raging, Momentum Score can't be reduced below 0 by any source — a baseline that survives even a Major Injury that would otherwise drop it to −1 under Resilient Flow.

### Relentless Rage (14th level)

Dropping to 0 HP while Raging: DC 10 Constitution save to drop to 1 HP instead. DC increases by 5 per use, resets on a short or long rest.

### Relentless Fury (15th level)

At ≤50% max HP: melee weapon damage dice step up one size (d6→d8, d8→d10). At ≤25%: one additional step (d6→d10, d8→d12). Stacks with Rage Damage and Brutal Critical. Reverts to normal above 50% HP.

### Unyielding Might (18th level)

Treat any Strength or Constitution roll of 9 or lower as a 10. Add Strength score as bonus damage when damaging objects or structures.

### Epic Boon (20th level)

Choose: **Titan's Wrath** (while Raging, melee attacks ignore all DR and deal bonus damage equal to Rage DR; once/long rest, a 30 ft shockwave forces a STR save DC 8+PB+STR or 8d10 force damage + prone, half damage and standing on success, can also clear terrain/break barriers) or **Primal Champion** (+4 STR and CON, max 24 each; unlimited Rage; advantage on checks to move/lift/break obstacles; auto-succeed STR checks DC ≤15).

## Primal Path (subclass) — not a contradiction, an incomplete list

This source names **Path of the Berserker** and **Path of Wild Fury** as illustrative examples ("such as") of a Primal Path subclass. [[Reaction Subclass Features]] already documented **Path of the Bear** and **Path of the Berserker** as Barbarian subclasses (Totemic Resistance and Reckless Counter respectively). Berserker matches across both sources; "Path of Wild Fury" doesn't match "Path of the Bear" — but since this source explicitly says "such as" rather than giving an exhaustive list, Path of the Bear is treated as a third, simply-unmentioned subclass here, not a naming contradiction. Full subclass features for any Path remain undocumented.

## Last Stand (confirmed universal mechanic)

Invoked when the Barbarian would be reduced to 0 HP, rolls a death save, or dies outright — a free action requiring no reaction or consciousness. Once resolved, the character permanently dies with no return possible. Three named options:

| Option | Effect | Best use |
|---|---|---|
| Final Rage | Persistent Rage 1 minute; can't drop below 1 HP; immune to all conditions including exhaustion; ignores non-0-HP-reducing kill effects | Surrounded by enemies |
| Last Laugh | Move + a guaranteed critical hit; target CON saves (DC 10+PB+DEX) or bleeds for 2× character level force damage/turn for 5 minutes (ignores Legendary Resistance) | Against one powerful target |
| Wrath of the World Totem | Allies within 100 ft (5 min): resistance to B/P/S damage, +Rage Damage to their attack/spell damage, +CON mod to their AC | Empowering the whole party |

Confirmed as a universal per-class mechanic (not Barbarian-specific) by [[Bard]]'s deep-dive, which uses near-identical rules for a different class — see [[Last Stand]] for the general framework and the growing per-class table.

## Class Reactions (confirmed universal mechanic)

A shared reaction-use pool separate from the normal action-economy reaction, sized to Proficiency Bonus, refreshing on a short or long rest, capped at 1 use per round; opportunity attacks don't spend it. Three Barbarian-specific reactions, all baseline (not subclass-gated, unlike [[Reaction Subclass Features]]'s two Path-specific reaction upgrades below):

- **Furious Defiance** (2nd) — trigger: hit within 5 ft while Raging; reduce damage by PB, then melee-counterattack.
- **Bloodrush Reprisal** (3rd) — trigger: hit within 5 ft while Raging; attacker CON saves (DC 8+PB+CON) or takes 2d6 weapon damage and is pushed 10 ft (half damage, no push on success); scales +1d6 at 7th/11th/15th/19th.
- **Primal Shockwave** (11th) — trigger: score a critical hit; chosen creatures within 15 ft STR save (DC 8+PB+STR) or knocked prone and take PB×d6 thunder damage.

Confirmed as a universal per-class mechanic by [[Bard]]'s deep-dive — see [[Class Reactions]] for the general framework and the growing per-class table.

## DCS class hook

Advantage on Brace rolls while Raging. Arm and leg Called Shot penalties are removed entirely while Raging (Head stays at −5) — see [[Called Shot Subclass Features]]. (DR formula superseded by the contradiction above — see that section rather than assuming CON-mod-doubled is settled.)

## Initiative hook (from Initiative System)

Lower Focus means higher risk on [[Seize the Moment]] — same tradeoff as [[Fighter]], but a Barbarian's Momentum resilience while Raging can make a failed attempt's Momentum loss less punishing.

## Reaction hook (from Reaction-Based Opportunities)

Two subclass-specific reaction upgrades: Path of the Bear gains resistance to the triggering damage type when using a Tactical Reaction; Path of the Berserker's Raging Counterattacks trade advantage for Reckless Attack rules instead — see [[Reaction Subclass Features]]. Separate from the base-class Level 7 Primal Defiance reaction (Momentum-loss mitigation) and the three baseline Class Reactions above (Furious Defiance, Bloodrush Reprisal, Primal Shockwave), none of which are subclass-gated.

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Dynamic Combat System (DCS)]]
- [[Damage Reduction]]
- [[Weapon Mastery]]
- [[Seize the Moment]]
- [[Reaction Subclass Features]]
- [[Tactical Reactions]]
- [[Initiative System]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
