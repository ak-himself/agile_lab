# HealthTracker App — MVP Scope

**Jira story:** [HTA-15 — Define MVP Scope and Acceptance Criteria](https://akhimself.atlassian.net/browse/HTA-15)  
**Target release:** HealthTracker v1.0 (target: 11 December 2026)

## MVP goal

Deliver a coherent first release with clear requirements, usable core screens, protected health data, integrated APIs, tested critical workflows, and a release-readiness process.

## MoSCoW priorities

### Must have — included in v1.0

- Requirements and testable acceptance criteria.
- UI/UX for the primary HealthTracker workflows, including the health dashboard.
- Backend and frontend foundations plus database setup.
- Authentication and authorization for protected functionality.
- API integration and data validation.
- Functional, integration, regression, security/privacy, accessibility, and performance checks.
- Bug fixes, app-store submission preparation, operational monitoring/rollback validation, and release notes.

### Should have — include where capacity allows

- CI/CD and repeatable test-environment setup.
- Accessibility/usability review and release-readiness documentation.
- Operational monitoring and rollback validation.

### Could have — optional if capacity allows

- Additional navigation, empty-state, and error-state design refinements beyond the core required flows.

### Won't have in v1.0 — explicitly deferred

- Wearable-device synchronization. This requires separate agreement on supported devices, permissions/consent, synchronization failure handling, and estimation before a future release.

## Capacity and release trade-off

The Jira plan allocates 20 story points to each of four two-week sprints. To protect the target v1.0 date, the team prioritizes the core must-have workflow and defers wearable-device synchronization. Optional refinements may be reduced before core security, testing, accessibility, or release-readiness work is cut.

## Acceptance criteria for this scope

- Must-have scope and explicit exclusions are recorded.
- Each delivery story has testable acceptance criteria.
- Stories are assigned to an epic and sprint, estimated with story points, and prioritized using MoSCoW labels.
- The team reviews this scope before treating the MVP backlog as committed.

## Definition of Done

A story is Done only when its acceptance criteria are met, the relevant pull request is reviewed and merged when code changes are required, and QA acceptance is recorded. A merge alone does not prove product or QA acceptance.

## Change control

Any request to add work to v1.0 should identify what will be removed or deferred to keep the release date and sprint capacity credible.