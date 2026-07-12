---
type: source
title: "FEARS Character Framework"
address: c-000038
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - character-sheet
  - crunch
status: developing
mocs:
  - "[[FEARS MOC]]"
related:
  - "[[FEARS Character Sheet]]"
  - "[[FEARS Combat System]]"
  - "[[Whisper Points]]"
  - "[[Mental State]]"
  - "[[Called Shot]]"
  - "[[Sanity]]"
  - "[[Focus]]"
  - "[[Corruption]]"
  - "[[Translation Matrix]]"
sources:
  - ".raw/FEARS Character Framework.md"
source_type: article
author: ""
date_published: ""
url: ""
confidence: high
key_claims:
  - "First source in this cluster to give actual dice formulas: Evasion = 1d20 + DEX + PROF; Whisper Points = 3 + Focus Mod + half Sanity Mod (rounded down implied, not stated explicitly)."
  - "Damage Reduction is per body part, not a single armor value, and combos with Called Shots (targeting head/torso/arms/legs for tactical effects)."
  - "Mental Resilience uses a four-stage tracker independent of raw Sanity/Focus/Corruption numbers: Stable -> Frayed -> Deranged -> Broken."
  - "Reactions (counterattack, disarm, bash, block) are free but require intentionally forgoing evasion on an incoming hit."
---

# FEARS Character Framework

Describes the **[[FEARS Character Sheet]]**, the physical/digital tool players use to track the seven systems introduced across the FEARS sources so far. Frontmatter marks it `status: wip`, same caveat as the other two sources in this cluster.

## What it resolves from earlier sources

This is the first FEARS source with real numbers. It closes gaps [[FEARS MOC]] had flagged as open:

- **Evasion formula**: `1d20 + DEX + PROF` — the actual roll behind [[FEARS Combat System]]'s "Evasion" concept, previously described only narratively.
- **Whisper Points formula**: `3 + Focus Mod + ½ Sanity Mod` — the first numeric grant rule for [[Whisper Points]], previously "earned through exceptional roleplay" with no formula at all.
- **Damage Reduction detail**: DR is tracked **per body part** (head/torso/arms/legs), not as one armor number — new detail for [[FEARS Combat System]].
- **Quick Conversion Guide (5E to FEARS)**: a partial, concrete version of what [[Translation Matrix]] only gestured at. Still not a full attribute-mapping table, but Evasion and Whisper Points now have worked conversion steps.

## What's genuinely new (not in earlier sources)

- **[[Called Shot]]** — targeting specific body parts in combat for tactical effects (source typos this as "Called shotss"/"Called shots" inconsistently; normalized here).
- **[[Mental State]]** — a four-stage tracker (Stable → Frayed → Deranged → Broken) layered on top of the Sanity/Focus/Corruption numbers from [[A World that Watches]].
- **Reactions** — free counterattack/disarm/bash/block options, but only unlocked by intentionally taking a hit instead of evading. Elaborates [[FEARS Combat System]]'s "Active Defense" and "Counterattack Opportunities," which were named without this detail.
- Confirms **Corruption Score (CS)** as the formal abbreviation for [[Corruption]], and **SAN**/**FOC** for [[Sanity]]/[[Focus]].

## Editorial note

Some internal wikilink text in the source is typo'd or pluralized inconsistently ("Evasions," "Damage Reductions," "Called shotss") — treated as the same concepts as [[FEARS Combat System]] rather than split into duplicate pages, per the vault's no-duplicate-pages rule. The `01_Rules/06_Optional/The Whisper Engine` link recurs here exactly as in [[A World that Watches]] — still undefined by any source ingested so far.

## See also

- [[FEARS Character Sheet]]
- [[FEARS Combat System]]
- [[Whisper Points]]
- [[Mental State]]
- [[Called Shot]]
- [[FEARS MOC]]
