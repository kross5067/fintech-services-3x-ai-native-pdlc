# Workstream 2: AI Tooling & Platform Enablement

> **Workstream Lead:** TBD | **Status:** 🟡 Active — Pilot Deployment | **Last Updated:** May 2026

---

## Purpose

Standardize and operate the AI tooling stack that Fintech/Services engineers use across every PDLC phase. This workstream eliminates tool fragmentation, ensures platform-grade reliability, and provides the infrastructure foundation for the Fintech / Services / 3X AI Native PDLC Transformation Program AI-native developer experience — including Claude Code, MCP servers, context graphs, and skill-based development.

---

## Objectives

1. Operate the standardized Fintech / Services / 3X AI Native PDLC Transformation Program AI tooling stack across all 15 pilot teams
2. Resolve MCP server access for all pilot teams (current active blocker)
3. Complete compliance review of full AI tooling stack
4. Extend self-service provisioning to full Fintech/Services rollout (Phase 2)
5. Instrument adoption telemetry to measure AI task coverage across PDLC phases

---

## Fintech / Services / 3X AI Native PDLC Transformation Program AI Tooling Stack (Current State — May 2026)

| PDLC Phase | Tool Category | Deployed Tool | Status |
|-----------|--------------|--------------|--------|
| All Phases | AI Coding Assistant | **Claude Code** | ✅ Deployed — 94.73% adoption |
| All Phases | Context & Tool Orchestration | **MCP (Model Context Protocol) Servers** | ⚠️ Partially deployed — access blocked for some teams |
| All Phases | Persistent Context | **Context Graphs** | 🟡 In progress |
| All Phases | Reusable AI Behaviors | **Skill Registry** | 🟡 In progress |
| Build | AI Code Generation | Claude Code (agentic mode) | ✅ Active |
| Build | PR Automation | Claude Code + GitHub Actions | ✅ Active (IBCC: 430 PRs/week) |
| Test | AI Test Generation | Claude Code test writing + E2E agent | ⚠️ E2E stability issues being resolved |
| Operate | AI Incident Response | **SREBot** | ✅ Active — 203 hrs/period saved |
| Operate | Observability | AI-enhanced monitoring | 🟡 In progress |
| Discovery | AI Requirements & Research | TBD | 🔵 Evaluating |
| Design | AI Design & Spec Generation | Blocked by design system readiness | 🔴 Blocked |
| Ship | AI-assisted Deployment | TBD | 🔵 Evaluating |

---

## Core Platform Components

### Claude Code
Claude Code is the primary AI coding assistant deployed across all 3X AI Native PDLC pilot teams. As of May 2026:
- **Adoption:** 94.73% of pilot team engineers actively using Claude Code
- **Usage:** Code generation, PR review, test writing, documentation, agentic task execution
- **Configuration:** Teams configure `.claude/` directories with team-specific context and skills

### MCP (Model Context Protocol) Servers
MCP servers extend Claude Code with access to internal Intuit systems and data — JIRA, Confluence, internal APIs, deployment pipelines. They are the connective tissue between Claude Code and Intuit's developer ecosystem.
- **Current status:** Partially deployed; some pilot teams do not yet have MCP access
- **Blocker:** MCP server provisioning gating — escalated to Platform Engineering team
- **Resolution target:** Required for Program GA (mid-June 2026)

### Context Graphs
Context graphs provide persistent, structured representations of team knowledge — architecture diagrams, codebase context, product specs — that Claude Code uses as long-running context rather than relying solely on conversation history.
- **Current status:** In development; design in progress
- **Benefit:** Eliminates redundant context-setting; enables multi-session and multi-agent workflows

### Skill Registry
A centralized registry of reusable AI skill definitions (e.g., "write a JIRA ticket from a Slack thread", "generate a test suite from an API spec"). Teams contribute skills; skills are shared across orgs.
- **Current status:** Initial skills defined by alpha teams; registry infrastructure in progress

### SREBot
AI-powered SRE automation for incident detection, triage, and response. Active across pilot teams.
- **Current output:** 203 engineering hours saved per period
- **Capability:** Automated alerting triage, runbook execution, incident summarization

---

## Key Initiatives

| Initiative | Owner | Target | Status |
|-----------|-------|--------|--------|
| Resolve MCP server access for all 15 pilot teams | Platform Eng | June 2026 | 🔴 Active Blocker |
| Complete InfoSec/Legal compliance review of AI stack | WS2 Lead + InfoSec | June 2026 | 🔴 Active Blocker |
| Deploy context graph infrastructure | Platform Eng | Q3 2026 | 🟡 In Progress |
| Build and launch Skill Registry v1 | WS2 Lead | Q3 2026 | 🟡 In Progress |
| Resolve E2E test stability for agentic workflows | WS2 + WS3 | June 2026 | 🟡 In Progress |
| Resolve design system readiness for AI-generated UI | Design System Team | June 2026 | 🔴 Active Blocker |
| Tool telemetry & adoption tracking (AI task coverage) | WS2 + WS5 | Q2 2026 | 🟡 In Progress |
| Self-service provisioning for Phase 2 rollout | Platform Eng | Q3 2026 | ⚪ Not Started |
| Evaluate AI tooling for Discovery and Design phases | WS2 Lead | Q3 2026 | 🔵 Evaluating |

---

## Active Blockers

| Blocker | Impact | Owner | Status |
|---------|--------|-------|--------|
| MCP server access not available for all pilot teams | Blocks full AI-native workflow for affected teams | Platform Eng | 🔴 Escalated |
| Compliance review not complete for full tooling stack | Blocks formal approval and Phase 2 rollout | WS2 + InfoSec | 🔴 In Review |
| Design system not ready for AI-generated UI | Blocks Design-phase AI tooling deployment | Design System Team | 🔴 Escalated |
| E2E test suite instability in agentic workflows | Reduces confidence in AI-assisted ship pipeline | WS2 + WS3 | 🟡 Working Group Active |

---

## OKRs

**Objective:** Operate a standardized, production-grade AI tooling stack enabling all 3X AI Native PDLC pilot teams to develop AI-natively by GA (mid-June 2026).

| Key Result | Current | Target |
|-----------|---------|--------|
| Claude Code adoption across pilot teams | 94.73% | 95%+ sustained through GA |
| Pilot teams with full MCP server access | Partial | 15/15 by GA |
| Compliance review complete | In progress | Complete by GA |
| AI task coverage measured across PDLC phases | TBD | Baseline established at M1 |
| Context graph infrastructure live | In progress | Q3 2026 |

---

## Dependencies

- WS1 (Strategy): exec alignment on tooling decisions and MCP escalation
- WS3 (Process Redesign): workflows must match tooling capabilities (especially MCP + context graphs)
- WS4 (Change Mgmt): enablement content depends on final tooling decisions
- WS5 (Measurement): adoption telemetry must feed AI task coverage metric
- Platform Engineering: MCP provisioning, context graph infra, self-service
- Design System Team: readiness for AI-generated UI components (blocks WS3 Design phase)
- InfoSec / Legal: compliance review authority

---

## Linked Issues

> Add GitHub issue links here as initiatives are created in the project board.
> Start with: MCP Access Blocker, Compliance Review Blocker, Design System Blocker, E2E Stability

---

## Addendum: References

| Source | Relevance |
|--------|-----------|
| 3X AI Native PDLC Demos 3X AI Native PDLC Demos & Learnings Learnings Bi-Weekly Meeting Notes (internal) | Source of real adoption metrics: 94.73% Claude Code, 430 PRs/week, SREBot 203 hrs, 8X Payroll velocity |
| Fintech/Services AI Agentic Transformation Program Doc (internal) | Tooling architecture: MCP, context graphs, skill registry, ADLC model |
| Anthropic Claude Code Documentation — https://docs.anthropic.com | Claude Code setup, MCP server configuration, agentic mode |
| MCP Protocol Specification — https://modelcontextprotocol.io | MCP architecture and server implementation reference |
| Intuit InfoSec AI tool review process (internal) | Compliance review requirements |
| Platform Engineering Roadmap (internal) | MCP provisioning and context graph infrastructure timelines |
