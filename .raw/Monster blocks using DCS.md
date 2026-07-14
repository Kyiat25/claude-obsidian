### Adapting the Dynamic Combat System to D&D 5e Monster Stat Blocks

The **Dynamic Combat System** can be integrated into standard 5e monster stat blocks by mapping **evasion**, **damage reduction (DR)**, and **called shots** onto existing monster mechanics. The following guidelines streamline this process while maintaining balance and ensuring compatibility.

---
### **1. Evasion f# Converting Monsters to Dynamic Combat System

> _"A dragon is not merely HP and AC - it is fury and fear, scales and strategy, ancient wisdom and terrible pride. Give your monsters the depth they deserve."_

---

## Overview

In standard 5E, monsters are simple stat blocks. AC is a static number. HP is a pool that drains. Abilities are lists of attacks. There's no psychological dimension, no tactical complexity, no sense that these are living creatures with strengths, weaknesses, and breaking points. A goblin fights identically whether leading a victorious charge or watching its warband crumble. An ancient dragon has the same static AC whether fresh or bloodied, desperate or dominant.

The monster, fundamentally, is a collection of numbers that players chip away at until it dies.

**Converting monsters to the Dynamic Combat System** changes this entirely.

DCS monsters are dynamic combatants with layered defensive systems, exploitable weaknesses, psychological vulnerabilities, and adaptive behaviors. They have Evasion DCs that reflect their agility, not abstract "armor class." They have Damage Reduction representing physical toughness that can be bypassed with precision. They have Momentum that rises and falls with combat flow, making them more dangerous when winning and more vulnerable when losing. They have Sanity and Focus determining morale resilience and concentration ability. They have bloodied thresholds that trigger desperation effects. They have called shot vulnerabilities that reward tactical targeting.

And when you kill their leader or push their casualties past breaking points, they face psychological crises that can shatter their resolve entirely.

### Why Convert Monsters to DCS

The Dynamic Combat System introduces mechanics that fundamentally change how combat works:

**Evasion replaces AC** - Static armor class becomes dynamic defense rolls. Monsters actively defend rather than passively hoping to be missed. This creates moment-to-moment tension and makes every attack resolution a contested roll.

**DR provides layered defense** - Damage Reduction represents physical toughness separate from evasion. Heavy armor doesn't make you harder to hit - it makes hits less effective. This feels more realistic and creates tactical depth.

**Momentum drives combat rhythm** - Monsters build Momentum when dominating, lose it when faltering. At high Momentum they become terrifying threats. At low Momentum they're vulnerable and desperate. Combat becomes a psychological rhythm game, not just HP attrition.

**Mental attributes enable morale** - Sanity and Focus allow Breaking Points, Rally attempts, fear effects, and concentration checks to function meaningfully. Goblin cowards break easily. Dragon tyrants hold firm. Celestials never waver. Psychology becomes tactical.

**Called Shots create vulnerabilities** - Every monster has exploitable weak points. Target the troll's head to disrupt regeneration. Aim for dragon wings to ground it. Shoot the orc captain's weapon arm to disarm their leadership. Tactics matter beyond "I attack."

**Bloodied states trigger transformations** - At 50% HP, creatures reveal desperation. Frailties expose weaknesses. Strengths grant resilience. Abilities trigger once-per-combat. Death throes promise explosive finales. The bloodied threshold becomes a dramatic turning point.

**Injuries create cascading consequences** - Major damage triggers trauma rolls. Broken bones, bleeding wounds, and critical injuries stack up. Monsters become visibly damaged, mechanically weakened, and psychologically shaken.

Without DCS conversion, all these systems don't work properly. Monsters remain flat stat blocks that players "attack until dead." With DCS conversion, they become dynamic threats that adapt, weaken, and break in tactically interesting ways.

### What This Document Provides

This is a comprehensive guide to converting 5E monsters into full DCS combatants. It provides:

**Quick Conversion Rules** - Fast formulas for on-the-fly conversion during play

**Standard Conversion System** - Detailed guidelines for important encounters and boss fights

**Special Rules** - Handling for unusual creature types (swarms, legendary creatures, etc.)

**Complete Examples** - Full DCS stat blocks for Goblin (CR 1/4), Troll (CR 5), Adult Red Dragon (CR 17)

**Integration Notes** - How converted monsters interact with all DCS systems

**DM Guidance** - When to convert fully vs. use shortcuts, batch processing for groups, priority targeting

The goal is to make DCS monster conversion as painless as possible while ensuring the full system works correctly. Quick defaults let you improvise. Detailed conversions create memorable encounters. Together, they transform every combat into a dynamic, tactical, psychological battle.

---

## SYSTEM 1: Quick Conversion Rules

For immediate play or less important encounters, these quick rules convert monsters in seconds:

### Evasion DC (Replaces AC)

**Formula:** 8 + Dex modifier + Proficiency Bonus

**Why Not Use AC Directly?** AC includes Dex, armor, shields, and magical bonuses all mashed together. Evasion represents active defense only. Natural armor becomes DR instead. The formula above captures just the "dodging" component.

**Examples:**

- Goblin (AC 15, Dex +2, Prof +2): Evasion DC **12**
- Orc (AC 13, Dex +1, Prof +2): Evasion DC **11**
- Ancient Dragon (AC 22, Dex +0, Prof +9): Evasion DC **17**

**Passive Evasion Alternative:** For groups of weak monsters, use Passive Evasion = 10 + Dex modifier This speeds up combat but makes monsters slightly easier to hit.

---

### Damage Reduction (DR)

**Quick Assignment by Size:**

|**Size**|**Base DR**|**Examples**|
|---|---|---|
|Small|1|Goblin, Kobold, Giant Rat|
|Medium|2|Bandit, Orc, Werewolf|
|Large|4|Troll, Bulette, Hill Giant|
|Huge|6|Adult Dragon, Roc|
|Gargantuan|8|Ancient Dragon, Kraken, Tarrasque|

**Armor Type Adjustments:**

- **Natural Armor (heavy):** +2 DR (Ankylosaurus, Dragon Turtle)
- **Armored Humanoids:** Use armor type (light +1, medium +2, heavy +3)
- **Supernatural Scales/Hide:** +2 DR (Dragons, Demons, Devils)

**Location-Based DR:**

- **Torso:** Base DR
- **Head/Arms/Legs:** Base DR - 1
- **Wings/Tail:** Base DR - 2
- **Critical Spots (eyes, throat):** Base DR - 3

---

### Mental Attributes (Quick)

**Sanity:** 10 + Wisdom Modifier (check CR minimums from Monster Mental Attributes)

**Focus:** 8 + Highest Mental Stat + CR/4 (check CR minimums)

See the Monster Mental Attributes document for detailed rules and type modifiers.

---

### Momentum

**Starting Momentum:** 0 (all creatures begin combat neutral)

**Momentum Range by Type:**

- **Beasts/Humanoids:** -2 to +2
- **Fiends/Aberrations:** -3 to +3
- **Dragons/Giants/Celestials:** -5 to +5
- **Undead/Constructs:** Usually cap at +2 unless Legendary

Momentum modifiers apply to their attack rolls and evasion DCs.

---

### Called Shots (Quick Effects)

**Universal Effects by Body Part:**

|**Target**|**Effect**|**Save**|
|---|---|---|
|Head|Stunned 1 round|Con DC 12 + CR/2|
|Arms/Claws|Drop weapon or halve damage|Str DC 12 + CR/2|
|Legs|Prone + speed 0|Dex DC 12 + CR/2|
|Wings|Grounded, no flight|Dex DC 12 + CR/2|
|Torso|Standard damage, no effect|N/A|

**Attack Penalty:** -2 to hit for called shots (standard)

For detailed, monster-specific called shot effects, see Standard Conversion System below.

---

### Quick Conversion Checklist

**For any monster, answer these questions:**

1. **Evasion DC:** 8 + Dex + Prof = _____
2. **DR:** Size base + armor type = _____
3. **Sanity:** 10 + Wis = _____
4. **Focus:** 8 + Mental + CR/4 = _____
5. **Momentum Range:** Type determines: _____
6. **Called Shots:** Use universal effects or custom?
7. **Reactions:** Simple (OA only) or complex?

**Done.** That's enough for 80% of encounters.

---

## SYSTEM 2: Standard Conversion System

For important encounters, boss fights, and recurring NPCs, use this detailed conversion system.

### Step 1: Defense Systems

#### Evasion DC Calculation

**Base Formula:** 8 + Dex modifier + Proficiency Bonus

**Adjustments:**

- **Legendary Creatures:** +2 to Evasion DC
- **Nimble Types (Rogues, Monks):** +1 to Evasion DC
- **Bulky Types (Heavy armor, slow):** -1 to Evasion DC

**Multi-Mode Defense:** Some creatures can use different defense modes:

- **Dodge Mode:** Standard Evasion DC (Dex-based)
- **Brace Mode:** 8 + Str modifier + Prof (for heavy armor or shield users)
- **Stalwart Mode:** High Con, planted stance (for bosses vs. single threats)

**Advantage/Disadvantage:**

- Bosses and legendary creatures may roll evasion with advantage
- Conditions (blinded, prone, restrained) impose disadvantage as normal

---

#### Damage Reduction (Detailed)

**Step 1: Base DR by Size** Use Quick Conversion table as starting point.

**Step 2: Type Adjustments**

- **Dragon/Devil/Demon:** +2 DR (supernatural scales/hide)
- **Elemental:** +1 DR (alien physiology)
- **Undead (corporeal):** +1 DR (deadened nerves)
- **Construct:** +3 DR (artificial materials)
- **Plant/Ooze:** Varies (see Special Types section)

**Step 3: Armor Considerations** For humanoid monsters in armor:

- **Light Armor:** Torso +1, Limbs +0
- **Medium Armor:** Torso +2, Limbs +1
- **Heavy Armor:** Torso +3, Limbs +2
- **Shields:** +1 to all locations when actively used

**Step 4: Location-Specific DR**

|**Body Part**|**DR Calculation**|
|---|---|
|Torso|Base DR + armor|
|Head|Base DR - 1 (vulnerable)|
|Arms/Legs|Base DR - 1 or base (heavy armor)|
|Wings|Base DR - 2 (fragile membranes)|
|Tail|Base DR (tough, muscular)|

**Critical Hit Interaction:** Natural 20s halve the target's DR before damage is applied.

---

### Step 2: Mental Attributes (Detailed)

Use the full calculation from Monster Mental Attributes document:

**Sanity:** 8 + Wisdom Modifier + CR Bonus + Type Modifier

**Focus:** 6 + Highest Mental Stat + CR Bonus + Type Modifier

**CR Bonus Table:**

|**CR Range**|**Sanity Bonus**|**Focus Bonus**|
|---|---|---|
|0-1/4|+0|+0|
|1/2-2|+1|+1|
|3-4|+2|+1|
|5-8|+2|+2|
|9-12|+3|+2|
|13-16|+3|+3|
|17-20|+4|+3|
|21+|+5|+4|

Apply type modifiers from Monster Mental Attributes document.

---

### Step 3: Momentum & Combat Flow

**Starting Momentum:** 0

**Momentum Range:**

- Determined by creature type (see Quick Conversion)
- Track per creature (or per group for mooks)

**Momentum Gains/Losses:**

|**Event**|**Momentum Change**|
|---|---|
|Successful attack|+1|
|Critical hit|+2|
|Dropping foe to 0 HP|+1|
|Called shot success|+2|
|Missed attack|-1|
|Taking critical hit|-2|
|Knocked prone/restrained|-1|
|Crossing bloodied (50% HP)|Reset to 0|
|Dropping to 25% HP|-2|

**Swing Guardrail:** Maximum +/-2 Momentum change per turn (before injury resets)

**Initiative Impact:** From Round 2 onward, Side Initiative is determined by average Momentum of each side. Higher average acts first.

---

### Step 4: Called Shot Vulnerabilities

Design specific called shot effects based on creature anatomy and abilities:

#### **Head Shots**

**Standard Effect:** Stunned condition (Con save)

**Creature-Specific Examples:**

- **Troll:** Disrupts regeneration for 1 round
- **Dragon:** Damages jaw, prevents breath weapon for 2 rounds
- **Beholder:** Damages central eye, disrupts anti-magic cone
- **Spellcaster:** Breaks concentration, disadvantage on next spell

**Save DC:** 8 + Attacker's Prof + Attack Modifier + Called Shot Bonus

---

#### **Limb Shots (Arms/Claws/Tentacles)**

**Standard Effect:** Drop weapon or halve damage (Str save)

**Creature-Specific Examples:**

- **Multiattack Creatures:** Lose one attack from multiattack
- **Grappler:** Release grappled targets
- **Shield Bearer:** Drop shield, lose AC bonus
- **Caster:** Disadvantage on somatic spells

---

#### **Leg Shots**

**Standard Effect:** Prone + speed 0 (Dex save)

**Creature-Specific Examples:**

- **Fast Creatures:** Speed halved instead of 0
- **Multi-legged:** Need multiple leg shots to immobilize
- **Flying Creatures:** If hit while flying, forced landing

---

#### **Wing Shots**

**Standard Effect:** Grounded, cannot fly (Dex save)

**Creature-Specific Examples:**

- **Dragon:** One wing = disadvantage on flight, both wings = grounded
- **Flying only creatures:** Falling damage if high altitude
- **Demon/Devil:** May have supernatural flight (harder to disrupt)

---

#### **Special Targets**

**Eyes:** -5 to hit, blinds creature (Dex save) **Throat:** -4 to hit, prevents breath weapons/spells (Con save) **Heart:** -6 to hit, massive damage + frightened nearby allies **Joints:** -3 to hit, permanent speed reduction until healed

---

### Step 5: Reactions

**Mook Creatures:** Opportunity attacks only

**Elite Creatures (Important NPCs):** 1-2 signature reactions

**Boss Creatures:** 2-3 reactions + legendary actions

#### **Common Reactions by Type:**

**Warriors:**

- **Counterattack:** When hit in melee, attack back with disadvantage
- **Shield Bash:** When missed by melee, bash attacker (Str save or prone)
- **Weapon Bind:** Lock weapons, both suffer -2 to attacks

**Agile Creatures:**

- **Evasive Maneuver:** Impose disadvantage on one attack per round
- **Riposte:** When enemy misses, make opportunity attack
- **Tumble:** When hit, move 5 ft without provoking

**Large Creatures:**

- **Tail Sweep:** When flanked, attack all adjacent enemies
- **Wing Buffet:** When missed, knock attacker back 10 ft
- **Tremor Stomp:** When bloodied, shake ground (Dex save or prone)

**Spellcasters:**

- **Counterspell:** As standard
- **Shield Spell:** As standard
- **Misty Step Escape:** When hit, teleport 30 ft

---

### Step 6: Bloodied & Bruised Effects

At 50% HP, all creatures trigger Bloodied & Bruised effects.

Design four effects per creature:

**Frailty (Weakness Exposed):**

- Examples: -2 AC, disadvantage on saves, vulnerable to damage type

**Strength (Desperation Resilience):**

- Examples: +2 damage, resistance to damage type, temporary HP

**Ability (Once-Per-Combat Triggered):**

- Examples: Special attack, buff allies, debuff enemies, escape ability

**Death Throes (On-Death Effect):**

- Examples: Explosion, curse, transformation, final attack

#### **Examples by Creature Type:**

**Beast (Wolf):**

- Frailty: -2 AC (exposed wounds)
- Strength: Pack Tactics bonus increased
- Ability: Desperate Bite (advantage + knockdown)
- Death Throes: Howl frightens enemies (DC 12 Wis save)

**Humanoid (Orc Captain):**

- Frailty: Disadvantage on Dex saves
- Strength: +2 damage rolls
- Ability: Battle Cry (allies gain advantage on next attack)
- Death Throes: Curse attackers (DC 14 Cha save or -1d4 damage for 1 minute)

**Dragon (Adult Red):**

- Frailty: Wings vulnerable (-2 DR on wings)
- Strength: Resistance to non-magical damage
- Ability: Legendary Roar (Sanity save DC 18 or frightened)
- Death Throes: Fire explosion (30 ft radius, 6d6 fire)

---

### Step 7: Leadership & Morale

**Identify Leaders:**

- Highest CR creature in group
- Designated leader by narrative
- Only leaders can attempt Rally

**Breaking Point Triggers:**

- Leader bloodied (triggers immediate Rally attempt)
- Leader dies (Breaking Point DC +2)
- 25%/50%/75% casualties (Breaking Point checks)

**Rally Mechanics:**

- Leader rolls 1d20 + Focus modifier
- DC based on casualty tier
- Success restores ally Momentum, rerolls failed morale saves
- Failure reduces ally Momentum further

See Bloodied, Breaking Points & Rally document for full rules.

---

## SYSTEM 3: Special Creature Types

### Swarms

**Evasion:** DC 10 + Dex (hard to "miss" a swarm) **DR:** 0 (many tiny creatures, no meaningful DR) **Called Shots:** Ineffective (can't target individuals) **Immunity:** Morale effects (mindless swarm)

**Special Rules:**

- Damage reduction based on swarm HP percentage
- At 50% HP: Half damage output
- At 25% HP: Quarter damage output
- No Momentum tracking

---

### Legendary Creatures

**Evasion:** Standard + 2 (supernatural agility) **DR:** Standard + type bonuses **Legendary Resistance:** Can ignore called shot effects 3/day **Legendary Actions:** Additional reactions per round

**Momentum:**

- Extended range (-5 to +5)
- At +4: Extra reaction, aura suppression
- At +5: Crit expansion (19-20), forced saves

**Morale:**

- Auto-succeed one Rally per combat
- Allies within 120 ft gain +2 to Breaking Point saves
- Legendary Phase 2 when bloodied (instead of standard bloodied effects)

---

### Undead

**Mindless Undead (Zombies, Skeletons):**

- Sanity/Focus: N/A
- Immune to morale effects
- DR applies normally
- Simple called shot effects only

**Intelligent Undead (Vampires, Liches):**

- Enhanced mental attributes (see Monster Mental Attributes)
- Immune to existential fear
- Vulnerable to holy terror (bypasses Sanity)
- Full DCS conversion applies

---

### Constructs

**Mindless Constructs (Golems, Animated Objects):**

- Sanity: N/A
- Focus: 4-8 (programmed purpose)
- Immune to morale
- High DR (+3 bonus)
- Vulnerable to specific damage types (varies)

**Sentient Constructs (Warforged, Modrons):**

- Sanity: 10 + Wis
- Focus: 8 + Con + CR/4
- Full DCS conversion applies
- Still high DR from artificial materials

---

### Aberrations

**Simple Aberrations (Rust Monster, Otyugh):**

- Standard conversion
- Alien instinct replaces tactics

**Complex Aberrations (Mind Flayer, Beholder):**

- Extremely high Sanity (15-20+)
- High Focus (12-16+)
- Cause Sanity saves in nearby creatures (aura)
- Alien psychology grants advantage on mental saves

---

### Oozes & Plants

**Oozes:**

- Very low Evasion DC (slow, amorphous)
- DR varies (acid immunity reduces physical DR)
- Immune to morale
- Vulnerable to called shots (any hit works)

**Plants:**

- Low Evasion DC (rooted or slow)
- Variable DR (bark armor can be high)
- Simple psychology (low Sanity/Focus)
- Vulnerable to fire

---

## Complete Conversion Examples

### CR 1/4 Goblin - Full DCS Conversion

**Original 5E Stats:** AC 15, HP 7 (2d6), Speed 30 ft Str 8 (-1), Dex 14 (+2), Con 10 (+0), Int 10 (+0), Wis 8 (-1), Cha 8 (-1) Proficiency +2

---

**DCS Conversion:**

**Defense:**

- **Evasion DC:** 12 (8 + 2 Dex + 2 Prof)
- **Passive Evasion:** 12 (10 + 2 Dex)
- **DR:** Torso 1, Limbs 1 (Small size, leather scraps)

**Mental Attributes:**

- **Sanity:** 8 (minimum for CR 0-1/4)
- **Focus:** 6 (minimum for CR 0-1/4)

**Momentum:**

- **Range:** -2 to +2 (humanoid)
- **Starting:** 0

**Called Shot Effects:**

- **Head (-2 to hit):** Disorient, disadvantage on next attack (no save)
- **Legs (-2 to hit):** Speed 0, prone (DC 10 Dex save)
- **Arms (-2 to hit):** Drop weapon (DC 10 Str save)

**Reactions:**

- **Opportunity Attack:** Standard only (mook creature)

**Bloodied Effects (at 3-4 HP):**

- **Frailty:** -2 AC (panicked)
- **Strength:** None (cowardly creature)
- **Ability:** Nimble Escape (bonus action hide or disengage)
- **Death Throes:** None (dies pathetically)

**Morale:**

- Very vulnerable to Breaking Points (Sanity 8)
- Cannot Rally (too low Focus)
- Routs easily when leader falls or casualties reach 25%

---

**Tactical Profile:**

**Strengths:**

- Nimble (decent Evasion DC for CR)
- Swarm tactics (use pack advantage)
- Cheap and expendable

**Weaknesses:**

- Fragile (7 HP, DR 1)
- Cowardly (Sanity 8 = breaks easily)
- Predictable (low Focus = poor tactics)

**DM Notes:**

- Use in groups of 6-10 for impact
- They break formation when leader bloodied/dead
- Perfect for demonstrating morale system to players
- Survivors flee at 50% casualties

---

### CR 5 Troll - Full DCS Conversion

**Original 5E Stats:** AC 15 (natural armor), HP 84 (8d10+40), Speed 30 ft Str 18 (+4), Dex 13 (+1), Con 20 (+5), Int 7 (-2), Wis 9 (-1), Cha 7 (-2) Proficiency +3

---

**DCS Conversion:**

**Defense:**

- **Evasion DC:** 12 (8 + 1 Dex + 3 Prof)
- **DR:** Torso 6, Arms/Legs 4, Head 4 (Large + thick hide)

**Mental Attributes:**

- **Sanity:** 11 (8 + (-1) Wis + 2 CR + 2 giant)
- **Focus:** 8 (6 + (-1) mental + 2 CR + (-1) giant, minimum 8)

**Momentum:**

- **Range:** -2 to +2 (giant type, limited intelligence)
- **Starting:** 0
- **Regeneration Bonus:** +1 Focus per round while regenerating

**HP Thresholds:**

- **Bloodied (42 HP):** Triggers bloodied effects + Auto Rally if leading
- **Critical (21 HP):** Major Injury, -2 Momentum

**Called Shot Effects:**

- **Head (-2 to hit):** Stunned 1 round (DC 15 Con save), interrupts regeneration
- **Arms (-2 to hit):** Halve claw damage (DC 15 Str save)
- **Legs (-2 to hit):** Prone + speed 0 (DC 15 Dex save)
- **Torso:** Standard damage only

**Reactions:**

- **Counterattack:** When hit in melee, make claw attack with disadvantage (once per round)

**Bloodied Effects (at 42 HP):**

- **Frailty:** Head DR reduced to 2 (exposed skull)
- **Strength:** +2 to all damage rolls (berserker fury)
- **Ability:** Reckless Assault (advantage on attacks, enemies have advantage against it)
- **Death Throes:** Final swipe (one claw attack at nearest creature)

**Regeneration Interaction:**

- Regains 10 HP per turn (start of turn)
- Regeneration stopped by fire/acid damage
- If regeneration stopped: Lose 1d4 Focus (panic)
- If regenerating: +1 Focus per round (confidence)
- If head shot stunned: No regeneration that round

**Morale:**

- Can lead lesser creatures (orcs, goblins)
- Rally DC varies by casualties
- Simple but determined (Sanity 11)
- Poor tactical adaptation (Focus 8)

---

**Tactical Profile:**

**Strengths:**

- High HP pool (84) + regeneration
- Heavy DR (6 torso, 4 limbs)
- Powerful attacks (multiattack, high damage)
- Psychological resilience (Sanity 11)

**Weaknesses:**

- Low Evasion DC (12 = easy to hit)
- Vulnerable to fire/acid (stops regeneration AND damages Focus)
- Poor tactics (Focus 8)
- Head shot disrupts regeneration

**DM Notes:**

- Showcase called shot system (head shot stops regeneration)
- Demonstrate regeneration-Focus interaction
- Bloodied state makes it more dangerous but more vulnerable
- Use fire/acid to create panic (Focus loss)
- Can be rallied by stronger leaders or used as solo brute

---

### CR 17 Adult Red Dragon - Elite DCS Conversion

**Original 5E Stats:** AC 19 (natural armor), HP 256 (19d12+133), Speed 40 ft, Fly 80 ft Str 27 (+8), Dex 10 (+0), Con 25 (+7), Int 16 (+3), Wis 13 (+1), Cha 21 (+5) Proficiency +6, Legendary Resistance (3/day), Legendary Actions (3/turn)

---

**DCS Conversion:**

**Defense:**

- **Evasion DC:** 16 (8 + 0 Dex + 6 Prof + 2 legendary)
- **Multi-Mode:** Can use Stalwart (Str-based) vs. overwhelming force
- **DR:** Torso 10, Wings 6, Head/Legs/Tail 8 (Huge + supernatural scales)

**Mental Attributes:**

- **Sanity:** 26 (8 + 1 Wis + 4 CR + 4 dragon + 9 ancient wisdom)
- **Focus:** 25 (6 + 5 Cha + 4 CR + 4 dragon + 6 legendary mind)
- **In Lair:** Sanity 30, Focus 29 (+4 territorial dominance)

**Momentum:**

- **Range:** -5 to +5 (dragon, extended)
- **Starting:** 0
- **At +4:** Extra reaction, Frightful Presence forces morale saves
- **At +5:** Crit expansion (19-20), first hit forces Str/Dex save

**HP Thresholds:**

- **Bloodied (128 HP):** Legendary Phase 2 (not standard bloodied effects)
- **Critical (64 HP):** May retreat strategically if not in lair

**Called Shot Vulnerabilities:**

- **Throat (-5 to hit):** Prevents breath weapon for 2 rounds (DC 20 Con save)
- **Wing Membrane (-3 to hit):** One wing = disadvantage on flight, both = grounded (DC 18 Dex save)
- **Eye (-7 to hit):** Blinds dragon, disadvantage on all attacks (DC 22 Dex save)
- **Heart (-6 to hit):** Massive damage, frightens nearby allies (DC 19 Sanity save)
- **Legs (-2 to hit):** Prone (DC 18 Dex save), but can still fly
- **Tail (-2 to hit):** Lose tail attack (DC 18 Str save)

**Reactions (Multiple per Round):**

- **Wing Buffet:** When missed by melee, knock attacker prone (DC 25 Str save)
- **Tail Sweep:** When flanked, attack all adjacent enemies
- **Legendary Parry:** Once per round, impose disadvantage on one attack
- **Frightful Roar:** When bloodied, all enemies within 120 ft make Sanity saves (DC 18)

**Legendary Actions (3/turn):**

- **Detect:** Spot hidden creatures
- **Tail Attack:** Make tail attack
- **Wing Attack (2 actions):** Knock back all nearby creatures, fly half speed
- **Legendary Counter:** When hit, make bite attack immediately

**Legendary Phase 2 (Bloodied at 128 HP):** Instead of standard bloodied effects, dragon enters Phase 2:

- **Enhanced:** Breath weapon recharges on 4-6 (not 5-6)
- **Fury:** +3 to all damage rolls
- **Desperation:** Wings vulnerable (-2 DR, easier to ground)
- **Terrifying:** Frightful Presence DC increases by +2

**Death Throes:**

- **Fire Explosion:** 30 ft radius, 8d6 fire damage (DC 20 Dex save half)
- **Treasure Curse:** Attackers cursed, disadvantage on next treasure roll
- **Final Words:** If intelligent PCs present, grants cryptic warning/prophecy

**Morale & Leadership:**

- **Legendary Rally:** Auto-succeed one Rally per combat
- **Draconic Inspiration:** Kobolds and lesser dragons within 120 ft immune to Breaking Points
- **Territorial Dominance:** +4 to all mental stats in lair
- **Frightful Presence:** Uses Sanity saves (DC 19) instead of Wisdom saves
- **Unbreakable:** Effectively immune to Breaking Points (Sanity 26, or 30 in lair)

**Special Abilities Integration:**

- **Legendary Resistance (3/day):** Can ignore called shot effects
- **Frightful Presence:** Now interacts with Sanity system
- **Fire Immunity:** Represented as DR 10 fire (can't be bypassed)

---

**Tactical Profile:**

**Strengths:**

- Psychologically invincible (Sanity 26)
- Perfect concentration (Focus 25)
- Extreme DR (10 torso)
- Extended Momentum range (-5 to +5)
- Legendary actions provide incredible action economy
- Nearly impossible to break morale

**Weaknesses:**

- Throat shot prevents breath weapon (signature attack)
- Wings can be grounded (loses mobility advantage)
- Eyes can be blinded (loses accuracy)
- Phase 2 makes wings more vulnerable

**DM Notes:**

- This is a multi-phase boss fight (Phase 2 at bloodied)
- Players should target specific body parts strategically
- Lair bonus (+4 mental stats) makes it nearly godlike
- Can Rally minions automatically once
- Use Momentum to show dragon's dominance
- At +5 Momentum, dragon becomes overwhelming force
- Consider retreat option outside lair if reduced to critical HP

**Combat Flow Example:**

**Round 1:** Traditional initiative, dragon likely goes first (high Dex/Wis)

**Round 2+:** Side Initiative, dragon side likely wins (starts 0 Momentum but builds fast)

**Rounds 3-5:** Dragon builds to +3/+4 Momentum, dominates battlefield

**Round 6:** PCs manage to hit dragon to 130 HP (just below bloodied)

- Triggers Legendary Phase 2
- Dragon roars (Frightful Presence, Sanity saves)
- Low-Sanity PCs or allies break
- Dragon still has auto-Rally available if minions falter

**Rounds 7-10:** Phase 2 combat, dragon more aggressive and vulnerable

- PCs target wings to ground dragon
- Called shots to throat to prevent breath weapon
- Dragon uses Legendary Actions to retaliate
- Momentum swings based on success/failure

**Round 11:** Dragon reduced to 60 HP (critical)

- If in lair: Fights to the death with fury
- If outside lair: May offer parley or retreat
- Death Throes if killed (fire explosion)

---

## Integration with Full DCS

### Momentum & Initiative

**Round 1:** Traditional initiative (all creatures roll)

**Round 2+:** Side Initiative based on average Momentum

- Calculate enemy average Momentum
- Calculate player average Momentum
- Higher average acts first
- Ties broken by leader Focus rolls

**Monster Momentum Affects:**

- Enemy attack rolls (Momentum modifier)
- Enemy Evasion DCs (add Momentum)
- Enemy morale (high Momentum = harder to break)
- Initiative order (average Momentum determines side)

---

### Breaking Points & Rally

**When Enemy Leader Bloodied:**

- Automatic Rally attempt (1d20 + Focus vs DC 15)
- Range 120 ft
- Success: Allies restore +1 Momentum
- Failure: Allies lose -1 Momentum

**When Enemy Leader Dies:**

- All allies roll Breaking Point (1d20 + Sanity)
- DC = current casualty DC + 2
- Failure: Rout (panic, flee, surrender)
- Success: Fight on at -1 Momentum

**Casualty Thresholds:**

- 25%: Breaking Point DC 15
- 50%: Breaking Point DC 20
- 75%: Breaking Point DC 25

See Bloodied, Breaking Points & Rally document for full rules.

---

### Injury System

**When Monsters Cross HP Thresholds:**

- 75% HP (Wounded): Roll d8 on Minor Injury table, -1 Momentum
- 50% HP (Bloodied): Roll d8 on Major Injury table, Momentum resets to 0
- 25% HP (Critical): Roll d8 on Critical Injury table, -2 Momentum
- 0 HP: Death saves (if notable) or instant death

**Monster CON Save:**

- DC = 10 + (damage / 10), minimum DC 12
- Success: Reduce injury severity one tier
- Failure: Suffer injury as rolled

**Important:** Only when crossing threshold in single attack, not accumulated damage

See Unified Trauma System for full injury tables and rules.

---

### Concentration

**Monster Spellcasters:**

- Use **Focus modifier** for concentration checks (not Con)
- DC = 10 or half damage, whichever higher
- Low Focus monsters lose concentration easily

**Example:**

- Goblin Shaman (Focus 6) maintains _Bless_
- Takes 12 damage
- Rolls 1d20 + 0 (Focus modifier) vs DC 12
- Likely to lose concentration

**High-CR Spellcasters:**

- Dragon Sorcerer (Focus 25) maintains _Wall of Force_
- Takes 40 damage
- Rolls 1d20 + 7 (Focus modifier) vs DC 20
- Likely to maintain concentration

---

### Evasion & DR Interaction

**Attack Resolution:**

1. **Attack Roll:** PC rolls 1d20 + attack bonus + Momentum
    
2. **Evasion Roll:** Monster rolls 1d20 + Dex + Prof + Momentum
    
3. **Compare:**
    
    - Defender higher: Miss
    - Tie: Glancing blow (half damage, then DR)
    - Attacker higher: Full hit
    - Natural 20 (attacker): Crit, DR halved
    - Natural 20 (defender): Perfect defense, no damage
4. **Apply DR:** Subtract DR for hit location
    

**Example:**

- Rogue attacks Troll torso
- Rogue rolls 18 + 6 (bonus) + 2 (Momentum) = **26**
- Troll rolls 12 + 1 (Dex) + 3 (Prof) + 0 (Momentum) = **16**
- Hit! Rogue deals 4d6 = 18 damage
- Troll has DR 6 (torso)
- Troll takes 12 damage

---

### Called Shots & Reactions

**Called Shot Resolution:**

1. **Declare Target:** Head/arms/legs/wings/etc.
2. **Attack Penalty:** -2 to hit (standard)
3. **Attack Resolution:** Normal attack vs evasion
4. **On Hit:** Apply damage, then target makes save
5. **Save Success:** Resist called shot effect
6. **Save Failure:** Suffer called shot effect (stun, disarm, prone, etc.)

**Reactions Can Modify:**

- Shield reactions may block called shots
- Counterattacks can discourage called shots
- Legendary actions can negate called shot effects

---

## Batch Processing for Large Groups

### When to Batch

**Always Batch:**

- Groups of 5+ identical creatures
- Unimportant mook encounters
- Random wilderness encounters

**Never Batch:**

- Boss fights
- Named NPCs
- Creatures with legendary actions
- Different creature types in same group

---

### Batch Rules

**Evasion:**

- Roll once for entire group vs each attack
- All creatures use same result
- Speeds up combat dramatically

**DR Application:**

- Use single DR value for group
- Don't track location-specific DR for mooks

**Damage:**

- Track total HP for group, not individuals
- Remove creatures as HP drops
- Example: 10 goblins, 70 total HP, remove 1 goblin per 7 HP lost

**Morale:**

- Roll Breaking Points for group, not individuals
- Apply rout results proportionally
- Example: 6 goblins, 3 fail morale, 50% rout

**Momentum:**

- Track group average
- +1 if majority hits, -1 if majority misses
- Simplified tracking

---

## DM Guidance

### When to Convert Fully vs. Shortcuts

**Use Full Conversion For:**

- Boss fights and major encounters
- Recurring villains and named NPCs
- Signature enemies in important story moments
- CR 5+ creatures in parties of 4-6 players
- Any combat where tactics matter

**Use Quick Conversion For:**

- Random encounters
- Mook groups
- CR 1/4-2 creatures in large numbers
- Unimportant battles
- Time-constrained sessions

**Use Batch Processing For:**

- 10+ identical creatures
- Mass combat scenes
- Army battles
- Swarms and mob encounters

---

### Priority Targeting

Not every monster needs full DCS treatment:

**Full DCS Tracking:**

- Leaders (need Rally, Momentum, mental stats)
- Spellcasters (need Focus for concentration)
- Boss monsters (need all systems)
- Creatures with legendary actions

**Simplified DCS:**

- Evasion DC + DR only
- Universal called shot effects
- No Momentum tracking
- No morale system

**Batch Processing:**

- Groups of identical mooks
- Single group Evasion roll
- Single DR value
- Group morale checks

---

### Common Mistakes to Avoid

**Over-Converting:**

- Don't calculate mental attributes for mindless creatures
- Don't track Momentum for every goblin
- Don't use complex called shots on mooks

**Under-Converting:**

- Don't forget mental attributes for leaders (breaks morale system)
- Don't skip DR entirely (makes combat feel like standard 5E)
- Don't ignore bloodied effects on bosses (wastes dramatic moment)

**Forgetting Integration:**

- Remember Momentum affects Initiative from Round 2+
- Remember Focus determines concentration (not Con)
- Remember Sanity determines morale resistance
- Remember injury thresholds trigger when crossed, not accumulated

**Slowing Combat:**

- Don't roll individual evasion for 10 goblins
- Don't track location-specific DR for mooks
- Don't use complex called shots on every attack

---

## Quick Reference: Conversion Checklist

**For any monster encounter, answer these:**

**Tier 1: Essential (Always)**

1. Evasion DC: 8 + Dex + Prof = _____
2. DR: Size + type = _____

**Tier 2: Important (Leaders, Spellcasters, Bosses)** 3. Sanity: 10 + Wis + adjustments = _____ 4. Focus: 8 + Mental + CR/4 = _____ 5. Momentum Range: Type determines = _____

**Tier 3: Complex (Bosses, Named NPCs)** 6. Called Shot Effects: Custom or universal? 7. Reactions: Which signature abilities? 8. Bloodied Effects: What are the 4 effects? 9. Morale: Can it Rally? What's its breaking point?

**Done.** You now have a functional DCS monster.

---

## Design Summary

**Core Principle:** DCS monsters are dynamic combatants with layered defenses, psychological depth, and adaptive behaviors.

**Quick Conversion:** Fast formulas for immediate play (Evasion, DR, mental stats).

**Standard Conversion:** Detailed system for important encounters (called shots, reactions, bloodied effects).

**Batch Processing:** Streamlined rules for large groups (group rolls, simplified tracking).

**Full Integration:** All systems work together (Momentum drives initiative, mental stats enable morale, injuries stack with bloodied effects).

This system transforms monsters from static stat blocks into living, breathing opponents. They have strengths and weaknesses. They build momentum when winning and collapse when losing. They break when their courage fails. They reveal desperate power when bloodied. They have leaders who Rally and followers who rout.

**Give your monsters the depth they deserve. Make every combat a tactical, psychological, dynamic battle.**
