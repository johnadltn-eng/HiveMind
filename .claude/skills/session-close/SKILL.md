# Session Close Skill

Use this at the end of any working session to capture what matters before closing the chat.

## What to do

Go through the conversation and extract anything worth keeping. Use this filter:

**Save if:**
- A decision was made that affects future work
- Something new was learned about a project, person, or situation
- A preference or feedback was given about how to work together
- A status changed (booking confirmed, contract sent, role pending, etc.)
- An insight emerged that would take time to re-derive

**Skip if:**
- It's task output that already lives in a file (script, carousel, email draft)
- It's ephemeral context only useful in this session
- It's already captured in an existing memory file

## Memory types to update

- `project_*.md` — booking status, project updates, key decisions
- `feedback_*.md` — how John wants to work, what to avoid, what landed well
- `user_*.md` — anything new about John's situation, goals, or preferences
- `reference_*.md` — new tools, contacts, platforms, external resources

## Format

Always update `MEMORY.md` index after writing or updating a file.

## Prompt to run this skill

At end of session, say: "let's do a session close" or "/session-close"

Claude will scan the conversation, propose what's worth saving, confirm with John, then write the files.
