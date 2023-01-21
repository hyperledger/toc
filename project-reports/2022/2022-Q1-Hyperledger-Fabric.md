---
layout: default
title: 2022 Q1 Hyperledger Fabric
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Fabric

Created by David Enyeart, last modified by Jim Zhang on Mar 10, 2022

<span style="letter-spacing: 0.0px;"> Hyperledger Fabric
<a href="https://github.com/hyperledger/fabric" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric</a></span>

# Project Health

Hyperledger Fabric is fairly mature and stable with a Long-term support
(LTS) release and incremental new features being added in minor
releases. There is less churn and fewer commits than in years past, with
continued focus on quality and support. New features get proposed,
approved, and implemented based on a community RFC process. Mailing list
activity is down compared to prior years. PRs and mailing list questions
are generally turned around quickly.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes</span>

# Questions/Issues for the TSC

None.

# Releases

v2.2 is the current LTS releases with patch releases approximately
quarterly.

Releases past quarter:

-   v2.2.4 - September 8, 2021
-   v2.3.3 - September 8, 2021
-   v2.4.0 - November 29, 2021
-   v2.4.1 - December 17, 2021

Additionally, SDKs are regularly patched, most notably Java SDK v2.2.11
to update log4j and address the log4j December vulnerability.

Upcoming releases:

-   v2.2.5 - Update to Go 1.17
-   v2.4.2 - Update to Go 1.17
-   v2.5.0 - Expected to be next LTS release



# Overall Activity in the Past Quarter

The project delivered v2.4.0 with two significant new features:

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
repository.
-   **Peer unjoin** - The new command "peer node unjoin" enables an
administrator to remove (unjoin) a channel from a peer.
The peer must be stopped when the command is executed so th"at channel artifacts can be cleaned up.
The channel's blockchain, state database, and associated entries
will be removed from the peer.
When the peer is restarted it will no longer receive blocks for the
channel.

v2.4.1 also added an external builder for 'chaincode as a service' to
the fabric-peer docker image that makes deployment to Kubernetes
environments simpler.

For more details on v2.4 see the <a href="https://hyperledger-fabric.readthedocs.io/en/latest/whatsnew.html#what-s-new-in-hyperledger-fabric-v2-4" class="external-link" rel="nofollow">What's New documentation</a> .

Additionally the project has been planning future work through the RFC
process.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow">RFCs merged</a> this quarter:

-   Purge Private Data

Other <a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow">RFCs are in review</a> with recent
discussions surrounding SmartBFT, OpenTelemetry tracing, and module
crypto service.

Finally, new project samples have been added to help users get up to
speed and deploy Fabric:

-   Asset transfer samples with new Gateway SDK - <a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow">https</a> <a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow">://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.</a>
<a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow">html</a>
-   Advanced REST sample demonstrating good practices for interacting
with a Fabric network - <a href="https://github.com/hyperledger/fabric-samples/tree/main/asset-transfer-basic/rest-api-typescript" class="external-link" rel="nofollow">https</a> <a href="https://github.com/hyperledger/fabric-samples/tree/main/asset-transfer-basic/rest-api-typescript" class="external-link" rel="nofollow">://github.com/hyperledger/fabric-samples/tree/main/asset-transfer-basic/</a>
<a href="https://github.com/hyperledger/fabric-samples/tree/main/asset-transfer-basic/rest-api-typescript" class="external-link" rel="nofollow">rest-api-typescript</a>
-   Kubernetes Test Network - <a href="https://github.com/hyperledger/fabric-samples/tree/main/test-network-k8s" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric-samples/tree/main/test-network-k8s</a>

# Current Plans

**<span class="blob-code-inner blob-code-marker">Releases </span>**

<span class="blob-code-inner blob-code-marker">The project is working on
a v2.5.0 release with a feature to Purge the history of private data.
The feature may help organizations meet GDPR requirements with the
ability to delete private data while preserving a hash of the data on
the blockchain. </span>

<span class="blob-code-inner blob-code-marker">Discussion about a future
Fabric v3.0 release was kicked off at the January 5th contributor
meeting. The proposal is to refactor some Fabric components so that new
features can be more easily added on top, most notably a proposed BFT
ordering service. For more details see the recording at </span> <span class="blob-code-inner blob-code-marker"> [Contributor Meetings
2022](https://wiki.hyperledger.org/display/fabric/Contributor+Meetings+2022)
. </span>

**Documentation**

We plan to resume the Fabric community documentation meetings and update
Fabric documentation in the following areas:

-   Developing Applications with new Gateway SDKs
-   Certificate management (expirations, renewals)

**Performance**

Update Caliper client for Fabric.

# Maintainer Diversity

No changes. 6 of 11 maintainers of core Fabric from IBM.

# Contributor Diversity

Year to year comparison, by commit:

-   Q4 2020 - 674 commits. 71% from IBM.
-   Q4 2021 - 361 commits. 80% from IBM

Year to year comparison, by contributor:

-   Q4 2020 - 94 contributors. 38% from IBM.
-   Q4 2021 - 45 contributors. 42% from IBM.

# Additional Information

Link to the Fabric dashboard: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222021-10-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-01-01T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">Q4 2021</a>

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 20-Jan-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62237276"></span>
<p>By " <span style="color: rgb(23,43,77);">We plan to resume the Fabric
community documentation meetings and update Fabric documentation in the
following areas </span>", are you saying that these would be done via
new contributors from the community? If yes, that's an excellent
initiative. Given that Fabric being one of the widely looked up projects
under the Hyperledger Foundation, you could consider asking the
community to write sample applications that makes use of Gateway SDKs.
Also completes the feedback circle.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Jan 27, 2022 15:23 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62237339"></span>
<p><a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a> From the
RFC  <a href="https://github.com/hyperledger/fabric-rfcs/blob/main/text/0005-lts-release-strategy.md" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric-rfcs/blob/main/text/0005-lts-release-strategy.md</a>
I see that upon every new LTS release, the previous releases would get
deprecated in 9 months. I see in the next quarter a new LTS release
(v2.5) is planned. How is this information conveyed to consumers of the
project? There could be an opportunity for us to improve how these are
handled, not only for Fabric but for other projects too.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Jan 28, 2022 09:27 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62243317"></span>
<p><a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> Apologies, I
missed the comments previously...</p>
<p>In terms of documentation, we have resumed monthly documentation
community meetings to discuss doc priorities, solicit volunteers, and
coordinate content.</p>
<p>In terms of samples, the first priority is to ensure we update the
showcase samples for Gateway SDKs, that effort is half done and
community members can sign up for any of the remaining samples in the
GitHub issue that tracks it - <a href="https://github.com/hyperledger/fabric-gateway/issues/190" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric-gateway/issues/190</a>
, it is also tagged as a Good First Issue to help people find it.</p>
<p>In terms of LTS releases, we communicate updates in the Fabric
contributor meeting and on the Fabric mailing list.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Mar 10, 2022 05:07 </div ></td>
</tr>
</tbody>
</table>




