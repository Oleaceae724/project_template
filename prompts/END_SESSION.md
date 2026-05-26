# End Session Prompt

Use this at the end of an AI coding session.

```md
Please end the session cleanly.

Do the following:
1. Summarize what changed.
2. List files touched.
3. Run or summarize relevant validation.
4. Update `docs/SESSION_HANDOFF.md`.
5. Update `docs/BUGS.md`, `docs/TECH_DEBT.md`, or `docs/DECISIONS.md` if relevant.
6. Note remaining risks or unfinished work.
7. Recommend the next safest step.

Also check for local cleanup needs:
- stopped dev servers
- stopped background tasks
- closed emulators if relevant
- no secrets or generated junk staged for commit
```
