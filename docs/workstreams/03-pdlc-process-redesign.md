# Workstream 3: PDLC Process Redesign

> **Workstream Lead:** TBD | **Status:** 🔵 Planning | **Last Updated:** May 2026

---

## Purpose

Redesign the Fintech/Services Product Development Lifecycle from the ground up with AI as a native participant at every phase. The goal is not to add AI steps to existing processes, but to eliminate waste, compress cycle time, and raise quality by reimagining how work gets done.

---

## Objectives

1. Map the current-state PDLC for Fintech and Services teams
2. Identify high-impact AI integration points at each PDLC phase
3. Design and document AI-native workflows for each phase
4. Pilot redesigned workflows with 2–3 teams in Q3 2026
5. Establish AI-native PDLC playbooks for org-wide adoption

---

## PDLC Phase Redesign Map

### Discovery
| Current State | AI-Native Future State |
|--------------|----------------------|
| Manual competitive research, stakeholder interviews | AI-synthesized market signals, auto-generated research briefs |
| PRD written manually over 2–4 weeks | AI-assisted PRD drafting with structured prompts in <1 week |
| Requirements defined in isolation | AI-suggested requirements based on historical delivery patterns |

### Design
| Current State | AI-Native Future State |
|--------------|----------------------|
| Design specs written manually | AI-generated spec drafts from PRD input |
| Architecture decisions in meetings | AI-suggested ADRs with trade-off analysis |
| Design review cycles take weeks | AI pre-checks for design completeness before human review |

### Build
| Current State | AI-Native Future State |
|--------------|----------------------|
| Code written manually | AI coding assistant for boilerplate, patterns, and scaffolding |
| Code review is fully manual | AI first-pass review flags issues before human review |
| Documentation written post-ship | AI generates inline docs and changelogs during build |

### Test
| Current State | AI-Native Future State |
|--------------|----------------------|
| Test cases written manually | AI-generated test suites from spec and code diff |
| Manual regression identification | AI-predicted regression risk by change surface |
| Bug reports are unstructured | AI-enriched bug reports with root cause suggestions |

### Ship
| Current State | AI-Native Future State |
|--------------|----------------------|
| Release notes written manually | AI-generated release notes from commit history |
| Deployment risk assessed manually | AI-scored deployment risk with rollback recommendation |
| Runbooks updated ad hoc | AI-updated runbooks based on deployment changes |

### Operate
| Current State | AI-Native Future State |
|--------------|----------------------|
| Incident triage is manual | AI-assisted triage with correlated signals |
| Post-mortems written manually | AI-drafted post-mortem from incident timeline |
| Performance insights require manual analysis | AI-generated continuous health summaries |

---

## Key Initiatives

| Initiative | Owner | Target | Status |
|-----------|-------|--------|--------|
| Current-state PDLC process map | TBD | Q2 2026 | ⚪ Not Started |
| AI integration point analysis per phase | TBD | Q2 2026 | ⚪ Not Started |
| Design AI-native workflow v1 (Build phase first) | TBD | Q3 2026 | ⚪ Not Started |
| Pilot with 2–3 volunteer teams | TBD | Q3 2026 | ⚪ Not Started |
| Document playbooks per phase | TBD | Q3–Q4 2026 | ⚪ Not Started |
| Full rollout process guide | TBD | Q4 2026 | ⚪ Not Started |

---

## OKRs

**Objective:** Ship AI-native PDLC workflows across all 6 phases, adopted by pilot teams by Q3 2026.

| Key Result | Measurement | Target |
|-----------|-------------|--------|
| Current-state process map complete | Binary | Q2 2026 |
| AI-native workflow defined for all 6 phases | Binary | Q3 2026 |
| Pilot teams reporting cycle time reduction | % | ≥30% reduction in pilot |
| Playbooks published and accessible | Binary | Q4 2026 |

---

## Dependencies

- WS2 (Tooling): redesigned workflows require finalized tool decisions
- WS4 (Change Mgmt): adoption depends on effective enablement
- WS5 (Measurement): baseline data needed to measure improvement

---

## Risks

| Risk | Mitigation |
|------|-----------|
| Teams resistant to process change | Early pilot volunteers + exec mandate |
| Workflow designs don't fit all team contexts | Modular playbook design with team-level flexibility |
| Process redesign outpaces tooling readiness | Phase tooling and process work in lockstep |

---

## Linked Issues

> Add GitHub issue links here as initiatives are created in the project board.

---

## References

- [Program Charter](../charter.md)
- [AI Tooling & Platform Workstream](02-ai-tooling-platform.md)
- [Measurement Workstream](05-measurement.md)
- DORA metrics framework
- Accelerate (Forsgren, Humble, Kim) — engineering performance benchmarks
