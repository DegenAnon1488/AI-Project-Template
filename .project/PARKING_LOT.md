# Parking Lot

Ideas that are **valuable but not required for v1.0**. Do not implement these until v1.0 ships and a deliberate decision is made to include them.

---

## Framework Enhancements (Post v1.0)

| Idea | Why It Waits |
|------|-------------|
| Framework migration guide (upgrade child projects between framework versions) | No child projects on v1.0 yet |
| Multi-language bootstrap scripts beyond PowerShell and Bash | v1.0 needs one reliable path first |
| Pre-commit hook templates | Added when child projects have code |
| Docker compose templates | Domain-specific; belongs in child projects |
| Tech stack starter kits (Next.js, FastAPI, etc.) | Violates "no application code" rule |
| Industry pack templates (healthcare, trading, vehicle) | Domain-specific; child project concern |
| Automated framework version sync across child repos | Requires multiple child projects first |
| GitHub Copilot instructions file | Evaluate after Cursor rules prove sufficient |
| VS Code settings sync | Cursor-specific focus for v1.0 |
| Dependabot configuration | Minimal deps in v1.0 framework |
| Code coverage thresholds in CI | No code to cover in template |
| Semantic release automation | Manual releases sufficient for v1.0 |
| Framework CLI tool (`oes init`) | Bootstrap script sufficient for v1.0 |
| Web-based project setup wizard | GitHub template + script sufficient |
| Integration with ChatGPT custom GPT for architect role | Process documentation sufficient for v1.0 |

---

## Documentation (Post v1.0)

| Idea | Why It Waits |
|------|-------------|
| Video walkthrough of bootstrap process | Record after v1.0 is stable |
| Architecture pattern catalog with diagrams | Patterns emerge from real projects |
| Compliance pack (HIPAA, SOC2 checklists) | Domain-specific |
| Security review skill for Cursor | Evaluate after core skills work |

---

## Cursor / AI (Post v1.0)

| Idea | Why It Waits |
|------|-------------|
| Subagent orchestration for full feature pipeline | Core skills first |
| Automated ADR generation from decisions | Manual ADR sufficient for v1.0 |
| Session memory auto-sync on every tool call | Manual closeout protocol first |
| Custom MCP server templates | Evaluate need from child projects |

---

## How to Promote an Item

1. A child project demonstrates the need.
2. Open a framework-improvement issue (Phase 0.4).
3. Product Owner approves for next framework version.
4. Remove from parking lot and add to ROADMAP.

---

**Last Updated:** 2026-07-09
