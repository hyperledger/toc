---
layout: default
title: 2023 Q1 Hyperledger Fabric
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q1 Hyperledger Fabric

Created by David Enyeart, last modified by Arun S M on Jan 19, 2023

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Fabric is fairly mature
and stable with a Long-term support (LTS) release and incremental new
features being added in minor releases. There is less churn and fewer
commits than in years past, with continued focus on quality and support.
New features get proposed, approved, and implemented based on a
community RFC process. Mailing list activity is down a bit compared to
prior years. PRs and mailing list questions are generally turned around
quickly.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. Yes
    1.  master → main
    2.  slave → replicas
    3.  blacklist → denylist
    4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? Yes</span>

# Questions/Issues for the TSC

None.

# Releases



v2.2 is the current LTS releases with patch releases approximately
quarterly.

Releases past quarter:

-   Fabric v2.2.9 - October 25, 2022
-   Fabric v2.4.7 - October 25, 2022
-   Fabric v2.5.0-alpha3 - December 21, 2022

Fabric CA

-   Fabric CA v1.5.6-beta3 - January 3, 2023

Fabric v2.5.0-alpha3 and Fabric CA v1.5.6-beta3 pre-releases were
created so that the community can try the new ARM support in the
binaries and images. This is more important these days given the rising
prevalence of Mac M1 ARM architecture in the developer community.



Upcoming releases:

-   Fabric v2.5.0 - Expected to be next LTS release

# Overall Activity in the Past Quarter



The project delivered fixes to the Fabric v2.2 (current LTS) and v2.4
(latest) releases.

The Purge Private Data History feature has been implemented with plan to
release in Fabric v2.5 in Q1.

ARM support was added for Fabric binaries and images and made available
in pre-releases v2.5.0-alpha3 and Fabric v1.5.6-beta3.

SmartBFT consensus algorithm is being integrated into the Fabric
ordering service for an eventual Fabric v3.0 release.

An RFC was merged, and development started, to create a
<a href="https://github.com/hyperledger/fabric-admin-sdk" class="external-link" rel="nofollow">fabric-admin-sdk</a> seeded from
Technical Working Group China that will help with programatic channel
and chaincode management. Targeting a Go SDK first.

The Fabric workshop created for Global Forum has been merged into <a href="https://github.com/hyperledger/fabric-samples/tree/main/full-stack-asset-transfer-guide" class="external-link" rel="nofollow">fabric-samples</a> .

New lab created - <a href="https://github.com/hyperledger-labs/microfab" class="external-link" rel="nofollow">microfab</a> - a single container
Fabric environment intended to accelerate application and chaincode
development, and used in the workshop mentioned above.

Additional Fabric repositories have shifted CI from Azure Pipelines to
Github Actions.

# Current Plans

<span class="blob-code-inner blob-code-marker">The project is working on
a v2.5.0 release in the release-2.5 branch, with a feature to Purge the
history of private data. The feature may help organizations meet GDPR
requirements with the ability to delete private data while preserving a
hash of the data on the blockchain. The v2.5 release is expected early
2023 and is expected to become the next long-term support (LTS)
release. 

<span class="blob-code-inner blob-code-marker">Fabric v3.0 release
development has started, primarily around refactoring the ordering
service for the upcoming BFT consensus integration. In the v3.0 release
we are considering deprecation and removal of some features that have
historically made deployment difficult, such as docker-in-docker
chaincode building.

# Maintainer Diversity

<span style="color: rgb(23,43,77);">6 of 8 maintainers from IBM.

# Contributor Diversity

Year to year comparison, by commit:

-   Q4 2021 - 361 commits. 80% from IBM.
-   Q4 2022 - 382 commits. 80% from IBM.

Year to year comparison, by contributor:

-   Q4 2021 - 45 contributors. 42% from IBM.
-   Q4 2022 - 40 contributors. 38% from IBM.

# Additional Information

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222022-10-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-01-01T05:00:00.000Z%22%7D" class="external-link" rel="nofollow">Insights dashboard link</a>

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~bur" class="confluence-userlink user-mention" data-username="bur" data-linked-resource-id="29033442" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Marcus Brandenburger</a>
 
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~TimoGlastra" class="confluence-userlink user-mention" data-username="TimoGlastra" data-linked-resource-id="31199909" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Timo Glastra</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~vramaiitkgp" class="confluence-userlink user-mention" data-username="vramaiitkgp" data-linked-resource-id="16325996" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ramakrishna V</a>  </span>

# Submission date

<span class="placeholder-inline-tasks"> 14-Jan-2023



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-80775699"></span>
<p>It was great to read that ARM support is something that you invest
into! (We are hoping to do the same with Cacti, slowly but surely)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by Peter Somogyvari at Jan 16, 2023 18:06 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-80775729"></span>
<p>IMO the <code>fabric-admin-sdk </code>  would be a very useful thing
from an engineering perspective. I remember those features were
available in the Fabric SDK (at least the Node.js version) until v1.4 or
so but were then dropped and exclusive use of the Fabric CLI was
promoted.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vramaiitkgp
at Jan 17, 2023 08:54 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-80775771"></span>
<p><a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a> – That's
great to see that the Fabric workshop created for Global Forum has been
merged into fabric-samples.  If there's interest in delivering th"at content again this year, I'd be happy to help with that.  Running this
as a virtual workshop would let us get this content to a much larger
audience than we were able to do at the in person workshop in Dublin. 
For other virtual workshops we've run we seen several hundred people
signing up for them, so this could be a good way to help more people get
started with Fabric this year.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at Jan 17, 2023 17:11 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-80775804"></span>
<p>Yes, this is exactly the gap that will be resolved!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Jan 17, 2023 21:24 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-80775805"></span>
<p><a href="https://wiki.hyperledger.org/display/~davidwboswell" class="confluence-userlink user-mention" data-username="davidwboswell" data-linked-resource-id="2392933" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Boswell</a> Sounds
good, once v2.5 is released we'll be in a good position to deliver a
virtual workshop on the long-term support stack (Fabric v2.5, gateway
SDK), perhaps Q2. I'll mention to the folks that worked on the
workshop.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Jan 17, 2023 21:27 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-80775810"></span>
<p>Great, sometime in Q2 or later sounds good.  If the folks that worked
on the workshop want to reach out to me about timing and promotion, I'll
be happy to talk with them.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at Jan 17, 2023 23:58 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-80775860"></span>
<p>Thanks <a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a> . Gre"at to see the progress on the SmartBFT integration. Also agree that the
admin SDK for Go would be welcomed by the community!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jimthematrix
at Jan 19, 2023 11:33 </div ></td>
</tr>
</tbody>
</table>




