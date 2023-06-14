---
layout: default
title: 2023 Q2 Hyperledger Sawtooth
parent: 2023
grand_parent: Project Updates
---

# Project Health

Sawtooth is going through a transition from Transact being separated and the idea that Sawtooth 2.0 would use https://github.com/Cargill/splinter . The last two monthly calls have looked at merging Transact and some of the libraries Bitwise and Blockchain TP created with the current 1.3.x branch and renaming it "main".  That would allow the 1.x branch to continue as several companies are using it exclusively for their clients(including Taekion & BlockchainTP)as well as not be dependent on a non-Hyperledger project - Splinter. The advantage is having a blockchain that can easily using different consensus mechanisms easily for different workload situations. 

New contributors have offered to step in a help rebuild the continuous test mode to make it easier to work with and faster.

# Questions/Issues for the TOC

None at this time
 
# Releases

There have been no releases since the last report, but the merged main will be a much improved release.

# Overall Activity in the Past Quarter

The number of posts in Discord has been rising and answers have been answered in a regular fashion.  We have made answering question on Discord and email to be answered in a faster fashion.

# Current Plans

The plans right now have three main objectives:

* Merge the current release 1.2 with Transact and other patches maintained outside of Sawtooth to a new core release.
* Overhaul the continuous testing Infrastrucure
* continue to replace Python code with RUST

# Maintainer Diversity

Maintainers are distributed across Bitwise IO, Cargill, Intel, and Walmart Labs.  Taekion and BlockchainTP will be added in Q3

# Contributor Diversity

Commits from 2023-1-23 to 2023-03-31 : 18
Committers from 2023-1-23 to 2023-03-318 : 3
Domains from 2023-1-23 to 2023-03-31 : 2

# Additional Information

The project is on a reboot to the 1.x branch to make it more accessible to a wider audience. Several companies have integrated the 1.x version of Sawtooth into their commercial product. Other companies will be contributing code to Hyperledger to improve the Sawtooth functionality.  One project - Taekion - will contribute an integrated Hedera Consensus Service into Sawtooth giving Sawtooth a Public consensus on a private chain seamlessly in the Sawtooth project.
