---
type: entity
title: "Cleric"
address: c-000070
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
first_mentioned: "[[Narrative Identity]]"
related:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Enemy Rally]]"
  - "[[Breaking Points]]"
  - "[[Momentum]]"
  - "[[Injury System]]"
  - "[[Corruption]]"
  - "[[Called Shot]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Bloodied Breaking Points Rally]]"
  - ".raw/Cleric.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Cleric — Faith Against the Void

**Full Caster tier**. "Even in a broken world, faith still answers." Prevents failure — stops collapse before it happens. Complexity self-rated MODERATE (4/10) by its own per-class deep-dive.

> "A god's will doesn't need steel to be felt. It needs someone willing to carry it."

## Signature abilities

- **Healing**
- **Divine Power**
- **Support Auras**

**Gameplay style**: support anchor, keeping the party alive and stable. **Core loop**: support → stabilise → sustain → repeat. Struggles in purely offensive fights; excels in extended encounters where healing, Channel Divinity, and sustained casting keep the party ahead of attrition.

## Class basics (from Cleric.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium, shields. Weapons — simple. Tools — none. Saves — Wisdom, Charisma. Skills — choose two from Crafting, History, Insight, Medicine, Persuasion, Religion, Resolve.
- **Starting Equipment**: (a) mace or (b) warhammer (if proficient); (a) scale mail, (b) leather, or (c) chain mail (if proficient); (a) light crossbow + 20 bolts or (b) any simple weapon; (a) priest's pack or (b) explorer's pack; a shield and a holy symbol.
- **Quick Build**: Wisdom highest, then Constitution. Any lineage (Human, Dwarf, Aasimar thematic). Acolyte/Hermit or a Religion/Insight background. Prepare a healing/control/damage spell mix; use Channel Divinity proactively, not held in reserve until enemies are already winning.

## Level progression (1st-20th)

| Level | PB | Features | Cantrips | Rituals | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | +2 | Manifestation of Faith, Spellcasting, Divine Domain | 3 | 1 | 2 | — | — | — | — | — | — | — | — |
| 2 | +2 | Channel Divinity: Turn the Profane (1/rest), Harness Divine Power | 3 | 1 | 3 | — | — | — | — | — | — | — | — |
| 3 | +2 | Cleric Subclass | 3 | 2 | 4 | 2 | — | — | — | — | — | — | — |
| 4 | +2 | Improvement, Cantrip Versatility | 4 | 2 | 4 | 3 | — | — | — | — | — | — | — |
| 5 | +3 | Destroy the Profane (CR 1/2) | 4 | 3 | 4 | 3 | 2 | — | — | — | — | — | — |
| 6 | +3 | Channel Divinity (2/rest), Sacred Guidance, Divine Rhythm | 4 | 3 | 4 | 3 | 3 | — | — | — | — | — | — |
| 7 | +3 | Subclass Feature | 4 | 4 | 4 | 3 | 3 | 1 | — | — | — | — | — |
| 8 | +3 | Destroy the Profane (CR 1), Improvement, Blessed Strikes | 4 | 4 | 4 | 3 | 3 | 2 | — | — | — | — | — |
| 9 | +4 | Divine Intervention | 4 | 5 | 4 | 3 | 3 | 3 | 1 | — | — | — | — |
| 10 | +4 | Heroic Boon | 5 | 5 | 4 | 3 | 3 | 3 | 2 | — | — | — | — |
| 11 | +4 | Destroy the Profane (CR 2), Subclass Feature | 5 | 6 | 4 | 3 | 3 | 3 | 2 | 1 | — | — | — |
| 12 | +4 | Improvement | 5 | 6 | 4 | 3 | 3 | 3 | 2 | 1 | — | — | — |
| 13 | +5 | Channel Divinity (3/rest) | 5 | 7 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | — | — |
| 14 | +5 | Destroy the Profane (CR 3), Turn the Profane Expanded | 5 | 7 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | — | — |
| 15 | +5 | Subclass Feature, Blessed Resilience | 5 | 8 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | — |
| 16 | +5 | Improvement | 5 | 8 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | — |
| 17 | +6 | Destroy the Profane (CR 4) | 5 | 9 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | 1 |
| 18 | +6 | Channel Divinity (4/rest) | 5 | 9 | 4 | 3 | 3 | 3 | 3 | 1 | 1 | 1 | 1 |
| 19 | +6 | Improvement | 5 | 9 | 4 | 3 | 3 | 3 | 3 | 2 | 1 | 1 | 1 |
| 20 | +6 | Epic Boon | 5 | 9 | 4 | 3 | 3 | 3 | 3 | 2 | 2 | 1 | 1 |

## Core class features (full text)

### Spellcasting (1st level) — fourth confirmed caster DC formula

Wisdom is the spellcasting ability. **Spell Save DC = 8 + PB + Wisdom modifier. Spell Attack Modifier = PB + Wisdom modifier.** Fourth independent confirmation of the `8 + PB + ability mod` formula, after [[Bard]], [[Bender]], and [[Binder]]'s Binding Save DC. Prepares spells = WIS mod + Cleric level (1 minute/spell circle to reprepare); rituals castable without slots.

### Divine Domain (1st level)

Choose a Divine Domain (examples given: Life, War, Knowledge, Light, Death — "etc.," not exhaustive). Two domain-specific subclass features at 1st, plus always-prepared Domain Spells that don't count against the prepared limit.

### Manifestation of Faith (1st level)

Choose: **Manifest Might** (proficiency with heavy armour + one martial weapon; weapon hits add radiant or necrotic damage = PB) or **Manifest Miracles** (one extra cantrip from any list, treated as Divine; PB added to any Divine cantrip's damage).

### Channel Divinity (2nd level, and 6th, 13th, 18th) — new Momentum interactions

Uses per the table (1/2/3/4 per rest). **Turn the Profane**: undead/fiends within 30 ft WIS save or turned 1 minute/until damaged — the formal name behind the existing page's "Turn Undead" reference from [[Bloodied Breaking Points Rally]]; same underlying effect, more precise naming and now including fiends explicitly, not a contradiction. **Ward of Faith** (reaction via Channel Divinity): expend a use to reduce an ally's Momentum **loss** by 1 (min 0) — a new [[Momentum]] interaction on the loss side, distinct from every gain-source seen on other classes. **Judgment** (bonus action via Channel Divinity): the next weapon/spell attack this turn counts as a Called Shot with no attack-roll penalty — wasted if not attacked with before turn's end; a new [[Called Shot]] access route.

### Harness Divine Power (2nd level)

Bonus action, expend a Channel Divinity use to regain a spell slot of level ≤ half PB (rounded up) — example given: PB +3 (5th level) regains a 2nd-level slot.

### Cleric Subclass (3rd level, and 7th, 11th, 15th)

Domain features at 3rd/7th/11th/15th.

### Destroy the Profane (5th level and beyond)

Undead/fiends that fail their Turn the Profane save are destroyed outright if their CR is at or below a threshold: 1/2 at 5th, 1 at 8th, 2 at 11th, 3 at 14th, 4 at 17th.

### Sacred Guidance (6th level)

Bonus action: grant a creature within 30 ft a bonus = PB to their next attack roll or save. Uses = WIS mod/long rest.

### Divine Rhythm (6th level) — new confirmed Momentum gain source

Healing an ally past a major HP threshold (Critical→Bloodied, Bloodied→Wounded, Wounded→Full) grants +1 Momentum. A fifth class-specific Momentum-gain trigger, alongside [[Bard]], [[Apothecary]], and [[Bender]]'s two.

### Blessed Strikes (8th level)

Once per turn on a weapon-attack or cantrip hit: +1d8 radiant damage.

### Divine Intervention (9th level)

Once/long rest: `d20 + PB`, 20+ succeeds and the deity intervenes (casts a spell or performs a divine act).

### Heroic Boon (10th level)

Choose: **Gift of Consecration** (immune to disease, poison damage, poisoned condition; once/short rest, dropping to 0 HP instead drops to 1 with temp HP = 2×Cleric level) or **Gift of Wrath** (once/short rest, double radiant/necrotic damage dice on a hit; Aura of Retribution — melee attackers within 10 ft take radiant damage = WIS mod when they hit the Cleric).

### Mercy of the Divine (10th level, reaction) — fourth Injury-downgrade class hook

Once/long rest: an ally within 30 ft about to suffer an Injury has it downgraded a tier (Major→Minor; Minor→negated, damage still taken but no Injury effect). The fourth distinct [[Injury System]] class hook, after Paladin's Sanctified Intercession (Critical→Major), Bard's Soothing Performance (Major→Minor/heals Minor), and Apothecary's Trauma Specialist (outright removal) — this one uniquely can prevent a Minor Injury from ever applying at all, not just reduce an existing one.

### Blessed Resilience (13th level)

Reduce spell/magical-effect damage taken by WIS mod. Uses = PB/long rest.

### Turn the Profane Expanded (14th level) — new Corruption data point

Turn the Profane now also affects deeply corrupted or deity-opposed creatures — "including creatures with high Corruption scores (typically 8+)." A new, rougher [[Corruption]] threshold distinct from [[Four Threads of the Mind]]'s formal 5/10/15/20 table — described as approximate ("typically"), used here for targeting eligibility rather than a character-facing consequence tier, so not treated as contradicting the existing thresholds. GM determines qualifying creatures per-deity.

### Epic Boon (20th level)

Choose: **Divine Herald** (auto-succeed Divine Intervention rolls; a second use, once/long rest) or **Avatar of Divinity** (60 ft flight, radiant/necrotic wings; aura: allies within 30 ft get radiant/necrotic resistance + 1d6+WIS HP at turn start, enemies within 30 ft take WIS-mod radiant/necrotic damage at their turn start).

## Last Stand (confirmed universal, 6th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Heaven's Gate | All enemies within 1000 ft DEX save (DC 10+PB+WIS) — fail: radiant damage = 2×character level, blinded+deafened 1 min, prone, drops held items; success: radiant damage = character level, prone. Ignores line of effect; no Legendary Resistance |
| Acts of God | Choose a domain-appropriate manifestation over a 100 ft radius, 5 minutes (examples: Life reverses death — allies regain 2d8 HP/turn; War makes all ally attacks critical; Death turns the area into a necrotic wasteland, 2d10/turn to enemies) — worked out with the GM per the Cleric's specific deity |
| Martyr's Blessing | Allies within 100 ft (5 min): can't fail death saves, immune to necrotic/radiant/psychic damage, deal max damage on all rolls; any ally reduced to 0 HP regains 1 HP and keeps acting. The Cleric's body dissolves into divine light |

Sixth class confirming [[Last Stand]] as universal; standard permanent-death clause, no exception.

## Class Reactions (confirmed universal, 6th class — with a genuine pool exception)

Reactions drawn from the shared PB pool (refresh short/long rest) as established by [[Barbarian]]/[[Bard]]/[[Apothecary]]/[[Bender]]/[[Binder]], a sixth confirmation of [[Class Reactions]] — though this class doesn't list "Class Reactions" as its own named table entry the way others do; the reactions are introduced individually at their unlock levels instead.

- **Blessed Ward** (2nd) — trigger: an ally within 30 ft makes a save; add 1d4 to the roll (seen but not yet resolved).
- **Sacred Interposition** (6th) — trigger: an ally within 30 ft would take spell/magical damage; halve it. **Once per long rest — explicitly not limited by the reaction pool.** Ruled: explained rather than anomalous — mirrors the once/long-rest cadence Clerics already have via Divine Intervention (10th level, above), rather than an unexplained bypass of the shared PB pool.
- **Mercy of the Divine** (10th) — see Core class features above; the source itself cross-references this as a reaction rather than repeating it.
- **Divine Reprisal** (13th) — trigger: a creature within 30 ft hits the Cleric with a melee attack; it takes 2d8+WIS radiant or necrotic damage (Cleric's choice) and WIS saves (DC 8+PB+WIS) or is frightened until the end of its next turn.

## Enemy-morale hook (from Bloodied Breaking Points Rally)

**Bane** on enemy [[Enemy Rally]] checks; **Turn Undead** (now confirmed as the formal ability **Turn the Profane**, see above) forces an automatic rout on undead — still notable since [[Breaking Points]] otherwise states undead/constructs are *immune* to morale entirely, making this a specific carve-out. The per-class deep-dive doesn't address this Breaking-Points interaction directly, so the underlying open question (spell-granted exception vs. genuine inconsistency) remains unresolved even with the fuller Turn the Profane mechanics now known.

## Mythology & Cultural Lore (from the Class Lore Compendium)

*"Divine Conduits: The Chosen of the Bound Pattern."* Clerics existed before they had gods to serve — the first faithful didn't worship the Elemental Embodiments (Vatharun, Nereus, Soltharion, Veydras, Nyzara), they *resonated* with them as living instruments for cosmic forces seeking mortal expression, only later mistaking those forces for creators. The Second Age's **Silence of the Twelve** saw twelve powerful clerics simultaneously lose all divine connection for three days; when power returned, none would explain what they'd experienced — some say they learned the gods' true origin and were struck mute for it. 3,000 clerics died at Ashkarra trying to channel divine power against the Eldritch corruption of the Day of Twelve Shadows, a failure that shook faith continent-wide.

**Source of Power (DM truth):** Divine power is genuinely **hybrid**. The younger Divine Spark gods truly do grant power in response to faith. But the Elemental Embodiments don't grant power at all — they *are* power, and clerics who serve them channel cosmic force directly rather than receiving a gift. Some clerics unknowingly serve gods; others unknowingly channel raw cosmic forces through a theological framework. Neither is wrong.

**Legendary figures:** **Saint Tharivol the Questioning** (First Age) — received genuine divine visions despite publicly doubting the gods' creation-claim, proving faith and doctrine aren't identical. **The Twelve Silent** (Second Age) — the clerics of the three-day Silence, still refusing to explain what they learned. Core philosophy, from "Meditations of a Field Medic," an anonymous Corvessan war-priest: *"They ask: how do you know your god is real? I answer: I don't. I believe. And belief becomes real when sufficient people share it... I heal. I bless. I guide. I stand between mortals and darkness. Call it what you will. I call it faith."*

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Enemy Rally]]
- [[Breaking Points]]
- [[Momentum]]
- [[Injury System]]
- [[Corruption]]
- [[Called Shot]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
