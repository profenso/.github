# Contributing to Profenso

## How to contribute

1. **Create a branch** from `main` for your work
2. **Make your changes** — keep commits small and focused
3. **Open a pull request** against `main`
4. **Get a review** — at least one approval is required
5. **Wait for CI** — all checks must pass before merging
6. **Merge** — your branch is automatically deleted after merge

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/). Every commit message must follow this format:

```
type: short description

Optional longer body explaining the why.
```

Valid types: `feat`, `fix`, `chore`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `revert`

Examples:
- `feat: add user authentication`
- `fix: correct timeout on health check`
- `docs: update deployment instructions`

This is enforced by a pre-commit hook. If your commit is rejected, check the message format.

## Local setup

Every repository uses [pre-commit](https://pre-commit.com/) for local quality checks. After cloning any repo:

```bash
pre-commit install
pre-commit install --hook-type commit-msg
```

This runs formatting, linting, security scans, and commit message validation automatically before each commit.

## Code review

- Be constructive and specific
- Approve when you're satisfied — don't leave PRs hanging
- Mark conversations as resolved when addressed
- All review threads must be resolved before merge

## Questions?

Open an issue using the relevant template, or ask in the team Slack channel.
