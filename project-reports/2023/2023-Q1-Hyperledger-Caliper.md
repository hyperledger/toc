---
layout: default
title: 2023 Q1 Hyperledger Caliper
parent: 2023
grand_parent: Project Updates
---

# Project Health

* 2 active maintainers
* PRs continuously submitted and merged (PR rate dropped a bit since the previous quarter, expected to improve in the next quarter)
* Questions on Discord and GitHub are regularly answered
* Monthly contributor calls (discussion happens mostly on Discord, as needed)

# Required Information

- Have you switched from master to main in all your repos? __Yes.__
- Have you implemented the [Common Repository Structure](../../governing-documents/repository-structure.md) in all your repos? __Yes.__
- Has your project implemented these inclusive language changes listed below to your repo? You can optionally [use the DCI Lint tool](https://github.com/petermetz/gh-action-dci-lint#usage) to make this a recurring action on your repo. __Yes.__
  - master → main
  - slave → replicas
  - blacklist → denylist
  - whitelist → allowlist
- Have you added an [Inclusive Language Statement](https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example) to your project's documentation and/or Wiki pages? [__Yes.__](https://hyperledger.github.io/caliper/vNext/contributing/#inclusive-language-guidelines)

# Questions/Issues for the TSC

Not at this time.

# Releases

The latest stable release is v0.5.0; we're also continuously publishing unstable releases after every merged PR:

* [npm](https://www.npmjs.com/package/@hyperledger/caliper-cli/v/0.5.0)
* [DockerHub](https://hub.docker.com/layers/caliper/hyperledger/caliper/0.5.0/images/sha256-3a7df18ef6a17a8c851dac19241049be2375dc892643c576932f360ca9d7198c?context=explore)

# Overall Activity in the Past Quarter

[List of merged PRs (3)](https://github.com/hyperledger/caliper/pulls?q=is%3Apr+merged%3A2022-12-08..2023-03-28+)

Summary of activities:
* CI pipeline improvements and fixes
* Planning collaboration with PSWG
* Submitting Caliper-PSWG co-mentored project proposal for the mentorship

# Current Plans

* Overview and decrease the issue backlog.
* Create developer docs that exhaustively document internal Caliper workings.
* Probably shrink the scope of Caliper to highly configurable workload generation and reporting (but less focus on monitoring and SUT managemenent).
* The Ethereum/Besu connector receives increasing attention, but its feature set is limited, it should be enhanced.
* Adjust Caliper capabilities if needed for PSWG-related collaboration (e.g., easier integration into k8s).

# Maintainer Diversity

[Current maintainers.](https://github.com/hyperledger/caliper/blob/943ab2a22872639f39ccb36f8baf94b2863e21c6/MAINTAINERS.md)

# Contributor Diversity

Contributions from maintainers and recent project mentees.

# Additional Information

N.A.
