---
type: concept
title: "Initiative"
address: c-000093
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
  - "[[Initiative System]]"
  - "[[Seize the Moment]]"
  - "[[Momentum]]"
  - "[[Breaking Points]]"
  - "[[Enemy Rally]]"
  - "[[Injury System]]"
  - "[[Called Shot]]"
sources:
  - "[[Initiative System]]"
---

# Initiative

"Battle is rhythm. The first strike is chaos, but soon the clash settles into a tide." Reimagines turn order as a consequence of the fight itself rather than one fixed roll.

## Round 1 — traditional order

Everyone rolls `1d20 + DEX modifier`, standard 5E style; surprise rounds function normally. Preserves the value of ambushers, scouts, and opening-alpha spellcasters — chaos and setup only, not the system's real signature.

## Round 2+ — Side Initiative

1. **Momentum check**: average each side's [[Momentum]] Score across active combatants. Higher average acts first.
2. **Tiebreaker**: if equal, each side's leader (highest-CR for enemies, highest-Focus-modifier PC) rolls `1d20 + Focus modifier`; higher wins.
3. **Group action**: the winning side takes all their turns in any order before the other side acts — full intra-round coordination.

**Routing guardrail**: creatures that routed or fled (failed [[Breaking Points]] or chose to flee) are removed from the average immediately — a single rout can't drag a whole side's Momentum average down and spiral into permanent lockout.

## Special cases

- **Legendary creatures**: once per combat, may declare they act first regardless of average Momentum.
- **Morale collapse**: if every remaining member of a side has failed a Breaking Point check, that side automatically acts second each round until a successful [[Enemy Rally]] resets at least one combatant to 0+ Momentum.
- **Enemy Auto-Rally**: a Bloodied leader's forced Rally attempt (see [[Bloodied and Bruised]]) directly feeds the next round's initiative comparison if it succeeds.

## System interactions

| System | Interaction |
|---|---|
| Momentum | Average MS is the initiative comparison itself |
| [[Seize the Moment]] | Lets a PC override the comparison with a Focus check |
| Breaking Points | Enemy routs lower the enemy average, improving PC odds |
| Enemy Rally | A successful Rally can swing the following round |
| [[Injury System]] | Major/Critical Injuries reset or drain Momentum, which feeds initiative |
| [[Called Shot]] | Crippling an enemy leader's Focus (throat, arm) weakens their Leadership roll |

## Monster hooks

- **Dragons/Giants**: at +4/+5 Momentum, almost always act first unless the party drains their average via Called Shots.
- **Undead/Constructs**: immune to morale mechanics entirely — can't Rally, can't be broken; initiative shifts only through raw Momentum.
- **Fiends**: infighting after a leader's death may cause internal Momentum penalties; competing Fiends can cancel each other's gains at GM discretion.
- **Celestials**: almost always succeed Rally attempts, keeping their average high and their initiative priority stable.

## See also

- [[Initiative System]]
- [[Seize the Moment]]
- [[Momentum]]
- [[Breaking Points]]
- [[Enemy Rally]]
- [[Injury System]]
- [[Called Shot]]
- [[FEARS MOC]]
