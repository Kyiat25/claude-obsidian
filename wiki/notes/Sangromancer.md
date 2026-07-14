---
type: entity
title: "Sangromancer"
address: c-000016
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
  - "[[Narrative Identity Framework]]"
  - "[[Class_breakdown]]"
  - "[[Momentum]]"
  - "[[Injury System]]"
  - "[[Corruption]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
  - "[[The Weave]]"
sources:
  - "[[Welcome to FEARS]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - ".raw/Sangromancer.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Sangromancer — Blood is Power

**Full Caster tier**. "You are not a reckless monster. You are a calculator. Every spell is a negotiation — between what you want and what your body can afford." The only caster who casts with HP instead of spell slots, and the only one who gets stronger as a fight drags on, because a longer fight means more bleeding enemies to feed on. Complexity self-rated HIGH (8/10) by its own per-class deep-dive.

> "You are not a reckless monster. You are a calculator. Every spell is a negotiation — between what you want and what your body can afford."

## Signature abilities

- **Blood Magic**
- **Self-Sacrifice Mechanics**
- **Life Drain**

**Gameplay style**: high-risk caster, balancing power and survival. **Core loop**: spend HP → gain power → recover → repeat. Excels in long fights against multiple bloodied targets (Vitae Harvest keeps HP afloat); struggles in fights that end before its feedback loops engage. **Warning built into the class itself**: a Sangromancer can die from their own abilities — casting below 30% HP accumulates Vitae Strain, and some subclass features have permanent HP costs.

## Class basics (from Sangromancer.md deep-dive)

- **Hit Dice**: 1d6/level (the fragile end of the HP spectrum, fitting an HP-as-resource caster). HP at 1st: 6 + CON mod. HP at higher levels: 1d6 (or 4) + CON mod/level after 1st.
- **Proficiencies**: Armour — **none** (blood magic requires exposed skin; multiclassing into an armoured class forces a choice between armour and casting). Weapons — simple, scimitars, shortswords. Tools — none. Saves — Constitution, Intelligence. Skills — choose two from Arcana, History, Insight, Intimidation, Investigation, Medicine, Nature, Religion.
- **Starting Equipment**: (a) scimitar or (b) any simple weapon; (a) component pouch or (b) arcane focus; (a) scholar's or (b) dungeoneer's pack; a dagger and a bone harvesting kit.
- **Quick Build**: Intelligence highest, then Constitution (survival depends on it). Any lineage (Shadar-kai, Tiefling, Drow thematic). Sage/Hermit or a Medicine/Arcana background. Target bloodied enemies first for Blood Resonance's cost reduction; use Vitae Harvest feedback to stay afloat; never cast below 30% HP unless the fight is ending.

**No Weapon Mastery feature anywhere in this document** — confirms [[Weapon Mastery]]'s existing Non-Martials table entry (Sangromancer listed alongside Witch, Wizard, Sorcerer, Warlock), a consistent silence rather than a contradiction.

## Level progression (1st-20th)

| Level | PB | Features | Spells Known | Vitae Strain Threshold |
|---|---|---|---|---|
| 1 | +2 | Sanguine Casting, Blood Sense, Bone Harvest, Vitae Harvest | 4 | — |
| 2 | +2 | Life Tap, Vitae Strain Track, Class Reactions | 5 | 5 |
| 3 | +2 | Sangromancer Pact, Blood Resilience | 6 | 5 |
| 4 | +2 | Improvement | 7 | 5 |
| 5 | +3 | Crimson Surge, Blood Resonance, Controlled Hemorrhage | 8 | 10 |
| 6 | +3 | Pact Feature | 9 | 10 |
| 7 | +3 | Blood Sense Enhancement, Class Reactions | 10 | 10 |
| 8 | +3 | Improvement | 11 | 10 |
| 9 | +4 | Hemorrhage Enhancement, Crimson Armour | 12 | 15 |
| 10 | +4 | Heroic Boon, Pact Feature | 13 | 15 |
| 11 | +4 | Vitae Mastery, Class Reactions | 14 | 15 |
| 12 | +4 | Improvement | 15 | 15 |
| 13 | +5 | Bone Lord, Exsanguinating Strike, Safe Bloodletting | 16 | 20 |
| 14 | +5 | Pact Feature | 17 | 20 |
| 15 | +5 | Sanguine Resilience, Sanguine Momentum | 18 | 20 |
| 16 | +5 | Improvement | 19 | 20 |
| 17 | +6 | Vitae Strain's Gift | 20 | 25 |
| 18 | +6 | Pact Feature | 21 | 25 |
| 19 | +6 | Improvement | 22 | 25 |
| 20 | +6 | Epic Boon | 23 | 30 |

## Core class features (full text)

### Sanguine Casting (1st level) — twelfth confirmed DC formula, third INT-based

No spell slots — casts by spending HP: **4 × spell level** (min 2 for cantrips); heightening costs +4 HP/level above base. Can't fuel casting with temp HP; can't drop below 10% max HP via Sanguine Casting alone. **Bloodied Empowerment**: below 50% HP, damage/healing spells deal/restore +1d6. **Critical State**: below 25% HP, +2d6 instead (replaces Bloodied Empowerment) + disadvantage on CON saves. **Hemorrhagic Vulnerability**: Bloodied grants vulnerability to piercing/slashing. **Vitae Strain Trigger**: casting below 30% HP gains 1 Vitae Strain. Intelligence-based: **Spell Save DC = 8+PB+INT, Spell Attack = PB+INT** — twelfth confirmation of the `8+PB+ability mod` formula, and the third on an Intelligence-based caster after [[Inventor]] and [[Magus]].

### Blood Sense (1st level)

Senses living creatures within 30 ft through walls (not lead/3+ ft stone), knowing their HP category (Healthy/Wounded/Bloodied/Critical). Passive, no action.

### Vitae Harvest (1st level)

Damaging a Bloodied creature with a spell auto-heals HP = spell level (1 for cantrips; 1.5× at 10th-16th, 2× at 17th+). **Vitae Depletion**: a creature targeted 3 times while Bloodied stops granting Vitae Harvest/Blood Resonance until it's no longer Bloodied or a long rest passes.

### Bone Harvest (1st level, enhanced at 9th)

1 minute harvesting a fresh (< 24h) Small+ skeletal corpse creates a **Bone Ward**: **Osseous Aegis** (temp HP = 5×PB until next long rest) or **Skeletal Barrier** (DR = PB against B/P/S, 1 hour). One Ward at a time; a bloodied corpse grants +5 temp HP and doubles duration. At 9th: Osseous Aegis → 10×PB temp HP; Skeletal Barrier → DR = PB+INT mod.

### Life Tap (2nd level)

Bonus action, touch a willing creature within 5 ft (30 ft at 7th): they take 1d6 unpreventable necrotic, the Sangromancer regains 1d6+CON mod HP. Against Bloodied targets: 2d6 damage/2d6+CON healed; below 25% HP, +PB more. Uses = INT mod per long rest.

### Vitae Strain Track (2nd level) — a parallel, explicitly distinct resource from Corruption

Gain 1 Vitae Strain when casting below 30% HP, harvesting a sentient humanoid corpse, or critically failing a CON save while casting. **Corruption Feast**: no Vitae Strain gain from casting Bloodied if the spell targets a Bloodied enemy. Six thresholds (5/10/15/20/25/30), each with a Boon and Curse:

| Threshold | Boon | Curse |
|---|---|---|
| 5 | Sanguine Surge — once/short rest, half-cost cast (quarter-cost vs. Bloodied) | Skeletal Hands — disadvantage hiding nature; self-healing −1d6 (min 1) |
| 10 | Bone Armour — +AC = Vitae Strain÷5 (min +1) | Blood Thirst — spend HP on a spell daily or gain 1 Exhaustion; also requires raw meat |
| 15 | Crimson Extraction — killing a Bloodied creature with a spell heals 5×spell level + 2×spell level temp HP | Ashen Flesh — disadvantage on CHA checks with non-corrupted creatures; no magical disguises |
| 20 | Necrotic Infusion — spells ignore necrotic resistance, treat immunity as resistance; against Bloodied, necrotic damage also reduces max HP until a long rest | Haemophilia — slashing/piercing hits deal +2d6 and cause ongoing 2d6 bleed (DC 18 Medicine or magical healing to stop); stacks with Hemorrhagic Vulnerability |
| 25 | Bone Sovereignty — concentrate on two spells if one is blood/bone/necrotic | Hollow Bones — vulnerable to bludgeoning; max HP −25; speed −10 ft; disadvantage on STR/DEX saves |
| 30 (max) | Unlocks Avatar of the Vitae Epic Boon | Reducible only via *Greater Restoration* (7th+), divine intervention, or a GM-approved atonement quest — never by resting |

**Explicitly stated distinct from Corruption Score** — the source itself draws this line, not an editorial inference: "Vitae Strain measures only what the sanguine arts have done to *you*, not what eldritch exposure has done to your soul." See [[Corruption]] for the cross-link.

### Sangromancer Pact (3rd level, and 6th, 10th, 14th, 18th)

Choose **Pact of the Bloodreaver** (melee, direct vitae feeding), **Pact of the Crimson Sage** (ranged manipulation, blood as puppet strings), or **Pact of the Marrow King** (bone constructs, undead legion command). Features at 3rd/6th/10th/14th/18th — not detailed further here.

### Blood Resilience (3rd level) — new Injury hook shape

Sacrificing HP for a blood-magic ability/spell/feature grants advantage on the next Injury saving throw before the Sangromancer's next turn. A new shape distinct from every downgrade/removal/suppression hook seen so far — improving the *save* rather than altering the injury's outcome directly.

### Crimson Surge (5th level)

Casting via Sanguine Casting allows a bonus-action weapon attack; a hit heals INT mod HP.

### Blood Resonance (5th level)

Casting on a Bloodied creature reduces the HP cost by 1/spell level (min 1); scales to −2/level at 11th, −3/level at 17th.

### Controlled Hemorrhage (5th level)

Once per short rest, halve an HP cost (round down, min 1) on a blood-magic sacrifice.

### Blood Sense Enhancement (7th level)

Auto-alerts when a tracked creature becomes Bloodied, no action; tracks up to 3 simultaneously. Range 30 ft→60 ft (11th)→90 ft (15th).

### Hemorrhage Enhancement (9th level)

Damaging a creature with blood via spell forces a CON save (DC = Spell Save DC) or it bleeds 1d6 necrotic/turn (stoppable via DC 15 Medicine or magical healing). Against Bloodied: DC+2, 2d6 bleed, only magical healing stops it; senses all bleeding creatures in Blood Sense range through walls. Uses = PB per long rest.

### Crimson Armour (9th level)

Bonus action: sacrifice any HP for DR 1 per 5 HP sacrificed (max DR 3) until next turn.

### Heroic Boon (10th level)

Choose: **Boon of the Vitae Font** (+20 max HP; a Blood Bank stores up to 20 HP across rests, drawable as a bonus action for healing or spellfuel; banks up to half Bloodied-enemy damage dealt, lasts 3 days, max 40 HP; once/long rest transfer up to 20 HP to a willing ally) or **Boon of the Ossuary Master** (Bone Ward effects doubled, bloodied-corpse bonus tripled instead of doubled; harvest as an action not 1 minute; two simultaneous Bone Wards).

### Vitae Mastery (11th level)

**Life Surge** (bonus action, 10 HP for 2d8+INT mod temp HP, uses = PB/short rest). **Sacrificial Ward** (casting while Bloodied grants DR = spell level, min 1, until next turn; stacks with Bone Ward DR).

### Bone Lord (13th level)

Action, sacrifice 10% max HP (unhealable while active) to animate a Bone Construct (Animated Armour stat block, bone/necrotic reflavor, +Sangromancer level HP, +PB attack/damage, necrotic resistance). **Bloodied Instant Summon**: killing a Bloodied creature free-animates its skeleton for 1 hour, no HP cost. One Construct at a time unless the Pact says otherwise.

### Exsanguinating Strike (13th level)

On a spell or weapon-attack hit, force a CON save (DC = Spell Save DC) — failure drains 5 HP/turn for 1 minute, bypassing DR (HP loss, not damage). One creature affected at a time. Uses = PB per long rest.

### Safe Bloodletting (13th level) — second new Injury hook shape

Self-inflicted HP loss from the Sangromancer's own class features can never cause a Critical Injury (Minor/Major still possible; external sources can still inflict Critical Injuries normally). A self-only immunity carve-out, the second new Injury-interaction shape this ingest, distinct from Blood Resilience's save-advantage above.

### Sanguine Resilience (15th level)

No longer gains Vitae Strain from casting Bloodied if current Vitae Strain ≤10.

### Sanguine Momentum (15th level) — new Momentum gain source

Casting a spell costing 8+ HP via Sanguine Casting grants **+1 Momentum** — a resource-threshold-gated trigger, a new shape distinct from every prior Momentum-gain hook (none scale by resource *amount spent* rather than the action taken).

### Vitae Strain's Gift (17th level)

Choose one permanent benefit gated by current Vitae Strain: **10+** (+2 Spell Save DC permanently), **15+** (no food/water/sleep, 1 HP/day Sanguine Sustenance instead), **20+** (once/long rest, a spell costs no HP), **25+** (immune to death-save failure from the Sangromancer's own HP expenditure — only external damage can kill them via casting).

### Epic Boon (20th level)

Choose: **Avatar of the Vitae** (requires 30 Vitae Strain; once/long rest, 1 minute: spells cost no HP, regain HP = 2×Vitae Strain immediately, immune to nonmagical damage, every bloodied-threshold feature applies to all visible creatures, reducing a creature to 0 HP deals Sangromancer-level necrotic to all others within 30 ft) or **Crimson Apotheosis** (spells on Bloodied creatures cost a flat 1 HP; Vitae Harvest heals full Sangromancer level instead of spell level; Bone Constructs permanent, no HP upkeep).

## Last Stand (confirmed universal, 17th class — a fourth distinct DC shape)

| Option | Effect |
|---|---|
| Crimson Cataclysm | 60 ft explosion; all creatures CON save (DC = 10+PB+Vitae Strain÷3) — fail: 6d10+1d10/5 Vitae Strain, stunned until end of next turn; success: half, not stunned. Allies within 60 ft heal 2×Sangromancer level. Leaves a Crimson Relic (an ally consumes it for 50 HP or +2 spell attack/DC for 1 hour) |
| Ossuary Immortal | Flesh burns away into an animated skeleton for 1 minute: resistance to all but radiant/bludgeoning, immune to poison/disease/exhaustion, spells deal max damage, squeezes through 1-inch gaps; each spell cast extends the duration by 1 round; collapses to dust permanently when it ends |
| Blood Legacy | Allies within 60 ft (10 min): temp HP = remaining HP+Sangromancer level, +2d6 necrotic + self-heal on their hits, advantage vs frightened/charmed, +2 AC. Body becomes a Blood Font (AC 10, 50 HP, 10 min): allies draw 4d8 HP once each; enemies within 10 ft take 3d6 necrotic/turn; destroying the Font ends all benefits |

Seventeenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Crimson Cataclysm's DC (`10+PB+Vitae Strain÷3`) is a **fourth distinct Last Stand DC shape** — the first to scale off a class resource total rather than an ability modifier, alongside the existing plain-8, 10+ability, and 12+ability patterns.

## Class Reactions (confirmed universal, 17th class — HP-layered)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest — every reaction also spends HP directly on top, the same resource-layering shape as [[Magus]]'s spell slots and [[Reaper]]'s Soul Tokens, this time with the Sangromancer's own HP as the secondary cost.

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Sanguine Shield | 2nd | Takes damage from any source | DR = INT mod against all damage until next turn | 1 use + 5 HP |
| Haemorrhagic Retaliation | 7th | A creature within 30 ft casts a spell or attacks | CON save (DC = Spell Save DC) or 2d8 necrotic + loses one daily ability use; disadvantage on the save if the creature is Bloodied | 1 use |
| Blood Transfusion | 11th | An ally within 30 ft drops to 0 HP | Ally regains HP = HP spent (min 8); may also transfer one condition from the ally to the Sangromancer | 2 uses + 8+ HP |

## Mythology & Cultural Lore (from the Class Lore Compendium)

*Blood-Weavers: Those Who Make Life Into Currency.*

Sangromancers claim the oldest observation of all — blood is life, and what carries life can be made to transfer it — with the first practitioners simply noticing blood magic was already happening around them. Velara the Red, an elf who extended her life over 2,000 years through blood manipulation before her accumulated blood-debt manifested as a valley-killing plague, embodies the art's central bargain: power purchased on credit against your own body. Gods responded to sangromancy's weaponization during the Second Age Rebellions with the Sanguine Persecution, driving the practice underground into the Crimson Veil; at Ashkarra's Fall, thousands of sangromancers died attempting to channel the city's collective lifeforce into a protective barrier, a paradox that killed them (you cannot sacrifice an entire population to save itself).

**Source of Power (DM truth):** Sangromancers believe they channel life-energy directly, bypassing gods, glyphs, and Threads entirely. In truth, blood magic accesses the [[Primal Glyphs]] — life force itself as a fundamental cosmic element, with every living thing carrying a fragment of the original creative energy that shaped reality. This makes sangromancy among the most powerful magic in existence, drawing from the same source that created the world, and among the most dangerous, since mishandling life-force causes cascading failures.

**Legendary figures:** Velara the Red, the elf sangromancer whose 2,000-year blood-extended life ended when her accumulated blood-debt manifested as a plague that killed an entire valley, her body finally dissolving into crimson mist.

*"Every spell requires sacrifice... We're honest about ours... You can't fake bleeding. Can't lie about pain... that's why they fear us. Not because we're powerful... But because we make visible what they hide: all magic requires sacrifice. We just don't hide the knife."* — The Hemomancer's Defense

## See also

- [[Welcome to FEARS]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[FEARS Class Roster]]
- [[Momentum]]
- [[Injury System]]
- [[Corruption]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Primal Glyphs]]
- [[FEARS MOC]]
