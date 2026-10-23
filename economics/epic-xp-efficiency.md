# Epic XP efficiency: goals, denominators, and tradeoffs

**Claims:** `TB-XP-002`, `TB-ECON-001`, `TB-ECON-002`  
**Reviewed:** 2026-10-23

## Optimize the actual objective

Several optimization targets are distinct:

- `total XP per attack` — all leaders combined.
- `XP per desired captain per attack` — may reward concentrating XP in fewer leaders.
- `XP per resource spent` — requires actual troop replacement and other marginal costs.
- `XP per wall-clock time` — matters during a limited event and depends on march/attack cadence.
- `permanent growth ROI` — future XP gained from durable bonuses vs XP spent now.

A recommendation that optimizes one denominator can be bad for another.

## Useful baseline model (`TB-ECON-001`; derived framework)

`xp_per_resource = total_xp_awarded / total_marginal_resource_cost`

Resource cost needs an explicit ledger: troop manufacturing costs, deaths and revival/replacement costs, mercenaries, silver, dragon coins, and scarce event consumables as relevant. Do not compare different metrics as if equivalent. Time, medals, and opportunity cost may be separately constrained.

## Why fewer captains is not automatically best

XP split among leaders yields the threshold in [experience distribution](../mechanics/experience-distribution.md), but removing a captain removes its eligible bonuses, artifact, equipment, and Leadership contributions. The relevant experiment must measure real battle output and cost, not XP fraction alone.

## Long-term strategic observation (`TB-ECON-002`; strategic_judgment)

For accounts with top-tier troops already researched, XP remains an important ongoing progression resource, while Conquest Points can have sharply diminished immediate utility. This is a **stage-specific strategy assessment**, not a universal fact about every player or event. PvP still has other potential value (silver, competition, unique rewards, clan defense).

## Reproducible XP test template

Record date/event/Epic and state; active bonuses and titles; participating leader set (including hero); star/level/equipment/artifacts; troop tier and squad counts; attack report; total XP and per-leader XP; enemy HP delta; lost troops; resource cost. Repeat enough trials to account for first-strike and proc variance.
