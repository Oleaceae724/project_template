# Local App Guide

Use this guide for desktop/browser-launched local apps.

## Expected behavior

- The app should be runnable with one clear command.
- The startup command should be documented.
- The app should open in the expected browser or local window when appropriate.
- Closing/stopping the app should not leave obvious stray background processes.

## Commands

Fill in when the stack is chosen.

```bash
# install
TBD

# start development app
TBD

# build
TBD

# run packaged/local version
TBD
```

## File output conventions

- Generated files should go in a documented folder.
- Temporary files should be ignored by Git.
- User-generated output should not be accidentally overwritten.

## Windows notes

- Avoid fragile `.bat` launchers when a package script can do the job.
- Do not hardcode user-specific paths.
- If a launcher is needed, document how to stop the app cleanly.

## Shutdown checklist

- [ ] Stop local dev server
- [ ] Stop background worker processes
- [ ] Close browser or local app window
- [ ] Confirm no emulator/server process was left running unexpectedly
