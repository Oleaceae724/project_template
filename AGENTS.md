# AGENTS.md

This repository is designed for AI-assisted development. Treat the docs in this repo as the source of truth for project context, decisions, implementation plans, testing expectations, and session handoff.

## Read first

Before planning or coding, read:

1. `docs/PRODUCT.md`
2. `docs/IMPLEMENTATION_PLAN.md`
3. `docs/ARCHITECTURE.md`
4. `docs/TESTING.md`
5. `docs/SESSION_HANDOFF.md`

If a file is still a template, say so and make a reasonable minimal assumption rather than inventing project details.

## Working rules

- Keep changes small, focused, and reviewable.
- Do not make broad unrelated refactors while implementing a feature.
- Do not add dependencies without explaining why they are needed.
- Do not delete working code without a rollback plan.
- Prefer simple, boring implementation choices over clever ones.
- Preserve existing behavior unless the task explicitly asks to change it.
- Update docs when behavior, commands, architecture, or workflows change.
- Never commit secrets, API keys, local caches, generated build output, or machine-specific paths.

## Before coding

- Restate the goal in concrete terms.
- Identify likely files or areas affected.
- List key risks and assumptions.
- Ask only blocking questions. If the missing detail is not blocking, make a conservative assumption and document it.

## During work

- Provide short progress updates at phase changes, blockers, or plan changes.
- Do not narrate every file read or routine command.
- Keep the implementation aligned with the current plan.

## Required validation

After code changes, run the smallest relevant set of checks available:

1. Targeted tests for changed behavior
2. Typecheck, if available
3. Lint, if available
4. Build check
5. Manual smoke test for the affected user flow

Do not claim validation passed unless the command or check was actually run. If a check cannot be run, explain why and recommend the next best validation.

## After coding

Update these files when relevant:

- `docs/SESSION_HANDOFF.md`
- `docs/BUGS.md`
- `docs/TECH_DEBT.md`
- `docs/DECISIONS.md`
- `docs/TESTING.md`
- `docs/ARCHITECTURE.md`

Final responses should include:

- what changed
- files touched
- validation run and results
- risks, limitations, or follow-ups
