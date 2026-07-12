---
type: source
title: "Dynamic Combat System (DCS)"
address: c-000072
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
  - crunch
status: developing
mocs:
  - "[[FEARS MOC]]"
related:
  - "[[FEARS Combat System]]"
  - "[[Evasion]]"
  - "[[Damage Reduction]]"
  - "[[Called Shot]]"
  - "[[Shields]]"
  - "[[Tactical Reactions]]"
  - "[[Momentum]]"
  - "[[Combat Flow]]"
  - "[[Injury System]]"
sources:
  - ".raw/DCS.md"
source_type: article
author: ""
date_published: ""
url: ""
confidence: high
key_claims:
  - "Gives the full crunch layer for combat that every earlier FEARS source described only narratively: exact Evasion formulas (Dodge vs Brace), per-armor-type Damage Reduction values, Called Shot penalty/save tables, and Momentum gain/loss event tables."
  - "Explicitly self-identifies as a summary/hub document — it repeatedly defers to separate, deeper source files for Momentum and the Injury System ('For full Momentum rules... see the Momentum document'). Combat Flow.md has since been ingested and confirmed this pattern: the deeper source matched DCS's summary with zero drift, just more granularity. Several other subsystems this document touches still have uningested deeper files (Momentum.md, Injury System.md, Called Shots.md, Evasion.md, Damage Reduction.md, Weapon Mastery System.md)."
  - "Confirms the five design pillars: Active Defence, Armour as Soak not Hit Chance, Momentum as Rhythm, Called Shots as Tactical Depth, Risk and Reward."
---

# Dynamic Combat System (DCS)

The crunch-authoritative combat document. [[FEARS Combat System]] (from [[Welcome to FEARS]], the very first source ingested into this cluster) described this system narratively — "Evasion + Damage Reduction," "Momentum ranging -2 to +3" — without formulas. This source supplies nearly everything that page's "What's still not specified" section was waiting for.

## Structure

This is itself a **summary/hub document**, not the deepest layer. It says so directly: "For full Momentum rules including monster scaling, epic tiers, the Exhaustion interaction, and the optional Swing Guardrail, see the **Momentum** document. The summary below covers core DCS interactions." **Confirmed by example**: [[Combat Flow]]'s deeper source has since been ingested — it expanded the summary's 9 steps into 12 with zero factual drift, just more granularity (and one genuine correction: Tactical Reactions' combined "Trap/Disarm" row was actually two distinct reactions). The same pattern likely applies to Called Shots, Injury System, Evasion, and Damage Reduction — still **separate, uningested files** in `.raw/` (`Momentum.md`, `Injury System.md`, `Called Shots.md`, `Evasion.md`, `Damage Reduction.md`). Every subsystem page from this ingest remains marked as a **DCS-level summary** until its deeper source is checked.

## What it resolves (previously "not specified")

- **Evasion formula**: two modes, Dodge (`1d20 + DEX + PROF`) and Brace (`1d20 + STR + PROF`), full outcome table (Nat 20 / clean win / tie / full hit / attacker Nat 20). See [[Evasion]].
- **Damage Reduction values**: Light/Medium/Heavy armor tables per body part, Total DR vs. Called-Shot-only DR distinction, layering rules, critical-hit DR halving. See [[Damage Reduction]].
- **Called Shot accuracy tradeoff**: full penalty table (Head −5, Arms −2, Legs −2, Torso 0; advanced: Eye −7, Hand −4, Throat −6, Wing −3, Tail −3), detection mechanic via Passive Perception, saving throws. See [[Called Shot]].
- **Momentum's exact modifier math**: full gain/loss event tables, score-to-effect table (+3 to −2), level scaling, resets, class exceptions (Barbarian, Monk). See [[Momentum]].

## What's genuinely new (not previously hinted at anywhere)

- **[[Shields]]** as active reaction-based tools (Block, Deflect, Bash) with optional Shield Stances.
- **[[Tactical Reactions]]** — the full menu of options unlocked by forgoing Evasion (Counterattack, Magic Attack, Trap/Disarm, Grapple Back, Trip/Sweep, Tactical Retreat, Weapon Bind, Intimidating Glare), elaborating [[FEARS Combat System]]'s vague "Counterattack Opportunities."
- **[[Combat Flow]]** — an explicit turn sequence (12 steps in the fully-ingested version; DCS's own summary gave 9).
- **[[Injury System]]** (summary) — Constitution Save vs. Grit Save mitigation choice, and a PC/monster split: player characters use Injury only, monsters additionally use "Bloodied" effects.
- **Class Hooks** — direct DCS integration notes for 10 classes: Rogue, Monk, Ranger, Barbarian, Paladin, Magus, Investigator, Shaman, Witch, Fighter. Applied to each class's page.

## Universal rule

DR cannot be reduced below 0 by any combination of effects.

## See also

- [[FEARS Combat System]]
- [[Evasion]]
- [[Damage Reduction]]
- [[Called Shot]]
- [[Shields]]
- [[Tactical Reactions]]
- [[Momentum]]
- [[Combat Flow]]
- [[Injury System]]
- [[FEARS MOC]]
