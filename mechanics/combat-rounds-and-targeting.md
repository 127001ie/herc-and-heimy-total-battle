# Combat rounds, targeting, and experience generation

**Claims:** `TB-COMBAT-004`, `TB-COMBAT-005`, `TB-XP-003`  
**Reviewed:** 2026-10-23  
**Status:** mix of player observation, working model, and hypothesis.

## Rounds and attack opportunities (`TB-COMBAT-004`; observed_player)

Reported behavior: in each round, every surviving squad has an attack opportunity unless killed before its turn. This makes squad count and turn ordering relevant. A squad eliminated early may lose its attack for that round and for later rounds. The first-strike order has been described as variable. Precise ordering and all exceptions are not independently established here.

## Target selection (`TB-COMBAT-005`; hypothesis)

Prior battle-report analysis suggests that an enemy may prioritize where it can inflict the most *effective absolute damage*, considering type interactions and overkill. This is not a verified targeting algorithm. Do not make guaranteed squad-survival predictions from it. Competing hypotheses should be tested using battle reports with one changed variable at a time.

## XP and removed HP (`TB-XP-003`; working_assumption)

Our current model treats XP as correlated to actual enemy HP removed, with **no additional XP for overkill**. This guides Epic farming analysis but should be checked against controlled total-XP and HP-delta records across events. Different Epics may have their own effective XP rates.

## Optimization caution

Adding a cheap squad can add attack opportunities, but it can also change turn order, targeting, troop death, replacement costs, and available Leadership. A blanket "more squads = better" rule is unjustified.
