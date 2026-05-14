# Governance Model

> **Last Updated:** May 2026 | **TPM:** Kim Ross

---

## Governance Principles

1. **Decide at the right level** — push decisions down to the workstream level wherever possible; escalate only what genuinely needs it
2. **Transparency by default** — all decisions, risks, and status are visible in this repo and the project board
3. **Speed over perfection** — favor a good decision made fast over a perfect decision made slow, with documented reasoning
4. **One source of truth** — GitHub is the system of record; all updates flow here

---

## Decision Rights (RACI Summary)

| Decision Type | Responsible | Accountable | Consulted | Informed |
|--------------|------------|------------|---------|---------|
| Workstream-level decisions | WS Lead | TPM | Relevant WS leads | All |
| Cross-workstream decisions | TPM | VP Eng | All WS leads | All stakeholders |
| Scope changes | TPM | Exec Sponsor | Steering committee | All |
| Budget reallocation | TPM | Exec Sponsor | Finance | Steering committee |
| AI tool approval | WS2 Lead | VP Eng | InfoSec, Legal | All engineers |
| Phase-gate go/no-go | TPM | Exec Sponsor | All WS leads | All stakeholders |
| Risk escalation (P1) | TPM | Exec Sponsor | Relevant WS leads | All |

---

## Governance Forums

### Weekly Workstream Lead Sync
- **Participants:** Kim Ross (TPM) + all workstream leads
- **Cadence:** Weekly, 60 minutes
- **Purpose:** Status updates, cross-workstream dependency review, blocker resolution
- **Outputs:** Updated GitHub Issues; risk register updates

### Bi-Weekly Steering Committee
- **Participants:** Kim Ross + VP Engineering (Fintech & Services) + WS leads as needed
- **Cadence:** Bi-weekly, 60 minutes
- **Purpose:** Decisions, risk review, scope and priority alignment
- **Outputs:** Decisions logged as GitHub Issues; leadership report published

### Monthly Exec Sponsor Update
- **Participants:** Kim Ross + Exec Sponsor(s)
- **Cadence:** Monthly, 30 minutes
- **Purpose:** Strategic alignment, budget, escalation
- **Outputs:** Exec summary published to GitHub

### Phase-Gate Review
- **Participants:** All stakeholders
- **Cadence:** At each program milestone (M0, M1, M4, M5, M6, M7)
- **Purpose:** Go/no-go decision for next phase
- **Outputs:** Phase-gate decision logged; program charter updated if scope changes

---

## Escalation Path

```
Issue identified at team or workstream level
    ↓
Workstream Lead attempts resolution (SLA: 48 hours)
    ↓ (if unresolved or cross-workstream)
TPM (Kim Ross) — coordinates resolution (SLA: 72 hours)
    ↓ (if impacts timeline, budget, or scope)
Steering Committee — decision at next bi-weekly or emergency call
    ↓ (if impacts program viability or requires org-level decision)
Exec Sponsor — final authority
```

---

## Issue Management

All program work is tracked in GitHub Issues using standardized templates:
- **Workstream Initiative** — for new work items within a workstream
- **Milestone Tracker** — for tracking progress against program milestones
- **Risk/Blocker** — for logging risks and active blockers

Labels used:
| Label | Meaning |
|-------|---------|
| `workstream-1` through `workstream-6` | Workstream ownership |
| `milestone` | Tied to a program milestone |
| `risk` | Active risk being managed |
| `blocker` | Active blocker requiring escalation |
| `decision-needed` | Requires a governance decision |
| `phase-0` through `phase-3` | Program phase |

---

## Change Management for Scope

Any change to program scope, timeline, or budget follows this process:

1. Change request documented as a GitHub Issue (label: `decision-needed`)
2. Impact assessment completed by TPM (effort, timeline, cost)
3. Decision made at appropriate governance level (see RACI above)
4. Charter and affected workstream docs updated within 3 business days of decision
5. Change communicated to all stakeholders via steering committee update

---

## References

- [Program Charter](charter.md)
- [Risk Register](workstreams/06-governance-risk.md)
- [Milestones](milestones.md)
- [GitHub Project Board Setup](./../.github/project-board-setup.md)
