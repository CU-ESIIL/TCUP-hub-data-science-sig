# Git coordination

<!-- Template. Replace every [BRACKETED] placeholder. Delete the two-computer
sections if you work on one computer. -->

How [INSTRUCTOR], [AGENT A], and [AGENT B] share this repository. AGENTS.md
summarizes these rules and links here. If the two disagree, report the
conflict instead of choosing one. Change any rule through [INSTRUCTOR], and
record the change in a session note.

## Setup

- **GitHub:** `[OWNER]/[REPO NAME]`, default branch `main`. GitHub holds the
  shared committed history. Uncommitted work exists only on the computer that
  has it.
- **[COMPUTER A]** ([operating system]): [what it has, for example the CAD
  software; which agent works here].
- **[COMPUTER B]** ([operating system]): [what it has; which agent works
  here]. Ignored local folders do not travel through Git and may be missing
  from the other computer.

## Before editing

1. Confirm the branch, working-tree status, and latest commits with
   read-only Git.
2. Bring the clone up to date. If the tree is clean and `main` is behind
   `origin/main`, pull with `git pull --ff-only`. [INSTRUCTOR] runs the pull or
   authorizes an agent to. If there are unexplained local changes or the pull
   can't fast-forward, stop and report. Don't reset or force anything.
3. Follow the read order in [AGENTS.md](../AGENTS.md#start-with-the-assigned-task).
4. Check that what the last handoff promised is present. If it's missing,
   stop and report. Don't re-create it.
5. List the files you will touch. Leave any file with another editor alone.
6. Ask [INSTRUCTOR] to close any file you will rewrite. An open editor can save
   its older copy over an agent's write.

## Working across computers

- **Default: one computer at a time, on `main`.** [INSTRUCTOR] reviews and
  pushes from the computer that made the changes. The other computer pulls
  and checks before anyone edits there.
- **Parallel work:** only with [INSTRUCTOR]'s approval. Record each agent's
  task, file scope, and computer in a session note. Scopes must not overlap.
  Stop and ask if they do.
- **Roles:** for larger work, [INSTRUCTOR] names the editor and the reviewer
  first. The reviewer is never the agent that wrote the work.

## Shared files

These files have one editor at a time: `AGENTS.md`, `README.md`, `TASKS.md`,
`PARKING.md`, `WATERSHED.md`, `HANDOFF.md`, `docs/prompt-library.md`, this
file, and the session-note template. Anyone may read them. Without a named
owner, agents propose changes in their own notes instead.

## Session notes

- **One note per agent per day:**
  `docs/session-notes/YYYY-MM-DD_session-notes_[agent].md`. Each agent writes
  only its own note, with a new `## HH:MM topic` block for each set of
  changes.
- **While another agent may be active,** put intended changes to shared files
  under **Proposed tracking updates** in your own note.

## Git actions

- **Local commits:** agents may commit their own daily notes, and files
  [INSTRUCTOR] explicitly approves for a local commit. Record that approval in
  the note.
- **Review and push:** [INSTRUCTOR] reviews local commits and pushes. A local
  commit is not confirmation and does not authorize a push or publication.
- **Before a commit:** inspect status and diffs, stage only the approved
  paths, run `git diff --cached --check`, and use a conventional-commit
  message.
- **If a pull or push fails:** preserve both sides, inspect the divergence,
  and integrate only with [INSTRUCTOR]'s approval. Never reset, force-push, or
  discard work.
- **Renames and moves:** a move and every reference it needs are one approval
  unit.
- **Without a fetch,** describe `origin/main` as cached.
- **No shell or Git:** say so, give [INSTRUCTOR] the checks to run one block per
  action, and never claim a Git action happened.

## Cross-platform

- Use repository-relative paths, never one machine's home folder.
- Preserve filename case.
- Keep formatting-only changes, such as line endings, in commits of their own.
