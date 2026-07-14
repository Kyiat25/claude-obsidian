---
type: concept
title: "Last Stand"
address: c-000102
created: "2026-07-12"
updated: "2026-07-12"
tags:
  - fears
  - ttrpg
  - combat
  - class-mechanic
status: developing
mocs:
  - "[[FEARS MOC]]"
complexity: intermediate
domain: fears
related:
  - "[[Barbarian]]"
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
  - "[[Class Reactions]]"
sources:
  - ".raw/Barbarian.md"
  - ".raw/Bard.md"
  - ".raw/Apothecary.md"
  - ".raw/Bender.md"
  - ".raw/Binder.md"
  - ".raw/Cleric.md"
  - ".raw/Druid.md"
  - ".raw/Fighter.md"
  - ".raw/Inventor.md"
  - ".raw/Investigator.md"
  - ".raw/Magus.md"
  - ".raw/Monk.md"
  - ".raw/Paladin.md"
  - ".raw/Ranger.md"
  - ".raw/Reaper.md"
  - ".raw/Rogue.md"
  - ".raw/Sangromancer.md"
  - ".raw/Shaman.md"
  - ".raw/Sorcerer.md"
  - ".raw/Tattooist.md"
  - ".raw/Warden.md"
  - ".raw/Warlock.md"
  - ".raw/Witch.md"
  - ".raw/Wizard.md"
confidence: high
---

# Last Stand

A universal per-class capstone mechanic — first sighted on [[Barbarian]]'s deep-dive and flagged there as possibly class-specific rather than universal; confirmed universal by [[Bard]]'s deep-dive, which uses near-identical framing and rules structure for a completely different class. **Confirmed 24/24 across the entire roster** — see the [[Sorcerer]] resolution below.

> [!note] Sorcerer's gap — resolved
> [[Sorcerer]]'s per-class deep-dive originally shipped with no Last Stand section. Ruled a genuine design gap (not an incomplete source), and closed with a GM-provided three-option table (Arcane Cataclysm, Well of Power, Wild Surge Unleashed — see the [[Sorcerer]] section below). This supersedes every earlier note on this page describing Sorcerer as "the sole exception" — those were accurate at the time of each ingest, before the gap was closed.

## DC-base: resolved as `10+PB+ability`

The canonical Last Stand save DC is **`10+PB+ability`** ([[Cleric]]'s Heaven's Gate, [[Apothecary]]'s Chemical Martyrdom, [[Inventor]]'s Null Field/Proximity Network, and now [[Sorcerer]]'s Arcane Cataclysm). Four classes' deep-dives had used `12+PB+ability` instead ([[Barbarian]]'s Last Laugh, [[Monk]]'s Empty Sun Technique, [[Paladin]]'s True Smite and Turn Fate, [[Rogue]]'s Death's Whisper — the prose previously misattributed "Last Laugh" to [[Bender]]; it's actually [[Barbarian]]'s), and [[Reaper]]'s three options had used a third base, plain `8+PB+ability`. **Ruled: all of these are transcription errors** — corrected to `10+PB+ability` in the tables below and on each class's own page.

> [!resolved] Warden's genuine gap, closed
> [[Warden]]'s The Earth Remembers named a save type (DEX or CON, per Prime Element) on all five variants but gave no DC anywhere. **Resolved by user ruling**: `10+PB+WIS`, matching Warden's own confirmed spellcasting DC and the canonical shape above.

> [!note] Ranger — not a gap, no save exists
> [[Ranger]]'s three Last Stand options were previously flagged alongside Warden's as "missing a DC," but on inspection none of them include a target saving throw at all — Hunter's Reckoning auto-hits/auto-crits, Call of the Wild summons creatures, Ghost of the Vale is pure buffs/auto-effects. There's no save to attach a DC to. **Ruled: not a gap** — Ranger's capstone kit simply doesn't use save-or-suffer effects, unlike most of the roster.

## Shared rules (confirmed identical across three sightings, with one confirmed exception)

Invoked when the character would be reduced to 0 hit points, rolls a death saving throw, or dies outright. A **free action** requiring no reaction or consciousness. Once resolved, the character **permanently dies** and cannot be returned by any means — true for [[Barbarian]], [[Bard]], and [[Apothecary]]'s options. Each class gets three named, flavor-appropriate options.

> [!note] Bender's Elemental Rebirth — ruled intentional exception
> [[Bender]]'s third Last Stand option, Elemental Rebirth, does not result in permanent death: the character transforms into an elemental for 24 hours, then reforms at 1 HP — **reverted to 1st level**. Instead of the death clause, it's gated by "usable only once per character's lifetime" plus the level reset. Ruled: intentional, not an error — the flavor (dissolving into and reforming from raw element) justifies surviving Last Stand, and the level-1 reversion functions as a soft-retirement lever, making permanent death or genuine retirement the more attractive choice for most players rather than a free escape hatch. The sole confirmed exception to the "permanently dies, cannot be returned" default every other option follows.

## Per-class options

### [[Barbarian]]

| Option | Effect |
|---|---|
| Final Rage | Persistent Rage 1 minute; can't drop below 1 HP; immune to all conditions including exhaustion; ignores non-0-HP-reducing kill effects |
| Last Laugh | Move + guaranteed critical hit; target CON saves (DC 10+PB+DEX) or bleeds for 2× character level force damage/turn for 5 minutes (ignores Legendary Resistance) |
| Wrath of the World Totem | Allies within 100 ft (5 min): resistance to B/P/S damage, +Rage Damage to their attack/spell damage, +CON mod to their AC |

### [[Bard]]

| Option | Effect |
|---|---|
| Best Kept Secret | Cast any spell from any class, up to highest known level, no components/slot cost; may maintain concentration beyond death for the spell's duration or 5 minutes, whichever is shorter |
| Friends on the Other Side | Reveal crucial intelligence about a foe (hideout, a credible enemy, a hidden motive/flaw) to up to CHA-modifier allies anywhere, delivered via their next dream |
| Swan Song | Allies who can hear the performance gain Bardic Inspiration dice equal to CHA modifier, which cancel all sources of disadvantage when used within 5 minutes |

### [[Apothecary]]

| Option | Effect |
|---|---|
| Chemical Martyrdom | All remaining concoctions detonate: 30 ft radius, 2d6 damage per remaining Reagent Point (mixed types); CON save (DC 10+PB+INT) — fail: full damage + poisoned + a random condition 1 min, success: half damage, no conditions. Area becomes toxic wasteland 1 hour |
| Emergency Metamorphosis | Transform into an Aberrant Hulk for 5 rounds: Large, 50 temp HP, +4 physical/−4 mental stats, 3 attacks/turn, regenerate 10 HP/turn, resistance to all physical damage; dies instantly and dissolves into toxic sludge when it ends |
| Panacea Sacrifice | Allies within 60 ft: heal 4d8+INT mod, end all diseases/poisons, remove one condition, 24-hour poison/disease immunity, advantage on all saves for 1 hour. The Apothecary's body crystallises into a Philosopher's Stone (resurrect once, or legendary crafting material) |

### [[Bender]]

| Option | Effect |
|---|---|
| Elemental Dissolution | Choose an affinity element; body dissolves into a 60 ft radius zone for 1 minute with element-specific effects (Air: 60mph winds + forced movement; Earth: difficult terrain + 2d10 bludgeoning/turn; Fire: 4d10 fire/turn + obscuring smoke; Water: deep water + forced pull) |
| Primordial Sacrifice | A willing ally within 60 ft gains full 18th-level Primordial Avatar state + the Bender's spells for 10 minutes; may permanently accept the transformation afterward for 3 Corruption Points |
| Elemental Rebirth | **Does not permanently kill the character** — transforms into an Air/Earth/Fire/Water Elemental for 24 hours, then reforms at 1 HP, **reverted to 1st level**. Usable once per character's lifetime instead of being gated by permanent death |

### [[Binder]]

| Option | Effect |
|---|---|
| Every Door at Once | Every remnant ever bound (not just currently bound) tears loose in a 30 ft radius; chosen creatures WIS save (Binding Save DC) or are frightened 1 min + take 6d8 psychic (half damage, no fear on success); allies in the radius gain temp HP = Binder level × 3 + advantage on their next save |
| The Debt Comes Due | One enemy within 60 ft damaged earlier this combat CON saves (Binding Save DC) or drops to 0 HP immediately; on success, takes damage = half current HP and is knocked prone |
| Unfinished Business | An ally within 30 ft immediately takes a full out-of-turn-order turn, and for that turn may use any one of the Binder's currently bound remnants' active abilities as if they were the Binder |

Binder's three options all reaffirm the standard permanent-death clause explicitly — confirms the clause is still the default (Bender's exception remains the only one seen).

### [[Cleric]]

| Option | Effect |
|---|---|
| Heaven's Gate | All enemies within 1000 ft DEX save (DC 10+PB+WIS) — fail: radiant damage = 2× character level, blinded+deafened 1 min, prone, drops held items; success: radiant damage = character level, prone. Ignores line of effect; no Legendary Resistance |
| Acts of God | Choose a domain-appropriate manifestation over a 100 ft radius, 5 minutes (Life reverses death — allies regain 2d8 HP/turn; War makes all ally attacks critical; Death turns the area into a necrotic wasteland, 2d10/turn to enemies) — worked out with the GM per the Cleric's specific deity |
| Martyr's Blessing | Allies within 100 ft (5 min): can't fail death saves, immune to necrotic/radiant/psychic damage, deal max damage on all rolls; any ally reduced to 0 HP regains 1 HP and keeps acting. The Cleric's body dissolves into divine light |

Sixth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception, same as Binder).

### [[Druid]]

| Option | Effect |
|---|---|
| Final Form | Immediately enter Wild Shape as any Beast, Plant, or Elemental with CR up to character level; lose all damage vulnerabilities; immune to hostile abjuration magic. Lasts up to 5 minutes |
| Ley Waste | Choose one Primordial cantrip/spell up to one level below highest slot; at the end of each turn for 1 minute, cast it without a slot/components (no concentration). Maintains one instance up to 4 additional minutes after death |
| Uncivilize | 5 minutes: all hostile creatures within 1000 ft have speed halved and can't teleport/plane-travel; all allies within 1000 ft gain *Freedom of Movement* |

Seventh class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Fighter]]

| Option | Effect |
|---|---|
| Die by the Sword | Move up to speed; make four times the normal Attack Action's attacks; immune to any effect stopping movement, preventing attacks, or reducing damage |
| Finest Hour | Allies within 100 ft at 0 HP healed to 1 HP; all allies within 100 ft gain temp HP = 4× Fighter level for 5 minutes; grants Second Wind to all allies in range |
| Warlord's Contingency | Grants Action Surge to all allies within 100 ft for 5 minutes; using it also ends one save-ending effect on the ally |

Eighth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Inventor]]

| Option | Effect |
|---|---|
| The Last Gadget | Choose one: Null Field (60 ft, suppresses magic 1 min; CON save DC 10+PB+INT or 6d10 lightning + Staggered until end of next turn); Golem Final Protocol (summon a CR-equal-to-level construct, 1 min); Proximity Network (60 ft, 8d10 thunder, DEX save DC 10+PB+INT for half) |
| Appreciation | Teleport all attunement items to chosen allies (no attunement required); all gadgets/infused items function at max potency for 5 minutes; allies may pass magic items between themselves within 60 ft |
| Deadman's Switch | INT-mod (min 2) allies each get a resource restoration or free move+advantage; plus one environmental trigger (Hazard Grid, Barrier Network, or Emergency Extraction) |

Ninth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Investigator]]

| Option | Effect |
|---|---|
| Exploit Mortality | Up to 3 creatures within 60 ft: Investigation check each; success grants vulnerability to all damage for 1 minute (bloodied targets auto-fail + suffer all Frailty effects at max); one attack against a chosen creature auto-crits, ignoring all DR/resistances |
| Revelation of the Veil | Allies within 60 ft gain Truesight 120 ft + advantage on all attacks/saves/checks for 1 minute; enemies within 30 ft WIS save or disadvantage on all rolls/saves for 1 minute |
| Inescapable Banishment | Fiends/undead/aberrations within 60 ft CHA save or banished to their native plane for 1d4 days, no Legendary Resistance |

Tenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Magus]]

| Option | Effect |
|---|---|
| Arcane Finality | Channel a damaging spell ≤5th level through the weapon; auto-hits and crits all creatures in its area/chosen targets; weapon attack +5d10 force damage plus a 1-minute burning mark (2d10/turn) |
| Blade of Continuum | For 5 minutes, every melee hit is an automatic critical + delayed damage next turn; enemies within 60 ft can't regain HP; on expiry, a shockwave deals 6d10 force damage in 30 ft |
| Arcane Aegis Unbroken | 40 ft Arcane Aegis, 1 minute: allies gain resistance to all damage + temp HP on first entry; enemy spells targeting the Magus or allies within 60 ft are reflected back |

Eleventh class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Monk]]

| Option | Effect |
|---|---|
| Empty Sun Technique | Move up to speed; two critical hits to one target in melee range; target WIS saves (DC 10+PB+WIS) or is placed under *imprisonment* (Slumber effect, the Monk's dead body is the focus); no Legendary Resistance |
| Into the Mist | Physical form evaporates; allies within 100 ft may teleport to a past long/short-rest location (DC 15 CON save for a short-rest one); enemies can't interfere |
| Transcendence | Invincible spectral image for 5 minutes; enemies within 10 ft disadvantaged, allies within 10 ft advantaged on all d20 rolls; fly 50 ft, pass through barriers; telepathy within 100 ft |

Twelfth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Paladin]]

| Option | Effect |
|---|---|
| Endless Mercy | Allies within 100 ft (5 min): regain HP = character level at the end of each Paladin turn, cured of poison/disease each turn, +3 to one chosen save |
| True Smite | Move up to speed; a critical hit to one target in melee range; target CHA saves (DC 10+PB+CHA) or banished to a chosen plane for 1d12+CHA mod months; no Legendary Resistance |
| Turn Fate | All enemies within 100 ft WIS save (DC 10+PB+CHA) or turned for 1 minute, evil-aligned at disadvantage; can't escape by taking damage; ignores line of effect |

Thirteenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception).

### [[Ranger]]

| Option | Effect |
|---|---|
| Hunter's Reckoning | Choose a target within 120 ft; for 5 minutes, all attacks/effects against it auto-hit and auto-crit, ignoring cover/invisibility/resistance; one immediate ranged attack against it |
| Call of the Wild | Summon 3 creatures (Beasts ≤CR4, Elementals ≤CR3, or Fey ≤CR3) within 30 ft for 5 minutes, immune to charm/fear/magical control |
| Ghost of the Vale | 5 minutes as a spectral guide: allies within 100 ft gain invisibility while not attacking/casting, plus advantage on Stealth/DEX saves; enemies within 30 ft disadvantaged on Perception/ranged attacks; flies 60 ft, passes through barriers |

Fourteenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). No explicit save DC anywhere in Ranger's options — **resolved by user ruling as not a gap**: none of the three call for a target saving throw at all (auto-hit, summon, buff/aura effects only), so there's nothing to attach a DC to.

### [[Reaper]]

| Option | Effect |
|---|---|
| Final Harvest | Dies immediately, consuming all Soul Tokens; creatures within 10 ft×tokens consumed CON save (DC 10+PB+CON) or take 1d10 necrotic/token (max 6d10) + matching max-HP reduction until a long rest; allies in the area gain temp HP = Reaper level×2 |
| Soul Anchor | Dies immediately; for 1 minute, spend 1 token/bonus-action to manifest as an untargetable spectral form (fly 30 ft, one weapon attack, can still Soul Harvest) until the Reaper's next turn each time |
| Death's Bargain | Dies immediately; one creature within 60 ft WIS saves (DC 10+PB+WIS) or drops to 0 HP, can't be stabilized for 1 minute, halved healing 24 hours; a chosen ally regains HP = Reaper level×2 and inherits all remaining Soul Tokens for 1 minute |

Fifteenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). DC corrected to the canonical `10+PB+ability` base — the original `8+PB+ability` in this document was a transcription error, not a genuine third base value.

### [[Rogue]]

| Option | Effect |
|---|---|
| Shadow's Requiem | Invisible, move up to speed; melee attacks against DEX-mod (min 1) enemies auto-hit and auto-crit; Surprised/Unaware targets also take Sneak Attack damage; dissolves into shadow |
| Escape Plan | Up to 5 willing allies within 60 ft teleport with the Rogue to a past long-rest location; allies gain advantage on DEX saves/Stealth for 5 minutes |
| Death's Whisper | All enemies within 100 ft WIS save (DC 10+PB+DEX) or frightened of the Rogue's allies for 5 minutes + psychic damage each turn within 30 ft of allies; enemies can't regain HP within 30 ft of the Rogue's spectral form for 5 minutes |

Sixteenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Death's Whisper adds a fourth data point to the `12+PB+ability` group.

### [[Sangromancer]]

| Option | Effect |
|---|---|
| Crimson Cataclysm | 60 ft explosion; all creatures CON save (DC = 10+PB+Vitae Strain÷3) — fail: 6d10+1d10/5 Vitae Strain, stunned; success: half, not stunned. Allies within 60 ft heal 2×Sangromancer level; leaves a Crimson Relic for one ally to consume |
| Ossuary Immortal | Becomes an animated skeleton for 1 minute: resistance to all but radiant/bludgeoning, immune poison/disease/exhaustion, spells deal max damage; each spell cast extends the duration; collapses to dust permanently after |
| Blood Legacy | Allies within 60 ft (10 min): temp HP, necrotic-lifesteal hits, advantage vs frightened/charmed, +2 AC. Body becomes a Blood Font (AC 10, 50 HP, 10 min) allies can draw HP from; destroying it ends the benefits |

Seventeenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Crimson Cataclysm's DC (`10+PB+Vitae Strain÷3`) is a **fourth distinct Last Stand DC shape**, the first scaling off a class resource total rather than an ability modifier.

### [[Shaman]]

| Option | Effect |
|---|---|
| Spiritstorm Manifestation | 40 ft Spiritstorm, 1 minute: enemies CON save (DC 10+PB+WIS) — fail: 8d10 force + blinded 1 minute; success: half, not blinded. 2d10/turn to enemies in the area; allies gain resistance to all damage + advantage on saves |
| Totemic Ascendance | Active Totems persist, indestructible, 5 minutes; allies within 60 ft of them gain temp HP, advantage on attacks/saves/checks, and 1d10 HP/turn; all Totems activate immediately |
| Ancestral Fury | 1 minute as an incorporeal spectral warrior, fly 60 ft; melee spell attack vs. any number of creatures within 30 ft, 6d10 radiant/necrotic each; enemies within 30 ft WIS save (DC 10+PB+WIS) each turn or frightened; expiry deals a 4d10 force burst |

Eighteenth class confirming Last Stand as universal; all three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Both DC-bearing options use `10+PB+WIS`, two more data points for the `10+PB+ability` group.

### [[Sorcerer]]

| Option | Effect |
|---|---|
| Arcane Cataclysm | 40 ft radius explosion centered on self; chosen creatures DEX save (DC 10+PB+CHA) — fail: 10d10 force damage + prone; success: half damage, no prone. Destroys terrain/unreinforced objects in range |
| Well of Power | For 1 minute, allies within 100 ft may cast any of the Sorcerer's known spells using the Sorcerer's remaining spell slots, auto-upcast to max level, using the Sorcerer's CHA mod for save DC/attack rolls |
| Wild Surge Unleashed | All creatures within 60 ft (allies included) immediately roll on the Wild Magic Surge table (one reroll per creature allowed); the area becomes a Wild Magic Zone for 10 minutes — any spell cast there triggers another surge roll |

Gap closed post-ingest (see the resolved note near the top of this page) rather than sourced from the original deep-dive. Reaffirms the standard permanent-death clause. Arcane Cataclysm's DC (`10+PB+CHA`) matches the canonical base.

### [[Tattooist]]

| Option | Effect |
|---|---|
| Ink of Defiance | 30 ft blast; hostiles CON save (DC 10+PB+CON) — fail: 10d10 acid+force, blinded until end of next turn; success: half, not blinded. Allies in the blast gain +3 Momentum |
| Last Stroke of the Artist | Cast any known spellbanger spell instantly, ignoring components/level/casting time, at its highest possible level; permanently dies after it resolves even if the spell would heal/stabilise |
| Eternal Canvas | Up to 3 allies within 30 ft each receive a tattoo/active spellbanger for 10 minutes; each gains +2 Evasion/saves and +2 Momentum; tattoos fade to scars when the effect ends |

All three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Ink of Defiance's DC (`10+PB+CON`) adds another data point to the `10+PB+ability` group.

### [[Warden]] — DC gap resolved

| Option | Effect |
|---|---|
| The Earth Remembers | 60 ft terrain transformation matching the Prime Element (e.g. Earthen Bulwark: DEX save, DC 10+PB+WIS, or 8d10 bludgeoning + prone; Unrelenting Storm: DEX save, DC 10+PB+WIS, for half of 8d10 lightning, then 3d10/round for 1 minute) |
| Hold the Line | Stays at 0 HP for 1 minute, immune to HP-damage death; allies within 30 ft gain +3 DR (stacking); each death-save success bursts 2d10 Prime Element damage to enemies within 10 ft; dies when the minute ends or a third death save fails |
| The Storm Breaks | 3 rounds as a raw elemental vessel: Elemental Presence radius 60 ft dealing 3d10; attacks auto-hit and auto-max; immune to all damage; can't be moved/charmed/frightened/controlled |

All three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). The Earth Remembers previously named a saving throw type without ever giving its DC, on any of its five element variants — **resolved by user ruling** to `10+PB+WIS`, matching Warden's own confirmed spellcasting DC and the canonical `10+PB+ability` shape used everywhere else in the roster.

### [[Warlock]]

| Option | Effect |
|---|---|
| Eldritch Oblivion | 60 ft blast; chosen creatures CON save (DC 10+PB+CHA) — fail: 12d10 necrotic + restrained 1 minute; success: half, not restrained. Area becomes magical darkness for 1 minute |
| Pactbound Sacrifice | Up to 5 allies within 60 ft (1 min): temp HP, +2d10 force on hits, auto-succeed next save. Up to 5 enemies: 2d10 psychic/turn; WIS save (DC 10+PB+CHA) or frightened of the Warlock's allies |
| Dark Concordance | Summon a CR 15 Avatar of the Patron within 30 ft, acting immediately after the Warlock, 1 minute, immune to charm/fear/banishment; on expiry, the area is corrupted for 1 hour |

All three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Both DC-bearing options use `10+PB+CHA`, two more data points for the `10+PB+ability` group.

### [[Witch]]

| Option | Effect |
|---|---|
| Hexstorm Manifestation | Chosen enemies within 60 ft get maxed-Hex-die Witches Mark; CON save (DC 10+PB+CHA) — fail: 8d10 necrotic + disadvantage on all rolls 1 minute; success: half damage. Enemies in the area can't heal or remove hex conditions for 1 minute |
| Spirit Tempest | 40 ft Spirit Tempest, 1 minute: entering/starting a turn deals 6d10 force, WIS save (DC 10+PB+CHA) or frightened; allies inside get resistance to all damage + 2d8 HP/turn; on expiry, 8d10 radiant/necrotic burst to enemies |
| Avatar of the Eternal Coven | 1 minute: resistance to all damage, immune to frightened/charmed/stunned, unlimited Witches Mark, enemies take 4d10 psychic/turn, allies regain 2d10 HP/turn. On expiry: enemies CHA save (DC 10+PB+CHA) or take 10d10 necrotic/radiant; allies get temp HP + advantage on all rolls for 1 minute |

All three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). All three options use `10+PB+CHA`, three more data points for the `10+PB+ability` group.

### [[Wizard]] — final class, closes the per-class deep-dive pass

| Option | Effect |
|---|---|
| The Final Theorem | Cast any spellbook spell (prepared or not, any circle) with no slot/components, as a 9th-circle slot; concentration persists up to 5 minutes after death |
| Arcane Legacy | INT-mod (min 1) allies within 60 ft each receive shared spell knowledge, castable once each within 24 hours using the Wizard's DC/attack mod |
| Null Field | 60 ft field, 5 minutes: spells ≤5th circle auto-counterspelled; ≥6th circle requires an INT save (DC 8+PB+INT); hostile concentration ends immediately; collapses for 10d10 force damage (half on save) |

All three options reaffirm the standard permanent-death clause (no exception — Bender remains the lone confirmed exception). Null Field's DC (`8+PB+INT`) is a **genuine third DC base**, distinct from the canonical `10+PB+ability` — unlike [[Reaper]]'s matching `8+PB+ability` shape (ruled a transcription error and corrected above), Wizard's Null Field is a capstone counterspell-style area effect rather than a single-target save, so it's left as-is pending confirmation rather than assumed to be the same kind of error. With Wizard, every FEARS class has now been checked against the Last Stand mechanic: all 24 confirm it, none contradict it (Bender's Elemental Rebirth remains the sole death-clause exception, still pending a ruling).

## See also

- [[Barbarian]]
- [[Bard]]
- [[Apothecary]]
- [[Bender]]
- [[Binder]]
- [[Cleric]]
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
- [[Class Reactions]]
- [[FEARS MOC]]
