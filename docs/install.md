# Install and Use

## Option 1: Use the packaged skill

Use:
- `dist/pm-world-class.skill`

This is the easiest path for systems that support packaged skill ingestion.

## Option 2: Use the source skills directly

Point your agent workflow at:
- `skills/public/pm-world-class/`
- `skills/public/tpm-execution/`
- `skills/public/exec-communication/`
- `skills/public/launch-operations/`
- `skills/public/risk-and-dependencies/`
- `skills/public/operating-reviews/`

## Claude-compatible usage pattern

1. Load the relevant `SKILL.md`
2. Read the linked `references/` files only as needed
3. Ask the agent for a concrete artifact, not generic advice

Example prompts:
- "Turn this initiative into a program brief."
- "Write me a VP-ready weekly update from these notes."
- "Build a launch plan with owners, milestones, and risks."
- "Create a RAID review from this messy project context."

## Best practice

Ask for one artifact at a time.
These skills work best when the request is tied to a real deliverable.