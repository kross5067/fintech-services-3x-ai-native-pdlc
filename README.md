# Fintech/Services/CoM: 3X AI Native PDLC Transformation

> **Program Status:** 🟡 Active — Pilot Phase | **Last Updated:** May 2026 | **TPM:** Kim Ross

## Overview

This repository is the single source of truth for the **Fintech/Services 3X AI Native Product Development Lifecycle (PDLC) Transformation** program — internally known as **Fintech / Services / 3X AI Native PDLC Transformation Program**. The goal is to reimagine how Fintech and Services teams at Intuit discover, build, test, and ship — embedding AI natively into every phase of the PDLC to achieve **3X improvement** in velocity, quality, and developer experience.

---

## Program Vision

> *Every Fintech/Services team operates with AI as a first-class participant in their PDLC — not a tool bolted on the side, but woven into how we think, design, build, and ship.*

**3X Targets (measured from baseline):**
- 3X improvement in feature delivery cycle time
- 3X reduction in escaped defects
- 3X increase in AI-assisted task coverage across PDLC phases

**Current Program Highlights (as of May 2026):**
- **94.73%** Claude Code adoption across 3X AI Native PDLC pilot teams
- **430** PRs/week on the IBCC team (AI-assisted)
- **8X** velocity improvement demonstrated by Alpha 2 Payroll team
- **203 hours** saved via SREBot automation
- **99.998%** system availability maintained through AI-native operations

---

## Repository Structure

```
fintech-3x-ai-native-pdlc/
├── README.md                          ← You are here
├── docs/
│   ├── charter.md                     ← Program charter & exec alignment
│   ├── milestones.md                  ← Key milestones & delivery schedule
│   ├── metrics.md                     ← 3X success metrics & baseline
│   ├── governance.md                  ← Decision rights & governance model
│   └── workstreams/
│       ├── 01-strategy-alignment.md   ← Workstream 1: Strategy & Exec Alignment
│       ├── 02-ai-tooling-platform.md  ← Workstream 2: AI Tooling & Platform
│       ├── 03-pdlc-process-redesign.md← Workstream 3: PDLC Process Redesign
│       ├── 04-change-management.md    ← Workstream 4: Change Mgmt & Enablement
│       ├── 05-measurement.md          ← Workstream 5: Measurement & Value
│       └── 06-governance-risk.md      ← Workstream 6: Governance & Risk
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── workstream-initiative.md   ← Template: new workstream initiative
│   │   ├── milestone-tracker.md       ← Template: milestone tracking issue
│   │   └── risk-blocker.md            ← Template: risk or blocker
│   └── project-board-setup.md         ← How to configure the GitHub Project board
```

---

## Fintech / Services / 3X AI Native PDLC Transformation Program Pilot Teams

The following Fintech/Services teams are active in the Fintech / Services / 3X AI Native PDLC Transformation Program AI-Native PDLC pilot:

| Team | Domain | Phase |
|------|--------|-------|
| Alpha 1 — IBCC | International Banking & Credit Card | 🟢 Live |
| Alpha 2 — Payroll | Payroll Platform | 🟢 Live |
| Stablecoin Wallet | Payments / Fintech | 🟡 In Progress |
| HR Advisor | Services / HR | 🟡 In Progress |
| ATS / GoCo GA | Talent & Services | 🟡 In Progress |
| 59ers / Five Niners | Platform Reliability | 🟡 In Progress |
| Pay for You | Consumer Payments | 🟡 In Progress |
| Payments Funds Management | Payments | 🟡 In Progress |
| Payments Conversion | Payments | 🟡 In Progress |
| Time Agent | Services / Time Tracking | 🟡 In Progress |
| SMB Health | Small Business | 🟡 In Progress |
| Company Creation Tool | Business Formation | 🟡 In Progress |
| Critical SMS Risk | Risk & Compliance | 🔵 Planning |
| Payments Surcharging | Payments | 🔵 Planning |
| AI Model Dev / Capital Onboarding | Platform / Fintech | 🔵 Planning |

---

## Workstreams at a Glance

| # | Workstream | Owner | Status |
|---|-----------|-------|--------|
| 1 | [Strategy & Executive Alignment](docs/workstreams/01-strategy-alignment.md) | Kim Ross | 🟡 Active |
| 2 | [AI Tooling & Platform Enablement](docs/workstreams/02-ai-tooling-platform.md) | TBD | 🟡 Active |
| 3 | [PDLC Process Redesign](docs/workstreams/03-pdlc-process-redesign.md) | TBD | 🟡 Active |
| 4 | [Change Management & Enablement](docs/workstreams/04-change-management.md) | TBD | 🟡 Active |
| 5 | [Measurement & Value Realization](docs/workstreams/05-measurement.md) | TBD | 🟡 Active |
| 6 | [Governance & Risk](docs/workstreams/06-governance-risk.md) | TBD | 🟡 Active |

---

## Key Milestones

See [docs/milestones.md](docs/milestones.md) for the full schedule. High-level:

| Milestone | Target Date | Status |
|-----------|-------------|--------|
| M0 — Program Foundation & Charter Approved | Q2 2026 | 🟢 Complete |
| M1 — Baseline Metrics Established | Q2 2026 | 🟡 In Progress |
| M2 — AI Tooling Stack Approved & Deployed | Q2 2026 | 🟡 In Progress |
| M3 — AI-Native PDLC Workflows Defined | Q2 2026 | 🟡 In Progress |
| M4 — Pilot Teams Live (Program GA) | Mid-June 2026 | 🟡 In Progress |
| M5 — Pilot Phase Gate | End of Q3 2026 | ⚪ Not Started |
| M6 — Full Fintech/Services Rollout | Q4 2026 | ⚪ Not Started |
| M7 — 3X Outcomes Validated | Q1 2027 | ⚪ Not Started |

---

## Active Risks & Blockers

| Risk | Impact | Status |
|------|--------|--------|
| MCP server access gating for pilot teams | High | 🔴 Active Blocker |
| Design system readiness for AI-generated UI components | High | 🔴 Active Blocker |
| E2E test stability in agentic workflows | Medium | 🟡 Monitoring |
| Compliance review gate timelines for AI tooling approval | High | 🔴 Active Blocker |

See [WS6 — Governance & Risk](docs/workstreams/06-governance-risk.md) for the full risk register.

---

## How to Contribute

- **Workstream leads:** Update your workstream doc weekly before the leadership sync
- **Pilot teams:** Log blockers immediately using the [risk-blocker template](.github/ISSUE_TEMPLATE/risk-blocker.md) — don't wait for the weekly sync
- **Issues:** Use the [issue templates](.github/ISSUE_TEMPLATE/) for initiatives, milestones, and risks
- **Project board:** All active work is tracked in the [GitHub Project board](../../projects) — see [setup guide](.github/project-board-setup.md)
- **Questions:** Open a Discussion or reach out to Kim Ross (kim_ross@intuit.com)

---

## References & Related Links

- 3X AI Native PDLC Demos 3X AI Native PDLC Demos & Learnings Learnings — Bi-Weekly Meeting Notes (internal Google Doc)
- Fintech/Services AI Agentic Transformation Program Doc (internal Google Doc)
- Intuit AI Transformation Program — Enablers/Pathfinders Track (internal Confluence)
- Fintech/Services OKRs (internal)
- Intuit Platform Engineering Roadmap (internal)

---

*This repository follows Intuit's internal open-source guidelines. All content is internal and confidential.*
