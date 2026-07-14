---
type: concept
title: "Weapon Mastery"
address: c-000089
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
  - "[[Weapon Mastery System]]"
  - "[[Weapon Skills]]"
  - "[[Momentum]]"
  - "[[Damage Reduction]]"
  - "[[Fighter]]"
  - "[[Monk]]"
  - "[[Bender]]"
  - "[[Binder]]"
sources:
  - "[[Weapon Mastery System]]"
  - ".raw/Binder.md"
---

# Weapon Mastery

The martial-class tactical engine: each mastered weapon grants access to a **Weapon Skill** ([[Weapon Skills]]) usable once per turn on a hit.

## Gaining mastery

Every martial/weapon-focused class starts with at least one mastered weapon (from a weapon they're already proficient with). Fighter starts with two of choice; most others start with one, scoped by class flavor (e.g. Rogue: one finesse/ranged weapon; non-martial casters: one simple weapon).

**Progression** happens through combat excellence: score a class-tier-dependent number of critical hits with a weapon, then spend 1 week of downtime training with it. Proficiency isn't required in advance — critting your way to mastery grants proficiency retroactively.

| Class tier | Simple weapon | Martial weapon |
|---|---|---|
| Fighter | 1 crit | 1 crit |
| Full Martials (Barbarian, Ranger, Paladin, Monk, Rogue, Warden, Reaper, Bender, Inventor, Investigator) | 2 crits | 3 crits |
| Half-Martials (Magus, Bard, Druid, Apothecary) | 3 crits | 4 crits |

> [!note] Tattooist and Shaman corrected to Non-Martials — resolved, deep-dive wins
> This table originally listed both as Half-Martials. [[Tattooist]]'s deep-dive states outright: "Tattooists do not gain Weapon Mastery. Your power flows through ink and design, not through martial perfection." [[Shaman]]'s deep-dive never mentions Weapon Mastery anywhere in its level table or core features. Ruled: the per-class deep-dive is authoritative over the old table — both are moved to the Non-Martials row below rather than kept as an unresolved conflict.
| Non-Martials (Sangromancer, Witch, Wizard, Sorcerer, Warlock, Tattooist, Shaman, Binder) | 5 crits | 5 crits (never via normal progression — see below) |

**[[Sangromancer]]'s per-class deep-dive confirms this row by omission**: no Weapon Mastery feature appears anywhere in the document, consistent with its Non-Martials listing above rather than contradicting it. **[[Sorcerer]]'s deep-dive confirms it explicitly rather than by silence**: "Sorcerers do not gain Weapon Mastery. Your power is entirely internal. Weapons are tools you carry, not extensions of your identity." The strongest possible confirmation of a Non-Martials row this cluster has produced — a direct statement rather than an inferred absence. **[[Warlock]]'s deep-dive confirms it by omission a second time** (no Weapon Mastery feature anywhere in the document) — this generic Patron document also never names Hexblade specifically, so it doesn't touch the existing Hexblade-as-Half-Martial exception already documented above. **[[Witch]]'s deep-dive confirms it a third time** by the same consistent silence. **[[Wizard]]'s deep-dive confirms it explicitly, twice over**: "Wizards do not gain Weapon Mastery. Your tools are spells" appears in both the flavor introduction and the Starting Equipment section — the same explicit-denial shape as [[Sorcerer]], not a silent gap. **[[Tattooist]]'s explicit denial** ("Tattooists do not gain Weapon Mastery") and **[[Shaman]]'s silent gap** were both originally table conflicts (listed as Half-Martials); ruled resolved per the deep-dive-wins policy and moved into this row.

> [!resolved] Binder added to Non-Martials — user ruling
> [[Binder]]'s deep-dive was previously read as total exclusion from Weapon Mastery entirely (rather than merely an unknown profile), since it never mentions the subsystem and every Remnant ability is a spell attack. **Resolved**: that same silent-omission shape is exactly how Sangromancer, Warlock, and Witch's rows above were confirmed as Non-Martials, not read as total exclusion — there's no principled reason to treat Binder's identical silence differently. Binder's own proficiency list ("Weapons — simple") and starting equipment (a simple melee or ranged weapon option) match this row precisely. Binder joins the Non-Martials tier: 5 crits with a simple weapon unlocks Weapon Mastery same as any other class here, martial weapon mastery only via the [[Weapon Mastery Feats|Weapon Adept feat]] — it'll rarely come up given Binder's kit runs entirely on Remnant spell attacks, exactly as true for Wizard or Sorcerer.

No hard cap on total masteries; most characters land at 3-6 over a campaign. Non-martial casters can only ever gain *simple* weapon masteries through normal play; martial weapon mastery for them requires the [[Weapon Mastery Feats|Weapon Adept feat]]. Hexblade Warlock is an explicit exception, treated as Half-Martial (one martial weapon mastery, 3/4-crit progression).

**[[Inventor]]'s per-class deep-dive confirms its Full Martials row with zero drift**: 2 crits for simple weapons, 3 for martial, exactly matching the table above. **[[Paladin]]'s per-class deep-dive confirms the same row with zero drift** for its own entry. **[[Ranger]]'s per-class deep-dive confirms it a third time.** **[[Reaper]]'s per-class deep-dive confirms it a fourth time**, **and [[Rogue]]'s confirms it a fifth time**, **and [[Warden]]'s confirms it a sixth time** (though Warden's mastery grant lands at 3rd level rather than 1st, later than every other Full Martial so far) — and adds a new detail no other class has stated: a **scheduled +1 weapon at 3rd/7th/11th/15th level**, layered on top of the standard crit-based unlock system rather than replacing it. Worth checking whether this scheduled-grant pattern is Reaper-specific or a universal rule other classes' deep-dives simply haven't mentioned yet.

**[[Binder]] is absent from this table entirely** — not an oversight, apparently. Binder's own per-class deep-dive never mentions Weapon Mastery once across its full text; its proficiencies are simple weapons only, and every Remnant ability is a spell attack rather than a weapon attack. Strong evidence, not explicit confirmation, that Binder doesn't participate in this subsystem at all, unlike every other ingested class.

## Using mastery

Declare a Weapon Skill **after confirming a hit, before rolling damage** (unless the skill states otherwise) — once per turn, universal rule.

### Fighter exception: multi-mastery rounds

Fighters may use **2-4 Weapon Skills in a single round**, one per available action slot: Attack Action, Bonus Action (if the skill has a BA version), Reaction (if it has one), and Action Surge (treated as a second Attack Action). Never the same skill twice; never without spending the matching action. This is the exact mechanic behind [[Fighter]]'s "highest decision density" identity. **Confirmed with zero drift** by [[Fighter]]'s own per-class deep-dive, including the 1-crit-per-weapon mastery progression from the table above.

## Momentum integration

Many skills scale up at +2 or +3 [[Momentum]] (e.g. Hamstring gains Disadvantage at +3, Bleed's damage increases). Some skills can grant +1 Momentum at GM discretion (used with advantage, chained after another skill, or at a pivotal moment) — a guideline, not automatic; individual skills state explicitly if they grant it. Momentum still can't exceed +3 by any means through this route.

## Monk & Bender: Technique Point engine

**Flow Strike** (Monk & Bender only): move 5 ft without provoking on any hit; at +3 Momentum, regain 1 Technique Point. Explicitly designed to fix Monk/Bender resource starvation. See [[Monk]] and [[Bender]] — this is the first source to connect Bender to Technique Points at all.

> [!contradiction] Monk's own deep-dive never mentions Flow Strike — introduces Ki Flow instead
> [[Monk]]'s per-class deep-dive never uses the name "Flow Strike." Instead it describes **Ki Flow**: regain 1 TP on beginning a turn at +3 Momentum (2nd level), or at +2 or higher (7th level) — a **turn-start** trigger, not the on-hit trigger Flow Strike describes. Both link Technique Point income to a high-Momentum state, so they may be the same underlying mechanic described two different ways, or two genuinely separate income sources — not resolved either way. The same shape of silence as [[Bender]]'s own deep-dive never mentioning Weapon Mastery/Flow Strike at all; between the two, no per-class source has yet independently confirmed Flow Strike exactly as [[Weapon Mastery System]] describes it.

## DCS integration

- **DR reduction**: skills like Shatter Guard directly reduce [[Damage Reduction|DR]].
- **Positioning control**: Push/Pin/Sweep-type skills alter enemy placement.
- **Boss safety valves**: prone/movement-0/Momentum-drain effects apply once per turn max, don't stack across attackers, and carry save protections — bosses can't be permanently locked down.

## Class integration summary

Fighter is the "weapon master supreme" — fastest progression (1 crit for any weapon), most masteries, multi-skill rounds. Every other class gets a short recommended-weapons-and-synergy note in the source (e.g. Barbarian: Greatsword/Greataxe/Maul, Momentum-friendly masteries feeding Rage; Ranger: bow masteries define battlefield control; Rogue: Bleed/Hamstring substitute for constant Sneak Attack setup). Full class-by-class detail lives in the source document rather than duplicated per-class here — see [[Weapon Mastery System]] for the complete table.

## See also

- [[Weapon Mastery System]]
- [[Weapon Skills]]
- [[Momentum]]
- [[Damage Reduction]]
- [[Fighter]]
- [[Inventor]]
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
- [[Bender]]
- [[Binder]]
- [[FEARS MOC]]
