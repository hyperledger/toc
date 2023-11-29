---
layout: default
title: Project Best Practices
parent: Guidelines
grand_parent: Hyperledger TOC
nav_order: 4
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Project Best Practices

## Introduction

This document provides a high level survey of best practices and suggestions for various aspects of management and maintenance of Hyperledger projects.
In many cases links are provided to other resources at Hyperledger and beyond for more detailed information.

The best practices generally apply to Hyperledger Graduated projects.
Many of the best practices also apply to Incubation projects, especially Incubation projects that are on a path to become a Graduated project.

The document will first provide a survey of existing guidelines and practices and then dive deeper into areas not covered elsewhere.

## Project Incubation Entry Considerations

The [Project Incubation Entry Considerations](../governing-documents/project-incubation-entry-considerations.md) provides baseline suggestions for new Incubations projects. For example:
* Follow basic open-source practices and licensing
* [DCO](https://developercertificate.org/) sign-offs on commits
* Diverse set of maintainers and stakeholders

## Project Incubation Exit Criteria

The [Project Incubation Exit Criteria](../governing-documents/project-incubation-exit.md) defines minimum requirements for Graduated projects. These are good suggestions for any project. In a nutshell:
* Use Apache 2 license
* Foster an active and diverse contributor community.
  - See [Fostering a community](#Fostering-a-community) section for more details.
* Provide automated unit and integration test coverage.
  - See [Continuous Integration](#Continuous-Integration) section for more details.
* Provide project documentation.
  - See [Documentation](#Documentation) section for more details.
* Ensure project infrastructure is in place (Github repository, mailing list, Discord chat, CI).
  - See [Repository structure](#Repository-structure) section for more details.
* Identify security key contacts and address security vulnerabilities.
  - See [Security](#Security) section for more details.
* Work towards an [OpenSSF Best Practices Badge](https://bestpractices.coreinfrastructure.org/en)

## Repository structure

* Projects should follow the [Common Repository Structure](repository-structure.md) which provides details for required and recommended repository files.

## Maintainer guidelines

* Projects should document maintainers along with maintainer roles and responsibilities in a MAINTAINERS.md file.
* See the [Maintainers Guidelines](MAINTAINERS-guidelines.md) and [sample MAINTAINERS.md](SAMPLE-MAINTAINERS.md) for suggested duties of a maintainer and guidance on how to add and remove maintainers.

## Inclusive naming

* Projects should adopt the [Inclusive naming recommendations](https://wiki.hyperledger.org/display/TSC/DCI+Working+Group%3A+Inclusive+Naming+Proposal). In a nutshell:
  - Name the default branch 'main' instead of 'master'
  - Follow [inclusive naming conventions](https://inclusivenaming.org/)
  - Add an inclusive language statement
  - Optionally use GitHub Action [DCI-Lint](https://github.com/petermetz/dci-lint)

## Project governance

* Use an RFC process (or similar process) to drive consensus and track agreement on project major decisions, features, design, etc.
  - Examples - [Sawtooth RFC process](https://github.com/hyperledger/sawtooth-rfcs) (same process in Ursa, Grid), [Sawtooth RFC governance and team structure](https://github.com/hyperledger/sawtooth-rfcs/blob/main/text/0006-sawtooth-governance.md), [Fabric RFC process](https://github.com/hyperledger/fabric-rfcs) (evolution of Sawtooth RFC process, example of github pages), [Aries RFC process](https://github.com/hyperledger/aries-rfcs)
* Use [Community Specification License v1.0](https://spdx.org/licenses/Community-Spec-1.0.html) in RFC repositories - more details TBD
* Maintainer governance - see [Maintainer guidelines](#Maintainer-guidelines) above
* Document project roles and responsibilities (maintainers, release managers, contributors, etc)
* Document project operational procedures, including how to manage a project roadmap

## Fostering a community

* Foster a welcoming, positive, and public environment where contributions are encouraged. - See [Creating an Inclusive Community presentation](https://www.youtube.com/watch?v=lHOINFlb9JA)
* Decisions should be made in public, or at least socialized in public
* Engage on Discord Chat - see [Suggested Channel Organization and Naming](https://wiki.hyperledger.org/display/TF/Hyperledger%27s+Transition+to+Discord+Proposal)
* Use Mailing lists for official business - start with a single mailing list, consider multiple if there becomes a need (users list versus contributors/maintainers list)
* Host public meetings on a regular cadence. Ask community about best meeting time, consider two meetings to cover different regions, or rotating meeting times (shifted 8 hours or 12 hours).

## Finding and encouraging new contributors

* Provide easy-to-find contributing documentation, link to it from CONTRIBUTING.md. Examples:
  - https://wiki.hyperledger.org/display/BESU/Contributing
  - https://github.com/hyperledger/cacti/blob/main/CONTRIBUTING.md
  - https://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html
  - https://wiki.hyperledger.org/display/indy/How+to+Contribute
  - https://hyperledger.github.io/firefly/contributors/
  - https://github.com/hyperledger/iroha/blob/main/CONTRIBUTING.rst
* Present at Meetups - Virtual or in person – these are well attended and the videos also get many views
  - Email meetup@hyperledger.org if you're interested in presenting or join one of the [bi-weekly Meetup and Workshop planning calls every other Thursday at 9:30 AM pacific](https://lists.hyperledger.org/g/meetups/calendar)
* Host technical Workshops - Virtual or in person (e.g. Global Forum) – these are well attended and the videos also get many views
  - Reach out to one of the Hyperledger Community Architects or join one of the [bi-weekly Meetup and Workshop planning calls every other Thursday at 9:30 AM pacific](https://lists.hyperledger.org/g/meetups/calendar)
* Take part in annual Mentorship program
  - Near the beginning of each year maintainers have the option to [submit projects to the annual Hyperledger mentorship program](https://wiki.hyperledger.org/display/INTERN/Mentorship+Projects) and work with mentees or code, documentation or research projects
* See also [Raising the Profile of your Hyperledger Project or Lab](https://docs.google.com/presentation/d/13nji_R-op77ERT-AV3-CbOOZwAOjtvq33RRGnjpL3Gc/edit#slide=id.g3cf4a9ebda_0_647)

## Project management and issues

* Maintain a written project roadmap, discuss in project meetings
* Create, clarify, and label issues in Github for contributors. Use Github default labels, e.g. "good first issue"
  - Consider splitting "good first issue" label into multiple labels, e.g. "good-first-issue-100-introductory" through "good-first-issue-400-expert" (see Cacti project)
* Review, triage, comment on, and close inbound Github issues

## Pull Request management

* Quick review turnarounds are appreciated and encourage future contributions (and shows up in Insight reports).
* Equal attention to PRs - review in order of arrival as a general rule of thumb.
* 'Over'-communicate in PR comments, especially if review is delayed - contributors don't know what is in a maintainer's head
* Be gentle on new contributors, perhaps relax coding guidelines and fix up later
* Don't leave contributors hanging... if the contribution is not a good fit say so
* Mentor new contributors through the process, in PRs and otherwise

## Security

* Provide three named security contacts per project
* Define security issue reporting process in SECURITY.md with reference to [Hyperledger reporting process](https://wiki.hyperledger.org/display/SEC/Defect+Response)
* Review, respond, and act on reported security vulnerabilities
* Follow security issue disclosure process - see [Disclosure task force](https://github.com/hyperledger/toc/issues/48)
* Leverage automated scans, tooling depends on language but usually includes some combination of:
  - linters
  - Software Composition Analysis dependency scans, e.g. Dependabot, Govulncheck
  - Static Application Security Testing (SAST) aka static analysis scans, e.g. CodeQL, Snyk
* Pin dependencies and keep dependencies up to date,  e.g. using Dependabot, although be wary of auto-upgrades and lookout for malware.
* Engage with Hyperledger staff on possibility of [security audits](https://wiki.hyperledger.org/display/SEC/Security+Code+Audits) for Graduated project major releases; address audit results and socialize
* Review [OpenSSF secure developer guide](https://github.com/ossf/wg-best-practices-os-developers/blob/main/docs/Concise-Guide-for-Developing-More-Secure-Software.md) and OpenSSF overview presentation to TOC ([charts](https://wiki.hyperledger.org/download/attachments/80775801/OpenSSF%20Hyperledger%2020230119.pdf?version=1&modificationDate=1674218724000&api=v2), [replay](https://youtu.be/0AFFIDKFNvc))
* Review and obtain OpenSSF Best Practices Badge - see [criteria](https://bestpractices.coreinfrastructure.org/en/criteria/0)
* Sign release artifacts (TBD) - see proposed [Security Artifact Signing task force](https://github.com/hyperledger/toc/issues/49)
* Also see [2022 security task force](https://wiki.hyperledger.org/display/TF/Task+Force+Recommendations)

## Documentation

* Documentation should minimally target the following audiences
  - User guide including Getting Started / Tutorial
  - Project developer guide including coding guidelines, design docs, build instructions, test instructions
  - Application developer guide
* See the [documentation template lab](https://github.com/hyperledger-labs/documentation-template) for an example of what to include in documentation
* [Documentation task force](https://wiki.hyperledger.org/display/TF/Documentation+task+force) will address Common styling guide, Recommended common publishing platform, Document best practices for creating documentation, etc.

## Releases

* Follow an established [Release taxonomy](https://toc.hyperledger.org/governing-documents/release-taxonomy.html) - either SemVer or CalVer; use consistent pre-release tags (e.g. -preview, -alpha, -beta)
* Document release strategy and release process including required approvals
* Document branch strategy, e.g. one branch per major.minor release works well so that it can be maintained in isolation while delivering major.minor.patch releases
* Document Long-term support (LTS) release strategy - [Fabric example](https://github.com/hyperledger/fabric-rfcs/blob/main/text/0005-lts-release-strategy.md)
* Use Github Actions to automate release process, e.g. publish artifacts and release notes upon drafting a GitHub release
* Use [Reproducible builds](https://reproducible-builds.org/)
* Sign release commits with [GPG](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits) (-S or --gpg-sign); sign release artifacts - see [Security Artifact Signing task force](https://github.com/hyperledger/toc/issues/49)
* Release artifacts
  - binaries attached to GitHub release
  - NPM packages - don't publish on every commit due to NPM limit of 1000 versions

## Continuous Integration

* GitHub Actions is the recommended CI platform, although use efficiently due to limits on number of runners, some ideas to limit runner usage:
  - Use [cancel-in-progress](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#example-using-concurrency-to-cancel-any-in-progress-job-or-run) to suppress multiple jobs for multiple pushes to the same pull request
  - Uncheck branch protection rule ["Require branches to be up to date before merging"](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-status-checks-before-merging) to reduce number of runs (potentially add a scheduled run if you are concerned about incompatible PRs getting merged)
  - Use [filters](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#filter-pattern-cheat-sheet) to eliminate unnecessary runs, e.g. doc PRs shouldn't require building and testing code.
  - Consider running some jobs on schedule (nightly) rather than on each pull request (e.g. full matrix of platform tests)
  - Inspect Github Actions run results on your own fork prior to opening Pull Request
  - Contact Hyperledger staff for the possibility of dedicated paid runners
* Pull request checks
  - DCO - [Developer Certificate of Origin](https://github.com/apps/dco)
  - Unit tests
  - Integration tests
  - Scans - see [Security](#Security) section, consider running on schedule (nightly) rather than on each pull request
  - Note - just because a change passes automated checks doesn't mean it is necessarily good, it still requires judicious maintainer review
* Test coverage reporting - run on-demand or nightly
* Keep CI clean and green at all times, address failures and flakes
* See also proposed [Automated Pipelines task force](https://github.com/hyperledger/toc/issues/44)

## GitHub configuration

* Define repository settings in `.github/settings.yml` so that they can be managed and tracked via pull requests, see [Fabric example](https://github.com/hyperledger/fabric/blob/main/.github/settings.yml).
* Consider using a CODEOWNERS file to specify write permission per directory
  - See [Fabric example](https://github.com/hyperledger/fabric/blob/main/CODEOWNERS) with additional `/docs` maintainers.
  - Add a link from CODEOWNERS to MAINTAINERS.md scope field so that users can find domain area contacts
* Consider using a .github/[PULL_REQUEST_TEMPLATE.md](https://raw.githubusercontent.com/hyperledger/fabric/main/.github/PULL_REQUEST_TEMPLATE.md) and .github/[ISSUE_TEMPLATE](https://github.com/hyperledger/fabric/tree/main/.github/ISSUE_TEMPLATE)
* Define Branch protection rules. Recommended configuration:
  - Check `Require a pull request before merging`
  - Check `Require approvals`
  - Check `Dismiss stale pull request approvals when new commits are pushed`
  - Check `Require review from Code Owners` to enforce CODEOWNERS file.
  - Check `Require status checks to pass before merging`
  - Uncheck `Require branches to be up to date before merging` to limit CI runs
  - Check `Restrict who can push to matching branches`
  - The remainder can remain unchecked unless there is a specific need
* Use [Reusable github actions](https://docs.github.com/en/actions/using-workflows/reusing-workflows) to reduce the number of top-level checks

## GitHub workflow

* Although there are often multiple paths to achieve an outcome in git and GitHub, there is value in defining a suggested path for contributors, both for the benefit of new GitHub users, and for the sake of project consistency.
  - See the [Hyperledger GitHub Contribution Guide](github-contribution-guide.md) for detailed guidance on forking, branching, remotes, creating pull requests, updating pull requests, and cherry picking
* **Rebase merging** is preferred over **Merge commits** and **Squash merging** to keep commit history and PR description clean (assuming contributors squash/amend their own pull requests)
* Nice to haves (consult the GitHub Best Practices documentation for details)
  - Try to have all the commits signed on your default branch. This is hard to do in practice, but could come in handy later.
  - Try to reduce the load on the CI by preserving the commit hashes post-merge (e.g. the commit hash on the main branch matches the commit hash from the pull request branch)
    - This makes it so that some CI tasks can be skipped on the main branch, thus reducing the load on the CI.
