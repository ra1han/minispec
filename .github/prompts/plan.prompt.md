---
description: "Creates implementation plans based on research or user context"
agent: 'planner'
---

# Plan

## Inputs

* ${input:research}: (Optional) Research file path to base the plan on

## Instructions

1. Gather context from ${input:research} or `research/`.
2. Count existing files in `plans/` and add 1 to determine the next sequence number.
3. Follow the planner agent's phases to create implementation plan and details files.
4. Write plan to `plans/{{NNN}}-<task>-plan.instructions.md` (three-digit zero-padded number).
5. Write details to `details/{{NNN}}-<task>-details.md` (same number as the plan).
6. Summarize planning outcomes and provide file paths.
