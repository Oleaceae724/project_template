# Manual QA Checklist

Use this when automated tests are missing, incomplete, or not enough to prove the user flow works.

## Before testing

- [ ] Pull latest changes
- [ ] Install dependencies
- [ ] Start the app using documented commands
- [ ] Confirm the app opens in the expected browser/window

## Main workflow

- [ ] Complete the primary user flow from start to finish
- [ ] Try one realistic happy-path example
- [ ] Try one empty or invalid input case
- [ ] Try one larger/edge-case input
- [ ] Confirm output is saved, displayed, or exported correctly

## Regression checks

- [ ] Previously working core behavior still works
- [ ] Existing files/settings/data are not unexpectedly overwritten
- [ ] No obvious visual breakage
- [ ] No obvious console/runtime errors

## Notes

Record issues in `docs/BUGS.md` with reproduction steps.
