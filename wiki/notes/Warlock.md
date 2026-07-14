---
type: entity
title: "Warlock"
address: c-000068
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
  - "[[Called Shot Subclass Features]]"
  - "[[Seize the Moment]]"
  - "[[Momentum]]"
  - "[[Called Shot]]"
  - "[[Injury System]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Class_breakdown]]"
  - "[[Classes_Summary]]"
  - "[[Bloodied Breaking Points Rally]]"
  - ".raw/Warlock.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Warlock — Power at a Price

**Full Caster tier**. "You didn't earn this power. You negotiated for it." A sustained damage dealer and control caster with unmatched short-rest recovery — fights in shorter, harder bursts than any other spellcaster. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive.

> "You didn't earn this power. You negotiated for it. The distinction matters more than you think."

## Signature abilities

- **Eldritch Blast** — reliable damage
- **Invocations** — customisation
- **Pact Magic** — efficient spell use

**Gameplay style**: consistent damage dealer with utility options. **Core loop**: use power → recover quickly → repeat. Struggles with prolonged nova damage across a rest-less day; excels on adventuring days with multiple short rests.

## Class basics (from Warlock.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, medium, shields. Weapons — simple. Tools — none. Saves — Wisdom, Charisma. Skills — choose two from Arcana, Deception, History, Intimidation, Investigation, Memory, Nature, Religion, Resolve, Streetwise.
- **Starting Equipment**: (a) light crossbow + 20 bolts or (b) any simple weapon; (a) component pouch or (b) wyrd focus; (a) scholar's or (b) dungeoneer's pack; leather armour, a simple weapon, two daggers.
- **Quick Build**: Charisma highest, then Constitution. Any lineage (Tiefling, Drow, Half-Elf thematic). Charlatan/Sage or a Deception/Arcana background. Hex as a bonus action, then Eldritch Blast enhanced by invocations; take short rests often — slots are most valuable refreshed.

**No Weapon Mastery feature anywhere in this document** — a confirming silence matching [[Weapon Mastery]]'s existing Non-Martials listing (Warlock already there alongside Sangromancer/Witch/Wizard/Sorcerer). This generic Patron document also never names Hexblade specifically, so it doesn't touch the existing Hexblade-as-Half-Martial exception already documented on that page.

## Level progression (1st-20th)

| Level | PB | Features | Cantrips | Spells | Slots | Slot Level | Invocations |
|---|---|---|---|---|---|---|---|
| 1 | +2 | Otherworldly Patron, Pact Magic, Eldritch Blast | 2 | 2 | 1 | 1st | — |
| 2 | +2 | Eldritch Invocations, Whispers of the Echoing Pact | 2 | 3 | 2 | 1st | 2 |
| 3 | +2 | Pact Boon | 2 | 4 | 2 | 2nd | 2 |
| 4 | +2 | Improvement | 3 | 5 | 2 | 2nd | 2 |
| 5 | +3 | Eldritch Blast (2 beams) | 3 | 6 | 3 | 3rd | 3 |
| 6 | +3 | Enhanced Boon | 3 | 7 | 3 | 3rd | 3 |
| 7 | +3 | Subclass Feature | 3 | 8 | 3 | 4th | 4 |
| 8 | +3 | Improvement | 3 | 9 | 3 | 4th | 4 |
| 9 | +4 | Eldritch Blast (3 beams), Eldritch Resilience | 3 | 10 | 4 | 5th | 5 |
| 10 | +4 | Heroic Boon, Patronal Reactions | 4 | 10 | 4 | 5th | 5 |
| 11 | +4 | Mystic Arcanum (6th level) | 4 | 11 | 4 | 5th | 5 |
| 12 | +4 | Improvement | 4 | 11 | 4 | 5th | 6 |
| 13 | +5 | Mystic Arcanum (7th level), Pact Magic (3/rest) | 4 | 12 | 4 | 5th | 6 |
| 14 | +5 | Eldritch Blast (4 beams), Subclass Feature | 4 | 12 | 5 | 5th | 6 |
| 15 | +5 | Mystic Arcanum (8th level), Eldritch Resilience (Injury) | 4 | 13 | 5 | 5th | 7 |
| 16 | +5 | Improvement | 4 | 13 | 5 | 5th | 7 |
| 17 | +6 | Mystic Arcanum (9th level), Pact Magic (4/rest) | 4 | 14 | 5 | 5th | 7 |
| 18 | +6 | Patron's Favour | 4 | 14 | 5 | 5th | 8 |
| 19 | +6 | Improvement | 4 | 15 | 5 | 5th | 8 |
| 20 | +6 | Epic Boon | 4 | 15 | 6 | 5th | 8 |

**Documentation quirk**: "Eldritch Resilience" is used as the name for two unrelated features — the 9th-level Pact Shield/Woven Fate/Supernatural Resolve suite, and again at 15th level ("Eldritch Resilience (Injury)") for an unrelated Injury downgrade. Not a contradiction, just a reused name across two different levels of the same document.

## Core class features (full text)

### Otherworldly Patron (1st level, and 6th, 10th, 14th, 15th)

Forge a pact with an otherworldly being (Fiend, Archfey, Great Old One named as examples). Features at 1st/6th/10th/14th/15th.

### Pact Magic (1st level) — seventeenth confirmed DC formula

All slots are the same, highest available level; recover fully on a short *or* long rest. Charisma-based: **Spell Save DC = 8+PB+CHA, Spell Attack = PB+CHA** — seventeenth confirmation of the `8+PB+ability mod` formula.

### Eldritch Blast (1st level)

1d10 force damage per beam on a hit; 2 beams at 5th, 3 at 9th, 4 at 14th. Each beam can target a different creature and rolls its own attack. Invocations modify it extensively — the foundation of the class's combat identity.

### Eldritch Invocations (2nd level, scaling)

Learn invocations per the table; swap one per level. Samples: **Agonizing Blast** (+CHA mod per beam), **Armor of Shadows** (at-will *Mage Armor*), **Devil's Sight** (120 ft darkvision through magical darkness), **Repelling Blast** (push 10 ft on a hit), **Accursed Smite** (Pact of the Blade, 5th+ prereq: crits reduce target DR by 2 or deal +1d8 force if no DR), **Chaos Shot** (see Called Shot note below).

### Whispers of the Echoing Pact (2nd level)

Re-attune Echo Glyphs (count = PB) during a 10-minute short-rest communion; once per short rest; glyphs must bind to castable spells.

### Pact Boon (3rd level, enhanced at 6th)

Choose: **Pact of the Blade** (summon a CHA-based magical pact weapon as an action, dismissed/vanishes if 5+ ft away for 1 minute; bond an existing weapon via 1-hour ritual; *Enhanced*: Attack action with the pact weapon grants two attacks), **Pact of the Chain** (*find familiar* as a ritual, no components; blink dog/imp/pseudodragon/quasit forms, telepathy + shared senses on the same plane; *Enhanced*: familiar gains temp HP = PB+CHA on short rests, and can grant the Warlock advantage via its own reaction when a creature near it is attacked), or **Pact of the Tome** (a Book of Shadows with 3 any-list cantrips + 2 inscribed 1st/2nd-circle Wyrd rituals not counting against spells known; *Enhanced*: more rituals via 2 hours + 50gp/circle, plus one swappable any-list spell not counting against known spells).

### Enhanced Boon (6th level)

Patron-specific enhancements beyond the Pact Boon's own 6th-level upgrade: **Blade — Eldritch Warcaster** (advantage on reaction attacks with the pact weapon; CHA instead of DEX for Evasion in light armour; reaction melee attack on taking melee damage). **Tome — Mystic Barrier** (temp HP = ½ Warlock level+CHA mod after each short rest; INT/CHA instead of DEX for Evasion unarmoured). **Chain — Spiritbinder's Aegis** (resistance to necrotic/radiant/psychic within 10 ft of the familiar; once/long rest, the familiar can sacrifice itself to restore the Warlock to 1 HP at 0).

### Eldritch Resilience (9th level)

**Pact Shield** (reaction: reduce damage by Warlock level+CHA mod, uses = CHA mod/long rest). **Woven Fate** (a rolled 1 on a save/check becomes a 2, uses = half PB/long rest). **Supernatural Resolve** (advantage vs. charmed/frightened/madness).

### Heroic Boon (10th level)

Choose: **Boon of the Eldritch Conduit** (casting via Pact Magic allows a free bonus-action cantrip; damaging with a 1st-circle+ spell grants temp HP = PB+CHA mod; a failed concentration check can be auto-succeeded by spending a Pact Magic slot) or **Boon of the Forbidden Pact** (once/long rest cast a ≤6th-circle any-list spell without a slot; dropping to 0 HP delays unconsciousness to the end of the next turn; Eldritch Blast deals +CHA-mod force to one additional creature within 10 ft of the target).

### Patronal Reactions (10th level)

Uses = PB per short rest (same shared pool, patron-flavoured): **The Fiend — Infernal Rebuke** (a melee attacker within 10 ft takes CHA+PB fire damage), **The Archfey — Fey Step** (teleport 15 ft on being hit, imposing disadvantage on the triggering attack), **The Great Old One — Psychic Backlash** (a visible attacker WIS saves, DC = Spell Save DC, or takes 2d8 psychic + disadvantage on the attack roll).

### Mystic Arcanum (11th level, and 13th, 15th, 17th)

A 6th-circle spell usable once/long rest without a slot; 7th/8th/9th-circle added at 13th/15th/17th, each once/long rest.

### Eldritch Resilience — Injury Downgrade (15th level) — twelfth Injury hook

Once per day, a Major Injury the Warlock would suffer downgrades to Minor — the standard tier-downgrade shape already seen on Paladin/Bard/Cleric, the twelfth distinct hook overall (reusing the "Eldritch Resilience" name from 9th level, see the documentation quirk above).

### Patron's Favour (18th level)

Cast any known spell of 5th circle or lower from any spell list using Pact Magic.

### Epic Boon (20th level)

Choose: **Eldritch Restoration** (once/short rest, starting a turn with 0 Pact Magic uses restores all of them as an action; a Pact Magic slot casts one level higher, up to 6th circle, once/turn) or **Boundless Invocations** (limited-use invocations become unlimited; one bonus invocation ignoring prerequisites; once/short rest, Eldritch Blast's beam count doubles).

## Last Stand (confirmed, 21st class confirming of 22 ingested — standard permanent-death clause)

| Option | Effect |
|---|---|
| Eldritch Oblivion | 60 ft blast; chosen creatures CON save (DC 10+PB+CHA) — fail: 12d10 necrotic + restrained 1 minute; success: half, not restrained. Area becomes magical darkness (only the Warlock sees through it) for 1 minute |
| Pactbound Sacrifice | Up to 5 allies within 60 ft (1 min): temp HP = 2×Warlock level, +2d10 force on hits, auto-succeed their next save. Up to 5 enemies in range: 2d10 psychic/turn; WIS save (DC 10+PB+CHA) or frightened of the Warlock's allies for the duration |
| Dark Concordance | Summon a CR 15 Avatar of the Patron (Fiend: Balor/Pit Fiend; Great Old One: Star Spawn Larva Mage/Aboleth; Archfey: custom) within 30 ft, acting immediately after the Warlock, 1 minute, immune to charm/fear/banishment; on expiry, the area is corrupted for 1 hour (2d6 necrotic on starting a turn there) |

Twenty-first class confirming [[Last Stand]] as universal (of 22 per-class files ingested — [[Sorcerer]] remains the sole exception); all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Both DC-bearing options use `10+PB+CHA`, two more data points for the `10+PB+ability` group.

## Class Reactions (22nd class confirming — clean shared-pool confirmation)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest, no stated exceptions (Patronal Reactions explicitly reuses the same PB-per-short-rest count rather than a separate pool).

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Eldritch Counter | 2nd | A creature within 60 ft casts a spell targeting the Warlock or an ally | Fire an Eldritch Blast beam at the caster; a hit gives their spell disadvantage on its attack roll or grants targets advantage on saves against it until the caster's next turn |
| Darkness Veil | 6th | The Warlock or an ally within 30 ft is targeted by a ranged attack | The attack is made with disadvantage; a resulting miss grants the target +1 Momentum |
| Patronal Reactions | 10th | Patron-specific (see above) | Infernal Rebuke / Fey Step / Psychic Backlash |

## Cross-links

- **[[Called Shot]]**: **Chaos Shot** invocation reduces the Called Shot penalty by 1 when delivered via Eldritch Blast; on a success, the target also gets disadvantage on its next Evasion roll or area-effect save — a new invocation-gated access route, distinct from the already-documented Hexblade subclass hook.
- **[[Momentum]]**: Darkness Veil's miss-triggered **+1 Momentum to the protected target** (self or ally) is a new shape — Momentum awarded to whoever was defended, not to the Warlock casting the reaction, distinct from every self-directed or attacker-penalizing trigger seen so far.

## Mythology & Cultural Lore (from the Class Lore Compendium)

*Pact-Bound: Those Who Trade Soul for Power.*

Warlocks emerged from a simple, terrible bargain: powerful entities want mortal servants, mortals want power, and trade is always possible. Patron types range from capricious Archfey to soul-collecting Fiends, sanity-destroying Great Old Ones, service-demanding Celestials, and environmentally-obligated Primordials — each granting a different flavor of power at a different cost. The Thirteen Doomed, the first recorded warlocks, attempted to serve thirteen patrons simultaneously and went mad within days, their screaming leaving a permanent audio-echo at the pact-site still audible 4,000 years later. At Ashkarra's Fall, warlocks who tried to break their pacts en masse — reasoning the city's destruction voided all contracts — found their patrons simply relocated the survivors and continued collecting.

**Source of Power (DM truth):** Warlock pacts create a karmic exchange — mortals trade their future (soul, service, freedom) for present power, knowledge, or ability, while patrons access the mortal world through the connection the warlock provides. This makes warlocks living bridges between planes, neither fully mortal nor fully spiritual, and — unlike most classes — their power largely bypasses the Thread system and Glyph layers entirely, flowing directly from patron to servant instead.

**Legendary figures:** The Thirteen Doomed, whose attempt to bind thirteen patrons simultaneously drove them to madness within days and left a permanent scream-echo at their pact-site.

*"They judge us for selling souls. But everyone sells something. Time. Freedom. Integrity. We're just honest about transaction... when Thread system fails and gods go silent, my patron still answers... At least I read the fine print."* — The Pact-Holder's Truth

## See also

- [[Class_breakdown]]
- [[Classes_Summary]]
- [[FEARS Class Roster]]
- [[Enemy Rally]]
- [[Called Shot Subclass Features]]
- [[Seize the Moment]]
- [[Momentum]]
- [[Called Shot]]
- [[Injury System]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[FEARS MOC]]
