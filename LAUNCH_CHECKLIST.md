# Overnight launch checklist

Before launch:
- Confirm the bowling winner and selected challenge.
- Read MASTER_PROMPT.md and the selected PROMPT_AND_ACCEPTANCE.md.
- Create/use a clean run branch or workspace from the pre-challenge snapshot.
- Confirm git push access to origin.
- Confirm sufficient disk space and no high-load unrelated batch jobs.

Launch:
- Start exactly one orchestrator run with the selected challenge context.
- Do not manually patch code after launch.
- Allow public web/package access and user-level dependency installation only.
- No sudo/root, patient data, confidential hospital data, or unrelated production changes.

Evidence to preserve:
- Git commit history.
- Agent/orchestrator logs.
- Automated test output.
- Sources used.
- Final README and short final report.

Morning acceptance:
- App starts from documented instructions.
- Main flow works end-to-end.
- Challenge-specific acceptance criteria have been evaluated.
- Known limitations are documented.
