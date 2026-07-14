---
audience: player
type: guide
status: excluded
tags:
  - template
---
# Monsters in the Dynamic Combat System - Complete Guide

> _"A goblin's leather may turn a glancing blow, but a dragon's scales demand respect. Each creature's body tells the story of how it survives - and how it dies."_

---

## Overview

In standard 5E, monsters are fundamentally simple. They have AC - a static number that determines if attacks hit. They have HP - a pool that drains until they die. They have attacks - a list of things they do each turn. Combat is binary: you hit or miss, they live or die. There's no rhythm, no psychology, no sense that these creatures are living beings with survival instincts, breaking points, or tactical adaptations.

A goblin with 7 HP fights identically whether fresh or bloodied, leading a victorious charge or watching its warband crumble. An ancient dragon with 500 HP is just a bigger HP sponge - its legendary intellect and psychological dominance don't affect how combat flows. An orc spellcaster maintains concentration with Constitution saves, as if physical toughness were the only measure of mental discipline.

**The monster is a collection of numbers that players chip away at until it stops moving.**

The Dynamic Combat System fundamentally transforms this. DCS monsters aren't stat blocks - they're dynamic combatants with layered defenses, psychological profiles, and adaptive behaviors. They don't have static AC; they have Evasion representing active defense. They don't have abstract HP pools; they have Damage Reduction showing physical toughness that can be bypassed. They don't maintain concentration with Constitution; they use Focus representing mental discipline.

And they have something standard 5E monsters completely lack: **breaking points**.

### The Psychology of Monster Combat

Every creature capable of thought has moments of crisis. When the goblin warband's chieftain falls bloodied, do they fight harder or does doubt creep in? When half the orc squad lies dead, do they hold formation or scatter? When the ancient dragon - wounded, grounded, seeing its hoard threatened - roars defiance, does it inspire or reveal desperation?

These aren't just narrative flourishes. In DCS, these are mechanical moments with tactical consequences:

**Momentum** - The dragon building Momentum from successful attacks becomes more terrifying, more accurate, more dangerous. The goblin losing Momentum from injuries becomes easier to hit, slower to react, more likely to panic.

**Bloodied Thresholds** - At 50% HP, creatures don't just keep fighting. They reveal desperation. Frailties expose weaknesses players can exploit. Strengths grant resilience that forces adaptation. Abilities trigger dramatic once-per-combat moves. Death Throes promise explosive finales that reward careful positioning.

**Breaking Points** - When the enemy leader dies or casualties mount, the survivors face psychological crises. Low-Sanity goblins break easily, scattering in panic. High-Sanity dragons hold firm, fighting to the death. The difference isn't just flavor - it's a tactical distinction that gives players new ways to win beyond "deal damage until dead."

**Rally** - Enemy leaders with high Focus can restore their troops' courage and hold the line. Leaders with low Focus often make things worse, their hollow cries demoralizing further. Killing the enemy captain isn't just removing one combatant - it's removing the keystone holding enemy morale together.

Without DCS conversion, all these systems break. Monsters can't have Breaking Points without Sanity scores. They can't Rally without Focus. They can't build threatening Momentum without the framework to support it. They can't reveal desperation when bloodied without the mechanics to express it.

### What This Document Provides

This is the complete guide to running monsters in the Dynamic Combat System. It covers every aspect of monster conversion and implementation:

**Section 1: Physical Combat Stats** - Converting AC to Evasion, assigning Damage Reduction, designing called shot vulnerabilities. The foundational layer that makes monster defense dynamic rather than static.

**Section 2: Special Mechanics** - Reactions, Momentum ranges, and creature type variations. How different monsters express their unique combat styles through the DCS framework.

**Section 3: Mental Attributes** - Sanity, Focus, and psychological warfare. Giving monsters the minds they need to interact with morale, fear, concentration, and Breaking Points.

**Section 4: Practical Implementation** - Batch rules, quick references, and table tools for real play. Making DCS monsters run smoothly without overwhelming the DM.

The goal is complete integration. By the end, you'll be able to convert any 5E monster into a full DCS combatant with psychological depth, tactical complexity, and adaptive behaviors. You'll know when to use full conversion for bosses, quick conversion for regulars, and batch rules for mooks. You'll understand how each creature type interacts with each system.

And most importantly, you'll transform combat from "attack until they die" into "exploit their weaknesses, break their courage, and watch them fold."

**Give your monsters the depth they deserve. Make every combat a battle of tactics, psychology, and steel.**

---

# SECTION 1: Physical Combat Stats

## Converting AC, HP, and Attacks to Evasion, DR, and Called Shots

### Evasion Conversion

Replace static AC with dynamic Evasion that monsters actively roll or use passively.

#### Quick Conversion Formula

**Evasion DC = 8 + Dexterity Modifier + Proficiency Bonus**

**Why This Formula?**

Standard 5E AC includes Dex, armor, shields, and magical bonuses all mashed together. Evasion represents active defense only - the creature's ability to dodge, duck, or anticipate attacks. Natural armor becomes Damage Reduction instead. The formula captures just the "avoiding" component.

**Example Conversions:**

- Goblin (AC 15, Dex +2, Prof +2): Evasion DC **12**
- Orc (AC 13, Dex +1, Prof +2): Evasion DC **11**
- Troll (AC 15, Dex +1, Prof +3): Evasion DC **12**
- Ancient Dragon (AC 22, Dex +0, Prof +9): Evasion DC **17**

---

#### CR-Based Proficiency Bonus

|**CR Range**|**Proficiency Bonus**|
|---|---|
|0-4|+2|
|5-8|+3|
|9-12|+4|
|13-16|+5|
|17-20|+6|
|21-24|+7|
|25-30|+8|

---

#### Evasion Methods by Monster Type

**Active Evasion (Roll Each Time)**

- **When to Use:** Important monsters, bosses, creatures with high Dexterity
- **Roll:** 1d20 + Dex modifier + proficiency bonus + Momentum vs attack roll
- **Benefits:** Creates dramatic moments, allows for critical evasion (Natural 20)
- **Drawbacks:** Slower resolution, more dice rolling

**Example:** Adult Red Dragon actively rolls evasion against each attack, adding its Momentum modifier to the roll. When at +4 Momentum, it becomes incredibly difficult to hit.

---

**Passive Evasion (Set DC)**

- **When to Use:** Mooks, large groups, time-pressed encounters
- **DC:** 10 + Dex modifier + proficiency bonus + Momentum
- **Benefits:** Speeds up combat significantly, reduces dice rolling
- **Drawbacks:** Less dramatic, no chance for critical defense

**Example:** Group of 10 goblins all use Passive Evasion DC 12. Players roll to hit vs DC 12 without individual goblin rolls.

---

**Hybrid Approach (Recommended)**

- **Leaders/Elites:** Active evasion with full dramatic potential
- **Regulars:** Passive evasion for quick resolution
- **Minions:** Batch evasion (one roll per group per round)
- **Legendary Creatures:** Active evasion + advantage on rolls

This approach maintains dramatic moments for important creatures while keeping combat flowing for groups.

---

#### Monster Size and Evasion Adjustments

|**Size**|**Evasion Modifier**|**Reasoning**|
|---|---|---|
|Tiny|+2|Hard to hit precisely, small target|
|Small|+1|Harder to target than medium creatures|
|Medium|+0|Standard baseline|
|Large|-1|Bigger target, easier to hit|
|Huge|-2|Much bigger target|
|Gargantuan|-3|Massive target, almost impossible to miss completely|

**Application:** Add these modifiers to the Evasion DC after calculating base.

**Example:** Large Troll (Evasion DC 12 - 1 = **11**), Tiny Sprite (Evasion DC 14 + 2 = **16**)

---

#### Momentum and Evasion

**Critical Integration Point:** Monster Evasion DC increases with Momentum.

- At **+3 Momentum:** Goblin with Evasion DC 12 becomes **DC 15**
- At **-2 Momentum:** Dragon with Evasion DC 17 becomes **DC 15**

This creates the core combat rhythm - winning creatures become harder to hit, losing creatures become easier. The psychological flow of battle manifests mechanically.

---

### Damage Reduction (DR) System

DR replaces the abstract concept of AC reducing hit chance with concrete damage mitigation after attacks land.

**Philosophy:** Heavy armor doesn't make you harder to hit - it makes hits less effective. A knight in plate gets hit just as often as a rogue in leather, but the plate absorbs more punishment. This feels more realistic and creates tactical depth.

---

#### Base DR by Creature Size

|**Size**|**Torso DR**|**Head DR**|**Arms/Legs DR**|**Wings/Tail DR**|
|---|---|---|---|---|
|Tiny|1|0|0|0|
|Small|1|1|0|0|
|Medium|2|1|1|1|
|Large|4|2|2|2|
|Huge|6|3|3|3|
|Gargantuan|8|4|4|4|

**Why Location-Based DR?**

Different body parts have different natural protection. Torsos are thick with muscle and organs. Heads have skulls. Limbs are thinner. Wings are fragile membranes. This creates tactical targeting opportunities - called shots to wings ground flying creatures because wings have lower DR.

---

#### Natural Armor Modifiers

|**Natural Armor Type**|**DR Bonus**|**Examples**|
|---|---|---|
|None/Soft Hide|+0|Most mammals, humanoids in clothing|
|Thick Hide/Fur|+1|Bear, dire wolf, winter wolf, apes|
|Chitin/Carapace|+2|Ankheg, rust monster, umber hulk, giant insects|
|Scales (light)|+2|Lizardfolk, yuan-ti, some reptiles, crocodiles|
|Scales (heavy)|+3|Dragon turtle, adult dragons, ancient wyrms|
|Metallic/Stone Skin|+3|Earth elemental, iron golem, stone giant|
|Supernatural/Magical|+4|Ancient dragons, some outsiders, unique creatures|

**Application:** Add natural armor bonus to base DR from size.

---

#### Creature Type DR Modifiers

|**Type**|**Torso Bonus**|**Other Locations**|**Special Rules**|
|---|---|---|---|
|Beast|+0|+0|Standard natural armor rules apply|
|Humanoid|+0|+0|May wear manufactured armor|
|Giant|+1|+1|Thick hide, robust build|
|Dragon|+2|+1|Legendary scales, ancient hide|
|Fiend|+1|+0|Supernatural resilience|
|Celestial|+2 vs mundane|+1 vs mundane|Radiant protection|
|Undead|+0|+0|Brittle - criticals reduce DR fully|
|Construct|+1|+1|Constructed materials|
|Aberration|+1 (head only)|+0|Alien anatomy, protected brain/core|
|Elemental|+2|+2|Alien physiology|
|Ooze|Variable|N/A|Usually low DR, no distinct body parts|
|Plant|+1|+0|Bark armor, woody growth|

---

#### DR Calculation Examples

**Hill Giant (Large Giant)**

1. **Base DR (Large):** Torso 4, Others 2
2. **Giant Type Bonus:** +1 all locations
3. **Thick Hide:** +1 all locations
4. **Final DR:** Torso **6**, Head/Arms/Legs **4**

**Adult Red Dragon (Huge Dragon)**

1. **Base DR (Huge):** Torso 6, Others 3
2. **Dragon Type Bonus:** Torso +2, Others +1
3. **Heavy Scales:** +3 all locations
4. **Supernatural Protection:** +1 all locations
5. **Final DR:** Torso **12**, Wings **7**, Head/Legs/Tail **8**

**Goblin (Small Humanoid)**

1. **Base DR (Small):** Torso 1, Head 1, Arms/Legs 0
2. **Humanoid Type:** +0
3. **Leather Scraps:** +0
4. **Final DR:** Torso **1**, Head **1**, Arms/Legs **0**

---

#### Manufactured Armor for Humanoids

Humanoid monsters may wear armor, which replaces their base size DR:

|**Armor Type**|**Torso DR**|**Limbs DR**|**Head DR**|
|---|---|---|---|
|Light Armor|2|1|1|
|Medium Armor|4|2|2|
|Heavy Armor|6|3|3|
|Shield (add)|+1 all|+1 all|+1 all|

**Example:** Hobgoblin in Chain Shirt + Shield

- Medium Armor: Torso 4, Limbs 2, Head 2
- Shield: +1 all locations
- Final: Torso **5**, Limbs/Head **3**

---

#### Critical Hit DR Interaction

**Normal Critical (Natural 20 on attack):**

- Halve DR before applying damage
- Example: Torso DR 6 becomes DR 3

**Called Shot Critical (Natural 20 on called shot):**

- Automatic effect application + halved DR
- Example: Head shot stun automatically applies, Head DR 4 becomes DR 2

**Undead Exception:**

- Critical hits reduce Undead DR to **0** (brittle bones)
- Represents decomposed, fragile skeletal structure
- Makes undead vulnerable to precision strikes

---

### Called Shot System for Monsters

Different monster anatomies create unique tactical opportunities and vulnerabilities.

**Philosophy:** Every creature has weak points. Targeting them requires precision (attack penalty) but offers powerful effects. This rewards tactical thinking and makes combat more than "I attack the torso until it dies."

---

#### Universal Called Shot Framework

|**Target**|**Attack Penalty**|**Base Effect**|**Save DC Formula**|
|---|---|---|---|
|Head|-5|Stun/Disorient 1 round|8 + Prof + Attack Mod|
|Arms/Limbs|-2|Disarm/Disable attacks|8 + Prof + Attack Mod|
|Legs|-2|Prone + speed 0|8 + Prof + Attack Mod|
|Wings|-3|Ground flying creature|8 + Prof + Attack Mod|
|Tail|-2|Disable tail attacks|8 + Prof + Attack Mod|
|Torso|0|Normal damage only|N/A|

**How It Works:**

1. **Declare Target:** Player announces called shot location
2. **Apply Penalty:** Attack roll suffers the penalty
3. **Resolve Attack:** Normal attack vs evasion resolution
4. **On Hit:** Apply damage, then target makes save
5. **Save Success:** Resist called shot effect (still took damage)
6. **Save Failure:** Suffer called shot effect (damage + condition)

---

#### Monster-Specific Anatomical Targets

**Dragons**

- **Throat (-6 penalty):** Prevents breath weapon for 2 rounds (Con save DC 8 + Prof + Attack Mod)
    - _Represents damaged internal fire glands or acid sacs_
- **Wings (-3 penalty):** Forces landing if airborne, grounded (Dex save)
    - _One wing damaged = disadvantage on flight checks_
    - _Both wings damaged = cannot fly_
- **Tail (-2 penalty):** Prevents tail attacks for 1 round (Str save)
- **Eyes (-7 penalty):** Blinds dragon (Dex save), disadvantage on all attacks

**Beasts (Quadrupeds)**

- **Front Legs (-2 penalty):** Disables claw attacks, reduces speed by half (Str save)
- **Hind Legs (-2 penalty):** Reduces speed to 0, prone (Dex save)
- **Muzzle/Snout (-4 penalty):** Prevents bite attacks for 1 round (Con save)
- **Eyes (-6 penalty):** Blinds creature (Dex save)

**Humanoids**

- **Weapon Hand (-2 penalty):** Forces weapon drop (Str save)
- **Shield Arm (-2 penalty):** Disables shield bonus to AC/evasion (Str save)
- **Legs (-2 penalty):** Prone + speed reduced to 0 (Dex save)
- **Throat (-5 penalty):** Prevents speech/spellcasting with verbal components (Con save)

**Aberrations**

- **Eye Stalks (-4 penalty, Beholder):** Disables specific eye ray permanently until healed
- **Tentacles (-3 penalty):** Reduces grapple ability, may sever tentacle
- **Brain/Core (-7 penalty):** Severe stunning effect, massive psychic feedback
- **Alien Anatomy:** May be immune to certain precision-based attacks

**Undead**

- **Joints (-3 penalty):** Easier than normal (joints deteriorate), permanent speed reduction
- **Skull (-5 penalty):** May expose glowing eyes/soul essence, vulnerability to radiant
- **Limbs (-2 penalty):** May continue moving even when "disabled" (undead persistence)
- **Spine (-6 penalty):** Severs connection to lower body, immobilizes

**Giants**

- **Knees (-3 penalty):** Prone + speed halved permanently until healed (Str save)
- **Head (-5 penalty):** Disorient, disadvantage on attacks for 2 rounds (Con save)
- **Weapon Arm (-2 penalty):** Drop weapon, may break arm entirely (Str save)

**Constructs**

- **Power Source (-7 penalty):** Disable construct entirely for 1 round (no save)
- **Joints/Hinges (-3 penalty):** Reduce speed to 0 or disable limb function
- **Sensor Arrays (-5 penalty):** Blind construct or disable specific sense

---

#### Creature Immunity Guidelines

|**Creature Type**|**Immune To**|**Reasoning**|
|---|---|---|
|Ooze|All called shots|No distinct anatomy, distributed form|
|Swarm|Precision shots|Distributed among hundreds of creatures|
|Elemental|Most physical effects|Elemental composition, no organs|
|Incorporeal|Physical shots|Lack physical form entirely|
|Plant (some)|Pain-based effects|No nervous system, different biology|
|Undead (skeletal)|Bleeding effects|No blood or circulatory system|

**Important:** These immunities don't make creatures invincible - they just redirect tactics. Oozes take full damage, just can't be targeted precisely. Swarms can be area-damaged. Incorporeal creatures have other vulnerabilities.

---

#### Called Shot Scaling by CR

**Low CR (0-4):**

- Basic effects only
- Shorter duration (1 round)
- Easier save DCs

**Medium CR (5-12):**

- Standard effects
- Normal duration (1-3 rounds)
- Standard save DCs

**High CR (13+):**

- May have resistance to effects
- Legendary resistance can negate
- Harder save DCs
- May require multiple called shots to disable

---

### Integration Guidelines

#### Balancing Physical Stats

**High Evasion + Low DR:**

- **Profile:** Agile but fragile
- **Examples:** Rogues, assassins, flying creatures, monks
- **Tactics:** Hard to hit, but devastating when you do
- **Player Strategy:** Use area attacks, limit movement, force disadvantage

**Low Evasion + High DR:**

- **Profile:** Tanky but hittable
- **Examples:** Heavily armored knights, giants, constructs
- **Tactics:** Easy to hit, but attacks don't hurt much
- **Player Strategy:** Called shots to bypass DR, overwhelming damage

**Balanced Approach:**

- **Profile:** Moderate both for reliable middle-ground
- **Examples:** Most standard humanoid warriors
- **Tactics:** Predictable and fair
- **Player Strategy:** Standard combat applies

**High Both:**

- **Profile:** Elite threats
- **Examples:** Ancient dragons, legendary warriors
- **Tactics:** Hard to hit AND hard to hurt
- **Player Strategy:** Requires teamwork, called shots, momentum manipulation

---

#### Size vs. Mobility Trade-offs

**Large Creatures:**

- Get more DR (survivability)
- Lower evasion (easier to hit)
- Bigger targets for called shots
- More devastating when they hit back

**Small Creatures:**

- Higher evasion (harder to hit)
- Minimal DR (fragile when hit)
- Harder to target precisely
- Less threatening individually

**Medium Creatures:**

- Balanced both aspects
- Standard baseline for system
- Most versatile in tactics

---

#### Monster Role Considerations

**Minions (Cannon Fodder):**

- Low DR, passive evasion for speed
- Basic or no called shot vulnerabilities
- Designed to die quickly
- Batch processing recommended

**Regulars (Standard Encounters):**

- Moderate DR, passive or active evasion
- Standard called shot vulnerabilities
- Core of most encounters
- Individual or small group tracking

**Elites (Challenging Opponents):**

- Moderate-High DR, active evasion for engagement
- Custom called shot vulnerabilities
- Signature abilities and reactions
- Full individual tracking

**Bosses (Major Threats):**

- High DR, active evasion + special defenses
- Unique called shot vulnerabilities
- Multiple reactions and legendary actions
- Full system integration required

---

#### Combat Pacing Through Called Shots

**Early Combat (Rounds 1-3):**

- Most attacks target torso (safe, reliable)
- Players learning enemy capabilities
- Building Momentum to enable later tactics

**Mid Combat (Rounds 4-6):**

- Players start using called shots tactically
- Targeting revealed weaknesses
- Momentum swings determine success rates

**Late Combat (Rounds 7+):**

- Desperate called shots to finish weakened foes
- High-risk, high-reward targeting
- Exploitation of bloodied vulnerabilities

---

## Quick Reference: Physical Conversion

### Step-by-Step Monster Physical Conversion

1. **Calculate Evasion DC:** 8 + Dex mod + Prof bonus (check CR table)
2. **Apply Size Modifier:** Adjust Evasion DC for creature size
3. **Assign Base DR:** Use size table as starting point
4. **Apply Type Modifiers:** Add creature type bonuses
5. **Add Natural Armor:** Factor in hide/scales/carapace bonuses
6. **Note Location DR:** Specify Torso/Head/Arms/Legs/Wings/Tail
7. **Design Called Shot Vulnerabilities:** Identify 1-3 special targets
8. **Choose Evasion Method:** Active for bosses/elites, passive for groups

### Red Flags to Watch

**DR Too High:**

- If DR negates most attacks completely
- Players frustrated by inability to hurt creature
- **Fix:** Reduce by 1-2 points or add vulnerabilities

**Evasion Too Low:**

- If players always hit easily
- Combat becomes boring attrition
- **Fix:** Increase by 2-3 points or add Momentum

**Called Shots Ignored:**

- Players never use tactical targeting
- System feels like standard 5E
- **Fix:** Create obvious vulnerabilities, reward usage

**Combat Slowing:**

- Evasion rolls taking too long
- Too much bookkeeping
- **Fix:** Use passive evasion, batch processing, streamline tracking

---

# SECTION 2: Monster Special Mechanics

## Reactions, Momentum, and Creature Type Variations

### Monster Reaction System

Not all monsters should have complex reactions. Use this tiered approach to maintain combat flow while adding tactical depth where it matters.

**Philosophy:** Reactions make combat dynamic and punish predictable tactics. But too many reactions overwhelm players and slow combat. The key is strategic placement - important monsters get reactions, mooks don't.

---

#### Reaction Tiers by Importance

**Tier 1: No Reactions (Mooks)**

- **Who:** Minions, swarms, basic creatures, cannon fodder
- **Reactions:** Opportunity attacks only (standard 5E)
- **Purpose:** Fast resolution, don't slow combat with decision trees
- **Examples:** Individual goblins, zombies, cultists, giant rats

**Tier 2: Simple Reactions (Regulars)**

- **Who:** Standard monsters, mid-tier threats, squad leaders
- **Reactions:** 1-2 basic options from universal list
- **Purpose:** Add tactical flavor without overwhelming
- **Examples:** Orc warriors, dire wolves, veterans, hobgoblin sergeants

**Tier 3: Signature Reactions (Elites/Bosses)**

- **Who:** Boss monsters, unique creatures, major story threats
- **Reactions:** 2-3 thematic reactions that define their combat style
- **Purpose:** Create memorable, tactically distinct encounters
- **Examples:** Dragon antagonists, vampire lords, archmages, demon princes

---

#### Universal Monster Reactions

Available to any Tier 2+ creature that meets the prerequisites:

|**Reaction**|**Prerequisites**|**Effect**|**Usage Limit**|
|---|---|---|---|
|**Counterattack**|Melee weapon/natural attack|Attack back with disadvantage|1/round|
|**Natural Block**|Natural armor DR 3+|+3 DR against one attack|2/round|
|**Instinctive Dodge**|Dex 14+|Reroll failed evasion once|1/round|
|**Threatening Roar**|Cha 12+, size Large+|Force Sanity save DC 12 in 30 ft|1/combat|
|**Desperate Strike**|Below 25% HP|Attack gains +4 damage|1/combat|
|**Shield Bash**|Shield equipped|Knock attacker prone (Str save)|1/round|
|**Weapon Bind**|Melee weapon|Lock weapons, both at -2 until broken|1/combat|

**How to Use:**

- Assign 1-2 reactions to Tier 2 creatures based on their nature
- Warriors get Counterattack or Weapon Bind
- Agile creatures get Instinctive Dodge
- Tanky creatures get Natural Block

---

#### Creature Type Signature Reactions

**Dragons**

- **Wing Buffet:** When missed by melee attack, knock attacker prone 10 ft back (Str save DC 8 + Str mod + Prof)
- **Tail Sweep:** When flanked (2+ enemies in melee), attack all adjacent enemies with tail
- **Elemental Backlash:** When hit by critical, deal element damage to attacker equal to CR
- **Frightful Roar:** When bloodied, all enemies within 120 ft make Sanity saves (DC 8 + Cha + Prof)

**Giants**

- **Rock Throw:** Reaction to ranged attacks, throw debris back for same damage (Dex save half)
- **Stomp:** When creatures move under 10 ft reach, stomp attack (Dex save DC 8 + Str + Prof or prone + damage)
- **Mighty Sweep:** When surrounded (3+ adjacent enemies), weapon attack hits all adjacent foes

**Beasts**

- **Pack Tactics:** When ally within 5 ft attacked, immediately move 15 ft without provoking
- **Feral Bite:** When reduced below half HP, bite attack with disease/poison
- **Territorial Charge:** When enemy approaches lair/young, charge with double speed and extra damage
- **Desperate Leap:** When bloodied, leap 20 ft to escape (Dex save or knocked prone)

**Fiends**

- **Hellish Rebuke:** When damaged, attacker takes fire/necrotic damage equal to half damage dealt (Dex save DC 8 + Cha + Prof half)
- **Tempting Whisper:** When hitting with attack, force Wisdom save DC 12 + Cha or charm briefly
- **Smoke Form:** When hit by critical, become partially incorporeal (resistance to all damage) until next turn

**Celestials**

- **Radiant Shield:** When ally within 30 ft hit, reduce damage by 1d8 + Cha mod and heal ally same amount
- **Inspiring Presence:** When bloodied, all allies within 60 ft gain advantage on next attack
- **Divine Retribution:** When striking evil creature, bonus radiant damage equal to Cha mod

**Undead**

- **Necrotic Touch:** When hit in melee, attacker takes 1d6 necrotic damage (no save)
- **Unnatural Persistence:** When reduced to 0 HP, make DC 15 Con save to stay at 1 HP (once per combat)
- **Chilling Presence:** When critically hit, attacker must make DC 12 Sanity save or frightened 1 round

**Constructs**

- **Repair Protocol:** When damaged, regain HP equal to damage reduction that was bypassed (once per combat)
- **Overload:** When reduced below 25% HP, next attack deals bonus damage equal to remaining HP
- **Defensive Subroutine:** When targeted by spell, advantage on save (2/combat)

**Aberrations**

- **Reality Warp:** When hit, teleport 10 ft in any direction (including vertically) without provoking
- **Mind Spike:** When damaged, attacker takes 1d8 psychic damage and makes DC 12 Sanity save
- **Alien Reflexes:** When evasion would be hit, reroll evasion with advantage (once per combat)

---

#### Reaction Frequency Guidelines

**Per Round Limits:**

- Most reactions limited to 1/round to prevent overwhelming players
- Prevents "reaction looping" where creature responds to every action

**Per Combat Limits:**

- Major reactions (roars, desperate strikes, transformations) limited to 1/combat
- Creates dramatic moments without repetition

**Legendary Creatures:**

- May use 2 reactions per round
- Can use 1 reaction per triggering event (can't stack same reaction)
- Legendary actions function separately from reactions

**Boss Creatures:**

- May have unlimited uses of weak reactions
- Limited uses of powerful reactions
- Can combine reactions with legendary actions for complex turns

---

### Monster Momentum System

Momentum ranges and behaviors vary dramatically by creature type, reflecting different psychological makeups and combat instincts.

**Philosophy:** Not all creatures build Momentum the same way. Beasts are reactive and flee quickly. Dragons build into overwhelming dominance. Constructs are stable but limited. Aberrations are unpredictable. The Momentum range reflects their psychology.

---

#### Momentum Ranges by Creature Type

|**Type**|**Momentum Range**|**Gain Modifiers**|**Loss Modifiers**|**Special Rules**|
|---|---|---|---|---|
|Beast|-2 to +2|Standard|-2 on first injury|Flee at -2 Momentum|
|Humanoid|-3 to +3|Standard|Standard|Use leadership/morale rules|
|Giant|-4 to +4|+1 when charging|-1 when confused|Rage at +3 Momentum|
|Dragon|-5 to +5|+2 in lair|Only -1 from injuries|Legendary momentum effects|
|Fiend|-3 to +3|+1 from causing fear|-2 from radiant damage|Chaotic swings|
|Celestial|-2 to +5|+1 from helping allies|Rarely lose momentum|Always positive in sacred spaces|
|Undead|-2 to +2|Slow, steady gains|Resist fear losses|Immune to morale effects|
|Construct|-1 to +3|Programmed consistency|Malfunction resets|Very stable momentum|
|Aberration|-4 to +4|Unpredictable (+1 random)|Unpredictable (-1 random)|Random momentum events|

---

#### Momentum Effects by Creature Type

**Dragons at High Momentum**

**+3 Momentum:**

- Advantage on all attack rolls
- +3 to Evasion DC (already hard to hit becomes nearly impossible)

**+4 Momentum:**

- Breath weapon recharges on 4-6 instead of 5-6
- Extra reaction per round
- Frightful Presence aura forces morale saves (DC 15)

**+5 Momentum (Dominating):**

- Crit expansion to 19-20
- Wing attack affects 30 ft cone instead of 15 ft
- Can use legendary action after each PC turn (not just 3 per round)
- First hit forces Str/Dex save (prone/pushed/disarmed)
- Enemies in melee cannot exceed 0 Momentum (suppression aura)

**Giants at High Momentum**

**+3 Momentum (Rage State):**

- Enter rage: +2 to damage, resistance to physical damage
- Advantage on Str checks and saves
- Immune to fear effects

**+4 Momentum (Reckless Fury):**

- Attacks have advantage
- Enemies have advantage against them
- Extra attack on multiattack
- Vulnerable to called shots (rage blinds them)

**Beasts at Low Momentum**

**-1 Momentum:**

- Cautious, won't take risks
- Prefer to circle and wait for openings

**-2 Momentum (Flight Response):**

- Attempt to flee or hide rather than fight
- If cornered, enter desperation (advantage on next attack, then flee)
- **Pack animals:** Scatter if alpha reaches -2 Momentum

**Undead Momentum Immunity**

**Mindless Undead:**

- No momentum system, act according to last commands
- Immune to morale-based Momentum loss
- Steady, predictable behavior

**Intelligent Undead:**

- Use momentum system normally
- Immune to fear-based momentum loss
- Cannot be demoralized below -2 (sustained by hatred/purpose)

**Celestials at High Momentum**

**+3 to +5 Momentum:**

- Aura of inspiration: allies within 30 ft gain +1 Momentum
- Radiant damage on all attacks
- Healing effects increased by 50%
- Automatically succeed Rally attempts

---

#### Environmental Momentum Modifiers

|**Environment**|**Creature Types Affected**|**Modifier**|**Duration**|
|---|---|---|---|
|**Lair/Territory**|Dragons, beasts, giants|+2 to max Momentum|While in area|
|**Sacred Ground**|Celestials|+1 Momentum per round|While present|
|**Consecrated Area**|Fiends, undead|-1 Momentum per round|While present|
|**Wild Magic Zone**|All spellcasters|Random +/-1 each spell|While casting|
|**Corrupted Land**|Celestials|-2 to max Momentum|While present|
|**Deep Water**|Non-aquatic|-2 Momentum immediately|Upon entering|
|**Bright Sunlight**|Undead (some)|-1 Momentum per round|While exposed|
|**Total Darkness**|Creatures with darkvision|+1 Momentum|Against non-darkvision foes|

**DM Application:** These modifiers create tactical terrain choices. Lure the dragon out of its lair to reduce its maximum Momentum. Fight undead on consecrated ground. Use bright daylight against vampires.

---

### Creature Type Variations

Each creature type interacts with DCS systems differently, reflecting their unique nature and psychology.

---

#### Beasts

**Philosophy:** Instinctual, reactive, survival-focused. Operate on primal drives rather than tactics.

**DCS Modifications:**

**Evasion:**

- Full Dex-based calculation
- Advantage when in natural terrain (forest for wolves, water for crocodiles)
- Disadvantage when far from preferred terrain

**DR:**

- Natural armor only, no manufactured equipment
- Thick fur/hide provides baseline protection
- Vulnerable body parts (belly, throat) have -2 DR

**Called Shots:**

- Extra vulnerable to intimidation effects (low Sanity)
- Targeting alpha/parent triggers rage (+2 Momentum immediately)
- Muzzle/snout shots prevent bite attacks

**Reactions:**

- Pack-based (coordinated movement)
- Territorial defensive (protect young/lair)
- Flight response (flee at -2 Momentum)

**Momentum:**

- Quick to build when winning
- Quick to collapse when losing
- Flee quickly at negative Momentum

**Mental Attributes:**

- Low Focus (easily distracted)
- Average Sanity (survival instinct)
- Immunity to existential fears (don't contemplate mortality)

**Special Rules:**

**Pack Tactics:** Share momentum within pack

- Use pack leader's Momentum score
- When alpha flees/dies, entire pack makes Breaking Point check

**Territory Bonus:** +2 to all stats when defending lair/young

- Applies to Evasion DC, damage rolls, save DCs
- Lost if forced away from protected area

**Flight Response:** Automatically attempt to flee at -2 Momentum

- Unless cornered or protecting young
- One desperate attack with advantage, then flee

---

#### Humanoids

**Philosophy:** Balanced, tactical, leadership-oriented. Full emotional and intellectual range.

**DCS Modifications:**

**Evasion:**

- Standard rules apply
- May wear armor affecting calculation
- Training can grant proficiency bonuses

**DR:**

- Equipment-based (armor, shields)
- Cultural variations (different fighting styles)
- Can be disarmed/stripped

**Called Shots:**

- Standard anatomical targeting
- Vulnerable to all precision attacks
- Equipment can be targeted (weapon, shield, armor straps)

**Reactions:**

- Tool/weapon based
- Tactical coordination with allies
- Formation benefits

**Momentum:**

- Full range (-3 to +3)
- Benefits from leadership and morale
- Rally attempts restore Momentum

**Mental Attributes:**

- Baseline for all mental attributes
- Full morale system applies
- Cultural/training modifiers

**Special Rules:**

**Leadership Structure:** Clear chains of command

- Leaders can attempt Rally
- Sub-leaders (sergeants) can coordinate
- Rank provides Focus bonuses

**Equipment Dependence:** Disarming significantly reduces effectiveness

- Without weapon: -4 to attack rolls
- Without armor: Recalculate DR (usually much lower)
- Without shield: Lose AC/evasion bonus

**Cultural Variations:** Different fighting styles by ethnicity/nation

- Disciplined armies (bonus to Focus)
- Berserker cultures (bonus to Momentum gains)
- Nomadic tribes (bonus to evasion)

---

#### Dragons

**Philosophy:** Ancient, arrogant, increasingly dangerous when threatened. Legendary intellects with cosmic perspective.

**DCS Modifications:**

**Evasion:**

- Size penalties offset by supernatural awareness
- Active evasion with advantage (boss-tier)
- Can use Legendary Action to auto-succeed evasion

**DR:**

- Legendary natural armor (supernatural scales)
- Weak points in wing membranes (lower DR)
- Age increases DR (+1 per age category past Young Adult)

**Called Shots:**

- Unique vulnerabilities (throat prevents breath, wings ground)
- Immunities (no "disarm" - claws are part of body)
- Legendary Resistance can negate effects 3/day

**Reactions:**

- Legendary reactions (multiple per round)
- Environmental manipulation (tail sweeps, wing buffets)
- Elemental backlash on critical hits

**Momentum:**

- Massive range (-5 to +5)
- Builds slowly but dominates at high values
- Escalating threat as momentum builds
- Environmental bonus (+2 in lair)

**Mental Attributes:**

- Extremely high Focus (legendary discipline)
- Extremely high Sanity (ancient wisdom)
- Age category bonuses stack
- Immune to fear from sources below their CR

**Special Rules:**

**Age Categories:** Older dragons more formidable

- Each age past Young Adult: +1 DR, +2 Sanity, +2 Focus
- Ancient dragons nearly unbreakable mentally

**Lair Actions:** Environmental reactions tied to territory

- Tied to lair, not personal abilities
- Lost if fought outside lair

**Frightful Presence:** Uses Sanity saves (not Wisdom saves)

- DC = 8 + Cha mod + Prof bonus
- Reflects psychological, not primal fear

**Legendary Resistance:** Can ignore effects

- 3/day auto-succeed any save
- Includes Momentum loss from single source
- Called shot effects can be negated

---

#### Undead

**Philosophy:** Persistent, fearless, driven by dark purpose. Psychology varies by intelligence.

**DCS Modifications:**

**Evasion:**

- Varies by type and intelligence
- Some have supernatural awareness (high-int undead)
- Mindless undead use passive evasion only

**DR:**

- Brittle bones (criticals reduce DR to 0)
- Some have supernatural protection (death knights, liches)
- Vulnerable to bludgeoning (bones shatter)

**Called Shots:**

- May continue functioning despite "disabling" hits
- Joints deteriorate easily (lower save DCs)
- No bleeding effects (no blood)

**Reactions:**

- Based on type and intelligence level
- Mindless: None beyond opportunity attacks
- Intelligent: Full reactions available

**Momentum:**

- Limited range (-2 to +2) for most
- Immune to fear-based loss
- Steady, predictable builds

**Mental Attributes:**

- Varies dramatically by intelligence
- See Mental Attributes section for detailed breakdown
- Mindless: N/A (immune to mental effects)

**Special Rules:**

**Undead Resilience:** Immune to exhaustion, many conditions

- Don't suffer physical trauma penalties
- Poison, disease, exhaustion ineffective

**Turning Vulnerability:** Clerical abilities bypass resistances

- Turn Undead uses different DC (not Sanity)
- Destroyed threshold replaces Breaking Points

**Negative Energy:** Some gain benefits in death/corruption areas

- Heal in necrotic zones
- Stronger in cursed lands

**Brittle Bones:** Critical hits devastating

- All critical hits reduce DR to 0
- Bludgeoning damage gets advantage on injury rolls

---

#### Aberrations

**Philosophy:** Alien, incomprehensible, sanity-blasting. Minds that don't work like mortal minds.

**DCS Modifications:**

**Evasion:**

- Alien anatomies have unexpected movement
- May have multiple ways to move (fly, swim, burrow)
- Difficult to predict (players roll at disadvantage to hit some)

**DR:**

- Unusual hide types
- May be immune to certain called shots (no "head" location)
- Alien biology resists normal damage

**Called Shots:**

- Anatomy doesn't match expectations
- "Head" might be torso, "limbs" might be tentacles
- Custom vulnerabilities replace standard

**Reactions:**

- Bizarre, reality-warping effects
- Psychic feedback on attackers
- Unexpected defensive abilities

**Momentum:**

- Chaotic swings (-4 to +4)
- Unpredictable patterns (random gains/losses)
- Can gain Momentum from confusing players

**Mental Attributes:**

- Extremely high Focus (alien mental superiority)
- Alien Sanity concepts (may be immune or inverted)
- Cause Sanity damage in others

**Special Rules:**

**Madness Aura:** CR 5+ cause Sanity saves

- DC = 12 + CR/3
- On first encounter within 30 ft
- Failure causes Sanity loss

**Alien Anatomy:** May be immune to precision attacks

- Distributed nervous system (no stun from head shots)
- Regenerating tentacles (called shots temporary)
- Multiple brains (backup systems)

**Reality Distortion:** High-CR aberrations alter physics

- Gravity, time, space become unreliable
- Environmental effects beyond normal control

---

#### Constructs

**Philosophy:** Purpose-driven, consistent, methodical. Built rather than born.

**DCS Modifications:**

**Evasion:**

- Predictable but persistent
- May have programmed evasion patterns
- Some can predict attacks (high Int)

**DR:**

- Material-based (stone, metal, wood)
- High DR from artificial materials (+3 bonus)
- May have modular construction (replace parts)

**Called Shots:**

- Structural weak points instead of anatomical
- Power sources, joints, hinges
- May expose internal mechanisms

**Reactions:**

- Programmed responses, very reliable
- Defensive subroutines
- Repair protocols

**Momentum:**

- Narrow but stable range (-1 to +3)
- Very consistent gains/losses
- Predictable behavior

**Mental Attributes:**

- N/A for mindless (immune to mental effects)
- Focused programming for intelligent (high Focus)
- No Sanity for true constructs

**Special Rules:**

**Construct Traits:** Immune to most mental effects

- Poison, disease, exhaustion, charm, fear
- Vulnerable to programming conflicts (confusion spells)

**Structural Integrity:** Different injury system

- Damage to components, not organs
- Can function at 0 HP briefly (1 round grace period)

**Programming Limits:** Cannot adapt beyond parameters

- Fixed tactical responses
- Exploitable patterns
- Vulnerable to unexpected tactics

---

## Integration Guidelines

### Mixing Creature Types in Encounters

When encounters include multiple creature types:

**Use Dominant Type Rules:** For group momentum and morale

- If humanoid leader commands beast pack, humanoids set morale rules
- Beasts still have individual flight responses

**Apply Individual Type Bonuses:** To each creature's personal stats

- Goblin humanoid gets humanoid modifiers
- Worg beast ally gets beast modifiers
- They share momentum only if grouped intentionally

**Maintain Type-Appropriate Reactions:** Even in mixed groups

- Humanoid captains use tactical reactions
- Beast mounts use territorial reactions
- Don't homogenize for convenience

**Consider Intertype Relationships:**

- Celestials inspire nearby allies (+1 Momentum aura)
- Fiends corrupt nearby creatures (Sanity save or -1 Focus)
- Dragons dominate lesser creatures (forced Rally successes)
- Aberrations disrupt normal creatures (random Momentum swings)

---

### Scaling by Challenge Rating

Higher CR creatures of the same type should feel more dangerous through system integration:

**CR 0-4 (Novice Tier):**

- Basic type features only
- Simple reactions (1 max)
- Standard Momentum range
- Low mental attributes

**CR 5-12 (Veteran Tier):**

- Full type features
- Signature reactions (2 max)
- Full Momentum range
- Moderate mental attributes
- Can lead groups

**CR 13-20 (Master Tier):**

- Enhanced type features
- Legendary reactions (3+)
- Extended Momentum range (+/-1 beyond standard)
- High mental attributes
- Environmental effects
- Inspire/suppress nearby creatures

**CR 21+ (Mythic Tier):**

- Transcendent type features
- Unlimited legendary actions
- Massive Momentum range
- Godlike mental attributes
- Reality-warping effects
- Regional effects

**Example Progression - Goblin to Goblin King:**

- **CR 1/4 Goblin:** Basic, DR 1, Evasion 12, Focus 6, Sanity 9
- **CR 1 Goblin Boss:** Leader, DR 2, Evasion 13, Focus 9, Sanity 11, can Rally
- **CR 3 Hobgoblin Captain:** Elite, DR 5, Evasion 14, Focus 12, Sanity 13, tactical reactions
- **CR 7 Goblin Warlord:** Master, DR 4, Evasion 15, Focus 15, Sanity 16, legendary Rally, inspires goblins

---

### Balancing Complexity

Not every creature needs every special rule:

**Important Encounters (Boss Fights, Story Moments):**

- Use full type variations
- All signature reactions
- Complete Momentum tracking
- Full mental attributes
- Custom bloodied effects

**Standard Encounters (Regular Combat):**

- Use basic type modifiers
- Simple reactions (1-2)
- Simplified Momentum (round to nearest)
- Mental attributes for leaders only
- Generic bloodied effects

**Trivial Encounters (Fodder, Random):**

- Use baseline rules with minimal modifications
- No reactions beyond opportunity attacks
- No Momentum tracking
- No mental attributes
- No bloodied effects

**DM Tip:** Start simple. Add complexity as your table becomes comfortable. Full DCS can be overwhelming initially.

---

# SECTION 3: Monster Mental Attributes

## Sanity, Focus, Morale Integration, and the Psychology of Combat

This section covers mental attribute assignment and morale system integration. For complete mental attribute rules and detailed calculations, see the **Monster Mental Attributes** document. For complete morale rules and Rally mechanics, see the **Bloodied, Breaking Points & Rally** document.

---

### Core Mental Attributes

Every creature capable of thought, emotion, or survival instinct needs mental attributes to interact with fear, morale, concentration, and psychological warfare.

**Sanity: Mental Stability Under Stress**

**Purpose:** Represents resistance to fear, trauma, existential horror, and battlefield psychology

**Quick Formula:** 10 + Wisdom Modifier (check CR minimums)

**Standard Formula:** 8 + Wisdom Modifier + CR Bonus + Type Modifier

**Role in Combat:**

- Determines Breaking Point resistance (morale checks)
- Affects fear effect saves
- Measures psychological resilience
- Influences Rally success when leader uses it on troops

---

**Focus: Mental Clarity and Discipline**

**Purpose:** Represents concentration ability, resistance to distraction, tactical awareness

**Quick Formula:** 8 + Highest Mental Stat + CR/4 (check CR minimums)

**Standard Formula:** 6 + Highest Mental Stat + CR Bonus + Type Modifier

- Mental Stat = Best of Int, Wis, or Cha modifiers

**Role in Combat:**

- Powers Rally attempts (leader's Focus determines success)
- Replaces Constitution for concentration checks
- Affects tactical decision-making
- Influences Momentum recovery speed

---

### CR-Based Mental Bonuses

|**CR Range**|**Sanity Bonus**|**Focus Bonus**|**Reasoning**|
|---|---|---|---|
|0-1/4|+0|+0|Weak-willed creatures|
|1/2-2|+1|+1|Basic mental resilience|
|3-4|+2|+1|Experienced threats|
|5-8|+2|+2|Veteran combatants|
|9-12|+3|+2|Elite opponents|
|13-16|+3|+3|Master-tier threats|
|17-20|+4|+3|Legendary creatures|
|21+|+5|+4|Mythic beings|

---

### Mental Attributes by Creature Type

For detailed rules, see **Monster Mental Attributes** document. Quick reference:

|**Type**|**Sanity Mod**|**Focus Mod**|**Special Rules**|
|---|---|---|---|
|Beast|+0|-2|Immune to existential fear|
|Humanoid|+0|+0|Full morale system|
|Giant|+2|-1|Advantage vs confusion|
|Dragon|+4|+4|Immune to fear from CR < own|
|Fiend|+2|+1|Resistance to charm|
|Celestial|+6|+3|Immune to despair, auto-Rally|
|Undead|Special|+1|Varies by intelligence|
|Construct|N/A or +0|+2|Immune to emotional manipulation|
|Aberration|Special|+3|Cause Sanity saves in others|

---

### Morale and Leadership Integration

Mental attributes drive battlefield psychology through the Breaking Points and Rally system.

**When to Use Morale Systems:**

- Enemy leader bloodied
- Enemy leader dies
- Enemy casualties reach 25%/50%/75%

For complete rules, see **Bloodied, Breaking Points & Rally** document.

---

#### Breaking Point Quick Reference

**Triggers:**

1. Leader bloodied - Immediate check for all allies
2. Leader dies - Check at +2 DC for all allies
3. Casualty thresholds - 25%/50%/75%

**Breaking Point DCs:**

|**Situation**|**Base DC**|**Leader Death Modifier**|
|---|---|---|
|25% Casualties|12|+2 if leader dead = DC 14|
|50% Casualties|15|+2 if leader dead = DC 17|
|75% Casualties|18|+2 if leader dead = DC 20|
|Leader Bloodied|Current Casualty DC|+0|

**Resolution:**

- Roll: 1d20 + Sanity modifier vs DC
- Success: Fight on, lose -1 Momentum
- Failure: Rout (panic, flee, surrender)
- Nat 1: Immediate rout + allies disadvantage next check
- Nat 20: Immune to Breaking Points + gain +1 Momentum

---

#### Rally Quick Reference

**When Leaders Attempt Rally:**

- Free action once per round
- When allies fail Breaking Points
- Automatically when leader becomes bloodied

**Rally DCs:** Same as Breaking Point DCs

**Rally Check:** 1d20 + Focus modifier vs DC

**Results:**

|**Roll**|**Effect**|
|---|---|
|Success|Allies reroll failed saves w/advantage, reset to 0 Momentum|
|Failure|Allies lose -1 Momentum|
|Nat 20|Reset to 0 Momentum + advantage on next attack + immune to next Breaking Point|
|Nat 1|Allies locked at -2 Momentum, leader can't Rally again this combat|

**Legendary Leaders:** Auto-succeed one Rally per combat

---

### Fear Effects Integration

Different types of fear interact with mental attributes in distinct ways.

**Standard Fear (Mundane Sources)**

Examples: Frightful Presence, Cause Fear spell, intimidation

- Save: Wisdom saving throw (standard 5E compatibility)
- Additional Effect: If failed, also lose 1 Focus until end of next turn
- Frightened Condition: Imposes -2 penalty to Focus-based rolls
- Duration: Standard spell/ability duration

**Existential Terror (Eldritch Sources)**

Examples: Cosmic horrors, reality distortions, forbidden knowledge

- Save: Sanity saving throw (replaces Wisdom)
- Failure: Causes Sanity damage + potential Corruption
- May Trigger: Mental Trauma in intelligent creatures
- Recovery: Requires Greater Restoration or narrative healing
- Long-Term: Can cause permanent Sanity reduction

**Supernatural Fear (Magical Sources)**

Examples: Dragon fear, fiend auras, undead presence

- Save: Wisdom save with Sanity modifier as bonus/penalty
- Failure: Standard frightened + creature-specific effects
- Duration: Often longer than mundane fear
- Area Effect: May affect multiple targets simultaneously

---

### Fear Immunity and Resistance

|**Creature Type**|**Fear Immunities**|**Fear Vulnerabilities**|
|---|---|---|
|Undead (mindless)|All fear|None|
|Undead (intelligent)|Mundane fear|Holy/radiant fear effects|
|Constructs|All emotional fear|Command/programming conflicts|
|Dragons|Fear from CR < own|None (legendary pride)|
|Celestials|Despair, existential|None|
|Fiends|Most mundane|Good-aligned sources|
|Beasts|Existential/cosmic|Predator/alpha displays|
|Aberrations|Reality-based fear|Pattern/order effects|

---

### Concentration and Spellcasting

For spellcasting monsters, mental attributes replace Constitution for concentration.

**Monster Concentration Rules:**

- **Concentration Checks:** Use Focus modifier (not Con)
- **DC:** 10 or half damage taken (whichever higher)
- **Mental Disruption:** Sanity damage forces concentration checks
- **Focus Thresholds:** Low Focus = easier to break concentration

**Focus-Based Concentration Thresholds:**

|**Focus Score**|**Concentration Effect**|
|---|---|
|12+|Normal concentration rules|
|8-11|Disadvantage on concentration saves from damage|
|4-7|Concentration breaks on any damage|
|1-3|Cannot maintain concentration|
|0|Cannot cast spells requiring concentration|

**Spellcaster Mental Bonuses:**

- **Divine Casters:** +2 Focus (divine guidance), +3 Sanity (faith protection)
- **Arcane Casters:** +2 Focus (magical training), +1 Sanity (broader worldview)
- **Natural Casters:** +1 Focus (instinctive magic), +0 Sanity (standard)

---

### Monster Mental Attribute Examples

**CR 1/4 Goblin**

- Sanity: 9 (minimum for CR)
- Focus: 6 (minimum for CR)
- Morale: Breaks easily, cannot Rally
- Fear: Vulnerable to intimidation

**CR 1 Orc**

- Sanity: 10
- Focus: 8
- Special: +1 Focus when charging (Aggressive trait)
- Morale: Can lead small groups

**CR 5 Troll**

- Sanity: 12 (8 + (-1) Wis + 2 CR + 2 giant + 1 stubborn)
- Focus: 8 (minimum for CR, +1 per round regenerating)
- Morale: Resistant to Breaking Points
- Fear: Immune to complex psychological effects

**CR 9 Young Red Dragon**

- Sanity: 18 (8 + 1 Wis + 3 CR + 4 dragon + 2 young adult)
- Focus: 18 (6 + 4 Cha + 3 CR + 4 dragon + 1 age)
- Morale: Nearly unbreakable, auto-Rally once per combat
- Fear: Frightful Presence uses Sanity saves

**CR 17 Adult Red Dragon**

- Sanity: 26 (in lair: 30)
- Focus: 25 (in lair: 29)
- Morale: Effectively immune to Breaking Points
- Fear: Immune to fear from any source below CR 15

**CR 13 Vampire**

- Sanity: 21 (12 base + 2 Wis + 3 CR + 4 centuries)
- Focus: 20 (12 base + 4 Cha + 3 CR + 1 undead)
- Morale: Unshakeable, supernatural will
- Fear: Immune to existential, vulnerable to holy terror

---

### Mental Attribute Recovery

**Short Rest Recovery:**

- Focus: Regain 1 point if no stressful activity
- Sanity: No natural recovery

**Long Rest Recovery:**

- Focus: Regain 1d4 points in safe environment
- Sanity: Regain 1 point in safe environment

**Magical Recovery:**

- Calm Emotions: Suppresses penalties for duration
- Greater Restoration: Restores 1d4 points to chosen attribute
- Heal: Restores all mental attributes to maximum

**Environmental Recovery:**

- Sacred Ground: Celestials/good creatures +1 per long rest
- Corrupted Areas: Evil creatures may gain similar benefits
- Natural Sanctuaries: Beasts and druids enhanced recovery

---

# SECTION 4: Practical Implementation

## Batch Rules, Quick References, and Table Tools for Real Play

### Large Group Combat Management

When running encounters with many creatures, streamlined approaches maintain DCS benefits while preserving game flow.

---

#### Batch Resolution Hierarchy

**Priority 1: Leaders and Elites**

- Full DCS rules (all systems)
- Individual initiative and detailed tracking
- Complete morale and momentum systems
- All reactions and special abilities
- Examples: Boss monsters, named NPCs, major threats

**Priority 2: Sergeants and Specialists**

- Simplified DCS rules (passive evasion, basic DR)
- Group initiative by type
- Mental attributes for morale only
- Limited reactions (1 signature)
- Examples: Squad leaders, special units, veterans

**Priority 3: Minions and Mooks**

- Minimal DCS rules (fixed DR, no reactions)
- Single group initiative
- No individual mental tracking
- Batch everything possible
- Examples: Individual goblins, zombies, cultists

---

#### Group Evasion Methods

**Option 1: Passive Group Evasion (Fastest)**

- Calculate single Evasion DC for entire group
- All attacks vs that group use same target number
- No rolling needed
- **Best for:** 10+ identical creatures

**Option 2: Representative Rolling (Balanced)**

- Roll evasion once per group per round
- Apply result to all members of that group
- Maintains some randomness
- **Best for:** 5-10 creatures, want some variance

**Option 3: Threshold System (Narrative)**

- Set group "hit threshold" based on average evasion
- Count successful hits until threshold reached
- Abstract individual targeting
- **Best for:** Mass combat, army battles

**Example:**

- 10 goblins, Passive Evasion DC 12
- Player attacks: "I attack the goblin group"
- Player rolls vs DC 12
- Hit = 1 goblin takes damage
- No goblin evasion roll needed

---

#### Batch Damage Reduction

**Uniform DR:** All creatures of same type use identical DR

- Goblin warriors: DR 1 all locations
- Orc soldiers: DR 2 torso, 1 limbs
- Troll pack: DR 6 torso, 4 limbs

**Simplified Called Shots:** Groups have one vulnerability

- Skeleton army: All vulnerable to bludgeoning
- Wolf pack: All vulnerable to intimidation (morale)
- Dragon cultists: All lose Momentum when leader dies

**No Location Tracking:** Just use torso DR for everything

- Speeds resolution dramatically
- Reserve location-specific for Priority 1 creatures

---

#### Group Morale Shortcuts

**Single Leader Rule:** Only track leader's mental attributes

- Leader bloodied/dies triggers morale for entire group
- No individual Breaking Point rolls
- Group succeeds or fails together
- Rally affects entire group at once

**Momentum Sharing:** All group members use leader's Momentum

- Simplifies tracking
- Leader's success/failure affects entire unit
- Individual heroics still possible for named members

**Batch Breaking Points:**

- Roll once for entire group
- Apply result proportionally
- Example: 8 goblins, rolled 12 on Breaking Point DC 15
- Result: 4 succeed (fight on), 4 fail (rout)

---

### Quick Reference Cards

#### Monster Conversion Checklist

```
MONSTER: _____________ CR: ___ TYPE: _______ ROLE: _______

PHYSICAL STATS:
□ Evasion DC: 8 + Dex (___) + Prof (___) = _____
□ Size DR: _____ → Torso _____ / Other _____
□ Natural Armor: _____ → +_____ DR bonus
□ Final DR: Torso _____ / Head _____ / Arms _____ / Legs _____

MENTAL STATS:
□ Sanity: 10 + Wis (___) = _____ (quick) or detailed: _____
□ Focus: 8 + Mental (___) + CR/4 = _____ (quick) or detailed: _____

SPECIAL FEATURES:
□ Reactions: None / Simple (1-2) / Signature (2-3)
□ Momentum Range: _____ to _____
□ Leadership: None / Sergeant / Elite Leader
□ Called Shot Vulnerabilities: _________________

COMBAT NOTES:
□ Morale Immunity: Yes / No (Type: _______)
□ Fear Effects: Standard / Supernatural / Immune
□ Batch Priority: 1 (Full) / 2 (Simple) / 3 (Minimal)
```

---

#### Type Quick Reference Card

|**Type**|**Sanity**|**Focus**|**Momentum**|**Special**|
|---|---|---|---|---|
|Beast|+0|-2|-2 to +2|Flee at -2|
|Humanoid|+0|+0|-3 to +3|Full leadership|
|Giant|+2|-1|-4 to +4|Rage at +3|
|Dragon|+4|+4|-5 to +5|Legendary effects|
|Fiend|+2|+1|-3 to +3|Chaotic|
|Celestial|+6|+3|-2 to +5|Auto-Rally|
|Undead|Special|+1|-2 to +2|Morale immune|
|Construct|N/A/+0|+2|-1 to +3|Stable|
|Aberration|Special|+3|-4 to +4|Sanity auras|

---

#### Combat Flow Quick Card

**Standard Round:**

1. Initiative: Leaders individual, groups together
2. Actions: Full rules Priority 1, simplified Priority 2-3
3. Reactions: Limited to Priority 1 + group leaders
4. Morale: Triggered by leader status or casualties

**Evasion Resolution:**

- Priority 1: Roll individual vs each attack
- Priority 2: Roll once per group per round
- Priority 3: Use passive DC, no rolls

**Damage Resolution:**

- Called Shots: Priority 1 only, torso for others
- Critical Hits: Full rules Priority 1, double damage others
- DR: Use type standard values

---

### Conversion Tools and Tables

#### AC to Evasion Conversion

|**Original AC**|**Quick Evasion DC**|**Use When**|
|---|---|---|
|10-12|8|Low-Dex, heavily penalized|
|13-15|8-10|Most low-CR creatures|
|16-18|10-14|Mid-CR, check Dex+Prof|
|19-21|13-16|High-CR, calculate|
|22+|16+|Legendary, always calculate|

---

#### DR Assignment by Common Monsters

|**Monster**|**Quick DR**|**Notes**|
|---|---|---|
|Goblin|1 all|Small + leather|
|Orc|2 all|Medium + hide|
|Bugbear|2 all|Medium + fur|
|Hobgoblin|5 torso, 3 other|Medium + chain + shield|
|Ogre|5 torso, 3 other|Large + hide|
|Hill Giant|6 torso, 4 other|Large + giant + thick|
|Troll|6 torso, 4 other|Large + regeneration|
|Young Dragon|8 torso, 5 other|Large + scales|
|Adult Dragon|12 torso, 8 other|Huge + heavy scales|
|Ancient Dragon|14 torso, 10 other|Gargantuan + supernatural|

---

### Table Speed Optimization

#### Pre-Combat Preparation

**Monster Cards:** Create index cards with converted stats

```
GOBLIN WARRIOR (x8)
Evasion DC: 12 | DR: 1 all | HP: 7 each (56 total)
Sanity: 9 | Focus: 6 | Momentum: -2 to +2
Called Shots: Head (stun DC 12), Legs (prone DC 12)
Morale: Standard, breaks at 25% casualties
```

**Group Sheets:** Track similar monsters together

```
ORC WARBAND
Leader (Orc Chief): Evasion 11, DR 3/2, HP 30
  Sanity 13, Focus 10, Can Rally
Warriors (x6): Evasion 11, DR 2, HP 15 each (90 total)
  Sanity 10, Focus 8, Group morale
Shared Momentum: -3 to +3 (start 0)
```

---

#### Mid-Combat Shortcuts

**Damage Dice Shortcuts:**

- Pre-roll damage for common attacks
- Write on index card: "Goblin damage: 5, 7, 4, 6, 3"
- Use in order, faster than rolling

**Use Average Damage:**

- Minions deal average damage
- Example: 1d6+1 = 4 damage flat
- Roll only for Priority 1 creatures

**Status Effect Batching:**

- Apply same condition to entire groups
- Track duration by group, not individual
- Token on group card: "Bless (3 rounds left)"

**Morale Wave System:**

- Check morale in "waves" not individually
- First failure triggers group check
- Success stops cascade, failure continues
- Fast resolution of mass routes

---

#### Post-Combat Streamlining

**Injury Recovery:**

- Groups heal at rate of toughest member
- Don't track individual injuries for minions

**Mental Recovery:**

- Leaders recover first, then groups benefit
- Abstract recovery for non-important NPCs

**Experience:**

- Award based on challenge overcome
- Don't calculate per-kill XP for mooks

---

### Scaling Guidelines by Party Size

**Small Parties (2-3 Players):**

- Reduce creature numbers
- Maintain full DCS complexity
- Focus on elite encounters
- Emphasize individual tactical depth

**Standard Parties (4-5 Players):**

- Use all DCS systems as designed
- Mix Priority levels (few elites, some regulars, many minions)
- Full morale system with leadership hierarchies
- Standard encounter building

**Large Parties (6-7 Players):**

- Increase minion count dramatically
- Use batch rules extensively
- Multiple elite opponents for enough targets
- Simplified morale (group checks)

**Epic Parties (8+ Players):**

- Mass combat focus
- DCS provides individual heroics layer
- Army-level morale and momentum
- Streamline everything except PC interactions

---

### Troubleshooting Common Issues

**Combat Taking Too Long**

Symptoms: Rounds lasting 15+ minutes, player boredom

Solutions:

- Move more creatures to Priority 3
- Use passive evasion exclusively
- Pre-roll all damage
- Set 30-second decision timers
- Batch identical actions

**Players Ignoring DCS Features**

Symptoms: No called shots, treating evasion as AC

Solutions:

- Create encounters rewarding tactics
- Give monsters obvious vulnerabilities
- Show DCS benefits through NPC actions
- Offer inspiration for creative use

**Too Much Bookkeeping**

Symptoms: Momentum/mental tracking slowing game

Solutions:

- Visual aids (tokens, cards, boards)
- Delegate tracking to players
- Simplify to Priority 1 only
- Use reference sheets

**System Overwhelming New Players**

Symptoms: Analysis paralysis, system avoidance

Solutions:

- Start with Priority 3 enemies only
- Introduce one system at a time
- Use pre-converted monsters
- Focus narrative over mechanics initially

---

### Implementation Roadmap

**Session 0: System Introduction**

- Explain core concepts
- Provide reference cards
- Set expectations for complexity
- Choose implementation speed

**Sessions 1-3: Basic Implementation**

- Evasion system only
- Basic DR by size
- No called shots/reactions yet
- Standard 5E morale

**Sessions 4-6: Expanded Features**

- Add called shot system
- Introduce simple reactions
- Begin mental attributes
- Add momentum for important creatures

**Sessions 7+: Full System**

- Complete DCS implementation
- Advanced morale system
- Creature type variations
- Custom conversions

---

## Design Summary

**Core Principle:** DCS monsters are dynamic combatants with layered defenses, psychological depth, and adaptive behaviors.

**Physical Stats:** Evasion replaces AC, DR provides damage mitigation, called shots create vulnerabilities.

**Special Mechanics:** Reactions add tactical depth, Momentum creates combat rhythm, type variations ensure uniqueness.

**Mental Attributes:** Sanity and Focus enable morale, fear, concentration, and psychological warfare.

**Practical Tools:** Batch rules for efficiency, quick references for speed, implementation roadmap for adoption.

This system transforms monsters from static stat blocks into living opponents. They dodge and absorb damage. They build momentum when winning and collapse when losing. They break when courage fails. They reveal desperation when bloodied. They have leaders who Rally and followers who rout.

**Give your monsters the depth they deserve. Make every combat a tactical, psychological, dynamic battle where steel meets strategy and courage is tested as much as skill.**

--- 