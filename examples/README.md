# Example prompts and agent files

Templates for running a course repository with two AI coding agents (for
example Claude Code and Codex) and one instructor who approves the work. To
use them, copy the folder into your own repository, replace every
`[BRACKETED]` placeholder, and delete what you don't need. Links inside the
files point to other files in the set, so they work once the files sit
together in your repository.

Generalized Nov 14, 2026 from Jason Tinant's ENGR133 and ENGR101 instructor
repositories at Oglala Lakota College. The prompt library's format follows
Brian Yandell's Prompt Examples.

## agentic-course-repo-templates

- [AGENTS.md](agentic-course-repo-templates/AGENTS.md): rules every agent
  follows: read order, how to verify, who decides, hard boundaries.
- [CLAUDE.md](agentic-course-repo-templates/CLAUDE.md): points Claude Code to
  AGENTS.md, so both agents share one rule set.
- [README.md](agentic-course-repo-templates/README.md): repository map,
  naming conventions, and where to start.
- [DEVELOPER.md](agentic-course-repo-templates/DEVELOPER.md): how work moves
  through the repository, including a three-step review before students see
  materials.
- [HANDOFF.md](agentic-course-repo-templates/HANDOFF.md): how to pass work
  between agents or computers, with a blank current prompt.
- [TASKS.md](agentic-course-repo-templates/TASKS.md),
  [PARKING.md](agentic-course-repo-templates/PARKING.md), and
  [WATERSHED.md](agentic-course-repo-templates/WATERSHED.md): approved work,
  open questions, and settled decisions.
- [docs/git-coordination.md](agentic-course-repo-templates/docs/git-coordination.md):
  how agents and computers share one repository without overwriting each
  other.
- [docs/session-start_prompt.md](agentic-course-repo-templates/docs/session-start_prompt.md)
  and [docs/session-closeout_prompt.md](agentic-course-repo-templates/docs/session-closeout_prompt.md):
  prompts to start and close a work session.
- [docs/session-notes/_template_session-notes.md](agentic-course-repo-templates/docs/session-notes/_template_session-notes.md):
  one agent's daily note.
- [docs/prompt-library.md](agentic-course-repo-templates/docs/prompt-library.md):
  thirteen reusable prompts, each in its improved form.
