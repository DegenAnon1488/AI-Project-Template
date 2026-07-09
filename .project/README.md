# .project/

Project memory and operating system for the Oster Engineering System (OES).

Cursor and developers should read [MEMORY.md](MEMORY.md) first to understand current project state.

---

## Live Files

| File | Purpose |
|------|---------|
| [PROJECT.yaml](PROJECT.yaml) | Machine-readable project identity |
| [MEMORY.md](MEMORY.md) | Current state — update every session |
| [BUILD_CONSTITUTION.md](BUILD_CONSTITUTION.md) | Non-negotiable build rules |
| [ROADMAP.md](ROADMAP.md) | Framework development phases |
| [PARKING_LOT.md](PARKING_LOT.md) | Ideas deferred beyond v1.0 |

---

## Directories

| Directory | Purpose |
|-----------|---------|
| [DECISIONS/](DECISIONS/) | Architecture Decision Records |
| [HISTORY/](HISTORY/) | Session logs and milestones |
| [CHECKLISTS/](CHECKLISTS/) | Definition of done, architecture review gate |
| [templates/](templates/) | Bootstrap templates for child projects (Phase 0.5) |

---

## Usage

### Working on this framework

1. Read `MEMORY.md`
2. Check `ROADMAP.md` for current phase
3. Follow `BUILD_CONSTITUTION.md`
4. Update `MEMORY.md` and `HISTORY/SESSION_LOG.md` at session end

### Bootstrapping a child project (Phase 0.5)

Templates in `templates/` are copied and customized via the bootstrap script. Placeholders use `{{PROJECT_NAME}}`, `{{OWNER}}`, etc.

---

**Framework version:** 1.0.0
