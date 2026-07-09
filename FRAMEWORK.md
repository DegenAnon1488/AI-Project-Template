# Framework Guide

**AI Project Template** — Oster Engineering System (OES) v1.0.0

---

## Purpose

This repository is a **GitHub Template Repository** that serves as the permanent engineering foundation for every software project. It is company infrastructure, not a product.

---

## What This Repository IS

- A reusable project template
- An Engineering Operating System (OES)
- A Cursor-aware project bootstrap
- A documentation and governance scaffold
- A standards library for professional software development
- A system that improves over time through lessons learned

---

## What This Repository IS NOT

- An application
- A demo or example project
- Tied to any specific business or domain
- A place for business logic or placeholder features
- A pre-built tech stack implementation

---

## Core Rules

1. **Infrastructure only** — No application code in the template.
2. **Plan before code** — Architecture review gate on every feature.
3. **Smallest safe change** — Preserve working behavior.
4. **GitHub is truth** — All meaningful changes are committed.
5. **Documentation is software** — Docs stay synchronized with the project.
6. **No orphan code** — Every file has a documented purpose.
7. **Repository self-sufficiency** — No external chat history required to operate.
8. **Ten-year rule** — Plain Markdown and YAML only; no proprietary lock-in.

---

## Roles

### Product Owner (You)

- Defines business goals and scope
- Approves plans and releases
- Validates with real users or data
- Makes final product decisions

### Chief Software Architect (ChatGPT)

- Designs system architecture
- Writes implementation prompts
- Reviews Cursor plans and outputs
- Prevents architecture drift

### Implementation Team (Cursor)

- Writes code and tests
- Implements **approved plans only**
- Maintains documentation sync
- Does not invent architecture or product direction

---

## Framework vs. Child Project

| Aspect | Framework Repo | Child Project (from template) |
|--------|---------------|-------------------------------|
| Purpose | Maintain the template | Build a product |
| Code | None | Application code added by team |
| `.project/` | Framework roadmap | Project-specific memory |
| Updates | Framework versions | Independent versioning |
| Name | `AI-Project-Template` | Your project name |

---

## Version 1.0 Scope

Version 1.0 delivers a **stable, professional foundation**:

| Phase | Deliverable | Status |
|-------|-------------|--------|
| 0.1 | Core skeleton, README, LICENSE | Complete |
| 0.2 | `.project/` memory system and templates | Complete |
| 0.2.5 | Framework QA / Milestone QA gate | Complete |
| 0.3 | `.cursor/` rules, skills, prompts, agents | Planned |
| 0.4 | `.github/` templates, labels, Actions | Planned |
| 0.5 | Bootstrap scripts and new-project workflow | Planned |
| 0.6 | Documentation standards and checklists | Planned |
| 0.7 | GitHub template configuration and validation | Planned |

Features beyond v1.0 are tracked in [.project/PARKING_LOT.md](.project/PARKING_LOT.md).

---

## Improving the Framework

When a child project reveals a useful pattern:

1. Open an issue using the framework-improvement template (Phase 0.4).
2. Document the lesson in the issue.
3. Propose a minimal change to the template.
4. Merge after review.

Do not add speculative features. If an idea is valuable but not required for the current version, add it to the parking lot.

---

## License

MIT — see [LICENSE](LICENSE).
