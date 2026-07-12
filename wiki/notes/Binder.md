---
type: entity
title: "Binder"
address: c-000057
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
first_mentioned: "[[Classes_Summary]]"
related:
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Class_breakdown]]"
  - "[[Weapon Mastery]]"
  - "[[Whisper Points]]"
  - "[[Focus]]"
  - "[[Momentum]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
  - "[[Dór-o Estel]]"
sources:
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - ".raw/Binder.md"
confidence: high
---

# Binder — Vessel of the Unfinished Dead

Specialized-tier class: "Vessel of the Unfinished Dead" — hosts fragments of the dead directly rather than summoning a separate creature. Explicitly replaces a retired **Summoner** class. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive. **Note on source status**: this document's own frontmatter reads `status: draft` — distinct from every other per-class file so far, which read `status: revised`. Not `excluded` (so not given the excluded-source treatment), but flagged here since it's a status value not seen elsewhere in this cluster; treated as canon like `revised` sources unless a future source contradicts it.

> "I do not command the dead. I let them borrow my hands, and I ask, politely, that they give them back."

## Signature abilities (from Classes_Summary / Class_breakdown)

- **Echo Binding** — hosts a fragment of the dead, gaining its Trait and abilities
- **Rebinding** — swaps which echoes are hosted between rests
- **Bleed Points** — turns the wear of hosting the dead into raw power

**Gameplay style**: adaptive shapeshifter, retooling its own toolkit rather than commanding a second body — a Binder trades a Summoner's separate-creature action economy for changing what the Binder's own body can do. **Core loop**: bind → channel → rebind → repeat.

## Class basics (from Binder.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armor — light, medium. Weapons — simple. Tools — none. Saves — Charisma, Wisdom. Skills — choose two from Arcana, Deception, History, Insight, Intimidation, Religion, Survival.
- **Starting Equipment**: (a) simple melee weapon or (b) simple ranged weapon + 20 ammunition; (a) leather or (b) studded leather armor; 10 pieces of chalk/graveyard soil + a component pouch or arcane focus; (a) scholar's pack or (b) explorer's pack; a personal effect belonging to the first remnant ever bound.
- **Quick Build**: Charisma highest (governs Binding Save DC), Constitution second. Any lineage; death-rite/mourning/Wyrd-adjacent heritages thematic. Gravedigger/Haunted Survivor/Battlefield Medic or a death/grief/Fracture-adjacent background. Bind remnants covering the party's gaps before combat, keep one Rebind in reserve, bank Bleed Points early for a big Push the Bind later.

## Level progression (1st-20th)

| Level | PB | Features | Remnants Bound | Remnant Tier | Max BP |
|---|---|---|---|---|---|
| 1 | +2 | Remnant Binding, Manifest Marks, Bleed Points | 1 | 1 | 2 |
| 2 | +2 | Rebinding, Class Reactions | 1 | 1 | 2 |
| 3 | +2 | Binding Order | 1 | 1 | 2 |
| 4 | +2 | Ability Score Improvement | 1 | 1 | 2 |
| 5 | +3 | Remnant Tier 2, Second Remnant | 2 | 2 | 3 |
| 6 | +3 | Binding Order Feature | 2 | 2 | 3 |
| 7 | +3 | Suppress/Reveal Signs, Additional Class Reaction | 2 | 2 | 3 |
| 8 | +3 | Ability Score Improvement | 2 | 2 | 3 |
| 9 | +4 | Remnant Tier 3, Adamant Mind | 2 | 3 | 4 |
| 10 | +4 | Heroic Boon, Binding Order Feature | 2 | 3 | 4 |
| 11 | +4 | Third Remnant | 3 | 3 | 4 |
| 12 | +4 | Ability Score Improvement | 3 | 3 | 4 |
| 13 | +5 | Remnant Tier 4 | 3 | 4 | 5 |
| 14 | +5 | Binding Order Feature | 3 | 4 | 5 |
| 15 | +5 | Rebinding Improvement (twice/rest) | 3 | 4 | 5 |
| 16 | +5 | Ability Score Improvement | 3 | 4 | 5 |
| 17 | +6 | Remnant Tier 5, Fourth Remnant | 4 | 5 | 6 |
| 18 | +6 | Threadscarred | 4 | 5 | 6 |
| 19 | +6 | Ability Score Improvement | 4 | 5 | 6 |
| 20 | +6 | Unbound (Epic Boon) | 4 | 5 | 6 |

## Core class features (full text)

### Remnant Binding (1st level)

The Binding Rite: a 10-minute ritual (short/long rest, or any 10 uninterrupted minutes) selecting a number of remnants equal to Remnants Bound, none higher than current Remnant Tier, from the Bound Remnants list below. Remnants stay bound until the rite is repeated or a long rest is finished. A remnant is not a creature — no separate HP, initiative, or turn; its abilities run through the Binder's own action economy, hit points, and saves.

**Binding Save DC = 8 + PB + Charisma modifier. Binding Attack Modifier = PB + Charisma modifier.** Matches the same `8 + PB + ability mod` shape confirmed for spellcasting DCs on [[Bard]] and [[Bender]] — a third independent confirmation of that formula pattern, this time for a non-spellcasting save.

### Manifest Marks (1st level)

Every bound remnant leaves a visible sign (narrative flavor, no default mechanical effect) — subtle or overt, chosen once per remnant. NPCs/guards may recognize a Binder by these; many Loom-Cities in [[Dór-o Estel]] have laws against unregistered binding.

### Bleed Points (1st level)

A pool of **Bleed Points (BP)**, max per the table. Gained (max once per trigger per round): taking damage from an attack/effect, an enemy within 30 ft dropping to 0 HP or being reduced to Bloodied by the Binder's attack, or failing a Focus or Sanity saving throw. No explicit [[Momentum]] interaction anywhere in this document — the first per-class deep-dive with zero Momentum mention, despite Bleed Points' gain triggers structurally resembling Momentum's own (taking damage, dropping an enemy) — flagged as an observation, not a contradiction.

**Spending**: **Push the Bind** (1 BP) — one extra damage die or impose disadvantage on a triggered save from a remnant's active ability, once per use. **Steady the Crack** (2 BP, reaction on taking damage) — reduce damage by 1d8 + Binder level. **Force the Bind** (3 BP, bonus action) — treat one additional unselected remnant as bound for 1 minute; can't reuse until a rest. All BP regained on a short or long rest.

> [!note] Proposed design addition — not in source
> Discussed with the user as a fix for Binder's zero-Momentum-interaction gap (see above). Not present in `.raw/Binder.md`; `.raw/` is immutable and was not edited. Suggested wording, offered here for the user's own design document, not treated as confirmed class content:
> **Momentum Surge** — When you spend a Bleed Point to Push the Bind and the triggered ability succeeds (the attack hits, or the target fails the imposed save), gain +1 Momentum, as the remnant's borrowed strength finds its rhythm inside you.
> Chosen over the two other options discussed (a flat trigger on any successful remnant active ability, or a Momentum gain on Rebinding mid-combat) because it mirrors Barbarian's Counterattack-via-forgoing-Evasion pattern — a spend-plus-success trigger, not a free one — keeping Momentum gain tied to Binder's actual risk/reward lever (Bleed Points) rather than to routine remnant use.

### Rebinding (2nd level)

Action: release one bound remnant, bind a different remnant of the same or lower Tier. Ongoing effects from the released remnant end; its Mark fades over the next minute. Once per rest; twice per rest at 15th level.

### Class Reactions (2nd level, and 7th) — confirmed universal, 5th class

Pool of Reaction Points = PB, refresh short/long rest — the same shared structure as [[Barbarian]]/[[Bard]]/[[Apothecary]]/[[Bender]], a fifth confirmation of [[Class Reactions]].

- **Borrowed Reflex** (2nd, 1 PB) — trigger: targeted by a visible attack; add CHA mod to the Evasion roll against it.
- **Remnant's Warning** (2nd, 1 PB) — trigger: an ally within 30 ft is targeted by an attack they can't see coming; that ally may immediately Evasion-roll against it (no bonuses requiring sight of the attacker).
- **Grasp from Beyond** (7th, 1 PB) — trigger: a creature within 15 ft tries to move away or Disengage; it STR saves (Binding Save DC) or its speed drops to 0 until the end of its turn.

### Binding Order (3rd level, and 6th, 10th, 14th) — full subclass detail, second class after Bender

Choose one of four Orders, each with features at 3rd/6th/10th/14th — full text below. No "such as" ambiguity here; this is an exhaustive, fully-detailed list like [[Bender]]'s Disciplines, not an incomplete example set like most other classes' subclasses.

### Ability Score Improvement (4th, 8th, 12th, 16th, 19th)

+2 to one score or +1 to two, max 20; optionally a feat instead.

### Second / Third / Fourth Remnant (5th, 11th, 17th level)

Remnants Bound increases to 2/3/4; Remnant Tier increases to 2 (5th) and 5 (17th, granting the full Bound Remnants list).

### Suppress/Reveal Signs (7th level)

Bonus action: hide or reveal all currently bound remnants' Manifest Marks; abilities remain fully usable either way.

### Adamant Mind (9th level)

Advantage on saves against charm, fright, possession, or thought/emotion-reading effects. On such a save's success against a visible creature, that creature takes psychic damage = Binder level + CHA mod.

### Heroic Boon (10th level)

Choose: **Boon of the Steady Vessel** (advantage on Focus saves resisting involuntary remnant bleed-through), **Boon of the Deep Well** (+2 max BP; Steady the Crack costs 1 BP instead of 2), or **Boon of the Open Door** (Binding Rite takes 1 minute instead of 10, once/long rest).

### Threadscarred (18th level)

Choose one currently bound remnant's Trait to retain permanently, even unbound, until switched (at the end of a long rest).

### Unbound (20th level, Epic Boon)

Choose: **Full Chorus** (bind one remnant beyond the normal max, 5 total; BP max → 8) or **The Last Door** (once/long rest, bind every remnant on the list simultaneously for 1 minute, gaining every Trait and active ability at once; costs 1 Exhaustion level afterward and locks out the Binding Rite until a long rest).

## Bound Remnants (full list, all 17)

Each has a Trait (passive) and an Active ability (bonus action unless stated, once/turn, saves use Binding Save DC).

### Tier 1 (1st level)

- **The Unmarked Soldier** — Trait: once/turn on a weapon hit, +1d6 damage of the weapon's type. Active (bonus action): brace — until your next turn, the first damage instance is reduced by 1d8 + CHA mod.
- **The Drowned Scholar** — Trait: advantage on INT (Investigation)/WIS (Insight) checks recalling or interpreting written information. Active (action): a creature within 30 ft WIS saves or takes 2d6 psychic + disadvantage on its next save before your next turn.
- **The Cornered Beast** — Trait: +10 ft walking speed. Active (bonus action): melee spell attack within 5 ft, 1d8 slashing, +1d8 more if the target already took damage this turn.
- **The Quiet Arsonist** — Trait: resistance to fire damage. Active (bonus action): a creature within 30 ft DEX saves or takes 2d6 fire (disadvantage on the save if flammable/dry brush, GM discretion).

### Tier 2 (5th level)

- **The Broken Oathkeeper** — Trait: reaction, an ally within 30 ft who fails a save gets +2 (declared before the outcome is known). Active (action): a creature within 60 ft that can hear you WIS saves or is compelled to move 15 ft toward/away (your choice) on its next turn.
- **The Unhealed Medic** — Trait: healing you or an ally within 5 ft receives adds CHA mod (min +1), once per instance. Active (action): touch heals 2d8 + CHA mod; once/rest, or 2 BP to reuse immediately.
- **The Silent Watcher** — Trait: advantage on WIS (Perception); can't be surprised while any remnant is bound. Active (action): truesight 30 ft until end of next turn.
- **The Frostbitten Guide** — Trait: resistance to cold; ice/snow difficult terrain costs no extra movement. Active (bonus action): a creature within 30 ft CON saves or takes 2d8 cold + speed halved until end of its next turn.

### Tier 3 (9th level)

- **The Unfinished Architect** — Trait: can't be involuntarily knocked prone on stable ground. Active (action): conjure a 20×10×1 ft Thread-glass wall within 60 ft (AC 5, 30 HP/10 ft section, 10 min or destroyed); once/short rest, or 3 BP to reuse.
- **The Unsent Letter** — Trait: telepathy with any creature within 60 ft that understands a language (they can block it). Active (action): a creature within 60 ft WIS saves or is charmed 1 minute, believing the Binder a trusted figure; ends if harmed.
- **The Hungering Debt** — Trait: dealing damage to a Bloodied creature grants 1 BP (once/turn, additive to the normal Bloodied-trigger). Active (bonus action): mark a creature within 60 ft — until end of next turn, damage it takes from any source adds 1d6 necrotic; only one mark at a time.
- **The Patient Hunter** — Trait: advantage on the first attack against a creature that hasn't acted yet. Active (bonus action): ranged spell attack within 90 ft, 2d10 piercing, ignores half/three-quarters cover.

### Tier 4 (13th level)

- **The Last Convocation** — Trait: advantage on CHA checks influencing groups of 3+. Active (action): self + 5 allies within 30 ft gain 1d8+Binder-level temp HP and advantage on their next save before your next turn.
- **The Collapsing Star** — Trait: resistance to radiant and necrotic damage. Active (action): creatures of choice within 20 ft of a point within 60 ft CON save or 4d10 force (half on success); once/rest, or 4 BP to reuse.
- **The Bound Executioner** — Trait: a critical hit grants 2 BP instead of the normal amount. Active (bonus action): melee spell attack on a Bloodied creature within 5 ft, 3d8 necrotic; a kill regains the Binder 1d8 HP.

### Tier 5 (17th level)

- **The Unwritten Ending** — Trait: once/long rest, dropping to 0 HP instead drops to 1. Active (action): reroll any one save/attack/damage roll made in the last 6 seconds by self or a creature within 60 ft (must use new result); once/long rest, or 6 BP to reuse.
- **The Fracture's Herald** — Trait: failing a Focus or Sanity save grants 2 BP instead of 1. Active (action, once/long rest): 15 ft radius rift within 60 ft — DEX save or 6d8 force + prone (half damage on success); everyone within 60 ft of the rift (including the Binder) Sanity saves or **gains 1 Whisper Point** — a new confirmed [[Whisper Points]] gain trigger, consistent with [[Fracture Whispers]]'s existing "failing a Sanity Save → yes" gain table.

## The Binding Orders (full text, all four)

- **The Chorus** (layer many voices): *We Are Several* (3rd) — bind one extra remnant beyond normal Remnants Bound after the Binding Rite, at least one Tier lower than the current max, not counted against other feature totals. *Layered Voice* (6th) — once/turn, apply a second bound remnant's Trait alongside an active ability's use, GM permitting. *Shared Burden* (10th) — gaining BP also grants a chosen ally within 30 ft temp HP = BP gained × 2. *Full Assembly* (14th) — the We Are Several bonus remnant no longer needs to be lower Tier.
- **The Severed** (a spectral double): *Manifest Double* (3rd) — bonus action, a double with the Binder's own scores and AC 10+DEX+CHA, no HP of its own (damage to it is instead taken by the Binder, halved); vanishes on unconsciousness/dismissal/30+ ft separation (reappears at the Binder's side); one attack/turn can route through it. *Split Focus* (6th) — Disengage/Dodge through the double without spending the Binder's own action. *Twinned Strike* (10th) — once/turn, a hit through the double also allows a personal weapon attack, no extra action. *Trade Places* (14th) — bonus action swap positions with the double within 30 ft, once/rest.
- **The Hollow Path** (restraint and control): *Suppression as Strength* (3rd) — bonus action, suppress a remnant (lose its Trait/active) for +2 Evasion and advantage on Focus saves until resumed (also bonus action). *Controlled Release* (6th) — resuming a suppressed remnant grants 1 BP and removes that turn's action-economy restriction on its next active-ability use, once. *Vestigial Precision* (10th) — once/turn, grant advantage on one d20 roll tied to a bound remnant's save-triggering ability; once/rest. *Perfect Stillness* (14th) — resistance to psychic damage and disadvantage on others' checks to sense the Binder's mental/emotional state, while any remnant is suppressed.
- **The Cartographers** (precision over breadth): *Precise Binding* (3rd) — +1 Binding Save DC; 1 BP converts a failed Focus save (bleed-through) into a success. *Charted Rebind* (6th) — once/long rest, Rebind without spending the daily use, if the new remnant is same Tier or lower. *Annotated Grasp* (10th) — a single-target active ability can also hit a second creature within 10 ft (half effect, advantage on its save). *The Complete Map* (14th) — once/long rest, the Binding Rite may access one Tier higher than normal.

## Last Stand (confirmed universal, 5th class — standard permanent-death clause, no exception)

| Option | Effect |
|---|---|
| Every Door at Once | Every remnant ever bound (not just currently bound) tears loose in a 30 ft radius; chosen creatures WIS save (Binding Save DC) or are frightened 1 min + take 6d8 psychic (half damage, no fear on success); allies in the radius gain temp HP = Binder level × 3 + advantage on their next save |
| The Debt Comes Due | One enemy within 60 ft damaged earlier this combat CON saves (Binding Save DC) or drops to 0 HP immediately; on success, takes damage = half current HP and is knocked prone |
| Unfinished Business | An ally within 30 ft immediately takes a full out-of-turn-order turn, and for that turn may use any one of the Binder's currently bound remnants' active abilities as if they were the Binder (Binder's DC/attack mod) |

All three options reaffirm the standard permanent-death clause explicitly ("Once a Last Stand is invoked, the character permanently dies... cannot return this character to life") — unlike [[Bender]]'s Elemental Rebirth exception, Binder's options don't break this rule. Fifth class confirming [[Last Stand]] as universal.

## Weapon Mastery: total silence, resolves an old open question

[[Weapon Mastery System]]'s tier table (Fighter/Full Martials/Half-Martials/Non-Martials) never listed Binder in any category — flagged at the time as an unresolved gap. This per-class deep-dive doesn't mention Weapon Mastery, mastered weapons, or Weapon Skills once across its full ~650 lines; Binder's proficiencies are simple weapons only, and every Remnant ability is a spell attack (melee or ranged), not a weapon attack. This is strong evidence — not explicit confirmation — that Binder simply doesn't participate in the Weapon Mastery subsystem the way every other ingested class does, rather than the profile being merely "unknown." Updated on [[Weapon Mastery]] accordingly.

## Multiclassing, party role, and setting notes (condensed)

Multiclass prerequisite: CHA 13+. Bleed Points don't merge with other classes' point pools. Remnants Bound/Tier are read off the Binder table using only Binder levels. Recommended multiclass pairings: Charisma casters (Warlock/Sorcerer/Bard) for shared stat, Fighter/Barbarian for a durable host chassis, Rogue for the Severed's double tactics. A 1-level dip nets one Tier-1 remnant + 2 BP; a 3-level dip is the practical minimum to pick up a Binding Order. In [[Dór-o Estel]], Binders draw the same wariness once reserved for the old Summoners (sometimes worse, since the Marks are visible) — registration, monitoring, or arrest in some Loom-Cities; "mourner-for-hire" status in others that lost people to the Fracture.

## See also

- [[Classes_Summary]]
- [[Class_breakdown]]
- [[FEARS Class Roster]]
- [[Weapon Mastery]]
- [[Whisper Points]]
- [[Focus]]
- [[Momentum]]
- [[Dór-o Estel]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
