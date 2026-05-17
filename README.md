# AI-Assisted Project Template

A reusable starter template for vibe-coded projects, especially local apps that run from a desktop/browser workflow.

This repo is intentionally light on application code and heavier on workflow, documentation, prompts, and guardrails. The goal is to help AI coding agents start each project with clear context, validation habits, and handoff routines.

## How to use this template

1. Create a new repo from this template or clone it into a new project folder.
2. Fill out `docs/PRODUCT.md` before coding.
3. Create or update `docs/IMPLEMENTATION_PLAN.md`.
4. Ask the coding agent to read `AGENTS.md` first.
5. Use the prompt playbooks in `prompts/` for planning, implementation, review, bug fixing, cleanup, and session handoff.

## Recommended first files to customize

- `docs/PRODUCT.md`
- `docs/IMPLEMENTATION_PLAN.md`
- `docs/ARCHITECTURE.md`
- `docs/TESTING.md`
- `docs/LOCAL_APP_GUIDE.md`
- `.env.example`

## Template philosophy

- Keep AI instructions short and repo-local.
- Prefer small, reviewable changes.
- Require validation after code changes.
- Track decisions, bugs, tech debt, and session handoff notes in the repo.
- Do not let one giant instruction file become the project brain.

## Suggested project types

This template is best for:

- local browser-launched apps
- desktop-like utilities
- small web apps
- AI-assisted prototypes that may become real products

For mobile projects, use the same docs and prompts, then add mobile-specific setup notes as needed.
