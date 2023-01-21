---
layout: default
title: 2022 Q3 Hyperledger Sawtooth
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Sawtooth

Created by Andrea Gunderson, last modified by Artem Barger on Oct 20, 2022

<span style="letter-spacing: 0.0px;"> Hyperledger Sawtooth
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow"><span>https://sawtooth.hyperledger.org/ </span></a></span>

# Project Health

In the last quarter focus has been on the Artifact APIs in the Sawtooth
Library, contributions to Sawtooth's underlying dependencies (Transact,
Augrim), and extending the Go SDK to include support for consensus
engines.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes </span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. </span> </span>
1.  master → main: Yes
2.  slave → replicas: Yes
3.  blacklist → denylist: Yes
4.  whitelist → allowlist: Yes
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages?</span> </span>          We have not added the statement to the
documentation yet.

# Questions/Issues for the TSC

No new issues.

# Releases

No recent releases

# Overall Activity in the Past Quarter

Artifact related traits Artifact, ArtifactStore, ArtifactCreator,
ArtifactCreatorFactory were added to sawtooth-lib along with the initial
traits and structs for a new publisher design.

Sabre performance was improved by implementing state caching in Transact
for large pieces of state, such as smart contracts.

Sawtooth Seth has been archived. 

The community continues to discuss Sawtooth-related issues on Discord.
The monthly live working sessions continue and now primarily focus on
design documents for Sawtooth 2-related work.

# Current Plans

The following work is currently in progress:

-   Add support to Go SDK for writing consensus engines
-   Add Go devmove consensus example
-   Merge transaction execution components from Transact into the
Sawtooth library
-   Merge some Sabre smart contract engine into Sawtooth library
-   Create a new consensus library that will be used by the Sawtooth
validator
-   Sawtooth 2 component designs
-   Rewriting the Sawtooth CLI in Rust (paused)



The following work is currently planned:

-   Initialize a Sawtooth service for Splinter



Plans will continue to be developed as part of the working sessions.

# Maintainer Diversity

Maintainers are distributed across
<a href="http://bitwise.io/" class="external-link" rel="nofollow"><span>Bitwise </span></a> IO, Cargill, Intel, and Walmart
Labs.

# Contributor Diversity

Commits from 2022-04-26 to 2022-07-26 :  53

Committers from 2022-04-26 to 2022-07-26 :  5

Domains from 2022-04-26 to 2022-07-26 :  2

# Additional Information

Insights <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222022-04-26T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-07-26T05:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222022-04-26T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-07-26T05:00:00.000Z%22%7D</span></a>

# Reviewed By

-   🔲 <span class="placeholder-inline-tasks">
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

<span class="placeholder-inline-tasks"> 27-Jul-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71698954"></span>
<blockquote>
<ol class="incremental">
<li><span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an  <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow" style="text-decoration: none;">Inclusive Language
Statement</a>  to your project's documentation and/or Wiki pages?<br /></span> </span> <span>         We have not added the statement to the
documentation but besides the instance noted above we believe the
documentation is inclusive.  </span></li>
</ol>
</blockquote>
<p><span>I believe there may be a mismatch in the question and the
answer. The question is attempting to get to a place where information
is given to the contributors of Sawtooth code or documentation that they
should ensure to use inclusive language in their contributions. The
answer seems to answer the question of whether to documentation notes
its inclusive nature. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Jul
27, 2022 17:47 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71698955"></span>
<blockquote>
<p><span>Artifact related traits Artifact, ArtifactStore,
ArtifactCreator, ArtifactCreatorFactory were added to sawtooth-lib along
with the initial traits and structs for a new publisher design.</span></p>
</blockquote>
<p><span>Can you provide more details on what these artifact related
traits do within Sawtooth?  </span></p>
<p><span>Is the Publisher related to publishing blocks? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Jul
27, 2022 17:49 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71698959"></span>
<p>Gotchya, there was some confusion when we had answered this question
in the past so I was just trying to cover both. I'll edit it to just say
that we have not added it to the website yet.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by agunde at Jul
27, 2022 18:37 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71698961"></span>
<p>Sure. We have some more information on the Splinter website (some of
these design docs were written before we revamped the sawtooth website
and have not been moved over yet). Information about the artifacts can
be found here <a href="https://www.splinter.dev/community/planning/artifact_store.html" class="external-link" rel="nofollow">https://www.splinter.dev/community/planning/artifact_store.html</a>
and how they are used by the publisher can be found here <a href="https://www.splinter.dev/community/planning/publisher_for_scabbard_v3.html" class="external-link" rel="nofollow">https://www.splinter.dev/community/planning/publisher_for_scabbard_v3.html</a>
. These design sfocuse on defining a publisher that can be used by both
Sawtooth 2.0 and Scabbard (Sabre service in Splinter), where the
publishing activity is very similar except for the ending "published" artifact, a Block in Sawtooth and a BatchResult in Scabbard.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by agunde at Jul
27, 2022 18:43 </div ></td>
</tr>
</tbody>
</table>




