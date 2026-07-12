# Bloodied, Breaking Points & Rally

> *"The roar of a bloodied warlord can still the trembling hands of an army — or shatter them if the cry falters."*

---

## Overview

**This is an enemy and monster system.** These rules apply to NPCs, monsters, and adversaries the party faces. PCs do not use this system. This asymmetry is intentional — it gives players tactical options to break enemy morale while maintaining PC agency and avoiding forced retreats.

For PCs, the only system that applies at 50% HP is the **Injury System** (Major Injury table via the Staggered threshold + Momentum reset to 0). The Bloodied system described here does not apply to them.

---

### Why This System Exists

Combat in FEARS is not just attrition. When an orc chieftain is brought low, do their troops fight harder out of desperation — or does doubt creep in? When half the goblin squad lies dead, do they hold formation or break? When a bandit captain roars defiance despite grievous wounds, does it steel their spines or reveal a weakness the PCs can exploit?

This system makes those moments matter mechanically. It transforms battles from HP attrition into psychological warfare where killing the right target at the right moment can shatter an entire force. It gives players tactical options beyond "deal damage until enemies die," makes enemy Focus and Sanity scores combat-relevant, and ensures that enemy leaders become high-value targets.

---

### The Three Pillars

**Bloodied & Bruised** — At 50% HP, enemies reveal their desperation. Frailties expose weaknesses. Strengths grant resilience. Abilities trigger once-per-combat moves. Death Throes promise explosive finales. Survival instinct overrides tactics.

**Breaking Points** — When enemy leaders die or casualties mount, surviving allies face Sanity-based morale tests. Success means they fight on despite fear. Failure means rout, panic, or surrender.

**Rally** — Enemy leaders can attempt Focus-based checks to restore their troops' courage. Successful rallies reset Momentum and inspire forces. Failed rallies demoralise further and create openings for the players.

---

## Sequencing at 50% HP

When an enemy crosses the 50% HP threshold, two systems trigger in order:

1. **Injury System first** — Roll on the Major Injury table (the Staggered threshold). Apply the result and Momentum reset to 0.
2. **Bloodied effects second** — All four Bloodied & Bruised effects (Frailty, Strength, Ability, Death Throes) activate immediately after.

Both systems apply. They are not alternatives — Injury represents physical trauma; Bloodied represents the psychological and instinctive shift of a creature fighting for survival.

---

## System 1: Bloodied & Bruised (Enemies)

### When Enemies Become Bloodied

An enemy becomes **Bloodied** at **50% HP or below**. This is the moment where survival instinct overrides tactics, where desperation fuels both strength and weakness, where the creature's true nature is revealed under pressure. Players can see this threshold coming and plan around it.

### Bloodied Effects

When an enemy becomes Bloodied, they immediately gain **all four** of the following effects:

| Effect | Description |
|---|---|
| **Frailty** | A tactical weakness is exposed (e.g., −2 Evasion, Disadvantage on saves, vulnerable to a damage type) |
| **Strength** | A desperation resilience emerges (e.g., +2 to damage, resistance to a damage type, temporary HP) |
| **Ability** | A once-per-combat triggered move activates (special attack, buff, debuff, or escape ability) |
| **Death Throes** | An explosive finale that triggers on death, rewarding careful positioning (area damage, curse, transformation, etc.) |

> **Design Note:** Effects should match creature type and narrative context. A cornered wolf gains Pack Tactics (Strength) but exposes its wounded flank (−2 Evasion, Frailty). A dying demon explodes in hellfire (Death Throes). A bloodied knight gains Advantage on attacks (Strength) but suffers Disadvantage on Evasion (Frailty).

**Player Tactical Options:**
- Force enemies Bloodied early to trigger their Frailty before they've dealt full damage
- Prepare for Death Throes with positioning and readied actions
- Exploit the Frailty weakness once it's revealed
- Adapt tactics when the enemy's Strength manifests

---

### Auto Rally Attempt (Enemy Leaders at Bloodied Threshold)

When an **enemy leader** — or, if no leader exists, the **highest CR enemy creature** — becomes Bloodied:

1. They **must immediately** attempt a **Rally check** (no choice — this is automatic).
2. **Range:** 120 feet. All enemy allies within range are affected.
3. This represents their cry of defiance or display of desperate fury echoing across the battlefield.

**Rally Check:** `1d20 + Focus modifier` vs DC 15 (or current casualty tier DC if higher)

| Roll Result | Outcome |
|---|---|
| **Success** | Enemy allies hold; all enemy allies within range gain +1 Momentum (maximum +3) |
| **Failure** | Enemy allies lose −1 Momentum; the leader's cry rings hollow |
| **Natural 20** | All enemy allies within range reset to 0 Momentum and gain Advantage on their next attack |
| **Natural 1** | All enemy allies within range lose −2 Momentum; leader cannot Rally again this combat |

**Legendary Enemy Leaders:** May auto-succeed on any Rally check once per combat (including this Auto Rally).

**Player Tactical Options:**
- Target enemy leaders early to force weak Auto Rally attempts when Bloodied
- Kill enemy leaders when Bloodied to prevent successful rallies
- Isolate enemy leaders >120 ft from their troops so Auto Rally affects no one
- Disrupt enemy leader Focus before the Bloodied threshold

---

## System 2: Breaking Points (Enemy Morale)

### What Triggers Breaking Points

Breaking Points occur when **death or mass casualties** shake enemy resolve. This is not fear of injury — it is the existential crisis of watching their cause crumble, their leader fall, their comrades die around them.

| Trigger | Effect |
|---|---|
| **Enemy Leader Dies** | All enemy allies roll Breaking Point at **+2 DC penalty** |
| **Highest CR Enemy Dies** (if no designated leader) | All enemy allies roll Breaking Point at **+2 DC penalty** |
| **25% Enemy Casualties** | All remaining enemy allies roll Breaking Point vs DC 15 |
| **50% Enemy Casualties** | All remaining enemy allies roll Breaking Point vs DC 20 |
| **75% Enemy Casualties** | All remaining enemy allies roll Breaking Point vs DC 25 |

**Enemy Casualties:** Count dead, unconscious, routed, or fled enemy creatures when calculating percentages.

**Player Tactical Options:**
- Kill enemy leaders to trigger the hardest Breaking Point checks
- Push casualties to 25%/50%/75% thresholds strategically
- Use area damage to cross multiple casualty thresholds rapidly
- Target low-Sanity enemies first to trigger cascading routs

---

### Breaking Point Check

**Check:** `1d20 + Sanity modifier` vs DC

| Situation | Base DC | With Leader Dead |
|---|---|---|
| 25% Casualties | 15 | DC 17 |
| 50% Casualties | 20 | DC 22 |
| 75% Casualties | 25 | DC 27 |
| Leader Bloodied (Auto Rally context) | Current casualty DC | +0 |

---

### Breaking Point Results

| Roll Result | Outcome |
|---|---|
| **Success** | Enemy fights on, but loses −1 Momentum |
| **Failure** | **Enemy Routs:** Panics, flees, or surrenders (see Monster Type Behaviours) |
| **Natural 1** | **Immediate Rout** + nearby enemy allies within 30 ft roll their next Breaking Point with Disadvantage |
| **Natural 20** | **Enemy Inspired:** Immune to Breaking Points for the rest of combat + gains +1 Momentum |

**Momentum Floor:** Failed Breaking Points lock enemy allies at **−2 Momentum minimum** until a successful enemy Rally resets them.

**Initiative Impact:** Routed enemies are removed from Side Initiative calculations.

**Player Tactical Options:**
- Force Natural 1s by targeting low-Sanity enemies near groups
- Exploit routed enemies for easy kills or let them flee
- Use routed enemies' −2 Momentum lock to dominate initiative

---

## System 3: Enemy Rally

### Normal Enemy Rally (Deliberate Action)

An enemy leader may attempt Rally as a **free action once per round** when allies fail Breaking Points or are wavering.

**Requirements:**
- Must be a designated enemy leader or highest CR enemy
- Enemy allies must be within **120 feet**
- Cannot Rally if **incapacitated**, **routing**, at **0 Focus**, or **below 0 Sanity**

**Rally Check:** `1d20 + Focus modifier` vs same DC as the failed Breaking Point

| Roll Result | Outcome |
|---|---|
| **Success** | Enemy allies reroll failed Breaking Point saves with Advantage; those who now succeed reset to 0 Momentum |
| **Failure** | Enemy allies lose −1 Momentum instead; the leader's words fall flat |
| **Natural 20** | All enemy allies within range reset to 0 Momentum + gain Advantage on their next attack + immune to next Breaking Point |
| **Natural 1** | Enemy allies locked at −2 Momentum; leader cannot Rally again this combat |

**Player Tactical Options:**
- Interrupt Rally attempts with Stun, Silence, or forced movement
- Damage enemy leaders before their Rally to lower Focus
- Force repeated Rallies by sustaining pressure — a leader who must Rally every round cannot act offensively
- Kill enemy leaders after failed Rallies when troops are demoralized

---

### Rally Limits

- **Normal Rally:** Once per round (free action)
- **Legendary auto-succeed:** Once per combat
- **Cannot Rally:** If at 0 Focus, below 0 Sanity, routing, unconscious, or dead
- **After Natural 1:** Cannot Rally again this combat

---

## DCS Integration

### Momentum Synergy

| System | Interaction |
|---|---|
| **Failed Enemy Breaking Point** | Enemies locked at −2 Momentum minimum until Rally succeeds |
| **Successful Enemy Rally** | Resets enemy Momentum to 0 or restores +1 Momentum |
| **Natural 20 Enemy Rally** | All enemy allies within range reset to 0 Momentum + Advantage on next attack |
| **Routing Enemies** | Removed from Side Initiative Momentum calculations |

Enemies at −2 Momentum are easier to hit and easier to evade. Breaking enemy morale directly impacts the combat flow mechanic, not just flavour.

### Injury System Integration

- Minor/Major/Critical Injuries on enemies **do not trigger Breaking Points** by themselves.
- **If an injury kills an enemy leader** — that death triggers Breaking Point for their troops.
- Called Shots on enemy leaders (head, throat, hand) may fast-track morale collapse by crippling the leader's ability to Rally before killing them.

**Player Tactical Options:**
- Use Called Shots to cripple enemy leaders before killing them — reduce their Focus via a throat shot, then kill for maximum Breaking Point impact
- Target wounded enemy leaders to maximise the DC of the Breaking Point check

### Focus and Sanity Integration

| Attribute | Role in This System |
|---|---|
| **Enemy Focus** | Powers Rally checks. High Focus = a leader who can stabilise their forces under pressure. |
| **Enemy Sanity** | Determines Breaking Point resistance. Low Sanity = easier to rout. |
| **Enemy Focus 0** | Cannot Rally. The leader becomes a tactical liability. |
| **Enemy Sanity 0** | Automatically fails all Breaking Points. Mentally broken — fights on only through rage or compulsion. |

**Player Tactical Options:**
- Use spells that degrade Focus or Sanity (Mind Sliver, Psychic Scream, Fear)
- Target low-Sanity enemies first to trigger cascading routs
- Disrupt enemy leader concentration to degrade Focus over time

### Class Hooks

| Class | Enemy Morale Manipulation |
|---|---|
| **Bard** | Cutting Words reduces enemy Rally checks; Vicious Mockery targets enemy Sanity |
| **Paladin** | Divine Smite on leaders to force Bloodied state; Channel Divinity to Frighten |
| **Warlock** | Eldritch Blast + Repelling Blast to isolate enemy leaders >120 ft from troops |
| **Investigator** | Study enemy leader to identify low Focus/Sanity stats before engaging |
| **Cleric** | Bane on enemy Rally checks; Turn Undead forces automatic rout on undead |

---

## Monster-Type Behaviours

| Creature Type | Rout Behaviour | Rally Traits |
|---|---|---|
| **Humanoids / Beasts** | Flee or surrender; highly reliant on leaders | Standard Rally rules; players can negotiate surrender |
| **Fiends** | Often turn on each other if their leader dies; infighting escalates | Rarely Rally; chaos creates openings |
| **Giants / Dragons** | Rarely rout; enter rage states or Death Throes phases instead | High Focus; difficult to break but devastating when broken |
| **Celestials** | Almost always succeed Rally attempts; inspire nearby allies automatically | Legendary Rally traits; requires overwhelming force |
| **Undead / Constructs** | **Immune** to Breaking Points and Rally (no morale) | N/A — cannot be broken through morale |
| **Aberrations** | Unpredictable; may attack randomly, freeze, or teleport when morale breaks | Sanity-based; erratic and unreliable |
| **Fey** | May vanish, turn invisible, or shift allegiance if morale breaks | Trickster Rally; deception-based and unreliable |

**Player Notes:**
- Do not waste time trying to break undead or construct morale — it does not exist
- Fiend infighting after a leader death can be exploited for free attacks
- Giant/Dragon rage states are predictable once triggered — prepare accordingly
- Fey may become neutral or allied if their morale breaks favourably

---

## Legendary and Epic Enemy Leaders

### Legendary Enemy Leaders

- **Auto-Rally Once Per Combat:** May choose to auto-succeed any Rally check, including the Auto Rally at Bloodied
- **Death-Defying Presence:** All enemy allies within 120 ft gain +2 to Breaking Point saves
- **Bloodied Phase:** Instead of standard Bloodied effects, enters **Legendary Phase 2** with new or enhanced abilities

**Player Tactical Options:**
- Assume a Legendary leader will succeed their first Rally — plan to force a second
- Focus fire to kill a Legendary leader in a single round if possible, denying any Rally
- Prepare for Phase 2 abilities when the Bloodied threshold approaches

### Epic-Tier Enemy Leaders (CR 17–20)

- **Expanded Momentum:** Can reach +4/+5, making Breaking Points much rarer
- **Inspiring Presence:** Leaders with Focus 18+ may Rally as a **bonus action**
- **Mental Fortitude:** Leaders with Sanity 20+ are **immune** to Breaking Points from casualties

---

## Player Tactical Summary

**Eight ways to attack enemy morale:**

1. Kill enemy leaders early — trigger Breaking Points with +2 DC penalty
2. Force enemy leaders Bloodied — make them attempt Auto Rally (which can fail)
3. Target enemy Sanity — lower modifiers with Fear, Mind Sliver, Phantasmal Force
4. Isolate enemy leaders — keep them >120 ft from troops so Rally affects no one
5. Attack enemy Focus — disrupt concentration, forcing Focus degradation in leaders
6. Kill systematically — push casualties to 25%/50%/75% thresholds
7. Create cascading routs — target low-Sanity enemies near groups to force Natural 1s
8. Interrupt enemy Rallies — stun, silence, or kill leaders during their Rally attempt

---

## Quick Reference

| Trigger | Who Rolls | Check | Success | Failure |
|---|---|---|---|---|
| **Enemy Leader Bloodied** (Auto Rally) | Enemy Leader | Focus vs DC 15+ | All allies +1 MS | All allies −1 MS |
| **Enemy Leader Dies** | All Enemy Allies | Sanity vs DC 17 | −1 MS, fight on | Rout |
| **25% Casualties** | All Enemy Allies | Sanity vs DC 15 | −1 MS, fight on | Rout |
| **50% Casualties** | All Enemy Allies | Sanity vs DC 20 | −1 MS, fight on | Rout |
| **75% Casualties** | All Enemy Allies | Sanity vs DC 25 | −1 MS, fight on | Rout |
| **Enemy Rally** (Normal) | Enemy Leader | Focus vs BP DC | Allies reroll w/Advantage | Allies −1 MS |

---

## Optional Variant: PC Breaking Points

**This variant is optional and changes the core asymmetry of the system.** By default, PCs do not use Breaking Points — this maintains player agency and prevents forced retreats. Only implement if your table wants higher stakes and is comfortable with PCs potentially being pressured to flee.

If implemented, PCs may face Breaking Point checks when:
- Party leader falls to 0 HP
- Half the party is incapacitated (unconscious, dead, or fled)
- Witnessing a catastrophic event (at GM discretion — ancient dragon arrives, city falls, etc.)

**Modified DCs for PCs:**

| Trigger | DC |
|---|---|
| Party leader down | 12 |
| 50% party incapacitated | 15 |
| Catastrophic event | 10–20 (scales with severity) |

**PC-Specific Results:**

| Roll | Outcome |
|---|---|
| **Success** | No penalty — PCs are heroes |
| **Failure** | −1 Momentum + must use next action to move away from threat OR stabilise a fallen ally |
| **Natural 1** | Frightened condition for 1 round + −2 Momentum |
| **Natural 20** | Inspired; immune to Breaking Points this combat + gain +2 Momentum |

**Key Differences from Enemy System:**
- PCs **never** automatically rout — player agency is preserved
- PCs choose between retreating or helping allies
- Any PC with the highest Focus score may attempt Rally (no designated leader required)
- Level 17+ PCs may auto-succeed Rally once per combat

**Recommendation:** Use enemy-only as the default. The PC variant is for tables that want a grittier, more punishing experience where even heroes can break under pressure.

---

## Examples

### Example 1: Orc Warlord Bloodied

An Orc Warlord (Leader, Focus +2) drops from 60 HP to 28 HP from a PC critical hit — crossing 50% HP.

**Sequencing:**
1. **Injury System first** — Roll Major Injury table (Staggered threshold). Result: Exposed (enemies gain Advantage on Called Shots). Warlord's Momentum resets to 0.
2. **Bloodied effects trigger:**
   - **Frailty:** −2 Evasion (exposed wounds — PCs hit more easily)
   - **Strength:** +2 damage (desperation fury — PCs take more if hit)
   - **Ability:** Battle Cry — all orc allies gain Advantage on their next attack
   - **Death Throes:** Explodes in 10 ft radius for 2d6 on death — PCs should reposition

3. **Auto Rally:** Warlord rolls `1d20 + 2` = 14 vs DC 15 → **Fails**. All orc allies within 120 ft lose −1 Momentum.

PCs recognise the turning point. The warlord is visibly wounded and his troops are shaken.

---

### Example 2: Enemy Leader Death Triggers Rout

The party kills the bandit captain. 8 bandits remain (no other high-CR enemies).

**Breaking Point triggered:**
- All 8 bandits roll Sanity saves
- DC = 15 + 2 (leader death) = **DC 17**
- Average bandit Sanity modifier: +0

**Results:**
- 3 bandits succeed (fight on at −1 Momentum — defending desperately)
- 4 bandits fail (rout — flee toward the cave entrance)
- 1 bandit rolls Nat 1 (immediate rout + drops weapon, sprints away in panic; bandits within 30 ft roll next Breaking Point with Disadvantage)

Only 3 bandits remain engaged and demoralised. Combat is effectively decided.

---

### Example 3: Successful Enemy Rally Holds the Line

10 goblins + 1 Hobgoblin Captain (Leader, Focus +3). PCs kill 3 goblins (30% casualties).

**25% threshold crossed:**
- All 7 remaining goblins roll Sanity vs DC 15
- 4 succeed (−1 MS, fight on)
- 3 fail (begin routing — fleeing toward a ladder)

**Captain Attempts Rally:**
- Free action. Rolls `1d20 + 3` = 18 vs DC 15 → **Success**
- 3 routing goblins reroll Breaking Point with Advantage — all 3 succeed
- All 7 goblins reset to 0 Momentum

The Captain's command has steadied the line. PCs recognise they need to eliminate the Captain next.
