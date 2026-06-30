---
name: goddard-synthesis
description: Weekly synthesis report for Goddard School. Trigger when John pastes a Fathom transcript link or raw transcript from his weekly call with Ohm, or says "run the Goddard synthesis." Outputs a plain-language report under 150 words for directors D, Roshanda, and Dinesh.
metadata:
  version: 1.0.0
---

# Goddard Weekly Synthesis

## Trigger
John pastes a transcript (Fathom link or raw text) from the weekly call with Ohm, or says "run the Goddard synthesis."

## Steps

1. Read the transcript
2. Read `projects/goddard/priorities.md` and `projects/goddard/decisions/log.md` for context
3. Output the synthesis in exactly this structure:

---

**What we did this week**
- [bullet 1]
- [bullet 2]
- [bullet 3]

**Decisions made**
- [decision]: [one-line reason]

**Results / metrics**
- [any views, engagement, leads, or quantifiable numbers mentioned — skip this section if none]

**Next week**
- [what gets done] — [who]

---

4. Save the output to `projects/goddard/synthesis/YYYY-MM-DD.md` using today's date

## Constraints
- Total output under 150 words
- Third-grade reading level — plain, friendly, direct
- No jargon, no marketing-speak
- This goes straight to the directors as-is — write it that way
