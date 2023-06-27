---
layout: default
title: Q2 Hyperledger Besu
parent: 2023
grand_parent: Project Updates
---

# Project Health

Hyperledger Besu is gaining more and more traction across public and private Ethereum and Ethereum-like networks. There is an uptick in contributions on the private network side with new contributors from Web3Labs and Kaleido moving towards maintainer status. The Besu strategy in the coming quarters is looking to be driven by more than just Consensys, with a focus on tech debt resolution that will simplify maintaining a Swiss-army knife client across many network types. These are also means for the current maintainers to engage new developers on the code-base and improve contributor skill, quality, and number. Discord activity remains heavy, with a relatively even split between public and private network questions and suggestions. The project is seeing some key contributors step away to focus on other areas, but we hope to fill the gap with new ones and leverage some of their knowledge in upskilling.

# Questions/Issues for the TOC

Have we been able to complete the asks around CircleCI funding by Hyperledger Foundation?

# Releases

There were only three Besu releases this quarter, two point releases with fixes and a huge quarterly with a number of new changes. We expect another rather large quarterly in July with a huge amount of features focused on performance, fixes, and tech debt. We are also using these quarterlies to deprecate older features relating to Quorum, which is no longer being maintained by Consensys. 

[Releases](https://github.com/hyperledger/besu/releases) this quarter: 
- 23.1.4
- 23.4.0 Quarterly
- 23.4.1 

# Overall Activity in the Past Quarter

Chat channels are very active in Discord. Users are eager to engage typically in two fashions: 
- Seeking support around Staking
- Seeking support in standing up private networks

We have also seen an uptick in interest around Besu as a research client for Ethereum Mainnet with new folks engaging in #besu-contributors channel.

Maintainers are quite active in engaging user questions and they often get what they need or we walk them through debugging with us so maintainers can make client improvements. We are also seeing an uptick in users helping users, which bolsters the community. The TOC may want to consider a way to track or reward these Discord "power users."

The project is working towards updating our modular code base in a way that actually uses modularity as opposed to a monolith with expanding scope. There is desire to set up a working group around abstracting consensus mechanisms in Besu which should greatly help private networks take new versions of Besu into production. This should also alleviate unintended side-effects of bugs or upstream changes on the rapidly evolving Mainnet from impacting long-standing networks. Multiple contributor groups are rallying around this goal. There is also activity around Besu as a part of the rollup ecosystem which is gradually evolving. Consensys has shared some roadmap items on 2nd Half but is actively soliciting feedback from other groups on project direction. 

# Current Plans

Current plans involve removing technical debt in the code-base, improving baseline performance, removing bugs, and modularizing the client with plug-ins. This sounds like a lot/lofty goals, but as more networks are stood up using Besu, resiliency, performance, and debt need to be addresses. Consensus mechanism modularity will hugely simplify the client but require a lot of work and must be balanced against other priorities. 

Rollups are also a big driver of the next iteration of the Besu client. The plug-in system gives Besu a unique position to address rollup client diversity and ingrain itself into valuable tech stacks. The plug-ins need better documentation and some love, starting with existing rollups use-cases. 

# Maintainer Diversity

No maintainers added, yet. We have new, active contributors moving closer to maintainer status. 

# Contributor Diversity

New contributors from Kaleido and Web3Labs continue to be active. We are also seeing the Ethereum Foundation funnel contributors toward Besu via grants and fellowship opportunities. These usually end up in EIP prototypes / designs and potentially new contributors down the line. 

We did lose Ethereum Classic contributors from the code base this quarter as they move to focus on CoreGeth. 

# Additional Information

None.
