# The Injury System

> *"A duel is not just the measure of life and death — it is the story written on flesh. Every cut tells the rhythm of the fight, every scar remembers who seized the moment and who faltered."*

---

## Overview

The Injury System introduces escalating consequences for combat damage. Rather than HP simply ticking down, injuries mark thresholds of trauma that shape the fight — making combat more visceral, dynamic, and meaningful.

**This system applies to all creatures — PCs, NPCs, and monsters alike.**

> **Note on Bloodied:** The *Bloodied, Breaking Points & Rally* system is a separate overlay that applies to **enemies and monsters only**, triggering at the same 50% HP threshold. When an enemy crosses 50% HP, the Injury System resolves first, then Bloodied effects trigger. For PCs, only the Injury System applies.

---

## Thresholds

| Threshold | HP Level | Injury Table | Momentum Effect |
|---|---|---|---|
| **Wounded** | 75% HP | Minor Injury (d8) | −1 MS |
| **Staggered** | 50% HP | Major Injury (d8) | Reset to 0 |
| **Critical** | 25% HP | Critical Injury (d8) | −2 MS |
| **Fatal** | 0 HP | Death saving throws | Reset to 0 |

> **Terminology note:** This system uses the term **Staggered** for the 50% HP threshold. The *Bloodied* label belongs to the enemy-only Bloodied & Bruised system that triggers at the same point. Both systems apply to enemies at 50% HP — the Injury System (Staggered) resolves first, then Bloodied effects trigger second.

**Crossing Multiple Thresholds in One Blow:** If a single attack drops a creature through more than one threshold, roll on each relevant injury table once per threshold crossed. Multiple injuries can accumulate from a single hit.

**Each Threshold Triggers Once:** A threshold only triggers the first time it is crossed. Healing back above the threshold and falling below it again does **not** re-trigger the injury roll.

---

## Mitigation — Choose Before Rolling

When a threshold is crossed, choose a mitigation option **before** rolling on the injury table. The choice is **blind** — you commit without knowing the result.

### Option A: Constitution Save

**DC = 10 + (damage taken ÷ 10), minimum DC 12**

| Result | Effect |
|---|---|
| **Success** | Reduce injury one tier: Critical → Major, Major → Minor, Minor → Ignored |
| **Failure** | Suffer the injury rolled |

### Option B: Grit Save

Endure through sheer willpower at the cost of long-term endurance.

- Suffer **1 level of Exhaustion**.
- **Ignore the injury entirely**, including the threshold's Momentum effect.
- No roll required — this automatically succeeds.

> **Note:** Each level of Exhaustion reduces all Momentum gains by 1 (minimum 0 per event). A character who uses Grit Saves repeatedly will find their ability to build combat rhythm increasingly compromised. See the Momentum document for full details.

> **Design Intent:** The blind choice creates meaningful pressure. The CON Save is free but uncertain — you might still suffer the full injury. The Grit Save is guaranteed but costs Exhaustion, which compounds over a long fight. Experienced players will develop instincts for when each is worth it.

---

## Injury Tables

### Minor Injury Table — Wounded (75% HP)

*Roll 1d8. Momentum: −1 MS (unless Grit Save used).*

| d8 | Injury | Effect |
|---|---|---|
| 1 | **Shallow Cut** | −1 additional Momentum (total −2 MS from this threshold). |
| 2 | **Bruised Ribs** | −5 ft movement speed until healed. |
| 3 | **Rattled** | Disadvantage on your next Evasion roll. |
| 4 | **Blood in the Eye** | Disadvantage on your next attack roll. |
| 5 | **Jarred Nerves** | Disadvantage on your next saving throw. |
| 6 | **Stagger** | Lose your Reaction until the start of your next turn. |
| 7 | **Pulled Muscle** | Disadvantage on Athletics and Acrobatics until healed. |
| 8 | **Close Call** | No additional effect beyond the −1 MS threshold loss. |

---

### Major Injury Table — Staggered (50% HP)

*Roll 1d8. Momentum: Reset to 0 (unless Grit Save used).*

| d8 | Injury | Effect |
|---|---|---|
| 1 | **Broken Bone** | Disadvantage on attacks using one limb. Roll 1d4: 1–2 = dominant arm, 3–4 = leg. |
| 2 | **Bleeding Wound** | 1d4 ongoing damage at the start of each turn until stabilised (DC 10 Medicine check as an action, or magical healing). |
| 3 | **Exposed** | Enemies gain Advantage on Called Shots against you until healed. |
| 4 | **Fractured Grip** | Drop held weapon or shield; Disadvantage on Strength checks until healed. |
| 5 | **Dazed** | Lose your Bonus Action until the start of your next turn. |
| 6 | **Shattered Focus** | Disadvantage on Concentration saves and Focus saves until healed. |
| 7 | **Torn Muscle** | Speed halved until healed. |
| 8 | **Winded** | Disadvantage on Constitution saves until your next Short Rest. |

---

### Critical Injury Table — Critical (25% HP)

*Roll 1d8. Momentum: −2 MS (unless Grit Save used).*

| d8 | Injury | Effect |
|---|---|---|
| 1 | **Crushed Chest** | Disadvantage on all CON saves; maximum HP halved until healed. |
| 2 | **Punctured Lung** | Speed halved; DC 15 CON save at the start of each turn or gain 1 level of Exhaustion. |
| 3 | **Severe Bleeding** | 1d6 ongoing damage at the start of each turn until healed (magical healing or DC 15 Medicine). |
| 4 | **Broken Spine / Hip** | Knocked prone at the start of each turn unless you succeed on DC 15 CON save. |
| 5 | **Lost Limb (Minor)** | One arm, hand, or leg is disabled until magically restored. |
| 6 | **Senseless** | DC 15 CON save at the start of each turn or lose your Action for that turn. |
| 7 | **Unsteady** | All attacks against you have Advantage until the start of your next turn. |
| 8 | **Trauma Shock** | Momentum resets to −2 and cannot be gained by any means until healed. |

---

## DCS Integration

### Momentum and Injuries

| Threshold | Momentum Effect |
|---|---|
| Minor (75%) | −1 MS |
| Staggered (50%) | Reset to 0 |
| Critical (25%) | −2 MS |
| Fatal (0 HP) | Reset to 0 |

Momentum effects apply after the injury roll and any mitigation. A Grit Save bypasses both the injury result and the Momentum effect.

**Barbarian Exception:** While Raging, a Major Injury drops Momentum to −1 instead of resetting to 0 (Resilient Flow, Level 1). At Level 11, Momentum cannot drop below 0 while Raging regardless of injury. Outside Rage, Barbarians lose Momentum at thresholds as normal.

**Monk Exception:** No change to injury threshold Momentum effects — Monks lose Momentum at thresholds as normal. Their Balanced Rhythm exception only covers missed attacks.

### Evasion, DR, and Injury Prevention

The best mitigation for injuries is preventing the damage that causes them:

- A successful **Dodge or Brace** prevents the attack from landing — no damage, no threshold.
- **DR** reduces damage after a hit lands and may prevent a hit from crossing a threshold.
- A **Glancing Blow** halves damage before DR — often the difference between crossing and not crossing a threshold.

### Called Shots and Injuries

If a Called Shot drives a target through a threshold, **both systems trigger**:

1. Resolve the Called Shot saving throw first.
2. Roll on the appropriate injury table.

These stack — a Leg Shot that knocks a target prone may also trigger Torn Muscle from the injury table. The Called Shot effect and the injury effect reinforce each other.

### Class Features and Injuries

| Class / Feature | Interaction |
|---|---|
| **Paladin — Sanctified Intercession** | Downgrades an ally's Critical Injury roll to a Major Injury roll. |
| **Barbarian — Resilient Flow (Rage)** | Major Injury while Raging drops MS to −1 rather than resetting. |
| **Barbarian — Enhanced Rage (Level 11)** | MS cannot drop below 0 while Raging, even from injury thresholds. |

---

## Monster Injuries

Monsters follow the same threshold and table rules as PCs. Their nature changes how injuries **manifest narratively** — the mechanical effects still apply, but the description should fit the creature.

### Legendary Monsters

On a **Critical Injury (25% HP)**, Legendary monsters may trigger a **Legendary Surge** — one immediate Legendary Action — before the injury penalties apply. This represents the creature's fury at being brought so low.

---

### Injury Variants by Monster Type

#### Aberrations
- Resist mental or sensory effects — ignore "Rattled" or "Blood in the Eye."
- "Lost Limb" may cause new unnatural limbs to sprout rather than disabling them.
- Critical Injuries often manifest as **psychic backlash**, forcing nearby mortals to make Sanity saves.

#### Beasts
- Injuries are visceral and direct: Broken Bone = limping, halved speed; Severe Bleeding = visible blood trail.
- Beasts typically **flee** at Major or Critical Injuries, dropping Momentum to −2 immediately.

#### Celestials
- Injuries manifest as *radiant dimming* rather than physical maiming:
  - "Lost Limb" → wing feathers burn away, flight halved.
  - "Senseless" → aura falters, nearby allies lose buffs.
- Celestials almost never fight at Critical Momentum unless narratively cornered.

#### Constructs
- Immune to bleeding, fatigue, and shock. Replace with malfunctions:
  - "Bleeding Wound" → **Fluid Leak** (Disadvantage on STR saves).
  - "Lost Limb" → **Arm Shears Off** (lose weapon function or attack mode).
  - "Severe Bleeding" → **Cracked Core** (Disadvantage on Concentration if magically powered).

#### Dragons
- Injuries should feel battlefield-altering:
  - "Lost Limb" → torn wing (grounded, speed halved).
  - "Trauma Shock" → enraged wingbeat knocks all creatures within 30 ft prone before Momentum resets.
  - "Crushed Chest" → Breath Weapon recharge worsens by 1 die step (e.g. 5–6 becomes 6 only).

#### Giants
- "Broken Bone" or "Fractured Grip" means dropping their weapon and smashing the ground.
- "Dazed" may stagger them into their own allies, dealing collateral damage.
- Critical Injuries often enrage them — they gain +1 MS even as they suffer the injury penalty.

#### Undead
- Ignore bleeding, lung, and shock results entirely.
- Injuries alter form, not function:
  - "Severe Bleeding" → ignored.
  - "Lost Limb" → keeps fighting; the severed limb continues to twitch nearby.
  - "Pulled Muscle" → ignored (undead do not fatigue).
- Each injury suffered instead **increases their Aura of Dread** — nearby mortals must make Focus or Sanity saves.

#### Plants and Oozes
- Replace with destabilisation:
  - "Bleeding Wound" → **Sap Flow** or **Acid Leak** (leave hazardous terrain in their wake).
  - "Broken Spine" → **Split in Half** (becomes two smaller oozes or plant masses).
  - "Senseless" → **Dormant** (incapacitated until struck again).

---

## Healing Injuries

| Injury Tier | How to Heal |
|---|---|
| **Minor** | Short Rest or any magical healing. |
| **Major** | Long Rest or magical healing (Cure Wounds 2nd level+, Healing Word 2nd level+). |
| **Critical** | Greater Restoration, Regenerate, or equivalent. Or 1 week+ downtime recovery at GM discretion. |
| **Lost Limb** | Regenerate spell or equivalent magical restoration. |
| **Ongoing Bleed (1d4)** | DC 10 Medicine check as an action, or any magical healing. |
| **Ongoing Bleed (1d6)** | DC 15 Medicine check as an action, or magical healing of 2nd level+. |

---

## Quick Reference

**When a threshold is crossed:**

1. **Choose mitigation BEFORE rolling** — CON Save (free, uncertain) or Grit Save (1 Exhaustion, guaranteed ignore; remember each Exhaustion level reduces Momentum gains by 1).
2. **Roll on the appropriate injury table** (unless Grit Save was used).
3. **Apply the threshold's Momentum effect** (unless Grit Save was used).
4. **For enemies at 50% HP (Staggered threshold):** Injury table resolves first, then Bloodied effects trigger.
