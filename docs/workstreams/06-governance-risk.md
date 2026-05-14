# Workstream 6: Governance & Risk

> **Workstream Lead:** TBD | **Status:** 🟡 Active | **Last Updated:** May 2026

---

## Purpose

Establish the governance structures, decision rights, and risk management practices that allow the Fintech / Services / 3X AI Native PDLC Transformation Program to move fast safely. This workstream ensures AI tools and processes meet Intuit's security, compliance, and responsible AI standards — and provides clear escalation paths when blockers arise.

---

## Objectives

1. Define program decision rights and escalation paths
2. Maintain a live program risk register with active mitigation tracking
3. Ensure all AI tools meet InfoSec and compliance requirements before deployment
4. Unblock active compliance review to achieve Program GA by mid-June 2026
5. Define and enforce responsible AI usage standards for Fintech/Services teams

---

## Decision Rights (RACI)

| Decision | Responsible | Accountable | Consulted | Informed |
|---------|------------|------------|---------|---------|
| Program charter approval | Kim Ross | Exec Sponsor | VPs Eng | All stakeholders |
| AI tool selection (Claude Code, MCP, etc.) | WS2 Lead | VP Eng | InfoSec, Legal | All engineers |
| MCP server access escalation | Kim Ross | VP Eng | Platform Eng | Pilot teams |
| Process redesign changes | WS3 Lead | VP Eng | Team leads | All engineers |
| Budget reallocation | Kim Ross | Exec Sponsor | Finance | Steering committee |
| Risk escalation (P1) | Kim Ross | Exec Sponsor | Relevant WS leads | All |
| Phase-gate go/no-go | Kim Ross | Exec Sponsor | All WS leads | All stakeholders |

---

## Responsible AI Framework

All AI tools and use cases deployed under this program must comply with:

| Requirement | Owner | Review Frequency | Status |
|------------|-------|-----------------|--------|
| InfoSec AI tool review | InfoSec | Per tool addition | 🔴 In progress — blocking GA |
| Data privacy assessment | Legal/Privacy | Per tool addition | 🔴 In progress |
| Responsible AI use standards | AI Gov team | Quarterly | 🟡 Defined; monitoring |
| Bias and fairness review | TBD | Per major use case | ⚪ Not started |
| Human-in-the-loop requirements | WS3 Lead | Per workflow design | 🟡 Defined for Build/Test |

> Reference: Intuit Responsible AI Policy (internal)

---

## Program Risk Register

### Active Blockers (🔴 — Require Immediate Action)

| ID | Blocker | Impact | Owner | Mitigation | Target Resolution |
|----|---------|--------|-------|-----------|-------------------|
| B01 | **MCP server access not available for all 15 pilot teams** | Blocks AI-native workflow for affected teams; threatens GA | Platform Eng (escalated by Kim Ross) | Platform Eng provisioning sprint; weekly check-in | June 2026 (GA) |
| B02 | **Compliance review not complete for AI tooling stack** | Blocks formal approval of Claude Code + MCP for Phase 2 rollout | WS2 Lead + InfoSec/Legal | Proactive engagement; review artifacts pre-submitted | June 2026 (GA) |
| B03 | **Design system not ready for AI-generated UI components** | Blocks Design-phase workflow adoption; affects ~6 pilot teams | Design System Team (escalated) | Interim workaround (human review of AI designs); design system sprint | June 2026 (GA) |

### Active Risks (🟡 — Monitoring)

| ID | Risk | Likelihood | Impact | Owner | Mitigation | Status |
|----|------|-----------|--------|-------|-----------|--------|
| R01 | E2E test suite instability in agentic workflows | Medium | High | WS2 + WS3 | Test automation working group; interim manual gates | 🟡 Monitoring |
| R02 | Low adoption beyond early adopters at scale (Phase 2) | Medium | High | WS4 Lead | AI Champions program; exec mandate; demo day events | 🟡 Monitoring |
| R03 | Tool fragmentation — teams adopt unapproved AI tools | Medium | Medium | WS2 Lead | Policy enforcement; curated approved stack | 🟡 Monitoring |
| R04 | Competing org priorities delay resources for Phase 2 | High | High | Kim Ross | Exec sponsor protected capacity; milestone accountability | 🔴 Active |
| R05 | Baseline data unavailable for M1 | Low | High | WS5 Lead | Data Eng engaged in Q2; proxy metrics from pilot in use | 🟡 Monitoring |
| R06 | 3X targets unachievable within timeline | Low | High | Kim Ross | Early pilot evidence (8X Payroll, 430 PRs/wk) is positive; phase-gate reviews | 🟢 Positive signal |
| R07 | AI-generated output quality issues at scale | Medium | Medium | WS3 Lead | Human-in-the-loop standards; PR review requirements | 🟡 Monitoring |

**Risk Ratings:** 🔴 Active/Escalated | 🟡 Monitoring | 🟢 Mitigated | ⚪ Closed

---

## Escalation Path

```
Team-level issue (pilot team or WS)
    → Workstream Lead (resolve within 48 hours)
        → TPM (Kim Ross) — if cross-workstream or >48 hours unresolved
            → Steering Committee — if impacts timeline, budget, or scope
                → Exec Sponsor — if impacts program viability or requires org-level decision
```

**Current P1 Escalations (as of May 2026):**
- B01: MCP Access — escalated to VP Eng / Platform Eng
- B02: Compliance Review — escalated to WS2 Lead + InfoSec/Legal with June deadline
- B03: Design System — escalated to Design System Team with June deadline

---

## Governance Cadence

| Forum | Participants | Frequency | Purpose |
|-------|------------|-----------|---------|
| WS Lead Sync | Kim Ross + all WS leads | Weekly | Status, blockers, dependencies |
| Steering Committee | Kim Ross + VPs Eng | Bi-weekly | Decisions, risks, scope |
| Exec Sponsor Update | Kim Ross + Exec Sponsor | Monthly | Strategic alignment, budget, escalations |
| 3X AI Native PDLC Demos 3X AI Native PDLC Demos & Learnings Learnings | All pilot teams + program team | Bi-weekly | Velocity demos, lessons learned sharing |
| Phase-Gate Review | All stakeholders | Per milestone | Go/no-go for next phase |

---

## Key Initiatives

| Initiative | Owner | Target | Status |
|-----------|-------|--------|--------|
| Unblock MCP server access (B01) | Platform Eng | June 2026 | 🔴 Active |
| Complete compliance review (B02) | WS2 + InfoSec | June 2026 | 🔴 Active |
| Unblock design system (B03) | Design System Team | June 2026 | 🔴 Active |
| Resolve E2E test stability (R01) | WS2 + WS3 | June 2026 | 🟡 In Progress |
| Risk register weekly refresh | Kim Ross | Ongoing | 🟢 Active |
| Phase-gate criteria confirmation | Kim Ross | Q2 2026 | 🟢 Defined |
| Responsible AI checklist for all tools | TBD | Q3 2026 | ⚪ Not Started |

---

## OKRs

**Objective:** Ensure all program decisions, risks, and AI deployments are governed with speed and safety — and that active blockers are resolved in time for Program GA.

| Key Result | Current | Target |
|-----------|---------|--------|
| Active blockers (B01–B03) resolved for GA | 0/3 resolved | 3/3 by mid-June 2026 |
| Risk register live and updated weekly | 🟢 Active | Ongoing |
| 100% of AI tools reviewed by InfoSec before Phase 2 | In progress | 100% by M5 |
| Zero unplanned escalations to Exec Sponsor | 2 active (MCP, design system) | Resolve; 0 in Phase 2 |
| All phase-gate criteria defined | 🟢 Defined | Done |

---

## Linked Issues

> Add GitHub issue links here as risk/blocker issues are created.
> Start with: [BLOCKER] MCP Server Access, [BLOCKER] Compliance Review, [BLOCKER] Design System Readiness, [RISK] E2E Test Stability

---

## Addendum: References

| Source | Relevance |
|--------|-----------|
| 3X AI Native PDLC Demos 3X AI Native PDLC Demos & Learnings Learnings Bi-Weekly Meeting Notes (internal) | Source of active blockers: MCP access, design system, E2E stability, compliance review |
| Fintech/Services AI Agentic Transformation Program Doc (internal) | Program risk context, workstream dependencies |
| Intuit Responsible AI Policy (internal) | Compliance and responsible AI requirements |
| Intuit InfoSec AI Tool Review Process (internal) | Compliance review process and SLA |
| NIST AI Risk Management Framework — https://www.nist.gov/system/files/documents/2023/01/26/AI%20RMF%201.0.pdf | AI risk management best practices framework |
| [Program Charter](../charter.md) | Decision rights and escalation authority |
| [Governance Model](../governance.md) | Full governance forums and RACI |
