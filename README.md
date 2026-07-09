# AI Project Template

**Version 1.0.0** — A reusable engineering template for professional software projects.

This repository is an **Engineering Operating System**, not an application. Use it as the starting point for every new software project: AI agents, PWAs, SaaS products, APIs, trading systems, knowledge bases, and internal tools.

Internally, the methodology is referred to as the **Oster Engineering System (OES)**.

---

## What This Is

| This template provides | This template does NOT provide |
|------------------------|-------------------------------|
| Project structure and standards | Application code |
| Cursor AI configuration | Business logic |
| Documentation templates | Demo apps or placeholder features |
| GitHub governance templates | Domain-specific implementations |
| Bootstrap workflow | Pre-built tech stack |

---

## Supported Project Types

This framework bootstraps any professional software project, including:

- AI Agents
- PWAs
- SaaS
- APIs
- Mobile Apps
- Desktop Apps
- Trading Systems
- Scanners
- Knowledge Bases
- RAG Systems
- Automation Platforms
- Dashboards
- Internal Business Tools
- Data Pipelines
- CLI Applications
- Libraries
- Microservices

---

## Three-Role Model

| Role | Actor | Responsibility |
|------|-------|----------------|
| **Product Owner** | You | Business goals, scope approval, validation |
| **Chief Software Architect** | ChatGPT | Architecture, plans, review, drift prevention |
| **Implementation Team** | Cursor | Code, tests, docs — approved plans only |

---

## Quick Start

### Create a New Project

1. On GitHub, click **Use this template** on this repository.
2. Name your new repository (e.g., `meme-coin-scanner`).
3. Clone locally and open in Cursor.
4. Run the bootstrap script (available in Phase 0.5):

   ```powershell
   .\scripts\bootstrap-project.ps1
   ```

5. Follow the setup prompts and begin Phase 0 (Foundation).

### Work on This Framework

If you are improving the template itself, read [FRAMEWORK.md](FRAMEWORK.md) first.

---

## Repository Structure

```
AI-Project-Template/
├── README.md                 # This file
├── FRAMEWORK.md              # What this repo is and is not
├── LICENSE                   # MIT
├── CHANGELOG.md              # Framework version history
├── CONTRIBUTING.md           # How to improve the framework
│
├── .project/                 # Project memory and operating system
├── .cursor/                  # Cursor rules, skills, prompts, agents
├── .github/                  # Issue/PR templates, Actions, labels
├── docs/                     # Engineering standards and guides
└── scripts/                  # Bootstrap and validation utilities
```

---

## Universal Build Workflow

Every feature follows this sequence:

1. Define the business goal.
2. Define the minimum useful version.
3. Write an architecture plan.
4. Cursor produces a plan — **no file edits yet**.
5. Review and approve the plan.
6. Cursor implements the smallest safe change.
7. Cursor runs tests or a smoke test.
8. Review results and validate manually.
9. Commit to GitHub.
10. Update project memory and documentation.

Never skip planning or testing.

---

## Documentation

| Document | Purpose |
|----------|---------|
| [FRAMEWORK.md](FRAMEWORK.md) | Framework identity and rules |
| [.project/ROADMAP.md](.project/ROADMAP.md) | Framework development phases |
| [.project/PARKING_LOT.md](.project/PARKING_LOT.md) | Ideas deferred beyond v1.0 |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to contribute improvements |
| [CHANGELOG.md](CHANGELOG.md) | Version history |

Additional standards and guides are added in later implementation phases.

---

## Version

**Current:** v1.0.0 (Phase 0.1 — Core skeleton)

See [CHANGELOG.md](CHANGELOG.md) for release history.

---

## License

MIT License — see [LICENSE](LICENSE).
