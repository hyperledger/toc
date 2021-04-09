---
layout: default
title: Criteria for a Promoted Release
nav_order: 4
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Criteria for a Promoted Release

Prior to bringing a project to the TSC for a vote on granting a Promoted
Release, a project must fulfill the following criteria:

1.  Project has reached [Graduated](./project-lifecycle.md#graduated) status (the processes and community are
    mature)
2.  The release features substantially fulfill the project\'s charter
3.  The release satisfies criteria defined by the project itself. All
    projects should meet some internally defined non-functional release
    criteria (bug counts, performance, etc.)
    1.  Test coverage (unit and functional/integration) is sufficient to
        have confidence that the release supports the non-functional
        criteria
    2.  Maintainers have reviewed all remaining open bugs and agree on
        severity/priority
    3.  Zero high or highest priority bugs remain open
    4.  The preceding release candidate has been published for a minimum
        period of time of 2 weeks
    5.  The release should not require users/operators to compile code
        to operate the base project on supported platforms
    6.  The documentation is sufficient to ensure that users/operators
        have clear guidance on how to get started and how to configure
        and operate.
4.  The project has met all technical criteria for the release:
    1.  The project has met all the criteria for [CII Best Practices Badge](https://bestpractices.coreinfrastructure.org/),
    2.  A security audit provided by Hyperledger was completed:
        1.  no bugs that affect security of the system remain open unless they have mitigating workarounds published in release notes
        2.  crypto code included in the release has been audited for crypto export compliance
    3.  A license scan was completed and all issues were resolved,
        including receiving an exception from the legal committee.
    4.  Changelog of all commits is generated and published.
    5.  Release notes generated and published.
