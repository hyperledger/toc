---
layout: default
title: 2022 Q4 Hyperledger Transact
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q4 Hyperledger Transact

Created by Andrea Gunderson, last modified by Grace Hartley on Dec 08, 2022

<span style="letter-spacing: 0.0px;"> Hyperledger Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a></span>

# Project Health

Maintainers plan for future features to go into libsawtooth instead of
into Transact; thus, Transact is currently in bug-fix-only maintenance
mode. We expect to be in maintenance mode for the foreseeable future,
until all projects currently using Transact have migrated to
libsawtooth.

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
make this a recurring action on your repo. Yes</span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? </span> </span> The statement has
not been added. <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);"></span> </span>

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 33 releases. The current
release is 0.4.6. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> :
<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow"><span>https://crates.io/crates/transact/versions</span></a>

# Overall Activity in the Past Quarter

Minor maintenance activities.

# Current Plans

Previous technical plans will transition to libsawtooth, including
threading model improvements and next-generation smart contract API. For
Transact itself, continued maintenance activities and support.

# Maintainer Diversity

Maintainers are the same as the previous quarter. Maintainers are
currently:

<table class="confluenceTable">
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

There was 1 contributor last quarter.

# Additional Information

Insights <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222022-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-11-16T06:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222022-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-11-16T06:00:00.000Z%22%7D</span></a>  

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   🔲 <span class="placeholder-inline-tasks">
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

<span class="placeholder-inline-tasks"> 15-Nov-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-78022019"></span>
<blockquote>
<p><span>Maintainers plan for future features to go into libsawtooth
instead of into Transact; thus, Transact is currently in bug-fix-only
maintenance mode. We expect to be in maintenance mode for the
foreseeable future, until all projects currently using Transact have
migrated to libsawtooth. </span></p>
</blockquote>
<p><span>Do you foresee this project moving to a dormant, deprecated, or
end of life stage in the near future? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Nov
15, 2022 20:44 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-78022022"></span>
<blockquote>
<p>&gt; Insights <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222022-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-11-16T06:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222022-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-11-16T06:00:00.000Z%22%7D</span></a></p>
</blockquote>
<p>There are four commits in the last quarter, and all were done by <a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> I wonder about
the health status of the project, is there any maintainers activity?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by C0rWin at Nov
15, 2022 22:10 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-78022046"></span>
<p><a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a> if you
look here:  <a href="https://github.com/daisy-row/transact-logs" class="external-link" rel="nofollow">https://github.com/daisy-row/transact-logs</a>  you can
see all actions, by repo and maintainer, for the last 365 days.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ryjones at Nov 16, 2022 14:00 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-78022051"></span>
<p>Yes, quite possible we will want to change the project status in the
next quarter.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Nov 16, 2022 16:28 </div ></td>
</tr>
</tbody>
</table>




