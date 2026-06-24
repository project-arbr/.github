# Governance

## Roles

### Project Lead

The Project Lead has final authority over the direction of Project Arbr and all repositories
under the organization. Responsibilities include:

- Setting product roadmap and priorities
- Merging contributions and cutting releases
- Maintaining the health of the community

Current Project Lead: **[@shubham-gyde](https://github.com/shubham-gyde)**

### Maintainers

Maintainers are trusted contributors with write access to one or more repositories. They:

- Review and merge pull requests
- Triage issues
- Participate in roadmap discussions

Maintainers are listed in each repo's `CODEOWNERS` file. New maintainers are nominated by the
Project Lead based on sustained, high-quality contributions.

### Contributors

Anyone who has had a pull request merged is a Contributor. Contributors can:

- Open issues and PRs
- Participate in design discussions
- Be nominated for Maintainer status

## Decision Making

- **Day-to-day** decisions (bug fixes, small features) are made by any Maintainer via PR review.
- **Significant changes** (new products, breaking changes, license changes) are discussed in a
  GitHub Discussion and decided by the Project Lead with Maintainer input.
- **Disputes** are resolved by the Project Lead.

## Release Process

1. Changes accumulate on `main` via merged PRs.
2. When ready for a release, the Project Lead creates a tag (`vX.Y.Z`) following
   [Semantic Versioning](https://semver.org/).
3. The CI/CD pipeline publishes Docker images and SDK packages automatically.

## Changes to Governance

This document may be updated by the Project Lead. Significant changes will be announced via
a GitHub Discussion.
