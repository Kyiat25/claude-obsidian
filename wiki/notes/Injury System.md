---
type: concept
title: "Injury System"
address: c-000079
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
status: mature
mocs:
  - "[[FEARS MOC]]"
complexity: advanced
domain: fears
related:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Combat Flow]]"
  - "[[Momentum]]"
  - "[[Bloodied and Bruised]]"
  - "[[Called Shot]]"
  - "[[Paladin]]"
  - "[[Bard]]"
  - "[[Apothecary]]"
  - "[[Cleric]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Bloodied Breaking Points Rally]]"
  - ".raw/Injury System.md"
confidence: high
---

# Injury System

> Editorial note: no separate source page was created for this ingest — `.raw/Injury System.md` deepens exactly this page's existing content (same pattern as the last five DCS-companion ingests), so it was merged in rather than duplicated.

"A duel is not just the measure of life and death — it is the story written on flesh." Escalating consequences for combat damage: injuries mark thresholds of trauma rather than HP just ticking down. **Applies to all creatures — PCs, NPCs, and monsters alike** (a correction of this page's prior framing, which implied PC-only scope; monsters use the full Injury System *and* the separate enemy-only [[Bloodied and Bruised]] overlay, not one or the other). Confirmed with zero drift against [[Dynamic Combat System (DCS)]]'s summary — the seventh consecutive DCS-companion source to check out this way.

## Thresholds

| Threshold | HP | Table | Momentum |
|---|---|---|---|
| Wounded | 75% | Minor Injury (d8) | −1 MS |
| **Staggered** | 50% | Major Injury (d8) | Reset to 0 |
| Critical | 25% | Critical Injury (d8) | −2 MS |
| Fatal | 0% | Death saving throws | Reset to 0 |

**Terminology note**: this system calls the 50% threshold "Staggered," deliberately distinct from "Bloodied" — [[Bloodied and Bruised]] is the separate enemy-only overlay that also triggers at 50% HP. Per [[Combat Flow]]'s sequencing: Staggered (Injury table) resolves first, then Bloodied effects trigger second, for enemies only.

Crossing more than one threshold in a single blow rolls on each relevant table. Each threshold triggers only the first time it's crossed — healing back above and dropping below again doesn't re-trigger it.

## Mitigation — chosen blind, before rolling

| Option | Cost | Effect |
|---|---|---|
| Constitution Save (DC = 10 + damage÷10, min 12) | none | Success reduces the injury one tier (Critical→Major→Minor→Ignored); failure suffers it in full |
| Grit Save | 1 level Exhaustion | Automatically ignores the injury entirely, including its Momentum effect — no roll |

Exhaustion reduces all future [[Momentum]] gains by 1/level (minimum 0) — the cost that keeps Grit Save from being strictly better.

## Injury tables

### Minor (Wounded, 75% HP) — −1 MS

| d8 | Injury | Effect |
|---|---|---|
| 1 | Shallow Cut | −1 additional Momentum (−2 MS total) |
| 2 | Bruised Ribs | −5 ft speed until healed |
| 3 | Rattled | Disadvantage on next Evasion roll |
| 4 | Blood in the Eye | Disadvantage on next attack roll |
| 5 | Jarred Nerves | Disadvantage on next saving throw |
| 6 | Stagger | Lose Reaction until start of next turn |
| 7 | Pulled Muscle | Disadvantage on Athletics/Acrobatics until healed |
| 8 | Close Call | No additional effect |

### Major (Staggered, 50% HP) — Momentum resets to 0

| d8 | Injury | Effect |
|---|---|---|
| 1 | Broken Bone | Disadvantage on attacks using one limb (1d4: 1-2 dominant arm, 3-4 leg) |
| 2 | Bleeding Wound | 1d4 ongoing damage/turn until stabilised (DC 10 Medicine or magic) |
| 3 | Exposed | Enemies get Advantage on [[Called Shot]]s against you until healed |
| 4 | Fractured Grip | Drop held weapon/shield; Disadvantage on STR checks until healed |
| 5 | Dazed | Lose Bonus Action until start of next turn |
| 6 | Shattered Focus | Disadvantage on Concentration and Focus saves until healed |
| 7 | Torn Muscle | Speed halved until healed |
| 8 | Winded | Disadvantage on CON saves until next Short Rest |

### Critical (25% HP) — −2 MS

| d8 | Injury | Effect |
|---|---|---|
| 1 | Crushed Chest | Disadvantage on CON saves; max HP halved until healed |
| 2 | Punctured Lung | Speed halved; DC 15 CON save/turn or gain Exhaustion |
| 3 | Severe Bleeding | 1d6 ongoing damage/turn until healed (magic or DC 15 Medicine) |
| 4 | Broken Spine/Hip | Prone at start of each turn unless DC 15 CON save succeeds |
| 5 | Lost Limb (Minor) | An arm, hand, or leg disabled until magically restored |
| 6 | Senseless | DC 15 CON save/turn or lose Action that turn |
| 7 | Unsteady | All attacks against you have Advantage until start of next turn |
| 8 | Trauma Shock | Momentum resets to −2 and cannot be gained until healed |

## Healing

| Tier | Method |
|---|---|
| Minor | Short Rest or any magical healing |
| Major | Long Rest or 2nd-level+ healing magic |
| Critical | Greater Restoration, Regenerate, or 1+ week downtime (GM discretion) |
| Lost Limb | Regenerate or equivalent |
| Ongoing bleed (1d4) | DC 10 Medicine action, or magic |
| Ongoing bleed (1d6) | DC 15 Medicine action, or 2nd-level+ magic |

## DCS integration

- [[Evasion]]/[[Damage Reduction]] are the real injury prevention layer — a successful Dodge/Brace means no damage and no threshold at all; DR and glancing blows can be the difference between crossing a threshold or not.
- [[Called Shot]]: if a shot drives a target through a threshold, both systems trigger and stack — Called Shot save resolves first, then the injury roll.
- **Barbarian**: while Raging, Major Injury drops MS to −1 instead of resetting (Resilient Flow); at level 11, MS can't drop below 0 while Raging regardless of injury.
- **Monk**: no exception here — Monks lose Momentum at thresholds normally; Balanced Rhythm only covers missed attacks, not injuries.

## Class features (new)

**Paladin — Sanctified Intercession**: downgrades an ally's Critical Injury roll to a Major Injury roll.

**Bard — Soothing Performance** (from `.raw/Bard.md`): a 10-minute uninterrupted performance during a short rest downgrades one conscious, listening ally's Injury by a tier (Major→Minor, Minor→healed entirely). Once per long rest. A different tier band than Paladin's Sanctified Intercession (Critical→Major) — the two don't overlap, so no contradiction, just two classes independently softening different parts of the injury track.

**Apothecary — Trauma Specialist** (Field Medic discipline, from `.raw/Apothecary.md`): the first class hook that **removes** an Injury outright rather than downgrading a tier — 1 minute + 2 Reagent Points for a Minor Injury, 10 minutes + 4 RP for Major, 1 hour + 8 RP for Critical. Time- and resource-gated rather than free, unlike Paladin's and Bard's reaction/performance-based downgrades. Confirms the class's own framing as "best equipped to treat, prevent, and downgrade Injuries mechanically."

**Cleric — Mercy of the Divine** (10th level, reaction, once/long rest, from `.raw/Cleric.md`): downgrades an ally's incoming Injury by a tier — Major becomes Minor, and uniquely, Minor is **negated entirely** (damage still taken, no Injury effect at all). The fourth distinct class hook, and the only one that can prevent a Minor Injury from ever applying rather than just softening an existing one.

**Investigator — Foreseen Harm** (11th level, once/short rest, from `.raw/Investigator.md`): downgrades a Major Injury to Minor. The fifth distinct class hook, and the first framed as **self-only** — every prior hook (Paladin, Bard, Apothecary, Cleric) protects an ally; this one protects only the Investigator.

**Monk — Serene Focus** (13th level, once/short rest, from `.raw/Monk.md`): suffering a Minor Injury, ignore all its effects until the end of the next long rest — the injury itself remains and must still be healed normally. The sixth distinct class hook, and the first that **suppresses effects without downgrading a tier or removing the injury outright** — a third distinct shape alongside the downgrade (Paladin/Bard/Cleric) and removal (Apothecary) approaches.

**Rogue — Nerve-Steeled** (9th level, from `.raw/Rogue.md`): the first Minor Injury suffered between long rests doesn't impose its normal [[Momentum]] penalty — other Injury effects still apply. The seventh distinct class hook, and the first that targets specifically an Injury's *Momentum* consequence rather than its narrative/mechanical effects, a universal-condition cousin of [[Barbarian]]'s Rage-gated Resilient Flow.

**Sangromancer — Blood Resilience and Safe Bloodletting** (3rd and 13th level, from `.raw/Sangromancer.md`): two more new hook shapes. Blood Resilience grants advantage on the *next Injury saving throw* after sacrificing HP for blood magic — improving the roll rather than altering the outcome, the eighth distinct hook and the first framed as a save bonus. Safe Bloodletting (13th) makes **self-inflicted** HP loss from the Sangromancer's own class features unable to cause a Critical Injury (external sources still can) — the ninth hook, and the first that's a self-only immunity to a specific injury tier rather than a downgrade, removal, or effect-suppression.

**Tattooist — Inked Resilience** (15th level, from `.raw/Tattooist.md`): sacrifice an active tattoo (inactive until the next long rest) to downgrade an Injury a tier (Critical→Major, Major→Minor, Minor→negated) **and** ignore any Momentum penalty from it. The tenth distinct hook, and the first to combine a tier-downgrade (Paladin/Bard/Cleric's shape) with a Momentum-penalty-ignore (Rogue's Nerve-Steeled shape) in a single feature rather than doing just one.

**Warden — Glacial Endurance** (Stoic Chill Prime Element Resonance, from `.raw/Warden.md`): when damage would cross an HP threshold and trigger an Injury save, expend a Power Die as a free action to reduce that damage by the die result — potentially preventing the threshold crossing (and the Injury save) entirely. The eleventh distinct hook, and the first that acts *before* an Injury save is even triggered rather than modifying an Injury's severity, save, or Momentum consequence after the fact.

**Warlock — Eldritch Resilience (Injury Downgrade)** (15th level, from `.raw/Warlock.md`): once per day, a Major Injury downgrades to Minor — the standard tier-downgrade shape already seen on Paladin/Bard/Cleric, the twelfth distinct hook overall. Notable only for reusing the "Eldritch Resilience" name already used for an unrelated 9th-level feature suite in the same document — a naming quirk, not a new mechanic shape.

## Monster injuries

Monsters follow the same thresholds and tables as PCs — only the narrative description changes to fit the creature, not the mechanics, except where noted:

- **Legendary monsters**: a Critical Injury (25%) may trigger one immediate Legendary Action (a "Legendary Surge") before injury penalties apply.
- **Aberrations**: resist mental/sensory results (ignore Rattled/Blood in the Eye); Lost Limb may sprout new limbs instead of disabling; Critical Injuries can force nearby mortals into Sanity saves via psychic backlash.
- **Beasts**: visceral and direct effects; typically flee at Major/Critical Injuries, dropping to −2 Momentum immediately.
- **Celestials**: injuries manifest as radiant dimming (Lost Limb → wings burn, flight halved; Senseless → aura falters, allies lose buffs); almost never fight at Critical Momentum unless narratively cornered.
- **Constructs**: immune to bleeding/fatigue/shock; Bleeding Wound → Fluid Leak (Disadvantage on STR saves), Lost Limb → Arm Shears Off, Severe Bleeding → Cracked Core (Disadvantage on Concentration if magic-powered).
- **Dragons**: battlefield-altering — Lost Limb → grounded wing; Trauma Shock → enraged wingbeat knocks all within 30 ft prone before Momentum resets; Crushed Chest → breath weapon recharge worsens by one die step.
- **Giants**: Broken Bone/Fractured Grip → drop weapon and smash the ground; Dazed → stagger into allies (collateral damage); Critical Injuries often enrage them into +1 MS even while suffering the penalty.
- **Undead**: ignore bleeding/lung/shock results and Pulled Muscle entirely; Lost Limb keeps fighting (severed limb twitches nearby); every injury instead increases their Aura of Dread, forcing nearby mortals into Focus/Sanity saves.
- **Plants and Oozes**: Bleeding Wound → Sap Flow/Acid Leak (hazardous terrain); Broken Spine → splits into two smaller creatures; Senseless → Dormant (incapacitated until struck again).

## See also

- [[Dynamic Combat System (DCS)]]
- [[Combat Flow]]
- [[Momentum]]
- [[Evasion]]
- [[Damage Reduction]]
- [[Called Shot]]
- [[Bloodied and Bruised]]
- [[Paladin]]
- [[Bard]]
- [[Apothecary]]
- [[Cleric]]
- [[Investigator]]
- [[Monk]]
- [[Rogue]]
- [[Sangromancer]]
- [[Tattooist]]
- [[Warden]]
- [[Warlock]]
- [[FEARS MOC]]
