# Contributing

Small team (~4). Conventions inherited org-wide:

- **Branch-based collaboration** (not forks); open a PR for review on shared repos.
- **kebab-case** repo + branch names.
- Every repo gets a one-line **description** + relevant **topics** (the org page is organized by topic).
- **Never commit secrets** (`.env`, keys, tokens) or PII (client / child-enrollment data). Use env vars; route media / large files to Backblaze B2, not git or LFS.
- Create new repos via `/newrepo` — it scaffolds `CLAUDE.md` / `AGENTS.md`, tags + describes the repo, and registers it in the knowledge `INDEX`.
