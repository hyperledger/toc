---
layout: default
title: 2022 Q1 Hyperledger Iroha
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Iroha

Created by Sara Garifullina, last modified by Peter Somogyvari on May 25, 2022

# Project Health

We are still continuing working as 2 teams – Iroha 1 and Iroha 2. Both
teams develop features, fix issues, talk to the community. Still, once
in 2 weeks we meet for our community meeting (where anyone could
attend). Iroha 2 is planning to show their first working version soon,
Iroha 1 constantly improving the production-ready versions and
implemented a couple of very nice features to increase the performance
and experience. We have questions from the community on various
integrated projects which we might need to discuss soon (e.g using
Burrow or Ursa). 

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes </span>

# Questions/Issues for the TSC

No questions for now

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.4.0-rc.1" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.4.0-rc.1</a>
 - Soon to publish RC 2 and after testing – 1.4.0

# Overall Activity in the Past Quarter

In terms of communications, chats were rather active, mailing lists -
not so much. The questions are being answered, communication continues
as well as the community calls – so if someone wants to connect, they
certainly can. 

In terms of development: 

#### Iroha v1:

Made a release of 1.4 - rc1 (tag is ready for rc2 as well - just needs
to be published as a release)

Added the feature of syncing node

Healthcheck

Fixes on the memory consumption and others

#### Iroha v2:

Improved performance

Added prometheus metrics for profiling

Integrated WASM to support more smart contracts

Integrating triggers

# Current Plans

Both Iroha 1 and Iroha 2 teams are active and have their own objectives:

#### Iroha v1: 

Release 1.4 based on release candidate 2

Speed up internal communication within Iroha

Moving configuration into the blockstore

Minimise OS traffic

#### Iroha v2:

Refactor Sumeragi consensus

Memory consumption improvements, 

Final testing for preview release candidate 1

New procedure for SDK synchronisation

# Maintainer Diversity

1 C++ developer and 1 QA specialist joined Iroha 1 team. Iroha 2 was
joined by a new project manager who will be leading the development and
the project in general and a Rust developer as well as several
specialists contributing into the libraries 

# Contributor Diversity

Soramitsu maintains Iroha still with help from 
<a href="https://wiki.hyperledger.org/display/~baziorek" class="confluence-userlink user-mention" data-username="baziorek" data-linked-resource-id="31203253" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grzegorz Bazior</a> 's team

# Additional Information

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   🔲 <span class="placeholder-inline-tasks">
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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 06-Feb-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62238618"></span>
<blockquote>
<p><span style="color: rgb(23,43,77);">e.g using Burrow </span></p>
</blockquote>
<p><span style="color: rgb(23,43,77);">Arnaud mentioned that he
communicated with the Iroha community that Burrow has been deprecated.
These may be the conversations that you are referring to. I wanted to
make sure that this is the case. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Feb
08, 2022 15:21 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62238664"></span>
<p><a href="https://wiki.hyperledger.org/display/~SaraG" class="confluence-userlink user-mention" data-username="SaraG" data-linked-resource-id="2392239" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Sara Garifullina</a> –
That's great to hear that Iroha 2 is planning to show their first
working version soon.  We're happy to coordinate with the team to help
them share this on Hyperledger's channels.  And if they have interest in
connecting with people who'd like to contribute, we could organize a
contribution campaign around this.  Feel free to reach out if you'd like
to talk more about that.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at Feb 08, 2022 17:48 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62238683"></span>
<p>Yes, that is the case. We are currently thinking about how to
approach this. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Feb
08, 2022 19:39 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62238684"></span>
<p>Thank you, that would be great! As soon as we have everything in
order, I hope we will all find the time to come up with something
interesting for the community  <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /> </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Feb
08, 2022 19:40 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62254027"></span>
<p>Apologies for the late review. LGTM</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Peter Somogyvari at May 25, 2022 05:32 </div ></td>
</tr>
</tbody>
</table>




