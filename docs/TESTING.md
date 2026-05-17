# Testing and Validation

## Available commands

Fill these in when the tech stack is chosen.

```bash
# install dependencies
TBD

# start app
TBD

# run tests
TBD

# typecheck
TBD

# lint
TBD

# build
TBD
```

## Validation expectations

After code changes, run the smallest relevant set of checks:

1. Targeted tests for changed behavior
2. Typecheck, if available
3. Lint, if available
4. Build check
5. Manual smoke test for the affected user flow

## Manual smoke test

- [ ] App starts successfully
- [ ] Main user flow works end-to-end
- [ ] No obvious console/runtime errors
- [ ] Generated output, saved files, or side effects appear in the expected place
- [ ] Closing/stopping the app does not leave obvious stray processes

## If validation cannot run

Document:

- which command failed or was unavailable
- why it could not run
- what was checked instead
- what risk remains
