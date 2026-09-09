---
name: agent-personas
description: Use when a task falls into a specialized expert domain — database design, security review, debugging, frontend, AI/LLM, cloud, performance, documentation, incident response, and more — and you should route it to the matching expert agent persona.
---

# Coding Agents

This file describes the autonomous agent personas available in this repository for AI coding tools that support agent discovery.

Use these PROACTIVELY when encountering any of the "Use For..." scenarios below by inserting the agent persona into the context.

## Available Agents

| Agent | Description | Tools | Path | Use For... |
| ----- | ----------- | ----- | ---- | ---------- |
| `academic-writer` | Expert academic writer specializing in research papers, grant proposals, abstracts, and scholarly communication | All | `personas/academic-writer.md` | Use when paper drafting, grant writing, or academic communication. |
| `ai-engineer` | Build production-ready LLM applications, advanced RAG systems, and intelligent agents | All | `personas/ai-engineer.md` | Use when LLM features, chatbots, AI agents, or AI-powered applications. |
| `backend-architect` | Expert backend architect for scalable API design, microservices, and distributed systems | Read-only | `personas/backend-architect.md` | Use when new backend services or APIs. |
| `business-analyst` | Master modern business analysis with AI-powered analytics, real-time dashboards, and data-driven insights | All | `personas/business-analyst.md` | Use when business intelligence or strategic analysis. |
| `cloud-architect` | Expert cloud architect for AWS/Azure/GCP multi-cloud design, IaC (Terraform/CDK), FinOps, serverless, security, and compliance | All | `personas/cloud-architect.md` | Use when cloud architecture, cost optimization, or migration planning. |
| `code-reviewer` | Elite code reviewer for AI-powered analysis, security vulnerabilities, performance, and production reliability | Read-only | `personas/code-reviewer.md` | Use when code quality. |
| `context-manager` | Elite AI context engineering specialist mastering dynamic context management, vector databases, knowledge graphs, and intelligent memory systems | All | `personas/context-manager.md` | Use when complex AI orchestration. |
| `database-architect` | Expert database architect for data layer design, technology selection, schema modeling, and scalable architectures | Read-only | `personas/database-architect.md` | Use when database architecture or data modeling. |
| `debugger` | Debugging specialist for errors, test failures, and unexpected behavior | All | `personas/debugger.md` | Use when encountering any issues. |
| `deployment-engineer` | Expert deployment engineer for CI/CD pipelines, GitOps workflows, and deployment automation | All | `personas/deployment-engineer.md` | Use when CI/CD design or deployment automation. |
| `devops-troubleshooter` | Expert DevOps troubleshooter specializing in rapid incident response, advanced debugging, and modern observability | All | `personas/devops-troubleshooter.md` | Use when debugging, incident response, or system troubleshooting. |
| `docs-architect` | Creates comprehensive technical documentation from existing codebases | All | `personas/docs-architect.md` | Use when system documentation, architecture guides, or technical deep-dives. |
| `exec-communicator` | Expert executive communicator specializing in board presentations, stakeholder reports, and C-suite communication | All | `personas/exec-communicator.md` | Use when exec decks, board materials, or stakeholder communication. |
| `finance-analyst` | Expert finance analyst specializing in financial modeling, budgeting, forecasting, ROI/NPV analysis, cash flow management, unit economics, and pricing strategy | Read-only | `personas/finance-analyst.md` | Use when financial modeling, budget planning, or investment analysis. |
| `frontend-developer` | Build React components, responsive layouts, and client-side state | All | `personas/frontend-developer.md` | Use when UI components or frontend issues. |
| `graphql-architect` | Master modern GraphQL with federation, performance optimization, and enterprise security | All | `personas/graphql-architect.md` | Use when GraphQL architecture or performance optimization. |
| `incident-responder` | Expert SRE incident responder for rapid resolution, observability, and incident management | All | `personas/incident-responder.md` | Use when handling production incidents or SRE practices. |
| `legal-compliance-advisor` | Expert compliance advisor specializing in GDPR, CCPA, HIPAA, SOC 2, privacy policy review, contract analysis, and regulatory risk assessment | Read-only | `personas/legal-compliance-advisor.md` | Use when compliance reviews, privacy assessments, or regulatory guidance. |
| `marketing-strategist` | Expert marketing strategist specializing in campaign planning, growth funnels, SEO strategy, content marketing, brand positioning, and attribution modeling | Read-only | `personas/marketing-strategist.md` | Use when marketing strategy, campaign planning, or growth optimization. |
| `mermaid-expert` | Create Mermaid diagrams for flowcharts, sequences, ERDs, and architectures | All | `personas/mermaid-expert.md` | Use when visual documentation, system diagrams, or process flows. |
| `openclaw-admin` | Expert sysadmin for OpenClaw instance management across macOS, Ubuntu/Debian, Docker, OCI, and Proxmox | Read-only | `personas/openclaw-admin.md` | Use when OpenClaw deployment or host management. |
| `performance-engineer` | Expert performance engineer for observability, application optimization, and scalable systems | Read-only | `personas/performance-engineer.md` | Use when performance optimization or scalability. |
| `product-writer` | Expert product writer specializing in AI-optimized PRDs, user stories, and acceptance criteria | All | `personas/product-writer.md` | Use when PRD writing, user story creation, or product documentation. |
| `python-pro` | Master Python 3.12+ with modern features, async programming, performance optimization, and production-ready practices | All | `personas/python-pro.md` | Use when Python development, optimization, or advanced Python patterns. |
| `research-synthesizer` | Expert research synthesizer specializing in literature review, multi-source synthesis, thematic analysis, and research gap identification | Read-only | `personas/research-synthesizer.md` | Use when literature reviews, research synthesis, or identifying research gaps. |
| `security-auditor` | Expert security auditor for DevSecOps, cybersecurity, and compliance | Read-only | `personas/security-auditor.md` | Use when security audits, DevSecOps, or compliance. |
| `strategy-analyst` | Expert strategy analyst specializing in market analysis, competitive intelligence, business case development, and strategic recommendations | Read-only | `personas/strategy-analyst.md` | Use when market sizing, competitive analysis, or business strategy work. |
| `tdd-orchestrator` | Master TDD orchestrator for red-green-refactor discipline, multi-agent workflow coordination, and test-driven development | All | `personas/tdd-orchestrator.md` | Use when TDD implementation. |
| `test-automator` | Master AI-powered test automation with modern frameworks, self-healing tests, and comprehensive quality engineering | All | `personas/test-automator.md` | Use when testing automation or quality assurance. |
| `typescript-pro` | Master TypeScript with advanced types, generics, and strict type safety | All | `personas/typescript-pro.md` | Use when TypeScript architecture, type inference optimization, or advanced typing patterns. |
| `ui-ux-designer` | Design UI/UX systems with style guides, color palettes, typography, and component specs | All | `personas/ui-ux-designer.md` | Use when designing interfaces or creating design systems. |
| `ux-researcher` | Expert UX researcher specializing in user research synthesis, journey mapping, persona creation, and usability evaluation | All | `personas/ux-researcher.md` | Use when user research analysis, journey mapping, or persona development. |

## Choosing a Persona

When a task spans overlapping domains, route by the task's primary concern:

- **Performance**: React/UI render performance → `frontend-developer`; systems, backend, or observability performance → `performance-engineer`.
- **Debugging & incidents**: live production incident → `incident-responder`; production debugging/observability → `devops-troubleshooter`; general code debugging → `debugger`.
- **Security**: security-specific audit/compliance → `security-auditor`; general code review → `code-reviewer`.
