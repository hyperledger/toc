---
layout: default
title: 2024 Q2 Hyperledger Besu
parent: 2024
grand_parent: Project Updates
---

# Project Health

The Besu project is doing quite well these days. There is significant interest around public blockchain networks and private chains. This includes a number of L2s that are looking to use Besu in their infrastructure, as well as more and more publicity around the public/private feature parity work (and new contributions). Community interest in Discord is up, contribution numbers are up, engagement by existing contributors and maintainers looks a lot more collaborative than it used to. Overall health is quite good. The #besu-enterprise channel has also helped funnel a lot of new traffic and interest around private networks to the right folks for support. Discord support overall remains strong and engagement with maintainers and the docs is looking strong. 

# Questions/Issues for the TOC

None right now.

# Releases

We had several issues with releases this quarter. This was due to the switch over to a new Github Actions-based release process, and the last removal of CircleCI. There have been a lot of headaches with processes on the GH side and it has become burdensome to deal with Github, besu-native, and other parts of the release. The Consensys team primarily handles releases, and may prepare a post-mortem.

We did release several strong releases this quarter, however. 

- 24.5.1
- 24.5.2
- 24.6.0 

These releases brought some high impact features like substantial peering performance improvements, block processing improvements, logging and other fixes, and RPC improvements. We also shipped SnapSync as a Server to allow Besu nodes to serve data to their peers over the Snap protocol. A big win for the health of Ethereum Mainnet and (eventually) for private networks. 

# Overall Activity in the Past Quarter

Chat channels stay very active. Maintainers and devs are helping each other support users, node operators, and more. Some security issues have come in and been patched. 

This quarter, maintainers were primarily focused on the Prague hardfork, addressing peering/sync issues and technical debt, shoring up performance, and shipping Snap Server. We are attempting to clear technical debt for a jam-packed 2H roadmap and delivery schedule, aligned around EOF and the Prague Fork, as well as finishing up the Public/Private network feature parity work and shipping a Bonsai Archive solution. 

# Current Plans

In the coming quarter we plan to continue to chip away at technical debt and modularity work. We also plan on beginning to sunset some legacy features like Tessera privacy. A blog is now in review announcing these plans and stating a timeline. This work will help streamline the code-base and get private networks on the most performant formats like Bonsai and Snap. This work will spill into Q3 and likely Q4. A big focus of the maintainers will be on performance and stability in Q3, targeting a much higher gas throughput number in 2025 for Besu's execution (road to Gigagas). 

Feature work is largely paused in this quarter besides Bonsai Archive and work on the plug-in API alongside new documentation to attract plug-in devs and L2s to use the system.

# Maintainer Diversity

No new maintainers were added this quarter, but several contributors remained active or increased activity to move toward maintainership. 

# Contributor Diversity

Many new contributors added PRs this quarter. Some were around private net features, like a fixed bass fee. Others were fixes to bugs, and some were cleanup, typo fixing (likely airdrop farming). Regardless, contribution activity is healthy. We are looking to keep some of these folks engaged. 

# Additional Information
