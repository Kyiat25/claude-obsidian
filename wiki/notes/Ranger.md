---
type: entity
title: "Ranger"
address: c-000064
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
  - "[[Damage Reduction]]"
  - "[[Evasion]]"
  - "[[Momentum]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Ranger.md"
confidence: high
---

# Ranger — Hunter of the Marked

**Half-Caster tier**. "The druid asks the forest's permission. The Ranger has already mapped every angle of approach." Builds increasing dominance over a single target — the intelligence officer, scout, and precision striker of the party. Complexity self-rated LOW (3/10) by its own per-class deep-dive.

> "The druid asks the forest's permission. The Ranger has already mapped every angle of approach."

## Signature abilities

- **Hunter's Mark** — escalating damage
- **Favoured Enemy** — deep specialization
- **Exploit Quarry** — tactical dismantling

**Gameplay style**: focused predator, eliminating key threats efficiently. **Core loop**: mark → build advantage → exploit → eliminate. Excels in prepared ambushes, single-target elimination, extended wilderness travel; struggles in unfamiliar urban environments and against threats that ambush first.

## Class basics (from Ranger.md deep-dive)

- **Hit Dice**: 1d10/level. HP at 1st: 10 + CON mod. HP at higher levels: 1d10 (or 6) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium, shields. Weapons — simple, martial. Tools — choose herbalist, navigator, or trapper tools. Saves — Strength, Dexterity. Skills — choose three from Animal Handling, Athletics, Crafting, Gathering, Insight, Investigation, Nature, Perception, Skinning, Stealth, Survival.
- **Starting Equipment**: (a) scale mail or (b) leather armour; (a) two shortswords or (b) two simple weapons; (a) dungeoneer's pack or (b) explorer's pack; a longbow and 20 arrows.
- **Quick Build**: Dexterity or Strength highest, then Wisdom. Any lineage (Wood Elf, Halfling, Human thematic). Outlander/Folk Hero or a Nature/Survival background. Hunter's Mark at combat start; Exploit Quarry on priority targets; Stalker's Step to reposition for optimal angles.

## Level progression (1st-20th)

| Level | PB | Features | Spells Known | 1st | 2nd | 3rd | 4th | 5th |
|---|---|---|---|---|---|---|---|---|
| 1 | +2 | Explorer, Favoured Enemy, Hunter's Mark, Weapon Mastery | — | — | — | — | — | — |
| 2 | +2 | Hunter's Preparation, Predator's Insight, Exploit Quarry, Fighting Style, Spellcasting | 2 | 2 | — | — | — | — |
| 3 | +2 | Ranger Subclass, Nature's Reprisal (Reaction) | 3 | 3 | — | — | — | — |
| 4 | +2 | Improvement | 3 | 3 | — | — | — | — |
| 5 | +3 | Multiattack, Fleet Guard | 4 | 4 | 2 | — | — | — |
| 6 | +3 | Empowered Mark, Favoured Enemy Synergy | 4 | 4 | 2 | — | — | — |
| 7 | +3 | Subclass Feature, Terrain Mastery, Claimed Ground | 5 | 4 | 3 | — | — | — |
| 8 | +3 | Improvement | 5 | 4 | 3 | — | — | — |
| 9 | +4 | Stalker's Step | 6 | 4 | 3 | 2 | — | — |
| 10 | +4 | Heroic Boon | 6 | 4 | 3 | 2 | — | — |
| 11 | +4 | Subclass Feature, Precision Kill, Contested Ground | 7 | 4 | 3 | 3 | — | — |
| 12 | +4 | Improvement | 7 | 4 | 3 | 3 | — | — |
| 13 | +5 | Hunter's Mark (1d10) | 8 | 4 | 3 | 3 | 1 | — |
| 14 | +5 | Keensense | 8 | 4 | 3 | 3 | 1 | — |
| 15 | +5 | Subclass Feature | 9 | 4 | 3 | 3 | 2 | — |
| 16 | +5 | Improvement | 9 | 4 | 3 | 3 | 2 | — |
| 17 | +6 | Hunter's Mark (1d12) | 10 | 4 | 3 | 3 | 3 | 1 |
| 18 | +6 | Strider, Sovereign Ground | 10 | 4 | 3 | 3 | 3 | 1 |
| 19 | +6 | Improvement | 11 | 4 | 3 | 3 | 3 | 2 |
| 20 | +6 | Epic Boon | 11 | 4 | 3 | 3 | 3 | 2 |

## Core class features (full text)

### Explorer (1st level)

Climbing or swimming speed = base movement; advantage tracking creatures; ignores nonmagical difficult-terrain penalties.

### Favoured Enemy (1st level, and 6th, 14th, 19th) — new Momentum gain source, Evasion discrepancy

Choose a creature type. **Called Shot**: penalties reduced (Head −2, Arms/Legs 0). **Bonus Damage**: +2 weapon damage. **Tracking**: advantage tracking/recalling info. **Hunter's Mark synergy**: combined, eliminates Called Shot penalties entirely and adds one damage-die step. **Favoured Enemy Agility**: roll Evasion **with advantage** against Favoured Enemies — see the Evasion note below. New Favoured Enemy at 6th/14th/19th.

**Momentum**: a successful hit against a Favoured Enemy grants **+2 Momentum** instead of the normal +1 — the eleventh class-specific Momentum-gain source in this cluster.

> [!note] Evasion formula didn't match the old DCS-summary claim — resolved, deep-dive wins
> The old [[Evasion]] page (from [[Dynamic Combat System (DCS)]]'s summary) stated Rangers add ~~"WIS modifier to Evasion rolls against marked or favoured targets"~~ — a flat bonus. Ruled: this per-class deep-dive is authoritative. Current rule: **advantage** on those Evasion rolls, no WIS-mod scaling.

### Hunter's Mark (1st level, and 6th, 13th, 17th) — DR contradiction

Mark a creature: bonus damage 1d6 (1d8 at 6th, 1d10 at 13th, 1d12 at 17th) on weapon attacks/damaging spells; attack-roll bonus +1 (+2 at 6th, +3 at 13th, +4 at 17th); Called Shot penalties reduced (Head −3, Arms/Legs −1); marked targets roll Evasion with disadvantage against the Ranger; no concentration required, one mark maintained at a time (until later features expand this). **DR Reduction: reduces the marked target's DR by 2** (flat).

> [!note] Conflicts with the old "Wisdom-modifier" claim — resolved, deep-dive wins
> The old [[Damage Reduction]] claim stated Hunter's Mark ~~"reduces the marked target's DR by the Ranger's Wisdom modifier"~~ — a scaling bonus. Ruled: this per-class deep-dive is authoritative. Current rule: flat **−2 DR**, no WIS-mod scaling — stacking additively with Colossus Slayer's own flat −2 (total −4 against already-injured, marked creatures).

### Weapon Mastery (1st level) — confirms Weapon Mastery System with zero drift

Mastery with one weapon of choice; Weapon Skill usable once per turn on a hit. **Hunter's Synergy**: movement-control Weapon Skills complement Hunter's Mark/Favoured Enemy. New masteries via crits: 2 for simple, 3 for martial — matching [[Weapon Mastery]]'s existing Full Martials row, where Ranger is already listed.

### Predator's Insight (2nd level)

Marked targets: on becoming bloodied, immediately learn one bloodied effect (Frailty/Strength/Ability/Death Throes); bonus-action Survival check (DC 12+CR) learns one more. Favoured Enemies: automatically know all four. Advantage tracking bloodied creatures via Survival.

### Hunter's Preparation (2nd level)

After 1+ minute of uninterrupted pre-combat preparation: advantage on the first Round-1 attack roll, +1 weapon damage die (+2 against a Favoured Enemy). Once per short or long rest.

### Exploit Quarry (2nd level, scaling at 4th/8th/14th/20th)

Bonus action: choose a Hunter's-Mark or Favoured-Enemy target within 30 ft, Survival or Perception check (DC = 8+target's DEX mod+their PB). Success: next attack before end of next turn deals extra damage — 1d8/4th, 2d8/8th, 3d8/14th, 4d8/20th — plus one chosen effect: **Pinned Prey** (speed 0 until end of their next turn), **Expose Weak Point** (DR halved against all attacks until the Ranger's next turn), **Disrupt Reaction** (no reactions until end of their next turn), or **Hamper Evasion** (disadvantage on their next Evasion roll). At 6th level, target two creatures simultaneously; at 14th, ignores condition immunity. Uses = WIS mod per long rest.

### Fighting Style (2nd level)

Choose one: Archery, Blind Fighting, Agile Defence, Dueling, Thrown Weapon Fighting, Two-Weapon Fighting, Beast Bond, Primal Strikes, or Forest Guardian — three options (Beast Bond, Primal Strikes, Forest Guardian) not seen on any other class's Fighting Style list.

### Ranger Subclass (3rd level, and 7th, 11th, 15th)

Choose a tradition (**Beast Master, Gloom Stalker, Hunter** named as examples). Features at 3rd/7th/11th/15th — not detailed further here (subclass-specific Colossus Slayer DR and Called Shot content comes from other sources, see [[Called Shot Subclass Features]]).

### Multiattack (5th level)

Two attacks on the Attack action.

### Fleet Guard (5th level) — new Damage Reduction class hook

Moving at least 10 ft during the Ranger's turn grants **DR 1** until the start of their next turn, stacking with armour DR.

### Empowered Mark (6th level)

Senses the marked target within 10% of bloodied and knows immediately when they cross it; while within 60 ft, always knows their exact location and can't be blinded/disadvantaged against them from invisibility. On the marked target becoming bloodied: Hunter's Mark's damage die steps up one, DR reduction increases by 2 (total −4), Called Shot penalties eliminated entirely.

### Terrain Mastery (7th level, and 11th, 15th)

Choose a terrain type (arctic, coast, desert, forest, grassland, mountain, swamp, Underdark). In it: ignore difficult terrain, advantage on Stealth/Survival checks, enemies disadvantaged detecting a stationary Ranger. Additional terrain types at 11th/15th.

### Claimed Ground (7th level) — second new Momentum gain source

After 10+ minutes studying a location, designate it Claimed Ground (non-magical); maintains a number = WIS mod (min 2). **Prepared Ambush** (move half speed free before initiative if combat starts here and the Ranger isn't surprised), **Territorial Momentum** (+1 Momentum on the first hit each turn here, on top of normal gain), **Immediate Mark** (free Hunter's Mark, no reaction cost, on a hostile creature's first entry), **Tactical Sight Lines** (can't be surprised; always knows creature count in the area). Claimed Ground counts as the chosen Terrain Mastery type.

### Stalker's Step (9th level)

Bonus action in dim light/darkness/obscurement: magical invisibility until start of next turn (ends on attacking/casting). PB uses per long rest. Reaction version: on a creature within 60 ft becoming bloodied, become invisible, move half speed without provoking, next attack against them has advantage.

### Heroic Boon (10th level)

Choose: **Path of the Predator** (rolling initiative expends a Hunter's Mark use to auto-mark a visible creature; reaction transfers the mark to a new target when the marked creature drops to 0 HP, learning two bloodied effects if the new target is bloodied) or **Path of the Sage** (two cantrips + two ritual spells from the Primordial list, don't count against spells known; *Guidance* on self as a bonus action; casting a ritual near a bloodied creature learns one of its effects).

### Precision Kill (11th level)

A critical hit against the Favoured Quarry grants +2 Momentum instead of the normal crit bonus — reinforces rather than replaces Favoured Enemy's own +2-on-hit interaction.

### Contested Ground (11th level)

Tactical Sight Lines extends to 120 ft. Reaction (1 Class Reaction use): a creature within Claimed Ground moving to a tactically advantageous position can be attacked once; a hit stops their movement. Up to two allies can be designated to share Tactical Sight Lines within the Ground.

### Keensense (14th level)

Keensense 30 ft: detects invisible/hidden creatures; bloodied creatures in range auto-fail Stealth against the Ranger; advantage on attacks against bloodied creatures detected this way.

### Strider (18th level)

Movement never provokes opportunity attacks; Dash as a bonus action ignoring difficult terrain in natural terrain; advantage on Survival/Animal Handling/Skinning/Gathering and resisting grapple/restrain/paralysis/speed-0 effects; in natural terrain, the party can't get lost and travels at double speed.

### Sovereign Ground (18th level) — eleventh confirmed DC formula

Tremorsense 30 ft within Claimed Ground; invisible creatures can't hide there. Once/long rest, declare a Claimed Ground location a **Last Stand Ground** for one encounter: Hunter's Mark damage steps up one die, creatures starting their turn there WIS save (**DC = 8+PB+WIS**, eleventh confirmation of the `8+PB+ability mod` formula) or frightened until end of their next turn, and once per encounter a reaction drops the Ranger to 1 HP instead of 0 within it. Max Claimed Ground locations increase to WIS mod + PB.

### Epic Boon (20th level)

Choose: **Foe Slayer** (+WIS mod to attack/damage against marked targets; once/turn an unstoppable strike bypasses all DR and deals critical damage, consuming the mark; reducing a marked creature to 0 HP transfers the mark free; bloodied marked targets take crits on 18–20, and dropping one to 0 HP grants an extra attack against another target) or **Nature's Wrath** (maintain Hunter's Mark on up to 3 creatures without concentration; a marked creature dropping to 0 HP triggers a choice of 4d10 area damage or 15 HP party healing; reaction forces a STR save, DC = 8+PB+WIS, or a marked creature's movement becomes 0; all bloodied creatures within 60 ft are disadvantaged attacking the Ranger/allies).

## Last Stand (confirmed universal, 14th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Hunter's Reckoning | Choose a target within 120 ft; for 5 minutes, all attacks/effects against it auto-hit and auto-crit, ignoring cover/invisibility/resistance; make one ranged attack against it immediately |
| Call of the Wild | Summon 3 creatures (Beasts ≤CR4, Elementals ≤CR3, or Fey ≤CR3) within 30 ft for 5 minutes, immune to charm/fear/magical control |
| Ghost of the Vale | 5 minutes as a spectral guide: allies within 100 ft gain invisibility while not attacking/casting, plus advantage on Stealth/DEX saves; enemies within 30 ft disadvantaged on Perception/ranged attacks; the Ranger flies 60 ft and passes through barriers |

Fourteenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). None of Ranger's options state an explicit save DC, so this source doesn't add a data point to the ongoing 10-vs-12-base DC question on [[Last Stand]].

## Class Reactions (confirmed universal, 14th class — clean shared-pool confirmation)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest, no stated exceptions.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Hunter's Reflex | 2nd | A Hunter's-Mark target makes an attack roll | Disadvantage; if it still hits, reduce damage by 1d6+WIS mod. Against bloodied marked targets: 2d6+WIS, and a hit forces a CON save (DC 8+PB+WIS) or their Strength benefit is suppressed |
| Quarry Interpose | 3rd | The marked target attacks an ally within 30 ft | Disadvantage; if it still hits, reduce damage by 1d8+PB. Against bloodied marked targets: intercept entirely by moving 10 ft (become the target), gaining resistance to that damage |
| Hunter's Snare | 11th | The marked target moves within 30 ft | STR save (DC 8+PB+WIS) or restrained until end of their next turn + PBd6 piercing. Against bloodied marked targets: DC +2, also grappled, damage PBd8 |

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Dynamic Combat System (DCS)]]
- [[Seize the Moment]]
- [[Reaction Subclass Features]]
- [[Damage Reduction]]
- [[Evasion]]
- [[Momentum]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
