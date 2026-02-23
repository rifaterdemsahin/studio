# Claude Rules

> Rules specific to Claude (Anthropic) when working on this project.

---

## Claude-Specific Guidelines

1. **Use long-context capability wisely.** When reviewing multiple files, read them all before making changes.
2. **Prefer editing over rewriting.** Make surgical changes rather than replacing entire files.
3. **Explain reasoning.** Add a brief comment or note explaining *why* a change was made, not just *what* changed.
4. **Respect the folder structure** defined in `aigent.md`. Do not create ad-hoc folders.
5. **Format Markdown properly.** Use headers, tables, and code blocks consistently.
6. **Do not hallucinate file paths.** Check that files exist before referencing them.
7. **Commit message format** — follow the format in `aigent.md`.

---

## Tone & Style

- Clear, concise, professional
- Use British English spellings (e.g. *colour*, *optimise*)
- Avoid filler phrases ("Certainly!", "Of course!")

---

## Limitations Awareness

- Claude cannot browse the internet directly — suggest URLs, don't fetch
- Claude cannot run code — describe commands for the user to run
- Claude cannot push to GitHub — instruct user to run `git push` or use report_progress
