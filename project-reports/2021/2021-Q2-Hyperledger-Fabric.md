---
layout: default
title: 2021 Q2 Hyperledger Fabric
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Fabric

Created by David Enyeart, last modified by Angelo De Caro on Apr 29, 2021

<span style="letter-spacing: 0.0px;"> Hyperledger Fabric
<a href="https://github.com/hyperledger/fabric" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric</a></span>

# Project Health

Hyperledger Fabric continues to mature, as evidenced by the following
observations throughout this report:

-   Two LTS releases available
-   Project developers have been spending a larger percentage of time on
maintenance and support than in the past, given the increasing
number of production deployments and two LTS releases.
-   Lower commit velocity on new features.
-   Healthy RFC process with reviews in contributor meetings to drive
consensus on new features.

The commit rate and mailing list activity were down compared to the same
period last year. PRs and mailing list questions are generally turned
around quickly.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? I believe the
decision was to point to a repolinter.json outside the repo, is
there finalized guidance?</span>

# Questions/Issues for the TSC

Is there finalized guidance for pointing to an external repolinter.json
in CI?

# Releases

v1.4 and v2.2 are the current LTS releases. Each has patch releases
quarterly. v1.4 LTS end of support is April 2021. Production users are
encouraged to upgrade to v2.2 as soon as possible.

Releases this quarter:

-   v1.4.10 - January 27, 2021
-   v1.4.11 - March 2, 2021
-   v2.2.2 - January 27, 2021
-   v2.3.1 - February 3, 2021

Upcoming releases planned for April 2021:

-   v1.4.12
-   v2.2.3
-   v2.3.2
-   v2.4.0-alpha

v2.3 added two major features which are seeing encouraging adoption in
the community:

-   Ledger snapshot enables a peer to take a snapshot of its state. This
allows new peers to join a channel from an agreed upon snapshot,
reducing the time to join a channel and the storage size required to
maintain a ledger. In the future it will also be possible to
prune/archive old blocks to bring the same benefit to existing
peers.
-   The channel participation management feature improves the privacy
and scalability of the ordering service since a global 'system
channel' will no longer be needed for the creation and management of
channels.

# Overall Activity in the Past Quarter

The project was busy maintaining the two LTS releases and preparing for
a v2.4.0-alpha release with the new Fabric Gateway (details below).

Additionally the project has been planning future work through the RFC
process.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow">RFCs merged</a> this quarter:

-   Fabric private chaincode (SGX) - an existing Hyperledger lab th"at could now be turned into a Fabric subproject given the merged RFC.

<a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow">RFCs in review</a> this quarter:

-   WASM for smart contracts
-   BFT ordering service
-   Modular crypto service
-   OpenTelemetry
-   Orderer ledger snapshots

# Current Plans

<span class="blob-code-inner blob-code-marker">The largest item being
worked in 2021 is the </span> <span class="blob-code-inner blob-code-marker">Fabric Gateway, a new component
that will implement much of the high-level 'gateway' programming model.
This will remove much of the transaction submission and query logic from
the client application and shift it to a common gateway running within
the Fabric peer, enabling each of the various client SDKs to be slimmer,
more consistent, and require less maintenance. It will also simplify the
administrative overhead of running a Fabric network because client
applications will be able to connect and submit transactions via a
single network port rather than the current situation where ports have
to be opened from a client application to multiple peers across
potentially multiple organizations. </span>

# Maintainer Diversity

One maintainer retired this quarter. 8 of 12 maintainers are from IBM
(two maintainers shifted from IBM to other companies this quarter).

# Contributor Diversity

Year to year comparison, by commit:

-   Q1 2020 - 1100 commits. 77% from IBM.
-   Q1 2021 - 692 commits. 76% from IBM

Year to year comparison, by contributor:

-   Q1 2020 - 88 contributors. 53% from IBM.
-   Q1 2021 - 70 contributors. 40% from IBM.

Documentation translation was a driver in the increased contributor
diversity.

# Additional Information

Link to the Fabric dashboard: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard?time=%7B%22from%22:%222021-01-01T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-03-31T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">Q1 2021</a>

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-50136104"></span>
<p>Thanks, Dave!  Good writeup</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mastersingh24
at Apr 15, 2021 08:54 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-50136111"></span>
<p>The answer to the question on repolinter is: no. There is an effort
to develop a common repolinter config file underway but no final
decision on whether what projects can do (i.e., use their own variations
or stick with the common one).</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Apr
15, 2021 09:28 </div ></td>
</tr>
</tbody>
</table>




