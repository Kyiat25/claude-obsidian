# Evasion — Dynamic Combat Defence

> *"Defence is not a wall — it is a choice, a rhythm, a stance. Some slip away; others plant their feet. Both may live."*

---

## 1. Core Principle

Evasion replaces AC. Whenever you are attacked, you choose **how you defend**:

- **Dodge (Dexterity):** Avoid the blow through speed and awareness.
- **Brace (Strength):** Plant your feet and absorb it through armour and stance.
- **Take the Hit:** Deliberately fail your Evasion to gain a free Tactical Reaction.

Your armour type determines which modes are available to you. Then you roll against the attacker's strike.

---

## 2. The Roll

**Attack Roll (attacker):** `1d20 + attack bonus`

**Defence Roll (defender):**

| Mode | Formula | Proficiency Applies When... |
|---|---|---|
| **Dodge** | `1d20 + Dex mod + PB` | Proficient in light armour, medium armour, shields, or has Unarmoured Defence |
| **Brace** | `1d20 + Str mod + PB` | Proficient in heavy armour or shields |

Momentum score and situational modifiers apply to the roll after the base is calculated.

> Heavy armour wearers **must** use Brace — they cannot Dodge.
> Great shield wielders **must** use Brace — they cannot Dodge.

---

## 3. Outcomes

| Result | Effect |
|---|---|
| **Defender Nat 20** | **Perfect Defence.** Attack misses entirely. Gain one free attack or action as a reaction. Light armour wearers may also shift 5 ft without provoking opportunity attacks. |
| **Defender > Attacker** | **Clean Defence.** Attack misses; no damage. Light armour wearers may shift 5 ft without provoking opportunity attacks. |
| **Defender = Attacker** | **Glancing Blow.** Damage is halved, then apply DR. Medium armour wearers do not lose Momentum on a tie. |
| **Defender < Attacker** | **Full Hit.** Apply DR normally. |
| **Attacker Nat 20** | **Critical Hit.** Always lands, bypasses Evasion entirely. DR for the targeted body part is halved. If also a Called Shot, the saving throw is made at disadvantage. |

---

## 4. Momentum Interaction

Evasion outcomes generate or cost Momentum, reflecting how the flow of battle shifts with each exchange.

| Defensive Result | Momentum Change |
|---|---|
| Perfect Defence (Nat 20 Defender) | +2 MS (light armour) or +1 MS (any other armour) + free reaction |
| Clean Dodge or Brace (any armour) | +1 MS |
| Clean Dodge in **light armour** | **+2 MS** |
| Glancing Blow in **medium armour** | No Momentum change |
| Glancing Blow (light or heavy armour) | −1 MS |
| Full Hit (any armour) | −1 MS |
| Critical Hit received | −2 MS |

> **Why light armour gets +2 MS on a clean dodge:** A successful Dodge in light armour represents precise, fluid movement — slipping an attack entirely through skill and timing rather than simply absorbing it. This is the mark of a combatant fully in rhythm, and the system rewards it accordingly.

---

## 5. Armour Identity

Each armour type defines a distinct playstyle and defence philosophy:

| Armour | DR (Torso/Head/Arms/Legs) | Defence Mode | Special |
|---|---|---|---|
| **Light** | 2/1/1/1 | Dodge (Dex) | +2 MS on clean dodge. Shift 5 ft on any successful dodge without provoking. |
| **Medium** | 4/2/2/2 | Dodge (Dex) | No Momentum loss on a tie. Reliable soak with no reposition perk. |
| **Heavy** | 6/3/3/3 | Brace (Str) only | Highest DR. No dodge-step. Anchors the line. |

**Shields** add DR to the arm location and grant access to Shield Reactions. See Section 9.

---

## 6. Area of Effect (AoE)

When affected by an AoE (Fireball, dragon breath, cone attacks):

- Roll **Evasion vs. the spell or ability DC**.

| Result | Effect |
|---|---|
| **Nat 20** | No damage. Light armour wearers may shift 5 ft. |
| **Success** | No damage. |
| **Tie** | Half damage, then apply DR. |
| **Failure** | Full damage, then apply DR. |

> AoE uses the same armour identity rules — light armour wearers can reposition on a Nat 20, medium armour wearers take no Momentum hit on a tie.

---

## 7. Forgoing Evasion — Tactical Reactions

You may choose **not to roll Evasion** and deliberately take the hit. This is a high-risk tactical option:

- You automatically take the **full hit** (DR still applies).
- You gain **1 free Tactical Reaction** this exchange (does not consume your normal reaction for the round).
- You lose **−1 Momentum**.
- You may forego Evasion **once per attack, per attacker**, per round. Each enemy's attack is its own opportunity — you cannot forego against the same attacker's second hit in a multi-attack sequence unless it comes from a new action (such as Action Surge, which creates a new window).
- **Damage resolves first**, then you declare and execute your Tactical Reaction.

> See the **DCS Core** document for the full list of available Tactical Reactions (Counterattack, Disarm, Grapple Back, Shield Reaction, Weapon Bind, etc.) and the Momentum reward for a successful Counterattack or Disarm.

---

## 8. Conditions and Modifiers

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

## 9. Shields and Evasion

Shields interact differently with Evasion depending on their type:

| Shield Type | DR Bonus | Evasion Bonus | Compatible Defence Mode |
|---|---|---|---|
| **Small Shield** | +2 DR (arm location) | +2 to Evasion rolls | Dodge or Brace |
| **Standard Shield** | +3 DR (arm location) | None | Dodge or Brace |
| **Great Shield** | +5 DR (all locations via Block) | None | **Brace only** — cannot Dodge |

> A character wielding a great shield cannot make Dodge Evasion rolls. They must Brace. The great shield's DR bonus applies to all locations when used in a Block reaction, not just the arm.

Shield Reactions (Block, Deflect, Bash) are available to any shield wielder and do not require forgoing Evasion to use — they are triggered as reactions in response to attacks. See the **DCS Core** document for full Shield Reaction rules.

---

## 10. Critical Hits and Evasion

- A **Nat 20 on the attack roll** automatically lands and **bypasses Evasion entirely** — no Evasion roll is made.
- DR for the targeted body part is **halved** before applying.
- If the attack was also a Called Shot, the target's saving throw against the effect is made **at disadvantage**.
- The defender suffers **−2 Momentum** from a critical hit received.

---

## 11. Class Hooks

Key class interactions with Evasion — see individual class entries for full mechanics:

| Class | Evasion Integration |
|---|---|
| **Rogue** | Tie results may be treated as a clean dodge (class feature). Sneak Attack bypasses DR entirely. |
| **Monk** | May spend a Technique Point to reroll a failed Evasion. At higher levels, may teleport and counterattack on a successful defence. Does not lose Momentum on missed attacks (but all Evasion-related losses apply normally). |
| **Ranger** | Adds Wisdom modifier to Evasion rolls against marked or favoured targets. |
| **Barbarian** | Advantage on Brace rolls while Raging. Constitution modifier adds to DR while Raging. Rage-dependent Momentum resilience — see Momentum document for full details. |
| **Paladin** | Aura grants DR equal to Charisma modifier to nearby allies. Shield Reactions integrate with Brace. |
| **Fighter** | Shield Reactions integrate with Brace. Multi-Mastery rounds via action economy. |
| **Magus** | Arcane Guard grants scaling DR while concentrating on a spell. |
| **Investigator** | Studied targets have their DR reduced, making evasion less critical against them. |
| **Shaman** | Totemic Wards grant elemental DR to nearby allies. |
| **Witch** | High-level Hex of Frailty reduces enemy DR, amplifying the value of landing hits past their Evasion. |

---

## 12. Monster Evasion

Monsters roll Evasion or have a set Defence DC, depending on how they are statted:

| Monster Type | Evasion Formula |
|---|---|
| **Humanoids** | Base + Dexterity modifier |
| **Giants** | Base + Dexterity modifier + 1 |
| **Dragons** | Base + Dexterity modifier + 3 |
| **Legendary creatures** | May auto-succeed on one Evasion roll per round (Legendary Resistance) |

---

## 13. Optional Feats — Evasion Enhancement

| Feat | Effect |
|---|---|
| **Agility Master** | +2 to all Evasion rolls. Always halve AoE damage on a failed roll. |
| **Medium Armour Evasion Expert** | Add Proficiency Bonus to Evasion rolls in medium armour. Halve non-magical AoE on failure. |
| **Heavy Armour Evasion Specialist** | Add Proficiency Bonus to Evasion rolls in heavy armour. Reduce melee damage on failed Brace rolls. |
| **Shield Mastery: Evasion Defender** | Add half Proficiency Bonus to Evasion rolls while wielding a shield. Gain a reaction after successful defences. |

---

## 14. Examples

### Example 1: Melee Attack vs Heavy Armour (Brace)

A **Fighter in heavy armour** (Torso DR 6) is attacked by an **orc with a greataxe** (1d12+3). The Fighter must use Brace.

1. **Attack Roll:** Orc rolls **18**.
2. **Brace Roll:** Fighter rolls `1d20 + 4 (Str + PB)` = **16**. Defender < Attacker → Full Hit.
3. **Damage:** Orc rolls 10 + 3 = **13 damage**. DR 6 reduces to **7 damage taken**.
4. **Momentum:** Fighter loses −1 MS. Orc gains +1 MS.

*Even though the attack lands, the plate absorbs nearly half the blow.*

---

### Example 2: Tie Result — Glancing Blow (Medium Armour)

Same scenario but the Fighter's **Brace Roll = 18** (ties the attack roll).

1. **Tie → Glancing Blow.** Damage halved first, then DR.
2. **Damage:** Orc rolls 12 + 3 = **15 damage**. Halved to **7**, then DR 6 reduces to **1 damage taken**.
3. **Momentum:** Medium armour — **no Momentum change** on a tie.

*The orc's axe bites in, but the Fighter's stance makes it little more than a scratch — and they haven't lost their rhythm.*

---

### Example 3: AoE Spell vs Light and Medium Armour

A **wizard casts Fireball** (DC 15, 8d6 fire) hitting a **Rogue in light armour** and a **Paladin in medium armour**.

1. **Rogue (Dodge, Dex+PB):** Rolls `1d20 + 7` = **17**. Success → **no damage**. May shift 5 ft. Gains +2 MS (light armour clean dodge).
2. **Paladin (Dodge, Dex+PB):** Rolls `1d20 + 2` = **15**. Tie → half damage, then DR. No Momentum change (medium armour tie).
3. **Damage:** Fireball deals 30 fire. Paladin: 30 ÷ 2 = 15, then DR 4 → **11 damage taken**.

*The rogue dives and repositions; the paladin steadies and absorbs.*

---

### Example 4: Critical Hit

A **dragon** makes a claw attack with a **Nat 20** against a Ranger in light armour (Torso DR 2).

1. **Critical Rule:** Nat 20 always lands. Evasion is bypassed entirely.
2. **DR:** Torso DR 2 → halved to **1**.
3. **Damage:** Dragon rolls 20 damage. 20 − 1 = **19 damage taken**.
4. **Momentum:** Ranger loses −2 MS from the critical hit.

*Even the most agile dodger can be mauled when fortune favours the dragon.*

---

### Example 5: Forgoing Evasion for a Counterattack

A **Barbarian** (heavy armour, DR 6 torso) is attacked by a hobgoblin (attack roll 16, damage 1d8+3).

1. **Barbarian chooses to forego Evasion** — deliberately taking the hit to counterattack.
2. **Damage resolves first:** Hobgoblin rolls 7 + 3 = 10 damage. DR 6 → **4 damage taken**.
3. **Barbarian loses −1 Momentum** for taking the hit.
4. **Barbarian declares Counterattack** as their free Tactical Reaction, rolling with advantage.
5. **Counterattack lands:** Barbarian gains **+2 Momentum** for the successful Counterattack.
6. **Net result:** −1 MS (hit) + 2 MS (counterattack) = **+1 MS net gain**. The Barbarian took 4 damage and came out ahead on rhythm.

*High-risk, high-reward. Taking a blow to deliver one is the essence of aggressive tactics.*

---

## Design Summary

- **Light Armour:** Agile — reposition on any successful dodge, +2 MS on clean dodge. Fragile if caught.
- **Medium Armour:** Steady — no reposition bonus, but no Momentum loss on ties. Reliable mid-tier defence.
- **Heavy Armour:** Tank — Brace only, best DR, no mobility perk. Holds the line.
- **Great Shield:** Brace only, massive DR, no dodge. The wall of the party.
- **Momentum:** Skilled defence builds rhythm. Light dodgers flow faster; tanks hold steady.
- **Crits always land.** Defence rolls always matter — you are never passively waiting for a static number to be beaten.
- **Class features integrate directly** into Evasion and Brace at every level.

Every attack in DCS is a **meaningful roll** — you are actively deciding how you survive, and every decision has consequence.
