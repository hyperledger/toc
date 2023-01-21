---
layout: default
title: 2019 Q3 Hyperledger Caliper
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Caliper

Created by Attila Klenik, last modified by Angelo De Caro on Sep 26, 2019

# Project Health

Caliper reached a significant milestone in the last quarter. The first
official pre-release was published to both
<a href="https://www.npmjs.com/package/@hyperledger/caliper-cli" class="external-link" rel="nofollow">NPM</a> and
<a href="https://hub.docker.com/r/hyperledger/caliper" class="external-link" rel="nofollow">DockerHub</a> . The published
artifacts significantly increased the setup&run experience for the
community, resulting in fewer issues/questions both on GitHub and
Rocket.Chat, which, in turn, freed up some maintainer efforts to focus
on new features and upgrades. 

Community relations mainly happen on Rocket.Chat, and the questions are
answered in detail, and on time. Furthermore, there is an increasing
contributor interest related to the supported DLTs.

# Questions/Issues for the TSC

There are no issues at this time.

# Releases

The first official pre-release (after some significant repository
restructuring and refactoring) was finally published on NPM and
DockerHub, marking the v0.1.0 state of Caliper.

Since then, the maintainers have a stable code-base to build upon
without worrying about breaking the release used by the community. This
increased the momentum of development for the project.

The maintainers haven't decided on a regular publishing frequency yet,
but they plan to bump versions after every added major feature or a set
of bug-fixes (this means an approximately 3-4 weeks long release cycle).

# Overall Activity in the Past Quarter

-   **Forum activities**
Mostly the Rocket.Chat channel is used for Q&A. Every question is
answered in detail or redirected towards the relevant docs page. The
questions are usually answered within a day (more often than not,
even within an hour or realtime), keeping in mind that the active
maintainers are mainly located in Europe.
-   **Project stats (since the last report)**
Issues closed: 83
PRs merged: 42
<a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vRZCaEWwKMZZCnHf-YVNcSpU3PYd81rozu9KVrSptg7NixRdyHp64isnLIKxq8fTJG7zg26UVpIgNaq/pubhtml?gid=1454794804&amp;single=true" class="external-link" rel="nofollow">Additional charts</a>
-   **Recent noteworthy dev-related activities**
-   Deprecated the old Fabric adapter, and replaced it with a more
"modern" one (increased flexibility, feature set,
maintainability)
-   Improving the new Fabric adapter (support SDK gateway mode,
discovery, wallets)
-   Fixed some load generation performance-related issues
-   Fixed some Docker monitoring bugs
-   Increased CLI and runtime flexibility
-   Started to cover the codebase with unit tests
-   **Published v0.1.0**
-   Added version selection for docs page, and improved the content
of some pages
-   Separated the sample benchmarks into a new
<a href="https://github.com/hyperledger/caliper-benchmarks" class="external-link" rel="nofollow">caliper-benchmarks</a>
repository, which (coupled with the release) provides an easy
entry point for the community to start experimenting with
Caliper.
-   **A UI component was implemented by Jason You during the summer
internship.** It is currently under review and further
polishing. He did an excellent job during the summer, even
though the Caliper code-base was under heavy development. This
component will further help the adoption of Caliper in the
community.

# Current Plans

The development tasks can be sorted mainly into the following
categories:

-   Stabilizing the core architecture
-   Introducing support for new platforms
-   Polishing the existing platform adapters
-   Improving the documentation

### Stabilizing the core architecture

-   The scope and goals of Caliper were a bit shady/undefined for some
time, mainly the line between being a load generator and/or a
monitoring framework.
-   The current consensus seems to indicate that Caliper will aim to
be a full-fledged, flexible load generator framework for DLTs. 
-   Correspondingly, the monitoring responsibility of Caliper will
be delegated to tried-and-true industrial-grade tools and
Caliper will provide integration with them.
-   As a first trial, a Prometheus integration was implemented and
is currently under review.
-   It's clear that Caliper should be a loosely coupled, distributed
framework/system, capable of generating workloads on a large scale.
-   Until recently, Zookeeper was used to coordinate multiple
Caliper "worker" nodes. It was an experimental feature, wasn't
easy to deploy, not to mention that it required additional
infrastructure elements (zookeeper nodes) beside Caliper.
-   To this end, this feature will be removed in v0.2.0
-   The plan is to introduce a more lightweight, embedded messaging
solution between clients in v0.3.0, like ZMQ or other similar
solutions. This would keep the Caliper artifacts self-contained
(like Kafka vs Raft in Fabric), facilitating deployment.
-   The last group of core-related work items is covering the code-base
with unit tests as much as possible. Once the code-base is
stabilized by the above items, hopefully, this task will become
easier.

### Introducing support for new platforms

Currently, there are multiple platform support PRs under review. Namely
for:

-   Ethereum
-   FISCO BCOS
-   Corda

It's worth to note that each PR is submitted <span class="inline-comment-marker" ref="99e874c0-4ed7-45bf-b26b-d89822fa71b5">by the community </span> 
<img src="emoticons/thumbs_up.svg" class="emoticon emoticon-thumbs-up" data-emoticon-name="thumbs-up" alt="(thumbs up)" />

### Polishing the existing platform adapters

A key selling point of Caliper is the ability to implement workloads in
a DLT-agnostic way. "Write once, run anywhere."
The list of supported DLTs is getting longer, which will hopefully give
some ideas about the required abstraction level of the Caliper API.
However, the help of the specific platform's experts/maintainers will be
probably needed to provide full-fledged support for the platforms.

### Improving the documentation

The issues/questions pressure towards the maintainers could be decreased
further by improving the documentation:

-   Clarifying the documentation of the general Caliper components and
adapters.
-   Providing detailed tutorials for writing benchmarks and other
tips&tricks.

There's already active work addressing this task group
(independently/concurrently with the other tasks).

# Maintainer Diversity

Current maintainer list and affiliations, in alphabetical order: 

-   Attila Klenik (Budapest University of Technology and Economics)
-   Feihu Jiang (Huawei)
-   Liam Grace (IBM), **new maintainer**
-   Nick Lincoln (IBM)
-   Yaoguo Jiang (Huawei)
-   Yu Pan (Huawei)

# Contributor Diversity

There are currently 28 contributors to the repository, 18 of them with
more than one commit. To the best of our knowledge, contributors are
from various companies/organizations, such as Huawei, IBM, Intel,
Soramitsu, Budapest University of Technology and Economics, Monax and
the University of Oregon. The maintainers are also keeping in touch with
other companies who are mainly interested in expanding the platform
support of Caliper (e.g., with Corda).

# Additional Information

N.A.

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-20023367"></span>
<p>Focusing on deployment and not monitoring seems like a good idea to
me. It is better to be doing one thing really well than two not so
well.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Sep
23, 2019 13:00 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-20023561"></span>
<p>Yes, we absolutely agree. Plus we don't want to reinvent the wheel.
Nor we have the resources for it  <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /> </p>
<p>(I think you mean load generation, not deployment)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by klenik at Sep
24, 2019 09:43 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-20023564"></span>
<p>Picking up our conversation from the July report...<br />
It's fine with me if the user indicates the network size and caliper
does not try to discover the size. It's just important that we keep
emphasis on reporting performance in the context of network size. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Sep 24, 2019 09:51 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-20023565"></span>
<p>Yes, that's true. However, this responsibility, in the end, falls to
the site publishing those reports.</p>
<p>The PSWG whitepaper defines a "reporting template", so the benchmarks
must report the network size anyway. A repeatable benchmark will include
every artifact needed to confirm the reported numbers, so everyone can
make sure that the reported network size is accurate. And the config
artifacts will also contain the known network topology (which could be
inaccurate in the case of Fabric discovery service, for example).</p>
<p>So it's the same workflow as the current non-DLT benchmarks. If you
don't believe the numbers, then verify the results yourself. If you
can't reproduce the results, then be suspicious. </p>
<p>For the Caliper-related reports (like the ones in the <a href="https://hyperledger.github.io/caliper-benchmarks/" class="external-link" rel="nofollow">caliper-benchmarks</a> repo), we'll
review each benchmark report (and artifacts), and will ensure they
adhere to the above requirements.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by klenik at Sep
24, 2019 10:06 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-20023567"></span>
<p>Yes, sorry, got my wires crossed for a moment.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Sep
24, 2019 10:21 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-20023917"></span>
<p>Thanks. sounds good.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Sep 25, 2019 15:19 </div ></td>
</tr>
</tbody>
</table>




