---
layout: default
title: 2020 Q4 Hyperledger Fabric
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Fabric

Created by David Enyeart, last modified by Gari Singh on Oct 22, 2020

# Project Health

Hyperledger Fabric continues to mature, as evidenced by the following
observations throughout this report:

-   Two LTS releases available
-   Project developers are spending a larger percentage of time on
maintenance and support than in the past, given the increasing
number of production deployments and two LTS releases.
-   Lower commit velocity on new features.
-   Healthy RFC process with reviews in contributor meetings to drive
consensus on new features.
-   Increased contributor diversity, driven in part by documentation
translation initiative.

The commit rate and mailing list activity are down slightly compared to
the same period last year.

The project would benefit from increased maintainer diversity.

# Questions/Issues for the TSC

None.

# Releases

v1.4 and v2.2 are the current LTS releases. Each has patch releases at least quarterly.

-   v1.4.8 - July 22, 2020
-   v1.4.9 - September 30, 2020
-   v2.2.0 - July 9, 2020
-   v2.2.1 - September 30, 2020
-   v2.3 is planned for November.

# Overall Activity in the Past Quarter

The project was busy maintaining the two LTS releases, given an
increasing number of production deployments.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow">RFCs merged</a> :

-   Ledger checkpointing
-   Channel participation API

<a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow">RFCs in review</a> :

-   Fabric website
-   Fabric gateway
-   WASM for smart contracts
-   Fabric private chaincode
-   BFT ordering service
-   Modular crypto service

In active development:

-   Ledger checkpointing
-   Channel participation API
-   WASM for smart contracts (tech preview released)
-   Samples and tutorials revamp
-   Production deployment guides
-   Documentation translation

Mailing list activity:

**557 messages in Q3 2019** versus **480 messages in Q3 2020** , down
14%. While Chat and Stackoverflow numbers are not available, they are
likely slightly down as well.

# Current Plans

The project is working towards a v2.3 release in November. Major
features include ledger checkpoint and channel participation management
without a system channel.

Ledger checkpoint will allow new peers to join a channel from a
checkpointed snapshot of the state database. This reduces the time to
join a channel, and reduces the storage size required to maintain a
ledger. In the future it will also be possible to prune/archive old
blocks to bring the same benefit to existing peers.

The channel participation management feature improves the privacy and
scalability of the ordering service since a global 'system channel' will
no longer be needed for the creation and management of channels.

The project is shifting from a release cadence of every 3 months to
every 4 months. The change is driven by the overall project
maturity/stability/velocity, as well as the difficulty for consumers to
keep up with a quarterly release cadence.

The other active development items mentioned above for Q2 continue into
Q3 as well.

# Maintainer Diversity

No <span class="inline-comment-marker" ref="2fe6f745-5a87-478f-beca-a645e3cb8c4a">maintainer changes </span>
for core fabric project this quarter. 12 of 13 from IBM.

# Contributor Diversity

Year to year comparison, by commit:

-   Q3 2019 - 1293 commits. 85% from IBM.
-   Q3 2020 - 893 commits. 68% from IBM

Year to year comparison, by contributor:

-   Q3 2019 - 85 contributors. 52% from IBM.
-   Q3 2020 - 106 contributors. 28% from IBM.

Documentation translation was a driver in the increased contributor
diversity.

# Additional Information

Link to the Fabric dashboard
<a href="https://lfanalytics.io/projects/hyperledger%2Ffabric/dashboard" class="external-link" rel="nofollow">https://lfanalytics.io/projects/hyperledger%2Ffabric/dashboard</a>

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
<td><span id="comment-41583908"></span>
<p>2 topics:</p>
<p><u><strong>Question 1:</strong></u></p>
<p>Curious on involvement of Working Groups in the RFC review processes.
Is there a process setup for projects to involve WG chairs/members?</p>
<p>For example, in this report I see multiple RFCs around smart
contracts currently in review. Smart Contract Working Group can actively
participate in the RFC review process, adding to the feature set and
giving feedback on best approaches. This will increase collaboration
across projects, learnings from similar features on other projects be
applied as well.</p>
<p><u><strong>Question 2:</strong></u></p>
<p>I see a process defined for release strategy, project lifecycle. Is
there a process defined for the definition of LTS?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Oct 15, 2020 03:30 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41583912"></span>
<p>Re Q1: The RFC discussions are public, so there's no limitation to
participation by anyone in those conversations, though don't be
surprised if the opinions of current Fabric users and developers are
given more weight than others with more abstract opinions when deciding
on a given RFC. The Smart Contract WG is currently on hold due to
inactivity. If anything, I believe the challenge is the opposite, th"at core maintainers of Fabric etc don't have much motivation currently to
participate in the Smart Contract WG. Until they do, using a WG as a way
to foster more cross-project communication or standardization will be
challenging. That's one thing the TSC has yet to have a great answer for
- how to make Working Groups relevant to the implementation work
happening on a project by project level.</p>
<p>I'll leave Q2 to Fabric maintainers.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by bbehlendorf
at Oct 15, 2020 04:38 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41583922"></span>
<p>Fabric used the RFC process to define a LTS strategy. See the agreed
upon LTS definition and rationale in the <a href="https://github.com/hyperledger/fabric-rfcs/blob/master/text/0005-lts-release-strategy.md" class="external-link" rel="nofollow">LTS RFC</a> .</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Oct 15, 2020 13:47 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41583925"></span>
<p>Thanks  <a href="https://wiki.hyperledger.org/display/~bbehlendorf" class="confluence-userlink user-mention" data-username="bbehlendorf" data-linked-resource-id="2392191" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Brian Behlendorf</a>   <a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Oct 15, 2020 14:14 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41584042"></span>
<p>Some of the comments asked about all fabric maintainers and
subprojects not defined.  I gather from that there are a lot of
subprojects in Fabric that are not the core DLT. </p>
<p>What sort of governance exists for those sub projects within fabric?
Is there a formal structure or a loose set of repos? And how can that be
synthesized to something the TSC can be aware of to provide best
practices to other projects that may be looking at their own
sub-projects and sub-repos?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Oct 19, 2020 05:50 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41584050"></span>
<p>Fabric now has 24 subproject repositories (various sdks, chaincode
languages, test, rfcs, website, common libraries, etc). It has been
fairly loosely governed - a Fabric core maintainer simply requests the
creation and indicates if the repo will be managed by fabric maintainers
or a different set of maintainers. Ry has been helpful in setting up the
initial repo structure and maintainers. I wouldn't want a whole lot of
process to get in the way, but I do think it would be useful to at least
write down and agree on the criteria for a new subproject and the
lightweight process to create and maintain it. I'm not sure if there is
something already written down from Hyperledger as a starting point?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at Oct 19, 2020 13:36 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41584317"></span>
<p>I think we need to be careful about conflating repositories with
subprojects.  Rather than having an "uber" repository, Fabric has broken
things out into multiple repositories as  <a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a> has
indicated in his response.<br />
<br />
We do assign appropriate (and active) maintainers to the various
repositories and do have a small set of release maintainers who have are
committers for almost all of the repositories.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by mastersingh24
at Oct 22, 2020 14:20 </div ></td>
</tr>
</tbody>
</table>




