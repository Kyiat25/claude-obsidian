---
type: entity
title: "Shaman"
address: c-000018
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
  - "[[Narrative Identity Framework]]"
  - "[[Class_breakdown]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Momentum]]"
  - "[[Damage Reduction]]"
  - "[[Evasion]]"
  - "[[Called Shot]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Welcome to FEARS]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Shaman.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Shaman — Spirit Mediator

**Full Caster tier**, Warlock-style pact-slot casting (fixed slot level, shared pool, recovers on a short or long rest). "The spirits don't leave a place cleanly. Where you have worked, the land holds memory. That is not a metaphor." A support-oriented battlefield controller who shapes the encounter space with persistent Totems rather than winning through raw damage. Complexity self-rated MODERATE (5/10) by its own per-class deep-dive.

> "The spirits don't leave a place cleanly. Where you have worked, the land holds memory. That is not a metaphor."

## Signature abilities

- **Totems** — ongoing effects
- **Spirit Binding** — versatility
- **Totemic Assault**

**Gameplay style**: zone controller, shaping the battlefield over time. **Core loop**: place → influence → reposition → repeat. Struggles when Totems get destroyed or high mobility is required; excels maintaining Totems and exploiting the Spirit-Touched Ground feedback loop.

## Class basics (from Shaman.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light, shields. Weapons — simple, blowguns, nets. Tools — none. Saves — Wisdom, Focus (a third confirmed Focus-as-saving-throw class after [[Inventor]] and [[Monk]]). Skills — choose two from Animal Handling, Arcana, Gathering, Insight, Medicine, Nature, Performance, Religion, Resolve.
- **Starting Equipment**: (a) quarterstaff or (b) any simple weapon; (a) shortbow + 20 arrows or (b) 5 javelins; (a) priest's or (b) explorer's pack; leather armour and an object to serve as a Totem.
- **Quick Build**: Wisdom highest, then Constitution. Any lineage (Orc, Goblin, Tiefling thematic). Outlander/Hermit or a Nature/Religion background. Place Totems before/at combat start; Totemic Assault on priority targets; stand in Spirit-Touched ground for the Momentum bonus.

**No Weapon Mastery feature anywhere in this document** — but [[Weapon Mastery]]'s existing table lists Shaman as a **Half-Martial** (3 crits simple/4 crits martial). This is a real gap, not a confirming silence like [[Sangromancer]]'s: Shaman *is* expected to have the subsystem per that table, yet this deep-dive never mentions it once. Flagged as unresolved on [[Weapon Mastery]].

## Level progression (1st-20th)

| Level | PB | Features | Bound Totems | Cantrips | Spells | Slots | Slot Level |
|---|---|---|---|---|---|---|---|
| 1 | +2 | Sacred Focus, Totems, Totemic Assault | 2 | — | — | — | — |
| 2 | +2 | Primal Magic, Spirit Link | 2 | 2 | 3 | 2 | 1st |
| 3 | +2 | Spirituality, Class Reactions | 2 | 2 | 4 | 2 | 2nd |
| 4 | +2 | Improvement | 3 | 3 | 5 | 2 | 2nd |
| 5 | +3 | Totemic Versatility | 3 | 3 | 6 | 2 | 3rd |
| 6 | +3 | Spirituality Feature, Spirit Intercession (Reaction) | 4 | 3 | 6 | 2 | 3rd |
| 7 | +3 | Ancestral Precision, Spirit-Touched Ground | 4 | 3 | 7 | 2 | 4th |
| 8 | +3 | Improvement | 4 | 3 | 7 | 2 | 4th |
| 9 | +4 | — | 5 | 3 | 8 | 2 | 5th |
| 10 | +4 | Spirituality Feature, Heroic Boon, Totemic Resilience | 5 | 4 | 8 | 2 | 5th |
| 11 | +4 | Greater Totem Spirit (6th level), Deepening Spirit | 5 | 4 | 9 | 3 | 5th |
| 12 | +4 | Improvement | 6 | 4 | 9 | 3 | 5th |
| 13 | +5 | Greater Totem Spirit (7th level) | 6 | 4 | 10 | 3 | 5th |
| 14 | +5 | Spirituality Feature | 6 | 4 | 10 | 3 | 5th |
| 15 | +5 | Greater Totem Spirit (8th level), Totemic Mastery, Awakened Ground | 7 | 4 | 11 | 3 | 5th |
| 16 | +5 | Improvement | 7 | 4 | 11 | 3 | 5th |
| 17 | +6 | Spiritbond Mastery, Greater Totem Spirit (9th level), Totemic Resilience Improvement | 7 | 4 | 11 | 4 | 5th |
| 18 | +6 | — | 8 | 4 | 12 | 4 | 5th |
| 19 | +6 | Improvement | 8 | 4 | 12 | 4 | 5th |
| 20 | +6 | Epic Boon | 8 | 4 | 12 | 4 | 5th |

**Documentation gap**: Totemic Shield (a Class Reaction, detailed below) is headed "5th Level" in its own section, but the level-progression table's 5th-level row lists only Totemic Versatility — Totemic Shield doesn't appear in the table at all. Treated as a source-internal inconsistency, not a contradiction between sources, the same kind of gap seen on [[Paladin]]'s undetailed Spellcasting and [[Reaper]]'s Momentum-naming quirk.

## Core class features (full text)

### Sacred Focus (1st level) — new Evasion formula variants

Choose the core strength channeling spiritual power: **Body** (max HP +1 at 1st, +1 again per Shaman level), **Heart** (+WIS mod, min +1, on charmed/frightened saves), **Mind** (WIS mod usable in place of INT for INT checks/saves), or **Soul** (unarmoured/shieldless Evasion DC becomes **10+DEX mod+WIS mod**, replacing the standard formula).

### Totems (1st level) — new Momentum gain source

Bind primal spirits into Tiny objects; must hold a Totem to use it; one Totem's ability active at a time unless stated otherwise. **Totem Save DC = 8+PB+WIS** (matches Spellcasting's DC exactly). **Totemic Rhythm**: activating, summoning, or moving a Spirit Totem in combat grants **+1 Momentum**. Bound Totems known scales per the table; see the Totem Catalogue below for samples.

### Totemic Assault (1st level)

Action while holding a Totem: target a creature within 60 ft, CHA save vs. Totem Save DC or take 1d10 necrotic (half on success). Scales to 2d10/5th, 3d10/11th, 4d10/17th.

### Primal Magic (2nd level) — thirteenth confirmed DC formula

Warlock-style pact slots: fixed level, shared pool, recovers short or long rest. Wisdom-based: **Spell Save DC = 8+PB+WIS, Spell Attack = PB+WIS** — thirteenth confirmation of the `8+PB+ability mod` formula.

### Spirit Link (2nd level)

Action: detect spiritual/magical creatures and effects within 60 ft, including wild magic zones, arcane rifts, ley lines, dead magic zones. Uses = WIS mod per long rest.

### Spirituality (3rd level, and 6th, 10th, 14th)

Choose **Curse Binder, Spirit Warrior, Wild Heart,** or **Witch Doctor**. Features at 3rd/6th/10th/14th — not detailed further here.

### Totemic Versatility (5th level)

End of a long rest: swap one known Totem for another from the list.

### Ancestral Precision (7th level) — new Called Shot access route

Bonus action, mark one enemy within 60 ft for 1 minute (uses = WIS mod/long rest): the Shaman and allies gain advantage on Called Shots against it; its DR is reduced by WIS mod (min 1); a failed Evasion roll against it grants allies within 30 ft +1 Momentum; if it's within an active Totem's range, Called Shots against it deal +2d6 spirit damage; dropping it to 0 HP jumps the mark to the nearest enemy within 30 ft.

### Spirit-Touched Ground (7th level) — second new Momentum gain source

A location becomes Spirit-Touched when a Totem is activated/placed there, a 2nd-circle+ Primal Magic spell is cast there, Totemic Assault is used there, or Spiritbond Mastery/a Greater Totem Spirit ability is used there. Accumulates up to 3 permanent marks (cleansable only deliberately). **Entering or starting a turn in a Spirit-Touched area grants +1 Momentum** (once per turn); once per long rest there, activate a Totem as a free action instead of a bonus action.

### Heroic Boon (10th level)

Choose: **Totemic Conduit** (activate two Totems with the same action; +30 ft to all Totem ranges; Totemic Assault gains an extra target) or **Spirit Surge** (once/short rest, overcharge a Totem to maximum numerical effect; once/short rest, activate all active Totems simultaneously as one action).

### Totemic Resilience (10th level, and 17th) — Damage Reduction contradiction

Choose one bound Totem type; while it's active, gain a benefit by category: **Guardian** (Bear/Ox/Turtle) → **DR 1**; **Spirit** (Raven/Owl/Fox) → +2 Evasion; **Ancestor** (Wolf/Eagle/Serpent) → advantage vs. frightened/charmed. Swappable on a long rest. At 17th: Totemic Assault against a target in range of two Totems gains advantage + temp HP (WIS mod+Shaman level).

> [!note] Didn't match the old "Totemic Wards elemental DR to allies" claim — resolved, deep-dive wins
> The old [[Damage Reduction]] claim stated, "zero drift" from the DCS-level summary: ~~"Shaman (Totemic Wards elemental DR)"~~ — implying an elemental-typed DR bonus granted to allies. Ruled: this per-class deep-dive is authoritative. Current rule: the Guardian Totem category (Bear/Ox/Turtle) grants flat, non-elemental **+1 DR to the Shaman only**; the other two Totem categories grant Evasion or save-advantage instead, not DR. No ally-targeted or elemental-typed DR mechanic exists.

### Greater Totemic Bond (11th level)

Bond a Greater Totem Spirit (doesn't count against Bound Totems); grants once/long-rest, no-slot access to its spells at specific levels (6th at 11th level, 7th/8th/9th at 13th/15th/17th). Casting one applies a Sacred Focus-based enhancement: **Body** (temp HP = 2×spell level), **Heart** (an ally within 10 ft of the target gains a d6 Inspiration die), **Mind** (reroll one damage/healing die, keep new result), **Soul** (targets have disadvantage on ongoing-effect saves). Totemic Versatility can also swap the Greater Totem Spirit.

### Deepening Spirit (11th level)

Spirit-Touched areas with 2+ marks: **Tactical Presence** (ground within 10 ft of active Totems is difficult terrain for hostiles); **Spiritual Impression** (once/long rest/location, ask the spirits a yes/no question about the past 7 days there).

### Totemic Mastery (15th level)

One additional active Totem simultaneously.

### Awakened Ground (15th level)

Locations Spirit-Touched three times become Spiritually Awakened: always know their direction/distance; sense a CR1+/1st-level+ creature's presence there while absent (doesn't wake the Shaman from sleep). **Restored Power**: a short rest at an Awakened location regains 1 expended slot of 3rd level or lower.

### Spiritbond Mastery (17th level)

Bond a second Greater Totem Spirit; their spell lists combine, and either spirit's Sacred Focus enhancement is usable on either's spells.

### Epic Boon (20th level)

Choose: **Avatar of the Spirits** (once/long rest, action, 1 minute: resistance to all damage, one extra active Totem, teleport 30 ft each turn as part of movement, Totemic Assault deals max damage) or **Eternal Spirit** (once/long rest, dropping to 0 HP but not killed instantly restores half max HP + activates a Totem free; no food/water/sleep needed, immune to exhaustion, can't be forcibly moved without consent; a destroyed/deactivated Totem auto-reactivates at the start of the Shaman's next turn).

## Totem Catalogue (sample — full catalogue deferred to a "Shaman Compendium" not in this source)

Bear (claws 1d6/1d8 STR slashing, magical), Eagle (Perception proficiency + advantage, 9th: can't be blinded, see invisible 30 ft), Earthquake (once/turn melee hit +1d6 damage, scales to 1d12/17th), Autumn Wind (hit forces a CON save or target can't regain HP until the Shaman's next turn), Twilight (Darkvision 120 ft, 9th: see through magical darkness), Hound (Survival proficiency + advantage, 9th: exact tracked-creature count/size/timing), Mountain — Body Focus (Evasion DC = 13+CON mod unarmoured/shieldless, 5th: resistance to nonmagical physical), Crossroads — Heart Focus (*speak with animals* always active, 5th: + *speak with plants*), Harvest — Soul Focus (free *goodberry* after each rest), Panther (Stealth proficiency + advantage, 9th: Hide as a bonus action in dim light/darkness).

## Last Stand (confirmed universal, 18th class — standard permanent-death clause)

| Option | Effect |
|---|---|
| Spiritstorm Manifestation | 40 ft Spiritstorm, 1 minute: enemies CON save (DC 10+PB+WIS) — fail: 8d10 force + blinded 1 minute; success: half, not blinded. Enemies in the area take 2d10/turn (Shaman's choice of type); allies gain resistance to all damage + advantage on saves |
| Totemic Ascendance | Active Totems persist, indestructible, 5 minutes; allies within 60 ft of them gain temp HP (4×Shaman level), advantage on attacks/saves/checks while in range, and 1d10 HP/turn if in range; all Totems activate immediately, affecting all valid targets |
| Ancestral Fury | 1 minute as an incorporeal spectral warrior, fly 60 ft; melee spell attack against any number of creatures within 30 ft, 6d10 radiant/necrotic each hit; enemies within 30 ft WIS save (DC 10+PB+WIS) each turn or frightened until their next turn; on expiry, a 4d10 force burst to chosen creatures within 30 ft |

Eighteenth class confirming [[Last Stand]] as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Both DC-bearing options use `10+PB+WIS`, two more data points for the `10+PB+ability` group on [[Last Stand]]'s open question.

## Class Reactions (confirmed universal, 18th class — clean shared-pool confirmation, but with the table-mismatch gap noted above)

Draws from the shared **Proficiency Bonus pool**, refreshing short/long rest, no stated exceptions.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Spirit Ward | 2nd | An ally within 30 ft is hit | Reduce damage by PB+WIS mod; attacker WIS saves or is Marked by Spirits (next attack against them has advantage) |
| Totemic Shield | 5th (see gap above) | An ally within 30 ft is hit | A Totem flares: resistance to that damage type + temp HP (PB+WIS mod); attacker WIS saves (DC 8+PB+WIS) or Marked by Spirits. At 11th, also +2 AC to the ally until the Shaman's next turn |
| Spirit Intercession | 6th | An ally within 15 ft is hit | Reduce that damage by WIS mod (min 1) |

## Mythology & Cultural Lore (from the Class Lore Compendium)

*Spirit-Hosts: Those Who Become Living Bridges.*

Shamans emerged from a question no witch or warlock asked: "What if I become the vessel?" Rather than binding spirits into objects (witches) or bargaining with distant patrons (warlocks), shamans invite spirits to inhabit living flesh directly, guided by one of four Sacred Focuses (Body, Heart, Mind, or Soul) that anchor the hosting and prevent full possession. Vorga the Hundred-Spirited, an orc shaman who hosted 47 spirits simultaneously through a Totem-network and lived 200 years before her final Totem shattered, represents the tradition's furthest extreme. Ashkarra's Fall killed thousands of shamans as hosted spirits fled or died with their hosts — survivors described it as "being abandoned by half your consciousness," and some who recovered learned to host corrupted spirits fleeing the dimensional collapse, gaining power at the risk of contamination.

**Source of Power (DM truth):** The Compendium names this "**Spirit Glyphs**" — consciousness itself as a fundamental cosmic force accessed directly through hosting. *Flagged discrepancy:* the established Five Laws framework ([[How the Five Layers Shape the Creation World]]) recognizes only five Glyph layers — Primal, Universal, Elemental, Form, and Personal — with no "Spirit" layer among them. Since [[Personal Glyphs]] govern how individual souls channel power and fate, that layer is the closest existing analog, but the Compendium's own framing treats spirit-hosting as accessing something distinct: a hybrid-consciousness synthesis (mortal experience + spiritual essence) that neither component could achieve alone. Left unresolved pending a future source clarifying whether "Spirit Glyphs" is a sixth layer or a Compendium-specific gloss on Personal Glyphs.

**Legendary figures:** Vorga the Hundred-Spirited, the orc shaman who hosted 47 spirits simultaneously and lived two centuries before her Totem-network finally shattered.

*"Wizard studies alone. Cleric prays alone. Warlock bargains alone. I am never alone... They call this possession. I call it partnership. My body is temple. Spirits are honored guests... Death doesn't end—it redistributes."* — The Spirit-Host's Testimony

## See also

- [[Welcome to FEARS]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[Dynamic Combat System (DCS)]]
- [[FEARS Class Roster]]
- [[Momentum]]
- [[Damage Reduction]]
- [[Evasion]]
- [[Called Shot]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Personal Glyphs]]
- [[How the Five Layers Shape the Creation World]]
- [[FEARS MOC]]
