---
layout: default
title: 2023 Q4 Hyperledger Besu
parent: 2023
grand_parent: Project Updates
---

# Project Health

Hyperledger Besu continues its momentum for usage on public and private Ethereum and Ethereum-like networks. We now have more accurate views of Besu's Mainnet usage ([here](https://etherclients.com/) and [here](https://www.ethernets.io/?synced=yes)). Besu is also seeing adoption on Layer 2 networks like Linea and the OP Stack for Optimism. We have one new Maintainer from Kaleido and hope to add more from Web3Labs. This quarter we saw improvements to Tracing / EVM performance and a new transaction pool implementation shipped. The client saw a number of bug fixes as a priority. The modularity work did not progress as much as intended...  Discord activity remains heavy, with a relatively even split between public and private network questions and suggestions. This quarter we added an enterprise-focused discord channel.  


# Questions/Issues for the TOC

How is the TOC planning to allocate resources for developer outreach and education that is not unduly burdensome on maintainers? 

# Releases

[Releases](https://github.com/hyperledger/besu/releases) this quarter:

- 23.10.0
- 23.10.1
- 23.10.2

# Overall Activity in the Past Quarter

Discord remains an awesome community tool for Besu. We are seeing heavy engagement and users helping users. The new split between enterprise and public nets has helped direct feature requests, support, and discussions to the right locations. This means we are losing less and less conversation in the flood of info. We have seen a lot of activity this quarter around improvements to IBFT/QBFT networks and getting Besu ready for L2 networks (also via open-sourced plug-ins, using the Besu plug-in API). As we support more networks, the modularity discussion needs to take a more prominent position in Q1 to avoid incurring tech debt. This could take the form of an expansion to the plug-in APIs or more decoupling within the code-base. 
We continue to see asks around certifications and tutorials for development using Besu. Some tutorials around the plug-in system may be helpful in courting new developers to Besu. 
We had a handful of security reports this quarter that were appropriately mitigated and released to users. 

# Current Plans

Right now, Besu is preparing to ship the Cancun fork. Scoping discussions have also begun around Prague fork scope among Besu Maintainers. There are also plans from Maintainers on an enterprise-focused roadmap to be included alongside the existing one in the wiki. This contains several improvements and features targeting existing private networks. How we package and ship the client will be of interest in the coming quarters (including networks like Mainnet, Linea and private nets). The Besu team is also working toward participating in the Verkle trie migration on Mainnet, shipping a new Archive mode, updating the sync pipelines to be forward compatible with Verkle, among other improvements to performance of the client. 

# Maintainer Diversity

We have one new Maintainer from Kaleido and are actively working to add two more from Web3Labs.

# Contributor Diversity

We are seeing a handful of contributors handle small, existing bugs that are impacting their deployments. These have ranged from logging / consistency fixes, to more detailed like RPC accuracy and functionality. We hope to continue to cultivate these contributors.  

# Additional Information

None 
