---
description: "Executes implementation plans with progress tracking"
agent: 'implementor'
---

# Implement

## Inputs

* ${input:plan}: (Optional) Implementation plan file path

## Instructions

1. Locate plan from ${input:plan}, open file, or most recent in `plans/`.
2. Resume from the first uncompleted step (check `[x]` markers).
3. Follow the implementor agent's phases to execute the plan.
4. Use the plan's `{{NNN}}` prefix for the changes log: `changes/{{NNN}}-<task>-changes.md`.
5. Update the changes log as steps complete.
6. Report progress with completed steps, blockers, and next resumption point.
