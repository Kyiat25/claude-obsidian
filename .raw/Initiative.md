# Initiative & Combat Flow

> *"Battle is rhythm. The first strike is chaos, but soon the clash settles into a tide. The side that seizes the rhythm rules the flow."*

---

## Overview

In standard D&D, initiative is rolled once at the start of combat and stays fixed for the entire fight. A rogue who rolls poorly goes last every round regardless of how the battle unfolds — a system that feels increasingly disconnected as the fight develops its own momentum and story.

**Initiative & Combat Flow** reimagines turn order as a living consequence of the battle itself. The opening round is chaotic — assassins strike from shadow, arrows fly, spells detonate. But as combat settles, the **side that has seized rhythm** presses its advantage. A devastating critical hit swings initiative your way. A leader's rallying cry steadies wavering allies. A tactical retreat resets the flow before the enemy can capitalise.

This system integrates directly with the **Dynamic Combat System**, making initiative a consequence of **Momentum**, **Focus**, and battlefield morale. It transforms combat from a static turn queue into a living tide of ebb and flow.

---

## 1. Round 1 — Traditional Order

Everyone rolls `1d20 + Dexterity modifier` as in standard 5E.

Combat proceeds in rolled order for the **first round only**.

Surprise rounds function normally.

> **Design intent:** Round 1 preserves the explosive opening that assassins, ambushers, and fast strikers are built around. Scouts who position before the fight, rogues who trigger a surprise round, and spellcasters who open with a devastating area spell all need this moment to matter. Round 1 is chaos and setup — Round 2 onward is where rhythm takes over.

---

## 2. Round 2+ — Side Initiative

At the start of each round from Round 2 onward, initiative is determined by the flow of the fight rather than a fixed roll.

### Step 1 — Momentum Check

Calculate each side's **average Momentum Score (MS)** across all active combatants.

The side with the **higher average** acts first this round.

### Step 2 — Tiebreaker: Leadership Roll

If both sides have equal averages:

- Each side's leader (the highest-CR creature for enemies, or the PC with the highest Focus modifier) rolls `1d20 + Focus modifier`.
- The higher result wins initiative for that round.

### Step 3 — Group Action

The winning side takes **all of their turns** in any order they choose, then the other side acts.

This means your party can coordinate freely within a round — decide who goes first, who sets up flanks, who finishes what the previous ally started.

> **Routing guardrail:** Creatures that have routed or fled (those who failed a Breaking Point check or chose to flee) are **removed from Momentum calculations immediately**. Their often-negative Momentum does not weigh down their side's average, preventing a single rout from spiralling into a permanent lockout.

---

## 3. Seize the Moment

> *"When the tide turns against you, it takes more than steel to hold the line — it takes a voice that cuts through chaos and a will that refuses to break."*

### Overview

**Seize the Moment** is a universal reaction available to all player characters that allows them to fight for initiative when the battle's rhythm has shifted against them. It mirrors the enemy Rally mechanic but places control — and risk — directly in the players' hands.

Only **one PC** may attempt Seize the Moment per round. If multiple players want to try, they must declare simultaneously and agree among themselves who attempts it. This preserves the drama of the moment and prevents the attempt from becoming a routine opening action.

---

### The Mechanics

**Type:** Reaction  
**Trigger:** At the start of Round 2+, before initiative for that round is determined  
**Range:** 60 feet — you must be able to see or hear your allies  
**Cost:** Consumes your reaction for the round (no opportunity attacks, Shield spell, or other reactions)  
**Frequency:** Once per round

**Check:** `1d20 + Focus modifier`

**DC = 10 + your Proficiency Bonus + the number of allies currently at negative Momentum**

The DC scales with how badly the party is faring. When everything is going well, this is a reliable gamble. When half the party is struggling at −1 or −2 Momentum, the check becomes genuinely hard — exactly when you need it most.

| Level | PB | 0 Allies Negative | 1 Ally Negative | 2 Allies Negative | 3+ Allies Negative |
|---|---|---|---|---|---|
| 1–4 | +2 | DC 12 | DC 13 | DC 14 | DC 15+ |
| 5–8 | +3 | DC 13 | DC 14 | DC 15 | DC 16+ |
| 9–12 | +4 | DC 14 | DC 15 | DC 16 | DC 17+ |
| 13–16 | +5 | DC 15 | DC 16 | DC 17 | DC 18+ |
| 17–20 | +6 | DC 16 | DC 17 | DC 18 | DC 19+ |

---

### Outcomes

| Result | Effect |
|---|---|
| **Success** | Your side acts first this round, regardless of average Momentum. You gain +1 MS. All allies within 60 ft add +1 to their first attack roll this round. |
| **Failure** | You lose 2 Momentum (to the standard minimum of −2). Your side acts second this round. You have Disadvantage on your first attack this round. |
| **Natural 1** | You and all allies within 60 ft lose −2 Momentum (to the standard minimum of −2). Your side acts second. The first enemy to act this round gains Advantage on their first attack against you. |
| **Natural 20** | Your side acts first. You and all allies within 60 ft reset to 0 Momentum. All allies within range gain Advantage on their first attack this round. The first enemy to act has Disadvantage on their first attack. |

> **Momentum minimum:** Seize the Moment cannot push any character's Momentum below the standard floor of −2. A character already at −2 who would lose further Momentum from a failed attempt stays at −2 — they are already at the bottom of the scale, and the attempt simply fails to help them.

> **Swing Guardrail interaction:** If your table uses the optional Swing Guardrail (±2 MS per turn before injury resets), the Momentum changes from Seize the Moment apply at the initiative step rather than during a character's action turn, and are not subject to the per-turn cap. This represents a moment of collective morale shift rather than an individual combat action.

---

### DCS Integration

**Momentum:** Seize the Moment directly manipulates Side Initiative by overriding the average Momentum comparison. Failure compounds Momentum loss — critical in a system where Momentum drives both attack and Evasion. A failed attempt at a desperate moment can accelerate the collapse it was meant to prevent.

**Breaking Points and Rally:** Seize the Moment mirrors the enemy Auto Rally Attempt that triggers when a leader becomes Bloodied. Used proactively before Breaking Point checks fire, a successful Seize the Moment into a crushing first strike can eliminate the threat that would have forced a morale check entirely.

**Focus as Leadership:** The roll uses Focus modifier rather than Charisma. This is deliberate — the battle cry of a tactically brilliant Investigator or a disciplined Monk counts as much as the booming voice of a Paladin. Mental discipline under pressure is what leadership in FEARS measures.

---

### Class Hooks

| Class | Interaction |
|---|---|
| **Paladin** | High Focus investment and auras make Paladins natural leaders for this roll; a successful attempt reinforces their party-anchor role. |
| **Bard** | Jack of All Trades adds half Proficiency Bonus to the Focus check; Bardic Inspiration can help allies capitalise on the first-attack bonus. |
| **Investigator** | High Focus builds and battlefield-reading abilities make timing this attempt a strength of the class. |
| **Warlock** | Focus-based; meaningful choice between Seize the Moment and holding the reaction for other features. |
| **Fighter / Barbarian** | Lower Focus means higher risk — but when it succeeds, the reversal feels earned and dramatic. |
| **Rogue** | Typically saves reactions for Uncanny Dodge or Sneak Attack windows; attempting Seize the Moment is a genuine sacrifice. |
| **Monk** | Gambles the reaction against Deflect Missiles or Patient Defense; high risk at low Focus, potent when it lands. |
| **Ranger / Druid** | Moderate Focus; effective pack leaders at mid-levels when the party is still building its Focus investment. |

---

### Optional Variants

**Bloodied Desperation:** If you are Bloodied (at or below 50% HP) when using Seize the Moment, add +2 to your roll — desperation sharpens the voice. However, increase the Momentum loss on a failure to the standard floor (−2) applied to all allies within range rather than just yourself. The moment is more dramatic in both directions.

**Legendary Heroism (Level 17+):** Once per long rest, you may use Seize the Moment even if you have already used your reaction this round. This represents the kind of heroic presence that transcends ordinary action economy at the highest levels of play.

---

### Examples

#### Level 3 party versus an Owlbear

A Fighter and Cleric are both at −1 Momentum after a rough opening round. The Paladin (Focus +3) calls out across the clearing.

- **DC:** 10 + 2 (PB) + 2 (two allies at negative Momentum) = **DC 14**
- **Roll:** `1d20 + 3` = 15 — **Success**
- **Result:** The party acts first. The Paladin gains +1 MS. The Rogue opens with a Sneak Attack from flank, and the battle rhythm swings decisively.

---

#### Level 10 party versus an Aboleth

The Wizard, Warlock, and Ranger are all at −2 Momentum after failed saves against the Aboleth's psychic attacks. The Barbarian (Focus +1, Bloodied) makes a desperate attempt.

- **DC:** 10 + 4 (PB) + 3 (three allies at negative Momentum) = **DC 17**
- **Bloodied bonus:** +2 to roll
- **Roll:** `1d20 + 1 + 2` = 16 — **Failure**
- **Result:** The Barbarian drops to −2 Momentum (already the floor — no further loss). The party acts second. The Barbarian has Disadvantage on their first attack. The gamble failed, but the floor held.

---

#### Level 18 party versus an Ancient Red Dragon

Three of six party members are at negative Momentum after the Dragon's breath weapon. The Bard (Focus +5, Jack of All Trades adds +3) burns their Legendary Heroism to attempt this despite already having used their reaction.

- **DC:** 10 + 6 (PB) + 3 (three allies negative) = **DC 19**
- **Roll:** `1d20 + 5 + 3` = 24 — **Success**
- **Result:** The party seizes initiative from a Dragon at +3 Momentum. Everyone resets to 0 or better. The Fighter's Action Surge opens before the Dragon's legendary actions can fire.

---

## 4. Special Cases

**Legendary Creatures:** Once per combat, a Legendary creature may declare that it acts first regardless of average Momentum. This represents the overwhelming presence of a being whose will bends the flow of battle to its own rhythm.

**Morale Collapse:** If all remaining members of a side have failed Breaking Point checks, that side automatically acts second each round until a successful Rally resets at least one combatant's Momentum to 0 or above.

**Enemy Auto-Rally:** When an enemy leader becomes Bloodied, they must immediately attempt a Rally check (see the Bloodied, Breaking Points & Rally document). A successful auto-Rally resets ally Momentum, which directly affects the following round's initiative comparison.

---

## 5. DCS Integration Summary

| System | Initiative Interaction |
|---|---|
| **Momentum** | Average MS determines Side Initiative from Round 2 onward |
| **Seize the Moment** | Allows PCs to override the Momentum comparison with a Focus check |
| **Routing Guardrail** | Routed creatures are removed from average Momentum calculations |
| **Breaking Points** | Enemy routs reduce enemy average Momentum; improving PC initiative odds |
| **Enemy Rally** | Successful Rally restores enemy Momentum; may swing initiative next round |
| **Injury System** | Major Injuries reset Momentum to 0; Critical Injuries drain −2 MS; both affect initiative calculation |
| **Called Shots** | Crippling an enemy leader (throat, arm) reduces their Focus for Leadership rolls |
| **Legendary Creatures** | May act first once per combat regardless of Momentum |

---

## 6. Quick Reference

| Step | What Happens |
|---|---|
| **Round 1** | All creatures roll `1d20 + DEX mod`. Act in rolled order. |
| **Round 2+** | Compare each side's average Momentum Score. Higher average acts first. |
| **Tie** | Each side's leader rolls `1d20 + Focus mod`. Higher result wins. |
| **Seize the Moment** | One PC may use their reaction to attempt `1d20 + Focus mod` vs DC (10 + PB + allies at negative MS). |
| **Routed creatures** | Excluded from average Momentum calculations. |
| **Legendary creatures** | May declare they act first once per combat, regardless of Momentum. |
| **After a Rally** | If enemy Rally succeeds, enemy Momentum resets may swing the next round's initiative comparison. |

---

## 7. Monster Hooks

**Dragons and Giants:** At high Momentum (+4/+5), their side almost always acts first unless the party can outmanoeuvre them with Called Shots that drain their Momentum or knock their average down.

**Undead and Constructs:** Immune to morale mechanics. Initiative shifts only through raw Momentum — they cannot Rally, cannot be broken, and grind forward at whatever rhythm they've built.

**Fiends:** If a leader dies, infighting may cause internal Momentum penalties; two Fiends competing for dominance may cancel each other's Momentum gains for a round at GM discretion.

**Celestials:** Almost always succeed Rally attempts, keeping their average Momentum high and their initiative priority stable. They are difficult to dislodge from the first-action position.
