# The Dynamic Combat System

The **Dynamic Combat System (DCS)** replaces static hit chances and AC with a responsive model of **Evasion**, **Damage Reduction**, and **Reaction-based tactics**. Each turn becomes a battlefield of choices, where perception, position, and timing redefine how combat unfolds.

The system also introduces **Momentum**, a combat rhythm mechanic that rewards aggressive precision and penalises recklessness or hesitation. **Critical Hits** bypass Evasion entirely, reinforcing their brutal impact, while **Combat Flow** establishes a clear turn sequence that empowers both attacker and defender with meaningful decisions.

Defenders can **forego dodging** to seize **tactical reaction windows** — counterattacks, disarms, shield manoeuvres, and more. Every attack roll, dodge, or reaction is not just a number, but a choice woven into the narrative of battle.

> **Universal Rule:** DR cannot be reduced below **0** by any combination of effects, abilities, or skills.

---

# 1. Evasion — The Primary Defence

Static AC is replaced with **Evasion**, representing a character's agility, awareness, and training in avoiding incoming attacks through active defence rather than passive armour class.

---

## Evasion Modes

When you are attacked, you choose **how you defend**:

- **Dodge (Dexterity):** Slip the blow through speed and awareness.
- **Brace (Strength):** Plant your feet and absorb it through armour and stance.
- **Take the Hit:** Deliberately fail your Evasion to gain a free Tactical Reaction.

Your armour type determines which modes are available to you (see Section 2).

---

## Evasion Roll Formula

**Dodge:** `1d20 + Dexterity Modifier + Proficiency Bonus`
- PB applies if proficient in **light armour**, **medium armour**, **shields**, or has **unarmoured defence**.

**Brace:** `1d20 + Strength Modifier + Proficiency Bonus`
- PB applies if proficient in **heavy armour** or **shields**.

Additional modifiers (Bardic Inspiration, Guidance, environmental bonuses) apply after the roll.

> The DC for the Evasion check equals the attacker's total attack roll.

---

## Evasion Outcomes

| Result | Effect |
|---|---|
| **Nat 20 (Defender)** | **Perfect Defence.** Attack misses entirely. Gain one free attack or action as a reaction. Light armour wearers may also shift 5 ft without provoking. |
| **Defender > Attacker** | **Clean Defence.** Attack misses; no damage. Light armour wearers may shift 5 ft without provoking. |
| **Defender = Attacker** | **Glancing Blow.** Damage is halved, then apply DR. Medium armour wearers do not lose Momentum on a tie. |
| **Defender < Attacker** | **Full Hit.** Apply DR normally. |
| **Nat 20 (Attacker)** | **Critical Hit.** Always lands, bypasses Evasion. DR for the targeted body part is halved. |

---

## Defensive Momentum Gains

Successfully defending generates Momentum, rewarding skilled play:

| Defensive Result | Momentum Change |
|---|---|
| **Nat 20 (Defender) — Perfect Defence** | +1 MS (any armour) or +2 MS (light armour) + free reaction |
| Clean Dodge or Brace (any armour) | +1 MS |
| Clean Dodge in light armour | +2 MS |
| Glancing Blow in medium armour | No Momentum change |
| Glancing Blow (other armour) | −1 MS |
| Full Hit | −1 MS |

---

## Critical Hits and Evasion

- A **natural 20 on the attack roll** automatically lands and **bypasses Evasion entirely**.
- DR for the targeted body part is **halved** before applying.
- If the attack is also a Called Shot, the target's saving throw against the Called Shot effect is made **at disadvantage**.

---

## Area of Effect (AoE)

When affected by an AoE (Fireball, dragon breath, etc.):

- Roll **Evasion vs. the spell or ability DC**.
- **Nat 20:** No damage. Light armour wearers shift 5 ft.
- **Success:** No damage.
- **Tie:** Half damage, then DR.
- **Fail:** Full damage, then DR.

---

## Conditions and Modifiers

| Condition | Effect on Evasion |
|---|---|
| Cover (half) | +2 |
| Cover (three-quarters) | +5 |
| Blinded, Surprised, Flanked, or can't see attacker | Disadvantage |
| Prone vs melee | Disadvantage |
| Prone vs ranged | Advantage |
| Restrained or Grappled | Disadvantage (can still Brace) |
| Moved ≥ half speed this turn | +1 Dodge-mode Evasion |

---

# 2. Armour as Damage Reduction (DR)

Armour no longer determines your chance to be hit — it provides **Damage Reduction (DR)**, absorbing damage after a blow lands, based on the **body part** struck. If a targeted location is unarmoured, it provides **0 DR**.

> **Applies To:** DR reduces physical damage types (slashing, piercing, bludgeoning). Magical, elemental, and psychic damage bypass DR unless the armour is specifically enhanced to resist those types.

---

## Armour Types

| Armour Type | Torso DR | Head DR | Arms DR | Legs DR | Defence Mode | Special |
|---|---|---|---|---|---|---|
| **Light** | 2 | 1 | 1 | 1 | Dodge (Dex) | +2 MS on clean dodge; shift 5 ft on dodge |
| **Medium** | 4 | 2 | 2 | 2 | Dodge (Dex) | No Momentum loss on tie |
| **Heavy** | 6 | 3 | 3 | 3 | Brace (Str) only | Highest DR; no dodge-step |

---

## How DR Applies

### Standard Attacks (No Called Shot)
When attacking without targeting a specific body part, damage is reduced by **Total DR** — the sum of all four locations:

**Total DR = Torso DR + Head DR + Arms DR + Legs DR**

This represents the attacker landing where they can, and the defender's armour providing full distributed protection.

> **Example:** A character in heavy armour has Total DR 15 (6+3+3+3). A 20-damage standard attack deals **5 damage**.

> **Design Intent:** Total DR against standard attacks is intentionally high. Full heavy armour is expensive, rare, and dangerous to acquire at low levels — a naturally armoured creature with equivalent DR is equally formidable for a reason. This incentivises Called Shots as a tactical tool, not an afterthought.

### Called Shots (Targeting Specific Location)
When making a Called Shot to a specific body part, damage is reduced by **only that location's DR**:

> **Example:** Called Shot to the arm (−2 penalty) against the same heavy armour target: Location DR 3. A 20-damage attack deals **17 damage**.
> **Trade-off:** Harder to hit, but bypasses 12 points of DR.

> Against heavily armoured opponents (Total DR 12+), Called Shots to arms or legs often deal more total damage despite the accuracy penalty.

---

## Critical Hits and DR

A critical hit automatically lands and **halves the DR** of the targeted body part before applying it.

---

## Layered Armour Rule

Players may layer lighter armour beneath heavier armour:
- **Effect:** DR values **stack** for the affected location.
- **Penalty:** Each additional layer reduces movement speed by **5 feet**.
- **Limit:** No more than **two layers** per body part (one per armour type) unless stated otherwise.

> **Example:** Gambeson (Light, Torso DR 2) under a breastplate (Medium, Torso DR 4) = **Torso DR 6**, but −5 ft movement.

---

## Optional Rules

### Armour Degradation (Optional)
Each time you take more than **10 damage** to a body part after DR is applied, roll a d6. On a **1**, that piece of armour's DR is reduced by 1 until repaired. Magical armour is only damaged on a 1 by magical weapons or critical hits.

### Weight Threshold Fatigue (Optional)
If total armour DR across all body parts exceeds your **Strength score**, gain 1 level of Exhaustion at the start of combat unless you pass a **Constitution save (DC 10 + armour layers)**. This check only applies if wearing armour you are not proficient in, or if DR exceeds your Strength score.

---

# 3. Called Shots — Precision Strikes

Attackers may declare a **Called Shot** to target a specific body part before making their attack roll, imposing tactical effects beyond standard damage.

Any character proficient with the weapon or spell being used may target **basic areas**. Targeting **advanced areas** also requires proficiency with the weapon or spell.

---

## Core Rules

1. **Declaration:** Called Shots must be declared **before** the attack roll is made.
2. **Attack Penalty:** A flat penalty applies based on the targeted location (see tables below).
3. **Passive Perception Detection:** When a Called Shot is declared, compare the defender's **Passive Perception** to the Detection DC. This is automatic — no action required.
   - **Detection DC** = 10 + Attacker's Attack Bonus − Called Shot Penalty
   - More extreme Called Shots (e.g., Head −5) are easier to spot due to telegraphing.
   - If **Passive Perception ≥ DC:** Defender gains **advantage** on their Evasion roll and is aware of the targeted location.
   - If **Passive Perception < DC:** Defender rolls Evasion normally.
4. **Resolution:** On a hit, roll damage normally. The target makes a **saving throw** to resist the Called Shot effect. On a **glancing blow**, damage is halved then DR applied — if any damage remains after DR, the Called Shot effect applies. If DR reduces the glancing blow damage to exactly 0, no effect triggers.
5. **Critical Hits:** If the attack is a critical hit, the saving throw against the Called Shot effect is made **at disadvantage**.
6. **Once Per Attacker Per Turn:** Only **one Called Shot effect** may apply per attacker per turn, regardless of how many attacks or spells land. If multiple hits could trigger effects, the attacker chooses which one applies; remaining hits deal damage only.
7. **Monster Immunities:** Creatures without relevant anatomy (oozes, swarms, elementals) may be immune to specific Called Shots at GM discretion. Effects may be adapted (e.g., "eye" → "sensory core," "leg" → "locomotive appendage").
8. **Unarmoured Targets:** If the targeted body part is unarmoured, the Called Shot saving throw is made at **disadvantage**. (Exception: creatures with Unarmoured Defence.)
9. **Stacking Penalties:** If the attacker already has disadvantage, Called Shot penalties still apply, making precision attacks riskier under pressure.

---

## Basic Areas

*Available to any character proficient with the weapon or spell being used.*

| Targeted Body Part | Attack Penalty | Save | Effect |
|---|---|---|---|
| **Head** | −5 | CON | Stunned/disoriented: Disadvantage on attacks + lose Reaction until end of next turn. |
| **Arms** | −2 | STR | Disarm or impose −2 to attacks for 1 round. |
| **Legs** | −2 | DEX | Speed reduced to 0, or fall Prone. |
| **Torso** | 0 | — | Standard damage; no additional effect. |

## Advanced Areas

*Requires proficiency with the weapon or spell used.*

| Target | Penalty | Save | Effect |
|---|---|---|---|
| **Eye** | −7 | CON | Blinded until end of next turn. |
| **Hand** | −4 | DEX | Drop held object or fail somatic spell component. |
| **Throat** | −6 | INT | Silenced for 1 turn (no verbal spells, no shouts). |
| **Wing** | −3 | DEX | Fall if airborne, or lose flight for 1d4 rounds. |
| **Tail** | −3 | DEX | Lose balance; fall prone if save fails. |

---

## Weapon Skills and Called Shots on the Same Attack

A Weapon Mastery Skill and a Called Shot may both be declared on the same attack. If both would impose a condition or require a saving throw, only **one saving throw** occurs — the attacker chooses which effect the save resists. The other effect applies automatically. This rewards tactical layering without removing defensive agency.

---

## Momentum Synergy

If a Called Shot **lands** and the target **fails their saving throw**, gain **+2 Momentum** instead of +1.

---

## Optional Rule: Insightful Combatant

A character may use **Insight** instead of Passive Perception against humanoid foes they have fought for more than 2 rounds, or who are attempting feints or disinformation. Rangers may use this against favoured enemies; Investigators may use it against any humanoid.

---

# 4. Shields as Dynamic Tools

Shields are active tools used both defensively and offensively through **reaction-based manoeuvres**. Their DR bonus, evasion interaction, and available reactions depend on their type.

---

## Shield Types

| Shield Type | DR Bonus | Evasion | Defence Mode | Notes |
|---|---|---|---|---|
| **Small Shield** | +2 DR (arm location) | +2 to Evasion rolls | Dodge or Brace | Light and nimble. Combines fully with both Dodge and Brace. |
| **Standard Shield** | +3 DR (arm location) | None | Dodge or Brace | Balanced protection. No evasion bonus, but solid DR and reaction options. |
| **Great Shield** | +5 DR (all locations while raised) | None | **Brace only** | Cannot Dodge while wielding. Massive soak. Imposes disadvantage on Stealth unless proficient in heavy armour. |

> Shield DR values represent the arm location as standard. Shield Block and Deflect reactions may extend this protection to other locations at time of use.

---

## Shield Reactions

| Reaction | Effect |
|---|---|
| **Shield Block** | Add **+3 DR** against one incoming attack. Declare after the attack hits but before damage is rolled. |
| **Shield Deflect** | Contest the attacker's roll with **Strength (Athletics)**. On success, the attack is completely negated. |
| **Shield Bash** | As a reaction to a melee attack or opportunity, deal **1d6 + Strength modifier** bludgeoning damage and attempt to push the attacker **5 feet** (Strength vs Strength or Dexterity contest). |

> Great shields add their DR to **all locations** while raised via Block, not just the arm. This represents the shield being actively interposed across the body.

---

## Optional Rule: Shield Stances

A character wielding a shield may adopt a **Shield Stance**, consuming their movement for the turn. Only one stance may be active at a time. Switching stances ends the previous one and costs half their total movement.

| Stance | Effect |
|---|---|
| **Defensive Brace** | Gain +1 Momentum when using Block. Attackers have disadvantage if you haven't moved this round. |
| **Offensive Press** | Advantage on Bash checks; +2 bludgeoning damage. Cannot Dodge while in this stance. |
| **Bulwark Wall** | Allies directly behind you gain +2 DR against ranged attacks. Cannot Dash or use reactions that move you. |
| **Interceptor's Flow** | Take one extra shield reaction per round. If both reactions fail, lose all Momentum and take −2 to Evasion until end of your next turn. |

Certain classes (Fighter, Paladin) may adopt a stance as a **bonus action** instead of using movement.

---

# 5. Forgoing Evasion — Tactical Reactions

A defender may **deliberately fail their Evasion roll** to gain a **free Tactical Reaction**. This represents taking the hit to exploit an opening, create Momentum, or control the battlefield.

---

## Rules

- You may forego Evasion **once per attack, per attacker**, per round. Each separate enemy's attack is its own opportunity. You cannot forego evasion against the same attacker's second hit in a multi-attack sequence unless that hit comes from a new action (such as Action Surge, which creates a new window).
- Forgoing Evasion does **not** consume your normal reaction for the round.
- When you forego Evasion, **immediately declare which Tactical Reaction you are using** — before damage is rolled. This allows reactions like Shield Block to modify the incoming damage. You then take the full hit, and execute your declared reaction.
- You take **full damage** from the attack (after DR), including all additional effects (poison, knockback, etc.).
- You lose **−1 Momentum** for taking the hit.

---

## Tactical Reaction Options

| Reaction | Effect |
|---|---|
| **Counterattack** | Make a melee or ranged weapon attack against the attacker with **advantage**. |
| **Magic Attack** | Make a touch spell against the attacker with advantage, or a ranged spell without. If you have already used a levelled spell this turn, the attack must be a cantrip. |
| **Trap / Disarm** | Attempt to restrain, entangle, or disarm the attacker (opposed Strength or Dexterity check). |
| **Shield Reaction** | Use one Shield Reaction (Block, Bash, Deflect) as a free reaction. |
| **Grapple Back** | Immediately initiate a Grapple (Athletics vs Acrobatics/Athletics). |
| **Trip / Sweep** | Attempt to knock the attacker prone (they make a Dexterity save). |
| **Tactical Retreat** | Move 5 feet without provoking opportunity attacks (requires open space). |
| **Weapon Bind** | Lock the attacker's weapon with yours — both suffer −2 to attacks until one breaks the bind (opposed Strength). |
| **Intimidating Glare** | Force the attacker to make a **Wisdom save (DC = 8 + PB + CHA mod)** or suffer disadvantage on their next attack and lose 1 Momentum. Once per encounter per target. |

> **Momentum Note:** Successfully landing a Counterattack or Disarm this way grants **+2 Momentum** instead of +1. This is an intentional reward for high-risk play — taking a hit to strike back is bold, and the Momentum gain reflects the tempo shift.

---

# 6. Momentum — Combat Rhythm

**Momentum** represents the flow and tempo of battle — a living measure of rhythm, timing, and control. It rises when you strike with precision or dominate the field, and falls when you falter or suffer punishing blows.

> For full Momentum rules including monster scaling, epic tiers, the Exhaustion interaction, and the optional Swing Guardrail, see the **Momentum** document. The summary below covers core DCS interactions.

---

## Tracking Momentum

- Characters begin combat at **0 Momentum**.
- Momentum is tracked per character (or creature) and resets to 0 after combat ends.
- **Standard range:** −2 to +3. Expands to +4 at level 17, +5 at level 20.

---

## Gaining Momentum

| Event | Momentum Gained |
|---|---|
| Successful attack | +1 MS |
| Critical Hit | +2 MS |
| Successful Called Shot (target fails save) | +2 MS |
| Clean Dodge or Brace | +1 MS |
| Clean Dodge in light armour | +2 MS |
| Successful Counterattack or Disarm via Forgoing Evasion | +2 MS |
| Successful Shield Bash or Deflect | +1 MS |
| Dropping an enemy to 0 HP | +1 MS |
| Healing an ally | +1 MS |
| Tactical or environmental edge (GM discretion) | +1 MS |

---

## Losing Momentum

| Event | Momentum Lost |
|---|---|
| Missed attack | −1 MS |
| Critical hit received | −2 MS |
| Forgoing Evasion (taking the hit) | −1 MS |
| Glancing blow received (non-medium armour) | −1 MS |
| Critical fail on any roll (Nat 1) | −2 MS |
| Receiving a condition (Stunned, Blinded, etc.) | −1 MS |
| Failing a saving throw | −1 MS |
| Knocked Prone or Restrained | −1 MS |
| Minor Injury (75% HP — Wounded) | −1 MS |
| Major Injury (50% HP — Staggered) | Reset to 0 |
| Critical Injury (25% HP) | −2 MS |
| Fatal (0 HP) | Reset to 0 |

> **Barbarian Exception:** The Barbarian's Momentum resilience is Rage-dependent and scales with level. While Raging: Major Injury drops MS to −1 instead of resetting (Resilient Flow); starting a turn at −2 or lower grants +2 MS (Fury Threshold). At Level 11, MS cannot be reduced below 0 while raging. Outside Rage, Barbarians lose Momentum normally.
> **Monk Exception:** Monks ignore the −1 MS penalty from missed attacks. A Nat 1 (−2 MS) still applies. All other Momentum losses are normal.

---

## Swing Guardrail (Optional)

A creature cannot gain or lose more than **±2 Momentum per turn** (before injury resets). This prevents yo-yoing and keeps pacing steady. Recommended for groups new to DCS or running high-encounter-density sessions.

---

## Momentum Effects

| Score | Effects |
|---|---|
| **+3** | +3 to Attack & Evasion. First attack each turn has Advantage. Enemies have Disadvantage on Called Shots against you. |
| **+2** | +2 to Attack & Evasion. +5 ft movement speed. |
| **+1** | +1 to Attack & Evasion. |
| **0** | No effect. |
| **−1** | −1 to Attack & Evasion. |
| **−2** | −2 to Attack & Evasion. Critical threat range against you expands to 19–20. |

---

## Resetting Momentum

Momentum naturally resets when combat rhythm breaks:

- **Short Rest or Scene Break:** Reset to 0.
- **Disengage or Withdraw Action:** Reset to 0. *(Note: this refers to the Disengage/Withdraw action, not the act of rolling Evasion — defenders roll Evasion every time they are attacked without any Momentum penalty.)*
- **Knocked Unconscious or Stabilised:** Reset to 0.
- **GM Discretion:** Parley, battlefield pauses, or magical disruptions may force a reset.

A character can only prevent or soften a Momentum reset **once per combat** unless a feature explicitly states otherwise.

---

# 7. Combat Flow — Step by Step

Every attack in DCS follows this sequence. Both attacker and defender have clear decision points at each step.

---

| Step | Attacker | Defender |
|---|---|---|
| **1. Declare Attack** | Declare a standard attack or a Called Shot (specify targeted body part). | Prepare to assess. |
| **2. Called Shot Detection** | *(Called Shots only)* | Compare **Passive Perception** to Detection DC (10 + Attack Bonus − Called Shot Penalty). If Passive Perception ≥ DC, gain **Advantage on Evasion** and know the target location. No roll required; this is automatic. |
| **3. Attack Roll** | Roll `1d20 + attack bonus`. Apply Called Shot penalty if applicable. | — |
| **4. Critical Hit Check** | If Nat 20: attack automatically lands. Skip Evasion. DR is halved. Called Shot save (if any) is at **disadvantage**. | — |
| **5. Evasion Roll** | If not a critical hit, note the attack roll total. | Choose Dodge or Brace (based on armour). Roll Evasion against the attack roll as DC. Compare result. |
| **6. Damage Roll** | If the attack lands (full or glancing), roll damage. | — |
| **7. Apply DR** | — | Apply DR for the targeted body part. On a glancing blow, halve damage first, then apply DR. DR cannot be reduced below 0. |
| **8. Tactical Reaction** | Brace for potential reaction. | If you chose to **forego Evasion**, you already declared your Tactical Reaction before the damage roll. Now execute it — resolve contested rolls, attacks, or effects as stated. |
| **9. Resolve Effects** | — | Apply all remaining effects in order: (a) injury threshold rolls first, (b) Called Shot saving throws, (c) conditions and ongoing effects. For enemies at 50% HP, Bloodied effects trigger after the injury roll. See the Injury and Bloodied Sequencing note below. |

---

## Injury and Bloodied Sequencing

When an enemy crosses the 50% HP threshold:

1. **Injury System triggers first** — roll on the Major Injury table and apply the result.
2. **Bloodied effects trigger second** — the creature's Frailty, Strength, Ability, and Death Throes all activate.

Both systems apply. Injury represents physical trauma; Bloodied represents the psychological and instinctive shift of a creature fighting for its life. The Bloodied system applies to **enemies and monsters only**. Player characters are subject to the Injury System but do not use Bloodied effects.

---

# 8. Injury System — Summary

When you cross an HP threshold, you may attempt to mitigate the injury before it is rolled. You must **choose your mitigation option before the injury table is rolled** — you are committing blind.

**Option A — Constitution Save (Reduce Injury Tier):**
Roll CON save (DC = 10 + damage taken ÷ 10, minimum DC 12). Success reduces the injury one tier (Critical → Major, Major → Minor, Minor → Ignored).

**Option B — Grit Save (Ignore Injury, Gain Exhaustion):**
Declare a Grit Save instead of rolling on the table. Suffer 1 level of Exhaustion. Ignore the injury and its Momentum effects entirely.

You may not attempt both options on the same threshold crossing.

> **Note:** Exhaustion gained from any source — including Grit Saves — reduces all Momentum gains by 1 per level (minimum 0 per event). A character who uses Grit Saves repeatedly will find their ability to build combat rhythm increasingly compromised. See the Momentum document for full details.

> For full injury tables and monster injury variants, see the **Injury System** document.

---

# 9. Class Hooks

Key class interactions with the DCS — see individual class entries for full details.

| Class | DCS Integration |
|---|---|
| **Rogue** | Sneak Attack ignores DR. Tie results may be treated as a clean dodge (class feature). |
| **Monk** | Spend Focus to reroll a failed Evasion. Does not lose Momentum from missed attacks. |
| **Ranger** | Adds Wisdom modifier to Evasion vs marked or favoured targets. |
| **Barbarian** | Advantage on Brace rolls while Raging. Con modifier adds to DR while Raging. Rage reduces Momentum losses from Major Injury thresholds rather than ignoring them entirely. |
| **Paladin** | Aura grants DR equal to Charisma modifier to nearby allies. Shield reactions integrate with Brace. |
| **Magus** | Arcane Guard grants scaling DR while concentrating. |
| **Investigator** | Studied targets have their DR reduced. |
| **Shaman** | Totemic Wards grant elemental DR to allies. |
| **Witch** | High-level Hex of Frailty reduces enemy DR. |
| **Fighter** | Shield reactions integrate with Brace. Multiple Weapon Skills per round. |

---

# 10. Design Summary

The DCS is built around five interlocking pillars:

**Active Defence** — Defenders roll every attack. Defence is never passive.

**Armour as Soak, Not Hit Chance** — Armour absorbs damage. Skill avoids it. Both matter.

**Momentum as Rhythm** — Combat has tempo. Build it, protect it, deny it to your enemies.

**Called Shots as Tactical Depth** — Every location means something. Precision is rewarded.

**Risk and Reward** — Taking a hit to land a counterattack, absorbing a blow to shield your ally, and fighting through injury are all meaningful choices that shift the rhythm of battle.

Every attack in DCS is a **meaningful roll** — you are not passively waiting to see if a static number is beaten. You are actively deciding how you survive, and every decision has consequence.
