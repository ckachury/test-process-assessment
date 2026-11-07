# Assessment method

This is the step-by-step method behind the toolkit. It works with TMMi or TPI NEXT; where the models differ, the difference is noted.

## Roles

| Role | Responsibility |
|---|---|
| Sponsor | Owns the business goals, approves scope and receives the results |
| Lead assessor | Plans the assessment, verifies evidence, scores and writes the report |
| Facilitator | Designs and runs the workshops (can be the lead assessor) |
| Co-facilitator / note taker | Clusters contributions live, manages breakout rooms, writes session notes |
| Internal coordinator | Schedules people, provides documents and tool access |

## Phase 0 · Prepare

**Goal:** agree why the assessment is being done and what it covers.

Activities:

- Kick-off with the sponsor: objectives, scope (teams, systems, locations), constraints and confidentiality rules.
- **Business drivers workshop** with people who know the organisation's strategy. Output: three to five prioritised drivers, each with at least one signal of success.
- Stakeholder map: who decides, who participates, who is affected.
- Document request list: test policy and strategy, plans, reports, defect data, tool exports, organisation charts, previous audits.
- Communication to participants: purpose, what will be done with the information, and that individuals are not being evaluated.

Outputs: assessment plan, business drivers, stakeholder map, document inventory.

## Phase 1 · Gather evidence

**Goal:** understand current practice from several angles.

| Source | How | What it shows best |
|---|---|---|
| Document review | Read policies, plans, reports, templates | What is defined and how formal it is |
| Tool data | Exports from test management, defect and CI tools | What actually happens, at scale |
| Interviews | 45–60 min, one role at a time ([guide](../templates/interview-guide.md)) | Reasons, constraints, decisions |
| Workshops | 60 min, 6–10 people, Liberating Structures ([designs](https://github.com/ckachury/liberating-structures-for-quality/blob/HEAD/sessions/test-process-assessment-workshops.md)) | Shared practice, tensions, ideas from the team |
| Observation | Attend a planning, a triage or a release meeting | Real involvement of stakeholders |

Rules:

- Workshops never ask about checkpoints literally. People describe their practice; assessors map it later.
- Sessions with operational staff run without their direct managers.
- Every contribution goes into the [evidence matrix](../templates/evidence-matrix.md) the same day, tagged with its source.

## Phase 2 · Verify and score

**Goal:** a defensible maturity profile.

- Map each piece of evidence to a process area (TMMi) or key area (TPI NEXT) and, where possible, to the checkpoint or practice it supports or contradicts.
- A checkpoint or practice is rated **met** only when at least two independent sources support it and none contradicts it.
- Record a **confidence level** for each area: high (three or more consistent sources), medium (two), low (one, or sources in conflict).
- Unknown is recorded as *not assessed*, never as *not met* or *met*.
- Review borderline ratings with a second assessor.

Output: maturity profile per area with confidence level and the evidence behind each rating.

## Phase 3 · Analyse

**Goal:** find the gaps that matter to the business.

- Translate each business driver into the areas that support it. Example: *"reduce production incidents"* points to test strategy, test design techniques, defect management and metrics.
- Define the **target profile**: the maturity each area needs to support the drivers, not the highest level possible.
- Compare current and target profiles. Look for root causes that cut across areas, such as missing ownership, unstable environments or no feedback from production.

## Phase 4 · Roadmap

**Goal:** a plan people can start on Monday.

- **Quick wins (4 to 8 weeks):** improvements teams can make without budget or permission. Many come straight from the workshops.
- **Improvement clusters:** in TPI NEXT, use the clusters to order checkpoints; in TMMi, group the practices of the next level that the drivers need most.
- Each item has an owner, an expected effect on a business driver, and a date.
- Change management: who needs to be convinced, what training is needed, what stops being done.

## Phase 5 · Follow up

- A small KPI dashboard built from the signals of success defined in phase 0.
- Monthly review of roadmap progress with the sponsor.
- Re-assessment of the areas in scope after 6 to 12 months.

## Sample plan

An example for one quality department of medium size, about 11 weeks:

| Weeks | Work |
|---|---|
| 1 | Kick-off, business drivers workshop, document request |
| 2–3 | Document and tool data review, interview schedule |
| 3–6 | Interviews and three area workshops |
| 6–8 | Verification, scoring, second-assessor review |
| 8–9 | Target profile and gap analysis |
| 9–10 | Roadmap and KPI proposal, validation with key stakeholders |
| 11 | Final report and presentation to the sponsor |

Reusing evidence from previous audits or projects shortens phases 1 and 2. Record what was reused and how recent it is.
