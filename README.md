# Tiered Review

Read this in [繁體中文](README.zh-TW.md).

Three-tier approval framework for AI agents.

- **Tier 1 — approve before acting:** anything external, irreversible, involving money or credentials, or changing a settled decision. No action without the owner's explicit words.
- **Tier 2 — act, then report:** read-only research and summaries, reversible personal organizing, drafts that are never sent.
- **Tier 3 — log only:** routine checks, health checks, scheduled triggers. No interruption.

Escalation rule: if any of these is true, it is Tier 1 — irreversible, visible to others, involves someone else's data or rights, or unclear which tier it is.

Full framework: [tiered-review.md](tiered-review.md) (English) · [分級審查制.md](分級審查制.md) (繁體中文)

## Related projects

Three parts of one workflow — rules, then tiers, then a paper trail:

- [workflow-skills](https://github.com/kttcat/workflow-skills) — the rules: nine learned workflow skills.
- [tiered-review](https://github.com/kttcat/tiered-review) — the tiers: this repo.
- [sqlite-audit-log](https://github.com/kttcat/sqlite-audit-log) — the paper trail: append-only SQLite audit log.

## License

MIT — see [LICENSE](LICENSE).
