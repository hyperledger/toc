---
layout: default
title: 2023 Q4 Hyperledger Sawtooth
parent: 2023
grand_parent: Project Updates
---

# Project Health

Project activity is similar to previous months with contributors mostly working
on bug fixes, code maintenance, and CI/build updates. Contributor discussions on
discord have increased as the team works through specific PRs.

# Questions/Issues for the TOC

None.

# Releases

There have been no releases since the last report.

# Overall Activity in the Past Quarter

The #sawtooth channel has continued to have user-level questions, many of which
are the result of documentation issues (thus the on-going effort to
enhance/correct documentation). Users are requesting better support for modern
versions of Ubuntu. The #sawtooth-contributors channel had technical discussion
on specific PRs.

Most PRs focused on documentation, bug fixes, linting, or CI/build enhancements.

# Current Plans

A (probably correct) PR was held up due to CI/build-related issues, and thus the
focus has shifted to fixing and updating CI. This includes a transition to
Github Actions, away from Jenkins, because it is more in-line with best
practices (both generally and the work being done by the automated pipeline
taskforce). Linting and build checks on sawtooth-core (1-3 branch) now work as
Github Actions, but integration tests remain in Jenkins. Work has been done in
prototyping updates to the dockerfiles used for integration tests. Next steps is
to merge those updates so they can be used to run integration tests manually,
and then integrate that into Github Actions to replace Jenkins.

# Maintainer Diversity

The process of moving inactive maintainers to retired (emeritus) status is
on-going.

We are optimistic that we can add a new maintainer within the next quarter.

# Contributor Diversity

Commits from 2023-07-28 to 2023-10-25 :  14

Committers from 2023-07-28 to 2023-10-25 :  4

Domains from 2023-07-28 to 2023-10-25 :  3

# Additional Information
[Insights](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222023-07-28T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-10-25T05:00:00.000Z%22%7D)
