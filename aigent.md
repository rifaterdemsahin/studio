# Agent Rules

> Rules that apply to all AI agents working on this project.

---

## General Rules

1. **Commit and push after every meaningful activity.** No work should remain uncommitted for more than one logical step.
2. **Follow the folder structure.** Each folder has a defined purpose — place files in the correct location.
3. **Keep files small and focused.** One topic per file; break large content into multiple files.
4. **Use Markdown for documentation.** All documentation files must be valid `.md` files.
5. **Static HTML only.** No build tools, no npm, no bundlers — the site must work as plain files on GitHub Pages.
6. **No secrets in code.** API keys, passwords, and tokens must never be committed.
7. **Update the README.md** at root level whenever a new section or significant file is added.
8. **Link everything.** Every HTML page must include the shared navigation menu (`index.html` pattern).

---

## Folder Naming Convention

```
1_Real_Unknown   → Problem definition
2_Environment    → Context and constraints
3_Simulation     → Mockups and examples
4_Formula        → Steps and guides
5_Symbols        → Source code
6_Semblance      → Errors and fixes
7_Testing_Known  → Tests and validation
```

---

## Commit Message Format

```
<folder>: <short description>

Examples:
4_Formula: add OBS configuration steps
6_Semblance: log audio hum issue and fix
root: update navigation menu with new links
```
