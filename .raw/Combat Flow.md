# Combat Flow

> *"Know the sequence. Every moment in combat has an order. Those who understand it survive; those who don't are always a step behind."*

---

## Overview

Every attack in the DCS follows a consistent sequence. Both attacker and defender have clear decision points at each step. Understanding the order matters — particularly around when damage resolves relative to reactions.

This document is the **master sequence reference**. For full rules on each system, see the relevant document (Evasion, Damage Reduction, Called Shots, Reactions, Momentum, Injury System).

---

## The Combat Sequence

| Step | Who Acts | What Happens |
|---|---|---|
| **1. Declare Attack** | Attacker | Choose target. Declare a **Standard Attack** or **Called Shot** (specify body part). Called Shot penalties apply immediately. |
| **2. Called Shot Detection** | Automatic | *Called Shots only.* Compare the defender's **Passive Perception** to the Detection DC. No roll or action required from either party. |
| **3. Attack Roll** | Attacker | Roll `1d20 + attack bonus`. Apply Called Shot penalty if applicable. Advantage/Disadvantage applies here. |
| **4. Critical Hit Check** | — | If the attack roll is a **Nat 20**: attack automatically lands. Skip Evasion entirely. DR is halved. If also a Called Shot, the saving throw is at **disadvantage**. |
| **5. Evasion Roll** | Defender | If not a critical hit, defender chooses **Dodge** or **Brace** (based on armour). Rolls against the attack roll as the DC. Or chooses to **Take the Hit** (skip to Step 7). |
| **6. Evasion Outcome** | — | Compare rolls. Determine clean defence, glancing blow, or full hit. Apply any Momentum changes from the evasion result. |
| **7. Damage Roll** | Attacker | If the attack lands (full hit or glancing blow), roll damage. On a glancing blow, halve damage first. |
| **8. Apply DR** | Defender | Apply DR of the targeted body part (minimum 0). On a critical hit, DR is halved before applying. |
| **9. Damage Applied** | — | Subtract final damage from HP. Check for **injury thresholds**. |
| **10. Tactical Reaction** | Defender | If the defender chose to **forego Evasion** (Step 5), they declared their Tactical Reaction before the damage roll. Now execute it — resolve contested rolls, attacks, or effects as stated. |
| **11. Resolve Effects** | — | Apply Called Shot saving throws, injury table rolls, Bloodied triggers (enemies only), conditions, and any other special effects. If an enemy crossed 50% HP in Step 9: resolve the **Injury table first**, then trigger **Bloodied effects** second. |
| **12. Momentum Update** | Both | Apply all remaining Momentum changes from the exchange. |

---

## Step-by-Step Detail

### Step 1 — Declare Attack

The attacker announces their action and target. If declaring a **Called Shot**, the targeted body part must be named before any rolls are made.

**Standard Attack:** Aims at no specific location. Uses **Total DR** on a hit.
**Called Shot:** Targets a specific location. Uses only that **location's DR** on a hit, but applies a flat attack roll penalty.

| Location | Penalty |
|---|---|
| Head | −5 |
| Arms | −2 |
| Legs | −2 |
| Torso | 0 (standard) |
| Eye | −7 |
| Hand | −4 |
| Throat | −6 |
| Wing / Tail | −3 |

---

### Step 2 — Called Shot Detection (Called Shots Only)

When a Called Shot is declared, the **defender's Passive Perception** is automatically compared to the Detection DC. This is free and requires no action.

**Detection DC = 10 + Attacker's Attack Bonus − Called Shot Penalty**

More extreme penalties (e.g., Head −5) are easier to spot because the attacker must telegraph their aim more obviously.

| Result | Effect |
|---|---|
| Passive Perception ≥ DC | Defender gains **Advantage on their Evasion roll**. Knows which body part is targeted. |
| Passive Perception < DC | Defender rolls Evasion normally. Does not know the targeted location. |

---

### Step 3 — Attack Roll

**Formula:** `1d20 + attack bonus (STR or DEX modifier + Proficiency Bonus)`

- Called Shot penalty applies.
- Advantage or Disadvantage applies here (from conditions, abilities, Detection result, etc.).
- If Advantage on Evasion was granted in Step 2, the attacker's roll is still their roll — the advantage applies to the *defender's* Evasion in Step 5.

---

### Step 4 — Critical Hit Check

If the attack roll is a **natural 20:**

- The attack **automatically lands**. Evasion is skipped entirely.
- DR for the targeted body part is **halved** (round down).
- If the attack was a Called Shot, the target's saving throw against the effect is made at **disadvantage**.
- Defender loses **−2 Momentum**.
- Proceed directly to Step 7.

If the attack roll is **not** a natural 20, proceed to Step 5.

---

### Step 5 — Evasion Roll (or Take the Hit)

The defender chooses one of three options:

**Option A — Dodge (Dexterity):**
`1d20 + DEX modifier + PB`
Available to: Light armour, Medium armour, Unarmoured Defence.

**Option B — Brace (Strength):**
`1d20 + STR modifier + PB`
Available to: Heavy armour, Shield users.
*Required for:* Great shield wielders (cannot Dodge), Heavy armour wearers (cannot Dodge).

**Option C — Take the Hit (Forego Evasion):**
Skip the roll. Automatically take the full hit. Gain a **free Tactical Reaction** (resolved at Step 10, after damage).
- Loses **−1 Momentum**.
- Once per attack, per attacker, per round. A new action from the same attacker (such as Action Surge) creates a new window.

---

### Step 6 — Evasion Outcome

Compare the defender's Evasion roll to the attack roll.

| Result | Outcome | Momentum |
|---|---|---|
| **Nat 20 (Defender)** | Perfect Defence. Attack misses entirely. Free attack or action as a reaction. Light armour may shift 5 ft. | +2 MS (light armour) or +1 MS |
| **Defender > Attacker** | Clean Defence. Attack misses. No damage. Light armour may shift 5 ft. | +2 MS (light) or +1 MS |
| **Defender = Attacker** | Glancing Blow. Damage halved first, then DR applied. | No change (medium armour) or −1 MS |
| **Defender < Attacker** | Full Hit. DR applied normally. | −1 MS |

---

### Step 7 — Damage Roll

Roll damage as per the weapon, spell, or ability.

- **Glancing Blow:** Halve the damage roll *before* applying DR.
- **Standard Hit:** Roll full damage.
- **Critical Hit:** Apply any extra dice (doubled weapon dice, etc.) before DR.

---

### Step 8 — Apply DR

Apply the **DR of the targeted body part** to the damage rolled.

- **Standard Attack:** Uses **Total DR** (sum of all four locations).
- **Called Shot:** Uses only the **targeted location's DR**.
- **Critical Hit:** DR is **halved** (round down) before applying.
- **Glancing Blow:** Damage was already halved in Step 7. Apply DR to the halved result.
- **DR minimum: 0.** DR cannot reduce damage below 0, and DR itself cannot be reduced below 0 by any effect.

---

### Step 9 — Damage Applied

Subtract the final damage from the target's HP.

**Check Injury Thresholds:**
- **75% HP (Wounded):** Roll Minor Injury table. −1 Momentum.
- **50% HP (Staggered):** Roll Major Injury table. Momentum resets to 0. *Enemies only:* Bloodied effects also trigger after the injury roll (see Step 11).
- **25% HP (Critical):** Roll Critical Injury table. −2 Momentum.
- **0 HP:** Standard death saving throw rules. Momentum resets to 0.

**Injury Mitigation — Choose Before Rolling:**
Before rolling on the injury table, the player must choose one of the following. The choice is **blind** — made before seeing the result.

| Option | Cost | Effect |
|---|---|---|
| **Constitution Save** | None | DC = 10 + (damage taken ÷ 10), minimum DC 12. Success reduces injury one tier. |
| **Grit Save** | 1 level of Exhaustion | Ignore the injury entirely, including Momentum effects. Each level of Exhaustion reduces all Momentum gains by 1 (minimum 0). |

---

### Step 10 — Tactical Reaction

*Only applies if the defender chose to Take the Hit (Step 5).*

Damage has already been applied. The defender now declares and executes their Tactical Reaction.

**Available Tactical Reactions:**

| Reaction | Effect |
|---|---|
| **Counterattack** | Make a melee or ranged weapon attack against the attacker with advantage. |
| **Magic Attack** | Touch spell with advantage, or ranged spell without. Must be a cantrip if a levelled spell was already used this turn. |
| **Trap Weapon** | Contested roll to lock the attacker's weapon. |
| **Disarm** | Contested roll to knock the weapon from the attacker's hands. |
| **Shield Reaction** | Use Shield Block, Deflect, or Bash as a free action. When using Shield Block as a Tactical Reaction, declare it before damage is rolled — the sequence is: forego Evasion → declare Shield Block → roll damage with Block's +3 DR applied. |
| **Grapple Back** | Initiate a grapple immediately. |
| **Trip / Sweep** | Attacker makes a DEX save or falls prone. |
| **Tactical Retreat** | Move 5 ft without provoking opportunity attacks. |
| **Weapon Bind** | Both suffer −2 to attacks until one breaks the bind. |
| **Intimidating Glare** | Force the attacker to make a **Wisdom save (DC = 8 + PB + CHA mod)** or suffer disadvantage on their next attack and lose 1 MS. Once per encounter. |

A successful Counterattack or Disarm via this method grants **+2 Momentum** instead of +1.

---

### Step 11 — Resolve Effects

Apply any remaining effects from the exchange:

- **Called Shot saving throws** — target makes their save (at disadvantage if the attack was a crit or target is at −2 MS; with advantage if target is at +3 MS). If DR reduced a glancing blow to exactly 0, no Called Shot effect triggers.
- **Injury table and Bloodied sequencing** — if an enemy crossed 50% HP in Step 9: (a) roll the Major Injury table first and apply the result, then (b) trigger Bloodied effects (Frailty, Strength, Ability, Death Throes). Both apply. Injury is physical trauma; Bloodied is the creature's instinctive shift. Enemies only — PCs do not use Bloodied effects.
- **Weapon Skill effects** — if a Weapon Skill was also declared on the same attack, apply the second effect automatically (one save was already resolved — the other applies without a save).
- **Conditions** — apply Stunned, Prone, Blinded, Silenced, etc. as triggered.
- **Ongoing damage** — note any bleed or similar effects for future turns.

---

### Step 12 — Momentum Update

Apply any Momentum changes that weren't already resolved in earlier steps. Both attacker and defender update their Momentum scores.

**Swing Guardrail (Optional):** A creature cannot gain or lose more than ±2 MS in a single turn before injury resets.

---

## Quick Reference — Full Sequence

```
1.  Declare Attack (standard or Called Shot)
2.  Called Shot Detection (Passive Perception vs DC — automatic)
3.  Attack Roll (1d20 + bonus, apply penalties)
4.  Critical Hit? → Skip Evasion, halve DR, disadvantage on Called Shot save
5.  Evasion Roll → Dodge / Brace / Take the Hit
6.  Evasion Outcome → clean, glancing, or full hit
7.  Damage Roll (halve if glancing)
8.  Apply DR (halve DR on crit, minimum 0)
9.  Damage Applied → check injury thresholds → choose mitigation before rolling
10. Tactical Reaction (if Evasion was foregone)
11. Resolve Effects (Called Shot saves → Injury table → Bloodied → Weapon Skills → conditions)
12. Momentum Update
```

---

## Common Questions

**Q: When does the Tactical Reaction resolve relative to damage?**
When you forego Evasion, you immediately declare your Tactical Reaction — before damage is rolled. This is what allows Shield Block to modify the incoming damage. All other reactions (Counterattack, Disarm, etc.) are declared at the same moment but executed after damage resolves.

**Q: Can I use a Shield Block after choosing to Take the Hit?**
Yes. Shield Block can be declared as your Tactical Reaction in Step 10. Declare Shield Block before the damage roll in Step 7 — the sequence is: forego Evasion → declare Shield Block as Tactical Reaction → roll damage with Block's +3 DR applied → damage resolves.

**Q: Can I forego Evasion twice in one round?**
Yes, if two different attackers each attack you. Forgoing Evasion is per attack per attacker. A single attacker's multi-attack counts as the same attack sequence — you can only forego Evasion against one of their attacks unless a new action (e.g., Action Surge) creates a new window.

**Q: Does a Called Shot effect apply on a glancing blow?**
Yes, if any damage gets through DR after halving. If DR reduces the halved damage to exactly 0, no effect triggers.

**Q: When do Bloodied effects trigger relative to the Injury table?**
The Injury table rolls first. Then Bloodied effects trigger (enemies only). Both apply.

**Q: Can I use my normal reaction after using a Tactical Reaction?**
Yes. A Tactical Reaction (gained by forgoing Evasion) does not consume your normal reaction for the round.

---

## Examples

### Standard Attack — Full Sequence

A **Fighter** (medium armour, Torso DR 4) attacks an **orc** (Brace roll +2, Torso DR 0).

1. **Declare:** Standard attack, no Called Shot.
2. **Detection:** N/A.
3. **Attack Roll:** `1d20 + 6` = 17.
4. **Crit Check:** Not a Nat 20.
5. **Evasion:** Orc Braces: `1d20 + 2` = 11. Defender < Attacker → Full Hit.
6. **Outcome:** Full hit. Orc loses −1 MS.
7. **Damage:** `1d8 + 4` = 11.
8. **DR:** Orc has no armour, DR 0. 11 − 0 = **11 damage**.
9. **Applied:** Orc takes 11 HP. No threshold crossed.
10. **Tactical Reaction:** N/A (orc didn't forego Evasion).
11. **Effects:** None.
12. **Momentum:** Fighter +1 MS. Orc −1 MS.

---

### Called Shot — Full Sequence

A **Rogue** (light armour) targets the **head** of a bandit (Passive Perception 12).

1. **Declare:** Called Shot — Head (−5 penalty).
2. **Detection:** Detection DC = 10 + 6 (Rogue's attack bonus) − 5 = **DC 11**. Bandit Passive Perception 12 ≥ 11 → **Advantage on Evasion**.
3. **Attack Roll:** `1d20 + 6 − 5` = 14. (After penalty.)
4. **Crit Check:** Not a Nat 20.
5. **Evasion:** Bandit Dodges with advantage: rolls 9 and 16, takes **16**. 16 > 14 → **Clean Defence**. Attack misses.
6. **Outcome:** Miss. Rogue loses −1 MS. Bandit gains +1 MS.
7–12: No damage, no effects.

---

### Critical Hit Called Shot — Full Sequence

A **Barbarian** (greatsword) targets an **ogre's** arm (−2 penalty). Rolls a Nat 20.

1. **Declare:** Called Shot — Arms (−2 penalty).
2. **Detection:** DC = 10 + 7 − 2 = **DC 15**. Ogre Passive Perception 8 < 15 → Normal Evasion (but moot — it's a crit).
3. **Attack Roll:** Nat 20.
4. **Crit:** Attack automatically lands. Skip Evasion. Ogre Arms DR 3 → halved to **1**. Ogre loses −2 MS.
7. **Damage:** Greatsword `2d6` doubled to `4d6` + Str mod. Rolls 18. Minus DR 1 = **17 damage**.
9. **Applied:** Ogre takes 17 HP. Crosses 50% threshold.
11. **Effects:** (a) **Injury first:** Roll Major Injury table. Results in "Fractured Grip" — drops weapon. (b) **Bloodied second:** Enemy Bloodied effects trigger (Frailty, Strength, Ability, Death Throes). Ogre also makes **STR save at disadvantage** (crit) against the arm Called Shot. Fails → drops weapon (doubly confirmed by both systems).
12. **Momentum:** Barbarian +2 MS (crit) +2 MS (Called Shot + failed save) = capped at +3 by Swing Guardrail if using that optional rule.

---

### Forgoing Evasion — Full Sequence

A **Paladin** (standard shield, medium armour) forgoes Evasion against a hobgoblin (attack roll 16, damage 1d8+3).

1–4. Hobgoblin attacks. Not a crit.
5. **Take the Hit:** Paladin forgoes Evasion. Commits to a Tactical Reaction.
6. **Outcome:** Full hit. Paladin loses −1 MS.
7. **Damage:** `1d8 + 3` = 9.
8. **DR:** Medium armour Torso DR 4. 9 − 4 = **5 damage**.
9. **Applied:** Paladin takes 5 HP.
10. **Tactical Reaction:** Paladin declares Counterattack. Rolls `1d20 + 7` with advantage → hits → deals 11 damage. Paladin gains **+2 MS**.
11. **Effects:** None.
12. **Momentum:** Net: −1 (took hit) + 2 (counterattack) = **+1 MS net gain**.
