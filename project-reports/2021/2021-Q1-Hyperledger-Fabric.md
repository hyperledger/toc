---
layout: default
title: 2021 Q1 Hyperledger Fabric
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Fabric

Created by David Enyeart, last modified by Danno Ferrin on Feb 18, 2021

# Project

Hyperledger Fabric
<a href="https://github.com/hyperledger/fabric" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric</a>

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

The project would benefit from increased maintainer diversity.

# Questions/Issues for the TSC

None.

# Releases

v1.4 and v2.2 are the current LTS releases. Each has patch releases
quarterly. v1.4 LTS release is scheduled for end of support in April
2021. Production users are encouraged to upgrade to v2.2 as soon as
possible.

Releases this quarter:

-   v1.4.10 - January 27, 2021
-   v2.2.2 - January 27, 2021
-   v2.3.0 - November 18, 2020

v2.3.0 added two major features:

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

The project was busy maintaining the two LTS releases and releasing a
new minor release.

In addition to the releases, the project completed an overhaul of the
documentation <a href="https://hyperledger-fabric.readthedocs.io/en/latest/deployment_guide_overview.html" class="external-link" rel="nofollow">deployment guides</a> , <a href="https://hyperledger-fabric.readthedocs.io/en/latest/tutorials.html" class="external-link" rel="nofollow">tutorials</a> , and related <a href="https://github.com/hyperledger/fabric-samples/blob/master/README.md" class="external-link" rel="nofollow">samples</a> in 2020.

Additionally the project has been planning future work through the RFC
process.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow">RFCs merged</a> this quarter:

-   Fabric website proposal for <span class="blob-code-inner blob-code-marker">
<a href="https://fabric.hyperledger.org" class="external-link" rel="nofollow">https://fabric.hyperledger.org</a> as a "front door" to the project, similar to what other projects have done (e.g. 
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow">https://sawtooth.hyperledger.org/</a> ) </span>
-   Fabric gateway component (see Current Plans for details)

<a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow">RFCs in review</a> this quarter:

-   WASM for smart contracts
-   Fabric private chaincode (SGX)
-   BFT ordering service
-   Modular crypto service
-   OpenTelemetry

In active development:

-   Fabric Gateway

# Current Plans

<span class="blob-code-inner blob-code-marker">The largest item being
worked in 2021 is the </span> <span class="blob-code-inner blob-code-marker">Fabric Gateway, a new component
that will implement much of the high-level 'gateway' programming model.
This will remove much of the transaction submission and query logic from
the client application and shift it to a common gateway (likely running
within a client's peer), enabling each of the various client SDKs to be
slimmer, more consistent, and require less maintenance. It will also
simplify the administrative overhead of running a Fabric network because
client applications will be able to connect and submit transactions via
a single network port rather than the current situation where ports have
to be opened to multiple peers across potentially multiple
organizations. </span>

# Maintainer Diversity

No maintainer changes for core Fabric project (11 of 13 from IBM).

# Contributor Diversity

Year to year comparison, by commit:

-   Q4 2019 - 1030 commits. 77% from IBM.
-   Q4 2020 - 579 commits. 78% from IBM

Year to year comparison, by contributor:

-   Q4 2019 - 90 contributors. 52% from IBM.
-   Q4 2020 - 79 contributors. 40% from IBM.

Documentation translation was a driver in the increased contributor
diversity.

# Additional Information

Link to the Fabric dashboard: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard?time=%7B%22from%22:%222020-09-30T22:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-30T23:00:00.000Z%22%7D" class="external-link" rel="nofollow">last quarter</a>

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



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41591405"></span>
<p>Should this be 2020 instead?</p>
<ul class="incremental">
<li>v2.3.0 - November 18, 2021</li>
</ul>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Jan 28, 2021 04:53 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41591408"></span>
<p>yep, updated!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Jan 28, 2021 06:25 </div ></td>
</tr>
</tbody>
</table>




