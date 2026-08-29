<!-- owner: shikanime | zone: internal | purpose: template inventory -->

# Reference

## Template inventory

| File                | Scope                          | Size  |
| ------------------- | ------------------------------ | ----- |
| `Astro.gitignore`   | Astro projects                 | 7 B   |
| `Devenv.gitignore`  | devenv state/scratch           | 30 B  |
| `Latex.gitignore`   | LaTeX build artifacts          | 2.8 K |
| `MLflow.gitignore`  | MLflow tracking                | 20 B  |
| `Wrangler.gitignore`| Cloudflare Wrangler            | 10 B  |

## Naming convention

- One file per tool: `<Tool>.gitignore` (PascalCase).
- Tool-scoped patterns only; no project-specific paths.

## Commands

| Command            | Purpose                        |
| ------------------ | ------------------------------ |
| `git commit`       | plain-text capitalized title   |
| `gh pr create`     | open a PR against `main`       |
