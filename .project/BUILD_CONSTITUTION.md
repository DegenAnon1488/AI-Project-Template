# Build Constitution

**Oster Engineering System (OES)** — Non-negotiable build rules for every project using this template.

Version: 1.0

---

## Core Principle

Do not let AI randomly build. AI implements a clear architecture — it does not invent one mid-build.

---

## Roles

### Product Owner

- Defines business goals and scope
- Approves plans and releases
- Validates with real users or data
- Makes final product decisions

### Chief Software Architect (ChatGPT)

- Designs system architecture
- Defines module boundaries
- Writes implementation prompts
- Reviews plans and outputs
- Prevents architecture drift

### Implementation Team (Cursor)

- Writes code and tests
- Implements **approved plans only**
- Maintains documentation sync
- Does not invent architecture or product direction

---

## Universal Build Workflow

Every feature follows this sequence:

1. Define the business goal.
2. Define the minimum useful version.
3. Decide where logic belongs.
4. Write an architecture plan.
5. Give Cursor a focused prompt.
6. Cursor produces a plan — **no file edits yet**.
7. Review and approve the plan.
8. Cursor implements the smallest safe change.
9. Cursor runs tests or a smoke test.
10. Review results and validate manually.
11. Commit to GitHub.
12. Update project memory and documentation.

Never skip planning or testing.

---

## Pipeline Separation

Separate processing into distinct stages. Do not mix unless there is a strong reason:

```
Raw Input
  → Extractor / Formatter        (structure, no interpretation)
  → Structured Data              (validated schema)
  → Reasoning / Decision Engine  (rules, scoring, recommendations)
  → Output Generator             (reports, alerts, API responses)
  → QA / Validation              (contradictions, missing evidence)
```

Each project defines its own pipeline stages in `PROJECT.yaml` and architecture docs.

---

## Non-Negotiable Rules

1. Build the smallest useful version first.
2. Keep modules separate.
3. Do not mix data collection, reasoning, and reporting.
4. Do not add features without approval.
5. Do not rewrite working code without reason.
6. Use stable input/output contracts.
7. Prefer JSON schemas for agent handoffs.
8. Preserve raw data when possible.
9. Test every change.
10. Commit only after review.
11. Run Milestone QA after every completed phase before starting the next.

---

## Feature Creep Filter

Before building any feature, ask:

1. Does this help get users or customers?
2. Does this improve accuracy, speed, or reliability?
3. Does this reduce manual work?
4. Is this required for the current version?

If none apply, defer to the roadmap.

---

## Architecture Review Gate

Before coding, complete [architecture-review-gate.md](CHECKLISTS/architecture-review-gate.md).

If the ten questions are unclear, do not code yet.

---

## Milestone QA Rule

After every completed phase or milestone, run Framework QA before starting the next phase.

This applies even if the phase was documentation-only.

Verify:

- Required files exist
- Documentation is internally consistent
- Cross-references work
- ROADMAP reflects current status
- MEMORY.md reflects current status
- CHANGELOG is updated
- No unapproved scope was added
- No application code was introduced in the framework repo
- Future Developer Test passes
- Documentation accuracy (no stale metadata: commit hashes, milestone status, version numbers, roadmap state)

Record results in [HISTORY/SESSION_LOG.md](HISTORY/SESSION_LOG.md). Fix failures before proceeding.

---

## Documentation Rule

Documentation is part of the software. Update docs in the same change as code. The repository must be self-sufficient — no external chat history required.

---

## Documentation Accuracy Rule

If a commit changes information that is recorded elsewhere in the repository (commit hashes, milestone status, version numbers, roadmap state, release information, roadmap progress, etc.), all affected documentation must be updated before the phase is considered complete.

The repository should never contain stale metadata. Documentation is considered part of the software.

Milestone QA must verify documentation accuracy before a phase is closed.

---

## Framework Dogfooding Rule

Every improvement to the engineering framework must first be used by the framework itself before being recommended for child projects.

The framework should continuously validate its own standards. New engineering practices should be proven inside the framework before becoming part of the reusable project template.

---

## Rule of Proven Need

Infrastructure should only be promoted into the framework after it has demonstrated value through real projects.

Do not build organizational structures because they might be useful. Build them because multiple projects have proven they are useful.

The framework should evolve from experience rather than speculation.

Every new rule, template, agent, folder, prompt, workflow, or standard must earn its place through actual use. Avoid speculative engineering. Prefer proven engineering.

The framework should never become smarter than the experience that created it.

---

## Master Rule

Use AI as an implementation force multiplier, not as an uncontrolled product manager.

You own the direction. ChatGPT designs and reviews. Cursor builds. GitHub records the truth.
