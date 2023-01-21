---
layout: default
title: 2021 Q4 Hyperledger Fabric
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Fabric

Created by David Enyeart, last modified by Bobbi Muscara on Nov 04, 2021

Hyperledger Fabric
<a href="https://github.com/hyperledger/fabric" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric</a>

# Project Health

Hyperledger Fabric has stabilized with an LTS release process and
incremental new features being added in minor releases. There is less
churn and fewer commits than in years past, with continued focus on
quality and support. New features get proposed, approved, and
implemented based on a community RFC process. Mailing list activity is
down compared to prior years. PRs and mailing list questions are
generally turned around quickly.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? Yes
2.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span>? Yes.</span>

# Questions/Issues for the TSC

None

# Releases

v2.2 is the current LTS releases with patch releases quarterly.

Releases past quarter:

-   v2.2.4 - September 8, 2021
-   v2.3.3 - September 8, 2021
-   v2.4.0-beta - August 12, 2021

Upcoming releases planned this quarter:

-   v2.4.0

# Overall Activity in the Past Quarter

The project delivered v2.4.0-beta with two significant new features:

-   **Fabric Gateway** - <span class="blob-code-inner blob-code-marker">The Fabric Gateway will
remove much of the transaction submission and query logic from the
client application and shift it to a common gateway running within
the Fabric peer, enabling each of the various client SDKs to be
slimmer, more consistent, and require less maintenance. Applications
will interact with a trusted peer (e.g. at their organization) and
the peer will coordinate endorsements from other peers and
submission to the ordering service. It will also simplify the
administrative overhead of running a Fabric network because client
applications will be able to connect and submit transactions via a
single network port at their organization rather than the current
situation where ports have to be opened from a client application to
multiple </span> <span class="blob-code-inner blob-code-marker">peers across potentially
multiple organizations. </span>The Fabric Gateway is delivered along
with slim SDKs in the
<a href="https://github.com/hyperledger/fabric-gateway" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric-gateway</a>
repository. Check out the <a href="https://github.com/hyperledger/fabric-gateway/tree/main/samples" class="external-link" rel="nofollow">client application samples</a>
.
-   **Peer unjoin** - The new command "peer node unjoin" enables an
administrator to remove (unjoin) a channel from a peer.
The peer must be stopped when the command is executed so th"at channel artifacts can be cleaned up.
The channel's blockchain, state database, and associated entries
will be removed from the peer.
When the peer is restarted it will no longer receive blocks for the
channel.

Additionally the project has been planning future work through the RFC
process.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow">RFCs merged</a> this quarter:

-   OpenTelemetry (implementation has started across Fabric, SDKs, and
chaincodes to enable tracing across the components).

New <a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow">RFCs in review</a> this quarter:

-   Private Data Purge

A survey was completed to gauge interest in future enhancements. The top
candidates were identified as 1) BFT support 2) Pruning of old blocks 3)
Performance improvements. Each of these items are on the Fabric roadmap.
Specifically in the area of BFT options, the
<a href="https://github.com/hyperledger/fabric-rfcs/pull/33" class="external-link" rel="nofollow">SmartBFT RFC</a> has been revived
and progress is being made on the
<a href="https://github.com/hyperledger-labs/mirbft" class="external-link" rel="nofollow">MirBFT Hyperledger lab</a> .

There has also been a significant amount of Fabric activity in
Hyperledger Labs, a few highlights:

-   <a href="https://github.com/hyperledger-labs/fabric-smart-client" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-smart-client</a>
-   <a href="https://github.com/hyperledger-labs/fabric-token-sdk" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-token-sdk</a>
-   <a href="https://github.com/hyperledger-labs/fabric-operations-console" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-operations-console</a>
-   <a href="https://github.com/hyperledger-labs/minifabric" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/minifabric</a>
-   <a href="https://github.com/hyperledger-labs/fabric-opssc" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-opssc</a>
-   <a href="https://github.com/hyperledger-labs/mirbft" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/mirbft</a>

# Current Plans

<span class="blob-code-inner blob-code-marker">The project is working
towards a final v2.4.0 release in Q4 with the Fabric Gateway as the
primary new feature. </span>

<span class="blob-code-inner blob-code-marker">Other work items in plan
or in progress: </span>

-   <span class="blob-code-inner blob-code-marker">A feature to purge
private data stores, which will help solutions meet GDPR
requirements.
<a href="https://github.com/hyperledger/fabric-rfcs/pull/46" class="external-link" rel="nofollow">RFC available for review</a>
.</span>
-   <span class="blob-code-inner blob-code-marker">A more realistic
Node.js SDK sample application demonstrating good practices
(connection management, error handling, timeouts, retries, etc)</span>
-   <span class="blob-code-inner blob-code-marker">Guidance for
kubernetes deployments and announcement of a Fabric Kubernetes
working group. For more information see the contributor meeting from
<a href="https://wiki.hyperledger.org/download/attachments/41590443/20211013_contributors_meeting.mp4?api=v2" rel="nofollow">October 13th</a> .</span>

# Maintainer Diversity

One new maintainer was added this quarter. 6 of 11 maintainers are from
IBM.

# Contributor Diversity

Year to year comparison, by commit:

-   Q3 2020 - 990 commits. 69% from IBM.
-   Q3 2021 - 411 commits. 59% from IBM

Year to year comparison, by contributor:

-   Q3 2020 - 130 contributors. 27% from IBM.
-   Q3 2021 - 87 contributors. 28% from IBM.

# Additional Information

Link to the Fabric dashboard: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-10-01T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">Q3 2021</a>

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks"> <a href="https://wiki.hyperledger.org/display/~Peter Somogyvari" class="confluence-userlink user-mention" data-username="Peter Somogyvari" data-linked-resource-id="31202399" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
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
<td><span id="comment-58859659"></span>
<p>There is a new template that asks the following question for #2 " <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);"> <a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?" It seems that the
answer to this is yes, but could you confirm? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Oct
25, 2021 15:23 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-58859925"></span>
<p>That is correct. We need to make sure we pick up the new template
next quarter.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Oct
26, 2021 19:23 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-58860196"></span>
<p>I made the edit in this report... and the answer is Yes!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Oct 28, 2021 13:30 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62228414"></span>
<p><span style="color: rgb(23,43,77);">Can we have details on the Fabric
Kubernetes working group and share &amp; encourage the community to get
involved? I tried to find in Rocket chat , mailing list but did not find
any details. We should share this working group details to fabric
mailing list and rocket chat. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by knagware9 at Nov 16, 2021 15:56 </div ></td>
</tr>
</tbody>
</table>




