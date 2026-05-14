# Program Charter: Fintech/Services 3X AI Native PDLC Transformation (Project Prometheus)

> **Version:** 1.1 | **Date:** May 2026 | **Status:** Active — Pilot Phase

---

## 1. Program Purpose

The Fintech/Services 3X AI Native PDLC Transformation program (internally: **Project Prometheus**) exists to fundamentally reimagine how Fintech and Services product teams at Intuit develop software. Rather than layering AI tools onto existing processes, this program embeds AI as a native participant at every stage of the Product Development Lifecycle — from discovery through operation — to achieve a 3X step-change in speed, quality, and engineering experience.

Prometheus is currently in active pilot with 15 teams across Fintech and Services. The GA target is **mid-June 2026**, after which the program shifts to full Fintech/Services rollout.

---

## 2. Strategic Alignment

| Alignment Area | Link |
|----------------|------|
| Intuit AI Strategy | AI-First company transformation |
| Business Unit OKRs | Fintech/Services FY26 OKRs (internal) |
| Platform Engineering | Platform Roadmap FY26 |
| AI Transformation Program | Pathfinder/Enabler Program (Intuit-wide) |
| Prometheus Program | Fintech-specific agentic PDLC initiative |

---

## 3. Scope

**In Scope:**
- All Fintech and Services engineering teams at Intuit
- All PDLC phases: Discovery, Design, Build, Test, Ship, Operate
- AI tooling (Claude Code, MCP servers, context graphs, skill-based dev)
- PDLC process redesign, enablement, and measurement
- Pilot teams: 15 active Prometheus teams (see team roster below)

**Out of Scope:**
- Payments and Tax business units (separate transformation tracks)
- Consumer product design (UX design tooling handled separately)
- Infrastructure and SRE (addressed via Platform Engineering, though SREBot outcomes feed into this program's metrics)

---

## 4. Executive Sponsors & Stakeholders

| Role | Name | Responsibility |
|------|------|----------------|
| Executive Sponsor | TBD | Program funding, escalation authority |
| VP Engineering, Fintech | TBD | Org alignment, resource commitment |
| VP Engineering, Services | TBD | Org alignment, resource commitment |
| TPM Lead | Kim Ross | Program execution, reporting, governance |
| Platform Lead | TBD | AI tooling & infrastructure (Claude Code, MCP, context graphs) |
| HR/Change Mgmt Partner | TBD | Enablement and adoption |
| AI Transformation Liaison | TBD | Coordination with Intuit-wide Enabler/Pathfinder program |

---

## 5. Prometheus Pilot Team Roster

| Team | Domain | Status | Key Metric |
|------|--------|--------|-----------|
| Alpha 1 — IBCC | International Banking & Credit Card | 🟢 Live | 430 PRs/week |
| Alpha 2 — Payroll | Payroll Platform | 🟢 Live | 8X velocity gain |
| Stablecoin Wallet | Payments / Fintech | 🟡 Active | In progress |
| HR Advisor | Services / HR | 🟡 Active | In progress |
| ATS / GoCo GA | Talent & Services | 🟡 Active | In progress |
| 59ers / Five Niners | Platform Reliability | 🟡 Active | 99.998% availability |
| Pay for You | Consumer Payments | 🟡 Active | In progress |
| Payments Funds Management | Payments | 🟡 Active | In progress |
| Payments Conversion | Payments | 🟡 Active | In progress |
| Time Agent | Services / Time Tracking | 🟡 Active | In progress |
| SMB Health | Small Business | 🟡 Active | In progress |
| Company Creation Tool | Business Formation | 🟡 Active | In progress |
| Critical SMS Risk | Risk & Compliance | 🔵 Planning | Pending onboard |
| Payments Surcharging | Payments | 🔵 Planning | Pending onboard |
| AI Model Dev / Capital Onboarding | Platform / Fintech | 🔵 Planning | Pending onboard |

---

## 6. Success Criteria (3X Definition)

The program is successful when, measured from the established baseline:

| Metric | Current Signal | 3X Target | Measurement Method |
|--------|---------------|-----------|-------------------|
| Feature cycle time (idea → ship) | 8X shown by Payroll Alpha | 3X across all teams | GitHub + JIRA velocity data |
| Escaped defects per release | TBD (M1 baseline) | 3X fewer | Incident & bug tracking |
| AI-assisted task coverage | 94.73% Claude Code adoption (pilot) | Sustained at scale | Developer survey + tooling telemetry |
| Developer experience score | TBD (M1 baseline) | 3X improvement | Quarterly DevEx survey |
| Engineering hours saved (automation) | 203 hrs/period via SREBot | Scale across all teams | Automation telemetry |

> Full metric definitions and measurement methodology in [docs/metrics.md](../metrics.md).

---

## 7. Workstreams

| # | Workstream | Purpose |
|---|-----------|---------|
| 1 | Strategy & Executive Alignment | Charter, OKRs, stakeholder management |
| 2 | AI Tooling & Platform Enablement | Claude Code, MCP servers, context graphs, skill registry |
| 3 | PDLC Process Redesign | AI-native workflows per PDLC phase (ADLC model) |
| 4 | Change Management & Enablement | Training, AI Champions, adoption |
| 5 | Measurement & Value Realization | Metrics, DORA, 3X validation |
| 6 | Governance & Risk | Decision rights, Responsible AI, compliance |

---

## 8. High-Level Timeline

| Phase | Timeline | Key Deliverable |
|-------|----------|-----------------|
| Phase 0 — Foundation | Q2 2026 (complete) | Charter approved, tooling provisioned, baseline collection started |
| Phase 1 — Pilot | Now → Mid-June 2026 | Prometheus GA: all 15 teams live on AI-native PDLC |
| Phase 2 — Scale | Q3–Q4 2026 | Full Fintech/Services rollout beyond pilot cohort |
| Phase 3 — Validate | Q1 2027 | 3X outcomes validated and reported to exec |

**Immediate focus (May–June 2026):**
- Unblock MCP server access for remaining pilot teams
- Resolve design system readiness for AI-generated UI
- Stabilize E2E test suites for agentic workflows
- Complete compliance review for AI tooling stack
- Achieve Prometheus GA by mid-June 2026

---

## 9. Budget & Resources

| Category | Notes |
|----------|-------|
| Headcount | Workstream leads + dedicated eng support per team |
| Tooling Budget | Claude Code licensing, MCP infrastructure, context graph infrastructure |
| Enablement Budget | AI Champions program, training workshops, demo days |

> Budget detail tracked separately; escalation to exec sponsor if reallocation needed.

---

## 10. Active Risks

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|-----------|
| MCP server access blocked for pilot teams | High | High | Escalated to Platform; tracked as active blocker |
| Design system not ready for AI-generated UI | High | High | Design system team engaged; interim workaround in place |
| E2E test stability in agentic workflows | Medium | High | Test automation working group formed |
| Compliance review gate delays AI tool approval | High | High | Proactive engagement with InfoSec/Legal |
| Low adoption beyond early adopters at scale | Medium | High | Change management workstream; exec mandate |
| Competing priorities in eng orgs | High | Medium | Exec sponsor alignment; protected pilot team capacity |

See [WS6 — Governance & Risk](workstreams/06-governance-risk.md) for the full risk register.

---

## 11. Governance

- **Weekly:** Workstream lead sync (TPM-facilitated, 60 min)
- **Bi-weekly:** Leadership steering committee
- **Monthly:** Exec sponsor update
- **At milestones:** Phase-gate go/no-go review
- **System of record:** GitHub Issues — all decisions, risks, and changes tracked here

See [docs/governance.md](../governance.md) for full decision rights and escalation paths.

---

## Approvals

| Name | Role | Signature | Date |
|------|------|-----------|------|
| | Executive Sponsor | | |
| | VP Engineering, Fintech | | |
| | VP Engineering, Services | | |
| Kim Ross | TPM Lead | ✓ | May 2026 |

---

*This document is reviewed and re-approved at each phase boundary. Next review: Prometheus GA (mid-June 2026).*
