<!-- owner: shikanime | zone: internal | purpose: how to add or edit a template -->

# Development

## Prerequisites

None beyond a text editor. The repo has no Nix shell or formatter.

## Local loop

1. Edit or add a `<Tool>.gitignore` file at the repo root.
2. Keep patterns tool-scoped — no project-specific paths.
3. Commit with a plain-text capitalized title (no conventional-commit
   prefix), matching the shikanime commit style used across repos.

## How to add a template

1. Create `<Tool>.gitignore` (PascalCase tool name, matching existing files).
2. Add only ignores that apply to that tool's generated/state files.
3. Open a pull request against `main`.
