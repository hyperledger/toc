---
layout: default
title: 2024 Q3 Hyperledger Besu
parent: 2024
grand_parent: Project Updates
---

# Project Health

The Besu project is thriving at the moment. There's growing interest in both public blockchain networks and private chains, with several Layer 2 solutions considering Besu for their infrastructure. Publicity around the work on public/private feature parity and new contributions is also increasing. Community activity on Discord has risen, contributions are up, and existing contributors and maintainers are collaborating more effectively than before. Overall, the project's health is robust. The #besu-enterprise channel has been effective in directing new interest in private networks to the right support teams. Discord support and engagement with maintainers and documentation remain strong.

# Questions/Issues for the TOC

None right now.

# Releases

We had fewer issues with releases this quarter, though it remains burdensome to deal with GitHub, besu-native, besu-homebrew, besu-docs and other aspects of the release process. Analysis of prior release challenges have been captured, and a [new iteration of the process has been developed](https://github.com/hyperledger/besu/pull/7685), which will be used next quarter.

This quarters releases:

- 24.7.0
- 24.7.1
- 24.8.0
- 24.9.0
- 24.9.1

The Besu releases from 24.7.0 to 24.9.1 brought a variety of key updates and improvements. Version 24.7.0 introduced performance enhancements, feature deprecations, and support for subnet-based peer permissions, while 24.7.1 added snap sync for IBFT/QBFT and addressed trie log pruning issues. Version 24.8.0 focused on private transaction tracing and Mainnet support, while 24.9.0 and 24.9.1 delivered updates in receipt compaction, JSON-RPC improvements, and further performance optimizations. Each release also included important bug fixes.

# Overall Activity in the Past Quarter

Chat channels remain highly active, with maintainers and developers collaborating to support users, node operators, and more. Any security issues which have been reported have been promptly patched. 

This quarter, maintainers were primarily focused on the Prague hardfork, addressing peering/sync issues and improvements to Snap Server. Technical debt pay-down continues, primarily in the form of performance analysis and improvement, as well as code decoupling to allow more modular use. Team is aligned around Verkle Tries, EOF and the Prague Fork, as well as finishing up the Public/Private network feature parity work and shipping a Bonsai Archive solution. 

# Current Plans

While the Prague and Osaka upgrades remain the projects primary focus, in Q4 we continue to chip away at technical debt and modularity work. Feature sunset has been announced [here](https://www.lfdecentralizedtrust.org/blog/sunsetting-tessera-and-simplifying-hyperledger-besu). A big focus of the maintainers will be on performance and stability in Q4, targeting a much higher gas throughput number in 2025 for Besus execution (road to Gigagas). 

Non-protocol feature work is largely paused in this quarter besides Bonsai Archive and work on the plug-in API alongside new documentation to attract plug-in devs and L2s to use the system.

# Maintainer Diversity

Luis Pinto was added as a maintainer this quarter, and multiple, full-time contributors have joined the team - we expect them to earn maintainer status later in Q4.  Part-time contributions continue and are increasing.

# Contributor Diversity

Many new contributors added PRs this quarter. Some were contributing to API features, or newly configurable options. Others were fixes to bugs, and some were cleanup, typo fixing (likely airdrop farming). Regardless, contribution activity is healthy. We are looking to keep some of these folks engaged. 

# Additional Information
