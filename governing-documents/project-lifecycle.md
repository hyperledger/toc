---
layout: default
title: Project Lifecycle
parent: Governing Documents
nav_order: 6
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Project Lifecycle

The term "project" within Hyperledger refers to a
collaborative endeavor to deliver a work item.
There may be some projects that are intended to produce a document, such
as a requirements or use cases document, a whitepaper, or analysis.
Other projects develop a new capability, refactor, or remove an
existing capability for the Hyperledger technology releases. Such
projects may take the form of a new component (e.g., a new repository) or
may propose additions, deletions, or changes to an existing
repository or repositories.

Many other open source initiatives leverage an incubation process for
new work items. Incubation seems to have the desired effect of encouraging
new ideas and tracks of work, while at the same time providing clear
guidance to the broader community as to what is real and supported,
versus what is still in the exploratory, experimental, or developmental
phases.

Therefore, Hyperledger has adopted a similar lifecycle process as
follows:

![Project lifecycle in graph format](project-lifecycle.svg "Project Lifecycle Graph").

Projects are in one of six possible states:

-   [*Proposal*](#proposal)
-   [*Incubation*](#incubation)
-   [*Graduated*](#graduated)
-   [*Dormant*](#dormant)
-   [*Deprecated*](#deprecated)
-   [*End of Life*](#end-of-life)

Projects may not necessarily move through those states in a linear way
and may go through several iterations.

# Proposal

Project Proposals must be submitted to the [TOC](https://www.hyperledger.org/about/leadership)
for review, using [Proposal Template](https://hyperledger.github.io/hyperledger-hip/).
Proposals that are approved enter into an *Incubation* state, unless
they are of a refactoring nature, in which case the project is turned over
to the relevant project maintainers to handle as they deem fit.

A Proposal must:

-   Have a clear description
-   Have a well-defined scope
-   Identify committed development resources
-   Identify initial maintainers
-   Be vendor neutral

# Incubation

Approved project proposals enter into *Incubation*. For new
components and modules, a repository is created under the
[Hyperledger Github org](https://github.com/hyperledger)
. New
features or capabilities must be handled through pull requests labeled
with tags that identify the project and tag it as
*incubator*. Pull requests ideally are capable of being enabled and disabled with feature-flags.

Projects in *Incubation* can overlap with one another.
Entering *Incubation* is meant to be fairly easy to allow for
community exploration of different ideas.

After a project qualifies to be declared *Graduated*, the
*project* maintainers can then vote to request a graduation
review by the TOC.

Entering *Incubation* does not guarantee that the project will
eventually get to the *Graduated* state. Projects may never get
to the *Graduated* state.

Projects seeking to graduate from *Incubation* must meet
the criteria defined in the 
[Incubation Exit Criteria](./project-incubation-exit.md) document.

# Graduated

(Formerly called 'Active') <a id="active"></a>

Projects that have successfully exited the *Incubation* phase
are in the *Graduated* phase.

# Dormant

Projects enter the *Dormant* state when the normal functions are
suspended or slowed down for a period of time. The TOC decides to move a project to or from the *Dormant* state upon request.
If *Dormant* projects are re-activated, they re-enter the *Incubation*
state even if they entered the *Dormant* state from the *Graduated* state.

# Deprecated

Anyone may propose that a project be *Deprecated* by submitting a
rationale and identifying a substitute project or component, if any. The
maintainers of the project shall vote on such a request and if it
passes, make that recommendation to the TOC. Members of the community
that disagree with the request can make their case before the TOC. The
TOC will consider all points of view and render a final decision
whether to deprecate.

A *Deprecated* project will be maintained for a six month
period by its community, after which it will be removed from any
subsequent formal releases. Notice will be given to the public of the
project deprecation. After the six-month deprecation
period, the project will be labeled *End of Life*.

# End of Life

A project that is no longer actively developed or maintained.
