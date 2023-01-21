---
layout: default
title: 2022 Q3 Hyperledger Grid
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Grid

Created by Shannyn Telander, last modified by Artem Barger on Sep 24, 2022

Hyperledger Grid: <a href="https://www.hyperledger.org/projects/grid" class="external-link" rel="nofollow"><span>https://www.hyperledger.org/projects/grid</span></a>  

# Project Health

Health is good. Roadmap items for release 0.4 are currently in
development. 

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
1.  master → main Yes
2.  slave → replicas N/A
3.  blacklist → denylist N/A
4.  whitelist → allowlist Yes
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? The statement has not been added.</span> </span>

# Questions/Issues for the TSC

No issues.

# Releases

-   Grid 0.3.5 - 5/29/2022

# Overall Activity in the Past Quarter

Work continues on the implementation of components for batch-tracking
within Grid. Multiple new components will be added to augment the
process of submitting a batch and overseeing its lifecycle. Allowing
batches to be submitted in plain JSON will make integrations simpler for
Grid. 



Additionally, began work on an RFC for the Grid Document smart contract.
Grid Document is a simple filesystem-like smart contract that will
enable users to store and share files within Grid. 



The main source of asynchronous engagement is on Discord and RFC PRs
remain. 

# Current Plans

Current work is focused on batch tracking components within Grid for the
next release, 0.4, and designing the Grid Document smart contract. 

# Maintainer Diversity

Maintainers are the same as the previous quarter. Current maintainers
are:



<table class="confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd"><p><span>Name </span></p></td>
<td class="confluenceTd"><p><span>Github </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Amelia Bradley </span></p></td>
<td class="confluenceTd"><p><span>ameliabradley </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Andi Gunderson </span></p></td>
<td class="confluenceTd"><p><span>agunde406 </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Chris Eckhardt </span></p></td>
<td class="confluenceTd"><p><span>cleckhardt </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Dan Middleton </span></p></td>
<td class="confluenceTd"><p><span>dcmiddle </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Darian Plumb </span></p></td>
<td class="confluenceTd"><p><span>dplumb94 </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Dave Cecchi </span></p></td>
<td class="confluenceTd"><p><span>davececchi </span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Davey Newhall </span></p></td>
<td class="confluenceTd"><p><span>dnewh </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>James Mitchell </span></p></td>
<td class="confluenceTd"><p><span>jsmitchell </span></p></td>
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
<td class="confluenceTd"><p><span>Ryan Banks </span></p></td>
<td class="confluenceTd"><p><span>RyanLassigBanks </span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Ryan Beck-Buysse </span></p></td>
<td class="confluenceTd"><p><span>rbuysse </span></p></td>
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

Contributor diversity remains steady with previous quarters, with some
share of the project's overall diversity coming from non-developer
participation in their areas of expertise. 

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors. 



There were a total of 7 contributors in the last quarter.

# Additional Information

Insights from May 23rd 2022 to August 25th 2022

  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222022-05-23T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-08-25T05:00:00.000Z%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222022-05-23T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-08-25T05:00:00.000Z%22%7D</a>

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

<span class="placeholder-inline-tasks"> 26-Aug-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71700960"></span>
<p>A list of corporations was part of contributor diversity.  Can you
add a similar summary to the maintainer diversity section?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by shemnon at Sep 07, 2022 16:25 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71701550"></span>
<p>The maintainers are currently employed by Bitwise IO (8), Cargill
(1), Intel (1), and unaffiliated (4). We don't list employment next to
names anymore because changes to employer doesn't change maintainer
status and has thus become orthogonal (but, we try and capture this in
the contributor section - a lot of the contributions happen by maintainers).</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Sep 23, 2022 14:57 </div ></td>
</tr>
</tbody>
</table>




