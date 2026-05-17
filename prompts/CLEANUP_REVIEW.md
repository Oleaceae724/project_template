# Cleanup Review Prompt

Use this after MVP work or several AI coding sessions.

```md
Please review the project for cleanup needs before adding more features.

Do not edit files yet.

Look for:
1. Stale docs.
2. Duplicated logic.
3. Oversized files.
4. Confusing names or structure.
5. Dead code or unused files.
6. Missing tests around critical behavior.
7. Agent-created drift from the intended architecture.
8. Security, data-loss, or local-file risks.

Output a prioritized cleanup plan with:
- issue
- why it matters
- suggested fix
- risk level
- validation needed
```
