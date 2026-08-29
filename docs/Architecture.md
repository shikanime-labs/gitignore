<!-- owner: shikanime | zone: internal | purpose: gitignore repo shape and conventions -->

# Architecture

`gitignore` is a small collection of reusable `.gitignore` templates. There
is no build, no flake, and no runtime — the repository *is* the content.

## Layout

Each template ships as a top-level file named `<Tool>.gitignore`:

- `Astro.gitignore` — Astro project ignores
- `Devenv.gitignore` — devenv scratch/state ignores
- `Latex.gitignore` — LaTeX build artifact ignores
- `MLflow.gitignore` — MLflow tracking ignores
- `Wrangler.gitignore` — Cloudflare Wrangler ignores
- `LICENSE` — repository license
- `README.md` — one-line project description

## Design intent

Keep templates framework-specific and free of project-specific paths so they
drop into any repo that adopts the tool. One concern per file; no nesting.
