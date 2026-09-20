# Rollback Rules

Rollback is a first-class requirement.

## Rollback Trigger

Rollback must be considered when:

- a modification fails
- verification fails
- Windows becomes unstable
- a major error appears
- performance regresses
- the user requests rollback

## Rollback Order

Reverse the order of applied changes.

Example:

Change 1
Change 2
Change 3

Rollback:

Change 3
Change 2
Change 1

## Verification

After every rollback:

1. Read current state.
2. Compare against recorded previous state.
3. Confirm restoration.
4. Log result.

## Rollback Report

Include:

- change
- original state
- rollback state
- result
- verification
- remaining issues

Never claim rollback success without verification.
