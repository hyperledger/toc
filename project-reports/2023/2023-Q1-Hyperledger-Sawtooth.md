---
layout: default
title: 2023 Q1 Hyperledger Sawtooth
parent: 2023
grand_parent: Project Updates
---

# Project Health

Activity primarily focused on integration of Transact into sawtooth-lib, with
discussions about simplifying the build processes.

# Required Information

- Have you switched from master to main in all your repos? YEs
- Have you implemented the [Common Repository
  Structure](../guidelines/repository-structure.md) in all your repos? Yes
- Has your project implemented these inclusive language changes listed below to
  your repo? You can optionally [use the DCI Lint
  tool](https://github.com/petermetz/gh-action-dci-lint#usage) to make this a
  recurring action on your repo. Yes
  - master → main
  - slave → replicas
  - blacklist → denylist
  - whitelist → allowlist
- Have you added an [Inclusive Language
  Statement](https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example)
  to your project's documentation and/or Wiki pages?
  Yes: [Statement](https://sawtooth.hyperledger.org/community/contributing.html#inclusive-language)


# Questions/Issues for the TSC

No new issues

# Releases

- sawtooth-lib v0.8.0

# Overall Activity in the Past Quarter

Initial work on integrating transact into sawtooth-lib and initial release
(v0.8.0) was done. This is the first step in merging transact into sawtooth-lib
and eventually deprecating transact.

Various smaller updates went into sawtooth-lib, mostly to update it to the
latest Rust compiler and language features.

# Current Plans

The primary project focus currently is accessibility by potential future
contributors. In particular, the current docker-based build and deployment
approach seems like a barrier to entry; therefore, the plan is to simplify
these aspects of the project to reduce the barrier.

Adjustments to sawtooth-lib's transact integration will continue as it becomes
better integrated into the library.

# Maintainer Diversity

Maintainers are distributed across Bitwise IO, Cargill, Intel, and Walmart Labs.

# Contributor Diversity

Commits from 2022-10-26 to 2023-01-28 :  19
Committers from 2022-10-26 to 2023-01-28 :  3
Domains from 2022-10-26 to 2023-01-28 :  2

# Additional Information

[Insights](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222022-10-27T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-01-28T06:00:00.000Z%22%7D)

