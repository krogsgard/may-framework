# May Framework

**An AI Chief of Staff architecture built on Claude Code.**

A replicable system for persistent AI operations across ephemeral sessions — using file-based memory, autonomous mission execution, and multi-agent coordination.

## Documentation

Full documentation: **https://krogsgard.github.io/may-framework/**

### Sections
- [Overview](https://krogsgard.github.io/may-framework/#overview) — What the system is and why it exists
- [Architecture](https://krogsgard.github.io/may-framework/#architecture) — File hierarchy, startup sequence, two-directory pattern
- [Agents](https://krogsgard.github.io/may-framework/#agents) — May, Atlas, Vulcan, Sentinel, Scribe, Ledger
- [Missions](https://krogsgard.github.io/may-framework/#missions) — Autonomous headless execution, self-healing loop
- [Memory & Cold Start](https://krogsgard.github.io/may-framework/#memory) — File roles, Scribe protocol, MEMORY.md discipline
- [Autonomy Model](https://krogsgard.github.io/may-framework/#autonomy) — Permission model, auto-approve rules
- [Tooling](https://krogsgard.github.io/may-framework/#tooling) — Scripts, workflows, PWA, Monday.com MCP
- [Rule Sets](https://krogsgard.github.io/may-framework/#rule-sets) — SOUL.md, CLAUDE.md, PLAYBOOK.md patterns
- [Getting Started](https://krogsgard.github.io/may-framework/#getting-started) — Step-by-step replication guide

## Stack

- **Runtime:** Claude Code CLI (Anthropic)
- **CI/CD:** GitHub Actions
- **Hosting:** GitHub Pages + Cloudflare Pages
- **Edge:** Cloudflare Workers, D1, R2
- **Frontend:** Vanilla JS / Astro 5

## License

MIT
