# Developer guide

<!-- Template. Replace every [BRACKETED] placeholder. -->

This guide describes how work moves through the [COURSE] instructor
repository, for [INSTRUCTOR] and anyone else who works on the materials.
[README](README.md) explains what the repository holds,
[AGENTS](AGENTS.md) sets the rules for AI agents, and
[Git coordination](docs/git-coordination.md) covers computers, branches, and
session notes. Where they disagree, they take precedence; report the conflict.

Labels used below:

- **Established:** already practiced or recorded as decided.
- **New direction:** approved but not yet carried out.
- **Unresolved:** open or proposed, with no decision yet.

## Starting work

1. Follow the read order in [AGENTS.md](AGENTS.md#start-with-the-assigned-task).
2. Check the clone before editing: branch, status, recent commits, and that
   the files a handoff promised are present. If something is missing, stop
   and report it.
3. Name the files you will touch before editing. If a file has another
   editor, leave it alone.
4. Close a file in your editor before an agent rewrites it. An open editor can
   save an older copy over the agent's changes.

## Four kinds of material

What a file *is* matters more than its extension.

| Kind | Where | Rule |
| --- | --- | --- |
| **Source:** editable materials | `01_` to `06_` folders | Edit here. Keep each source's assets beside it. |
| **Working:** capture and drafts | `scratch.md` (ignored), `_inbox/` | Not instructions. Move accepted items into tracking files or sources. |
| **Output:** rendered files | `10_outputs/` | Regenerate from source. An output may not match the current source. |
| **Posted:** what students actually received | `11_posted/` (ignored) | A record, so don't edit it. Editing a source doesn't update a posted copy. |

Lesson plans record what was planned; class recaps record what was delivered.
Keep them separate.

## Picking up a half-finished change

When [INSTRUCTOR] starts restructuring between agent sessions and stops partway:

1. **Commit the partial state with a clear marker,** for example
   `docs: prepare week 9 refactor [in progress]`.
2. **Leave intent in a scratch file.** Scratch is evidence of intent, not a
   decision.
3. **Ask one agent to reconstruct it read-only first:** an evidence map (file,
   state, role), [INSTRUCTOR]'s directions labeled Decided, Approved,
   Proposed, or Open, and an ordered plan. No sources are edited yet.
4. **Approve the plan and assign editors** before anyone implements it.

## Reviewing teaching materials before students see them

1. **Author check.** Each activity tells the student four things: the first
   file to open, the action to take, where the result goes, and a visible
   sign the step is done.
2. **Independent review.** A different agent reviews the whole set, read-only,
   for ambiguity, contradictions, dates, submission steps, fallbacks for
   absence or blocked access, links students can reach, and unneeded prose.
   Two agents agreeing does not verify classroom facts.
3. **Dummy-content rehearsal.** Follow one student path from start to finish
   with labeled dummy content. Record steps you couldn't test as untested.

## Not settled here

[LIST OPEN QUESTIONS THAT LIVE IN PARKING OR TASKS.]
