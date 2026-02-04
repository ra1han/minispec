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
4. Update the changes log at `changes/` as steps complete.
5. Report progress with completed steps, blockers, and next resumption point.
