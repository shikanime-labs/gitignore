<!-- owner: shikanime | zone: internal | purpose: known failure modes and fixes -->

# Troubleshooting

## Template not picked up by a consumer

The file must be named exactly `<Tool>.gitignore` at the repo root. A
misnamed or nested file will not be found by tools that glob this repo.

## Patterns too broad

A template that ignores a generic path (e.g. `build/`) can swallow wanted
files in a consuming repo. Keep patterns tool-specific and prefer
subdirectory-scoped globs where the tool writes under a known folder.

## Drift between forks

This repo is the source of truth; consumers should track it, not copy
templates inline. Copying inline freezes the ignore list and hides later
fixes.
