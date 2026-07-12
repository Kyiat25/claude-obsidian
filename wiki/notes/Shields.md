---
type: concept
title: "Shields"
address: c-000075
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
status: developing
mocs:
  - "[[FEARS MOC]]"
complexity: basic
domain: fears
related:
  - "[[Dynamic Combat System (DCS)]]"
  - "[[Damage Reduction]]"
  - "[[Tactical Reactions]]"
sources:
  - "[[Dynamic Combat System (DCS)]]"
  - ".raw/Reaction-based_opportunities.md"
---

# Shields

Active reaction-based tools, not passive DR bonuses.

## Types

| Shield | DR Bonus | Evasion | Mode | Notes |
|---|---|---|---|---|
| Small | +2 DR (arm) | +2 to Evasion | Dodge or Brace | Combines with both defence modes |
| Standard | +3 DR (arm) | none | Dodge or Brace | Balanced |
| Great | +5 DR (arm, always-on) | none | Brace only | Cannot Dodge; Stealth disadvantage unless heavy-armor proficient |

## Shield reactions

- **Block** — +3 DR against one incoming attack, declared after the hit but before damage.
- **Deflect** — contested Strength (Athletics) roll; success negates the attack entirely.
- **Bash** — reaction dealing 1d6 + STR bludgeoning and a 5 ft push attempt.

### Clarification (from Reaction-Based Opportunities)

The Great shield's Types-table entry previously read "+5 DR (all locations while raised)," conflating two separate effects. `.raw/Reaction-based_opportunities.md` states them distinctly: the base **+5 DR is always-on and arm-only** while the shield is wielded; the **all-locations** extension only happens when Block is actively used as a reaction (adding its own +3 DR to every location, not just the arm, for that one attack). Table corrected above to reflect this — read as a precision fix to existing wording, not a new contradiction.

## Optional: Shield Stances

Consumes the turn's movement; one active at a time (Fighter/Paladin may adopt via bonus action instead):

- **Defensive Brace** — +1 Momentum on Block; attacker disadvantage if you haven't moved.
- **Offensive Press** — advantage on Bash, +2 bludgeoning damage, no Dodge.
- **Bulwark Wall** — allies behind you get +2 DR vs. ranged; no Dash/movement reactions.
- **Interceptor's Flow** — extra shield reaction per round; both failing costs all Momentum and −2 Evasion until next turn.

## See also

- [[Dynamic Combat System (DCS)]]
- [[Damage Reduction]]
- [[Tactical Reactions]]
- [[FEARS MOC]]
