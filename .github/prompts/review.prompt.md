---
description: "Reviews implementation work for accuracy and compliance"
agent: 'reviewer'
---

# Review

## Inputs

* ${input:scope}: (Optional) Time scope: "today", "this week", or "since last review"

## Instructions

1. Locate artifacts from ${input:scope} or discover from ``.
2. Correlate related research, plan, and changes files by their `{{NNN}}` prefix.
3. Follow the reviewer agent's phases to validate implementation.
4. Write review log to `reviews/{{NNN}}-<task>-review.md` (use the same number as the related artifacts).
5. Report findings with severity, missing work, and recommended next steps.
