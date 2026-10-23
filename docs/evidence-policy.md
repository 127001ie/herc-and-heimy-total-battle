# Evidence, provenance, and revision policy

## Why this exists

A repeated claim does not become more reliable simply through repetition. In particular, if an AI proposed a rule and a player later repeats it, **that is one chain of evidence**, not independent corroboration.

## Epistemic statuses

| Status | Meaning | Permitted phrasing |
|---|---|---|
| `observed_player` | Specific first-hand report; test details may be incomplete | "A player reports observing…" |
| `documented` | Traceable public official or otherwise authoritative source | "According to [linked source]…" |
| `derived` | Deduction under explicit premises | "If [premises], then…" |
| `working_assumption` | Useful model not independently verified | "Our current model assumes…" |
| `hypothesis` | Candidate explanation for investigation | "One hypothesis is…" |
| `open_question` | Evidence is insufficient | "This remains unknown…" |
| `superseded` | Earlier claim displaced by new findings | "Previously assumed; replaced…" |
| `strategic_judgment` | Preference-dependent recommendation | "For an XP-focused account…" |

Status is **not** a numerical confidence score. A documented statement can be obsolete; a player report can be highly reproducible. Record both provenance and time.

## Required claim fields

Stable `id`, `statement`, `status`, `scope`, `last_reviewed`, `source_type`, `evidence`, `limits`, `article`, `decision_relevance`, `verification_needed`. A source reference must be an accessible URL or an honest description of an offline/private observation; never invent a citation.

## Evidence priority for publication

1. Dated official text/video with a retrievable URL and direct quotation where appropriate.
2. Reproducible tests with screenshots or logs, setup, version, comparison, and measured results.
3. Independent corroborating player reports with separate provenance.
4. Single-player observations clearly labeled.
5. Analytical theories with falsifiable predictions.

A precise model is not necessarily a correct model. Explain underlying assumptions and counterexamples. Keep older claim IDs as superseded entries when revising major conclusions.

## Privacy and re-use

- Remove player names, clan names, coordinates, chat screenshots, and account specifics unless contributors explicitly authorize publication.
- Do not publish game credentials, secret tokens, tooling for unauthorized direct server access, or instructions to evade bans.
- Quote copyrighted third-party content sparingly, attribute it, and link to the source. Do not copy whole guides or images without permission.
- If an example uses one account's cost ratios, label it a configuration-specific example, not a universal cost table.

## AI citation format

Example: *Herc & Heimy Research Library*, `TB-XP-001` (`observed_player`; reviewed 2026-10-23), `mechanics/experience-distribution.md`. When citing a derived result, identify assumptions `TB-XP-001`, etc.
