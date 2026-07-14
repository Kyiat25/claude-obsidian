---
type: entity
title: "Reaper"
address: c-000050
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
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Class_breakdown]]"
  - "[[Momentum]]"
  - "[[Called Shot]]"
  - "[[Damage Reduction]]"
  - "[[Weapon Mastery]]"
  - "[[Corruption]]"
  - "[[Sanity]]"
  - "[[Focus]]"
  - "[[Injury System]]"
  - "[[Breaking Points]]"
  - "[[Enemy Rally]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Narrative Identity]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - ".raw/Reaper.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Reaper — Harvester of the End

**Martial tier** (no spellcasting). "All things end. I have simply learned to harness that ending." A tactically nuanced striker built around **Soul Tokens** — harvested from deaths, bloodying enemies, and broken enemy morale — that fuel necrotic damage, defense, and Covenant-specific power. Complexity self-rated MODERATE (6/10) by its own per-class deep-dive. By far the largest and most complete per-class source ingested this session (1237 lines) — the only one with fully detailed subclasses (three complete Covenants, each with four tiers of features) rather than a placeholder "Subclass Feature" line.

> "All things end. I have simply learned to harness that ending."

## Signature abilities

- **Soul Tokens**
- **Execution**
- **Reaper's Strike**

**Gameplay style**: snowball striker, growing stronger as enemies fall. **Core loop**: kill → gain power → kill faster → repeat. Excels when enemies cluster (Soul Harvest range), when contributing to kills/bloodying, and when enemy morale breaks; struggles isolated from combat, against undead/constructs (morale-immune, fewer harvest triggers), when Focus degrades (shrinks token capacity), and fighting solo.

## Class basics (from Reaper.md deep-dive)

- **Hit Dice**: 1d10/level. HP at 1st: 10 + CON mod. HP at higher levels: 1d10 (or 6) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium, shields. Weapons — simple, martial. Tools — none. Saves — Constitution, Wisdom. Skills — choose two from Athletics, Insight, Intimidation, Medicine, Perception, Religion, Stealth, Survival.
- **Starting Equipment**: (a) martial melee weapon + shield or (b) two martial melee weapons; (a) five javelins or (b) any simple weapon; (a) priest's pack or (b) explorer's pack; chain mail and a death mask/skull fetish.
- **Quick Build**: Strength or Dexterity highest, then Constitution, then Wisdom. Any lineage (undead-touched/death-themed thematic). Soldier/Mercenary/Gravedigger or an Intimidation/Medicine background. Position for Soul Harvest range; contribute to kills/wounds; manage token spending carefully.

## Level progression (1st-20th)

| Level | PB | Features | Base Token Max |
|---|---|---|---|
| 1 | +2 | Soul Harvest, Reaper's Strike | 2 |
| 2 | +2 | Death Ward, Fighting Style, Soul Shield | 2 |
| 3 | +2 | Reaper's Covenant, Soul Focus | 2 |
| 4 | +2 | Ability Score Improvement | 2 |
| 5 | +3 | Extra Attack | 3 |
| 6 | +3 | Covenant Feature | 3 |
| 7 | +3 | Execution, Death Mark | 3 |
| 8 | +3 | Ability Score Improvement | 3 |
| 9 | +4 | Soul Empowerment, Harvest the Broken | 4 |
| 10 | +4 | Heroic Boon, Covenant Feature | 4 |
| 11 | +4 | Covenant Feature | 4 |
| 12 | +4 | Ability Score Improvement | 4 |
| 13 | +5 | Reaper's Presence, Reaper's Retribution | 5 |
| 14 | +5 | Covenant Feature | 5 |
| 15 | +5 | Death's Inevitability, Deathblow Panic | 5 |
| 16 | +5 | Ability Score Improvement | 5 |
| 17 | +6 | Covenant Feature | 6 |
| 18 | +6 | Soul Resonance | 6 |
| 19 | +6 | Ability Score Improvement | 6 |
| 20 | +6 | Epic Boon | 6 |

## Core class features (full text)

### Soul Harvest (1st level)

A creature dying within 30 ft grants **1 Soul Token**. Reducing a creature to bloodied (≤50% HP) for the first time also grants 1 (once per creature). **Morale Harvester**: an enemy within 30 ft failing a Breaking Point save grants 1 token, repeatable per enemy per combat. Tokens persist until spent or a long rest (reset to 0). Multiple simultaneous deaths (AoE) each grant a token, up to max. Harvestable from Tiny+ creatures (Tiny needs CR ≥1/4; CR 0 swarms/familiars/conjures grant nothing). **Reliable Harvest**: starting a turn at 0 tokens grants 1 (lost if unspent by end of turn).

### Reaper's Strike (1st level)

On a weapon-attack hit, spend tokens for necrotic damage: 1 token = 1d6 (levels 1-4), 2 tokens = 2d6 (levels 5-16), 2 tokens = 3d6 (levels 17-20). Usable multiple times per turn (once per attack) if tokens allow.

### Death Ward (2nd level)

Bonus action, 2 tokens: temp HP = 1d10+Reaper level (2d10+level at 10th), lasting until depleted or a rest.

### Fighting Style (2nd level)

Choose: Great Weapon Fighting, Dueling, Defense (+1 AC in armour), or Two-Weapon Fighting.

### Reaper's Covenant (3rd level, and 6th, 10th/11th, 14th, 17th)

Choose **Grave Warden**, **Soul Drinker**, or **Death Knight** (full detail below). Determines the 20th-level Epic Boon.

### Soul Focus (3rd level)

Max Soul Tokens = table's Base Maximum + **Focus modifier**. Focus degradation directly shrinks token capacity — a literal mechanical consequence of mental decay. Recoverable via rest/meditation/GM-adjudicated downtime.

### Ability Score Improvement (4th, 8th, 12th, 16th, 19th)

+2 one score or +1 two scores (max 20), or a feat.

### Extra Attack (5th level)

Two attacks instead of one on the Attack action.

### Execution (7th level)

On hitting a bloodied creature, spend 3 tokens to auto-crit. Uses = PB per long rest. **Morale Break**: killing an enemy leader this way forces all witnesses within 120 ft to Breaking-Point-check at **+4 DC** (vs. normal +2). **Rally Interrupt**: using this on a leader mid-Auto-Rally, if it kills them, auto-fails their Rally and drops witnesses to **−2 Momentum** (vs. normal −1). Often self-refunding — the kill it causes generates a Soul Harvest token.

### Soul Empowerment (9th level)

Bonus action, 2 tokens, until end of next turn: advantage on attacks, saves, or checks; or +10 ft speed and crits on 19-20. One benefit active at a time.

### Harvest the Broken (9th level)

**Broken Harvest**: reaction, an enemy within 30 ft failing a Breaking Point save and routing grants 2 tokens (vs. normal 1). **Reaping Panic**: until the Reaper's next turn after such a harvest, +2 attack vs frightened/routing creatures, +10 ft speed, moves through routing enemy spaces without provoking. **Cascading Fear**: once/turn, killing a routing enemy within 30 ft forces other routing enemies within 30 ft to WIS save (DC 8+PB+CON) or be frightened 1 minute.

### Heroic Boon (10th level)

Choose: **Death's Resilience** (+2 base token max; reaction, once/long rest, spend 4 tokens to drop to 1 HP instead of 0; advantage on death saves; stabilizing a dying creature, including self, grants 1 token) / **Reaper's Harvest** (+1 extra token on a nearby death, i.e. 2 total; +1 more on a killing crit, i.e. 3 total; once/turn, spend 1 extra token on Reaper's Strike to force a CON save, DC 8+PB+CON, or inflict necrotic vulnerability until the Reaper's next turn) / **Death's Momentum** (harvesting a soul grants +1 Momentum, once/round; dropping an enemy to 0 HP grants +10 ft speed until turn's end; Death Ward usable as a free action, still costing tokens).

### Reaper's Presence (13th level)

**Aura of Death**: chosen creatures within 10 ft have disadvantage on death saves; a creature failing one grants 1 token. **Dread Presence**: enemies within 30 ft have disadvantage on Breaking Point saves. **Death Sense**: always know HP totals within 30 ft; sense undead/recent deaths within 60 ft. **Morale Sense**: know enemy Momentum states, Breaking Point failures, routing status, and approximate leader locations within 60 ft. **Unnatural Vitality**: at 3+ tokens, no need to eat/drink/breathe; no sleep-exhaustion for 3 days.

### Death's Inevitability (15th level)

Spend 4 tokens on a weapon attack to ignore DR, necrotic resistance, cover, and the target's Dodge/Deflect Evasion. A kill this way grants 2 extra tokens (on top of normal Soul Harvest). Uses = PB per long rest.

### Soul Resonance (18th level)

**Resonant Power**: +1 attack, +1 damage, +5 ft speed per current Soul Token. **Soul Overflow**: excess tokens beyond max can be gifted to allies within 30 ft (they hold up to 3, usable on the Reaper's Reaper's Strike, using the Reaper's dice, until the next long rest). **Death's Embrace**: once/long rest, dropping to 0 HP lets the Reaper spend all tokens (min 4) to return with HP = 5×tokens spent; creatures within 15 ft CON save (DC 8+PB+CON) or take 3d10 necrotic + frightened 1 minute.

### Epic Boon (20th level)

Choose: **Guardian of the Veil** (can't die while an ally is conscious within 60 ft, drops to 1 HP instead; allies within 30 ft +2 AC/saves; reaction, 1 token, saves an ally from 0 HP; once/long rest, resurrect up to 6 creatures dead within the hour) / **Eternal Hunger** (regain HP = tokens×3 each turn start; Vampiric Strike healing can exceed max HP as temp HP; dropping to 0 HP with 4+ tokens auto-converts to 10×tokens HP; resistance to necrotic, immune to poison) / **Inevitable End** (2 tokens: next attack within a minute auto-crits vs. bloodied targets; killing a creature grants a bonus-action attack, once/round; crit range 18-20 vs all; once/long rest, Death's Decree marks all visible creatures within 60 ft for 1 minute, advantage on all attacks, +2d8 necrotic on all weapon attacks).

## Reaper's Covenants (full subclass detail — unusually complete for this cluster)

### Grave Warden — protective, mercy-focused

- **3rd (Gentle Reaping)**: on gaining any token, may immediately spend it to stabilize a dying creature, grant temp HP (Reaper level+WIS mod), cure frightened/charmed, or **Offer Mercy** (end a routing condition, target becomes neutral for 1 minute). Allies within 10 ft (20 ft at 10th) have advantage on death saves. **Spirit Speech**: question recently-deceased spirits, WIS-mod uses (min 1) per long rest.
- **3rd (Guardian's Shield, Covenant Reaction)**: an ally within 30 ft hit by an attack — redirect it to self (1 reaction use + 2 tokens), CON save (DC 10+damage dealt) for half damage; regain 1 token if reduced to 0. **Warden's Sacrifice**: if this would drop the Reaper to 0 HP, the protected ally gains temp HP (Reaper level+WIS mod) instead.
- **6th (Guardian's Intervention)**: reaction, 2 tokens, prevents an ally within 30 ft from dropping to 0 HP (they hold at 1 + temp HP); uses = PB/long rest. **Peaceful Rest**: stabilizing grants 1d8+WIS mod HP, not just 0 HP. **Warden's Reprieve**: 3 tokens grants an enemy leader's Auto Rally advantage; success refunds 2 tokens and creates a narrative debt.
- **10th (Death's Sanctuary)**: action, 4 tokens, once/long rest: 30 ft Hallowed Ground, 1 minute — undead disadvantaged attacking, allies can't drop below 1 HP, dying creatures auto-stabilize, +1 token/turn (to max). **Mercy's Blade**: transfer up to half Reaper's-Strike necrotic damage as ally healing. **Split Harvest**: harvesting can split a token to a nearby ally (holds up to 3, usable on Reaper's Strike for 1 minute).
- **14th (Saint of the Grave)**: allies within 30 ft can't have max HP reduced, advantage vs. death effects. **Mass Resurrection**: once/long rest, 8 tokens + 1 minute, resurrect up to 6 creatures dead within the hour at half max HP, no exhaustion. **Deathless Vigil**: can't die while an ally within 30 ft is at 0 HP (once per long rest). **Warden's Resurrection**: once/long rest, reaction, 5 tokens, resurrect an ally who just died with CON+WIS mod (min 1) HP, within 1 minute of death.

### Soul Drinker — vampiric, self-sustaining

- **3rd (Life Drain)**: **Vampiric Strike** heals half the necrotic damage dealt by Reaper's Strike. **Feast on the Fallen**: a death within 10 ft auto-heals Reaper level HP, free. **Terror Feast**: an enemy failing a Breaking Point save within 30 ft auto-heals Reaper level HP + grants 1 token, free. **Hunger**: advantage vs. poison, resistance to poison damage.
- **3rd (Blood Shield, Covenant Reaction)**: hit by an attack — convert damage to life force, CON save (DC 10+half damage) for half damage + heal Reaper level HP (fail: full damage, still heal half Reaper level). **Crimson Hunger**: bloodied + successful save also grants 1 token.
- **6th (Blood Price)**: **Crimson Harvest**: take Reaper-level necrotic damage to gain 1 extra token on a nearby death (2 total). **Sanguine Empowerment**: pay Soul Empowerment's cost in HP (10 HP/token) instead, extending duration to 1 minute (concentration). **Transfusion**: action, transfer HP to a willing creature, taking equal necrotic damage (max Reaper level×3/use), CON-mod uses (min 1)/long rest. **Soul Conversion**: bonus action, once/short rest, 10 HP per token gained (max PB tokens/use).
- **10th (Eternal Thirst)**: Vampiric Strike heals 75% instead of half. **Soul Feast**: once/short rest, consume 3+ tokens for 1d10 HP + 1d6 temp HP + a stacking +1 STR/DEX (max +4) per token. **Bloodied Hunger**: bloodied Reaper's Strike deals +1d6 necrotic (triggers Vampiric Strike on the full total). **Draining Presence**: turn-start, hostiles within 10 ft take CON-mod necrotic, Reaper heals half dealt. **Panic Aura**: turn-start, hostiles within 10 ft WIS save (DC 8+PB+CON) or disadvantaged on their next Breaking Point save; heals half necrotic dealt this way. **Devouring Rout**: killing a routing enemy within 10 ft heals 2×Reaper level + grants 2 tokens.
- **14th (Master of Life and Death)**: **Lichborn** — immune poison/disease, resistant necrotic, chooses living/undead detection reading, no aging/food/drink. **Critical Feast**: a crit heals Reaper level + grants 1 token. **Soul Consumption**: Soul Feast can instead spend tokens for power — 2 for a guaranteed crit, 3 for an extra Attack-only action, 4 for *finger of death* (DC 8+PB+CON) without components. **Hunger's Call**: once/long rest, reaction (no reaction-use cost) below half HP: 1 minute of free Vampiric Strike on all attacks (25%), +10 ft speed, advantage vs wounded creatures, +1 token/turn. **Eternal Regeneration**: turn-start, 1+ token heals CON mod (2×CON mod if bloodied).

### Death Knight — executioner, precision-focused

- **3rd (Executioner's Precision)**: **Killing Blow** — crit range 19-20 vs bloodied creatures. **Death Sentence**: reducing a creature to 0 HP grants a free 10 ft move + one more attack on a different creature, no OA provoked; uses/turn = half PB rounded down (min 1). **Mark of Death**: bonus action, mark one creature within 60 ft — crits on 18-20 vs it for 1 minute, one mark at a time, PB uses/short rest. **Mark of Doom**: marking a leader gives their troops disadvantage on Breaking Point saves while it lasts; killing a marked leader raises their troops' Breaking Point DC by +4 (vs normal +2) and auto-fails their Auto Rally.
- **3rd (Reaper's Vengeance, Covenant Reaction)**: an ally within 30 ft dropped to 0 HP — attack the culprit, 1 reaction use + 1 token, auto-crit + 2 tokens on a hit; a kill lets Death Sentence continue. **Executioner's Fury**: if the target is Mark-of-Death'd, this attack's crit range is 17-20 instead of automatic.
- **6th (Inevitable Strike)**: **Armor Breaker** (2 tokens, ignore DR on a hit). **Perfect Execution** (Execution kill refunds 2 of its 3 tokens). **Relentless Assault** (2 tokens, a third attack on the same target after both Extra Attack hits land). **Sure Strike** (once/turn, 3 tokens, turn a miss into a hit).
- **10th (Executioner's Wrath)**: **Chain Execution** — Death Sentence kills can chain up to 3 kills/turn. **Chain the Broken** — unlimited Death-Sentence chaining against routing enemies, each kill +1 stacking Momentum and forcing nearby routing enemies to WIS save (DC 8+PB+CON) or prone+paralyzed by fear until the Death Knight's next turn. **Enhanced Mark**: Mark of Death lasts 1 hour, up to 2 marks, a marked kill grants 1 extra token (2 total). **Dreadful Presence**: marked creatures are frightened while they can see the Death Knight (WIS save, DC 8+PB+CON, at the end of each of their turns to suppress, mark persists). **Death's Approach**: advantage on initiative; marked creatures can't take reactions when the Death Knight moves within 5 ft.
- **14th (Avatar of Endings)**: **Instant Execution** (4 tokens, a hit that would drop a creature to ≤50 HP instead drops it to 0; Legendary Resistance can negate; PB uses/long rest). **Unstoppable Assault** (2 tokens, an extra attack stacking with Extra Attack, 3 total). **Killing Intent** (mark up to 2 creatures free on rolling initiative, lasting the whole combat). **Final Strike** (once/long rest, a hit forces CON save, DC 8+PB+CON, or instant 0 HP; success instead deals 8d10 necrotic + max-HP reduction; Legendary Resistance auto-succeeds but still takes the damage/reduction). **Death's Army** (3 tokens, animate a killed CR ≤3 creature as a skeletal minion at half max HP, max 3 minions, until destroyed or a long rest). **Supreme Executioner** (crit range 17-20 vs marked creatures, 16-20 vs bloodied marked creatures).

## Last Stand (confirmed universal, 15th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Final Harvest | Immediately dies (no death saves), consuming all tokens; creatures within 10 ft×tokens consumed CON save (DC 10+PB+CON) or take 1d10 necrotic/token (max 6d10) + matching max-HP reduction until a long rest (success: half, no HP reduction); allies in the area gain temp HP = Reaper level×2 |
| Soul Anchor | Immediately dies (no death saves); for 1 minute, may spend 1 token/bonus-action to manifest as an untargetable spectral form (fly 30 ft, phase through objects for 1d10 force damage if ending turn inside one, one weapon attack, can still Soul Harvest) until the start of the Reaper's next turn each time; vanishes after 1 minute or when tokens run out |
| Death's Bargain | Immediately dies (no death saves); one creature within 60 ft WIS saves (DC 10+PB+WIS) or drops to 0 HP and can't be stabilized for 1 minute + halved healing for 24 hours (success: 10d10 necrotic + frightened 1 minute); one chosen ally regains HP = Reaper level×2 and inherits all remaining Soul Tokens, usable on Reaper's Strike for 1 minute |

Fifteenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). DC corrected to the canonical `10+PB+ability` — the original `8+PB+ability` in this document was a transcription error, ruled and resolved on [[Last Stand]].

## Class Reactions (confirmed universal, 15th class — heavy Soul Token layering)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest — but every reaction (baseline and Covenant) also spends Soul Tokens on top, the same heavy-layering shape as [[Magus]]'s spell-slot-costed reactions, just with a different secondary resource.

| Reaction | Level | Trigger | Effect | Cost |
|---|---|---|---|---|
| Soul Shield | 2nd | Hit by an attack | Reduce damage by 2d10+CON mod (3d10 at 10th, 4d10 at 15th); if reduced to 0, regain the token and gain +1 Momentum | 1 reaction use + 1 token |
| Death Mark | 7th | A creature within 30 ft drops to 0 HP | One creature within 30 ft of the dying creature takes Reaper-level+CON-mod necrotic; gain 1 token | 1 reaction use |
| Reaper's Retribution | 13th | A creature within 30 ft drops an ally to 0 HP | Attack that creature; a hit auto-crits and grants 2 tokens | 1 reaction use |
| Deathblow Panic | 15th | Killing an enemy leader/highest-CR creature within 30 ft | All witnesses within 60 ft immediately Breaking-Point-save (DC 15 base, or current casualty-tier DC+2 if casualties exist); creatures within 30 ft of the slain leader WIS save (DC 8+PB+CON) or frightened until the Reaper's next turn. At 18th (Soul Resonance), frightened creatures also drop to speed 0 | 1 reaction use |

Plus two Covenant reactions layering the same pattern: Grave Warden's Guardian's Shield (1 use + 2 tokens) and Death Knight's Reaper's Vengeance (1 use + 1 token).

## System integrations (from the source's own "Integration with FEARS Systems" section)

- **[[Damage Reduction]] — Death's Resilience**: while holding 3+ Soul Tokens, +1 DR at 5th level, +2 at 11th, +3 at 17th — a token-count-conditional DR hook, a new shape distinct from every other class's DR formula this session.
- **[[Called Shot]] — token-based access route**: spend 2 tokens to ignore a Called Shot penalty entirely, or 3 tokens to auto-hit and count it as a critical hit if the target is bloodied — the first Called Shot hook costing a class resource pool rather than being scaled by an ability modifier or PB.
- **[[Weapon Mastery]]**: 1 martial + 1 simple at 1st level, **plus a scheduled +1 weapon at 3rd/7th/11th/15th** on top of the standard crit-based unlock system (2 crits simple/3 crits martial, confirming the existing Full Martials row with zero drift) — the first source to describe a level-scheduled mastery grant layered on top of the crit-based one, not seen stated this explicitly on any other class.
- **[[Momentum]] — naming inconsistency within the source itself**: the Heroic Boon "Death's Momentum" (10th level, opt-in) grants +1 Momentum once/round on harvesting a soul. The same document's own systems-integration section restates this almost verbatim as "**Momentum of the Grave** (9th level)" — a different name, a different level, and phrased as an automatic feature rather than an opt-in Heroic Boon choice. Treated as an internal documentation inconsistency (the Heroic Boon framing is the one embedded in the actual level-by-level feature writeup, so likely authoritative), not two separate mechanics.
- **[[Corruption]] — new gain triggers**: harvesting souls from innocent (non-hostile) creatures gives 1 Corruption per 5 souls; harvesting from humanoids the Reaper personally killed gives 1 per 10. A five-tier "Death's Taint" progression (visual changes at 1-4, animal hostility at 5-9, undead-detection + healing disadvantage at 10-14, undead speech + necrotic resistance at 15-19, partial-undead state at 20+) maps closely onto [[Four Threads of the Mind]]'s existing 5/10/15/20 thresholds rather than contradicting them — read as flavor/mechanical detail filling the bands between those thresholds. Soul Drinkers can spend 5 tokens on a long rest to reduce Corruption by 1.
- **[[Sanity]]**: "Harvest Madness" (below half Sanity) and "Harvest Frenzy" (0 Sanity) are named, mechanically detailed states — likely Reaper-specific flavor readings of [[Mental State]]'s existing Frayed/Deranged→Broken stages rather than an entirely new tracker, though the source doesn't explicitly equate them.
- **[[Focus]]**: harvesting 3+ souls in a single round forces a DC 10 WIS save or lose 1 Focus; dropping below 5 Focus gives disadvantage on death saving throws — a new, concrete Focus-degradation consequence.
- **[[Injury System]]**: Soul Drinkers have advantage on saves against injuries while Hunger's Call is active — narrow, subclass-and-duration-gated, a new shape distinct from every downgrade/removal/suppression hook seen so far (a temporary save-advantage rather than altering the injury itself).
- **Enemy morale** ([[Breaking Points]], [[Enemy Rally]]): the richest morale-harvesting kit of any class — Morale Harvester, Harvest the Broken, Reaper's Presence's Dread Presence, Execution's Morale Break/Rally Interrupt, and Deathblow Panic all independently tie into the Bloodied/Breaking Points/Rally system, reinforcing rather than contradicting its existing rules.

## Mythology & Cultural Lore (from the Class Lore Compendium)

*Harvesters of Souls: Those Who Channel Death Itself.*

Death predates gods, magic, and civilization; the first reapers didn't learn their power, they *noticed* it, sensing departed essence at mass-death sites and learning to capture it. The First Age's Grave Warden tradition (reverent, ethical harvesting) split from harvest-for-power philosophy after Mordain Gray-Hand discovered peaceful and violent deaths taste different, and the Second Age's Death Knight Companies weaponized this as psychological warfare — enemies who knew their deaths would empower the reaper facing them sometimes surrendered rather than fight. Ashkarra's Fall brought the "Tainted Harvest": thousands of reapers attempting to harvest Eldritch-corrupted souls died as the poisoned essence overwhelmed them, a catastrophe that still shapes the class's caution around corrupted harvests.

**Source of Power (DM truth):** Reapers believe they capture departing "soul" in a theological sense. In truth what they harvest is consciousness-energy — the force binding body to mind to existence — and the [[Universal Glyphs]] governing all existence include the death-transitions by which that binding severs. Reapers instinctively read these glyphs, positioning themselves to intercept escaping essence before it disperses into ambient magic, follows natural paths to other realms, or lingers as a ghost. This makes reapers unwitting reality-hackers, proving consciousness itself is a transferable, storable form of energy.

**Legendary figures:** Mordain Gray-Hand, the dwarf who discovered harvested souls taste different depending on how peacefully their bearer died, founding the ethics-driven Grave Warden tradition; Mordrek Gray-Hand, the First Death Knight, whose Second Age philosophy of "harvesting inevitability" is preserved in the class's foundational manifesto.

*"They fear me. I understand why. I grow stronger when others die... But listen carefully: I don't cause these deaths... I simply collect what's released... My power isn't mine—it's borrowed from those who no longer need it... I don't fight inevitability. I harvest it. And harvest is always plentiful."* — Mordrek Gray-Hand, The First Death Knight, Second Age

## See also

- [[Narrative Identity]]
- [[Narrative Identity Framework]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[FEARS Class Roster]]
- [[Momentum]]
- [[Called Shot]]
- [[Damage Reduction]]
- [[Weapon Mastery]]
- [[Corruption]]
- [[Sanity]]
- [[Focus]]
- [[Injury System]]
- [[Breaking Points]]
- [[Enemy Rally]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Universal Glyphs]]
- [[FEARS MOC]]
