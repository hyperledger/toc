---
layout: default
title: 2021 Q2 Hyperledger Besu
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Besu

Created by Grace Hartley, last modified by Gari Singh on Oct 16, 2021

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Besu remains a strong
project with a growing community network of contributors. This quarter
the team has focused on Ethereum protocol improvements as well as many
performance improvements, included in the Hyperledger Besu 21.7.0
Release, which will be launched on July 6th.  </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? No, this was not completed with final Berlin
mainnet activation as originally planned. It is was deprioritized to
be completed after the London Hard fork (scheduled for mid-July)
because of unknown downstream impacts.
<a href="https://github.com/hyperledger/besu/issues/2035" class="external-link" rel="nofollow">Issue is here</a> .
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes, via
GitHub actions. </span>

<span style="font-size: 24.0px;letter-spacing: -0.01em;">Questions/Issues for
the TSC </span>

None, at this time. DCO sign off remains a challenge, but we are aware
that this request is being considered by Linux Foundation's Legal team.

# Releases

<span style="color: rgb(23,43,77);">Hyperledger Besu has completed six
releases. We are currently preparing for the 21.7.0 Quarterly Release.</span>

-   <span style="color: rgb(0,0,0);">21.1.3 - 2021 Mar 23 </span>
-   <span style="color: rgb(0,0,0);">21.1.4 - 2021 Apr 8 </span>
-   <span style="color: rgb(0,0,0);">21.1.5 - 2021 Apr 21 </span>
-   <span style="color: rgb(0,0,0);">21.1.6 - 2021 May 19 </span>
-   <span style="color: rgb(0,0,0);">21.1.7 - 2021 Jun 1 </span>
-   <span class="placeholder-inline-tasks" style="color: rgb(0,0,0);">21.7.0-RC1 - 2021 Jun 15 </span>

<span class="placeholder-inline-tasks" style="color: rgb(0,0,0);">Functional improvements in these releases
include: </span>

**<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">Berlin Network Upgrade - Released </span></span>**

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">The team completed work to ensure
Hyperledger Besu was compatible with the Ethereum hard fork, Berlin,
which occurred on April 15th. The   </span> <a href="https://blog.ethereum.org/2021/03/08/ethereum-berlin-upgrade-announcement/" class="external-link" rel="nofollow" style="text-decoration: none;">Berlin Network upgrade</a>  included
<span style="color: rgb(76,76,76);"> several improvements to the
Ethereum mainnet, such as the addition of subroutines to the EVM, the
introduction of “transaction envelopes”; which make it easier for
Ethereum to support several different kinds of transactions, and changes
in gas costs to increase the security of the network. </span> </span>

**<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">London Hard Fork - Scheduled for July 14th</span> </span>**

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">The team has been preparing Hyperledger
Besu to be compatible with the next Ethereum hard fork, London. The
London Hard Fork includes:  </span> </span>

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

**Besu on Tessera**

Besu is now compatible with and can be run with Tessera, the Apache 2.0
licensed private transaction manager written in Java. If you have
previously used Orion as a privacy transaction manager of choice, it
will be deprecated in November 2021. Tessera is a drop in replacement
for Orion.



<span style="font-size: 24.0px;letter-spacing: -0.01em;">Overall
Activity in the Past Quarter </span>

<span style="color: rgb(23,43,77);">Many of the maintainers have been
focusing on continuing mainnet compatibility work and adding
cross-client support for GoQuorum within the Besu codebase. </span>

# Current Plans

1.  The project team remains currently working towards its 21.7.0
Release, scheduled for July of 2021. The 21.7 Release is expected to
include the following features:

2.  1.  London network upgrade
2.  EIP-1559
3.  Besu working with Tessera

3.  Similar to last quarter, Besu is also continuing to engage with its
community and grow the diversity and decentralization of its
maintainer and contributor base. 

# Maintainer Diversity

Our maintainer decentralization had a small decrease from the prior
quarter. 

The three organizations include:

-   ConsenSys Quorum (FKA PegaSys)
-   Chainsafe
-   Splunk 

We completed moving 3 maintainers to emeritus status and we added 4
(Vijay Michalik, Sajida Zouarhi, Gary Schulte, and Alexandra Tran) new
maintainers from ConsenSys. We also updated our
<a href="https://github.com/hyperledger/besu/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow">maintainer definition</a> to allow
for non-code contributors. Because we expanded the definition of
maintainers, which we think is valuable for our community, we have seen
a slight decrease in the maintainer diversity of the organizations.

The maintainers breakdown is:

-   13% non-ConsenSys (3 of 23) - a decrease of 6% from last quarter. 

# Contributor Diversity

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fbesu/dashboard;subTab=technical?time=%7B%22from%22:%222021-03-23T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-06-21T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">LF Analytics from March 23 to June
21st</a>

Commits from  2021-03-23 to 2021-06-21 : 253

Committers from 2021-03-23 to 2021-06-21: 33  (13 non-ConsenSys)

Identified Orgs  2021-03-23 to 2021-06-21:  5

# Badging

Hyperledger Besu is testing out the badging process.
<a href="https://wiki.hyperledger.org/display/BESU/Project+Badge+Status" rel="nofollow">Here is a link</a> of its current statuses for each of
the badges.

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>






