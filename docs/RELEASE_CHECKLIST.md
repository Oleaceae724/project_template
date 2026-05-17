# Release Checklist

Use this before calling a version finished or ready to share.

## Code health

- [ ] Feature scope matches `docs/PRODUCT.md`
- [ ] Known bugs are documented
- [ ] Tech debt is documented
- [ ] Unused files or experiments are removed

## Validation

- [ ] Tests pass, if available
- [ ] Typecheck passes, if available
- [ ] Lint passes, if available
- [ ] Build succeeds
- [ ] Manual QA checklist completed

## Documentation

- [ ] README setup instructions are accurate
- [ ] `.env.example` is current
- [ ] Architecture notes are current
- [ ] Session handoff is current

## Local app checks

- [ ] App starts with documented command
- [ ] App shuts down cleanly
- [ ] Generated output goes to expected folder
- [ ] No secrets or local-only files are committed
