# Kilocode Rules

> Rules specific to Kilocode when working on this project.

---

## Kilocode-Specific Guidelines

1. **Use available tools.** Prefer built-in file tools (view, edit, create, grep, glob) over bash where possible.
2. **Minimal changes.** Make the smallest change that solves the problem — avoid refactoring unrelated code.
3. **Run tests.** After any code change, run existing tests to confirm nothing is broken.
4. **Read before writing.** Always view the file before editing it.
5. **Follow `aigent.md`.** All general rules in `aigent.md` apply here too.
6. **Static HTML only** — no npm, no build tools, no package.json changes.

---

## Tool Preferences

| Task | Preferred Tool |
|------|---------------|
| Find files | `glob` |
| Search file contents | `grep` |
| Read a file | `view` |
| Edit a file | `edit` |
| Create a new file | `create` |
| Run a command | `bash` (sync mode) |

---

## Workflow

1. Read the issue
2. Explore the codebase
3. Report a plan with **report_progress**
4. Make minimal changes
5. Run lint/tests
6. **report_progress** again with changes committed
