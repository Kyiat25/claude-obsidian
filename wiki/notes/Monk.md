---
type: entity
title: "Monk"
address: c-000062
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
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Evasion]]"
  - "[[Weapon Mastery]]"
  - "[[Bender]]"
  - "[[Damage Reduction]]"
  - "[[Momentum]]"
  - "[[Called Shot]]"
  - "[[Injury System]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Evasion]]"
  - "[[Weapon Mastery System]]"
  - ".raw/Monk.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Monk — Perfect Motion

**Martial tier** (no spellcasting). "The strike that ends the fight is not the fastest or the hardest. It is the one that arrives exactly when the enemy has nothing left to counter it." A mobility and disruption specialist — breaks the enemy's combat rhythm and presses the disrupted state harder than any other class. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive.

> "The strike that ends the fight is not the fastest or the hardest. It is the one that arrives exactly when the enemy has nothing left to counter it."

## Signature abilities

- **Ki Techniques** — control, mobility, disruption
- **Pressure Points** — disable enemies
- **Flow State** — reward for maintaining rhythm

**Gameplay style**: high-mobility disruptor, deciding who gets to act and who doesn't. **Core loop**: move → strike → disrupt → reposition → repeat. Struggles with sustained ranged pressure and closing the gap; excels choosing the angle of engagement and staying mobile. Against bloodied targets, costs drop, effects extend, and damage surges — a consistent thread through nearly every feature below.

## Class basics (from Monk.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — none. Weapons — simple, shortswords (treated as monk weapons). Tools — one artisan's tool of choice. Saves — Dexterity, Focus (a second confirmed Focus-as-saving-throw class after [[Inventor]]). Skills — choose two from Acrobatics, Athletics, Insight, Memory, Perception, Religion, Resolve, Stealth.
- **Starting Equipment**: (a) any simple weapon or (b) a shortsword; (a) dungeoneer's pack or (b) explorer's pack; 10 darts.
- **Quick Build**: Dexterity highest, then Wisdom. Any lineage (Human, Tiefling, Elf thematic). Hermit/Far Traveller or an Acrobatics/Insight background. Flurry of Blows to build pressure; Patient Defence against bloodied attackers; Stunning Strike to break momentum at critical moments.

## Level progression (1st-20th)

| Level | PB | Martial Arts | Technique Points | Unarmoured Movement | Features |
|---|---|---|---|---|---|
| 1 | +2 | 1d6 | — | — | Martial Arts, Unarmoured Defence, Ki-Empowered Strikes |
| 2 | +2 | 1d6 | 3 | +10 ft | Techniques, Unarmoured Movement, Ki Sense, Ki Flow, Class Reactions |
| 3 | +2 | 1d6 | 5 | +10 ft | Monastery Subclass, Unarmoured Resilience (DR 1) |
| 4 | +2 | 1d6 | 5 | +10 ft | Improvement |
| 5 | +3 | 1d8 | 6 | +15 ft | Multiattack, Stunning Strike |
| 6 | +3 | 1d8 | 7 | +15 ft | Empowered Strikes, Improved Flurry, Evasion |
| 7 | +3 | 1d8 | 8 | +15 ft | Subclass Feature, Ki Flow (turn-start) |
| 8 | +3 | 1d8 | 9 | +15 ft | Improvement |
| 9 | +4 | 1d8 | 9 | +20 ft | Perfect Motion, Unarmoured Resilience (DR 2), Ki Flow Disruption |
| 10 | +4 | 1d8 | 10 | +20 ft | Heroic Boon |
| 11 | +4 | 1d8 | 11 | +20 ft | Subclass Feature, Perfect Counter (Reaction) |
| 12 | +4 | 1d10 | 12 | +20 ft | Improvement |
| 13 | +5 | 1d10 | 13 | +25 ft | Astral Teachings, Meridian Strike, Serene Focus |
| 14 | +5 | 1d10 | 14 | +25 ft | Diamond Soul |
| 15 | +5 | 1d10 | — | +25 ft | Subclass Feature, Deadeye Strike, Unarmoured Resilience (DR 3) |
| 16 | +5 | 1d10 | — | +25 ft | Improvement |
| 17 | +6 | 1d10 | — | +30 ft | Timeless Self |
| 18 | +6 | 1d10 | — | +30 ft | Empty Body |
| 19 | +6 | 1d12 | — | +30 ft | Improvement |
| 20 | +6 | 1d12 | — | +30 ft | Epic Boon |

Technique Points become unlimited from 15th level onward (regenerate automatically).

## Core class features (full text)

### Martial Arts (1st level)

While unarmed or wielding only monk weapons and unarmoured/shieldless: unarmed strikes use the Martial Arts die instead of normal damage; Dexterity replaces Strength for unarmed/monk-weapon attack and damage rolls; **Deflect Missiles** (reaction on being hit by a ranged attack) reduces damage by `1d10 + DEX mod + WIS mod + Monk level` — the first exact formula for this ability, reduced to 0 lets the Monk catch and throw it back (PB on the attack roll, range 20/60, counts as a monk weapon); **Bonus Attack** grants one extra unarmed strike as a bonus action on the Attack action.

**Balanced Rhythm** (Momentum): ignores the −1 Momentum penalty from missed attacks (Nat 1's −2 still applies) — confirms [[Momentum]]'s existing Monk exception with zero drift.

### Unarmoured Defence (1st level) — new Evasion formula

While unarmoured/shieldless: add **Wisdom modifier** to all Evasion rolls. The first confirmed Monk-specific Evasion bonus formula — see [[Evasion]].

### Ki-Empowered Strikes (1st level)

Hitting a bloodied creature with an unarmed strike: bonus damage = Martial Arts die; if the target has temp HP, halve it first (reduce by 2× Martial Arts die before dealing damage); counts as granting Sneak Attack advantage if multiclassed. At 10th level, attacks against bloodied creatures crit on 19–20; at 17th, on 18–20.

### Monk Techniques (2nd level) — ninth confirmed DC formula, second non-caster

Technique Points fuel manoeuvres: pool = Monk level, replenishes on short or long rest (30 min meditation). **Technique Save DC = 8 + PB + Wisdom modifier** — ninth independent confirmation of the `8+PB+ability mod` formula, and the second confirmed on a non-caster class after [[Investigator]]'s Death Throes Denial.

**Techniques**: **Flurry of Blows** (1 TP: two bonus-action unarmed strikes after the Attack action; three against bloodied targets plus cumulative −10 ft speed per hit; free once/short rest against bloodied targets at 13th), **Patient Defence** (1 TP: Dodge as a bonus action; against bloodied targets, spend 1 TP with no extra reaction to strike with advantage when Dodge-disadvantage causes a miss — can trigger Stunning Strike free), **Step of the Wind** (1 TP: Disengage/Dash as a bonus action, double jump distance; against bloodied targets, +15 ft movement and a 15 ft teleport through disrupted Ki), **Ki-Fueled Agility** (1 TP: reroll a failed Evasion roll).

### Unarmoured Movement (2nd level)

+10 ft movement while unarmoured/shieldless, scaling per the table (up to +30 ft at 17th).

### Ki Sense (2nd level)

Senses any creature within range becoming bloodied, no action required, through walls/darkness/invisibility (general direction + approximate distance). Range: 30 ft base, 60 ft at 6th, 90 ft at 11th, 120 ft at 17th. Hitting a creature with an unarmed strike reveals whether it's above or below 50% HP.

### Ki Flow (2nd level, and 7th) — possible overlap with Weapon Mastery's Flow Strike, not resolved

At 2nd: beginning a turn at maximum Momentum (+3) regains 1 Technique Point, once per round. At 7th: beginning a turn at +2 or higher regains 1 TP, once per turn. **This document never mentions "Flow Strike"** — the on-hit, +3-Momentum-triggered TP regeneration ability that [[Weapon Mastery]] describes as shared identically between Monk and [[Bender]]. Ki Flow is turn-start-triggered rather than hit-triggered, so the two are not obviously the same mechanic under different names, but both link Technique Point income to a high-Momentum state. Not resolved as contradiction or confirmation — flagged as an open question on [[Weapon Mastery]] and [[FEARS MOC]], the same shape as the earlier Bender/Technique-Point silence.

### Monastery Subclass (3rd level, and 7th, 11th, 15th)

Choose a subclass reflecting martial/spiritual tradition (examples: **Flickering Dark**, **Open Hand**). Features at 3rd/7th/11th/15th — not detailed further here.

### Unarmoured Resilience (3rd level, and 9th, 15th) — contradicts Damage Reduction's existing formula

While unarmoured/shieldless: **DR 1** at 3rd, **DR 2** at 9th, **DR 3** at 15th — a flat, level-gated progression applied before Injury threshold calculations.

> [!note] Conflicts with the old Damage Reduction claim — resolved, deep-dive wins
> The old [[Damage Reduction]] claim stated Monk unarmoured DR = ~~"½ Dexterity modifier; may spend a Technique Point for +2 DR to all locations"~~. Ruled: this per-class deep-dive is authoritative. Current rule: the flat level-gated formula above (1/2/3 DR at 3rd/9th/15th), no DEX-mod scaling, no TP-spend option.

### Multiattack (5th level)

Two attacks instead of one on the Attack action.

### Stunning Strike (5th level)

On an unarmed-strike hit, spend 1 TP: target CON saves (DC = Technique Save DC) or stunned until end of the Monk's next turn. **Against bloodied targets**: costs 0 TP, DC +2, failure stuns for 2 rounds, even a success imposes disadvantage on the target's next attack. At 13th level, affects normally-stun-immune bloodied creatures (they save with advantage instead of being immune); at 17th, bloodied targets below 25% HP save at disadvantage.

### Empowered Strikes (6th level)

Unarmed strikes count as magical (bypass nonmagical resistance/immunity). Against constructs/undead, +Martial Arts die force damage. Against bloodied creatures, +1d10 force damage.

### Improved Flurry of Blows (6th level)

Flurry of Blows' second strike crits on 19–20.

### Perfect Motion (9th level)

**Fall Resistance** (reaction: reduce falling damage by 5×Monk level), **Fluid Movement** (move on vertical surfaces/across liquids without falling, on the Monk's turn), **Liquid Grace** (once/short rest, ignore difficult terrain and move through enemy spaces without provoking).

### Ki Flow Disruption (9th level)

Reaction, spend 1 TP: when a bloodied creature within Ki Sense range moves, force a CON save (DC = Technique Save DC) — failure drops its speed to 0 for the rest of its turn, success halves it. Works even against Dash/Disengage.

### Heroic Boon (10th level)

Choose: **Purity of Body** (immune to disease/poison; dropping to 0 HP while bloodied creatures are within Ki Sense range immediately regains HP = remaining TP + 5×bloodied-creatures-in-range, once/long rest) or **Purity of Mind** (advantage on WIS saves; bonus action ends charmed/frightened on self; senses the emotional state of bloodied creatures in Ki Sense range).

### Astral Teachings (13th level)

Spend 2 TP for temporary proficiency (language/skill/tool/weapon) until incapacitated or reused; spend 3 TP to grant an ally within 30 ft the same for 1 hour.

### Meridian Strike (13th level)

3 TP, part of an Attack action against a bloodied creature: unarmed strike with advantage; on hit, CON save (DC = Technique Save DC + 2) — failure lets the Monk choose two of Ki Seal (no legendary actions/reactions until Monk's next turn), Meridian Lock (speed 0 until Monk's next turn), Vital Disruption (disadvantage on attacks until Monk's next turn), Energy Drain (lose one recharged ability use); success applies one chosen effect. Automatically fails if the target is bloodied and stunned.

### Serene Focus (13th level) — sixth Injury class hook, a new shape

Once per short rest, suffering a Minor Injury: ignore all its effects until the end of the next long rest. **The injury itself remains and must still be healed normally** — the sixth distinct [[Injury System]] class hook, and the first that suppresses effects without downgrading a tier (Paladin/Bard/Cleric) or removing the injury outright (Apothecary).

### Diamond Soul (14th level)

Proficiency in all saving throws. Spend 1 TP to reroll a failed save +1d4. Against bloodied attackers, automatic +1d4 to saves (no TP cost); succeeding against a bloodied creature's ability can reflect the effect back at them (same save required).

### Deadeye Strike (15th level) — new Called Shot access route

Once per turn on a Called Shot: reduce the penalty by DEX modifier (minimum reduction of 1) — the same access-route shape as [[Fighter]]'s Surgical Precision and [[Investigator]]'s Forensic Called Shot, but scaled by DEX mod rather than PB.

### Timeless Self (17th level)

No longer ages, needs food/water, or suffers magical-aging penalties. Ability scores and max HP can't be reduced short of *wish*.

### Empty Body (18th level)

Spend 4 TP: invisible 1 minute, resistance to all damage except force; attacks while invisible +1d10 force damage. Against bloodied creatures while invisible: force damage doubles to 2d10, immune to magical detection, Ki Sense extends to 240 ft. Alternatively, 8 TP casts *astral projection* (self only) without components.

### Epic Boon (20th level)

Choose: **Boundless Technique** (regain all TP on rolling initiative; starting a turn at 0 TP regains 2 automatically at +3 Momentum; if any creature is already bloodied at initiative, gain +4 temporary TP usable only against bloodied creatures, can exceed max) or **Enlightened Mastery** (once/turn use a Technique for free; Flurry of Blows becomes three strikes; rolling initiative with <4 TP regains half Monk level rounded up; reducing a bloodied creature to 0 HP regains 2 TP, can trigger multiple times per turn).

## Last Stand (confirmed universal, 12th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Empty Sun Technique | Move up to speed; two critical hits to one target in melee range; target WIS saves (DC 10+PB+WIS) or is placed under *imprisonment* (Slumber effect, the Monk's dead body is the focus, cannot be removed/dispelled); no Legendary Resistance |
| Into the Mist | Physical form evaporates; allies within 100 ft may teleport to any location they long-rested at in the past week, or short-rested at (DC 15 CON save); enemies can't interfere |
| Transcendence | Invincible spectral image for 5 minutes; enemies within 10 ft have disadvantage, allies within 10 ft have advantage on all d20 rolls; fly 50 ft, pass through barriers; telepathy within 100 ft |

Twelfth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

## Class Reactions (confirmed universal, 12th class — corrected to the shared PB pool)

> [!note] Header/mechanics mismatch — resolved
> The source's own header claims these reactions "use your Proficiency Bonus pool, refreshing on short or long rest," with a note that Monk reactions "cost Focus rather than PB uses in some cases." In practice, all three reactions were originally written as costing only Focus, with no PB use mentioned anywhere. Ruled: the header is correct — these reactions draw from the shared PB pool like every other class. Corrected below (Focus costs replaced with pool uses).

| Reaction | Level | Trigger | Effect | Pool cost |
|---|---|---|---|---|
| Fluid Reversal | 2nd | A creature within 5 ft makes a melee attack | Miss: unarmed strike with advantage, DEX save (DC = Technique Save DC) or prone on hit. Hit: reduce damage by Martial Arts die + WIS mod, then unarmed strike. Against bloodied attackers: DC +2, failed save also stuns, free (no pool use) | 1 shared PB pool use |
| Flowing Reversal | 3rd | A creature enters reach or melee-attacks | Unarmed strike; on hit, STR save (DC = Technique Save DC) or prone/pushed 10 ft (Monk's choice); move 10 ft without provoking if triggered by reach-entry. Against bloodied: push 20 ft, failed save also −10 ft speed for 1 minute + disadvantage standing up | 1 shared PB pool use |
| Perfect Counter | 11th | Evasion roll beats a melee/ranged attack by 5+ | Teleport adjacent to the attacker, two unarmed strikes with advantage; both hit: 1 more pool use stuns until Monk's next turn. Against bloodied: free (no pool use), auto-crit below 25% HP, Stunning Strike usable without extra TP | 1 shared PB pool use (+1 to stun) |

## Mythology & Cultural Lore (from the Class Lore Compendium)

*"Body-Masters: Those Who Perfect the Self."* Monks emerged from a simple observation — mortals are born weak but can become strong without limit. The **Ascetic Rebellion** (First Age) terrified religious authorities: monks demonstrating water-walking, stone-breaking bare hands, and surviving without food, proving enlightenment required neither gods nor glyphs. The Faith of the Bound Pattern couldn't integrate monks — they refuse divine authority, use no glyphs, sit entirely outside the Thread system — so it simply buried them: monasteries "closed," masters "retired." It didn't work, because monastic knowledge is embodied in muscle memory and breath control, not books that can be burned.

**Source of Power (DM truth):** What monks call "ki" is their own interpretation of the [[Personal Glyphs]] — the Fundamental Force governing individual will and self-determination. Physical discipline lets a monk rewrite their own personal reality, editing their own source code through the body itself. Master monks don't transcend mortality; they redefine what "mortal" means.

**Philosophy**, from "The Manual of Self-Perfection": *"The wizard says: study glyphs, cast spells, reshape reality. The cleric says: pray to gods... We say: become. Not become something. Just become... My body is weapon. My breath is spell. My discipline is armor. I need nothing external because everything necessary exists within."*

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Dynamic Combat System (DCS)]]
- [[Weapon Mastery]]
- [[Bender]]
- [[Seize the Moment]]
- [[Damage Reduction]]
- [[Evasion]]
- [[Momentum]]
- [[Called Shot]]
- [[Injury System]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
