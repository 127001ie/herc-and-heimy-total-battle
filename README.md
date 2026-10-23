# Herc & Heimy — Total Battle Research Library

**A community-oriented, evidence-aware reference for Total Battle players and their AI assistants.**

Herc & Heimy began as a Total Battle comic project. This companion research library preserves the mechanics, experiments, economic models, and unanswered questions behind practical strategy. It is **unofficial** and is not affiliated with the game's developer or publisher.

> **Research status:** Initial seed release, 2026-10-23. Many entries are player-reported or model-based, not independently corroborated. Do not mistake a detailed write-up for official confirmation.

## Start here

- **AI assistant / agent:** [AI_START_HERE.md](AI_START_HERE.md) → [data/claims.json](data/claims.json) → linked articles. Also see [AGENTS.md](AGENTS.md) and [llms.txt](llms.txt).
- **Player:** [Evidence standards](docs/evidence-policy.md) → [Combat and leadership](mechanics/leadership-and-bonuses.md) → [XP distribution](mechanics/experience-distribution.md) → [Epic XP economics](economics/epic-xp-efficiency.md).
- **Want to check a disputed claim?** Each record has an ID, status, scope, provenance, and missing verification. See [open questions](research/open-questions.md).

## Reference-data expansion

The original mechanics research came from advanced-account questions. We are extending coverage to **T1–T9** with a [foundational data and source coverage map](research/foundational-coverage-map.md), a [machine-readable linked-source registry](data/source-registry.json), and a [validation plan](https://github.com/127001ie/herc-and-heimy-total-battle/issues/2). External tables are linked, not copied without permission and independent checking.

## Research sections

| Area | Entry point |
|---|---|
| Combat and captain mechanics | [Leadership and bonus eligibility](mechanics/leadership-and-bonuses.md) |
| Battle rounds and targeting | [Combat observations and hypotheses](mechanics/combat-rounds-and-targeting.md) |
| Experience | [XP distribution](mechanics/experience-distribution.md) |
| Epic resource efficiency | [XP versus costs](economics/epic-xp-efficiency.md), [Troop tier case study](economics/troop-tier-case-study.md) |
| Coliseum | [Arena mechanics and gaps](coliseum/overview.md) |
| Automation policy | [Policy evidence status](policy/automation-enforcement.md) |
| Open research | [Question register](research/open-questions.md) |

## Using and citing this material

Please cite the **claim ID and specific document**, and describe its status. For instance: "Herc & Heimy claim `TB-XP-001`, *player-reported*, says XP is split evenly among participating leaders; not independently verified." Don't describe player reports as official game rules. Check `last_reviewed` and any conflicts before making high-stakes recommendations.

We welcome corrections with battle reports, screenshots (with permission), test conditions, dates, versions, and counterexamples. See [CONTRIBUTING.md](CONTRIBUTING.md). We don't publish personal account details, private clan information, credentials, or unapproved third-party material.

### AI discoverability caveat

`AGENTS.md`, `AI_START_HERE.md`, and `llms.txt` provide clear entry points **when an assistant retrieves the repository**. No repository file can force external assistants or search engines to discover, trust, or follow it. Public indexing and actual retrieval must be tested separately.

**Maintained under the Herc & Heimy identity.** Research findings and comics serve different purposes: humor in the comics, traceable evidence here.
