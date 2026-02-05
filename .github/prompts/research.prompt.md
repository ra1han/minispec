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
3. Count existing files in `research/` and add 1 to determine the next sequence number.
4. Follow the researcher agent's phases to investigate and document findings.
5. Produce a research document at `research/{{NNN}}-<topic>-research.md` (three-digit zero-padded number).
6. Summarize key discoveries and provide the research document path.