---
layout: default
title: 2020 Q4 Hyperledger Besu
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Besu

Created by Danno Ferrin, last modified by Arun S M on Apr 29, 2021

# Project Health

Hyperledger Besu remains a strong project with a growing community
network of contributors. This quarter the team has focused on Ethereum
protocol improvements as well as many performance improvements, included
in the Hyperledger Besu 20.10.0 Release, which was launched on November
3rd. The team is currently building towards its Q1 2021 release.

# Questions/Issues for the TSC

There are no issues or questions for this reporting period.

# Releases

Hyperledger Besu has completed six bi-weekly releases, including the
quarterly major release cycle for 20.10.0 (1.5.5 on 23 Jun, 20.10.0-RC1
on 8 Oct, 20.10.0-RC2 on 21 Oct, 20.10.0 on 3 Nov, 20.10.1 on 17 Nov,
20.10.2 on 2 Dec).

Also, Hyperledger Besu transitioned to the CalVer release versioning
taxonomy for our Q4 release.

Some functional improvements include:

**Production-Ready Features:**

-   **Privacy:** The most recent set of privacy enhancements include:

-   -   <a href="https://besu.hyperledger.org/en/stable/Concepts/Privacy/Multi-Tenancy/" class="external-link" rel="nofollow"><span>Multi Tenancy of Privacy
Groups </span></a>

-   **Performance**

-   -   Support for OpenTelemetry as a metrics backend (in addition to
existing Prometheus support)
-   New library updates for secpk256k1 and altBN precompiles,
resulting in 3% to 15% overall performance improvements
depending on the chosen network.
-   EVM tool added to the standard set of distribution binaries.

-   **Standard Tracing APIs** : 

-   -   Added debug\_standardTraceBlockToFile ,
debug\_standardTraceBadBlockToFile , and debug\_getBadBlocks to
support Ethereum Foundation mainnet chain security efforts.

**Early Access Features:**

-   **EIP-1559 Support:** Hyperledger Besu has been one of the clients
leading the implementation of EIP-1559, a major upgrade to
Ethereum’s transaction fee market. This work accelerated this
quarter.
-   **Ephemeral Testnet YOLO:** In preparation for the next network
upgrade, Berlin, an ephemeral testnet called YOLO was launched. 
This network has evolved into YOLOv3 with additional EIPs.

Go to the <a href="https://github.com/hyperledger/besu/releases" class="external-link" rel="nofollow"><span>Changelog </span></a> for
more details.

# Overall Activity in the Past Quarter

There have been some significant maintainer contributions from
decentralized maintainers

-   Ethereum Classic’s Thanos Hard Fork support was contributed by Ed
Mack from Chainsafe Systems
-   OpenTelementry metrics support was contributed by Antoine Tolume
from Splunk.
-   DNS Auto-discovery for Ethereum Mainnet and Testnets, by Antoine
Tolume from Splunk.
-   Next Quarter OpenTracing support is expected to land, also provided
by Antoine Tolume from Splunk.

The remainder of the maintainers have been focusing on continuing
mainnet compatibility work and adding cross-client support for GoQuorum
within the Besu codebase.

# Current Plans

1.  The project team remains currently working towards its 21.2.0
Release, scheduled for February or March of 2021. The 21.2 Release
is expected to include the following features:

2.  1.  Berlin network upgrade (pending Ethereum All Core Devs
scheduling)
2.  Bonsai Tries (slipped from 20.10)
3.  QiBFT a cross-client BFT algorithm specified by the EEA.

3.  Similar to last quarter, Besu is also continuing to engage with its
community and grow the diversity of its maintainer and contributor
base. 

# Maintainer Diversity

Our maintainer diversity remained fairly consistent from the prior
quarter.  We continue to have maintainers from four different
organizations. 

The four organizations include:

-   ConsenSys Quorum (FKA PegaSys)
-   Web3Labs
-   Chainsafe
-   Splunk 

There were no new maintainers added or removed this quarter.

The maintainers breakdown is currently:

-   16% non-ConsenSys (unchanged from last quarter)

# Contributor Diversity

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fbesu/dashboard?time=%7B%22from%22:%222020-09-28T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-08T01:50:27.952Z%22%7D" class="external-link" rel="nofollow"><span>LF Analytics for Besu from 28
Sep 2020 to 7 Dec 2020 </span></a>

Commits from 2020-08-28 to 2020-12-07 : 169

Committers from 2020-08-28 to 2020-12-07 : 20 (5 non-PegaSys)

Identified Orgs  2020-08-28 to 2020-12-07 : 4 + 1 independent

# Additional Information

N/A

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
-   🔲 <span class="placeholder-inline-tasks">
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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41588195"></span>
<p>What is the goal of "adding cross-client support for GoQuorum within
the Besu codebase"? To be able to replace a GoQuorum client with a Besu
client?</p>
<p>Nit: you should delete "The team is also looking forward to
participating at the Hyperledger Member Summit." which is obviously a
leftover from the previous report.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Dec
09, 2020 06:37 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41588232"></span>
<p>That, and to allow for multi-client and multiple-implementation
blockchains like you see in mainnet.  The recent <a href="https://blog.ethereum.org/2016/11/25/security-alert-11242016-consensus-bug-geth-v1-4-19-v1-5-2/" class="external-link" rel="nofollow">mainnet consensus bug</a>  (which
was from two versions of the same client) would have been worse if only
one client ran mainnet, which is why the ethereum foundation keeps
funding multiple clients.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Dec 09, 2020 15:51 </div ></td>
</tr>
</tbody>
</table>




