---
description: "Creates implementation plans based on research or user context"
agent: 'planner'
---

# Plan

## Inputs

* ${input:research}: (Optional) Research file path to base the plan on

## Instructions

1. Gather context from ${input:research} or `research/`.
2. Follow the planner agent's phases to create implementation plan and details files.
3. Write plan to `plans/{{YYYY-MM-DD}}-<task>-plan.instructions.md`.
4. Write details to `details/{{YYYY-MM-DD}}-<task>-details.md`.
5. Summarize planning outcomes and provide file paths.
