---
type: entity
title: "Rogue"
address: c-000063
created: "2026-07-11"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - archetype
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
  - "[[Investigator]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Momentum]]"
  - "[[Evasion]]"
  - "[[Called Shot]]"
  - "[[Injury System]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Rogue.md"
confidence: high
---

# Rogue — Precision and Opportunity

**Martial tier** (no spellcasting). "Everyone fights. The Rogue chooses when, where, and whether the fight is worth having at all." A predator, not a warrior — wins by ending fights before they begin rather than enduring them. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive.

> "Everyone fights. The Rogue chooses when, where, and whether the fight is worth having at all."

## Signature abilities

- **Sneak Attack** — massive conditional damage
- **Cunning Action** — constant repositioning
- **Exploit Weakness** — reduces DR and penalties (per [[Class_breakdown]] — see naming-collision note below)

**Gameplay style**: hit-and-run assassin, picking the moment and ending it. **Core loop**: create advantage → strike hard → escape → repeat. Excels in encounters it can set up; struggles in long frontal engagements with no room to reposition.

### Naming collision — still not resolved

[[Class_breakdown]] gave the name "Exploit Weakness" to Rogue, the same name [[Welcome to FEARS]] originally used for [[Investigator]] (whose equivalent [[Class_breakdown]] renamed to "Exploit Vulnerability"). This per-class deep-dive **never uses the term "Exploit Weakness" at all** — Rogue's DR/penalty-reduction effects here are folded directly into Sneak Attack's own DCS Integration bullets (DR Bypass, Called Shot Synergy) rather than named as a separate feature. Doesn't resolve the collision either way — it's simply silent on the name, the same shape of non-answer [[Investigator]]'s own deep-dive gave when it didn't address the cross-class overlap.

## Class basics (from Rogue.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light. Weapons — simple, Finesse martial. Tools — thieves' tools. Saves — Dexterity, Intelligence. Skills — choose four from Acrobatics, Athletics, Crafting, Deception, Insight, Intimidation, Investigation, Memory, Perception, Performance, Persuasion, Sleight of Hand, Stealth, Streetwise.
- **Starting Equipment**: (a) rapier or (b) shortsword; (a) shortbow + 20 arrows or (b) shortsword; (a) burglar's, (b) dungeoneer's, or (c) explorer's pack; leather armour, two daggers, thieves' tools.
- **Quick Build**: Dexterity highest, then Intelligence (Arcane Trickster/Investigation) or Charisma (social builds). Any lineage (Halfling, Drow, Goblin thematic). Outcast/Criminal or a Stealth/Deception background. Position for Sneak Attack each turn; Cunning Action to reposition/hide; save reactions for Uncanny Dodge.

## Level progression (1st-20th)

| Level | PB | Sneak Attack | Features |
|---|---|---|---|
| 1 | +2 | 1d6 | Expertise (2), Sneak Attack, Thieves' Cant, Weapon Mastery |
| 2 | +2 | 1d6 | Cunning Action |
| 3 | +2 | 2d6 | Rogue Subclass, Shadow Reversal (Reaction) |
| 4 | +2 | 2d6 | Improvement |
| 5 | +3 | 3d6 | Uncanny Dodge, Deadly Flourish |
| 6 | +3 | 3d6 | Expertise (4), Evasion |
| 7 | +3 | 4d6 | Subclass Feature |
| 8 | +3 | 4d6 | Improvement |
| 9 | +4 | 5d6 | Reliable Talent, Nerve-Steeled |
| 10 | +4 | 5d6 | Heroic Boon |
| 11 | +4 | 6d6 | Subclass Feature, Sneak Attack Stability |
| 12 | +4 | 6d6 | Improvement |
| 13 | +5 | 7d6 | Precise Critical (1 die), Perfect Shot |
| 14 | +5 | 7d6 | Keensense |
| 15 | +5 | 8d6 | Subclass Feature |
| 16 | +5 | 8d6 | Improvement, Shadow Step |
| 17 | +6 | 9d6 | Precise Critical (2 dice) |
| 18 | +6 | 9d6 | Elusive |
| 19 | +6 | 10d6 | Improvement |
| 20 | +6 | 10d6 | Epic Boon |

## Core class features (full text)

### Expertise (1st level, and 6th)

Choose two skill proficiencies (or one skill + one tool); double PB for those checks. Two more at 6th.

### Sneak Attack (1st level) — new Momentum gain source

Once per turn, extra damage on a Finesse/ranged weapon hit with advantage (or an ally within 5 ft of a non-incapacitated target, without disadvantage). Scales per the table. **DCS Integration**: **DR Bypass** (ignores target DR entirely); **Called Shot Synergy** (a qualifying Called Shot's attack-roll penalty reduced by 2); **Critical Hits** (a critical Sneak Attack doubles all Sneak Attack dice and auto-imposes any Called Shot effect without a save).

**Momentum — Cunning Flow**: landing a Sneak Attack grants **+2 Momentum** instead of the normal +1, once per turn — the same "+2 instead of +1" shape as [[Ranger]]'s Favoured Enemy hits.

### Thieves' Cant (1st level)

Secret rogue language — signs, phrases, jargon, hidden warning/opportunity symbols.

### Weapon Mastery (1st level) — confirms Weapon Mastery System with zero drift

Mastery with one Finesse or ranged weapon of choice; Weapon Skill usable once per turn on a hit, combinable with Sneak Attack on the same hit. New masteries via crits: 2 for simple, 3 for martial — a fifth independent zero-drift confirmation of [[Weapon Mastery]]'s Full Martials row, where Rogue is already listed.

### Cunning Action (2nd level) — genuine exception to the Momentum reset rule

Bonus action: Dash, Disengage, or Hide.

> [!contradiction] Slippery Escape overrides the core Disengage-resets-Momentum rule
> [[Momentum]]'s core rules state plainly: "Disengage/Withdraw action... reset Momentum to 0." Rogue's **Slippery Escape** interaction explicitly states using Cunning Action to Dash, Disengage, or Hide does **not** cost Momentum — and standing up from prone doesn't either. This isn't a vague DCS-summary approximation being corrected; it's a named class feature deliberately carving out an exception to a documented universal reset trigger. Treated as a genuine, confirmed class-specific exception (the same status as [[Barbarian]]'s Rage-based loss exceptions), not a contradiction to silently resolve — the base rule still applies to every class without this feature.

### Rogue Subclass (3rd level, and 7th, 11th, 15th)

Choose an archetype (**Arcane Trickster, Assassin, Thief** named as examples). Features at 3rd/7th/11th/15th — not detailed further here (Assassin's Called Shot interaction is already documented via [[Called Shot Subclass Features]]).

### Uncanny Dodge (5th level, reaction)

On being hit by a visible attacker: halve the damage.

### Deadly Flourish (5th level)

On a critical hit, choose one: **Disarm** (target drops a held item), **Off-Balance** (disadvantage on the target's next attack), or **Hemorrhage** (+1d6 weapon-type damage at the start of the target's next turn). Applies alongside any Injury the crit causes, not instead of it.

### Evasion (6th level) — naming collision with the FEARS Evasion mechanic

On an effect allowing a DEX save for half damage: no damage on success, half on failure. **This is the classic D&D-legacy "Evasion" ability** (a save-outcome modifier), an entirely different mechanic from FEARS's own [[Evasion]] system (the Dodge/Brace defense roll that replaces AC). The two share a name only by coincidence of terminology inherited from 5E — not the same feature, not cross-referenced as such anywhere in this source.

### Reliable Talent (9th level)

Proficient ability checks treat a rolled 9 or lower as a 10.

### Nerve-Steeled (9th level) — new Injury/Momentum interaction

The first Minor Injury suffered between long rests doesn't impose its normal Momentum penalty (other Injury effects still apply). A once-per-long-rest, universal-condition version of the kind of Injury-Momentum carve-out [[Barbarian]]'s Resilient Flow does only while Raging.

### Heroic Boon (10th level)

Choose: **Deadly Precision** (reroll 1s/2s on Sneak Attack damage dice; a critical hit lets a reaction add one more weapon attack against the same target, can itself benefit from unused Sneak Attack) or **Shadow Dancer** (Cunning Action's Dash/Disengage/Hide each grant a bonus effect until the Rogue's next turn — no-OA movement, +2 AC, or advantage on the next attack respectively; Uncanny Dodge also grants a free 10 ft move without provoking).

### Sneak Attack Stability (11th level) — third self-directed Momentum-loss mitigation

Landing Sneak Attack damage reduces any Momentum loss the Rogue would suffer before their next turn by 1 (min 0) — the third confirmed self-directed version of this exact shape, after [[Magus]]'s Adaptive Mind (the ally-directed originals are [[Cleric]]'s and [[Paladin]]'s shared Ward of Faith).

### Precise Critical (13th level, and 17th)

Crits on 19–20 with ranged/Finesse weapons; +1 extra weapon damage die on crits (+2 dice at 17th).

### Perfect Shot (13th level) — new Called Shot access route

Once per long rest, a Called Shot with **no attack-roll penalty at all**; if it qualifies for Sneak Attack, automatically deals maximum (non-rolled) Sneak Attack damage in addition to normal weapon damage. A different shape from every other class's penalty-reduction hooks — a full penalty waiver rather than a scaled reduction, but gated to once per long rest rather than once per turn.

### Keensense (14th level)

Keensense 10 ft — detects invisible/hidden creatures nearby if the Rogue can hear.

### Shadow Step (16th level)

Bonus action: teleport up to 60 ft to a visible unoccupied dim-light/darkness space, no OA provoked; next attack this turn has advantage + 2d6 damage. Uses = PB per long rest.

### Elusive (18th level)

While not incapacitated: disadvantage on all attacks against the Rogue if they can see the attacker. Reaction on a missed melee attack: **Riposte** (one melee attack against the attacker) or **Fade** (Disengage + move half speed without provoking from that attacker).

### Epic Boon (20th level)

Choose: **Stroke of Luck (Enhanced)** (a miss against a Sneak-Attack-qualifying target becomes a critical hit, or a failed check/save is treated as a natural 20; uses = half DEX mod per long rest) or **Master of Shadows** (bonus action invisibility until next turn, ends on attack/cast, uses = DEX mod per short or long rest; hitting with advantage once/short rest deals max Sneak Attack damage; untrackable by nonmagical means; advantage on initiative).

## Last Stand (confirmed universal, 16th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Shadow's Requiem | Invisible, move up to speed; melee attacks against DEX-mod (min 1) enemies auto-hit and auto-crit; Surprised/Unaware targets also take Sneak Attack damage; dissolves into shadow, no trace left |
| Escape Plan | Up to 5 willing allies within 60 ft teleport with the Rogue to a past long-rest location (or nearest safe spot); allies gain advantage on DEX saves/Stealth for 5 minutes |
| Death's Whisper | All enemies within 100 ft WIS save (DC 10+PB+DEX) or frightened of the Rogue's allies for 5 minutes + psychic damage = Sneak Attack damage each turn within 30 ft of allies; enemies can't regain HP within 30 ft of the Rogue's spectral form for 5 minutes |

Sixteenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). DC corrected to the canonical `10+PB+DEX` — the original `12+PB+DEX` in this document was a transcription error, ruled and resolved on [[Last Stand]].

## Class Reactions (confirmed universal, 16th class — clean shared-pool confirmation)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest, no stated exceptions.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Cunning Dodge | 2nd | Hit by a visible attack | Reduce damage by 1d6+DEX mod; move 10 ft without provoking |
| Shadow Slip | 3rd | A creature within 5 ft misses the Rogue | Gain +1 Momentum, or immediately Hide |
| Shadow Reversal | 3rd | Targeted by a visible attack | DEX (Stealth) contested by enemy Perception; success makes the attack miss and grants a 10 ft move without provoking |
| Killing Opportunity | 11th | An ally within 30 ft hits a creature | If the target is within Sneak Attack range, make one weapon attack against it as part of the reaction |

Shadow Slip's +1 Momentum on an enemy's miss is a new gain-trigger shape — self-benefit from an *opponent's* failure, distinct from every prior "attacker loses Momentum" hook (Cleric, Bard, Inventor) which penalized the enemy rather than rewarding the Rogue directly.

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Investigator]]
- [[Dynamic Combat System (DCS)]]
- [[Seize the Moment]]
- [[Reaction Subclass Features]]
- [[Momentum]]
- [[Evasion]]
- [[Called Shot]]
- [[Injury System]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
