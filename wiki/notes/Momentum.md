---
type: concept
title: "Momentum"
address: c-000077
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
aliases:
  - "MS"
related:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[FEARS Combat System]]"
  - "[[Evasion]]"
  - "[[Tactical Reactions]]"
  - "[[Breaking Points]]"
  - "[[Enemy Rally]]"
  - "[[Damage Reduction]]"
  - "[[Injury System]]"
  - "[[Sanity & Focus in Combat]]"
  - "[[Bard]]"
  - "[[Apothecary]]"
  - "[[Bender]]"
  - "[[Binder]]"
  - "[[Cleric]]"
  - "[[Druid]]"
  - "[[Fighter]]"
  - "[[Inventor]]"
  - "[[Investigator]]"
  - "[[Magus]]"
  - "[[Monk]]"
  - "[[Paladin]]"
  - "[[Ranger]]"
  - "[[Reaper]]"
  - "[[Rogue]]"
  - "[[Sangromancer]]"
  - "[[Shaman]]"
  - "[[Sorcerer]]"
  - "[[Tattooist]]"
  - "[[Warden]]"
  - "[[Warlock]]"
  - "[[Witch]]"
  - "[[Wizard]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Bloodied Breaking Points Rally]]"
  - ".raw/Momentum.md"
confidence: high
---

# Momentum

> Editorial note: no separate source page was created for this ingest — `.raw/Momentum.md` deepens exactly this page's existing content (same pattern as [[Combat Flow]], [[Called Shot]], and [[Damage Reduction]]'s ingests), so it was merged in rather than duplicated.

The combat-rhythm tracker [[FEARS Combat System]] first mentioned (as a bare "-2 to +3 range") back in the very first FEARS ingest. A **state bonus**, not a spendable pool — constantly rising and falling, not fixed like HP. Starts at 0 each combat, resets to 0 after. Every table below is confirmed identical to the original [[Dynamic Combat System (DCS)]] summary — the fifth consecutive DCS-companion source to check out with zero drift (after [[Combat Flow]], [[Bloodied Breaking Points Rally]], [[Called Shot]], [[Damage Reduction]]).

## Gaining

Successful attack (+1), Critical Hit (+2), successful [[Called Shot]] (+2), clean Dodge/Brace (+1, or +2 in light armor), successful Counterattack/Disarm via [[Tactical Reactions]] (+2), successful Shield Bash/Deflect (+1), dropping an enemy to 0 HP (+1), healing an ally (+1), GM-discretion tactical edge (+1). Class-specific ally-support source (from [[Bard]]): granting Bardic Inspiration gives the recipient +1 to +3 Momentum immediately (scaling with the Bard's Performance check result), independent of anything the recipient does with the die itself. Second class-specific source (from [[Apothecary]]): Chemical Rush grants the Apothecary +1 Momentum for healing a bloodied ally or applying a beneficial concoction in combat — a self-directed support trigger, distinct from Bard's ally-directed one. Third and fourth class-specific sources (from [[Bender]]'s Elemental Flow): casting a damaging/condition Bender spell grants +1 Momentum, and landing an elemental strike as part of the Attack action grants +1 Momentum once per turn — the first class with two independent self-directed Momentum triggers rather than one. **First total absence** (from [[Binder]]): the Binder's per-class deep-dive never mentions Momentum once, despite its own Bleed Points resource having near-identical gain triggers (taking damage, dropping an enemy to 0/Bloodied). Flagged as an observation, not a contradiction — Bleed Points appears to be a fully separate resource track running in parallel to Momentum rather than replacing or feeding it. **Proposed fix, not in source**: discussed with the user — a "Momentum Surge" trigger (successfully Push the Bind → +1 Momentum) drafted on [[Binder]]'s page as a design suggestion, not confirmed class content. Fifth class-specific source (from [[Cleric]]'s Divine Rhythm): healing an ally past a major HP threshold grants +1 Momentum — an ally-support trigger structurally close to Bard's Inspirational Momentum but tied to healing thresholds specifically. Sixth and seventh class-specific sources (from [[Druid]]): Primal Shift (10th level) grants +1 Momentum immediately on entering Beast Form during an active encounter, and Nature's Remembrance grants +1 Momentum once per turn for casting a spell or using Wild Shape while in a Nature-Remembered area — the second class (after Bender) with two independent self-directed triggers. Eighth class-specific source (from [[Fighter]]'s Action Surge): using Action Surge grants +1 Momentum **immediately, regardless of whether the resulting attacks land** — the least-conditional gain trigger of any class, since every other class's gain sources depend on a roll succeeding.

Ninth class-specific source (from [[Investigator]]'s Exploit Momentum, 3rd level): designating a creature as Quarry, or successfully exploiting a weakness, grants +1 Momentum — an analytical trigger tied to the class's core identity rather than raw aggression. Tenth class-specific source (from [[Magus]]'s Spellstrike, 1st level): delivering a cantrip through a weapon attack counts as a weapon attack for all Momentum purposes and generates +1 Momentum (+2 on a critical hit). Eleventh and twelfth class-specific sources (from [[Ranger]]): a successful hit against the Ranger's Favoured Enemy grants +2 Momentum instead of the normal +1 (reinforced, not replaced, by Precision Kill's crit version at 11th level); separately, Claimed Ground's Territorial Momentum grants +1 Momentum on the first hit each turn while within a Claimed Ground location, on top of normal gain. Thirteenth class-specific source (from [[Reaper]]'s Soul Shield reaction): reducing incoming damage to exactly 0 grants +1 Momentum (and refunds the token spent) — a defensive-reaction trigger, not an attack-based one. Fourteenth class-specific source (from [[Rogue]]'s Sneak Attack, Cunning Flow): landing a Sneak Attack grants +2 Momentum instead of the normal +1, once per turn — the same "+2 instead of +1" shape as [[Ranger]]'s Favoured Enemy. Fifteenth class-specific source (from [[Rogue]]'s Shadow Slip reaction): a creature missing the Rogue within 5 ft grants +1 Momentum — a new shape, self-benefit from an *opponent's* failure rather than a penalty inflicted on the opponent. Sixteenth class-specific source (from [[Sangromancer]]'s Sanguine Momentum, 15th level): casting a spell that costs 8+ HP via Sanguine Casting grants +1 Momentum — the first Momentum-gain trigger gated by the *amount* of a resource spent rather than the action taken. Seventeenth and eighteenth class-specific sources (from [[Shaman]]): Totemic Rhythm (1st level) grants +1 Momentum on activating, summoning, or moving a Spirit Totem; Spirit-Touched Ground (7th level) separately grants +1 Momentum (once/turn) on entering or starting a turn in a Spirit-Touched area — a second class (after [[Druid]]/[[Bender]]) with two independent self-directed triggers. Nineteenth and twentieth class-specific sources (from [[Sorcerer]]): Draconic Bloodline's Draconic Momentum grants +1 Momentum on dealing ancestor-element spell damage; Wild Magic's Avatar of Chaos grants +3 Momentum at the start of every turn for its 10-minute duration, the largest flat per-turn Momentum grant of any class feature seen so far. [[Sorcerer]] is also the first class whose source supplies a **default Momentum trigger table for any unbuilt origin** — a design-level meta-rule (Elemental/Draconic → damage with a spell; Shadow/Necrotic → reducing a creature to 0 HP with a spell; Wild/Chaos → a Surge; Divine/Radiant → healing with a spell; Psionic/Aberrant → a creature failing a save against the Sorcerer's spell), rather than a single fixed mechanic. Twenty-first and twenty-second class-specific sources (from [[Tattooist]]): Etched Flow (1st level) grants +1 Momentum on activating a tattoo, applying Bad Ink, or using Art Loan in combat; Bad Ink separately grants the wielder +1 Momentum when it triggers on a hit — a second independent trigger distinct from Etched Flow's application-time trigger.

**[[Wizard]]'s Arcane Flow** (Magic Sense, 5th level): casting a spell that successfully imposes a condition or reduces an enemy to 0 HP grants +1 Momentum — the final class-specific gain source in this cluster's per-class deep-dive pass. Note: the feature's own text mis-names the trigger as "casting a Bender spell," an apparent copy-paste artifact from another class's document — the class's own flavor introduction states the trigger generically, and that generic wording is treated as authoritative (see [[Wizard]] for the full discrepancy write-up).

**[[Witch]]'s Hex Momentum** (11th level): once per turn, a hexed creature (via Witches Mark or Hex Contagion) failing a save against a Witch effect grants +1 Momentum — a control-caster's version of the "enemy fails a save" trigger shape already seen on other classes, tied specifically to the Witch's hex-spreading identity.

**[[Warlock]]'s Darkness Veil** (6th-level Class Reaction): when a ranged attack against the Warlock or an ally misses because of the reaction's imposed disadvantage, the *target* (self or ally) gains +1 Momentum — a new shape where the beneficiary of a defensive reaction gets the Momentum, not the Warlock casting it and not a penalty inflicted on the attacker.

**[[Warden]] — the richest single class for Momentum interactions this session**: four innate triggers plus one more per Discipline (only one Discipline is ever active per character, so a given Warden has five triggers total, but the source documents all four Discipline variants). Innate: Natural Awareness (winning Round 1 initiative, +1), Elemental Presence (activating it in Round 1, +1), Elemental Rebuke (target fails its CON save, +1), Elemental Absorption (reducing damage to exactly 0, +1). Discipline-specific: Guardian's Protection Style (protected ally takes no damage, +1), Fanatic's Pugilist (two unarmed strikes both hit in a turn, +1), Sentinel's Territorial Claim (a creature fails the Claimed Zone save, +1), Apex Predator's Predator's Mark (reducing Prey to 0 HP, +2). No other class this session ties Momentum this thoroughly into its core class chassis rather than a single subclass or a couple of features.

**Documentation quirk, not a contradiction** (from [[Reaper]]): the class's Heroic Boon "Death's Momentum" (10th level, opt-in) grants +1 Momentum once/round on harvesting a soul — but the same source's own systems-integration section restates this almost verbatim as "Momentum of the Grave (9th level)," with a different name, a different level, and phrased as automatic rather than an opt-in choice. Treated as an internal inconsistency in the source (the Heroic Boon framing embedded in the level-by-level writeup is likely authoritative), not two separate mechanics.

## Enemy Momentum suppression (growing pattern)

Three classes now inflict a Momentum penalty on an enemy rather than modifying the character's own score: [[Cleric]]'s Ward of Faith reduces an *ally's* Momentum loss (not enemy-facing), [[Bard]]'s Cutting Rhythm reduces an *enemy's* Momentum gain by 1, and now [[Inventor]]'s Infusion Burst (7th level Class Reaction): if a blocked/reduced attack would have dropped the target below their Bloodied threshold, **the attacker loses 1 Momentum outright** — the first confirmed case of an enemy losing Momentum flatly, rather than merely having a gain reduced.

## Reset exception (from Rogue)

**[[Rogue]]'s Slippery Escape** (Cunning Action, 2nd level) is a confirmed, named exception to the core reset rule below: using Cunning Action to Dash, Disengage, or Hide does **not** reset Momentum to 0, despite the general rule that a Disengage/Withdraw action always does. Standing up from prone also doesn't cost Momentum under this feature. Unlike the DCS-summary-vs-deep-dive contradictions seen on other classes, this is a deliberate class-specific carve-out, not a conflicting data point — the base reset rule still applies to every class without this feature.

## Resetting (confirmed pattern, not a one-off)

**[[Druid]]'s Wild Shape**: entering Beast Form during combat **resets** Momentum to +1 — neither a gain nor a loss, and the first confirmed case of a class ability resetting Momentum to a specific nonzero value rather than modifying it by a fixed amount or zeroing it out (the existing zero-reset triggers are all penalty-driven — Fatal/0 HP, Major Injury/Staggered). Natural attacks in Beast Form count as weapon attacks for Momentum purposes. **[[Fighter]]'s Rush of Adrenaline** confirms this is a real, repeating pattern rather than a one-off: spending hit dice to heal below half HP also resets Momentum to +1 (unless already higher) — the second class with this exact reset-to-+1 shape, on an entirely unrelated trigger (self-healing under pressure, vs. transforming). Worth watching whether "+1" specifically, rather than some other value, becomes the confirmed universal reset target.

## Losing

Missed attack (−1), critical hit received (−2), forgoing Evasion (−1), non-medium-armor glancing blow (−1), Nat 1 (−2), receiving a condition (−1), failed save (−1), Prone/Restrained (−1), Minor Injury/Wounded (−1), **Major Injury/Staggered resets to 0**, Critical Injury (−2), **Fatal/0 HP resets to 0**. Threshold losses only trigger the first time a threshold is *crossed* — healing back past it doesn't re-trigger the loss.

**Class mitigation** (from [[Cleric]]'s Ward of Faith): expending a Channel Divinity use as a reaction reduces an ally's Momentum *loss* by 1 (min 0) — the first class-specific interaction on the losing side rather than the gaining side. **Confirmed word-for-word on [[Paladin]]** — Paladin's own Ward of Faith (also via Channel Divinity) is identical text, the first case of an entire named ability shared verbatim between two classes rather than just a similar shape. **Second instance, self-directed** (from [[Magus]]'s Adaptive Mind, 11th level reaction): identical shape (reduce Momentum loss from an attack by 1, min 0), but protects the Magus *themself* rather than an ally within range — the first self-directed version of this exact mechanic.

**Paladin exception** (Righteous Stability, 9th level): beginning a turn at +2 or higher Momentum, the first attack that misses the Paladin before their next turn doesn't reduce Momentum — subsequent misses and other losses apply normally. A conditional, once-per-turn cousin of [[Monk]]'s unconditional Balanced Rhythm.

**Barbarian exception** (Rage-dependent, scales with level, not a permanent baseline):
- Level 1 (Resilient Flow): Major Injury drops MS to −1 instead of resetting, while Raging.
- Level 1 (Fury Threshold): starting a turn Raging at −2 or lower grants +2 MS.
- **Level 7 (Primal Defiance, new)**: as a reaction when about to lose Momentum from damage, reduce the loss by 1 (min 0) and gain +1 MS — usable PB times per short rest.
- Level 11 (Enhanced Rage): while Raging, MS cannot drop below 0 from any source.
- Outside Rage, losses are normal.

**Monk exception**: ignores the −1 MS penalty from missed attacks (Nat 1's −2 still applies) — reflects "Balanced Rhythm": a miss is redirected, not a break in rhythm, but a landed blow still disrupts it. Confirmed with zero drift by [[Monk]]'s own per-class deep-dive. That same deep-dive also ties Technique Points to Momentum via **Ki Flow** (regain 1 TP at turn-start when at +3 Momentum, or +2 at 7th level) — see [[Weapon Mastery]] for the open question of whether this is the same mechanic as "Flow Strike" or a separate one.

## Effects by score

| Score | PC Effect |
|---|---|
| +3 (Combat Advantage) | +3 Attack & Evasion; first attack each turn has Advantage; enemies have Disadvantage on Called Shots against you |
| +2 | +2 Attack & Evasion; +5 ft movement |
| +1 | +1 Attack & Evasion |
| 0 (Neutral) | none |
| −1 | −1 Attack & Evasion |
| −2 (Struggling) | −2 Attack & Evasion; critical threat range against you expands to 19-20 |

## Epic expansion (new)

PCs can exceed the standard +3 cap at high level, to stay competitive against legendary monsters:

| Score | PC Effect (level 17+) |
|---|---|
| +4 (Overwhelming), level 17+ | +4 Attack & Evasion; first hit each round adds +PB damage; 1 extra Reaction/round |
| +5 (Dominating), level 20+ | +5 Attack & Evasion; one **Heroic Surge** per combat (extra Action) |

Crit-range expansion and aura effects at high Momentum are **monster-only** — PCs at +5 get the Heroic Surge but not those monster-specific properties (see Monster Scaling below).

## Resets

Short Rest/scene break, Disengage/Withdraw action, knocked unconscious/stabilised, reduced to 0 HP, or GM discretion (parley, battlefield pause) all reset Momentum to 0. Explicitly **not** a reset: rolling Evasion when attacked — only the deliberate Disengage/Withdraw *action* triggers it. A character can only prevent/soften a reset once per combat.

## Exhaustion (new)

Exhaustion reduces Momentum **gains**, not the cap or current score: each level cuts all gains by 1 (minimum 0 per event); at 3+ levels, no Momentum can be gained at all until Exhaustion drops. Interacts with [[Injury System]]'s Grit Save, which grants a level of Exhaustion in exchange for ignoring an injury.

## Optional: Swing Guardrail

A creature can't gain or lose more than ±2 Momentum per turn (before injury resets) — recommended for groups new to DCS. **Epic variant**: expands to ±3/turn at level 17+.

## Monster scaling (new)

| Monster type | Range | Character |
|---|---|---|
| Beasts / Humanoids | −2 to +2 | Instinct and grit; predictable rhythm |
| Fiends, Aberrations, Monstrosities | −3 to +3 | Erratic, dangerous, unpredictable |
| Giants, Dragons, Celestials | −5 to +5 | Build into overwhelming dominance |
| Undead / Constructs | rarely exceed +2 unless Legendary | Limited but unnervingly steady |

### Monster effects at high Momentum

| Tier | Monster-only effect |
|---|---|
| +4 (Overwhelming) | Extra Reaction/round; aura forces melee attackers to make a DC 15 Focus/WIS save or their first attack has Disadvantage |
| +5 (Dominating) | Crit range 19-20; first hit/round forces a STR/DEX save or the target is prone/pushed 10 ft/disarmed; aura forces a DC 18 Focus/WIS save or the attacker's Momentum is treated as 0 that turn only (not a permanent change) |

## Caster Spell Save DC floor (new)

Casters never count below **−1 MS** when calculating Spell Save DCs, even at −2 Momentum — keeps casters viable under sustained attrition without fully negating the system's pressure on them.

## System interactions

[[Evasion]] and Attack rolls are both modified by MS directly. [[Damage Reduction]] only applies after a blow already connects — Momentum governs whether it connects at all. [[Called Shot]] saves get Advantage at +3 MS, Disadvantage at −2. [[Injury System]] and Momentum spiral together: injuries reset/drain Momentum, and low Momentum makes further injury more likely. Optional (from [[Sanity & Focus in Combat]]): the Momentum Synergy toggle raises max [[Focus]] by +1 per 3 Momentum, off by default.

## Enemy-morale interaction (from Bloodied Breaking Points Rally)

Enemy-only: a failed [[Breaking Points]] check locks the enemy at **−2 Momentum minimum** until a successful [[Enemy Rally]] resets it — a floor mechanic distinct from the normal −2 range. A Nat 20 Rally resets allies to 0 and grants Advantage on their next attack; a Nat 1 Rally locks them at −2 and forfeits further Rally attempts that combat.

## Background tie-in (unimplemented design intent)

[[FEARS Advanced Backgrounds]]'s system-level notes call for high-rank backgrounds to provide "Momentum Generation" from a fearsome or inspirational reputation. No individual background page specifies a Momentum interaction mechanically — this is a stated design goal at the system level, not yet implemented per background.

## Design history

[[The Dynamic Combat System (Excluded Draft)|An earlier, explicitly excluded draft]] of the combat system used a **−3 to +3** range (7 states, including an "Overwhelmed" −3 tier: first attack disadvantage, attacks against you have advantage) and different class-specific rules for Barbarian/Monk/Rogue/Fighter. None of that is reflected above — this page documents only the current, confirmed range and rules. Kept for provenance, not as an alternate ruleset.

## See also

- [[Dynamic Combat System (DCS)]]
- [[FEARS Combat System]]
- [[Evasion]]
- [[Damage Reduction]]
- [[Called Shot]]
- [[Tactical Reactions]]
- [[Injury System]]
- [[Breaking Points]]
- [[Enemy Rally]]
- [[The Dynamic Combat System (Excluded Draft)]]
- [[Druid]]
- [[Fighter]]
- [[Inventor]]
- [[Investigator]]
- [[Magus]]
- [[Monk]]
- [[Paladin]]
- [[Ranger]]
- [[Reaper]]
- [[Rogue]]
- [[Sangromancer]]
- [[Shaman]]
- [[Sorcerer]]
- [[Tattooist]]
- [[Warden]]
- [[Warlock]]
- [[Witch]]
- [[Wizard]]
- [[FEARS MOC]]
