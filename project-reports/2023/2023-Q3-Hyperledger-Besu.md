---
layout: default
title: 2023 Q3 Hyperledger Besu
parent: 2023
grand_parent: Project Updates
---

# Project Health

Hyperledger Besu continues its momentum for usage on public and private Ethereum and Ethereum-like networks. There is an uptick in contributions on the private network side with three contributors being nominated for Maintainer status at Kaleido and Web3Labs. We continue to focus on improvements around Bonsai and readying private networks for the storage format. Client performance is seeing improvement across sync, block processing, and RPC. Discord activity remains heavy, with a relatively even split between public and private network questions and suggestions. Execution clients are becoming an item of note for Ethereum L2s and L3s. Besu is setting strategy around this future and engaging multiple L2 networks, starting with Linea. 

# Questions/Issues for the TOC

Are there remaining asks of Consensys around the CI that should be spelled out?

# Releases

[Releases](https://github.com/hyperledger/besu/releases) this quarter:

- 23.7.1
- 23.7.2
- 23.7.3

# Overall Activity in the Past Quarter

Heavy activity in chat channels as usual around community support, documentation questions, and staking/node operator questions. There was discussion around separating out #besu into #besu-public-net and #besu-private-net to better support users. There has also been an increase in asks around certifications and tutorials for development. 
Maintainers this quarter have been primarily focused on tech debt resolution, Cancun development, the EVM tool and optimizations, and private network bug fixes and optimizations. Not much progress was made on consensus mechanism modularity. As the client moves to consolidate Mainnet and Private network defaults around Bonsai and Snap Sync, we hope this work will progress around a more unified client view on both network types. 
L2s have also been a popular topic of questions and feature requests, both in Discord and in our Github. We expect this to continue with Linea's adoption of Besu components in its zkEVM infrastructure. 

We had some security reports. Details shared in our traditional security channels. 

# Current Plans

The plug-in revitalization work was back-burnered in Q3, but may be prioritized in Q4 with a renewed push for Besu in many L2s and in modular consensus mechanism working group. Bonsai continues to improve with more storage reductions and performance improvements continuing into next quarter with an eye on Verkle Tries. In development is an RPC scaling "fleet mode" solution, as well as Bonsai-compatible ARCHIVE storage format. We also expect improvements to sync time and resiliency in the next quarter. We hope to revisit modular consensus mechanisms in Q4.  

# Maintainer Diversity

Three PRs opened to elevate two Web3Labs contributors to maintainer status (George T and Nischal S) and one from Kaleido (Matthew W). We expect these to pass and the new maintainers to be added in the next quarter! 

# Contributor Diversity

Contributor diversity continues to improve. The noteworthy items are above. 

# Additional Information

None. 

