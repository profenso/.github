# .github

Organisation-wide default community health files for **Profenso**.

Files in this repo are automatically inherited by every repository in the organisation that doesn't define its own. GitHub resolves bottom-up — a repo's own files always take priority over these defaults.

## What's included

| File | Purpose |
|---|---|
| **Issue templates** | Bug report, feature request, security concern, access request, infrastructure request |
| **PR template** | Generic pull request template (stack-specific repos override this) |
| **SECURITY.md** | How to report vulnerabilities privately |
| **CONTRIBUTING.md** | How we work — branching, conventional commits, pre-commit, code review |
| **profile/README.md** | Organisation profile shown on the Profenso GitHub page |

## How it layers

| Layer | Source | Wins when... |
|---|---|---|
| Repo | `.github/` in the repo itself | Always wins |
| Scaffold | Added by `scaffold-iac` or `scaffold-py` bootstrap | Overrides org defaults |
| Org default | This repo (`profenso/.github`) | Fallback when repo has nothing |

## Changing these files

Changes here affect **every repo** that hasn't overridden them. Open a PR and get a review — treat these like org-wide policy.
