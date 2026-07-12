---
type: entity
title: "Paladin"
address: c-000065
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
  - "[[Injury System]]"
  - "[[Momentum]]"
  - "[[Called Shot]]"
  - "[[Damage Reduction]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
  - "[[Cleric]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Injury System]]"
  - ".raw/Paladin.md"
confidence: high
---

# Paladin — Oath Made Steel

**Half-Caster tier**. "The oath is not a promise to a god. It is a promise to everyone behind you." A tank, healer, and burst striker often simultaneously — most powerful at the centre of a fight, absorbing pressure and redirecting it as radiant judgment. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive.

> "The oath is not a promise to a god. It is a promise to everyone behind you."

## Signature abilities

- **Divine Smite** — burst damage
- **Auras** — protect allies
- **Lay on Hands** — sustain

**Gameplay style**: frontline leader, protecting and enduring, striking when it matters. **Core loop**: hold → choose moment → smite → reset. Struggles at range and in mobility-rewarding fights; excels getting in, staying in, and protecting the people behind them.

## Class basics (from Paladin.md deep-dive)

- **Hit Dice**: 1d10/level. HP at 1st: 10 + CON mod. HP at higher levels: 1d10 (or 6) + CON mod/level after 1st.
- **Proficiencies**: Armour — all armour, shields. Weapons — simple, martial. Tools — none. Saves — Wisdom, Charisma. Skills — choose two from Athletics, Insight, Intimidation, Medicine, Persuasion, Religion, Resolve.
- **Starting Equipment**: (a) martial weapon + shield or (b) two martial weapons; (a) five javelins or (b) any simple melee weapon; (a) priest's pack or (b) explorer's pack; chain mail and a holy symbol.
- **Quick Build**: Strength highest, then Charisma. Any lineage (Human, Aasimar, Dragonborn thematic). Noble/Soldier or a Persuasion/Religion background. Position between enemies and fragile allies; Divine Smite on hits that matter; use Lay on Hands proactively rather than reactively when possible.

## Level progression (1st-20th)

| Level | PB | Features | Spells Known | 1st | 2nd | 3rd | 4th | 5th |
|---|---|---|---|---|---|---|---|---|
| 1 | +2 | Divine Sense, Lay on Hands, Weapon Mastery | — | — | — | — | — | — |
| 2 | +2 | Divine Smite, Martial Action, Fighting Style, Spellcasting | 2 | 2 | — | — | — | — |
| 3 | +2 | Paladin Subclass, Holy Precision | 3 | 3 | — | — | — | — |
| 4 | +2 | Improvement | 3 | 4 | — | — | — | — |
| 5 | +3 | Multiattack | 4 | 4 | 2 | — | — | — |
| 6 | +3 | Aura of Protection | 4 | 4 | 3 | — | — | — |
| 7 | +3 | Subclass Feature | 5 | 4 | 3 | — | — | — |
| 8 | +3 | Improvement | 5 | 4 | 4 | — | — | — |
| 9 | +4 | Aura of Courage, Righteous Stability | 6 | 4 | 4 | 2 | — | — |
| 10 | +4 | Heroic Boon | 6 | 4 | 4 | 3 | — | — |
| 11 | +4 | Subclass Feature, Improved Divine Smite | 7 | 4 | 4 | 3 | — | — |
| 12 | +4 | Improvement | 7 | 4 | 4 | 4 | — | — |
| 13 | +5 | Channel Divinity (2/rest) | 8 | 4 | 4 | 4 | 2 | — |
| 14 | +5 | Cleansing Touch | 8 | 4 | 4 | 4 | 3 | — |
| 15 | +5 | Additional Fighting Style | 9 | 4 | 4 | 4 | 3 | — |
| 16 | +5 | Improvement | 9 | 4 | 4 | 4 | 4 | — |
| 17 | +6 | Aura Improvements | 10 | 4 | 4 | 4 | 4 | 2 |
| 18 | +6 | Channel Divinity (3/rest) | 10 | 4 | 4 | 4 | 4 | 3 |
| 19 | +6 | Improvement | 11 | 4 | 4 | 4 | 4 | 3 |
| 20 | +6 | Epic Boon | 11 | 4 | 4 | 4 | 4 | 4 |

**Notable gap**: this document never gives a Spellcasting-feature writeup (no Spell Save DC / Spell Attack formula), despite listing "Spellcasting" as a 2nd-level feature name in the table — the only per-class deep-dive so far to name the feature without detailing it. Not treated as a contradiction, just an incompleteness worth flagging.

## Core class features (full text)

### Divine Sense (1st level)

1 minute: know the location of any Celestial, Fiend, or Undead within 60 ft (not behind total cover), and sense consecrated/desecrated areas in the same radius. Uses = PB+1 per long rest.

### Lay on Hands (1st level)

Healing pool = 5×Paladin level. Action: touch a creature to restore HP from the pool, or spend 5 points to cure one disease/neutralise one poison.

### Weapon Mastery (1st level) — confirms Weapon Mastery System with zero drift

Mastery with one martial weapon; Weapon Skill usable once per turn on a hit. **Divine Synergy**: Weapon Skills stack with Divine Smite — apply a Weapon Skill and expend a slot for Divine Smite on the same hit. New masteries via crits: 2 for simple weapons, 3 for martial — exactly matching [[Weapon Mastery]]'s existing Full Martials row, where Paladin is already listed.

### Divine Smite (2nd level)

On a weapon-attack hit, expend a Divine spell slot: 2d8 radiant for a 1st-circle slot, +1d8 per higher circle (max 5d8); +1d8 more against Fiends/Undead.

### Martial Action (2nd level)

Bonus action each turn: **Guard** (disadvantage on the next attack against self/adjacent ally) or **Wind Up** (extra damage = PB on the next heavy/versatile weapon hit) — a subset of [[Fighter]]'s Martial Action list.

### Fighting Style (2nd level, and 15th)

Choose one (another at 15th): Duelling, Great Weapon Fighting, Interception, Protection, Shield Master, or **Sanctified Weapon** (+1d4 damage against creatures opposed to the Paladin's oath tenets — Paladin-exclusive, not on Fighter's or Magus's lists).

### Paladin Subclass (3rd level, and 7th, 11th, 15th)

Choose a Sacred Oath (**Oath of Devotion, Oath of Vengeance, Oath of the Ancients** named as examples). Features at 3rd/7th/11th/15th plus always-prepared Oath Spells — not detailed further here.

### Holy Precision (3rd level) — new Called Shot access route

Once per turn on a Called Shot: reduce the penalty by Charisma modifier (min 1). With +3 CHA, a head shot's normal −4 becomes only −1. Same access-route shape as [[Fighter]]'s/[[Investigator]]'s/[[Monk]]'s hooks, scaled by CHA.

### Multiattack (5th level)

Two attacks on the Attack action.

### Aura of Protection (6th level, and 17th) — contradicts the existing Damage Reduction hook

When the Paladin or an ally within 10 ft (30 ft at 17th) makes a saving throw, add CHA modifier (min +1) to the roll. Requires consciousness.

> [!note] Conflicts with the old "Aura = CHA mod DR" claim — resolved, deep-dive wins
> The old [[Damage Reduction]] claim stated ~~"Paladin (Aura = CHA mod DR to allies)"~~. Ruled: this per-class deep-dive is authoritative — Aura of Protection is a saving-throw bonus only, with no Damage Reduction component. The old DR claim doesn't survive the ruling and has been removed from [[Damage Reduction]].

### Aura of Courage (9th level, and 17th)

The Paladin and allies within 10 ft (30 ft at 17th) cannot be frightened. Requires consciousness.

### Righteous Stability (9th level) — new Momentum exception

Beginning a turn at +2 or higher Momentum: the first attack that misses the Paladin before the start of their next turn doesn't reduce Momentum. Subsequent misses, successful attacks, and other Momentum losses still apply normally — a conditional, once-per-turn version of [[Monk]]'s unconditional Balanced Rhythm.

### Heroic Boon (10th level)

Choose: **Divine Recovery** (a creature healed by Lay on Hands may spend a Hit Die + CON mod for extra HP, plus temp HP = CHA mod) or **Radiant Strikes** (weapon hits deal +1d8 radiant, +2d8 against Fiends/Undead; stacks with Divine Smite).

### Improved Divine Smite (11th level)

All melee weapon hits deal +1d8 radiant automatically — passive, doesn't count as using Divine Smite (regular Divine Smite still usable once/turn on top of this).

### Channel Divinity (available from 2nd level via subclass; scaling at 13th/18th) — confirms shared features with Cleric

Subclass grants the first Channel Divinity option at 3rd level; 2 uses/rest at 13th, 3 at 18th. **Ward of Faith** (reaction via Channel Divinity: an ally within 30 ft about to lose Momentum has that loss reduced by 1, min 0) and **Judgment** (bonus action via Channel Divinity: next weapon/spell attack counts as a Called Shot with no attack-roll penalty, wasted if not attacked before end of turn) are **word-for-word identical** to [[Cleric]]'s features of the same names — the first confirmed case of an entire named ability pair shared verbatim between two classes' Channel Divinity options, not just a similar shape. See [[Momentum]] and [[Called Shot]] for the cross-links.

### Cleansing Touch (14th level)

Action: end one spell affecting self or a willing touched creature. Uses = CHA mod (min 1) per long rest.

### Aura Improvements (17th level)

Aura of Protection, Aura of Courage, and any subclass auras extend to 30 ft.

### Epic Boon (20th level)

Choose: **Aura of Salvation** (10 minutes, once/long rest: allies within 30 ft get resistance to nonmagical damage, auto-succeed death saves, regain CHA-mod HP at the start of their turns) or **Avatar of Retribution** (+CHA mod to all weapon damage rolls; Divine Smite damage +2d8 radiant).

## Last Stand (confirmed universal, 13th class — standard permanent-death clause, plus a DC-base observation)

| Option | Effect |
|---|---|
| Endless Mercy | Allies within 100 ft (5 min): regain HP = character level at the end of each Paladin turn, cured of poison/disease each turn, +3 to one chosen save (WIS/STR/CON) |
| True Smite | Move up to speed; deliver a critical hit to one target in melee range; target CHA saves (DC 10+PB+CHA) or banished to a chosen plane for 1d12+CHA mod months; no Legendary Resistance |
| Turn Fate | All enemies within 100 ft WIS save (DC 10+PB+CHA) or turned (as Turn Undead) for 1 minute, evil-aligned creatures save at disadvantage; can't escape by taking damage; ignores line of effect |

Thirteenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). DC corrected to the canonical `10+PB+CHA` — the original `12+PB+CHA` in this document was a transcription error, ruled and resolved on [[Last Stand]].

## Class Reactions (confirmed universal, 13th class — clean shared-pool confirmation)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest, no stated exceptions — as clean as [[Fighter]]'s confirmation.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Divine Intercession | 2nd | An ally within 10 ft is targeted by an attack | Force the attack to target the Paladin instead; reduce the damage by PB+CHA mod |
| Aegis of Oath | 3rd | A creature within the Paladin's Aura targets an ally | The ally gains +PB to Evasion for that attack; if it still hits, the ally takes half damage and the Paladin takes the other half as radiant damage |
| Radiant Judgment | 11th | The Paladin smites a creature with Divine Smite | Chosen hostile creatures within 10 ft of the target CON save (DC 8+PB+CHA — tenth confirmation of the `8+PB+ability mod` formula) or take PBd6 radiant damage and are blinded until end of their next turn |

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Dynamic Combat System (DCS)]]
- [[Bloodied and Bruised]]
- [[Breaking Points]]
- [[Injury System]]
- [[Seize the Moment]]
- [[Reaction Subclass Features]]
- [[Momentum]]
- [[Called Shot]]
- [[Damage Reduction]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Cleric]]
- [[FEARS MOC]]
