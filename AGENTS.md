# AGENTS.md

This repository is a class homework submission collection for Geekbang's
"Algorithm Training Camp" cohort. Most work happens inside per-week,
per-student folders rather than in a single application codebase.

## Repository purpose

- Store student algorithm homework submissions by week and student ID.
- Keep optional weekly notes in `NOTE.md` files beside homework solutions.
- Accept many small, independent code files rather than one buildable project.

## Directory layout

- Root folders are organized by week, for example:
  - `Week 01/`
  - `Week 02/`
  - `Week 03/`
  - `Week 05/`
  - `Week 06/`
  - `Week 07/`
  - `Week 预习周/`
- Inside each week folder, student work lives in `id_XXX/` directories.
- A typical student directory contains:
  - one or more solution files
  - an optional `NOTE.md`

Example:

- `Week 01/id_118/LeetCode_26_118.py`
- `Week 01/id_118/NOTE.md`

## Scope rules for edits

- Prefer the smallest possible change.
- Treat each `Week XX/id_XXX/` directory as owned by that student.
- Do not modify files across many student directories unless the task
  explicitly requires a repo-wide documentation or maintenance change.
- For submission fixes, only edit the targeted student's folder plus any
  clearly related root documentation.
- Avoid renaming week folders or student folders.

## Naming conventions

- Homework solution filenames should follow the repository convention:
  `LeetCode_<problem_number>_<student_id>.<ext>`
- `NOTE.md` is the expected filename for optional study notes.
- Preserve existing casing and spacing in directory names.

## Working in this repository

- There is no single package manager or standard build command at the root.
- Do not assume a repo-wide test suite exists.
- Validate only the files you changed, using language-appropriate commands when
  practical.
- Many paths contain spaces, such as `Week 01/...`; always quote these paths in
  shell commands.
- Prefer focused searches and file reads over broad recursive commands.

## Safe change strategy

1. Read `README.md` first for repository submission rules.
2. Locate the exact week and student directory involved in the task.
3. Edit only the minimum set of files needed.
4. Keep naming consistent with the existing submission format.
5. If adding documentation, keep it generic and compatible with a
   multi-language homework repository.

## Things to avoid

- Do not reorganize the repository structure.
- Do not introduce root-level tooling unless explicitly requested.
- Do not add dependencies for the whole repository to support a single student
  submission.
- Do not normalize or translate existing folder names unless asked.

## Verification guidance

- For documentation-only changes, review formatting and path references.
- For code changes in a student folder, run only narrow checks relevant to that
  file's language, if tooling is available.
- Mention clearly when no automated tests exist for the affected area.
