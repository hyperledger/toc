# Introduction
All Hyperledger projects MUST have a `MAINTAINERS.md` file at the top-level directory of the source code. This document will provide guidelines on what should be included in the `MAINTAINERS.md` file.

# Guidelines
## List of Project Maintainers
The first thing that MUST be included in the `MAINTAINERS.md` file is a list of the project's maintainers, both active and emeritus.

It is recommended that the lists be sorted alphabetically and contain the maintainers name, GitHub ID, LFID, Company Affiliation, and Scope. The following shows the suggested format for the information:

**Active Maintainers**

| Maintainer | GitHub ID | LFID | Company Affiliation | Scope |
| ---------- | --------- | ---- | ------------------- | ----- |
|            |           |      |                     |       |

**Emeritus Maintainers**

| Maintainer | GitHub ID | LFID | Company Affiliation | Scope |
| ---------- | --------- | ---- | ------------------- | ----- |
|            |           |      |                     |       |

## What Does Being a Maintainer Entail
The `MAINTAINERS.md` file SHOULD contain information about the different types of maintainers that exist (whole project, repo, part of repo) and what their duties are (e.g., maintainers calls, quarterly reports, code reviews, issue cleansing).

## How to Become a Maintainer
The `MAINTAINERS.md` file SHOULD contain information about how to become a maintainer for the project. This section SHOULD list specific information about what is required. Information that SHOULD be included in this section:

* What is required before someone can be considered to become a maintainer
* Consider whether there should be different requirements based on the scope (whole project, repo, part of repo) of maintainership
* Whether sponsorship by an existing maintainer is required
* How maintainers are proposed to the community. A number of our projects require that a PR be done against the `MAINTAINERS.md` file to make this proposal
* How many maintainers must approve the proposed maintainer. This should include information about what happens if someone vetoes the proposal
* How long the existing maintainers have to respond to the proposal

## How Maintainers are Removed or Moved to Emeritus Status
The `MAINTAINERS.md` file SHOULD contain information about how a maintainer is removed from the list of active maintainers. Information that SHOULD be included in this section:

* What are the reasons a maintainer would be removed from the list of active maintainers
* How this is proposed; similar to the way in which maintainers are added, one way to do this is via a PR against the `MAINTAINERS.md` file
* How a emeritus maintainer becomes active again


# Example MAINTAINERS Files
* [Hyperledger Besu](https://github.com/hyperledger/besu/blob/master/MAINTAINERS.md)
* [Hyperledger Fabric](https://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html#maintainers)
* [Hyperledger Sawtooth](https://github.com/hyperledger/sawtooth-rfcs/blob/master/text/0006-sawtooth-governance.md#contributor-permission-levels)
* [Hyperledger Grid (same as Sawtooth)](https://github.com/hyperledger/grid-rfcs/blob/master/text/0008-grid-governance.md#contributor-permission-levels)
* [Hyperledger Transact (same as Sawtooth)](https://github.com/hyperledger/transact-rfcs/blob/master/text/0000-transact-governance.md#contributor-permission-levels)

# References
* [TSC Decision Log - Common Maintainers Management Policy](https://wiki.hyperledger.org/display/TSC/Common+Maintainers+management+policy)
