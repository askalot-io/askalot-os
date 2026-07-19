# Askalot OS

**Askalot OS** is a Research Operating System — a platform that escorts a researcher across the entire research lifecycle: **ideation → questionnaire design → campaign → execution → data-quality analysis**.

Unlike a conventional "survey tool", Askalot treats research as an end-to-end workflow:

- **Formally verified questionnaires** — questionnaire logic is written in QML (Questionnaire Markup Language) and mathematically proven with the Z3 SMT solver before fielding: no dead branches, no unreachable questions, no contradictory skip logic.
- **AI-assisted design** — AI agents help turn reference documents into a Research Brief, plan questionnaire chapters, generate and validate QML, and evaluate whether the collected data can actually answer the research goals.
- **Campaign management** — sampling strategies, respondent pools, interviewer workflows, magic-link survey access, and live fielding supervision.
- **Data-quality pipeline** — a medallion pipeline (Bronze → Silver → Gold) with raking/weighting and quality metrics (RMSE, MAE, Chi-Square) at every stage, exportable to CSV, SPSS, and Parquet.
- **Open integration surface** — a REST API and an MCP (Model Context Protocol) server, plus a Claude Code plugin, so agents and scripts can drive the whole platform.

## Links

| Resource | Where |
|----------|-------|
| 🌐 Main landing page | [askalot.io](https://askalot.io) |
| 📚 Documentation site | [docs.askalot.io](https://docs.askalot.io) |
| 📝 QML compiler & validator | [askalot-io/QML](https://github.com/askalot-io/QML) |
| 📖 Documentation sources | [askalot-io/docs](https://github.com/askalot-io/docs) |
| 🔌 Claude Code plugin | [askalot-io/askalot-plugin](https://github.com/askalot-io/askalot-plugin) |

## Feature requests & bug reports

This repository is the **public issue tracker for the Askalot platform**. Anyone is welcome to open an issue here — no customer account required:

- 🐛 **Bug reports** — something broke, behaved unexpectedly, or produced wrong results? [Open a bug report](../../issues/new?labels=bug) with steps to reproduce, what you expected, and what happened instead.
- 💡 **Feature requests** — missing a capability, an export format, an integration? [Open a feature request](../../issues/new?labels=enhancement) describing the problem you are trying to solve.
- ❓ **Questions** — unsure whether something is a bug or by design? Open an issue anyway; we will triage and label it.

Please search [existing issues](../../issues) before filing a new one, and never include credentials, personal data, or respondent data in an issue.

## Release notes

Release notes and general platform information are published here in Markdown under [`release-notes/`](release-notes/). Watch this repository (**Watch → Custom → Releases**) to be notified of new releases.
