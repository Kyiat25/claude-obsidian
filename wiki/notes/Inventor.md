---
type: entity
title: "Inventor"
address: c-000012
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
first_mentioned: "[[Welcome to FEARS]]"
related:
  - "[[Welcome to FEARS]]"
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Narrative Identity]]"
  - "[[Class_breakdown]]"
  - "[[Weapon Mastery]]"
  - "[[Damage Reduction]]"
  - "[[Momentum]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Welcome to FEARS]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - ".raw/Inventor.md"
confidence: high
---

# Inventor — Controlled Innovation

**Half-Caster tier**. "Any sufficiently prepared Inventor is indistinguishable from magic." A spell is treated as a component, same as iron or leather — the measure of a good Inventor is how cleverly they use what they have, not how much magic they know. Complexity self-rated MODERATE (6/10) by its own per-class deep-dive.

> "Any sufficiently prepared Inventor is indistinguishable from magic."

## Signature abilities

- **Constructs/Turrets** — act independently
- **Modifications** — adapt tools mid-combat
- **Field Engineering** — shape battlefield dynamics

**Gameplay style**: battlefield architect, controlling space, tempo, and engagement through creations. **Core loop**: deploy → modify → trigger → refine. Struggles without preparation for the current situation; excels in any scenario it could see coming, or any encounter where gadgets/constructs/infused items compound.

## Class basics (from Inventor.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium. Weapons — simple, hand crossbows, heavy crossbows. Tools — thieves' tools + one other of choice. Saves — Focus, Intelligence (the first confirmed Focus-as-a-saving-throw class, distinct from the still-open Focus Save/Focus check questions on [[Focus]]). Skills — choose three from Arcana, Crafting, Deception, Gathering, History, Investigation, Medicine, Nature, Religion, Sleight of Hand.
- **Starting Equipment**: (a) light crossbow + 20 bolts or (b) any two simple weapons; (a) scale mail, (b) leather, or (c) chain mail (if proficient); thieves' tools and a dungeoneer's pack.
- **Quick Build**: Intelligence highest, then Constitution. Any lineage (Gnome, Human, Dwarf thematic). Guild Artisan/Sage or a Crafting/Arcana background. Distribute infused items pre-combat; use Emergency Gadget reactively; target Called Shots at unprotected locations for maximum DR bypass.

## Level progression (1st-20th)

| Level | PB | Features | Spells | 1st | 2nd | 3rd | 4th | 5th | Upgrades |
|---|---|---|---|---|---|---|---|---|---|
| 1 | +2 | Inventor Specialisation, Magic Item Analysis | — | — | — | — | — | — | — |
| 2 | +2 | Spellcasting, Arcane Retrofit, Tool Expertise | 2 | 2 | — | — | — | — | — |
| 3 | +2 | Specialisation Upgrade, Engineered Guard | 3 | 3 | — | — | — | — | 1 |
| 4 | +2 | Improvement | 3 | 3 | — | — | — | — | 1 |
| 5 | +3 | Weapon Mastery, Specialisation Feature | 4 | 4 | 2 | — | — | — | 2 |
| 6 | +3 | Arcane Reconstruction, Cross-Disciplinary Knowledge | 4 | 4 | 2 | — | — | — | 2 |
| 7 | +3 | Wondrous Item Proficiency, Class Reactions | 5 | 4 | 3 | — | — | — | 3 |
| 8 | +3 | Improvement | 6 | 4 | 3 | — | — | — | 3 |
| 9 | +4 | Specialisation Upgrade | 7 | 4 | 3 | 2 | — | — | 4 |
| 10 | +4 | Improved Magical Crafting, Wondrous Item Recharge, Heroic Boon | 7 | 4 | 3 | 2 | — | — | 4 |
| 11 | +4 | Study of Magic | 8 | 4 | 3 | 3 | — | — | 5 |
| 12 | +4 | Improvement | 8 | 4 | 3 | 3 | — | — | 5 |
| 13 | +5 | Specialisation Upgrade | 9 | 4 | 3 | 3 | 1 | — | 6 |
| 14 | +5 | Specialisation Feature | 9 | 4 | 3 | 3 | 1 | — | 6 |
| 15 | +5 | Specialisation Upgrade | 10 | 4 | 3 | 3 | 2 | — | 7 |
| 16 | +5 | Improvement | 10 | 4 | 3 | 3 | 2 | — | 7 |
| 17 | +6 | Wondrous Item Mastery | 11 | 4 | 3 | 3 | 3 | 1 | 8 |
| 18 | +6 | Peerless Inventor | 11 | 4 | 3 | 3 | 3 | 1 | 8 |
| 19 | +6 | Improvement | 12 | 4 | 3 | 3 | 3 | 2 | 9 |
| 20 | +6 | Epic Boon | 12 | 4 | 3 | 3 | 3 | 2 | 9 |

## Core class features (full text)

### Inventor Specialisation (1st level)

Choose an engineering discipline: **Gadgetsmith, Golemsmith, Infusionsmith, Potionsmith, Thundersmith, Warsmith, Fleshsmith, Cursesmith, Runesmith, or Relicsmith**. Features at 1st, 3rd, 5th, and 14th level — full detail deferred to a separate Inventor Subclasses document, not included in this source.

### Magic Item Analysis (1st level)

Knows *detect magic* and *identify*, castable as rituals without material components — practical assessment, "reading engineering, not reciting formulae."

### Spellcasting (2nd level) — sixth confirmed caster DC formula, first Intelligence-based

Intelligence is the spellcasting ability. **Spell Save DC = 8 + PB + Intelligence modifier. Spell Attack Modifier = PB + Intelligence modifier.** Sixth independent confirmation of the `8 + PB + ability mod` formula, and the **first** confirmed on an Intelligence-based caster (previous five were WIS or CHA: [[Bard]], [[Bender]], [[Binder]], [[Cleric]], [[Druid]]) — good evidence the formula generalizes across every spellcasting ability score, not just WIS/CHA. Knows spells from the Inventor list per the table; regains all slots on a long rest; can use an arcane focus or any proficient tool as a spellcasting focus.

### Arcane Retrofit (2nd level)

During a long rest, ritual-transfer a +1/+2/+3 weapon's magical bonus (excluding artefacts/sentient weapons) into an Inventor weapon; the original is destroyed. Can similarly convert magical-AC armour to a lighter armour type.

### Tool Expertise (2nd level)

PB doubled for ability checks using tool proficiencies gained from this class.

### Specialisation Upgrade (3rd level, and 9th, 13th, 15th)

Choose an upgrade from the Specialisation list; gains scale per the Upgrades column. No duplicate upgrades unless stated otherwise; may swap one upgrade for another (same or lower level) on levelling. **Generic Upgrades** available regardless of Specialisation: Shield Proficiency, Tool Proficiency.

### Engineered Guard (3rd level) — new Damage Reduction class hook

While wearing armour the Inventor has modified or created (including anything bearing their infusions/upgrades/modifications): **+1 DR to all body locations**. Stacks with base armour DR, but not with other Inventor features that explicitly grant DR.

### Weapon Mastery (5th level) — confirms Weapon Mastery System with zero drift

Mastery with one simple weapon + one additional weapon granted by Specialisation (if applicable). New masteries via critical hits: **2 crits for simple weapons, 3 for martial** — exactly matching [[Weapon Mastery]]'s existing "Full Martials" row, which already lists Inventor by name. DCS synergy: Weapon Skills as tactical levers (Shatter Guard reduces DR for a construct's next attack; Hamstring controls movement to feed a deployed trap).

### Arcane Reconstruction (6th level)

Learns *mending* (at will) and *cure wounds* (or a different spell if already known); constructs targeted by *cure wounds* heal normally — "biological repair and mechanical repair are the same discipline applied to different substrates."

### Cross-Disciplinary Knowledge (6th level)

Choose one cross-Specialisation feature: a Gadgetsmith Unrestricted Upgrade; an Infusionsmith's Animated Weapon/Blasting Rod/Infused Weapon; a Potionsmith's Alchemical Reagent Pouch + Alchemical Fire or Acid; a Thundersmith's Stormforged Weapon (+ ammunition knowledge). Lost/destroyed crafted items can be recreated on a long rest.

### Wondrous Item Proficiency (7th level)

Ignores class restrictions on magic item use; attunement slots increase to **4**.

### Improved Magical Crafting (10th level)

Can craft/modify magical items of Uncommon rarity or below during downtime without a special formula.

### Wondrous Item Recharge (10th level)

Short rest: recharge one magic item's expended charges (roll its recharge die). Uses = INT mod per long rest.

### Heroic Boon (10th level)

Choose: **Boon of the Master Tinkerer** (once/short rest, 10 minutes to grant an attuned item one additional GM-approved property until next long rest) or **Boon of the Arcane Forge** (once/long rest, 10 minutes to craft a single-use Uncommon-or-lower item that crumbles after one use).

### Study of Magic (11th level)

On casting a spell, apply one free modification: change damage type (acid/fire/cold/lightning/thunder), adjust range ±30 ft, or change area-of-effect shape (cone↔cylinder, sphere↔cube of similar size).

### Wondrous Item Mastery (17th level)

Attunement slots increase to **5**; any wondrous item usable as a bonus action instead of an action.

### Peerless Inventor (18th level)

Once/long rest, action: assemble one of — **Arcane Cannon** (2d10 force, 60 ft line or 20 ft cone, 10 minutes, bonus-action fire), **Mechanical Ally** (Iron Golem stat block at half HP, 1 hour, simple commands), or **Emergency Barrier** (60 ft wall of force-reinforced metal, 10 minutes, 100 HP).

### Epic Boon (20th level)

Choose: **Boon of Limitless Creation** (once/short rest, instant mundane/alchemical item ≤100gp; crafting time halved and cost −25% for magic items; attunement slots to 6) or **Boon of Arcane Perfection** (ignore material components including expensive ones; once/long rest cast any Inventor spell ≤5th without a slot; all crafted items masterwork, +1 effectiveness).

## Last Stand (confirmed universal, 9th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| The Last Gadget | Choose one: Null Field (60 ft, suppresses magic 1 min; CON save DC 10+PB+INT or 6d10 lightning + Staggered until end of next turn); Golem Final Protocol (summon a CR-equal-to-level construct, 1 min, simple commands); Proximity Network (60 ft, 8d10 thunder, DEX save DC 10+PB+INT for half) |
| Appreciation | Teleport all attunement items to chosen allies (no attunement required, no per-ally limit); all gadgets/infused items function at max potency for 5 minutes; allies may pass magic items between themselves within 60 ft as a bonus action |
| Deadman's Switch | INT-mod (min 2) allies each get one of: all spell slots restored, all class resource uses restored, temp HP = 3×Inventor level, or a free move + advantage on next attack/save. Plus one environmental trigger: Hazard Grid (60 ft difficult terrain + 2d8 thunder/turn, 1 min), Barrier Network (up to 120 ft of force barriers, 1 min), or Emergency Extraction (allies within 60 ft teleport to a pre-designated safe point) |

Ninth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

## Class Reactions (confirmed universal, 9th class — 7th-level gate ruled intentional)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest — but explicitly stated as **available from 7th level**, later than any other class's reactions confirmed so far (most start at 2nd or 3rd).

> [!note] Ruled: intentional slow-build design
> Inventor's identity is built around preparation — it "struggles without preparation... excels in any scenario it could see coming" — and its reactive tricks depend on having Specialisation Upgrades and other options already banked. The late gate reflects that dependency rather than a documentation gap.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Emergency Gadget | 7th | Self or an ally within 30 ft is hit by an attack or targeted by a spell | Deploy a stored Specialisation gadget/invention that normally needs an action, as part of the reaction. Defensive effects (cover, obscurement, DR, forced saves) apply before the triggering damage resolves |
| Infusion Burst | 7th | Self or an ally within 30 ft takes damage from an attack | Reduce the triggering damage by 2d6+INT mod (3d6+INT at 11th, 4d6+INT at 15th), or trigger the infused item's offensive/utility effect instead. **New Momentum interaction**: if the attack would have dropped the target below their Bloodied threshold, the attacker loses 1 Momentum |
| Overclock | 7th | Attack action hits with an Inventor weapon or infused weapon | Roll an extra weapon damage die; target CON saves (DC 8+PB+INT) or has DR reduced by 2 until the Inventor's next turn |

## See also

- [[Welcome to FEARS]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[FEARS Class Roster]]
- [[Weapon Mastery]]
- [[Damage Reduction]]
- [[Momentum]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
