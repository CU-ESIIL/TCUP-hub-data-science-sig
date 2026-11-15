# Reusable prompt: close out a work session

<!-- Template. Paste the prompt below at the end of an agent session. -->

---

Close out the work done in this session so I can resume safely. Update only
records that need a real change.

## Establish scope and state

Follow the read order in [AGENTS.md](../AGENTS.md#start-with-the-assigned-task)
and [Git coordination](git-coordination.md). Read this session's note blocks.
Check the branch, working-tree state, and commits with read-only Git. Tell
apart local, committed, and pushed work.

Before writing, name the files you will change and who owns each. This prompt
assigns your own daily note. Edit shared files (TASKS, PARKING, WATERSHED,
README, HANDOFF) only if I've named you their owner; otherwise propose the
changes in your note.

## Record

In your own note, using the [template](session-notes/_template_session-notes.md):

- What changed and why, with links to evidence.
- Checks actually run, results, and what wasn't tested.
- Unresolved findings and deadlines, with time zones.
- The Git state and one next action, with what it needs.

Use the status ladder. Mark finished agent work Done (unverified); only I mark
it Confirmed.

## Finish

Check changed links, dates, and the diff. Return the updated records, open
decisions, the next action, and a suggested conventional commit message.
Leave files uncommitted. Don't push or start follow-up work.
