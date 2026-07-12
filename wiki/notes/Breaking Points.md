---
type: concept
title: "Breaking Points"
address: c-000082
created: "2026-07-11"
updated: "2026-07-11"
tags:
  - fears
  - ttrpg
  - combat
status: developing
mocs:
  - "[[FEARS MOC]]"
complexity: intermediate
domain: fears
related:
  - "[[Bloodied Breaking Points Rally]]"
  - "[[Bloodied and Bruised]]"
  - "[[Enemy Rally]]"
  - "[[Sanity]]"
  - "[[Momentum]]"
sources:
  - "[[Bloodied Breaking Points Rally]]"
---

# Breaking Points

Enemy-only Sanity-based morale checks (see [[Bloodied Breaking Points Rally]]'s status note). Triggered by leader death or casualty thresholds; failure means rout.

## Triggers

| Trigger | DC |
|---|---|
| Enemy leader dies (or highest-CR enemy, if no leader) | current casualty DC +2 |
| 25% enemy casualties | 15 |
| 50% enemy casualties | 20 |
| 75% enemy casualties | 25 |

Casualties = dead, unconscious, routed, or fled. Check: `1d20 + Sanity modifier` vs. the DC.

## Outcomes

| Roll | Result |
|---|---|
| Success | Fights on, −1 Momentum |
| Failure | **Routs** — panics, flees, or surrenders (see Monster-Type Behaviours below) |
| Nat 1 | Immediate rout + allies within 30 ft roll their next check at Disadvantage |
| Nat 20 | Immune to Breaking Points rest of combat, +1 Momentum |

**Momentum floor**: a failed Breaking Point locks the enemy at **−2 Momentum minimum** until a successful [[Enemy Rally]] resets it. Routed enemies drop out of Side Initiative entirely.

## Monster-type behaviours

| Type | Rout behavior | Rally traits |
|---|---|---|
| Humanoids / Beasts | Flee or surrender; leader-reliant | Standard rules |
| Fiends | Turn on each other after a leader dies | Rarely Rally |
| Giants / Dragons | Rarely rout; rage or Death Throes instead | High Focus, hard to break |
| Celestials | Almost always succeed Rally, inspire allies automatically | Legendary Rally traits |
| Undead / Constructs | **Immune** — no morale exists | N/A |
| Aberrations | Unpredictable — random attacks, freeze, teleport | Sanity-based, erratic |
| Fey | May vanish or shift allegiance | Trickster Rally, unreliable |

## Epic-tier note

Leaders with Sanity 20+ are immune to casualty-triggered Breaking Points entirely.

## Optional variant: PC Breaking Points

Off by default (see [[Bloodied Breaking Points Rally]]). If a table opts in: triggers are party-leader-down (DC 12), 50% party incapacitated (DC 15), or GM-declared catastrophic events (DC 10-20). PCs never auto-rout — failure costs −1 Momentum and forces a choice (retreat or stabilize an ally), not a forced flee. Any PC with the highest Focus may attempt Rally; level 17+ PCs may auto-succeed once per combat.

## Background tie-in (unimplemented design intent)

[[FEARS Advanced Backgrounds]]'s system-level notes call for high-rank backgrounds to provide "Breaking Point Protection" — leadership or spiritual strength aiding allies, conceptually similar to this page's Rally mechanic. No individual background page specifies this mechanically; [[Soldier]]'s Rally the Troops and [[Knight]]'s Knight's Banner are the closest analogues (both grant temp HP + fear-save benefits to nearby allies) but neither is stated to interact with Breaking Points specifically.

## See also

- [[Bloodied Breaking Points Rally]]
- [[Bloodied and Bruised]]
- [[Enemy Rally]]
- [[Sanity]]
- [[FEARS MOC]]
