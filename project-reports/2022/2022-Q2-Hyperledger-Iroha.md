---
layout: default
title: 2022 Q2 Hyperledger Iroha
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q2 Hyperledger Iroha

Created by Sara Garifullina, last modified by Jim Zhang on Aug 25, 2022

<span style="letter-spacing: 0.0px;"> </span>

# Project Health

Generally, the situation is the following: Iroha 1 is being maintained
and improved in terms of performance – the new transport system is being
developed. Iroha 2 is rapidly growing – the team welcomed several new
developers and numerous features; releases are presented every month. 
<a href="https://wiki.hyperledger.org/display/~baziorek" class="confluence-userlink user-mention" data-username="baziorek" data-linked-resource-id="31203253" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grzegorz Bazior</a> is
leading this year's Mentorship effort. Community is not very active but
the team is open and answers the questions when those occur.

Iroha 2 team has acquired 4 more Rust developers to speed up the planned
workload and cover more "functional ground". Also, as part of a wider
organisational change, Iroha 2 team will fall within HL Iroha 2.0 Tribe
which consists of multiple related projects. As a result, to improve the
internal communication, we are planning to start running monthly
technical demonstration sessions on new delivered features. In the near
future, we are aiming to open the demo session to a wider audience and
make it publicly available to the wider Hyperledger community. In
addition, Iroha 2 has started with a new front-and initiative
(blockchain Explored). Currently, UI/designs are ready and the
development is well underway. 

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes </span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. </span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? Not yet</span> </span>

# Questions/Issues for the TSC

# Releases (Iroha 1x)

<a href="https://github.com/hyperledger/iroha/releases/tag/1.4.0" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.4.0</a>

<a href="https://github.com/hyperledger/iroha/releases/tag/1.5.0" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.5.0</a>

# Releases (Iroha 2x)

<a href="https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.2" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.2</a>

<a href="https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.3" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.3</a>

# Overall Activity in the Past Quarter

We moved to Discord with the whole Hyperledger Community and adapted the
chat bot – now it connects Discord, Telegram and Gitter and runs more
easily maintainable code, so everyone should be able to stay in contact
just the way it is convenient to them.

# Iroha v1

Some of the most important technical results for Iroha 1 team in the
last quarter were:

-   the module for MST was rebuilt for more efficiency
-   <a href="https://wiki.hyperledger.org/display/~baziorek" class="confluence-userlink user-mention" data-username="baziorek" data-linked-resource-id="31203253" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grzegorz Bazior</a> and
his team helped greatly with updating Python library that is now
working perfectly with Iroha 1 newest versions
-    Work is on the way on rework of the transport
-   Burrow now works with RocksDB
-   Other optimisations

# Iroha v2 (main completed features for the last quarter):

-   Introduced better and improved non-mintable assets
-   Introduced new standard for TPS benchmarks
-   Account restructuring
-   Roles are no longer optional. More features to be axed 
-   SDK - Trigger support
-   RawGenesisBlock builder 
-   Real-world performance testing (stable ~40TPS) 

# Current Plans

It is important to keep in touch with the community using all the
channels possible: Iroha 2 is being very actively developed with many
new team members.

Iroha 1 is also not only maintained – the next release should include
changes that will drastically improve the performance via rework of the
transport – it should be completed for Iroha v1.6.

**Iroha v2 (in the progress):**

-   Improved common filtering API
-   Debug 3 high severity actor-related bugs:

1.  1.  Slow processing (~50TPS)
2.  Kura init (versioning)
3.  Register/unregister peer

-   Distributed testing in CI
-   Ongoing work on WASM dynamic linkage
-   Docker friendly CLI 



**Long term deliverables for Iroha 2**

1.  Hijiri (local reputation system)
2.  Offline transactions (Hardware is ready and waiting to be
programmed)
3.  Parachain compatibility 
4.  Iroha Python Library should be improved 
5.  Transaction fees are to be introduced. 

# Maintainer Diversity

Iroha 2 has considerably grown in size and diversity of resources.
Currently, Iroha 2 team consist of 1 front-end developer (mainly engaged
in the blockchain explorer initiative), a technical writer, fully
committed QA and currently, the core team consists of 8 Rust
developers. 

# Contributor Diversity

<a href="https://wiki.hyperledger.org/display/~baziorek" class="confluence-userlink user-mention" data-username="baziorek" data-linked-resource-id="31203253" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grzegorz Bazior</a> 's team
still greatly contributes to the project, Soramitsu's team is growing as
well. We hope to find more contributors interested in features th"at Iroha 2 can provide. 

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
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
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

<span class="placeholder-inline-tasks"> 10-May-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62252393"></span>
<p><a href="https://wiki.hyperledger.org/display/~SaraG" class="confluence-userlink user-mention" data-username="SaraG" data-linked-resource-id="2392239" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Sara Garifullina</a> A
couple of questions to clarify:</p>
<ol class="incremental">
<li>Is Iroha v2 a full rewrite in Rust instead of C++?</li>
<li>Are the transaction fees going to be optional? The ones that are to
be introduced in V2 - from the list of long term deliverables</li>
</ol>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by Peter Somogyvari at May 10, 2022 22:26 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62252437"></span>
<p><a href="https://wiki.hyperledger.org/display/~SaraG" class="confluence-userlink user-mention" data-username="SaraG" data-linked-resource-id="2392239" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Sara Garifullina</a> – I
like the idea of running monthly technical demonstration sessions.  We'd
be happy to work with you to help you promote those so lots of people
can learn about how to use and contribute to Iroha.  We've seen a lot of
interest in technical demos and workshops recently and I think we can
get a good audience for these.  For instance, a recent technical
workshop for FireFly that we ran as a virtual meetup had over 670 people
sign up for it.  Happy to talk with you more about how we can help
promote what's happening with Iroha.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at May 11, 2022 14:46 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62252438"></span>
<p>I did not see an answer to this question:</p>
<blockquote>
<span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">3. Has your project implemented these
inclusive language changes listed below to your repo? You can optionally
<span>  </span> <a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow" style="text-decoration: none;">use
the DCI Lint tool</a> <span>  </span>to make this a recurring action on
your repo.<br /></span> </span>master → main<br />
slave → replicas<br />
blacklist → denylist<br />
whitelist → allowlist
</blockquote>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at May
11, 2022 15:22 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62252448"></span>
<blockquote>
<ul class="incremental">
<li>Burrow now works with RocksDB</li>
</ul>
</blockquote>
<p>Can you elaborate on how Iroha uses Burrow?  Are these rocks db
changes in burrow itself or the iroha code wrapping burrow?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at May 11, 2022 18:22 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62253218"></span>
<p>In the Maintainer and Contributor diversity section, It is not clear
who Grzegorz's or  <span style="color: rgb(23,43,77);">Soramitsu's teams
are. Are these teams tied to two different organizations? Do they focus
on different releases or different functional areas? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by denyeart at May 19, 2022 13:58 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71697018"></span>
<p>Hi! Sorry it took me some time to get here. As I said in Discord, it
is not exactly the same rewrite. The team just decided that it will be
more beneficial to use Rust to work on the newer features that they see
important. On the fees –  yes, they are optional. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jun
17, 2022 12:36 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71697019"></span>
<p>Right now Iroha team is working on some blog posts and are thinking
about Demo. After all the necessary features and materials are ready,
they will definitely contact you about this – now the team has enough
people to join many activities and represent Iroha more. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jun
17, 2022 12:39 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71697020"></span>
<p>Sorry, I believe we missed this – yes, we never had any lists or
replicas to my knowledge but the names of branches were changed some
time ago.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jun
17, 2022 12:40 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71697022"></span>
<p>So, there was a Burrow integration with Iroha ( <a href="https://iroha.readthedocs.io/en/develop/integrations/index.html#hyperledger-burrow" class="external-link" rel="nofollow">https://iroha.readthedocs.io/en/develop/integrations/index.html#hyperledger-burrow</a>
) but it did not work before with Iroha running with RocksDB, only with
Postgres version. It is more about Iroha itself I guess. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jun
17, 2022 12:42 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71697023"></span>
<p>Grzegorz is from a separate company, and is a maintainer independent
from Soramitsu. He helps out with Python library for Iroha 1, for
example, and helps with Mentorship projects, working together with Iroha
1 developer. We use "teams" to separate Iroha 1 and Iroha 2 teams – as
these versions are rather different, their work is in a way
separate. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jun
17, 2022 12:45 </div ></td>
</tr>
</tbody>
</table>




