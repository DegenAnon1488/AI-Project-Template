# Framework Roadmap

**AI Project Template — Oster Engineering System v1.0.0**

This roadmap tracks development of the **framework itself**, not child projects.

---

## Phase 0.1: Core Skeleton — In Progress

**Goal:** Establish the repository identity and minimal structure.

**Deliverables:**

- [x] README.md
- [x] LICENSE (MIT)
- [x] FRAMEWORK.md
- [x] CHANGELOG.md
- [x] CONTRIBUTING.md
- [x] .gitignore
- [x] .project/ROADMAP.md
- [x] .project/PARKING_LOT.md
- [x] Minimal directory skeleton
- [ ] Git initialized on `main`
- [ ] GitHub repository created and linked

**Success:** A developer can clone the repo and understand what it is within five minutes.

---

## Phase 0.2: Project Memory System — Planned

**Goal:** Create `.project/` templates and memory infrastructure.

**Deliverables:**

- PROJECT.yaml schema and template
- MEMORY.md template
- BUILD_CONSTITUTION.md template
- ADR template and DECISIONS/ structure
- HISTORY/ structure (session log, milestones)
- Checklists (definition-of-done, architecture-review-gate)
- Bootstrap-ready templates in `.project/templates/`

**Success:** A bootstrapped child project has all memory files ready to customize.

---

## Phase 0.3: Cursor Configuration — Planned

**Goal:** Configure Cursor to understand OES on first open.

**Deliverables:**

- AGENTS.md (master agent instructions)
- Core rules (.mdc): framework-core, roles-and-gates, project-memory, no-orphan-code, git-standards
- Essential skills: plan-feature, implement-approved, smoke-test, update-memory
- Prompt library (plan, implement, smoke-test, session-closeout)
- Agent definitions (architect-reviewer, implementation-engineer, qa-validator)

**Success:** Cursor reads rules automatically and follows plan-before-code workflow.

---

## Phase 0.4: GitHub Governance — Planned

**Goal:** Professional GitHub templates and automation.

**Deliverables:**

- Issue templates (feature, bug, architecture, documentation, framework-improvement)
- Pull request template with OES checklist
- Standard labels (labels.yml)
- Framework validation workflow
- Markdown lint workflow

**Success:** New issues and PRs follow OES standards by default.

---

## Phase 0.5: Bootstrap Workflow — Planned

**Goal:** One-command new project setup.

**Deliverables:**

- bootstrap-project.ps1 (Windows)
- bootstrap-project.sh (Unix)
- Interactive 5-question setup
- Placeholder replacement in PROJECT.yaml, README, MEMORY.md
- new-project-from-template.md guide

**Success:** A new project can be bootstrapped in under ten minutes.

---

## Phase 0.6: Documentation Standards — Planned

**Goal:** Complete engineering standards library.

**Deliverables:**

- docs/engineering/OPERATING_SYSTEM.md
- docs/standards/ (git, testing, release, versioning)
- docs/architecture/STANDARDS.md
- docs/onboarding/FUTURE_DEVELOPER_TEST.md
- All project checklists (launch, release, completion)

**Success:** Every OES process is documented in the repo.

---

## Phase 0.7: Template Finalization — Planned

**Goal:** Ship v1.0.0 as a GitHub Template Repository.

**Deliverables:**

- validate-framework.sh script
- GitHub template repository enabled
- Branch protection on main
- Tag v1.0.0
- Future Developer Test passes on the framework itself
- Test bootstrap of one sample child project

**Success:** "Use this template" produces a fully functional OES project.

---

## v1.0.0 Release Criteria

All Phase 0.1–0.7 deliverables complete. See [.project/PARKING_LOT.md](PARKING_LOT.md) for items explicitly deferred.

---

**Last Updated:** 2026-07-09
