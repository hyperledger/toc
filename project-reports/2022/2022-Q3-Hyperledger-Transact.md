---
layout: default
title: 2022 Q3 Hyperledger Transact
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Transact

Created by Andrea Gunderson, last modified by David Enyeart on Sep 22, 2022

<span style="letter-spacing: 0.0px;"> Hyperledger Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a></span>

# Project Health

Health is good. In the last quarter there was one release. This release
includes a number of fixes to the stability of the SQL-backed merkle
state implementation, including stable behavior of the merkle tree after
state pruning has been applied.  It also includes changes to support
using the SQL-backed merkle state in the context of a wider transaction.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes</span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. </span> </span>
1.  master → main Yes
2.  slave → replicas N/A
3.  blacklist → denylist N/A
4.  whitelist → allowlist Yes
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? The statement has not been added.
</span> </span>

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 33 releases. The current
release is 0.4.6. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> :
<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow"><span>https://crates.io/crates/transact/versions</span></a>

# Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion has been moved to
Discord.

Additional work:

-   Fix state pruning when using SqlMerkleState
-   Allow the use of SqlMerkleState with-in existing transactions
-   Stabilize the "state-merkle-sql-in-transaction" feature by removing
it
-   Make updates necessary for the eventual stabilization of the
"playlist-smallbank" feature

# Current Plans

The Transact team is investigating merging libtransact into sawtooth-lib
in order to simplify the overall dependency tree. sawtooth-lib did not
exist when the Transact project was created, but might now be a good
fit.

Future:

-   Re-evaluate threading model for batch scheduling and execution
-   Setup a documentation site to help explain/advocate the project
-   Add a next-generation smart contract API / simplified smart
contracts (cross-project with Sawtooth, in progress)
-   Further develop the Transact SDK for JavaScript

# Maintainer Diversity

Maintainers are the same as the previous quarter. Maintainers are
currently:

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd"><p><strong>Name</strong></p></td>
<td class="confluenceTd"><p><strong>GitHub</strong></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Andi Gunderson </span></p></td>
<td class="confluenceTd"><p><span>agunde406 </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Isabel Tomb </span></p></td>
<td class="confluenceTd"><p><span>isabeltomb </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>James Mitchell </span></p></td>
<td class="confluenceTd"><p><span>jsmitchell </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Logan Seeley </span></p></td>
<td class="confluenceTd"><p><span>ltseeley </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Peter Schwarz </span></p></td>
<td class="confluenceTd"><p><span>peterschwarz </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Richard Berg </span></p></td>
<td class="confluenceTd"><p><span>rberg2 </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Ryan Beck-Buysse </span></p></td>
<td class="confluenceTd"><p><span>rbuysse </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Ryan Banks </span></p></td>
<td class="confluenceTd"><p><span>ryanlassigbanks </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Shannyn Telander </span></p></td>
<td class="confluenceTd"><p><span>shannynalayna </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Shawn Amundson </span></p></td>
<td class="confluenceTd"><p><span>vaporos </span></p></td>
</tr>
</tbody>
</table>

# Contributor Diversity

There were a total of 5 contributors in the last quarter.

# Additional Information

Insights from May 23rd 2022 to August 25th 2022

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222022-05-23T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-08-25T05:00:00.000Z%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222022-05-23T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-08-25T05:00:00.000Z%22%7D</a>

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
-   🔲 <span class="placeholder-inline-tasks">
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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 31-Aug-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71700743"></span>
<blockquote>
<p><span>The Transact team is investigating merging libtransact into
sawtooth-lib in order to simplify the overall dependency tree.
sawtooth-lib did not exist when the Transact project was created, but
might now be a good fit. </span></p>
</blockquote>
<p><span>Does this mean that the transact project would be end-of-life?</span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Aug
31, 2022 18:23 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71700816"></span>
<p>Would probably mean that it goes into maintenance mode for a while
since its a dependency for several other projects. There are also
non-library pieces too.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Sep 01, 2022 14:43 </div ></td>
</tr>
</tbody>
</table>




