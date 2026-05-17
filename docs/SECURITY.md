# Security

## Secrets

- Never commit real API keys, tokens, passwords, certificates, or credentials.
- Use `.env` for local secrets and keep `.env.example` as the safe template.
- If a secret is committed by accident, rotate it immediately.

## Data handling

Document what data the app reads, writes, stores, uploads, or generates.

## Local files

- Avoid writing outside documented project/output folders.
- Ask before deleting user data.
- Back up or preserve user files before destructive operations.

## Dependencies

- Add new packages only when justified.
- Prefer widely used, maintained packages.
- Document why a new dependency was added.

## AI agent safety rules

- Do not expose secrets in logs or summaries.
- Do not invent security claims.
- Do not bypass validation to make a task appear complete.
