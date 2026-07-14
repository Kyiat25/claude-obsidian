---
type: entity
title: "Witch"
address: c-000022
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
  - "[[Narrative Identity]]"
  - "[[Spirit Debt]]"
  - "[[Classes_Summary]]"
  - "[[FEARS Class Roster]]"
  - "[[Class_breakdown]]"
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Momentum]]"
  - "[[Damage Reduction]]"
  - "[[Weapon Mastery]]"
  - "[[Last Stand]]"
  - "[[Class Reactions]]"
sources:
  - "[[Welcome to FEARS]]"
  - "[[Narrative Identity]]"
  - "[[Classes_Summary]]"
  - "[[Class_breakdown]]"
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Witch.md"
  - ".raw/Class_Lore_Compendiums_DorOEstel_UPDATED.md"
confidence: high
---

# Witch — Architect of Misfortune

**Full Caster tier**. "The Fireball hits everything at once and is done. The curse starts on one creature and radiates outward based on what the enemies do." Not a blaster, not a healer — a patient sustained-control engine that wins inevitably rather than quickly, by making every enemy action less reliable until nothing works. Complexity self-rated HIGH (8/10) by its own per-class deep-dive.

> "A smart enemy who keeps passing saves stays clean. One who panics becomes a node that infects everything around it."

## Signature abilities

- **Hexes**
- **Witch's Mark**
- **Curse Propagation**

**Gameplay style**: debuffer and control specialist, weakening enemies until they collapse. **Core loop**: curse → spread → escalate → collapse. Weak to fast, hard-hitting initiative before control is established; strong in any fight lasting 3+ rounds, especially against many enemies. **Design note straight from the source**: Hex Contagion's unlimited spread is intentional — the Charisma save is the sole balancing mechanism, a deliberate identity differentiator from AoE spells.

## Class basics (from Witch.md deep-dive)

- **Hit Dice**: 1d8/level. HP at 1st: 8 + CON mod. HP at higher levels: 1d8 (or 5) + CON mod/level after 1st.
- **Proficiencies**: Armour — light. Weapons — simple. Tools — herbalism kit. Saves — Wisdom, Charisma. Skills — choose two from Arcana, Crafting, Medicine, Memory, Nature, Perception, Persuasion, Resolve, Survival.
- **Starting Equipment**: (a) shortbow + 20 arrows or (b) any simple weapon; (a) two daggers or (b) any simple melee weapon; leather armour, an explorer's pack, a druidic focus.
- **Quick Build**: Charisma highest, then Wisdom. Any lineage (Half-Elf, Tiefling, Gnome thematic). Sage/Hermit or an Arcana/Insight background. Malefic Touch every bonus action; Witches Mark via reaction on key rolls; let Hex Contagion spread after the first bloodied/fallen enemy.

**No Weapon Mastery feature anywhere in this document** — a third confirming silence this session (after [[Sangromancer]] and [[Warlock]]) matching [[Weapon Mastery]]'s existing Non-Martials listing, where Witch is already named.

### Hex of Frailty (6th level, Coven Feature — Coven of the Hidden Moon)

> [!note] Gap closed post-ingest
> The existing [[Damage Reduction]] page cited "Hex of Frailty" as a Witch DR-reduction hook, but this per-class deep-dive never detailed it — Coven-specific features (1st/6th/10th/14th) were left generic. Ruled: a genuine feature, not a documentation error, and designed to fill the 6th-level Coven Feature slot for Coven of the Hidden Moon.

A creature currently affected by the Witch's Malefic Touch hex or bearing Witches Mark has its DR reduced by **2** for as long as the hex/mark persists on it. Magnitude matches the cluster's other enemy-DR-reduction effects ([[Ranger]]'s Hunter's Mark, [[Ranger]]'s Colossus Slayer, [[Inventor]]'s Overclock, all flat −2); rides on the existing hexed-target mechanic rather than adding a new action-economy cost, consistent with how Hunter's Mark's DR reduction rides on an existing spell effect rather than standing alone.

## Level progression (1st-20th)

| Level | PB | Features | Cantrips | Spells |
|---|---|---|---|---|
| 1 | +2 | Coven, Spellcasting, Malefic Touch | 4 | 2 |
| 2 | +2 | Spirit Binding, Fateful Twist, Hex Ward | 4 | 3 |
| 3 | +2 | Witches Mark (d4), Hex Echo | 4 | 4 |
| 4 | +2 | Improvement | 5 | 5 |
| 5 | +3 | Witches Mark (d6), Spirit Binding (2), Life Drinker | 5 | 6 |
| 6 | +3 | Coven Feature, Curse Resonance | 5 | 7 |
| 7 | +3 | Hex-Turn (Reaction) | 5 | 8 |
| 8 | +3 | Improvement, Echo Scent | 5 | 9 |
| 9 | +4 | Greater Binding (1), Hex Contagion | 5 | 10 |
| 10 | +4 | Coven Feature, Witches Mark (d8), Heroic Boon | 6 | 11 |
| 11 | +4 | Hex Momentum | 6 | 12 |
| 12 | +4 | Improvement | 6 | 12 |
| 13 | +5 | Greater Binding (2), Cursed Misfortune, Spreading Malice | 6 | 13 |
| 14 | +5 | Coven Feature, Enhanced Hex | 6 | 13 |
| 15 | +5 | Witches Mark (d10), Spirit Binding (3), Concordance | 6 | 14 |
| 16 | +5 | Improvement | 6 | 14 |
| 17 | +6 | Greater Binding (3), Web of Malice | 6 | 15 |
| 18 | +6 | — | 6 | 15 |
| 19 | +6 | Improvement | 6 | 15 |
| 20 | +6 | Spell Exchange, Epic Boon | 6 | 15 |

Spell slots follow the standard full-caster progression (4/3/3/3/2/1/1/1/1 by 20th).

## Core class features (full text)

### Coven (1st level, and 6th, 10th, 14th)

Choose a magical tradition (**Coven of the Hidden Moon** — forbidden knowledge/shadow magic — and **Coven of the Verdant Wood** — healing/growth/life — named as examples). Always-prepared spells; features at 1st/6th/10th/14th, not detailed further here.

### Spellcasting (1st level) — eighteenth confirmed DC formula

Charisma-based: **Spell Save DC = 8+PB+CHA, Spell Attack = PB+CHA** — eighteenth confirmation of the `8+PB+ability mod` formula. Spells known (not prepared); ritual-tagged spells slot-free; a druidic focus or a Witch's Implement serves as the spellcasting focus.

### Malefic Touch (1st level)

Bonus action, 30 ft, Evocation cantrip (Witch-exclusive): the target is hexed until the start of the Witch's next turn, disadvantaged on its next save against a Witch spell. At 5th level it also deals damage on application (1d6 at 5th-10th, 2d6 at 11th-16th, 3d6 at 17th+, necrotic or radiant, chosen when learned). **"Hexed"** is the umbrella term covering both this and Witches Mark.

### Spirit Binding (2nd level, and 5th, 15th)

Bind spirits into **Witch Implements** (Brewer's Cauldron, Soul Candle, Nightflyer named as examples); one at 2nd, more at 5th/15th. Creating/replacing one takes a 1-hour ritual during a rest.

### Fateful Twist (2nd level, reaction) and Hex Ward (2nd level, reaction)

**Fateful Twist**: a hexed creature's attack roll is imposed with disadvantage; uses = PB per short or long rest. **Hex Ward**: a hexed creature targeting the Witch forces a CHA save (DC = 8+PB+CHA) or the attack redirects to another valid target within 30 ft; same use economy. Both draw from the shared pool (see Class Reactions below).

### Witches Mark (3rd level, scaling Hex die, and Hex Echo)

Reaction: curse a creature making an ability check/attack/save — it rolls the Witch's **Hex die** and subtracts the result from its roll. Persists until dismissed, the target dies, or re-cast on someone else; no concentration; uses = PB per long rest; one target at a time. Hex die scales 3rd (d4) → 5th (d6) → 10th (d8) → 15th (d10). If the marked target drops to 0 HP, a bonus action moves the curse to a new creature within 30 ft. **Hex Echo**: successfully applying Witches Mark via reaction allows an immediate free cantrip cast (no action) targeting the marked creature or originating from the Witch's space.

### Life Drinker (5th level)

Once per turn, a hexed creature missing the Witch with an attack heals the Witch a Hex die's worth of HP.

### Curse Resonance (6th level)

Once per turn, damaging a hexed creature with a cantrip regains 1 Class Reaction pool use.

### Echo Scent (8th level)

Being hit by a hexed creature's spell allows an Arcana/Insight check (DC = 10+spell level) to learn an Echo Glyph tied to that spell for 24 hours, permanently learnable after the next long rest by sacrificing a known Glyph. Once per long rest.

### Hex Contagion (9th level) — the class's signature mechanic

A Witches-Marked creature becoming Bloodied or dropping to 0 HP forces everyone within 15 ft to CHA save (DC = 8+PB+CHA) or become **Hex-Spread** (suffers the Hex die penalty on their next roll of any kind). Hex-Spread creatures can repeat the save each turn-end to shed it; a Hex-Spread creature failing its own save can spread the effect further within 15 ft. **No spread limit** — the CHA save alone balances it.

### Hex Momentum (11th level) — new Momentum gain source

Once per turn, a hexed creature (via Witches Mark or Hex Contagion) failing a save against a Witch effect grants **+1 Momentum**.

### Cursed Misfortune (13th level)

While Witches-Marked: can't benefit from Lucky/Portent-style reroll-altering traits; disadvantage on death saving throws.

### Spreading Malice (13th level)

Moving Witches Mark to a new creature (after the old target hits 0 HP) forces a CHA save on the new target or it becomes Hex-Spread too.

### Enhanced Hex (14th level)

Witches Mark also applies the *Hex* spell's effects; no line of sight required to apply it (works through obstacles/magical darkness against hidden creatures).

### Concordance of Spirits (15th level)

Once per long rest, cast a concentration spell as a bonus action even in the same round as a levelled spell cast; succeeding a concentration save grants temp HP = the Hex die.

### Web of Malice (17th level)

**Curse Chain**: a Hex-Spread creature failing its save auto-triggers Hex Contagion with no action from the Witch, chaining once per round. **Evasion Collapse**: Hex-Spread creatures have disadvantage on *all* Evasion rolls, benefiting every attacker, not just the Witch. **Lasting Contagion**: a creature succeeding its save to end Hex-Spread still suffers the Hex die penalty once more on its next turn before fully releasing. **Momentum Threshold**: with 3+ creatures simultaneously Witches-Marked/Hex-Spread, the Hex die increases one size for the rest of combat (d4→d6→d8→d10→d12), dropping back below 3.

### Spell Exchange (20th level)

A short rest allows swapping any number of known spells for others of a castable level.

### Epic Boon (20th level)

Choose: **Avatar of Spirits** (once/long rest, action, 1 minute: resistance to all damage, 60 ft fly + hover, one extra concentration spell simultaneously; enemies within 30 ft take CHA-mod psychic damage each of their turns) or **Eternal Pact** (dropping to 0 HP but not outright killed restores half max HP + activates a Witch Implement as part of the same reaction; Witches Mark die always rolls max; no aging, immune to exhaustion).

## Last Stand (confirmed, 22nd class confirming of 23 ingested — standard permanent-death clause)

| Option | Effect |
|---|---|
| Hexstorm Manifestation | Chosen enemies within 60 ft get maxed-Hex-die Witches Mark; CON save (DC 10+PB+CHA) — fail: 8d10 necrotic + disadvantage on all rolls 1 minute; success: half damage, still rolls Hex die next roll. Enemies in the area can't heal or remove hex conditions for 1 minute |
| Spirit Tempest | 40 ft Spirit Tempest, 1 minute: entering/starting a turn there deals 6d10 force, WIS save (DC 10+PB+CHA) or frightened until it ends; allies inside get resistance to all damage + 2d8 HP/turn; on expiry, 8d10 radiant/necrotic burst to all enemies in the area |
| Avatar of the Eternal Coven | 1 minute: resistance to all damage, immune to frightened/charmed/stunned, unlimited Witches Mark, enemies within 30 ft take 4d10 psychic/turn, allies regain 2d10 HP/turn. On expiry: enemies within 30 ft CHA save (DC 10+PB+CHA) or take 10d10 necrotic/radiant (half on success); allies get temp HP (2×Witch level) + advantage on all rolls for 1 minute |

Twenty-second class confirming [[Last Stand]] as universal (of 23 per-class files ingested — [[Sorcerer]] remains the sole exception); all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). All three options use `10+PB+CHA`, three more data points for the `10+PB+ability` group.

## Class Reactions (confirmed, 23rd class confirming — clean shared-pool confirmation)

Draws from the shared **Class Reaction Pool** (PB uses per short or long rest); only 1 reaction per round, matching the universal rule.

| Reaction | Level | Trigger | Effect |
|---|---|---|---|
| Fateful Twist | 2nd | A hexed creature makes an attack roll | Disadvantage on that roll |
| Hex Ward | 2nd | A hexed creature targets the Witch with an attack | CHA save (DC 8+PB+CHA) or the attack redirects to another valid target within 30 ft |
| Hex-Turn | 7th | A hexed creature makes an attack roll | CHA save (DC 8+PB+CHA) — fail: redirect to another valid target within 30 ft; success: disadvantage on the attack. At 15th, a redirected target also has disadvantage on its save against the effect |

Hex Ward and Hex-Turn overlap in shape (both redirect a hexed creature's attack via a CHA save) but trigger differently — Hex Ward only fires when the Witch themself is the original target, Hex-Turn fires on any attack roll by a hexed creature.

## Mythology & Cultural Lore (from the Class Lore Compendium)

*Implement-Binders: Those Who Make Spirits Their Tools.*

Witches emerged from the discovery that spirits will inhabit objects if asked properly — a witch binding a spirit to an implement (cauldron, broom, candle, mirror, knife) creates a living tool, neither fully spirit nor fully object. Thessara the Hundred-Implements, who bound 100 different spirits into 100 different objects simultaneously, built a workshop that continued operating autonomously for decades after her death, fulfilling contracts she'd made with the bound spirits. The Second Age's discovery of the Witch's Mark — a curse-technique that finds hairline cracks in a target's defenses and applies calculated pressure until reality frays around them — made witches feared as curse-workers rather than mere spirit-negotiators. Ashkarra's Fall shattered thousands of implements and devastated coven-networks, but survivors learned to bind spirits fleeing the dimensional collapse itself.

**Source of Power (DM truth):** Spirit-binding accesses the [[Universal Glyphs]] — the same fundamental force governing relationship and connection that underlies [[Tamer]] partnerships and [[Reaper]] consciousness-harvest — creating a hybrid entity (neither spirit nor object) capable of effects neither component could achieve alone. The Witch's Mark works through what the Compendium calls "**Flaw Glyphs**," channeling cosmic imperfections (Pride, Wrath, Fear, Envy) directly into a target's existence — not a curse but an invitation for their own Flaws to manifest. *Flagged discrepancy:* like Shaman's "Spirit Glyphs," "Flaw Glyphs" does not appear among the five established Glyph layers (Primal, Universal, Elemental, Form, Personal) in [[How the Five Layers Shape the Creation World]]; left unresolved pending a source that clarifies whether Flaws constitute a sixth layer or are a Compendium-specific gloss on an existing one.

**Legendary figures:** Thessara the Hundred-Implements, whose bound-spirit workshop kept operating autonomously for decades after her own death.

*"I say: I negotiated. With spirits older than gods, wiser than wizards, more patient than clerics... My implements aren't tools—they're colleagues... My power isn't mine. It's negotiated, borrowed, temporarily granted by spirits who could refuse anytime. But they don't refuse. Because our partnership works."* — The Implement-Binder's Pact

## See also

- [[Welcome to FEARS]]
- [[Narrative Identity]]
- [[Spirit Debt]]
- [[Classes_Summary]]
- [[Class_breakdown]]
- [[Dynamic Combat System (DCS)]]
- [[FEARS Class Roster]]
- [[Momentum]]
- [[Damage Reduction]]
- [[Weapon Mastery]]
- [[Last Stand]]
- [[Class Reactions]]
- [[Universal Glyphs]]
- [[How the Five Layers Shape the Creation World]]
- [[FEARS MOC]]
