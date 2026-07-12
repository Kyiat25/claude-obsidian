---
type: concept
title: "Class Reactions"
address: c-000103
created: "2026-07-12"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - combat
  - class-mechanic
status: developing
mocs:
  - "[[FEARS MOC]]"
complexity: intermediate
domain: fears
related:
  - "[[Barbarian]]"
  - "[[Bard]]"
  - "[[Apothecary]]"
  - "[[Bender]]"
  - "[[Binder]]"
  - "[[Cleric]]"
  - "[[Druid]]"
  - "[[Fighter]]"
  - "[[Inventor]]"
  - "[[Investigator]]"
  - "[[Magus]]"
  - "[[Monk]]"
  - "[[Paladin]]"
  - "[[Ranger]]"
  - "[[Reaper]]"
  - "[[Rogue]]"
  - "[[Sangromancer]]"
  - "[[Shaman]]"
  - "[[Sorcerer]]"
  - "[[Tattooist]]"
  - "[[Warden]]"
  - "[[Warlock]]"
  - "[[Witch]]"
  - "[[Wizard]]"
  - "[[Last Stand]]"
  - "[[Tactical Reactions]]"
  - "[[Momentum]]"
sources:
  - ".raw/Barbarian.md"
  - ".raw/Bard.md"
  - ".raw/Apothecary.md"
  - ".raw/Bender.md"
  - ".raw/Binder.md"
  - ".raw/Cleric.md"
  - ".raw/Druid.md"
  - ".raw/Fighter.md"
  - ".raw/Inventor.md"
  - ".raw/Investigator.md"
  - ".raw/Magus.md"
  - ".raw/Monk.md"
  - ".raw/Paladin.md"
  - ".raw/Ranger.md"
  - ".raw/Reaper.md"
  - ".raw/Rogue.md"
  - ".raw/Sangromancer.md"
  - ".raw/Shaman.md"
  - ".raw/Sorcerer.md"
  - ".raw/Tattooist.md"
  - ".raw/Warden.md"
  - ".raw/Warlock.md"
  - ".raw/Witch.md"
  - ".raw/Wizard.md"
confidence: high
---

# Class Reactions

A universal per-class shared reaction pool — first sighted on [[Barbarian]]'s deep-dive and flagged there as possibly class-specific; confirmed universal by [[Bard]]'s deep-dive, which uses the identical pool structure for a completely different class. Every class is expected to have its own baseline named reactions drawing on this pool (9/24 confirmed so far — see the [[Druid]] exception below). [[Fighter]] gives the cleanest, most explicit confirmation yet: its reactions are stated plainly to draw from "your Proficiency Bonus pool, which refreshes on a short or long rest," no qualifications or partial exceptions. [[Inventor]] adds a new wrinkle: its reactions are explicitly gated to **7th level**, later than any other class confirmed so far (most unlock at 2nd or 3rd) — worth watching whether this is a half-caster pattern or Inventor-specific. [[Investigator]] adds a third partial exception: two of its three reactions use the shared pool, but Predictive Step runs on its own INT-mod-per-long-rest budget — the same shape as [[Cleric]]'s Sacred Interposition exception, this time on a martial class. [[Apothecary]] has the largest set seen yet — 7 reactions, spanning 1st to 15th level. [[Bender]] calls the pool "Reaction Points" explicitly, confirming that's the underlying name for the shared PB pool across classes, not just informal shorthand — [[Binder]] uses the same "Reaction Points" term.

> [!note] Cleric's Sacred Interposition bypass — explained by Divine Intervention
> [[Cleric]]'s Sacred Interposition (6th level) is explicitly "once per long rest — not limited by reaction pool," the first Class Reaction in this cluster that draws on its own separate budget instead of the shared PB pool. **Ruled: not an unexplained anomaly** — Clerics already have Divine Intervention (9th level, also once/long rest, see [[Cleric]]) as an established once-per-long-rest divine-favor resource shape; Sacred Interposition follows that same cadence rather than the generic shared pool. Cleric's other three reactions (Blessed Ward, Mercy of the Divine, Divine Reprisal) still use the shared pool normally — this is a class-specific carve-out with a clear precedent in the class's own design, not a documentation inconsistency.

> [!note] Druid has no shared pool at all — explained by Wild Shape
> [[Druid]] goes further than Cleric's single exception: none of its three reaction-triggered features (Nature's Snare, Bestial Reflex, Reactive Disruption) reference a shared PB pool. Each has its own independent budget — Nature's Snare is capped once per round with no other limiter, Bestial Reflex uses PB per short rest **and requires being in Beast Form** (i.e. an active Wild Shape), Reactive Disruption uses WIS modifier per long rest. **Ruled: explained rather than anomalous** — Druids' resource identity already centers on Wild Shape (its own short-rest-charge pool, see [[Druid]]'s level table) rather than a PB-based reaction pool; Bestial Reflex in particular is directly gated on Wild Shape being active, and the class's reaction design leans on that existing resource axis instead of introducing a second, redundant shared pool.

## Shared rules (confirmed identical across both sightings)

A **Proficiency-Bonus-sized pool**, separate from and in addition to the character's normal [[Tactical Reactions|action-economy reaction]]. Refreshes on a short or long rest. Capped at 1 use per round. Opportunity Attacks do not spend from this pool. Not subclass-gated — these are baseline class features, distinct from subclass-specific reaction upgrades like those on [[Reaction Subclass Features]].

## Per-class reactions

### [[Barbarian]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Furious Defiance | 2nd | Hit within 5 ft while Raging | Reduce damage by PB, then melee-counterattack |
| Bloodrush Reprisal | 3rd | Hit within 5 ft while Raging | Attacker CON saves (DC 8+PB+CON) or takes 2d6 weapon damage + pushed 10 ft; scales +1d6 at 7th/11th/15th/19th |
| Primal Shockwave | 11th | Score a critical hit | Chosen creatures within 15 ft STR save (DC 8+PB+STR) or knocked prone + PB×d6 thunder damage |

### [[Bard]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Dissonant Echo | 2nd | Creature within 30 ft hits an ally | Expend a Bardic Inspiration die, subtract from damage; attacker WIS saves (DC 8+PB+CHA) or is frightened of the Bard until end of its next turn |
| Cutting Rhythm | 3rd | Enemy within 60 ft gains Momentum from a successful attack | Expend a Bardic Inspiration use, reduce their Momentum gain by 1 (min 0) |
| Cutting Counter | 7th | Creature within 60 ft makes an attack roll, ability check, or damage roll | Expend a Bardic Inspiration die, subtract from the roll; if it now fails, the Bard and one ally within 30 ft may each move 10 ft without provoking. At 15th level, both also gain advantage on their next roll |

Bard's three reactions all expend Bardic Inspiration on top of the shared PB pool — a resource-layering pattern worth watching for on other resource-based casters.

### [[Apothecary]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Emergency Injection | 1st | Ally within 5 ft takes damage | 1 PB + 1 RP: ally gains 1d6+INT temp HP; if bloodied, also resistance to the triggering damage type until next turn |
| Volatile Defence | 2nd | Creature enters a space within 5 ft | 1 PB: chemical cloud, CON save (DC 8+PB+INT) or poisoned + movement 0 until next turn |
| Caustic Retaliation | 3rd | Hit by a melee attack | 1 PB + 1 RP: attacker takes 2d6 acid; their weapon loses 1 DR penetration (cumulative, max −3) until repaired |
| Adrenaline Surge | 5th | Ally within 30 ft fails a save | 2 PB + 2 RP: reroll with advantage; if still failed, ally gains +2 Momentum |
| Smoke Bomb Escape | 7th | Self or ally within 30 ft targeted by attack/spell | 2 PB: 10 ft smoke cloud (heavily obscured until next turn); target may move half speed without provoking |
| Panacea Protocol | 10th | Ally within 30 ft drops to 0 HP | 3 PB + 4 RP: they regain 3d8+INT HP and end one condition; Apothecary gains +2 Momentum |
| Philosopher's Reversal | 15th | Self or ally within 30 ft would gain a condition (except exhaustion) | 3 PB + 3 RP: negate it, reflect onto the source (within 60 ft) via CON save (DC 8+PB+INT) or they suffer it instead |

Confirms Bard's resource-stacking pattern (most Apothecary reactions cost Reagent Points on top of the PB pool) and extends it to a non-caster resource pool, not just a spellcasting one.

### [[Bender]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Elemental Counter | 2nd (1 RP) | A creature within 30 ft makes an attack roll against the Bender | Attacker has disadvantage on that roll |
| Primordial Deflection | 2nd (2 RP) | Self or an ally within 30 ft would take affinity-type damage | Reduce the damage by 2d8 + spellcasting mod |
| Reactive Surge | 6th (2 RP) | Hit by an attack | Attacker DEX saves (DC = spell save DC) or takes 2d6 elemental damage (half on success); scales to 3d6/11th, 4d6/17th |
| Reactive Casting | 11th (3 RP) | Hit by an attack | Cast a Bender cantrip targeting the attacker as part of the reaction |

### [[Binder]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Borrowed Reflex | 2nd (1 PB) | Targeted by a visible attack | Add CHA mod to the Evasion roll against it |
| Remnant's Warning | 2nd (1 PB) | An ally within 30 ft is targeted by an attack they can't see | That ally may immediately Evasion-roll against it (no bonuses requiring sight) |
| Grasp from Beyond | 7th (1 PB) | A creature within 15 ft moves away or Disengages | It STR saves (Binding Save DC) or its speed drops to 0 until end of its turn |

### [[Cleric]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Blessed Ward | 2nd | An ally within 30 ft makes a saving throw | Add 1d4 to the roll (after seeing the result but before the outcome is determined) |
| Sacred Interposition | 6th | An ally within 30 ft would take spell/magical damage | Halve it. **Once per long rest — not limited by the reaction pool** (see contradiction above) |
| Mercy of the Divine | 10th | An ally within 30 ft would suffer an Injury | Downgrade it a tier (Major→Minor; Minor negated). Also documented as a Core Class Feature; the source cross-references it as a reaction rather than repeating it |
| Divine Reprisal | 13th | A creature within 30 ft hits the Cleric with a melee attack | It takes 2d8+WIS radiant or necrotic damage (Cleric's choice); WIS saves (DC 8+PB+WIS) or frightened until end of its next turn |

Sixth class confirming Class Reactions as universal — though notably the source itself never labels these as a single "Class Reactions" table the way other classes do; they're introduced individually at their unlock levels instead, recognized as the same mechanic by structure (PB-pool-adjacent, reaction-triggered) rather than by name.

### [[Druid]] — see contradiction above

| Reaction | Level | Trigger | Effect | Budget |
|---|---|---|---|---|
| Nature's Snare | 2nd | Hostile creature enters/ends turn within 10 ft | STR save (DC 8+PB+WIS) or restrained until end of Druid's next turn; area becomes difficult terrain regardless | Once per round, no pool |
| Bestial Reflex | 6th | Targeted by melee/ranged attack while in Beast Form | Advantage on the Evasion roll; if evaded, move 5 ft without provoking | PB uses / short rest |
| Reactive Disruption | 14th | Creature within 30 ft begins casting | Contested WIS (Insight) vs spellcasting ability check; success negates the spell (slot not expended) | WIS-mod uses / long rest |

None of Druid's three reactions draw from a shared PB pool — see the contradiction callout above.

### [[Fighter]]

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Defensive Counter | 2nd | A creature makes a melee attack against the Fighter | Miss: one melee attack, weapon damage + PB + STR/DEX mod on hit. Hit: reduce damage by PB, then make one melee attack |
| Guarded Riposte | 3rd | A creature makes a melee attack against the Fighter | Miss: one weapon attack with advantage, +PB+ability mod damage, target disadvantaged on its next attack. Hit: one weapon attack, +PB damage, target disadvantaged on its next attack |
| Tactical Masterstroke | 11th | An ally within 30 ft misses an attack | Grant a reroll with advantage; if it still misses, the Fighter may make one weapon attack against the same target |

Eighth class confirming Class Reactions as universal — and the cleanest confirmation of the shared-PB-pool default seen yet, explicitly stated with no exceptions.

### [[Inventor]] — gated to 7th level, ruled intentional

> [!note] Ruled: intentional slow-build design, not an error
> Every other class's reactions unlock at 2nd or 3rd level; Inventor's wait until 7th. Ruled: intentional — Inventor's identity is a slow-build class that "struggles without preparation... excels in any scenario it could see coming," and its reactive tricks (deploying stored gadgets, triggering infused items) depend on having banked Specialisation Upgrades and other options first. The late gate reflects that dependency rather than a documentation gap.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Emergency Gadget | 7th | Self or ally within 30 ft is hit by an attack or targeted by a spell | Deploy a stored Specialisation gadget that normally needs an action, as part of the reaction |
| Infusion Burst | 7th | Self or ally within 30 ft takes damage from an attack | Reduce damage by 2d6+INT mod (scales to 3d6/11th, 4d6/15th), or trigger the infused item's effect instead; if the hit would have dropped the target below Bloodied, the attacker loses 1 Momentum |
| Overclock | 7th | Attack action hits with an Inventor/infused weapon | Extra weapon damage die; target CON saves (DC 8+PB+INT) or DR reduced by 2 until the Inventor's next turn |

Ninth class confirming Class Reactions as universal — draws from the standard shared pool like Fighter, just later than any other class.

### [[Investigator]] — Predictive Step, explained by an existing resource shape

> [!note] Ruled: explained, not anomalous
> Predictive Step's "INT mod per long rest" budget isn't an arbitrary bypass — Investigator's own Bloodied Analysis feature (elsewhere in this class's kit) already uses the identical "INT mod per long rest" shape. Same pattern as [[Cleric]] (mirrors Divine Intervention's cadence) and [[Druid]] (leans on Wild Shape) — a resource shape the class already has, not an unexplained exception.

| Reaction | Level | Trigger | Effect | Budget |
|---|---|---|---|---|
| Quick Analysis | 2nd | A visible creature makes an attack roll | Force a reroll with disadvantage; if it still hits, mark with Exploit Weakness (+PB damage on next hit) | Shared PB pool |
| Exploit Interruption | 5th | A Studied creature within 30 ft attacks, casts, or moves | Trip, Expose, or Distract (counters vary by trigger); two counters at 11th level | Shared PB pool |
| Predictive Step | 7th | The designated Quarry makes an attack roll | Impose disadvantage on that attack roll | INT mod per long rest — matches Bloodied Analysis's own budget shape |

Tenth class confirming Class Reactions as universal, but the third to carry a partial or total pool exception — after [[Cleric]]'s Sacred Interposition and [[Druid]]'s total departure, Investigator's Predictive Step is the second single-reaction exception (like Cleric's), this time on a martial rather than caster/hybrid class.

### [[Magus]] — heaviest resource-layering yet

| Reaction | Level | Trigger | Effect | Budget |
|---|---|---|---|---|
| Arcane Deflection | 2nd | Hit by a weapon attack | Expend a spell slot: reduce damage by 1d8/slot level + INT mod; move 10 ft without provoking | 1 PB use + a spell slot |
| Arcane Riposte | 7th | Creature within 5 ft hits with a melee attack | Expend a spell slot: slot-level×d8 force damage to the attacker, guaranteed | Spell slot |
| Adaptive Mind | 11th | Hit by an attack | Reduce that attack's Momentum loss by 1 (min 0) | PB uses per **short rest** (own cadence, not the pool's short-or-long refresh) |

Every Magus reaction layers a spell-slot cost on top of the shared PB pool — the heaviest resource-stacking seen on any class's reactions, beyond Bard's/Apothecary's Bardic-Inspiration/Reagent-Point layering since this spends the Magus's actual spellcasting resource. Eleventh class confirming Class Reactions as universal.

### [[Monk]] — corrected to the shared PB pool

> [!note] Header/mechanics mismatch — resolved
> The source's header claimed these draw from "your Proficiency Bonus pool," but every individual reaction was originally written as costing Focus only, with no PB use anywhere in the mechanics. Ruled: the header is correct — Monk's reactions draw from the shared PB pool like every other class, and the table below has been corrected accordingly (Focus costs replaced with pool uses).

| Reaction | Level | Trigger | Effect | Pool cost |
|---|---|---|---|---|
| Fluid Reversal | 2nd | A creature within 5 ft makes a melee attack | Miss: unarmed strike with advantage, DEX save or prone. Hit: reduce damage by Martial Arts die + WIS mod, then strike. Against bloodied: DC +2, also stuns, free (no pool use) | 1 shared PB pool use |
| Flowing Reversal | 3rd | A creature enters reach or melee-attacks | Unarmed strike; on hit, STR save or prone/pushed 10 ft; move 10 ft without provoking if triggered by reach-entry | 1 shared PB pool use |
| Perfect Counter | 11th | Evasion beats an attack by 5+ | Teleport adjacent, two unarmed strikes with advantage; both hit: stun for 1 more pool use | 1 shared PB pool use (+1 to stun) |

Twelfth class confirming Class Reactions as universal — a clean confirmation, not an exception, now that the header/mechanics mismatch is resolved.

### [[Paladin]] — clean shared-pool confirmation

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Divine Intercession | 2nd | An ally within 10 ft is targeted by an attack | Force the attack to target the Paladin instead; reduce damage by PB+CHA mod |
| Aegis of Oath | 3rd | A creature within the Paladin's Aura targets an ally | Ally gains +PB to Evasion for that attack; if it still hits, ally takes half damage, Paladin takes the other half as radiant |
| Radiant Judgment | 11th | The Paladin smites a creature with Divine Smite | Chosen hostiles within 10 ft of the target CON save (DC 8+PB+CHA) or take PBd6 radiant + blinded until end of their next turn |

Thirteenth class confirming Class Reactions as universal, drawing cleanly from the shared PB pool with no stated exceptions — as clean a confirmation as [[Fighter]]'s.

### [[Ranger]] — clean shared-pool confirmation

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Hunter's Reflex | 2nd | A Hunter's-Mark target makes an attack roll | Disadvantage; if it still hits, reduce damage by 1d6+WIS mod. Against bloodied marked targets: 2d6+WIS + a CON save to suppress their Strength benefit |
| Quarry Interpose | 3rd | The marked target attacks an ally within 30 ft | Disadvantage; if it still hits, reduce damage by 1d8+PB. Against bloodied marked targets: intercept entirely by moving 10 ft, gaining resistance |
| Hunter's Snare | 11th | The marked target moves within 30 ft | STR save (DC 8+PB+WIS) or restrained + PBd6 piercing. Against bloodied marked targets: DC +2, also grappled, PBd8 |

Fourteenth class confirming Class Reactions as universal, drawing cleanly from the shared PB pool with no stated exceptions.

### [[Reaper]] — heavy Soul Token layering, four base reactions plus two Covenant reactions

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Soul Shield | 2nd | Hit by an attack | Reduce damage by 2d10+CON mod (scales to 3d10/10th, 4d10/15th); reducing it to 0 refunds the token and grants +1 Momentum | 1 use + 1 token |
| Death Mark | 7th | A creature within 30 ft drops to 0 HP | One creature within 30 ft of it takes Reaper-level+CON-mod necrotic; gain 1 token | 1 use |
| Reaper's Retribution | 13th | A creature within 30 ft drops an ally to 0 HP | Attack it; a hit auto-crits and grants 2 tokens | 1 use |
| Deathblow Panic | 15th | Killing an enemy leader/highest-CR creature within 30 ft | Mass Breaking Point check for witnesses within 60 ft; creatures within 30 ft of the leader WIS save or frightened |  1 use |

Plus Grave Warden's Guardian's Shield (1 use + 2 tokens) and Death Knight's Reaper's Vengeance (1 use + 1 token) — every Reaper reaction layers a Soul Token cost on top of the shared PB pool, the same heavy-resource-stacking shape as [[Magus]]'s spell-slot-costed reactions, just with a different secondary resource. Fifteenth class confirming Class Reactions as universal.

### [[Rogue]] — clean shared-pool confirmation

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Cunning Dodge | 2nd | Hit by a visible attack | Reduce damage by 1d6+DEX mod; move 10 ft without provoking |
| Shadow Slip | 3rd | A creature within 5 ft misses the Rogue | Gain +1 Momentum, or immediately Hide |
| Shadow Reversal | 3rd | Targeted by a visible attack | DEX (Stealth) contested by enemy Perception; success makes the attack miss + a 10 ft move without provoking |
| Killing Opportunity | 11th | An ally within 30 ft hits a creature | If within Sneak Attack range, make one weapon attack against it as part of the reaction |

Sixteenth class confirming Class Reactions as universal, drawing cleanly from the shared PB pool with no stated exceptions.

### [[Sangromancer]] — HP-layered

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Sanguine Shield | 2nd | Takes damage from any source | DR = INT mod against all damage until next turn | 1 use + 5 HP |
| Haemorrhagic Retaliation | 7th | A creature within 30 ft casts a spell or attacks | CON save (DC = Spell Save DC) or 2d8 necrotic + loses a daily ability use; disadvantage on the save if the creature is Bloodied | 1 use |
| Blood Transfusion | 11th | An ally within 30 ft drops to 0 HP | Ally regains HP = HP spent (min 8); may transfer one condition to the Sangromancer | 2 uses + 8+ HP |

Every Sangromancer reaction that costs HP layers it on top of the shared PB pool — the same resource-stacking shape as [[Magus]]'s spell slots and [[Reaper]]'s Soul Tokens, using the Sangromancer's own HP as the secondary cost. Seventeenth class confirming Class Reactions as universal.

### [[Shaman]] — clean shared-pool confirmation, but a table/section-heading mismatch

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Spirit Ward | 2nd | An ally within 30 ft is hit | Reduce damage by PB+WIS mod; attacker WIS saves or is Marked by Spirits (next attack against them has advantage) |
| Totemic Shield | 5th (per its own heading — absent from the level table's 5th-level row) | An ally within 30 ft is hit | A Totem flares: resistance to that damage type + temp HP (PB+WIS mod); attacker WIS saves or Marked by Spirits. At 11th, also +2 AC |
| Spirit Intercession | 6th | An ally within 15 ft is hit | Reduce that damage by WIS mod (min 1) |

Eighteenth class confirming Class Reactions as universal, drawing cleanly from the shared PB pool with no stated exceptions.

### [[Sorcerer]] — present in substance, absent in structure

Unlike every other class, this source never groups its reactions under one "Class Reactions" heading — they're scattered through Feature Descriptions at their own levels instead.

| Reaction | Level | Trigger | Effect | Stated pool use? |
|---|---|---|---|---|
| Arcane Deflection | 2nd | Damage from a visible creature within 30 ft | 1 SP; CHA save halves or quarters the damage; gain temp SP = circle | Not in feature text (only the summary table) |
| Volatile Aura | 3rd | Damage from any source | Elemental Retaliation, Momentum Surge (+2 Momentum), or Arcane Echo | Yes, explicit |
| Arcane Intercept | 4th | A visible creature casts a spell targeting another | Redirect (1 SP) or cancel (2 SP, gain temp SP) | Yes, explicit |
| Metaflux Veil | 7th | Damage from a visible spell | 1 SP; halve or quarter the damage (+temp SP on the latter) | Not in feature text (only the summary table) |

Two of the four reactions explicitly consume a Class Reactions pool use in their own text; the other two only cost sorcery points in their feature write-up, yet the source's own Resource Awareness table lists all four as pool-users. Treated as a source-internal inconsistency between individual feature text and its own summary table. Nineteenth class confirming the underlying mechanic exists, even without a consolidated section.

### [[Tattooist]] — spellbanger-layered

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Inkguard | 2nd | A visible creature hits with an attack | +PB to Evasion until end of the current turn; if this raises Evasion above the attack roll, the attack retroactively misses | 1 use |
| Ink Flare | 3rd | A creature within 10 ft hits with a melee attack | Attacker DEX saves (DC = Spell Save DC) or takes 3d6 acid (scaling to 4d6/11th, 5d6/17th) + disadvantage on its next attack; success halves damage, no disadvantage | 1 use + 1 spellbanger |
| Flash of Art | 7th | A visible creature targets an ally within 30 ft with an attack | Ally gains +2 Evasion + resistance to the triggering damage type; if it still hits, reduce damage by PB+CON mod. At 15th, also +2 to all saves | 1 use |

Ink Flare's spellbanger cost is a fourth class this session (after [[Magus]]'s spell slots, [[Reaper]]'s Soul Tokens, [[Sangromancer]]'s HP) to layer a secondary resource on top of the shared PB pool. Twentieth class confirming Class Reactions as universal.

### [[Warden]] — clean shared-pool confirmation, with a 2-use reaction

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Elemental Rebuke | 2nd | A creature within 5 ft hits with a melee attack | Rolled Power Die of Prime Element damage; CON save or pushed 5 ft; a failed save also grants +1 Momentum | 1 use |
| Elemental Wall | 7th | A creature moves toward the Warden or a nearby ally | STR save or speed 0; failure also deals WIS-mod (scaling) Prime Element damage | 1 use |
| Primal Retribution | 13th | A creature within 30 ft damages the Warden or an ally | CON save — fail: 3d8 Prime Element damage + a Frailty (scaling); success: half, no Frailty | 2 uses |

Primal Retribution's 2-use cost matches the shape of [[Sangromancer]]'s Blood Transfusion — not every reaction in this cluster costs a flat single use. Twenty-first class confirming Class Reactions as universal, drawing cleanly from the shared PB pool with no stated exceptions.

### [[Warlock]] — clean shared-pool confirmation

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Eldritch Counter | 2nd | A creature within 60 ft casts a spell targeting the Warlock or an ally | Fire an Eldritch Blast beam at the caster; a hit gives disadvantage on their spell's attack roll or advantage on saves against it |
| Darkness Veil | 6th | The Warlock or an ally within 30 ft is targeted by a ranged attack | Disadvantage on the attack; a resulting miss grants the target +1 Momentum |
| Patronal Reactions | 10th | Patron-specific | Infernal Rebuke / Fey Step / Psychic Backlash, using the same PB-per-short-rest count as the shared pool rather than a separate one |

Twenty-second class confirming Class Reactions as universal, drawing cleanly from the shared PB pool with no stated exceptions.

### [[Witch]] — clean shared-pool confirmation, with overlapping reaction shapes

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Fateful Twist | 2nd | A hexed creature makes an attack roll | Disadvantage on that roll |
| Hex Ward | 2nd | A hexed creature targets the Witch with an attack | CHA save or the attack redirects to another valid target within 30 ft |
| Hex-Turn | 7th | A hexed creature makes an attack roll | CHA save — fail: redirect; success: disadvantage. At 15th, a redirected target also saves at disadvantage |

Hex Ward and Hex-Turn overlap in shape (both redirect a hexed attack via CHA save) but differ in trigger scope — Hex Ward only fires when the Witch is the original target. Twenty-third class confirming Class Reactions as universal.

### [[Wizard]] — final class, self-explained pool exception

> [!note] Already explained by the source itself — not a genuine anomaly
> Counterspell Instinct is "explicitly not a pool use," but unlike every other exception this session, the deep-dive itself ties this to a specific named feature (Magic Sense) rather than stating it as a bare rule. No ruling needed — the source already explains its own exception.

| Reaction | Level | Trigger | Effect | Pool cost |
|---|---|---|---|---|
| Arcane Deflection | 2nd | Hit by a spell or magical effect | Halve the damage; can't cast levelled spells next turn | 1 use |
| Counterspell Instinct | 5th | A visible creature within 60 ft begins casting | Cast prepared *counterspell* as a reaction (spell slot spent normally) | Not a pool use — explained by Magic Sense |
| Arcane Rebound | 10th | The Wizard succeeds a save against a hostile spell targeting only them | The caster must save against their own spell or suffer its effects | 1 use |

With [[Cleric]] and [[Druid]] (explained by existing resource shapes), [[Monk]] (corrected to the shared pool), [[Investigator]] (explained by Bloodied Analysis's matching budget), and Wizard (self-explained by Magic Sense) all resolved, every one of Class Reactions' pool-structure questions from the 24-class pass is closed. Twenty-fourth and final class confirming Class Reactions as universal, closing out the per-class deep-dive pass.

## See also

- [[Barbarian]]
- [[Bard]]
- [[Apothecary]]
- [[Bender]]
- [[Binder]]
- [[Cleric]]
- [[Druid]]
- [[Fighter]]
- [[Inventor]]
- [[Investigator]]
- [[Magus]]
- [[Monk]]
- [[Paladin]]
- [[Ranger]]
- [[Reaper]]
- [[Rogue]]
- [[Sangromancer]]
- [[Shaman]]
- [[Sorcerer]]
- [[Tattooist]]
- [[Warden]]
- [[Warlock]]
- [[Witch]]
- [[Wizard]]
- [[Last Stand]]
- [[Tactical Reactions]]
- [[Momentum]]
- [[FEARS MOC]]
