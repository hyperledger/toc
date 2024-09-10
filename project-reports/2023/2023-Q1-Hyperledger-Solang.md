---
layout: default
title: 2023 Q1 Hyperledger Solang
parent: 2023
grand_parent: Project Updates
---

# Project Health

Hyperledger Solang development is going very well, and we have made huge strides towards compatibility with the latest Solana and Substrate chains.
We hope to see more user activity in the following quarter, as the compiler is now usable for end-users (or Solidity developers). We expect to be
helping users and fixing bugs as they arise.

# Required Information

- Have you switched from master to main in all your repos? **Yes**
- Have you implemented the [Common Repository Structure](../../governing-documents/repository-structure.md) in all your repos? **Only the main solang repo**
- Has your project implemented these inclusive language changes listed below to your repo? You can optionally [use the DCI Lint tool](https://github.com/petermetz/gh-action-dci-lint#usage) to make this a recurring action on your repo.
  - master → main
  - slave → replicas
  - blacklist → denylist
  - whitelist → allowlist
  **Yes** (please note [this issue in the DCI lint tool](https://github.com/petermetz/gh-action-dci-lint/issues/2))
- Have you added an [Inclusive Language Statement](https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example) to your project's documentation and/or Wiki pages? **Yes**

# Questions/Issues for the TSC

There are no issues at this time.

# Releases

Since entering incubation, we have had a steady stream of releases:

* 2022-09-16: Hyperledger Solang v0.1.13 Genoa
* 2022-12-02: Hyperledger Solang v0.2.0 Berlin

  This release marks stability for the latest Parity Substrate/Polkadot chain
* 2023-01-05: Hyperledger Solang v0.2.1 Rio
* 2023-02-20: Hyperledger Solang v0.2.2 Alexandria

  This release marks stability for the latest Solana's Anchor and generates Solana IDL metdata

# Overall Activity in the Past Quarter

We have been working hard towards compatibility with both Parity Substrate (including Polkadot) and Solana. Both these efforts are now complete and we hope to see more user activity.

Discord is very active and we see new users ask questions.

# Current Plans

* Do everything to support and attract Solidity developers on Solana and Substrate
* Improve the developer experience for Solidity
* Maintain compatibility the latest Solidity version

# Maintainer Diversity

We have three active maintainers: Sean Young, Lucas Steuernagel, and Cyrill Leutwiler. They are distributed across Solana Labs and Parity Technologies.

# Contributor Diversity

Since entering incubation (2022-08-30, commit f1f90b538e0adf8d4a1d47179ef9b92d7d60d040):

* 190 commits
* 8 different commit authors

Salaheldin Soliman, last years Hyperledger Mentee, continues to make great contributions.

# Additional Information

None at this time.
