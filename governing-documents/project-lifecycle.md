---
layout: default
title: Project Lifecycle
parent: Governing Documents
grand_parent: Hyperledger TOC
nav_order: 4
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

Projects are in one of four possible states:

-   [*Incubation*](#incubation)
-   [*Graduated*](#graduated)
-   [*Dormant*](#dormant)
-   [*Archived*](#archived)

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

The TOC may decide to move a *Graduated* project that no longer meets
the [Incubation Exit Criteria](./project-incubation-exit.md) back to
the *Incubation* state until it meets the criteria again.

# Dormant

(Covers the state formerly known as 'Deprecated') <a id="deprecated"></a>

Projects enter the *Dormant* state when the normal functions are
suspended, slowed down for a period of time, or the project is being
deprecated.

When possible, the maintainers of the project shall vote on such a change
of state and if it passes, make that recommendation to the TOC, but
anyone may propose that a project be moved to *Dormant* state. Members
of the community who disagree with the request can make their case
before the TOC. The TOC will consider all points of view and render a
final decision.

If *Dormant* projects are re-activated, they re-enter the *Incubation*
state even if they entered the *Dormant* state from the *Graduated* state.


# Archived

(Formerly called 'End of Life')<a id="end-of-life"></a>

Projects that have been in the *Dormant* state for a period of 6 months
will be automatically archived.

If anyone wants to resume work on an *Archived* project they may
submit a proposal to the TOC for consideration.

If an *Archived* project is re-activated, it re-enters the *Incubation*
state independent of its prior history.
