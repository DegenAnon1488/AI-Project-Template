# Architecture Decision Records

This directory stores Architecture Decision Records (ADRs) for this project.

---

## Format

Each decision is a numbered Markdown file:

```
DECISIONS/
├── README.md           # This index
├── 0001-use-fastapi.md
├── 0002-offline-first-pwa.md
└── ...
```

Use [0000-template.md](0000-template.md) or [.project/templates/ADR.template.md](../templates/ADR.template.md) to create new records.

---

## When to Write an ADR

Create an ADR when a decision is:

- Hard to reverse
- Affects architecture or module boundaries
- A tech stack or tooling choice
- A scope or security decision
- Likely to confuse a future developer if undocumented

---

## Index

| # | Title | Status | Date |
|---|-------|--------|------|
| — | No decisions recorded yet | — | — |

Update this table when adding ADRs.

---

## Status Values

- **proposed** — Under discussion
- **accepted** — Decision is active
- **deprecated** — No longer recommended
- **superseded** — Replaced by a newer ADR (link to it)
