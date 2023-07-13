---
layout: default
title: 2023 Q3 Hyperledger Cacti
parent: 2023
grand_parent: Project Updates
---


# Project Health

We've had a slight dip in active contributors this past few months, but other than that the project appears to be in good health, the maintainers are hard at work on unifying the former Weaver and Cactus code-bases and we've made some headway
with this by way of 
1. Starting the work on the new documentation website (which is based on the recommended documentation template of Tracy)
2. Making it so that the Weaver packages are part of the monorepo compilation and release process
3. Making some headway preparing for the Corda v5 release
4. Engaging with the community and seeking out opportunities to grow through contributions
5. Working with the LFX mentees who were selected for the given projects related to Cacti.

# Questions/Issues for the TOC

Just putting it out there: We are planning on applying for graduated status this year.
Not exactly sure when yet but we would like to make it happen at or around the same time
as we release our v2.0.0 and hopefully before the big workshop that we had planned for
November.

# Releases

We've issued `v2.0.0-alpha-prerelease` and `v2.0.0-alpha.1` and in the coming quarter plan on issuing `v2.0.0-alpha.2`
`v2.0.0-alpha.3` and also `v2.0.0` 

There might be additional alpha/beta/release candidate releases issued as needed because we are still
working on some of the vulnerable dependency upgrades and we plan on getting a security audit as well.

# Overall Activity in the Past Quarter

1. Most of our traffic comes from Discord (the chat)
2. The daily pair programming calls are in place and questions are being answered as they come up most of the time.
3. There is constant new development happening, we are actually being overloaded a little bit with pull requests because the CI is robust but slow-ish (apologies to Ry - we are hard at work on improving dependency caching and refactoring the CI to avoid duplicate work as much as possible but this is still in progress)
4. Worked on a draft for release management. This is an [open PR](https://github.com/hyperledger/cacti/pull/2337), and is currently being tested and evaluated.
5. Using the above release management draft as a guide, the Weaver packages were published under the Cacti namespace and appropriately tagged, with automated publishing configured through Github Actions.
6. The Weaver Lab repo was being maintained and augmented in minor ways because a client project had an active dependency on it. We would periodically sync those changes to the Cacti repo. That process has now concluded, and we have frozen the Weaver repo to further additions, and (thanks to Ry Jones) moved all open Weaver issues to the Cacti repo.
7. From a technical perspective, we started working on integration of the Cactus and Weaver code-bases, adding support for new ledgers such as Corda v5, ledger state proof generation and validation protocols for Besu and Ethereum, integration with DID registries, and conformity with Internet community standards.


# Current Plans

`What are the main features planned?`

1. Cross-ledger atomic transactions
2. Corda v5 support
3. Polkadot support
4. New documentation site
5. Ledger views and proofs for Besu and Ethereum
6. Support for IETF-standard Secure Asset Transfer Protocol (SATP) using Relays and Node Server
7. Syncing identities across permissioned networks using public DID registries and VCs
8. Performance measurement and benchmarking of cross-chain operations
9. We plan to issue v2.0.0 this quarter which will be a big deal!


# Maintainer Diversity

No new maintainers added.
At present we have 3 separate organizations with 2 maintainers each, 6 total.

# Contributor Diversity

https://insights-v2.lfx.linuxfoundation.org/cactus/technical-contributors/participating-organizations

# Additional Information

We plan on applying for graduated status in the coming months and if anyone has any preliminary feedback that is most welcome!
