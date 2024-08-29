---
layout: default
title: Project Lifecycle
parent: Governing Documents
grand_parent: LF Decentralized Trust TAC
nav_order: 4
---

[//]: # 'SPDX-License-Identifier: CC-BY-4.0'

# Project Lifecycle

The term "project" within Linux Foundation Decentralized Trust (LFDT) refers to a
collaborative endeavor to deliver a work item.
There may be some projects that are intended to produce a document, such
as a requirements or use cases document, a whitepaper, or analysis.
Other projects develop a new capability, refactor, or remove an
existing capability for the LFDT technology releases. Such
projects may take the form of a new component (e.g., a new repository) or
may propose additions, deletions, or changes to an existing
repository or repositories.

Many other open source initiatives leverage an incubation process for
new work items. Incubation seems to have the desired effect of encouraging
new ideas and tracks of work, while at the same time providing clear
guidance to the broader community as to what is real and supported,
versus what is still in the exploratory, experimental, or developmental
phases.

Therefore, LFDT has adopted a similar lifecycle process as
follows:

![Project lifecycle in graph format](project-lifecycle.svg 'Project Lifecycle Graph').

Projects are in one of four possible states:

- [_Incubation_](#incubation)
- [_Graduated_](#graduated)
- [_Dormant_](#dormant)
- [_Archived_](#archived)

Projects may not necessarily move through those states in a linear way
and may go through several iterations.

# Proposal

Project Proposals must be submitted to the [TAC](https://www.lfdecentralizedtrust.org/about/leadership)
for review, using [Proposal Template](https://lfdt.github.io/lfdt-hip/).
Proposals that are approved enter into an _Incubation_ state, unless
they are of a refactoring nature, in which case the project is turned over
to the relevant project maintainers to handle as they deem fit.

A Proposal must:

- Have a clear description
- Have a well-defined scope
- Identify committed development resources
- Identify initial maintainers
- Be vendor neutral

# Incubation

Approved project proposals enter into _Incubation_. For new
components and modules, a repository is created under the
[LFDT Github org](https://github.com/lfdt)
. New
features or capabilities must be handled through pull requests labeled
with tags that identify the project and tag it as
_incubator_. Pull requests ideally are capable of being enabled and disabled with feature-flags.

Projects in _Incubation_ can overlap with one another.
Entering _Incubation_ is meant to be fairly easy to allow for
community exploration of different ideas.

After a project qualifies to be declared _Graduated_, the
_project_ maintainers can then vote to request a graduation
review by the TAC.

Entering _Incubation_ does not guarantee that the project will
eventually get to the _Graduated_ state. Projects may never get
to the _Graduated_ state.

Projects seeking to graduate from _Incubation_ must meet
the criteria defined in the
[Incubation Exit Criteria](./project-incubation-exit.md) document.

# Graduated

(Formerly called 'Active') <a id="active"></a>

Projects that have successfully exited the _Incubation_ phase
are in the _Graduated_ phase.

The TAC may decide to move a _Graduated_ project that no longer meets
the [Incubation Exit Criteria](./project-incubation-exit.md) back to
the _Incubation_ state until it meets the criteria again.

# Dormant

(Covers the state formerly known as 'Deprecated') <a id="deprecated"></a>

Projects enter the _Dormant_ state when the normal functions are
suspended, slowed down for a period of time, or the project is being
deprecated.

When possible, the maintainers of the project shall vote on such a change
of state and if it passes, make that recommendation to the TAC, but
anyone may propose that a project be moved to _Dormant_ state. Members
of the community who disagree with the request can make their case
before the TAC. The TAC will consider all points of view and render a
final decision.

If _Dormant_ projects are re-activated, they re-enter the _Incubation_
state even if they entered the _Dormant_ state from the _Graduated_ state.

# Archived

(Formerly called 'End of Life')<a id="end-of-life"></a>

Projects that have been in the _Dormant_ state for a period of 6 months
will be automatically archived.

If anyone wants to resume work on an _Archived_ project they may
submit a proposal to the TAC for consideration.

If an _Archived_ project is re-activated, it re-enters the _Incubation_
state independent of its prior history.
