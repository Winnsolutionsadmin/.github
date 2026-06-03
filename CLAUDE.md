# org-dotgithub

## COLD-START RITUAL (read on the first message of every session)

1. Read this entire file.
2. Read `memory-bank/activeContext.md` for the live state — what the last session did, where artifacts live, what open questions are blocking, what's next.
3. If working on a deliverable, also read `memory-bank/lessons.md` for any folder-specific dos/don'ts.
4. If `memory-bank/activeContext.md` and this file conflict, trust `activeContext.md` for state and trust this file for rules / standing instructions.
5. At session end, run `/wrap-session` to refresh `memory-bank/activeContext.md` and audit in-flow captures.

## What this is

This is the special **`.github` repository** for the `Winnsolutionsadmin` GitHub organization (remote: `github.com/Winnsolutionsadmin/.github`). GitHub renders files placed here org-wide, so this repo holds the org's community-health / governance config rather than any application code.

Contents:
- `profile/README.md` — the public **org landing-page** shown on the GitHub org profile. Describes Winn Solutions / Winn Ventures, names the [`knowledge`](https://github.com/Winnsolutionsadmin/knowledge) repo as the source of truth (`INDEX.md`), and documents the repo **topic taxonomy** (`client`, `growing-mindfully`, `belief-knowledge`, `skill`, `infra`, `internal`, `productized-ai`).
- `CONTRIBUTING.md` — org-wide contribution conventions (branch-based collaboration, kebab-case names, one-line description + topics per repo, never commit secrets/PII, create repos via `/newrepo`).
- `SECURITY.md` — org-wide security policy (private vuln reporting to jarred@winn.solutions, no secrets in history, no client PII / child-enrollment data in git).

**Type:** infra (org-level GitHub governance config). **Status:** active / live org config, low-churn by nature — single commit (`e4884e8`), clean tree.

## Memory

Project state lives in `memory-bank/`:
- `activeContext.md` — where the last session left off (read first)
- `projectbrief.md` — what this repo is and why
- `lessons.md` — accumulated dos/don'ts specific to this repo
- `progress.md` — what works / what's broken / what's queued
- `decisions/` — ADRs
- `MEMORY.md` — index of the above
