# Which Open Source Software License Should We Use?

* Status: accepted
* Deciders: Assemble Dev Team, Red Hat Legal
* Date: 2022-09-20


## Context and Problem Statement

We needed to decide which Open Source Software Licensing we should use to ensure the project and it's contributors are covered from a legal perspective.

## Decision Drivers 

* Ensure licensing does not conflict with other Open Source projects we are developing with, namely Backstage.io and Konveyor.io
* Ensure license allows the proper ammount of flexibility for open source contributions, and proprietary implementations
* Ensure license is inline with Cloud Native Computing Foundation requirements for potential acceptance

## Considered Options

* https://www.apache.org/licenses/LICENSE-2.0
* https://opensource.org/licenses/MIT


## Decision Outcome

The Apache 2 License was chosen because it was inline with multiple open source inititives that our project is aligned to including konveyor.io, backstage.io and https://github.com/redhat-appstudio. Our project governance team needs to ensure this license is placed at the root of each repository that are intended for open source useage. Our project governance team needs to ensure contributors are aware of the license before making any pull requests.

### Positive Consequences <!-- optional -->

* The license offers everything we need from the decision drivers and is widely used within Red Hat


### Negative Consequences <!-- optional -->

* Understanding the governance of the Apache 2 license is more complex than the MIT license

