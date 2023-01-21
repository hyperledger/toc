---
layout: default
title: 2021 Q3 Hyperledger Fabric
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Fabric

Created by David Enyeart, last modified by Gari Singh on Oct 16, 2021

Hyperledger Fabric
<a href="https://github.com/hyperledger/fabric" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric</a>

# Project Health

Hyperledger Fabric continues to mature, as evidenced by the following
observations throughout this report:

-   LTS release available
-   Project developers have been spending a larger percentage of time on
maintenance and support than in the past, given the increasing
number of production deployments and LTS releases.
-   Lower commit velocity on new features in core Fabric, more activity
around extensions in Hyperledger labs
-   Healthy RFC process with reviews in contributor meetings to drive
consensus on new features.

The commit rate and mailing list activity were down compared to the same
period last year. PRs and mailing list questions are generally turned
around quickly.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? Yes
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Not yet</span>

# Questions/Issues for the TSC

None

# Releases

v2.2 is the current LTS releases with patch releases quarterly. v1.4 LTS
went end of support in April 2021. Production users are encouraged to
use v2.2, users who want to try new features are encouraged to use v2.3
and v2.4.0-alpha and provide feedback.

Releases past quarter:

-   v1.4.12 - April 23, 2021
-   v2.2.3 - April 23, 2021
-   v2.3.2 - April 23, 2021
-   v2.4.0-alpha - April 15, 2021

Upcoming releases planned this quarter:

-   v2.2.4
-   v2.3.3
-   v2.4.0-beta

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

The project was busy maintaining the releases and preparing for a
v2.4.0-beta release with the new Fabric Gateway (details below).

Additionally the project has been planning future work through the RFC
process.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow">RFCs merged</a> this quarter:

-   Orderer ledger snapshots

<a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow">RFCs in review</a> this quarter:

-   WASM for smart contracts
-   BFT ordering service
-   Modular crypto service
-   OpenTelemetry

There has also been a significant amount of Fabric activity in
Hyperledger Labs, a few highlights:

-   <a href="https://github.com/hyperledger-labs/fabric-smart-client" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-smart-client</a>
-   <a href="https://github.com/hyperledger-labs/fabric-token-sdk" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-token-sdk</a>
-   <a href="https://github.com/hyperledger-labs/fabric-operations-console" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-operations-console</a>
-   <a href="https://github.com/hyperledger-labs/minifabric" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/minifabric</a>
-   <a href="https://github.com/hyperledger-labs/fabric-opssc" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-opssc</a>
-   <a href="https://github.com/hyperledger-labs/mirbft" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/mirbft</a>

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
to be opened from a client application to multiple </span> <span class="blob-code-inner blob-code-marker">peers across potentially
multiple organizations. The Fabric Gateway is expected to be function
complete for a Q3 v2.4.0-beta release.</span>

<span class="blob-code-inner blob-code-marker">Other work items in plan
or in progress: </span>

-   <span class="blob-code-inner blob-code-marker">A feature to purge
private data stores, which will help solutions meet GDPR
requirements. An RFC is expected so that we can gather additional
feedback from the community. </span>
-   <span class="blob-code-inner blob-code-marker">A feature to unjoin a
peer from a channel. </span>
-   <span class="blob-code-inner blob-code-marker">A more realistic
Node.js SDK sample application demonstrating good practices
(connection management, error handling, timeouts, retries, etc)</span>
-   <span class="blob-code-inner blob-code-marker">Guidance for
kubernetes deployments </span>

<span class="blob-code-inner blob-code-marker">Additional discussion of
Fabric roadmap can be found in <a href="https://wiki.hyperledger.org/download/attachments/41590443/20210623_contributors_meeting.mp4?api=v2" rel="nofollow">this contributor meeting recording</a> . </span>



# Maintainer Diversity

Two maintainers retired this quarter. 5 of 10 maintainers are from IBM.

# Contributor Diversity

Year to year comparison, by commit:

-   Q2 2020 - 1140 commits. 67% from IBM.
-   Q2 2021 - 396 commits. 54% from IBM

Year to year comparison, by contributor:

-   Q2 2020 - 96 contributors. 38% from IBM.
-   Q2 2021 - 77 contributors. 22% from IBM.

# Additional Information

Link to the Fabric dashboard: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222021-04-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-07-01T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">Q2 2021</a>

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-56721679"></span>
<p>One thing to pay attention to is the node sdk's docs and sample
codes.</p>
<p>Currently, in the official doc website of  <a href="https://hyperledger.github.io/fabric-sdk-node" class="external-link" rel="nofollow">https://hyperledger.github.io/fabric-sdk-node</a> , we
can not find a single sample code to run directly.</p>
<p>There're tutorials on some functionalities (e.g.,  <a href="https://hyperledger.github.io/fabric-sdk-node/release-2.2/tutorial-commonconnectionprofile.html" class="external-link" rel="nofollow">https://hyperledger.github.io/fabric-sdk-node/release-2.2/tutorial-commonconnectionprofile.html</a>
), however, all given code is snippet, and cannot run end-to-end (e.g.,
reading local credential, and send request to the network). This will
affect the user experience heavily.</p>
<p>Besides, the issue list of the node sdk's github repo is disabled,
hence no one can report any issue there.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by baohua at Jul
28, 2021 16:36 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-56721785"></span>
<p>Thanks <a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> , the <a href="https://hyperledger.github.io/fabric-sdk-node" class="external-link" rel="nofollow">https://hyperledger.github.io/fabric-sdk-node</a> page
has a Samples section at the bottom that links to the fabric-samples
repository where the client samples can be found. It sounds like you
didn't see this, so please let us know how we can make this link more
clear.</p>
<p>BTW, Fabric is investigating shifting from Jira to GitHub for issue
reporting. We have enabled GitHub issues on Fabric repository as a trial
and will likely roll this out to all repositories and socialize on the
mailing list.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Jul 29, 2021 14:29 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-56721814"></span>
<p>I did check the fabric-samples repo too. There're several code using
sdk-node. I would say it's a little too complicated as a sample.</p>
<p>IMHO, it will be better provide a single and simple sample as a basic
tutorial.</p>
<p>Using github issues is fine, let's enable it soon.</p>
<p>Thanks!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at Jul
29, 2021 17:27 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-56721924"></span>
<p>Ok, I've opened a PR against fabric-sdk-node to update the samples
doc reference to be Asset Transfer in fabric-samples - <a href="https://github.com/hyperledger/fabric-samples/#asset-transfer-samples-and-tutorials" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric-samples/#asset-transfer-samples-and-tutorials</a></p>
<p>If you look at those samples, you'll see there are beginner samples
starting with Basic asset transfer that has a corresponding tutorial
that is meant as the single and simple starting point for newbies - <a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow">https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html</a></p>
<p>The Fabric docs also point to this as the starting point.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Jul 30, 2021 22:41 </div ></td>
</tr>
</tbody>
</table>




