# Leadership and bonus eligibility

**Claims:** `TB-COMBAT-001`, `TB-COMBAT-002`, `TB-COMBAT-003`  
**Reviewed:** 2026-10-23  
**Evidence maturity:** player reports and an unverified analytical assumption.

## Shared army Leadership (`TB-COMBAT-001`; observed_player)

A participating group of battle leaders contributes to a **shared Leadership pool**; troops are not individually assigned to captains. The army's composition must fit the applicable combined capacity. This was described by an experienced player in an October 2026 strategy discussion; it has not yet been independently reproduced in the public repository.

## Bonus eligibility (`TB-COMBAT-002`; observed_player)

Applicable captain abilities, equipped items, and artifacts contribute to the **same participating army**, restricted by their stated eligibility (e.g. Guardsmen, Monsters, or entire army). Removing a leader can therefore reduce Leadership **and** multiple types of combat bonus; it does not merely remove bonuses from some imaginary captain-specific troop contingent.

## Additive Strength stacking (`TB-COMBAT-003`; working_assumption)

A long-running analytical model assumes bonuses within the same applicable Strength category **add** rather than independently multiply. This model has been repeated in strategy advice but its origin is partly prior assistant guidance; repeated reliance is not independent validation. Precise interactions between all categories of bonus, activated effects, artifacts, and combat-specific mechanics remain to be audited.

The working formula for one eligible bonus pool is:

`effective_bonus_percent = sum(applicable_bonus_percentages)`

This is a hypothesis about the **bonus accumulation layer**, not a claim that damage itself is a linear function of a single displayed statistic. Different combat procs (e.g. a separate hit, double damage, block) require separate modeling.

## Decision relevance

Removing a captain can increase each remaining leader's fraction of XP while lowering the army's total output and changing resource losses. Compare total XP, XP per desired leader, and cost/XP under controlled conditions. See [XP distribution](experience-distribution.md).

## Needed tests

- Swap one equipment item providing a known single bonus while holding all else fixed.
- Measure the displayed aggregate statistic and battle outcomes; distinguish rounding and proc effects.
- Independently verify whether every listed bonus category belongs to the same additive pool.
