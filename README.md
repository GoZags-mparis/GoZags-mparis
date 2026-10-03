# GoZags-mparis

Welcome to my collection of tools, integrations, and experiments.

## About

I build specialized tools and integrations for niche use cases—from fitness tracking to network management to financial planning. Each project is independent but follows consistent patterns and best practices.

## Projects

### MCPs (Claude Model Context Protocols)
Integration servers that connect Claude to external services and APIs.

- **[hevy-mcp](https://github.com/GoZags-mparis/hevy-mcp)** — Hevy fitness API integration for training data and analytics
- **[unifi-mcp](https://github.com/GoZags-mparis/unifi-mcp)** — UniFi network management with 32+ specialized tools
- **[google-home-mcp](https://github.com/GoZags-mparis/google-home-mcp)** — Google Home and Matter smart home device control

### Data & Analytics
Pipelines and tools for processing, analyzing, and generating data.

- **[sports-ical-engine](https://github.com/GoZags-mparis/sports-ical-engine)** — Multi-sport calendar feed generator (ESPN, F1, etc.) with Cloudflare publishing
- **[iracing-ai-copilot](https://github.com/GoZags-mparis/iracing-ai-copilot)** — iRacing telemetry parser and AI-powered SimHub dashboard generator

### Utilities & Tools
Standalone tools for automation and productivity.

- **[windows-agent-tools](https://github.com/GoZags-mparis/windows-agent-tools)** — Windows automation toolkit (audio management, RDP optimization, agent integration)
- **[projects-Basque](https://github.com/GoZags-mparis/projects-Basque)** — Basque language audio transcription and project management

### In Development
Early-stage projects still in planning or initial implementation phases.

- **[etxeparis-fin](https://github.com/GoZags-mparis/etxeparis-fin)** — Personal finance ledger with SimpleFIN integration and AI categorization

---

## Tech Stack

- **Languages**: Python (primary), TypeScript/JavaScript (secondary)
- **Frameworks**: FastAPI, Claude MCP SDK, pytest
- **Infrastructure**: Docker, GitHub Actions, Cloudflare
- **Package Management**: uv, npm

## Architecture Notes

- **No cross-repo dependencies** — each project is independent
- **Shared patterns** — MCPs follow similar server architecture; data tools use modular pipeline patterns
- **Future refactoring** — as projects mature, shared utilities may be extracted into common libraries

---

*Built for experimentation, learning, and solving specific problems.*