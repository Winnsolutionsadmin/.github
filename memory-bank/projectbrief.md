# org-dotgithub — project brief

## Purpose / what this is

The special **`.github` repository** for the `Winnsolutionsadmin` GitHub organization (remote: `github.com/Winnsolutionsadmin/.github`). GitHub treats files in this repo as org-wide defaults, so it serves as the org's governance and community-health surface — the public org profile plus shared contribution and security policy. It contains no application code.

## What it holds

- **`profile/README.md`** — the public landing page on the org's GitHub profile. Describes Winn Solutions / Winn Ventures, designates the [`knowledge`](https://github.com/Winnsolutionsadmin/knowledge) repo (`INDEX.md`) as the source of truth, and documents the org's repo **topic taxonomy**: `client`, `growing-mindfully`, `belief-knowledge`, `skill`, `infra`, `internal`, `productized-ai`.
- **`CONTRIBUTING.md`** — org-wide conventions: branch-based collaboration (no forks), kebab-case repo/branch names, one-line description + topics per repo, never commit secrets or PII, create repos via `/newrepo`.
- **`SECURITY.md`** — org-wide security policy: private vulnerability reporting to jarred@winn.solutions, no secrets in git history, no client PII / child-enrollment data in repos.

## Type

infra (org-level GitHub governance config)

## Status

active — live org config, low-churn by nature. History is a single commit (`e4884e8`); clean working tree.

## Key tech

- Plain Markdown, no build step, no dependencies.
- GitHub's special `.github` repo mechanism (org-wide rendering of `profile/README.md`, `CONTRIBUTING.md`, `SECURITY.md`).

## Key constraints

- Files here apply ORG-WIDE — edits affect the public org profile and every repo's default contributing/security surface. Treat changes as governance changes.
- Same hard rules as the rest of the org: no secrets, no client/child PII in git history.
