# Agent Personas

A collection of 32 specialized expert agent personas for AI coding tools. Each
persona is a markdown file describing an expert role — its mindset, workflow,
and rules — that an AI assistant can adopt when a task falls into that domain.

## What's inside

```text
agent-personas/
├── SKILL.md            # Index table: all personas, descriptions, when to use
├── personas/           # One .md file per persona
│   ├── debugger.md
│   ├── security-auditor.md
│   ├── frontend-developer.md
│   └── ...
└── README.md
```

Personas cover:

- Engineering (debugger, code-reviewer, python-pro)
- Architecture (backend-architect, cloud-architect, database-architect)
- DevOps and security (incident-responder, deployment-engineer, security-auditor)
- Product and design (ui-ux-designer, product-writer, ux-researcher)
- Business roles (strategy-analyst, finance-analyst, legal-compliance-advisor)

The full list with descriptions is in [SKILL.md](SKILL.md).

## How to use

1. When a task matches a persona's domain, read the matching file from
   `personas/` and adopt its role — the file defines the persona's identity,
   workflow, and conventions.
2. `SKILL.md` includes routing guidance for overlapping domains (e.g. which
   debugging persona to pick for a live incident vs. a local bug).

For tools that auto-discover skills (e.g. Claude Code), placing this directory
where skills are loaded makes the personas available via the `SKILL.md`
description.

## Attribution

These personas originate from
[Claude Octopus](https://github.com/nyldn/claude-octopus) by nyldn.

## License

MIT — see [LICENSE.md](LICENSE.md).
