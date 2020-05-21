---
layout: default
title: Project Lifecycle
nav_order: 6
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Project Lifecycle

The term "project" within Hyperledger will refer to a
collaborative endeavor to deliver a work item.
There may be some projects that are intended to produce a document, such
as a requirements or use cases document, a whitepaper, or analysis.
Others may be to develop a new capability, or refactor (or remove) an
existing capability for the Hyperledger technology releases. Such
projects may take the form of a new component (e.g. a new repository) or
may propose additions, deletions or changes to an existing
repository(s).

Many other open source initiatives leverage an incubation process for
new work items, and this seems to have a desired effect of encouraging
new ideas and tracks of work, while at the same time providing clear
guidance to the broader community as to what is real and supported,
versus what is still in the exploratory/experimental/developmental
phases.

Therefore Hyperledger has adopted a similar lifecycle process as
follows:

Projects are in one of five possible states:

-   [*Proposal*](#proposal)
-   [*Incubation*](#incubation)
-   [*Active*](#active)
-   [*Promoted Release*](#promoted-release)
-   [*Deprecated*](#deprecated)
-   [*End of Life*](#end-of-life)

Projects may not necessarily move through those states in a linear way
and may go through several iterations.

# Proposal

Project Proposals shall be submitted to the [TSC](https://www.hyperledger.org/about/leadership)
for review, using [Proposal Template](https://wiki.hyperledger.org/display/TSC/Project+Proposals).
Proposals that are approved shall enter into an *Incubation* state, unless
they are of a refactoring nature, in which case they will be turned over
to the relevant project maintainer(s) to handle as they deem fit.

A Proposal must:

-   have a clear description
-   have a well-defined scope
-   identify committed development resources
-   identify initial maintainers
-   be vendor neutral

# Incubation

Approved project proposals enter into *Incubation*. For new
components/modules, a repository will be created under the
[Hyperledger Github org](https://github.com/hyperledger)
and optionally in [JIRA](https://jira.hyperledger.org), if requested. New
features/capabilities should be handled through pull requests labeled
with tags that identify the project and tag it as
*incubator* (and will ideally be capable of being enabled/disabled with feature-flags).

Projects in *Incubation* may overlap with one another.
Entering *Incubation* is meant to be fairly easy to allow for
community exploration of different ideas.

Once a project qualifies to be declared *Active*, the
*project*\'s maintainers can then vote to request a graduation
review by the TSC.

Entering *Incubation* does not guarantee that the project will
eventually get to *Active* state. Projects may never get
to *Active* state.

Projects seeking to graduate from *Incubation* must meet
the criteria defined in the 
[Incubation Exit Criteria](./project-incubation-exit.md) document.

# Active

Projects that have successfully exited the *Incubation* phase
are in the *Active* phase. *Active* projects are eligible
for [*Promoted Releases*](#promoted-release).

# Promoted Release

A project\'s maintainers seeking to publish a *Promoted
Release* (see Hyperledger\'s use of [semver](./release-taxonomy.md#1);
also, [semver.org](https://semver.org)) must seek approval of the TSC
whether in Active or Incubation status as defined above. While it is
expected that most projects will have reached an *Active* status by
the time their maintainers seek to announce a *Promoted Release*, the
TSC may approve such requests also in cases where the project is still
in *Incubation* status, should the TSC believe that the project\'s code is
sufficiently mature.

# Deprecated

Anyone may propose that a project be *Deprecated*, by submitting a
rationale and identifying a substitute project/component (if any). The
maintainers of the project shall vote on such a request and if it
passes, make that recommendation to the TSC. Members of the community
that disagree with the request shall make their case before the TSC. The
TSC shall consider all points of view and render a final decision to
deprecate or not.

A *Deprecated* project will be maintained for a six month
period by its community, after which it will be removed from any
subsequent formal releases. Notice will be given to the public of the
project\'s deprecation. After the six-month deprecation
period, the project will be labeled *End of Life*.

# End of Life

A project that is no longer actively developed or maintained.
