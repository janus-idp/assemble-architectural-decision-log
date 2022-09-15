# Definition of Done

* Status: proposed

## Context and Problem Statement

In order to foster transparency and productive colaboration, we must have a shared understanding of what it means for work to be complete.

## Considered Options

* Global 'Definition of Done'
* Repository-specific 'Definitions of Done'

## Decision Outcome

We decided to largely define acceptance for code contributions at the repository level.

We have identified 2 ways to enforce quality for contributions to individual repsitories:

1. A GitHub pull request template as demonstrated [here](https://github.com/halkyonio/assemble-local-dev/blob/main/.github/PULL_REQUEST_TEMPLATE.md)
2. A GitHub Pull Request Action defined that runs tests, scans, or other quality checks

In general, we have agreed that when a feature is "done" it means:

* The feature has been tested (automated tests are ideal)
* Code has been merged to the main branch of its repository and is passing the quality checks defined in that repository
* Other team members understand the feature and how to use it because the code is well documented or adequately self-documenting

In the case of an experimental feature or a "SPIKE", we've agreed that "done" means the team has discussed (ideally using an ADR) and there is a consensus to move forward or stop working

### Positive Consequences

* some loose global acceptance criteria defined
* flexibility to further define acceptance that makes sense in the context of the codebase (repository)

### Negative Consequences <!-- optional -->

* some planning and configuration overhead when creating a new repository
