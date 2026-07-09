# Architecture Review Gate

Complete this checklist **before any code is written** for a new feature or module.

If any answer is unclear, stop and resolve with the Product Owner and Architect first.

---

## Feature

**Name:** [feature name]  
**Date:** [YYYY-MM-DD]  
**Author:** [who filled this out]

---

## Ten Questions

### 1. What problem are we solving?

[Answer]

### 2. Who is the user?

[Answer]

### 3. What is the smallest version that creates value?

[Answer]

### 4. What data goes in?

[Answer — inputs, formats, sources]

### 5. What output comes out?

[Answer — outputs, formats, consumers]

### 6. Where does the logic belong?

[Answer — which module, layer, or pipeline stage]

### 7. What should NOT be built yet?

[Answer — explicit deferrals]

### 8. What could break?

[Answer — risks, edge cases, dependencies]

### 9. How will we test it?

[Answer — smoke test, unit test, manual validation]

### 10. What does success look like?

[Answer — measurable outcome]

---

## Gate Result

- [ ] All ten questions answered clearly
- [ ] Product Owner aware of scope
- [ ] Architect reviewed placement in architecture
- [ ] Ready for Cursor plan (no file edits until plan approved)

**Approved by:** [Owner / Architect]  
**Date:** [YYYY-MM-DD]

---

## After Approval

1. Save or reference this checklist in the feature issue or PR.
2. Create an ADR if the decision is architectural (see [DECISIONS/README.md](../DECISIONS/README.md)).
3. Proceed to Cursor plan prompt — not implementation.
