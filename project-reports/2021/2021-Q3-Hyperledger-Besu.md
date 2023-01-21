---
layout: default
title: 2021 Q3 Hyperledger Besu
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Besu

Created by Grace Hartley, last modified by Arnaud J Le Hors on Nov 11, 2021

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Besu remains a strong
project with a growing community network of contributors. This quarter
the team has focused on Ethereum protocol improvements, including
EIP-1559, which went live on August 5th, as well as many performance
improvements, included in the Hyperledger Besu 21.10.0 Release, which
will be launched on October 26th.  </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes, this
is complete. </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?  <span style="color: rgb(23,43,77);">Yes, via GitHub actions </span></span>

# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">None, at this time. DCO sign off
remains a challenge, but we are aware that this request is being
considered by Linux Foundation's Legal team. </span>

# Releases

<span style="color: rgb(23,43,77);">Hyperledger Besu has completed five
releases. We are currently preparing for the 21.10.0 Quarterly Release.</span>

-   <span style="color: rgb(0,0,0);">21.7.0 RC 1 - 2021 Jun 15 </span>
-   <span style="color: rgb(0,0,0);">21.7.0 RC 2 - 2021 June 22 </span>
-   <span style="color: rgb(0,0,0);">21.7.0 (full release) - 2021 Jul 6</span>
-   <span style="color: rgb(0,0,0);">21.7.1 - 2021 Jul 14 </span>
-   <span style="color: rgb(0,0,0);">21.7.2 - 2021 Aug 4 </span>
-   <span style="color: rgb(0,0,0);">21.7.3 - 2021 Sep 2 </span>
-   <span style="color: rgb(0,0,0);">21.7.4 - 2021 Sep 16 </span>

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">Functional improvements included in these
releases: </span> </span>

**<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">London Hard Fork - Launched on August 5th</span> </span>**

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">The team has been preparing Hyperledger
Besu to be compatible with the next Ethereum hard fork, London. The
London Hard Fork included:  </span> </span>

-   <a href="https://eips.ethereum.org/EIPS/eip-1559" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-1559: Fee market
change for ETH 1.0 chain</a>
-   <a href="https://eips.ethereum.org/EIPS/eip-3198" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-3198: BASEFEE
opcode</a>
-   <a href="https://eips.ethereum.org/EIPS/eip-3529" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-3529: Reduction in
refunds</a>
-   <a href="https://eips.ethereum.org/EIPS/eip-3541" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-3541: Reject new
contracts starting with the 0xEF byte</a>
-   <a href="https://eips.ethereum.org/EIPS/eip-3554" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-3554: Difficulty Bomb
Delay to December 1st 2021</a>

**EthStats Support**

Previously, we launched EthStats support as an experimental feature. We
are pleased to share that it is now a stable feature generally available
for use within Hyperledger Besu. EthStats provides insight into network
health by displaying real time and historical statistics about the
network and nodes on public mainnets, testnets and permissioned
networks.

**QBFT: The New Byzantine Fault Tolerant Consensus Algorithm**

The team has released QBFT, a Byzantine Fault Tolerant consensus
algorithm, building on the capabilities of IBFT and IBFT 2.0. In
addition to the benefits of earlier BFT consensus mechanisms, such as
stability and reliability, QBFT aims to provide performance improvements
in cases of excess round change. QBFT is interoperable between the
GoQuorum Ethereum client and Hyperledger Besu and supports networks with
both GoQuorum and Hyperledger Besu nodes.

# Overall Activity in the Past Quarter

<span style="color: rgb(23,43,77);">Many of the maintainers have been
focusing on continuing mainnet compatibility work and adding
cross-client support for GoQuorum within the Besu codebase.
Specifically, the team was dedicated towards the London Hard Fork.
Significant contributions have come from Hedera Hashgraph, who are
working on integrating the Besu EVM into future releases of Hedera's
network. Hedera's focus is on performance and utility. </span>

# Current Plans

1.   **21.10.0 Release:** The project team remains currently working
towards its 21.10.0 Release, scheduled for October 2021. The 21.10.0
Release is expected to include the following features:
1.  Performance improvements to prepare for the Merge
2.  Optimistic Besu: The team will be exploring different options
for supporting use of the Besu EVM for Optimistic Rollups
3.  Permissioning features will be extended to include more granular
account permissioning for different transaction and interaction
types.
4.  EVM Library: the core EVM component will be separated as a stand
alone library, suitable for use outside of an integrated mainnet
client.
2.   **Eth 1 to Eth 2 Merge:** Some of the Besu team is participating in
a Eth1 and Eth2 contributor meet-up the week of October 2nd to
discuss in detail the plans for the Eth 1 to Eth2 Merge, which moves
Ethereum from Proof of Work to Proof of Stake. We anticipate this
body of work to take up a significant amount of the team's time in
the coming months.
3.   **Grace Hopper Open Source Day:** The Besu project is participating
in the Grace Hopper Open Source Day and we are excited to share our
project with new joiners there.
4.   **Community Engagement:** Similar previous quarters, Besu is also
continuing to engage with its community and grow the diversity and
decentralization of its maintainer and contributor base. We have
added about 15 new good first issues so we encourage the community
to give them a try.

# Maintainer Diversity

There four organizations who are maintainers include:

-   ConsenSys Quorum (FKA PegaSys)
-   Chainsafe
-   Hedera Hashgraph
-   Splunk 

The maintainers breakdown is:

-   16% non-ConsenSys (4 of 25) - This is a slight improvement from
prior quarters.

# Contributor Diversity

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fbesu/dashboard;subTab=technical?time=%7B%22from%22:%222021-06-21T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-09-22T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">LF Analytics from June 22nd to
September 22nd</a>

Commits from  2021-06-22 to 2021-09-22 : 215

Committers from 2021-06-22 to 2021-09-22: 28  (9 non-ConsenSys)

Identified Orgs  2021-03-23 to 2021-06-21:  4

# Badging

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Attachments:

[QBFT Presentation for the EEA.pdf](attachments/58856594.pdf)

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-58856392"></span>
<p>Maybe this isn't appropriate for a TSC review question, but I'm
curious so I'll ask anyway:  is there any kind of formal write-up or
paper on your QBFT protocol?  I did some light googling and couldn't
find anything.  Thanks!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Sep
30, 2021 06:49 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-58856595"></span>
<p>No problem! Here is a presentation made to the Enterprise Ethereum
Alliance outlining the changes  <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a> . The
only formal white paper is about IBFT 1 and IBFT 2. QBFT is the next
iteration of IBFT 2.  [QBFT Presentation for the EEA.pdf](attachments/58856594.pdf)
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by grace.hartley at Oct 01, 2021 20:32 </div ></td>
</tr>
</tbody>
</table>


