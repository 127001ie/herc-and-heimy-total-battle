# Foundational coverage plan: T1–T9

**Status:** Source-discovery stage, 2026-10-23. This is an evidence map, **not** a verified data dump.

The initial Herc & Heimy library arose from mature-account questions. Broader usefulness requires reference data, then context-aware models and strategy. An AI helping a T3 player should not inherit T9 assumptions about whether VP, CP, building resources, or early captains still matter.

## Coverage matrix

| Domain | What the database needs | Current public leads | Gap / validation needed | Priority |
|---|---|---|---|---|
| Academy research | Each research and level; VP/CP currency and cost, prerequisites, Academy gate, unlock effect | [Total Battle Wiki planner](https://totalbattlewiki.com/research/planner/), [TB Toolkit research](https://www.tbtoolkit.com/research), [official VP](https://scorewarrior.theymes.com/hc/en/total-battle/articles/valor-points-504), [official CP](https://scorewarrior.theymes.com/hc/en/total-battle/articles/conquest-points-505) | Compare independent totals, boundaries and missing late tiers; obtain permission before copying source tables | **P0** |
| Building construction | Per level/type: wood, iron, stone, Great Architect's Blueprints, prerequisite Capitol, production benefits | [Total Battle Wiki buildings](https://totalbattlewiki.com/buildings/), [official blueprints](https://scorewarrior.theymes.com/hc/en/total-battle/articles/great-architects-blueprints-231), [official building resources](https://scorewarrior.theymes.com/hc/en/total-battle/articles/building-resources-224) | Distinguish building counts, wall segments, mine blueprint costs; verify actual milestone amounts | **P0** |
| Crypt access, economy, build | Level/rarity gates, tar type, costs, double-explore probability, rewards and captain gear; effective tar/chest/time | [official crypts](https://scorewarrior.theymes.com/hc/en/total-battle/articles/crypts-460), [official exploration math](https://scorewarrior.theymes.com/hc/en/total-battle/articles/the-cost-of-exploring-crypts-and-crypt-exploration-efficiency-425), [Total Battle Wiki crypts](https://totalbattlewiki.com/crypts/), [official captains](https://scorewarrior.theymes.com/hc/en/total-battle/articles/which-captains-should-i-hire-and-why-465) | Establish tested baseline and exact optimization objective; distinguish exploration cost, progress, capacity, completion and chest volume | **P0** |
| Troops and mercenaries | Unlock levels, base stats, troop resource costs, replacement economics, combat roles | [TotalBattleIQ reference](https://totalbattleiq.com/), [Total Battle Wiki troops](https://totalbattlewiki.com/) | Permission/licensing, snapshot version, independent spot-checks, distinction between base and buffed stats | P1 |
| Equipment, materials, gems | Recipes, source crypt, material quality, costs, stats, equipment progression | [official equipment](https://scorewarrior.theymes.com/hc/en/total-battle/articles/why-do-i-need-to-craft-equipment-446), [Total Battle Wiki](https://totalbattlewiki.com/) | Versioned variants, probabilistic crafting quality, sources and original verification | P1 |
| Captains, heroes, artifacts, monuments | Level and star bonuses, scaling caps, fragment sources/costs, synergy | [official captains](https://scorewarrior.theymes.com/hc/en/total-battle/articles/which-captains-should-i-hire-and-why-465), [Total Battle Wiki](https://totalbattlewiki.com/) | Current roster, rare/seasonal unlocks, separate base bonus from environment or future-patch speculation | P1 |
| Progression and farming pathways | Best VP/CP/XP/tar/silver tactics by account stage and available events | [official resource index](https://scorewarrior.theymes.com/hc/en/total-battle/categories/in-game-resources-41) plus analyzed evidence | Explicit cost denominator, opportunity costs, stage-specific alternative strategies | P1 |
| Events and season rewards | Eligibility, cost, points, reward tables, update timelines | [official support](https://scorewarrior.theymes.com/hc/en/total-battle), player screenshots | Highly volatile; event- and date-scoped records, no stale universal claims | P2 |
| Clan infrastructure | Clan research, production, chest economy, tile bonuses | [official clan research](https://scorewarrior.theymes.com/hc/en/total-battle/articles/why-should-i-research-clan-technologies-255), [official clan resources](https://scorewarrior.theymes.com/hc/en/total-battle/articles/how-can-i-manage-clan-resources-314) | Inputs/outputs of clan buildings, contribution economics, clan maturity and social constraints | P2 |
| Combat mechanics and optimization | Per-tier efficiency, round order, targeting, buffs and battle XP | [existing Herc & Heimy combat research](../mechanics/leadership-and-bonuses.md), [XP](../mechanics/experience-distribution.md) | Preserve firsthand and experimental evidence, avoid unfounded generalization from elite armies | P0 ongoing |

## Public source discovery is not an open license

Searchable websites can be *read* and *linked*. That does not automatically grant the right to mirror tables, scripts, images or databases. For each candidate source record its identity, date checked, scope, terms/license status, and an independent verification plan. Never silently scrape or bulk-republish a competitor's material. Seek permission or collect original in-game observations where needed.

## Two layers, not one encyclopedia

- **Reference layer**: versioned, granular facts and source links (level costs, unlock gates, numeric stats) without pretending they are investment advice.
- **Reasoning layer**: dependency graphs, total-cost calculators, build comparisons, optimal-path models and sensitivity to player stage, assumptions, available time, resources and goals.

Example questions the combined system should answer: "How much more VP/CP is required to unlock T6 from my current levels?", "What blueprint bottleneck is coming at Capitol 30?", "Will a Carter gear upgrade pay for itself in tar saved or additional clan chests?" Each answer should cite data, distinguish prerequisites from optional research, and show the optimization objective.

## Stage segmentation

Track starter (T1–T3), developing (T4–T6), advanced (T7–T8), and mature (T9 / research-complete) as **editorial convenience**, not official divisions. Strategies and currency values can change dramatically between these stages.

## First validation sprint

1. Build a **source registry** and coverage matrix (this document).
2. Independently cross-check one VP branch, one CP branch, one blueprint milestone ladder, and one crypt build example. Do not import full third-party tables before permission and verification.
3. Publish an original **research path calculator specification**, incorporating prerequisites and currencies independently.
4. Publish a crypting ROI methodology (tar per completed crypt, chest yield per hour, travel and march limits) grounded in official mechanics; label any unverified factors.
5. Solicit community evidence and corrections with reproducible configurations.

### Known source conflicts to watch

Official Total Battle help says Crypt exploration efficiency increases progress per march, while exploration cost reduces Tar needed; double exploration may grant a second strike without extra Tar. A guide that treats these as interchangeable is unsuitable as a formula source. Also, the official Captain reference has game-roster facts that may lag new releases: record check dates instead of assuming any single roster is exhaustive.

**Private/account-specific reasoning stays out of the public repo.** We can apply public models privately to account data without publishing those inputs.
