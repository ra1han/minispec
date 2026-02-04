---
description: "Initiates research for implementation planning based on user requirements"
agent: 'researcher'
---

# Research

## Inputs

* ${input:topic}: Primary research topic or focus area

## Instructions

1. Define the research scope from ${input:topic} and conversation context.
2. Check `research/` for existing research to extend.
3. Follow the researcher agent's phases to investigate and document findings.
4. Produce a research document at `research/{{YYYY-MM-DD}}-<topic>-research.md`.
5. Summarize key discoveries and provide the research document path.