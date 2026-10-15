# HealthTracker App

A course project tracked in Jira under the **HealthTracker App** project (`HTA`). This repository is the source-control companion for the project’s sprint planning, requirements, implementation, QA, and release workflow.

## Project links

- Jira project: https://akhimself.atlassian.net/browse/HTA-1
- MVP scope and acceptance criteria: [`docs/MVP_SCOPE.md`](docs/MVP_SCOPE.md)
- Jira story for the scope document: https://akhimself.atlassian.net/browse/HTA-15

## Delivery plan

The Jira plan uses four two-week sprints with a target of 20 story points per sprint. The v1.0 MVP prioritizes core requirements, UI/UX, backend and frontend foundations, API integration, testing, security, accessibility, and release readiness. Wearable-device synchronization is explicitly deferred beyond v1.0 to protect the agreed release scope.

## Development workflow

1. Create a branch with the Jira key, e.g. `HTA-15-define-mvp-scope`.
2. Include the Jira key in commit messages and pull-request titles.
3. Review changes through pull requests before merging.
4. A story is not considered Done solely because a PR is merged; acceptance criteria and QA acceptance must also be satisfied.

## Current status

This repository was initially empty. The first commit establishes project documentation; application implementation and test evidence should be added as the corresponding Jira stories are completed.