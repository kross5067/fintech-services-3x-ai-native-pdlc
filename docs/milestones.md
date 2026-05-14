# Program Milestones

> **Last Updated:** May 2026 | **TPM:** Kim Ross

---

## Milestone Summary

| ID | Milestone | Phase | Target Date | Status | Owner |
|----|-----------|-------|-------------|--------|-------|
| M0 | Program Foundation Complete | Phase 0 | Q2 2026 | 🟢 Complete | Kim Ross |
| M1 | Baseline Metrics Established | Phase 0 | Q2 2026 | 🟡 In Progress | WS5 Lead |
| M2 | AI Tooling Stack Approved & Deployed | Phase 1 | Q2 2026 | 🟡 In Progress | WS2 Lead |
| M3 | AI-Native PDLC Workflows Defined | Phase 1 | Q2 2026 | 🟡 In Progress | WS3 Lead |
| M4 | Prometheus GA — All Pilot Teams Live | Phase 1 | Mid-June 2026 | 🟡 In Progress | Kim Ross |
| M5 | Pilot Results Reviewed (Phase Gate) | Phase 1→2 | End of Q3 2026 | ⚪ Not Started | Kim Ross |
| M6 | Full Fintech/Services Rollout | Phase 2 | Q4 2026 | ⚪ Not Started | Kim Ross |
| M7 | 3X Outcomes Validated | Phase 3 | Q1 2027 | ⚪ Not Started | WS5 Lead |

**Status Key:** 🟢 Complete | 🟡 In Progress | 🔴 At Risk | ⚪ Not Started

---

## Milestone Details

### M0 — Program Foundation Complete
**Target:** Q2 2026 | **Status:** 🟢 Complete
**Exit Criteria:**
- [x] Program charter approved by exec sponsors
- [x] All 6 workstream leads named
- [x] Governance cadence (steering committee, WS lead sync) active
- [x] Program GitHub repo live and structured
- [x] OKRs defined for all workstreams
- [x] Prometheus pilot team roster confirmed (15 teams)

**Owner:** Kim Ross

---

### M1 — Baseline Metrics Established
**Target:** End of Q2 2026 | **Status:** 🟡 In Progress
**Exit Criteria:**
- [x] Claude Code adoption baseline captured — **94.73% across pilot teams**
- [x] PR velocity baseline captured — **430 PRs/week (IBCC team)**
- [ ] Feature cycle time baseline captured (last 6 months of JIRA data)
- [ ] Escaped defect rate baseline captured (last 4 quarters)
- [ ] Developer experience survey launched and baseline score recorded
- [ ] DORA metrics baseline captured for all pilot teams
- [ ] Baseline report approved by steering committee

**Current signals:**
- Alpha 1 IBCC: 430 PRs/week (AI-assisted)
- Alpha 2 Payroll: 8X velocity improvement observed
- 59ers/Five Niners: 99.998% availability maintained
- SREBot: 203 engineering hours saved per period

**Owner:** WS5 Lead

---

### M2 — AI Tooling Stack Approved & Deployed
**Target:** Q2 2026 | **Status:** 🟡 In Progress — **🔴 BLOCKER: MCP Access**
**Exit Criteria:**
- [x] Claude Code deployed and adopted across pilot teams (94.73% adoption)
- [x] Initial MCP server configuration defined
- [ ] MCP server access unblocked for all 15 pilot teams ⚠️ **Active blocker**
- [ ] Compliance review completed for full AI tooling stack ⚠️ **Active blocker**
- [ ] Context graph infrastructure provisioned
- [ ] Skill registry established and accessible
- [ ] Self-service provisioning available to all pilot teams
- [ ] Tooling telemetry in place for adoption tracking

**Blocking issues:**
- MCP server access gating — not all pilot teams have access; escalated to Platform team
- Compliance review not yet complete — InfoSec/Legal review in progress

**Owner:** WS2 Lead

---

### M3 — AI-Native PDLC Workflows Defined
**Target:** Q2 2026 | **Status:** 🟡 In Progress — **🔴 BLOCKER: Design System**
**Exit Criteria:**
- [x] Agentic Development Lifecycle (ADLC) model documented
- [x] AI-native workflow defined for Build and Test phases (observed from pilot teams)
- [ ] AI-native workflow documented for Discovery, Design, Ship, and Operate phases
- [ ] Design system readiness confirmed for AI-generated UI components ⚠️ **Active blocker**
- [ ] E2E test stability requirements defined for agentic workflows ⚠️ **At risk**
- [ ] Playbooks published and accessible to all pilot teams
- [ ] Workflows reviewed and approved by sample of engineers and PMs

**Blocking issues:**
- Design system not ready for AI-generated UI components — impacting Design phase workflow definition
- E2E test suite instability in agentic workflows — test automation working group engaged

**Owner:** WS3 Lead

---

### M4 — Prometheus GA — All Pilot Teams Live
**Target:** Mid-June 2026 | **Status:** 🟡 In Progress
**Exit Criteria:**
- [x] Alpha 1 (IBCC) and Alpha 2 (Payroll) fully live — evidence of 8X velocity and 430 PRs/week
- [ ] All 15 Prometheus pilot teams onboarded and active on AI-native PDLC
- [ ] MCP access resolved for all teams *(depends on M2 blocker)*
- [ ] E2E test stability resolved for agentic workflows *(depends on M3)*
- [ ] Prometheus GA readiness review completed and approved by steering committee
- [ ] Pilot measurement instrumentation active across all teams

**Pilot teams still in onboarding:** Critical SMS Risk, Payments Surcharging, AI Model Dev/Capital Onboarding

**Owner:** Kim Ross

---

### M5 — Pilot Results Reviewed (Phase Gate)
**Target:** End of Q3 2026 | **Status:** ⚪ Not Started
**Exit Criteria:**
- [ ] Prometheus GA retrospective published (post mid-June)
- [ ] Cycle time improvement vs. baseline measured for at least 5 pilot teams
- [ ] Escaped defect rate vs. baseline measured
- [ ] Developer experience survey results compared to baseline
- [ ] Lessons learned documented and shared
- [ ] Go/no-go decision for Phase 2 (full rollout) made by exec sponsor

**Phase Gate:** Exec Sponsor go/no-go. No-Go = extend pilot; adjust approach.

**Owner:** Kim Ross

---

### M6 — Full Fintech/Services Rollout
**Target:** Q4 2026 | **Status:** ⚪ Not Started
**Exit Criteria:**
- [ ] All Fintech/Services teams (beyond pilot cohort) onboarded to AI-native PDLC
- [ ] All engineers completed role-based AI enablement training
- [ ] AI Champions active in all orgs
- [ ] Measurement dashboards live for all teams
- [ ] Governance and compliance processes embedded org-wide

**Owner:** Kim Ross

---

### M7 — 3X Outcomes Validated
**Target:** Q1 2027 | **Status:** ⚪ Not Started
**Exit Criteria:**
- [ ] Feature cycle time: 3X improvement vs. M1 baseline measured and validated
- [ ] Escaped defect rate: 3X reduction vs. M1 baseline measured and validated
- [ ] AI-assisted task coverage: 3X of initial benchmark sustained at scale
- [ ] Developer experience: 3X improvement vs. M1 baseline measured and validated
- [ ] 3X validation report delivered to exec sponsors
- [ ] Program retrospective complete
- [ ] Learnings shared with Intuit-wide AI Transformation program (Enablers/Pathfinders)

**Owner:** WS5 Lead

---

## Phase Gate Criteria

Phase gates are go/no-go checkpoints between program phases. The exec sponsor makes the final call.

| Gate | Between Phases | Decision Owner | No-Go Consequence |
|------|--------------|---------------|------------------|
| Gate 0→1 | Foundation → Pilot | Exec Sponsor | ✅ Passed — Pilot active |
| Gate 1→2 | Pilot → Scale | Exec Sponsor | Decision at M5 (end of Q3 2026) |
| Gate 2→3 | Scale → Validate | Exec Sponsor | Decision at M6 completion |

---

## References

- [Program Charter](charter.md)
- [Metrics & Measurement](metrics.md)
- [Governance Model](governance.md)
- Prometheus Demos & Learnings — Bi-Weekly Meeting Notes (internal Google Doc)
