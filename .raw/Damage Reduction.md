# Damage Reduction

> *"Armour does not make you harder to hit — it makes you harder to kill."*

---

## 1. What Is DR?

**Damage Reduction (DR)** is the soak value provided by armour, shields, or natural resilience. It reduces damage **after** a blow lands, working in tandem with Evasion and Brace.

- **Evasion (Dodge)** — avoid the blow through Dexterity.
- **Evasion (Brace)** — absorb and redirect through Strength.
- **DR** — mitigate the damage that does connect.

> **Universal Rule:** DR cannot be reduced below **0** by any combination of effects, abilities, skills, or conditions. DR may reduce incoming damage to 0 entirely — a well-armoured defender can fully absorb a weak blow.

---

## 2. How DR Works

1. Resolve the **Evasion or Brace** roll.
2. If the attack lands (full hit or glancing blow): roll damage.
3. On a **glancing blow**, halve the damage first, then apply DR.
4. Apply the **DR of the targeted body part** to the damage rolled.
5. On a **critical hit**, DR for the targeted body part is **halved** (round down) before applying.
6. Remaining damage is subtracted from HP.

---

## 3. Armour Types

### Light Armour

| Location | DR |
|---|---|
| Torso | 2 |
| Head | 1 |
| Arms | 1 |
| Legs | 1 |

- **Defence Mode:** Dodge (Dex + PB)
- **Special:** On any successful dodge, shift **5 ft** without provoking opportunity attacks.
- **Momentum:** +2 MS on a clean dodge (vs +1 for other armour types).
- **Mobility:** No speed penalty.
- **Stealth:** No disadvantage.
- **Playstyle:** Mobile skirmishers who survive by slipping away. Low DR, but high rhythm generation and repositioning.

**Examples:** Padded, Leather, Studded Leather, Gambeson (as base layer).

---

### Medium Armour

| Location | DR |
|---|---|
| Torso | 4 |
| Head | 2 |
| Arms | 2 |
| Legs | 2 |

- **Defence Mode:** Dodge (Dex + PB)
- **Special:** No dodge-step. On a **glancing blow (tie)**, no Momentum is lost.
- **Momentum:** No Momentum change on a tie result.
- **Mobility:** May impose Stealth disadvantage depending on material (chain, brigandine, scale).
- **Playstyle:** Reliable hybrid defence — steady soak with some agility. No flashy perks but consistent performance.

**Examples:** Scale Mail, Chain Shirt, Brigandine, Breastplate.

---

### Heavy Armour

| Location | DR |
|---|---|
| Torso | 6 |
| Head | 3 |
| Arms | 3 |
| Legs | 3 |

- **Defence Mode:** **Brace only (Str + PB).** Cannot Dodge.
- **Special:** Highest DR of any armour type. No dodge-step, no reposition perk.
- **Mobility:** −5 ft speed unless Strength ≥ 15. Disadvantage on Stealth checks.
- **Playstyle:** Anchored tank. Holds the line, absorbs punishment, protects allies. Maximises soak at the cost of all mobility.

**Examples:** Half-Plate, Splint, Full Plate.

> **Design Intent:** Heavy armour's Total DR (15) against standard attacks is intentionally high. Full heavy armour is expensive, rare, and difficult to acquire — a naturally armoured creature with equivalent DR is equally formidable for a reason. This system incentivises Called Shots as a tactical tool against armoured opponents, not an afterthought.

---

## 4. Shields

Shields provide DR and may grant Evasion bonuses depending on type. Shield DR applies to the **arm location** as standard; Block and Deflect reactions may extend protection to other locations at time of use.

| Shield Type | DR Bonus | Evasion Bonus | Defence Mode | Notes |
|---|---|---|---|---|
| **Small Shield** | +2 (arm location) | +2 to all Evasion rolls | Dodge or Brace | Light and nimble. Combines fully with both Dodge and Brace. |
| **Standard Shield** | +3 (arm location) | None | Dodge or Brace | Balanced protection. No evasion bonus but solid DR and reaction access. |
| **Great Shield** | +5 (all locations via Block) | None | **Brace only** | Cannot Dodge. Massive soak. Imposes Stealth disadvantage unless proficient in heavy armour. |

> A character wielding a **great shield** cannot make Dodge Evasion rolls. They must Brace. The great shield's +5 DR bonus applies to **all locations** when used in a Block reaction — not just the arm — representing the shield being actively interposed across the body.

### Shield Reactions

| Reaction | Effect |
|---|---|
| **Block** | Add **+3 DR** against one incoming attack. Declare after the attack hits, before damage is rolled. |
| **Deflect** | Contest the attacker's roll with **Strength (Athletics)**. On success, the attack is completely negated. |
| **Bash** | Deal **1d6 + Strength modifier** bludgeoning damage and attempt to push the attacker 5 ft (Strength vs Strength or Dexterity contest). |

---

## 5. How DR Applies — Standard Attacks vs Called Shots

### Standard Attacks (No Called Shot)

When attacking without targeting a specific body part, damage is reduced by **Total DR** — the sum of all four locations:

**Total DR = Torso DR + Head DR + Arms DR + Legs DR**

This represents the attacker landing where they can, and the defender's armour providing full distributed protection.

| Armour | Torso | Head | Arms | Legs | Total DR |
|---|---|---|---|---|---|
| Light | 2 | 1 | 1 | 1 | **5** |
| Medium | 4 | 2 | 2 | 2 | **10** |
| Heavy | 6 | 3 | 3 | 3 | **15** |

> **Example:** A 20-damage standard attack against a character in heavy armour deals: 20 − 15 = **5 damage**.

---

### Called Shots (Targeting a Specific Location)

When making a Called Shot, damage is reduced by **only that location's DR** — bypassing the distributed protection of the full armour system.

| Armour | Arm DR | DR Bypassed vs Standard | Worth the −2 Penalty? |
|---|---|---|---|
| Light | 1 | 4 | Situational |
| Medium | 2 | 8 | Usually |
| Heavy | 3 | 12 | **Almost always** |

> **Example:** Called Shot to the arm (−2 penalty) against heavy armour. Location DR: 3. A 20-damage attack deals: 20 − 3 = **17 damage**. The −2 accuracy penalty is almost always worth it against opponents with Total DR 10+.

> **Strategic Note:** Against heavily armoured opponents, Called Shots to arms or legs transform from optional tactics into essential strategies. The accuracy penalty is outweighed by bypassing the majority of the armour's protection.

---

## 6. Critical Hits and DR

A critical hit (Nat 20 on the attack roll):
- **Automatically lands** — bypasses Evasion entirely.
- **Halves the DR** of the targeted body part (round down) before applying.
- If the attack was also a Called Shot, the saving throw against the effect is made at **disadvantage**.

> **Example:** Critical hit to the torso of a heavy armour wearer. Normal Torso DR 6 → halved to **3**. A 20-damage crit deals: 20 − 3 = **17 damage**.

---

## 7. Layered Armour

Lighter armour may be worn beneath heavier armour, stacking DR values:

- **Effect:** DR values stack at each location.
- **Penalty:** Each additional layer reduces movement speed by **5 ft**.
- **Limit:** Maximum **2 layers** per location (one per armour type). No two layers of the same type.
- **Proficiency:** You may wear one piece of non-proficient armour as long as it is not a torso piece — it will not impose non-proficiency penalties in that case.

> **Example:** Gambeson (Light, Torso DR 2) under a Breastplate (Medium, Torso DR 4) = **Torso DR 6**, but −5 ft movement.

---

## 8. Magical and Natural DR

| Source | Effect |
|---|---|
| **Magic-enhanced armour (+1, +2, +3)** | Adds bonus to DR at all covered locations. |
| **Resistant armour** | +2 DR against a chosen damage type (elemental, etc.). |
| **Dragonborn natural resistance** | +2 DR against their breath weapon's element. |
| **Tough feat** | +1 DR to all body parts. |
| **Elemental Runes** | +2 DR against a chosen element. |
| **Reinforced Seams (light armour upgrade)** | +1 to Evasion rolls. |
| **Hardened Plates (medium/heavy upgrade)** | +1 DR to the torso location. |
| **Spiked Harness** | Deal 1d4 piercing damage to any creature that grapples or strikes you unarmed. |

---

## 9. Class and Subclass DR Features

Key class interactions with the DR system. See individual class entries for full mechanics:

| Class / Feature | DR Interaction |
|---|---|
| **Barbarian (Unarmoured)** | DR = Constitution modifier (minimum 1). Doubled while Raging. |
| **Monk (Unarmoured)** | DR = ½ Dexterity modifier. May spend a Technique Point for +2 DR to all locations until the start of their next turn. |
| **Druid — Circle of the Moon** | Beast forms gain DR = ½ level. Using Wild Shape as an action grants +1 DR to all locations. |
| **Rogue** | Sneak Attack damage **ignores DR entirely**. |
| **Ranger — Colossus Slayer** | Reduces target DR by 2 on attacks against injured creatures. |
| **Ranger — Hunter's Mark** | Reduces target DR by the Ranger's **Wisdom modifier** for the duration of the mark. |
| **Fighter — Battle Master** | Precision manoeuvre bypasses ½ of the target's DR on one attack. |
| **Paladin** | Aura of Protection grants DR equal to Charisma modifier to nearby allies. |
| **Magus** | Arcane Guard grants scaling DR while concentrating on a spell. |
| **Investigator** | Studied targets have their effective DR reduced (see class entry for amount). |
| **Shaman** | Totemic Wards grant elemental DR to allies in range. |
| **Witch** | High-level Hex of Frailty reduces enemy DR. |

---

## 10. DR Reduction — Stacking and Minimum

Multiple effects can reduce a target's DR simultaneously — Weapon Skills, class features, Hunter's Mark, and Shatter Guard may all apply at once. Regardless of how many effects stack:

**DR cannot be reduced below 0 at any location.**

A target with DR 3 subject to Shatter Guard (−4 DR) has an effective DR of **0**, not −1. This prevents DR reduction from becoming bonus damage.

---

## 11. Optional Rules

### Armour Degradation (Optional)

Introduce durability tracking for gritty campaigns:

Each time a character takes more than **10 damage** to a body part after DR is applied, roll a d6. On a **1**, that piece of armour's DR is reduced by 1 until repaired by a skilled artisan. Magical armour is only damaged on a 1 caused by a magical weapon or a critical hit.

### Weight Threshold Fatigue (Optional)

If total armour DR across all body parts exceeds your **Strength score**, gain 1 level of Exhaustion at the start of combat unless you pass a **Constitution save (DC 10 + number of armour layers)**. This check applies only if wearing armour you are not proficient in, or if total DR exceeds your Strength score.

---

## 12. Quick Reference

| Armour | DR (Torso/Head/Arms/Legs) | Total DR | Defence Mode | Key Perk |
|---|---|---|---|---|
| **Light** | 2/1/1/1 | 5 | Dodge (Dex) | 5 ft shift on dodge; +2 MS on clean dodge |
| **Medium** | 4/2/2/2 | 10 | Dodge (Dex) | No MS loss on tie |
| **Heavy** | 6/3/3/3 | 15 | Brace (Str) only | Highest total DR |
| **Small Shield** | +2 arm | — | Dodge or Brace | +2 Evasion bonus |
| **Standard Shield** | +3 arm | — | Dodge or Brace | Shield reactions |
| **Great Shield** | +5 all (via Block) | — | Brace only | Massive block DR; no Dodge |

---

## 13. Combat Flow with DR

1. Attack declared (standard or Called Shot).
2. Defender chooses **Dodge**, **Brace**, or **Take the Hit** (forego Evasion for a Tactical Reaction).
3. Compare rolls → clean defence, glancing blow, or full hit.
4. If damage is dealt: roll damage. On a glancing blow, halve first, then apply DR.
5. Apply DR of the targeted body part (minimum 0).
6. On a critical hit: halve DR before applying.
7. Subtract final damage from HP. Check injury thresholds.
