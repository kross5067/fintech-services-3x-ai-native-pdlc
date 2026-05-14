# GitHub Project Board Setup Guide

> **Program:** Fintech/Services 3X AI Native PDLC Transformation
> **Purpose:** This guide walks you through setting up the GitHub Project board for this program from scratch.

---

## Step 1: Create the Project

1. Go to the repo and click the **Projects** tab
2. Click **New project**
3. Select **Board** layout (or **Roadmap** if you prefer timeline view)
4. Name it: `3X AI Native PDLC — Program Board`
5. Add a description: *Tracks all workstream initiatives, milestones, and risks for the Fintech/Services 3X AI Native PDLC Transformation*

---

## Step 2: Configure Columns

Set up the following columns (swimlanes) to reflect the work lifecycle:

| Column | Purpose |
|--------|---------|
| 🗂 **Backlog** | Identified but not yet prioritized |
| 🔵 **Up Next** | Prioritized and ready to start this sprint/cycle |
| 🟡 **In Progress** | Actively being worked |
| 🔍 **In Review / Blocked** | Awaiting review or blocked by dependency |
| ✅ **Done** | Complete — exit criteria met |

---

## Step 3: Configure Labels

Create the following labels in the repo (Settings → Labels):

| Label | Color | Use |
|-------|-------|-----|
| `workstream-1` | `#0052CC` | Strategy & Alignment |
| `workstream-2` | `#0075CA` | AI Tooling & Platform |
| `workstream-3` | `#7057FF` | PDLC Process Redesign |
| `workstream-4` | `#008672` | Change Mgmt & Enablement |
| `workstream-5` | `#E4E669` | Measurement & Value |
| `workstream-6` | `#D93F0B` | Governance & Risk |
| `milestone` | `#0E8A16` | Program milestone tracker |
| `risk` | `#B60205` | Active risk |
| `blocker` | `#E11D48` | Active blocker |
| `decision-needed` | `#F9D0C4` | Requires governance decision |
| `phase-0` | `#BFD4F2` | Foundation phase |
| `phase-1` | `#BFD4F2` | Pilot phase |
| `phase-2` | `#BFD4F2` | Scale phase |
| `phase-3` | `#BFD4F2` | Validate phase |

---

## Step 4: Configure Milestones

Create GitHub Milestones for each program milestone:

1. Go to Issues → Milestones → **New milestone**
2. Create one milestone per program milestone:

| GitHub Milestone Name | Due Date |
|----------------------|---------|
| M0 — Program Foundation Complete | End of Q2 2026 |
| M1 — Baseline Metrics Established | End of Q2 2026 |
| M2 — AI Tooling Stack Approved | Q3 2026 |
| M3 — AI-Native PDLC Workflows Defined | Q3 2026 |
| M4 — Pilot Teams Live | Q3 2026 |
| M5 — Pilot Phase Gate | End of Q3 2026 |
| M6 — Full Rollout | Q4 2026 |
| M7 — 3X Outcomes Validated | Q1 2027 |

---

## Step 5: Seed Initial Issues

Use the issue templates to create seed issues for each workstream:

1. Go to Issues → **New issue**
2. Choose the **Workstream Initiative** template
3. Create one issue per initiative listed in each workstream's markdown doc
4. Apply the appropriate `workstream-#` and `phase-#` labels
5. Assign to the relevant GitHub milestone
6. Add to the project board

**For milestones,** create one issue per program milestone using the **Milestone Tracker** template.

---

## Step 6: Set Up Automations (Optional but Recommended)

In the Project board settings, enable automations:

| Trigger | Action |
|---------|--------|
| Issue opened | → Move to **Backlog** |
| Issue assigned | → Move to **Up Next** |
| Pull request opened | → Move to **In Progress** |
| Issue closed | → Move to **Done** |

---

## Step 7: Roadmap View (Optional)

For a timeline view of milestones:

1. Click **+ New view** in the project board
2. Select **Roadmap**
3. Set the date field to **Due Date**
4. Group by **Milestone**
5. Name it: `Program Roadmap`

---

## Maintenance

- **Workstream leads** update their issues weekly before the WS lead sync
- **TPM (Kim Ross)** updates milestone tracker issues bi-weekly before the steering committee
- **Risks and blockers** are logged immediately when identified — don't wait for the weekly sync

---

## References

- [GitHub Projects Documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- [Program README](../README.md)
- [Governance Model](../docs/governance.md)
