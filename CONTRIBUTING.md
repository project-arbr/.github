# Contributing to Project Arbr

Thanks for your interest in contributing! This guide applies to all repositories under the
[project-arbr](https://github.com/project-arbr) organization.

## Getting started

1. **Find an issue** — look for issues tagged `good first issue` or `help wanted` in any repo.
2. **Comment on the issue** before starting work to avoid duplicate effort.
3. **Fork** the repository and create a feature branch from `main`:
   ```
   git checkout -b feat/my-feature
   ```
4. **Make your changes** and test them locally (see the repo-specific `CONTRIBUTING.md` for setup).
5. **Commit** using [Conventional Commits](https://www.conventionalcommits.org/):
   ```
   feat: add Mistral provider support
   fix: correct token count for streaming responses
   docs: update quickstart
   ```
6. **Open a Pull Request** against `main`. Fill out the PR template.

## Commit format

| Prefix | When to use |
|--------|-------------|
| `feat:` | New user-facing feature |
| `fix:` | Bug fix |
| `docs:` | Documentation only |
| `refactor:` | Code change that is not a bug fix or feature |
| `chore:` | Build, CI, or dependency updates |
| `test:` | Adding or updating tests |

Breaking changes: add `!` after the type — `feat!: rename config keys`

## Pull request expectations

- One PR per logical change
- CI must pass before merge
- At least one maintainer approval required
- No secrets, tokens, or `.env` files committed
- Squash-merge to keep `main` history clean

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

Open a [discussion](https://github.com/orgs/project-arbr/discussions) or a `question` issue.
