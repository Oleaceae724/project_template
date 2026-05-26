# Fix Bug Prompt

Use this when fixing a bug.

```md
Bug to fix:
[describe bug]

Known reproduction steps:
1. [step]
2. [step]
3. [step]

Expected behavior:
[expected]

Actual behavior:
[actual]

Please:
1. Reproduce or reason through the bug.
2. Identify likely root cause.
3. Propose the smallest safe fix.
4. Implement the fix.
5. Add or update tests if reasonable.
6. Run relevant validation.
7. Update `docs/BUGS.md` and `docs/SESSION_HANDOFF.md`.

Do not do unrelated cleanup unless it is necessary for the fix.
```
