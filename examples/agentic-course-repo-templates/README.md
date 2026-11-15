# [REPO NAME]

<!-- Template. Replace every [BRACKETED] placeholder, then delete this comment. -->

## Project overview

Instructor repository for [COURSE], [COURSE TITLE] ([TERM]). It holds
editable course materials, instructor references, and records of course
development.

## Start here

- **Find course materials.** Open the [syllabus](01_syllabus/),
  [lesson plans](02_lesson-plans/), [activities](03_activities/),
  [homework](04_homework/), or [readings](05_readings/).
- **Resume work.** Find approved work in [TASKS](TASKS.md). Use the
  [session-start prompt](docs/session-start_prompt.md) and the latest agent
  note to check the next action and Git state. [PARKING](PARKING.md) holds
  open questions and proposals. [WATERSHED](WATERSHED.md) records
  [INSTRUCTOR]'s decisions.
- **Make a change.** Follow [AGENTS.md](AGENTS.md#start-with-the-assigned-task)
  and [Git coordination](docs/git-coordination.md#before-editing).

## Repository map

<!-- Adjust the folders to your course. Numbered prefixes keep them in order. -->

| Path | Purpose |
| --- | --- |
| `01_syllabus/` | Syllabus and welcome materials |
| `02_lesson-plans/` | Lesson plans and class recaps |
| `03_activities/` | Activity sources and assets |
| `04_homework/` | Homework sources and rubrics |
| `05_readings/` | Readings and figures |
| `06_instructor/` | Run sheets and answer keys (instructor only) |
| `docs/` | Git coordination, prompts, and session notes |
| `AGENTS.md` | Rules for agents and contributors |
| `HANDOFF.md` | Handoff instructions and the current prompt |
| `TASKS.md`, `PARKING.md`, `WATERSHED.md` | Approved work, open questions, decisions |
| `10_outputs/` | Rendered outputs (ignored by Git) |
| `11_posted/` | Copies of what was posted to students (ignored; instructor only) |

Ignored folders may be missing from another computer. Check `.gitignore`
before relying on them.

## Naming conventions

[DESCRIBE YOUR CONVENTIONS, for example: start files with `[COURSE]_`, use
`modXX-Y` for modules, underscores between parts, hyphens inside them.]

## Documentation and session workflow

Use the [start prompt](docs/session-start_prompt.md) to resume and the
[closeout prompt](docs/session-closeout_prompt.md) to record what changed, the
Git state, and the next action. Session notes are in
[docs/session-notes/](docs/session-notes/). Reusable prompts are in the
[prompt library](docs/prompt-library.md).
