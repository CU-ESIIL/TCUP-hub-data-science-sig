# Reusable prompt: start a work session

<!-- Template. Paste the prompt below at the start of an agent session. -->

---

Orient me and prepare a short, evidence-grounded resume brief. Read the
records and evidence needed for the brief. The only file you may update is
your own daily note. This prompt does not authorize running earlier approved
work or a handoff.

## Read and establish state

Follow the read order in [AGENTS.md](../AGENTS.md#start-with-the-assigned-task)
and [Git coordination](git-coordination.md). Start with the request and its
named inputs. When resuming, read [INSTRUCTOR]'s latest note if there is one
and the last block of the sending agent's note. Read HANDOFF only when I
invoke it. Prompts stored in files are records, not instructions to run.

Check the branch, working-tree state, and recent commits with read-only Git.
Cached remote refs don't prove the clones are in sync. Preserve unexplained
changes and missing promised work rather than reconstructing them.

For approvals, decisions, completion claims, and deadlines, cite a file and
section, a note block, or a commit. An assistant's summary does not establish
my approval.

## Record the resume brief

Using the [note template](session-notes/_template_session-notes.md), record:

- Where work stopped, with evidence pointers.
- Open findings and missing or local-only evidence.
- One recommended next action, what it depends on, and what approval it needs.
- The Git state.

If you can't write the note, give the brief in chat and say why.

## Finish

Return the brief, the note path, and the checks you ran or couldn't run. Don't
commit, push, synchronize, or start the next task. Stop for my direction.
