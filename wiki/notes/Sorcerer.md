---
type: entity
title: "Sorcerer"
address: c-000067
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
  - "[[Momentum]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
  - "[[The Weave]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - ".raw/Sorcerer.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Sorcerer — Magic Incarnate

**Full Caster tier**. "Magic doesn't flow *through* you. It is *you*." The only class whose subclass ("Sorcerous Origin") is chosen at 1st level and is explicitly framed as *the* class-design axis rather than a mid-game specialization — the source states outright that a Draconic Sorcerer, Wild Magic Sorcerer, and Divine Soul "are not flavors of the same thing... different classes that happen to share spell slots." Complexity self-rated MODERATE by its own frontmatter, though the actual mechanical density (rich sorcery-point economy, four separate reaction-triggered features, per-origin subsystems) reads closer to the HIGH end of this cluster.

> "Magic doesn't flow through you. It is you, and every spell you cast is a form of self-expression so primal that even the gods once took notice."

## Format outlier — the most structurally divergent per-class source this session

Unlike every other per-class deep-dive, this document: uses an `avatar` image-block header instead of the standard narrative-quote opening; states **"Sorcerers do not gain Weapon Mastery"** outright rather than leaving it to inference (the strongest possible confirmation of [[Weapon Mastery]]'s existing Non-Martials listing); embeds its reactions inline within Feature Descriptions rather than consolidating them under one "Class Reactions" heading; includes a **Universal Conversion Rules** table for adapting any published 5E Sorcerous Origin, and a **Momentum Integration by Origin Theme** table providing default Momentum triggers for origins with no built-in one — a generalizable design meta-system no other class's deep-dive has attempted; and originally shipped with no Last Stand section at all (closed post-ingest — see below).

## Signature abilities

- **Metamagic** — modifies spells dynamically
- **Resource Conversion** — trades power for flexibility
- **Innate Casting** — raw magical output

**Gameplay style**: flexible blaster, adapting spells as situations change. **Core loop**: cast → modify → convert → repeat. Thrives in magic-heavy campaigns (enemy spellcasters, cursed items, magic traps all feed Arcane Metabolism); in martial-heavy campaigns the absorption features go dormant and it plays like a strong standard Arcane caster.

## Class basics (from Sorcerer.md deep-dive)

- **Hit Dice**: 1d6/level. HP at 1st: 6 + CON mod. HP at higher levels: 1d6 (or 4) + CON mod/level after 1st.
- **Proficiencies**: Armour — none. Weapons — simple. Tools — none. Saves — Constitution, Charisma. Skills — choose two from Arcana, Deception, Insight, Intimidation, Memory, Persuasion, Religion, Resolve.
- **Starting Equipment**: (a) light crossbow + 20 bolts or (b) any simple weapon; (a) dungeoneer's or (b) explorer's pack; two daggers. **No arcane focus or component pouch** — the body is the focus (see Innate Casting).
- **Quick Build / party fit**: "The party wants a Sorcerer when they need someone defined by their origin, not their training... you don't just survive magical encounters, your very nature transforms them into fuel."

## Level progression (1st-20th)

| Level | PB | SP | Features | Cantrips | Spells Known |
|---|---|---|---|---|---|
| 1 | +2 | 2 | Sorcerous Origin, Font of Magic, Spellcasting, Innate Casting, Arcane Metabolism | 3 | 2 |
| 2 | +2 | 3 | Metamagic (2), Arcane Deflection | 3 | 3 |
| 3 | +2 | 4 | Origin Feature, Volatile Aura | 3 | 4 |
| 4 | +2 | 5 | Improvement, Arcane Intercept | 4 | 5 |
| 5 | +3 | 6 | Sorcerous Renewal (1d4+1) | 4 | 6 |
| 6 | +3 | 7 | Metamagic (3), Origin Feature | 4 | 7 |
| 7 | +3 | 8 | Metaflux Veil | 4 | 8 |
| 8 | +3 | 9 | Improvement | 4 | 9 |
| 9 | +4 | 10 | Sorcerous Renewal (2d4+1) | 4 | 10 |
| 10 | +4 | 11 | Heroic Boon, Origin Feature | 5 | 11 |
| 11 | +4 | 12 | Metamagic (4) | 5 | 12 |
| 12 | +4 | 13 | Improvement | 5 | 12 |
| 13 | +5 | 14 | Sorcerous Renewal (3d4+1) | 5 | 13 |
| 14 | +5 | 15 | Devour Spell, Origin Feature | 5 | 13 |
| 15 | +5 | 16 | Magical Shell | 5 | 14 |
| 16 | +5 | 17 | Improvement | 5 | 14 |
| 17 | +6 | 18 | Sorcerous Renewal (4d4+1), Metamagic (5) | 5 | 15 |
| 18 | +6 | 19 | Origin Feature | 5 | 15 |
| 19 | +6 | 20 | Improvement | 5 | 15 |
| 20 | +6 | 21 | Epic Boon | 5 | 15 |

SP = Sorcery Points.

## Core class features (full text)

### Sorcerous Origin (1st level, and 3rd, 6th, 10th, 14th, 18th)

Choose the source of innate power: **Draconic Bloodline, Wild Magic, Divine Soul, Shadow Magic, Aberrant Mind, Clockwork Soul**, or any published 5E origin via the Universal Conversion Rules. Permanent barring GM-approved narrative change. Determines spell access, resource mechanics, defensive identity, combat role, and campaign contribution — features at 1st/3rd/6th/10th/14th/18th.

### Font of Magic (1st level)

**Sorcery Points**: start at 2, scale per the table, full recovery on a long rest. **Flexible Casting**: bonus action to convert a spell slot to SP (= slot circle) or SP to a slot (1st=2, 2nd=3, 3rd=5, 4th=6, 5th=7 SP; created slots vanish on a long rest). **Empowering Reserves** (2 SP: +CHA mod to one ability check), **Imbuing Touch** (2 SP: nonmagical item becomes magical for 1 hour), **Sorcerous Fortitude** (any SP for 2×temp HP), **Reroll** (1 SP: reroll a failed ability check).

### Spellcasting (1st level) — confirms the universal DC formula again, CHA-based

Cantrips (3, scaling) and Spells Known (2, scaling) from the Arcane list; may swap one known spell per level. **Spell Save DC = 8+PB+CHA, Spell Attack = PB+CHA.**

### Innate Casting (1st level)

Body is the spellcasting focus — no arcane focus/component pouch/external tool ever needed; components with no gp cost are waived entirely.

### Arcane Metabolism (1st level)

Taking damage from a visible creature's spell **automatically** (no reaction) converts damage equal to the spell's circle (min 1) into temporary sorcery points, lasting until the next long rest. DR/resistance applies before Metabolism reads the remaining damage.

### Metamagic (2nd level, and 6th, 11th, 17th)

Knows 2 options at 2nd level (+1 at 6th/11th/17th, total 5 by 17th): **Heightened Spell** (3 SP, target saves at disadvantage), **Twinned Spell** (SP = spell circle, single-target spell hits a second creature), **Quickened Spell** (2 SP, cast as bonus action), **Subtle Spell** (1 SP, no V/S components), **Empowered Spell** (1 SP, reroll CHA-mod damage dice, keep new), **Careful Spell** (SP = spell circle, CHA-mod creatures auto-succeed the save), **Distant Spell** (1 SP, double range or self→30 ft). **Flexible Metamagic**: multiple options stackable on one spell if SP allows.

### Arcane Deflection (2nd level, reaction)

Taking damage from a visible creature within 30 ft: spend 1 SP, they CHA save (DC = 8+PB+CHA) — fail: damage halved, success: damage reduced by a quarter. Either way, gain temp SP = the spell's circle (min 1).

### Volatile Aura (3rd level, reaction, explicit Class Reactions pool use)

Taking damage from any source: spend 1 Class Reactions pool use, choose one: **Elemental Retaliation** (creatures within 5 ft DEX save, DC 8+PB+CHA, or take 1d6 origin-typed damage, scaling to 2d6/5th, 3d6/11th, 4d6/17th), **Momentum Surge** (+2 Momentum), or **Arcane Echo** (creatures within 10 ft INT save, DC 8+PB+CHA, or blinded until end of their next turn).

### Arcane Intercept (4th level, reaction, explicit Class Reactions pool use)

A visible creature within 30 ft casts a spell targeting another creature: spend 1 Class Reactions pool use, then either **Intercept (Quick)** (1 SP, redirect the spell to self) or **Intercept (Full)** (2 SP, cancel it entirely, gain temp SP = its circle, min 1). Uses = PB, long rest recovery.

### Sorcerous Renewal (5th level, and 9th, 13th, 17th)

Short-rest SP recovery: 1d4+1 at 5th, 2d4+1 at 9th, 3d4+1 at 13th, 4d4+1 at 17th — on top of full long-rest recovery.

### Metaflux Veil (7th level, reaction) — inconsistent pool attribution

Taking damage from a visible spell: spend 1 SP, choose **Deflect** (half damage) or **Charge** (quarter damage + temp SP = circle, min 1). **Unlike Volatile Aura/Arcane Intercept, this feature's own text never mentions the Class Reactions pool** — only the Resource Awareness summary table later claims it draws from that pool. Same inconsistency affects Arcane Deflection above. Flagged as a source-internal mismatch between individual feature text and its own summary table, not resolved.

### Heroic Boon (10th level)

Choose: **Arcane Fusion** (Metamagic costs −1 SP, min 0; two Metamagic options stack for free) / **Spellsense** (sense active magical auras within 60 ft; 1 minute concentration, no Focus cost, to identify a spell's school/circle) / **Arcane Reflection** (taking spell damage grants +1 AC and saves until the Sorcerer's next turn).

### Devour Spell (14th level, reaction)

A visible creature within 30 ft targets the Sorcerer (or includes them in an area) with a spell: CHA save vs. the caster's Spell Save DC — success: spell negated, gain SP = 2×circle (min 2); failure: spell affects normally, gain SP = circle (min 1). Once/long rest, or pay 4 SP to reuse before the next long rest.

### Magical Shell (15th level)

Resistance to spell damage; Arcane Metabolism's temp-SP gain is doubled.

### Epic Boon (20th level)

Choose: **Arcane Conjunction** (reaction, no cost, redirect a targeting spell to another creature in range, once/long rest; plus CHA-mod free *counterspell* uses/long rest) / **Boundless Sorcery** (SP fully refills on a short *or* long rest; max SP spendable on one action rises from PB to CHA mod) / **Arcane Avatar** (origin-specific capstone — e.g. Draconic gains damage-type resistance + 5-SP advantage-on-spell-attacks; Wild Magic doubles Surges/turn; Divine Soul gets at-will *spirit guardians*; Shadow Magic gets 60 ft blindsight in darkness + at-will *shadow step*; other origins negotiated with the GM).

## Sorcerous Origins (fully detailed for two; a conversion framework for the rest)

### Draconic Bloodline

**Draconic Ancestry** (1st: choose a dragon type/element, matching-element spells gain +CHA-mod damage). **Draconic Resilience** (1st: max HP +1/level; unarmoured AC = 13+DEX mod). **Draconic Momentum** (1st: dealing ancestor-element spell damage grants +1 Momentum). **Elemental Affinity** (3rd: +CHA mod to one damage roll of a matching-element spell; 1 SP for 1-hour resistance to that element). **Dragon Wings** (6th: bonus action, 60 ft fly speed, dismissible, blocked by non-accommodating armour). **Draconic Presence** (10th: 5 SP, 60 ft aura, 1 minute concentration via Focus — entering hostiles WIS save vs. Spell Save DC or charmed/frightened, choice of the Sorcerer's; 24-hour immunity on success). **Draconic Ascendance** (14th: immune to ancestor's damage type; spend up to 5 extra SP on a matching spell for +1d6/point). **Dragon Incarnate** (18th: 7 SP, 10 minutes, Large size, 80 ft fly, +2 STR/CON, +2 Spell Save DC; ends early if knocked unconscious).

### Wild Magic

**Chaotic Heritage** (1st: once/long rest, casting a 1st-circle+ spell rolls a d10 — a 1 triggers the Wild Magic Surge table). **Tides of Chaos** (1st: once/long rest, advantage on an attack/check/save; using it flags the next spell cast for a GM-rolled Surge check). **Bend Luck** (1st: 2 SP reaction, ±1d4 to another creature's roll after seeing it but before the outcome). **Controlled Chaos** (3rd: 2 SP, roll twice on the Surge table and choose). **Chaotic Spell** (6th: spend up to 3 extra SP, one Surge-table roll attempt per point spent). **Wild Surge Mastery** (10th: 5 SP to choose a Surge result instead of rolling). **Cascading Chaos** (14th: a Surge grants +2 Momentum and a free bonus-action cantrip). **Avatar of Chaos** (18th: 7 SP, 10 minutes — Surges trigger on 1-3 instead of just 1; +3 Momentum at the start of every turn; ends early if knocked unconscious).

### Other origins (Divine Soul, Shadow Magic, Storm Sorcery, Aberrant Mind, Clockwork Soul, or any published 5E origin)

Adaptable via **Universal Conversion Rules**: bonus spell slots → bonus SP equal to slot circle (once/long rest); Concentration (CON saves) → Focus saves; Wild Magic Surge rolls stay Wild-Magic-exclusive, never granted to base-class reactions; bonus Metamagic options stack on top of the standard progression; Elemental-Affinity-style damage bonuses apply to damage dealt with no Metabolism interaction; a 3rd-level origin feature that defines the origin's identity should move to 1st level instead. A **Momentum Integration by Origin Theme** table supplies a default trigger for any origin lacking one: Elemental/Draconic → damage of your element with a spell = +1 Momentum; Shadow/Necrotic → reducing a creature to 0 HP with a spell = +1 Momentum; Wild/Chaos → a Surge = +2 Momentum; Divine/Radiant → healing with a spell = +1 Momentum to both caster and target; Psionic/Aberrant → a creature failing a save against the Sorcerer's spell = +1 Momentum.

## Last Stand Options

> [!note] Gap closed post-ingest
> The original per-class deep-dive had no Last Stand section — confirmed as a genuine design gap (not an incomplete-source artifact) and closed with the options below, provided directly rather than sourced from `.raw/Sorcerer.md`. See [[Last Stand]] for the cluster-wide resolution.

| Option | Effect |
|---|---|
| Arcane Cataclysm | 40 ft radius explosion centered on self; chosen creatures DEX save (DC 10+PB+CHA) — fail: 10d10 force damage + prone; success: half damage, no prone. Destroys terrain/unreinforced objects in range |
| Well of Power | For 1 minute, allies within 100 ft may cast any of the Sorcerer's known spells using the Sorcerer's remaining spell slots, auto-upcast to max level, using the Sorcerer's CHA mod for save DC/attack rolls |
| Wild Surge Unleashed | All creatures within 60 ft (allies included) immediately roll on the Wild Magic Surge table (one reroll per creature allowed); the area becomes a Wild Magic Zone for 10 minutes — any spell cast there triggers another surge roll |

Reaffirms the standard permanent-death clause (not stated otherwise). Arcane Cataclysm's DC (`10+PB+CHA`) matches the canonical Last Stand DC base. With this addition, Sorcerer is the 24th and final class with a documented Last Stand table — the mechanic is now confirmed universal across the entire roster.

## Class Reactions: present in substance, absent in structure

Unlike every other class, this source never groups its reactions under a single "Class Reactions" heading — Arcane Deflection, Volatile Aura, Arcane Intercept, and Metaflux Veil are scattered across Feature Descriptions at their respective levels instead. Functionally, two of the four (Volatile Aura, Arcane Intercept) explicitly consume "a Class Reactions pool use," matching the shared PB-pool default every other class confirms; the other two (Arcane Deflection, Metaflux Veil) only cost sorcery points in their own feature text, yet the source's own **Resource Awareness** summary table lists all four as drawing from the Class Reactions Pool. Treated as a source-internal inconsistency (summary table vs. individual feature text), not fully resolved — see the Metaflux Veil note above. With that caveat, this still counts as the nineteenth class confirming the underlying mechanic exists, even without a tidy consolidated section.

| Reaction | Level | Trigger | Effect | Stated pool use? |
|---|---|---|---|---|
| Arcane Deflection | 2nd | Damage from a visible creature within 30 ft | 1 SP; CHA save (DC 8+PB+CHA) halves or quarters the damage; gain temp SP = circle | Not in feature text (only in summary table) |
| Volatile Aura | 3rd | Damage from any source | Elemental Retaliation, Momentum Surge (+2 Momentum), or Arcane Echo | Yes, explicit |
| Arcane Intercept | 4th | A visible creature casts a spell targeting another | Redirect (1 SP) or cancel (2 SP, gain temp SP) | Yes, explicit |
| Metaflux Veil | 7th | Damage from a visible spell | 1 SP; Deflect (half) or Charge (quarter + temp SP) | Not in feature text (only in summary table) |

## Mythology & Cultural Lore (from the Class Lore Compendium)

*Bloodline-Touched: Those Born With Power Running Through Their Veins.*

When Astralor wove the nine Fundamental Forces into reality, some mortals were born with fragments of those forces already embedded in their souls — not learned, not granted, but inherited. The First Age's Sorcerous Houses cultivated distinct bloodline types (Dragon-Blooded, Fey-Touched, Shadow-Born, Divine-Sparks, Elemental-Veined) through selective breeding, most infamously the Sorcerous Emperors — a dragonborn dynasty that ruled Ashkarra entirely through inherited fire-magic, concentrating power in a single lineage until the city's fall scattered or destroyed it. The Fourth Age's Thread instability now triggers spontaneous sorcerous manifestation in mortals with no magical ancestry at all, a crisis for any society that tried to regulate magic as a bloodline-inheritable resource.

**Source of Power (DM truth):** Sorcerers believe their power is literally genetic — cosmic fragments diluted but never eliminated across generations. In truth, sorcerous "bloodlines" are karmic rather than biological: sorcerers inherit metaphysical patterns, echoes of cosmic forces their ancestors touched, carried in the soul rather than the blood. When a sorcerer manifests power, they access ancestral memory embedded in spirit — which is why sorcery can theoretically manifest in anyone whose soul carries sufficient cosmic imprint, explaining the Fourth Age's spontaneous awakenings independent of known lineage.

**Legendary figures:** The Sorcerous Emperors, the dragonborn dynasty whose every ruler was born sorcerer, concentrating inherited fire-magic into a single bloodline that governed Ashkarra until its fall.

*"I didn't ask for this. Didn't earn it. Didn't deserve it. I was simply born with fire in my veins and lightning in my heart... I didn't choose magic. Magic chose me. And I'll spend my life proving I'm worthy of that choice."* — The Sorcerer's Burden

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Momentum]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
