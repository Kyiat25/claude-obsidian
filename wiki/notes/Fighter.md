---
type: entity
title: "Fighter"
address: c-000061
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
  - "[[Weapon Mastery]]"
  - "[[Momentum]]"
  - "[[Called Shot]]"
  - "[[Evasion]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Weapon Mastery System]]"
  - ".raw/Fighter.md"
confidence: high
---

# Fighter — Master of the Battlefield

**Martial tier** (no spellcasting). "Everyone else has a plan. The Fighter has trained for the moment when the plan stops working." Has the highest **decision density** of any class — wins through choices, not raw power. Complexity self-rated LOW (2/10) by its own per-class deep-dive, the lowest of any class ingested this session — deliberately built for new players and anyone wanting reliable, effective combat without complex resource pools.

> "Everyone else has a plan. The Fighter has trained for the moment when the plan stops working."

## Signature abilities

- **Martial Actions** — advanced combat options
- **Weapon Mastery** — deep weapon specialisation
- **Action Surge** — breaks the action economy

**Gameplay style**: tactical control, always having an answer and the tools to execute it. **Core loop**: assess → choose optimal action → reposition/control → repeat.

## Class basics (from Fighter.md deep-dive)

- **Hit Dice**: 1d10/level. HP at 1st: 10 + CON mod. HP at higher levels: 1d10 (or 6) + CON mod/level after 1st.
- **Proficiencies**: Armour — all armour and shields. Weapons — simple, martial. Tools — none. Saves — Strength, Constitution. Skills — choose two from Acrobatics, Animal Handling, Athletics, Crafting, History, Insight, Intimidation, Perception, Resolve, Survival.
- **Starting Equipment**: (a) chain mail or (b) leather armour + longbow + 20 arrows; (a) martial weapon + shield or (b) two martial weapons; (a) light crossbow + 20 bolts or (b) two handaxes; (a) dungeoneer's pack or (b) explorer's pack.
- **Quick Build**: Strength or Dexterity highest, then Constitution. Any lineage (Human, Hobgoblin, Dwarf thematic). Soldier/Guard or an Athletics/Intimidation background. Choose a Fighting Style, pick two Martial Actions suited to your weapon, use Action Surge when it counts.

## Level progression (1st-20th)

| Level | PB | Features | Martial Actions Known | Action Surges |
|---|---|---|---|---|
| 1 | +2 | Rush of Adrenaline, Martial Action, Weapon Mastery | 2 | — |
| 2 | +2 | Action Surge, Fighting Style | 2 | 1 |
| 3 | +2 | Fighter Subclass, Weapon Mastery (Full) | 2 | 1 |
| 4 | +2 | Improvement, Martial Versatility | 3 | 1 |
| 5 | +3 | Multiattack (2), Surgical Precision | 3 | 1 |
| 6 | +3 | Improvement | 3 | 1 |
| 7 | +3 | Subclass Feature | 3 | 1 |
| 8 | +3 | Improvement, Battlefield Awareness | 4 | 1 |
| 9 | +4 | Multiattack (3) | 4 | 1 |
| 10 | +4 | Heroic Boon | 4 | 1 |
| 11 | +4 | Subclass Feature, Tactical Masterstroke (Reaction) | 4 | 1 |
| 12 | +4 | Improvement | 5 | 1 |
| 13 | +5 | Action Surge (2/rest) | 5 | 2 |
| 14 | +5 | Improvement | 5 | 2 |
| 15 | +5 | Subclass Feature | 5 | 2 |
| 16 | +5 | Improvement | 6 | 2 |
| 17 | +6 | Multiattack (4) | 6 | 2 |
| 18 | +6 | Master Combatant, Legendary Weaponmaster | 6 | 3 |
| 19 | +6 | Improvement | 6 | 3 |
| 20 | +6 | Epic Boon | 7 | 3 |

## Core class features (full text)

### Rush of Adrenaline (1st level) — Momentum reset, second confirmed instance

When damage would drop the Fighter below half max HP: reaction, spend up to PB hit dice, roll them, regain that total + CON modifier as HP. **Momentum immediately resets to +1 (unless already higher).** The second confirmed case of a class ability resetting Momentum to a specific nonzero value rather than a plain gain/loss/zero-reset — after [[Druid]]'s Wild Shape entry. Not a coincidence limited to one class; see [[Momentum]] for the updated framing.

### Martial Action (1st level)

Bonus action each turn to perform one Martial Action; starts knowing two, gains more at higher levels (table above). Full list: **Aim** (double PB on next ranged attack), **Guard** (disadvantage on next attack against self/adjacent ally), **Quick Strike** (two extra light-melee attacks as bonus action), **Wind Up** (extra damage = PB on next heavy/versatile attack), **Feint** (advantage on next attack within 5 ft), **Press the Advantage** (move 10 ft without provoking + extra melee attack after a hit), **Suppressive Fire** (disadvantage on target's attacks until next turn).

### Weapon Mastery (1st level, and 3rd level) — confirms Weapon Mastery System with zero drift

At 1st: mastery with one martial + one simple weapon; a mastered weapon's Weapon Skill usable once per turn on a hit. At 3rd: three additional masteries (four total); Weapon Skills usable **once per action type** — Attack Action, Bonus Action (if the skill has one), Reaction (if applicable), and Action Surge — never the same skill twice in a round. Fastest mastery unlock of any class (1 crit per weapon, any type), no cap on total masteries. This exactly confirms [[Weapon Mastery]]'s existing "Fighter exception: multi-mastery rounds" section and its 1-crit progression entry — zero drift between the two independent sources.

### Action Surge (2nd level) — Momentum gain, confirmed clean

One additional action on the Fighter's turn; once per rest until 13th level (2/rest) and 18th level (3/rest, once per turn each). **Using it grants +1 Momentum immediately regardless of whether the resulting attacks land** — the cleanest, least-conditional Momentum-gain trigger of any class seen so far (every other class's gain sources depend on a roll succeeding).

### Fighting Style (2nd level, and 13th, 18th)

Choose one (may add another at 13th/18th, replaceable via Martial Versatility): **Archery** (+2 ranged attack rolls), **Blind Fighting** (Blindsight 10 ft), **Agile Defence** (DEX mod added to Evasion regardless of armour type — see [[Evasion]]), **Armoured Defence** (layer armour without penalty), **Dueling** (+2 damage with a one-handed weapon and no other weapon/shield; Evasion rolled with advantage once/turn), **Great Weapon Fighting** (reroll 1s/2s on two-handed/versatile damage dice), **Interception** (reaction: reduce an ally's damage by 1d10+PB), **Protection** (reaction: disadvantage on attacks against an adjacent ally, requires shield), **Shield Master** (shield's bonus added to Evasion — see [[Evasion]]), **Two-Weapon Fighting** (ability mod added to second attack's damage), **Unarmed Fighting** (unarmed strikes 1d6+STR, d8 without weapon/shield).

### Improvement (4th, 6th, 8th, 12th, 14th, 16th, 19th level)

Choose: +2 to one ability score, +1 to two ability scores, or +1 to one ability score plus a martial talent.

### Martial Versatility (4th level)

On gaining an Improvement, may swap one Fighting Style or Martial Action for another.

### Multiattack (5th level)

Two attacks on the Attack action; three at 9th, four at 17th.

### Surgical Precision (5th level) — new Called Shot access route

Once per turn on a Called Shot attempt: reduce the attack-roll penalty by PB. At 5th level (PB +3), an arm Called Shot (normally −2) becomes a **+1 bonus** to hit. The first class hook that can flip a Called Shot penalty into a net bonus rather than merely softening it.

### Battlefield Awareness (8th level)

+3 to initiative rolls. Opportunity attacks against the Fighter have disadvantage. Reaction: impose disadvantage on an attack targeting an ally within 10 ft.

### Heroic Boon (10th level)

Choose: **Boon of Indomitable Will** (once/short rest, reroll a failed save against a condition; once/long rest, dropping to 0 HP instead drops to 1) or **Boon of Tactical Superiority** (bonus action: grant an ally within 30 ft advantage on their next attack/save; when the Fighter attacks with advantage, +2d6 damage).

### Master Combatant (18th level)

Action Surge grants **two** additional actions instead of one. Once per round, reaction: make an attack or perform any action-requiring action (Dodge, Disengage, Help).

### Legendary Weaponmaster (18th level)

All proficient weapons treated as mastered; Weapon Skills usable from any wielded weapon. Critical hits apply two Weapon Skills (both from that weapon) instead of one.

### Epic Boon (20th level)

Choose: **Boon of the Warlord** (once/long rest, action: allies within 30 ft gain an additional attack action on their next turn for 1 minute; allies within 30 ft get +2 AC and saves while the Fighter is conscious) or **Boon of Unbreakable Valour** (resistance to all damage below half max HP; once/short rest, an attack that would reduce the Fighter to 0 HP instead drops them to 1 HP with an immediate counterattack).

## Last Stand (confirmed universal, 8th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Die by the Sword | Move up to speed; make **four times** the normal Attack Action's attacks; immune to any effect stopping movement, preventing attacks, or reducing damage |
| Finest Hour | Allies within 100 ft at 0 HP healed to 1 HP; all allies within 100 ft gain temp HP = 4× Fighter level for 5 minutes; grants Second Wind to all allies in range (5 minutes) |
| Warlord's Contingency | Grants Action Surge to all allies within 100 ft for 5 minutes; using it also ends one save-ending effect on the ally |

Eighth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

## Class Reactions (confirmed universal, 8th class — clean shared-pool confirmation)

Explicitly draws from the **Proficiency Bonus pool**, refreshing on short or long rest — a clean, unqualified confirmation of the shared-pool default, unlike [[Cleric]]'s partial exception or [[Druid]]'s total departure from it.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Defensive Counter | 2nd | A creature makes a melee attack against the Fighter | Miss: one melee attack, weapon damage + PB + STR/DEX mod on hit. Hit: reduce damage by PB, then make one melee attack |
| Guarded Riposte | 3rd | A creature makes a melee attack against the Fighter | Miss: one weapon attack with advantage, +PB+ability mod damage on hit, target disadvantaged on its next attack. Hit: one weapon attack, +PB damage on hit, target disadvantaged on its next attack |
| Tactical Masterstroke | 11th | An ally within 30 ft misses an attack | Grant a reroll with advantage; if it still misses, the Fighter may make one weapon attack against the same target |

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Dynamic Combat System (DCS)]]
- [[Weapon Mastery]]
- [[Momentum]]
- [[Called Shot]]
- [[Evasion]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Seize the Moment]]
- [[Reaction Subclass Features]]
- [[FEARS MOC]]
