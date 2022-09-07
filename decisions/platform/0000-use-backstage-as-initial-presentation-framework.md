# Use Backstage as Initial Presentation Framework

* Status: proposed

## Context and Problem Statement


An Internal Developer Platform is a system of components working together to provide a Developer Experience. A good Developer Experience requires a user-friendly interface through which a developer can interact with the system. We must agree on a set of conventions for implementing and packaging user-interface components.


## Considered Options

* Use [Backstage](backstage.io) as initial presentation framework
* Build a UI from scratch

## Decision Outcome

Chosen option: Use [Backstage](backstage.io) as initial presentation framework and extend it as necessary so that we can demonstrate working software faster and participate in a vibrant open source community.

## Pros and Cons of the Options

### Use Backstage as initial presentation framework

* Good, because Backstage is widely adopted in the community
* Good, because there is a set of conventions for extending Backstage
* Good, because Backstage implements a core set of Internal Developer Platform UI features out of the box
* Bad, because we may need to revisit choices to support UI portability in the future

### Build a UI from scratch

* Good, because we have full control of design
* Good, because we can use [PatternFly](https://www.patternfly.org/) to support cross-cutting UI concerns
* Bad, because this path represents a lot of work that isn't necessarily focused on the problems we most want to solve