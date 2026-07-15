---
type: entity
title: "Warden"
address: c-000049
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
  - "[[Narrative Identity]]"
  - "[[Narrative Identity Framework]]"
  - "[[Territory Bond]]"
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Class_breakdown]]"
  - "[[Momentum]]"
  - "[[Damage Reduction]]"
  - "[[Evasion]]"
  - "[[Called Shot]]"
  - "[[Injury System]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Narrative Identity]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - ".raw/Warden.md"
confidence: high
---

# Warden — Nature's Front Line

**Half-Caster tier**. "The storm doesn't move for you. It moves through you." An immovable retaliatory tank whose Prime Element defines identity down to the mechanical level — the mountain that won't move, the fire that burns harder when struck, the storm that punishes retreat. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive.

> "The storm doesn't move for you. It moves through you."

## Signature abilities

- **Elemental Presence** — channels the elements as extensions of the body
- **Source Magic** — retaliatory elemental force
- **Elemental Wall/Rebuke** — punishes attackers on reaction

**Gameplay style**: immovable retaliatory tank, absorbing pressure and returning it with interest. **Core loop**: hold position → absorb → retaliate → repeat. Struggles at range and against foes that ignore terrain; excels at chokepoints, prepared positions, and fights where the enemy must come to it.

## Class basics (from Warden.md deep-dive)

- **Hit Dice**: 1d10/level. HP at 1st: 10 + CON mod. HP at higher levels: 1d10 (or 6) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium, heavy, shields. Weapons — simple, martial. Tools — herbalist tools. Saves — Constitution, Wisdom. Skills — choose three from Animal Handling, Athletics, Intimidation, Nature, Perception, Resolve, Survival.
- **Starting Equipment**: (a) martial weapon + shield or (b) two martial weapons; (a) chain mail or (b) scale mail + shield; (a) explorer's or (b) dungeoneer's pack; herbalist tools and a component pouch.
- **Quick Build**: Strength or Constitution highest, then Wisdom. Guardian Discipline recommended for new players; Athletics, Perception, Survival, Intimidation.

## Level progression (1st-20th)

| Level | PB | Features | Power Dice | Spells Known | Spell Slots | Slot Level |
|---|---|---|---|---|---|---|
| 1 | +2 | Warden's Discipline, Natural Awareness, Natural Power | 4 (d4) | — | — | — |
| 2 | +2 | Elemental Presence, Source Magic, Class Reactions | 4 (d4) | 2 | 1 | 1st |
| 3 | +2 | Prime Element, Weapon Mastery | 4 (d4) | 2 | 1 | 1st |
| 4 | +2 | Improvement | 4 (d4) | 2 | 1 | 1st |
| 5 | +3 | Extra Attack | 5 (d6) | 3 | 2 | 2nd |
| 6 | +3 | Discipline Feature, Elemental Absorption | 5 (d6) | 3 | 2 | 2nd |
| 7 | +3 | Prime Elemental Shield | 5 (d6) | 4 | 2 | 2nd |
| 8 | +3 | Improvement | 5 (d6) | 4 | 2 | 2nd |
| 9 | +4 | Elemental Fortitude | 6 (d6) | 5 | 2 | 3rd |
| 10 | +4 | Discipline Feature, Heroic Boon | 6 (d6) | 5 | 2 | 3rd |
| 11 | +4 | Improved Natural Power | 6 (d8) | 6 | 2 | 3rd |
| 12 | +4 | Improvement | 6 (d8) | 6 | 2 | 3rd |
| 13 | +5 | Nature Sense | 7 (d8) | 7 | 3 | 4th |
| 14 | +5 | Discipline Feature | 7 (d8) | 7 | 3 | 4th |
| 15 | +5 | Channel Power | 7 (d8) | 8 | 3 | 4th |
| 16 | +5 | Improvement | 7 (d8) | 8 | 3 | 4th |
| 17 | +6 | Elemental Dominance | 7 (d10) | 9 | 3 | 5th |
| 18 | +6 | Improvement | 7 (d10) | 9 | 3 | 5th |
| 19 | +6 | Improvement | 7 (d10) | 10 | 4 | 5th |
| 20 | +6 | Master of Elements, Epic Boon | 7 (d10) | 10 | 4 | 5th |

## Core class features (full text)

### Warden's Discipline (1st level, and 6th, 10th, 14th)

Choose **Guardian, Fanatic, Sentinel,** or **Apex Predator** — full detail below.

### Natural Awareness (1st level) — new Momentum gain source

+WIS mod to initiative. Winning initiative in Round 1 (highest individual roll) grants **+1 Momentum**. At 18th, also advantage on initiative rolls in natural environments.

### Natural Power (1st level)

Power Dice (quantity/size per the table): on a weapon-attack hit, expend one, roll it, add the result as bonus damage of a chosen type (acid/bludgeoning/cold/fire/lightning/thunder). Regain half (round down) on a short rest, all on a long rest.

### Elemental Presence (2nd level) — second new Momentum gain source

Bonus action, 1 minute (PB uses/long rest): creatures starting their turn within 5 ft take WIS-mod damage of the Prime Element's type; sheds dim light 10 ft; advantage on Intimidation against creatures that can see the Warden. **Activating it in Round 1 grants +1 Momentum.**

### Source Magic (2nd level) — sixteenth confirmed DC formula

WIS-based: **Spell Save DC = 8+PB+WIS, Spell Attack = PB+WIS** — sixteenth confirmation of the `8+PB+ability mod` formula. Slots recharge on a short *or* long rest. Concentration uses CON save proficiency.

### Class Reactions (2nd level, and 7th, 13th) — third new Momentum gain source

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest.

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Elemental Rebuke | 2nd | A creature within 5 ft hits with a melee attack | They take a rolled Power Die of Prime Element damage; CON save (DC 8+PB+WIS) or pushed 5 ft; a failed save also grants **+1 Momentum** | 1 use |
| Elemental Wall | 7th | A creature moves toward the Warden or an ally within 10 ft | STR save or speed 0 until end of their turn; failure also deals WIS-mod damage (1d8+WIS mod at 11th) of Prime Element type | 1 use |
| Primal Retribution | 13th | A creature within 30 ft damages the Warden or an ally | CON save (DC 8+PB+WIS) — fail: 3d8 Prime Element damage + an appropriate Frailty (+1d8 at 15th/19th); success: half, no Frailty | 2 uses |

### Weapon Mastery (3rd level) — confirms Weapon Mastery System with zero drift

Mastery with **two** martial weapons at 3rd level (later than most classes' 1st-level grant); Weapon Skill usable once per turn on a hit. New masteries via crits: 2 simple/3 martial — a sixth independent confirmation of the Full Martials row, where Warden is already listed.

### Prime Element (3rd level) — new Damage Reduction hooks

Choose one, each with an active effect and a passive "Warden Resonance":

- **Earthen Bulwark** (Bludgeoning): Power Die bludgeoning damage forces a STR save or grapples for 1 minute. Resonance — **Stone Skin**: +1 DR against all physical damage while wearing medium/heavy armour.
- **Flaming Bravery** (Fire): Power Die fire damage repeats at the start of the target's next turn, no save. Resonance — **Heat Ward**: while bloodied, melee attackers automatically take WIS-mod fire damage.
- **Stoic Chill** (Cold): Power Die cold damage imposes disadvantage on the target's next attack. Resonance — **Glacial Endurance**: new Injury-interaction shape, see below.
- **Unrelenting Storm** (Lightning/Thunder): Power Die lightning/thunder damage, if the target moves willingly before the Warden's next turn, triggers a second Power Die roll + WIS mod as extra damage. Resonance — **Grounding Charge**: resistance to lightning; metal-weapon attackers automatically take WIS-mod lightning damage.
- **Putrid Corrosion** (Acid): Power Die acid damage denies the target's STR/DEX damage bonus until the end of their next turn. Resonance — **Caustic Hide**: creatures grappling or grappled by the Warden take WIS-mod acid damage each of their turns.

### Extra Attack (5th level)

Two attacks instead of one on the Attack action.

### Elemental Absorption (6th level) — fourth new Momentum gain source

Reaction: taking Prime-Element-type damage reduces it by a rolled (not expended) Power Die; the reduced amount becomes bonus damage on the Warden's next weapon attack before their next turn. Uses = PB per short or long rest. **Reducing damage to exactly 0 grants +1 Momentum.**

### Prime Elemental Shield (7th level, reaction, 1 Class Reaction use)

On being attacked or forced to save, invoke the Prime Element's shield: **Earthen Bulwark** (advantage on Evasion vs. ranged attacks/DEX saves), **Flaming Bravery** (+PB to Evasion, a successful evade burns the attacker for WIS mod), **Stoic Chill** (reduce melee damage by WIS mod + a rolled Power Die), **Unrelenting Storm** (reduce ranged damage to self/an adjacent ally by WIS mod + a rolled Power Die), **Putrid Corrosion** (the triggering metal weapon's attacks are disadvantaged and can't benefit from advantage until the Warden's next turn).

### Elemental Fortitude (9th level)

No CON save needed for concentration on Warden spells while holding 1+ Power Dice; advantage vs. frightened/charmed by elemental-origin creatures; +1 Power Die recovered per short rest.

### Heroic Boon (10th level)

Choose: **Warden's Permanence** (Elemental Presence always active, no duration/bonus-action cost, radius +10 ft; a failed Elemental Rebuke CON save also inflicts the Prime Element's secondary effect automatically) or **Unyielding Terrain** (while stationary: +3 DR stacking with armour, advantage on all saves, advantage on Evasion vs. melee; Class Reaction pool regains 1 use at the start of each turn, max = PB).

### Improved Natural Power (11th level)

Once per turn, a weapon attack or Warden cantrip hit deals +2d8 Prime Element damage for free, no Power Die cost.

### Nature Sense (13th level)

Touch a natural surface 1 minute to remotely perceive any point on it within 100 ft for up to 10 minutes (blind/deaf to own senses meanwhile, endable at will). Never surprised in natural environments.

### Channel Power (15th level)

Bonus action, once/long rest: expend 4 Power Dice to regain one expended spell slot.

### Elemental Dominance (17th level)

Elemental Presence radius → 15 ft; damage from it forces a CON save (DC 8+PB+WIS) or the Prime Element's secondary effect for 1 round. Elemental Absorption now works against all elemental damage types (bonus-damage payoff still Prime-Element-only).

### Epic Boon (20th level)

Choose: **Boon of the Immovable Force** (immune to forced movement; can't be knocked prone while not having moved on the turn; Evasion results can never go below a halved-damage partial defence) or **Boon of the Living Element** (no food/water/sleep; immune to Prime Element damage; once per lifetime, dying instead becomes the element for 1 hour — incorporeal, unharmable, no physical interaction — then reforms at 1 HP).

## Warden's Disciplines (full subclass detail)

### Guardian — steel and stone

- **Combat Training** (1st): proficiency with all martial weapons; choose a Fighting Style (Archery, Defence, Great Weapon Fighting, Protection), a second at 15th. **Momentum**: Protection Style + the protected ally taking no damage grants +1 Momentum.
- **Strength of the Elements** (6th): a Power Die expended for damage treats any non-max roll as max; WIS-mod uses (min 1) per short rest.
- **Shielding Aura** (10th, reaction, 1 Class Reaction use): self or a creature within 30 ft taking elemental damage — halve it.
- **Nature's Fury** (14th): expend a Power Die for advantage on a weapon attack; every d20 that would hit rolls the Power Die separately for extra Prime Element damage per hit.

### Fanatic — unarmed and unrelenting

- **Pugilist** (1st): unarmed strikes use the Power Die for damage and WIS instead of STR for attack/damage; Attack action with an unarmed strike grants a bonus-action extra unarmed strike; unarmed strikes count as magical. **Momentum**: two unarmed strikes in a turn, both hitting, grants +1 Momentum.
- **Precise Power** (6th): a Power Die on an unarmed strike rolls twice, keep higher; WIS-mod uses per long rest.
- **Extension Stance** (10th): unarmed reach extends to 15 ft with both hands empty; touch spells can reach 15 ft while grappling (elemental force holds the target).
- **Exploding Elements** (14th): a hit Power Die unarmed strike bursts — creatures within 5 ft of the target (not the Fanatic) take the Power Die result as Prime Element damage, DEX save (DC 8+PB+WIS) for half.

### Sentinel — the ground obeys

- **Territorial Claim** (1st): spending no movement on a turn creates a 10 ft **Claimed Zone** — entering/starting there forces a STR save (DC 8+PB+WIS) or half speed for the rest of the turn; advantage on opportunity attacks within it; allies inside get +WIS mod to Evasion. Collapses on the Sentinel's movement, reforms on stopping. **Momentum**: a failed Claimed Zone save grants +1 Momentum.
- **Ground Control** (6th): a failed Claimed Zone save also triggers Elemental Presence damage immediately; opportunity attacks against creatures leaving the Zone work even against Disengage.
- **Sentinel's Anchor** (10th): while stationary — Zone radius → 20 ft, advantage on all saves, +2 armour DR (stacking), no teleporting into the Zone.
- **Elemental Dominion** (14th): the Claimed Zone becomes automatic difficult terrain for enemies; a failed entry save also inflicts the Prime Element's secondary effect for free (no Power Die cost).

### Apex Predator — the hunt made permanent

- **Predator's Mark** (1st): bonus action, mark one creature within 60 ft as **Prey** (until re-marked, Prey dies, or a long rest) — +WIS mod damage on every weapon hit against Prey; always know their approximate location within 60 ft; Called Shot penalties against them reduced by 1; advantage tracking them. **Momentum**: reducing Prey to 0 HP grants +2 Momentum.
- **Predator's Pursuit** (6th): ignore difficult terrain moving toward Prey; Prey's Disengage forces a DEX save (DC 8+PB+WIS) or it fails (still moves, but the opportunity attack still lands); Called Shot penalty reduction against Prey totals 2.
- **Apex Strike** (10th): the first weapon attack against Prey each turn expends a Power Die rolled twice (keep higher) on a hit; a critical hit forces a CON save (DC 8+PB+WIS) or Prey gains a Prime-Element-appropriate Frailty.
- **Final Hunt** (14th): once/long rest, reducing Prey to 0 HP free-designates a new Prey immediately; against a bloodied Prey, Extra Attack grants three attacks instead of two.

## Last Stand (confirmed, 20th class of 21 ingested — standard permanent-death clause, DC gap resolved by user ruling)

| Option | Effect |
|---|---|
| The Earth Remembers | 60 ft terrain transformation matching the Prime Element (e.g. Earthen Bulwark: DEX save, DC 10+PB+WIS, or 8d10 bludgeoning + prone, permanent terrain; Unrelenting Storm: DEX save, DC 10+PB+WIS, for half of 8d10 lightning, then 3d10/round for 1 minute) — DC resolved below for all five element variants |
| Hold the Line | Stays at 0 HP for 1 minute, immune to HP-damage death; allies within 30 ft gain +3 DR (stacking); each death-save success bursts 2d10 Prime Element damage (no save) to enemies within 10 ft; dies when the minute ends or a third death save fails |
| The Storm Breaks | 3 rounds as a raw elemental vessel: Elemental Presence radius 60 ft dealing 3d10 (no save); attacks auto-hit and auto-max; immune to all damage; can't be moved/charmed/frightened/controlled. Dies when it ends |

Twentieth class confirming [[Last Stand]] as universal (of 21 per-class files ingested — [[Sorcerer]] remains the sole exception); all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

> [!resolved] The Earth Remembers' missing DC
> Previously the only Last Stand option in the cluster to name a saving throw type across all five element variants without ever giving a DC. **Resolved by user ruling**: `DC = 10 + PB + WIS`, matching Warden's own confirmed spellcasting DC (`8+PB+WIS`) and the canonical `10+PB+ability` Last Stand shape used everywhere else in the roster. Applies uniformly across all five Prime Element variants — only the save type (DEX or CON, per element) differs.

## Mythology & Cultural Lore

> [!note] Original composition — no raw source
> Warden is absent from all three `Class_Lore_Compendiums_DorOEstel` variants (they cover Runesmith/Shadowbinder/Tamer instead, three retired classes Bender/Warden/Binder replaced on the current roster). No `.raw/` source treats Warden's mythology. The section below was composed to fill that gap, following the Compendium's own template and staying consistent with established Dór-o Estel cosmology (including [[World Anchors and Thread System]]) — it is original wiki content, not an ingestion, and carries no `.raw/` source citation.

*Unmoved Roots: Those Who Become the Ground They Defend.*

Wardens trace their tradition to the first guardians who planted themselves at chokepoints — mountain passes, city gates, river fords — and simply refused to leave, absorbing every blow meant for what stood behind them until attacker and defender both forgot the Warden had ever been capable of retreat. During Ashkarra's Fall, as the city's own World Anchor buckled under the triple Spirit Thread alignment, several Wardens attempted to physically brace it — planting themselves at its base and channeling their Prime Element into the failing structure. No single Warden could out-anchor a dying World Anchor, and all who tried were lost with the city, but the attempt itself became the tradition's defining legend: the conviction that a body, held still and fed enough elemental will, can function as a small, mortal echo of what a World Anchor does at civilization's scale.

**Source of Power (DM truth):** Wardens access the [[Elemental Glyphs]] the same way a Bender does — but where a Bender embraces the fluidity between them, a Warden locally *halts* it. Standing still long enough, and channeling hard enough into a single element, a Warden's body becomes a miniature stabilizing point, imposing the same kind of local permanence a [[World Anchors and Thread System|World Anchor]] imposes on reality at large — which is why Wardens instinctively read a battlefield the way a World Anchor reads a Loom-City, and why "the ground obeys" a Sentinel-discipline Warden almost literally. Neither Wardens nor the scholars who study them have ever connected this to actual World Anchor mechanics; it remains an unrecognized structural echo, not a stated in-world theory.

**Legendary figures:** Borun Ironroot, a dwarf said to have held a mountain pass alone against a routed army for three days and nights without taking a single step backward, dying on his feet still facing the direction the enemy had come from — his stance is still taught as the founding posture of the Guardian discipline.

*"The storm doesn't move for you. It moves through you. Plant your feet before you plant your argument — anyone can speak of holding ground. Fewer are still standing on it three days later."* — attributed to Borun Ironroot

## See also

- [[Narrative Identity]]
- [[Territory Bond]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[FEARS Class Roster]]
- [[Momentum]]
- [[Damage Reduction]]
- [[Evasion]]
- [[Called Shot]]
- [[Injury System]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Elemental Glyphs]]
- [[World Anchors and Thread System]]
- [[FEARS MOC]]
