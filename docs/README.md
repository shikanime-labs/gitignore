<!-- owner: Automata | zone: technical | purpose: Canonical technical doc index for shikanime-labs/gitignore -->
# gitignore — technical index

A collection of ready-to-use `.gitignore` templates for languages, frameworks, and tools. Each file is a standard template meant to be dropped into a repository root or appended to a global ignore.

## Canonical sources

- [Repository README](https://github.com/shikanime-labs/gitignore#readme)
- [Technical wiki](https://github.com/shikanime-labs/gitignore/wiki)

## Templates

| Template | Scope |
| --- | --- |
| `Astro.gitignore` | Astro projects |
| `Devenv.gitignore` | devenv / Nix dev shells |
| `Latex.gitignore` | LaTeX builds |
| `MLflow.gitignore` | MLflow runs and artifacts |
| `Wrangler.gitignore` | Cloudflare Workers |

## Usage

Copy a template into your repository root (or append it to your global ignore) and commit. Validate patterns with `git check-ignore` before submitting changes. Pull requests follow the org default template in [shikanime-labs/.github](https://github.com/shikanime-labs/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md); the repository carries no local template.

## Documentation rule

In-repo `docs/` is canonical for technical detail. The [wiki](https://github.com/shikanime-labs/gitignore/wiki) is a rendered human index that links here.
