---
type: entity
title: "Investigator"
address: c-000011
created: "2026-07-11"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - archetype
status: developing
mocs:
  - "[[FEARS MOC]]"
entity_type: character-class
role: "archetype"
first_mentioned: "[[Welcome to FEARS]]"
related:
  - "[[Welcome to FEARS]]"
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Narrative Identity]]"
  - "[[Class_breakdown]]"
  - "[[Rogue]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Momentum]]"
  - "[[Called Shot]]"
  - "[[Injury System]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Welcome to FEARS]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Investigator.md"
confidence: high
---

# Investigator — Truth is a Weapon

**Martial tier** (no spellcasting — a Ritualist, not a caster: no Spell Save DC anywhere in this source). "Every creature has a system. Every system has a failure point. Find it. Press it." A burst striker, skill master, and supernatural specialist — devastating against bloodied targets, increasingly resistant to (and eventually able to banish) the supernatural. Complexity self-rated HIGH (7/10) by its own per-class deep-dive — tied for the highest complexity rating seen this session.

> [!note] Naming collision with the Investigator background — flagged, not silently resolved
> [[FEARS Advanced Backgrounds]] Batch 2 introduces an "Investigator" *background* ([[Investigator (Background)]]) — a completely different mechanical concept (a 4-rank detective-agency progression track) that happens to share this class's name. The two are unrelated in the source text; a character could be this class, that background, both, or neither. Disambiguated via filename since two pages can't both be named `Investigator.md`.

> "Every creature has a system. Every system has a failure point. Find it. Press it."

## Signature abilities

- **Exploit Vulnerability** — identify and expose weaknesses
- **Research** — prepare advantages before or during combat
- **Precision Strike** — turn knowledge into devastating hits

**Gameplay style**: analytical striker, dismantling enemies piece by piece before finishing them. **Core loop**: study → identify weakness → exploit → execute. Struggles in chaotic fights with no time to observe; excels in prepared encounters and against recurring enemy types.

### Naming collision — still not resolved

[[Class_breakdown]] renamed this class's [[Welcome to FEARS]]-era signature ability from "Exploit Weakness" to "Exploit Vulnerability," giving the "Exploit Weakness" name to [[Rogue]] instead. This per-class deep-dive uses **both** names for genuinely different Investigator features (Exploit Vulnerability at 2nd level, a separate Exploit Weakness at 5th level) — so within this source they're not synonyms, but the cross-source naming collision with Rogue remains unresolved and unaddressed by this document.

## Class basics (from Investigator.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium. Weapons — simple, hand crossbows, heavy crossbows, longswords, rapiers, shortswords. Tools — one gaming set of choice. Saves — Dexterity, Intelligence. Skills — choose three from a long list including Arcana, Athletics, Crafting, Deception, History, Insight, Intimidation, Investigation, Medicine, Memory, Nature, Perception, Persuasion, Religion, Resolve, Sleight of Hand, Stealth, Streetwise.
- **Starting Equipment**: leather armour; a dagger + (a) longsword or (b) rapier; (a) heavy crossbow + 20 bolts or (b) hand crossbow + 20 bolts; (a) dungeoneer's pack or (b) priest's pack; a grimoire and component pouch.
- **Quick Build**: Intelligence highest, then Dexterity. Any lineage (Human, Gnome, Half-Elf thematic). Sage/Acolyte or an Investigation/Arcana background. Study the primary target as a bonus action before attacking; spend Exploit Vulnerability's bonus damage on the first major hit; save Finisher for the bloodied threshold.

## Level progression (1st-20th)

| Level | PB | Features | Ritual Level | Rushed Incantation Uses |
|---|---|---|---|---|
| 1 | +2 | Expertise (2), Ritualist | 1st | — |
| 2 | +2 | Myths and Legends, Rushed Incantation, Exploit Vulnerability | 1st | INT mod |
| 3 | +2 | Occult Specialisation, Exploit Momentum | 2nd | INT mod |
| 4 | +2 | Improvement | 2nd | INT mod |
| 5 | +3 | Exploit Weakness, Weapon Mastery, Forensic Called Shot | 2nd | INT mod +1 |
| 6 | +3 | Expertise (4), Occult Specialisation Feature, Forensic Upgrade | 3rd | INT mod +1 |
| 7 | +3 | Opportunistic Piety, Predictive Step (Reaction) | 3rd | INT mod +1 |
| 8 | +3 | Improvement | 3rd | INT mod +1 |
| 9 | +4 | Supernatural Resolve | 4th | INT mod +2 |
| 10 | +4 | Finisher, Heroic Boon | 4th | INT mod +2 |
| 11 | +4 | Improvement, Foreseen Harm | 4th | INT mod +2 |
| 12 | +4 | Enigma Arcane | 5th | INT mod +3 |
| 13 | +5 | Esoteric Knowledge | 5th | INT mod +3 |
| 14 | +5 | Occult Specialisation Feature, Bloodied Mastery | 6th | INT mod +3 |
| 15 | +5 | Enigma Arcane Improvement, Supernatural Resolve Improvement | 6th | INT mod +3 |
| 16 | +5 | Improvement | 6th | INT mod +3 |
| 17 | +6 | Exorcist, Finisher Scaling | 7th | INT mod +4 |
| 18 | +6 | Enigma Arcane Improvement | 7th | INT mod +4 |
| 19 | +6 | Improvement, Bonus Grimoire Spell | 7th | INT mod +4 |
| 20 | +6 | Spellbinder, Epic Boon | 8th | INT mod +4 |

## Core class features (full text)

### Expertise (1st level, and 6th)

Choose two skill proficiencies; double PB for checks with them. Two more at 6th level.

### Ritualist (1st level)

Maintains a **Grimoire** of ritual spells: starts with three 1st-level rituals, gains more per the Ritual Level column. New rituals encountered can be inscribed with time/materials. Ritual spells cast without slots (10-minute casting time).

### Myths and Legends (2nd level)

Advantage on all checks to predict Bloodied effects from Exploit Vulnerability; automatically learns a target's Frailty on completing the universal Research Bonus process. Studying an already-bloodied creature immediately reveals its Death Throes with no check.

### Rushed Incantation (2nd level)

Cast any 1-action Grimoire ritual as a **bonus action**, bypassing the normal 10-minute cast time; material components ≤100gp waived. Uses = INT mod (min 1), scaling per the table.

### Exploit Vulnerability (2nd level) — new Momentum-adjacent signature ability

Bonus action: study a creature within 30 ft, Investigation or Perception check (DC = 8 + target's DEX mod + their PB). Success: next attack against them before end of next turn deals extra damage — 2d6 at 2nd, 3d6 at 5th, 4d6 at 10th, 5d6 at 15th, 6d6 at 20th — plus one chosen effect: **Disrupt Evasion** (disadvantage on their next Evasion), **Off-Balance** (DEX save or prone/staggered, granting advantage until the Investigator's next turn), or **Expose Weak Point** (DR halved against this and the next attack it receives).

**Bloodied Analysis**: on a successful study, attempt to predict bloodied effects — DC 12+CR/2 learns one, DC 15+CR/2 learns two, DC 18+CR/2 learns all four; natural 20 learns all four exactly plus advantage on the next attack. At 6th level, study two creatures simultaneously; at 14th, ignores target immunities to Exploit Vulnerability's imposed conditions. Uses = INT mod per long rest.

### Exploit Momentum (3rd level) — new Momentum gain source

Designating a creature as Quarry, or successfully exploiting a weakness, grants **+1 Momentum**. Ninth class-specific Momentum-gain trigger in this cluster, tied to the class's core analytical identity rather than combat aggression.

### Occult Specialisation (3rd level, and 6th, 10th, 14th)

Choose: **Antiquarian, Archivist, Detective, Exterminator, Inquisitor, Medium,** or **Occultist**. Features at 3rd/6th/10th/14th — full detail not included in this source.

### Exploit Weakness (5th level) — the naming-collision ability

Once per turn on a weapon-attack hit: treat the target as vulnerable to that weapon's damage type (base damage roll only). **Bloodied Exploitation**: on a bloodied creature whose Frailty is known, choose one — **Compound Weakness** (maximise the Frailty's DR reduction or Evasion penalty), **Tactical Exposure** (allies within 60 ft learn the Frailty; next ally attack gets the Research Bonus), or **Analytical Counter** (counter one bloodied Strength effect instead of dealing bonus damage).

### Weapon Mastery (5th level)

Mastery with one simple or finesse weapon; Weapon Skill usable once per turn on a hit. DCS synergy: Weapon Skills that reduce Evasion or expose locations set up Exploit Vulnerability/Finisher.

### Forensic Called Shot (5th level) — new Called Shot access route

On a Called Shot against the designated Quarry, reduce the attack-roll penalty by PB. At 5th level (PB +3), an arm shot's normal −2 becomes a **+1 bonus** — the same shape as [[Fighter]]'s Surgical Precision and [[Cleric]]'s Judgment, but gated to the Quarry specifically rather than any target.

### Forensic Upgrade (6th level)

Exploit Vulnerability can study two creatures simultaneously; separate Bloodied Analysis checks each; Research Bonus duration applies independently per target.

### Opportunistic Piety (7th level)

Once per short rest, choose: **Banish** (*banishment*), **Miracle Healing** (heal 2× Investigator level), or **Warding** (holy symbol deals radiant damage to attackers of the warded creature).

### Supernatural Resolve (9th level, and 15th)

Resistance to necrotic and psychic damage; immune to charmed/possessed. At 15th, also resistance to radiant and thunder.

### Finisher (10th level, and 17th) — new Called Shot/Injury synergy

Once per turn on a bloodied (≤50% HP) target hit with Exploit Weakness active: **4d10 bonus damage** (6d8 at 17th) instead of Exploit Weakness's normal effect. **Death Throes Denial**: reducing a bloodied creature to 0 HP with a Called Shot to a vital area forces a CON save (DC = 8 + INT mod + PB — the seventh confirmation of the `8+PB+ability mod` formula, and the first seen on a non-caster class, extending it beyond spellcasting entirely) or its Death Throes don't trigger.

### Heroic Boon (10th level)

Choose: **Boon of the Occult Savant** (double PB for INT checks identifying creatures/spells/effects; successfully identifying a weakness grants allies +1d6 damage against that creature for 1 minute; once/short rest swap a Grimoire spell) or **Boon of Paranormal Fortitude** (resistance to psychic/necrotic; can't be frightened/charmed; allies within 10 ft can't be surprised and gain +INT mod to initiative).

### Foreseen Harm (11th level) — fifth Injury-downgrade class hook

Once per short rest, when the Investigator would suffer a Major Injury, downgrade it to Minor. The fifth distinct [[Injury System]] class hook, after Paladin's Sanctified Intercession, Bard's Soothing Performance, Apothecary's Trauma Specialist (removal), and Cleric's Mercy of the Divine — this one is self-only (protects the Investigator, not an ally), the first downgrade hook framed that way.

### Enigma Arcane (12th level, and 15th, 18th)

Grimoire gains a higher-circle ritual (level = Ritual Level, doesn't count against normal ritual total). At 15th/18th, one additional spell from any list, castable once/long rest without a ritual, using spell save DC (implying Investigator does have a spell save DC for this narrow purpose, despite no standard Spellcasting feature — not otherwise detailed in this source).

### Esoteric Knowledge (13th level)

Two more skill proficiencies; if already proficient, double PB for those checks instead.

### Bloodied Mastery (14th level)

Advantage on bloodied-effect prediction checks (stacks with Myths and Legends); once/long rest, auto-succeed and learn all four. On a bloodied target, choose two Bloodied Exploitation options instead of one; Analytical Counter extends to 2 rounds; immunity (not just advantage) to predicted Death Throes for the Investigator and allies; Death Throes Denial DC +2.

### Exorcist (17th level)

Can cast *protection from evil and good* at will.

### Bonus Grimoire Spell (19th level)

Add one spell from any list to the Grimoire regardless of ritual status, at a level castable via the Ritual Level column.

### Epic Boon (20th level)

Choose: **Boon of the Eternal Hunter** (three Investigator spells, once/long rest each without components; Exploit Weakness on a bloodied creature deals +8d10 damage replacing Finisher, ignoring all DR if Frailty is known) or **Boon of the Apex Hunter** (advantage on tracking/identifying/recalling creature info; study as a bonus action; learn an additional vulnerability/resistance/immunity on study; Finisher deals force damage +4d10; choose to trigger/suppress Death Throes; fiends/undead/aberrations at 0 HP WIS-save or banished 1d4 rounds; once/long rest, an Inevitable Strike auto-hits, ignores resistances/immunities, deals max damage, cannot be prevented by reactions).

## Last Stand (confirmed universal, 10th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Exploit Mortality | Up to 3 creatures within 60 ft: Investigation check (DC = 8+target's DEX mod+their PB) each; success grants vulnerability to all damage for 1 minute (bloodied targets auto-fail + suffer all Frailty effects at max); one attack against a chosen creature auto-crits, ignoring all DR/resistances |
| Revelation of the Veil | Allies within 60 ft gain Truesight 120 ft + advantage on all attacks/saves/checks for 1 minute; enemies within 30 ft WIS save (DC 10+PB+INT) or disadvantage on all rolls/saves for 1 minute (success: disadvantage on attacks until end of next turn) |
| Inescapable Banishment | Fiends/undead/aberrations within 60 ft CHA save (DC 10+PB+INT) or banished to their native plane for 1d4 days, no Legendary Resistance (success: 4d10 radiant + frightened 1 minute) |

Tenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

## Class Reactions (confirmed universal, 10th class — explained, not anomalous)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest — but **Predictive Step is explicitly exempted**, running on its own INT-modifier-per-long-rest budget instead.

> [!note] Ruled: explained by Bloodied Analysis's matching budget shape
> Predictive Step's "INT mod per long rest" isn't an arbitrary bypass — this class's own Bloodied Analysis feature (see above) already uses the identical budget shape. Same pattern as [[Cleric]] (mirrors Divine Intervention) and [[Druid]] (leans on Wild Shape): an existing class resource shape, not an unexplained exception.

| Reaction | Level | Trigger | Effect | Budget |
|---|---|---|---|---|
| Quick Analysis | 2nd | A visible creature makes an attack roll | Force a reroll with disadvantage; if it still hits, mark with Exploit Weakness (+PB damage on the next hit against them). Against a Studied bloodied attacker whose Strength effect is known: spend 2 uses to also apply Analytical Counter | Shared PB pool |
| Exploit Interruption | 5th | A Studied creature within 30 ft attacks, casts, or moves | Trip (STR save or movement halved/stopped), Expose (disadvantage on next attack; next ally attack has advantage), or Distract (if casting, STR save or the spell fails, slot not expended). At 11th, apply two counters to the same trigger | Shared PB pool |
| Predictive Step | 7th | The designated Quarry makes an attack roll | Impose disadvantage on that attack roll | **INT mod per long rest — not the shared pool** |

## See also

- [[Welcome to FEARS]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[Dynamic Combat System (DCS)]]
- [[FEARS Class Roster]]
- [[Rogue]]
- [[Enemy Rally]]
- [[Breaking Points]]
- [[Seize the Moment]]
- [[Momentum]]
- [[Called Shot]]
- [[Injury System]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
