# Change Management

Every system modification is treated as a controlled change.

Required fields:

- ID
- timestamp
- category
- target
- previous state
- proposed state
- reason
- evidence
- risk
- backup
- rollback
- verification
- result

Changes must be applied sequentially where practical.

If a critical modification fails, stop and evaluate rollback before continuing.
