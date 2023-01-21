---
layout: default
title: 2021 Q4 Hyperledger FireFly
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger FireFly

Created by Nickolaus John Guyer, last modified by Kamlesh Nagware on Jan 27, 2022

Hyperledger FireFly 
<a href="https://github.com/hyperledger/firefly" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly</a>

# Project Health

Hyperledger FireFly continues to make progress toward v1.0

<table class="confluenceTable">
<tbody>
<tr class="header">
<th class="confluenceTh">Dimension</th>
<th class="confluenceTh">Link to Insights</th>
</tr>

<tr class="odd">
<td class="confluenceTd">Commit Activities</td>
<td class="confluenceTd"><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=source-control%2Fcommits%2Foverview" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=source-control%2Fcommits%2Foverview</a></td>
</tr>
<tr class="even">
<td class="confluenceTd">PR Activities</td>
<td class="confluenceTd"><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=pull-request-management%2Fgithub-pr%2Foverview" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=pull-request-management%2Fgithub-pr%2Foverview</a></td>
</tr>
<tr class="odd">
<td class="confluenceTd">Contributor Strength</td>
<td class="confluenceTd"><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;quicktime=time_filter_3M" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;quicktime=time_filter_3M</a></td>
</tr>
</tbody>
</table>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? Yes
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes</span>

# Questions/Issues for the TSC

-   None

# Releases

-   Our release process and versioning schemes were established this
quarter (documented in the <a href="https://hyperledger.github.io/firefly/maintainers/maintainers.html" class="external-link" rel="nofollow">Maintainer Docs</a> ), and all
firefly-\* repos are following semantic versioning now. 
-   Recent releases can be found on the Release page: 
<a href="https://github.com/hyperledger/firefly/releases" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly/releases</a>
-   Each FireFly microservice may have an independent release
schedule/version, and releases for each service can be found in
their respective repos
-   While we are striving to keep breaking changes to a minimum, there
is a possibility that some releases will include breaking changes
before the project reaches v1.0

<span style="font-size: 24.0px;letter-spacing: -0.01em;">Overall
Activity in the Past Quarter </span>

The team continues to make good progress toward
<a href="https://github.com/hyperledger/firefly/issues/117" class="external-link" rel="nofollow">v1.0</a> , including adding several
major new pieces of work:

-   Tokens (fungible and non-fungible)
-   Custom smart contract support (in progress)
-   Performance testing and tuning

The <a href="https://github.com/hyperledger/firefly-fir" class="external-link" rel="nofollow">FireFly Improvement Request
(FIR)</a>  process was established earlier this quarter and the first
FIR is currently in progress for Custom Smart Contracts.

# Current Plans

<a href="https://github.com/hyperledger/firefly/issues/117" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly/issues/117</a>

The v1.0 release remains the primary focus of the team

# Maintainer Diversity

<a href="https://github.com/orgs/hyperledger/teams/firefly-committers/members" class="external-link" rel="nofollow">https://github.com/orgs/hyperledger/teams/firefly-committers/members</a>

8 of 8 maintainers are from Kaleido.

# Contributor Diversity

<a href="https://github.com/hyperledger/firefly/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly/graphs/contributors</a>

<a href="https://github.com/hyperledger/firefly-ethconnect/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly-ethconnect/graphs/contributors</a>

<a href="https://github.com/hyperledger/firefly-fabconnect/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly-fabconnect/graphs/contributors</a>

<a href="https://github.com/hyperledger/firefly-tokens-erc1155/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly-tokens-erc1155/graphs/contributors</a>

<a href="https://github.com/hyperledger/firefly-dataexchange-https/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly-dataexchange-https/graphs/contributors</a>

<a href="https://github.com/hyperledger/firefly-cli/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly-cli/graphs/contributors</a>

<a href="https://github.com/hyperledger/firefly-ui/graphs/contributors" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly-ui/graphs/contributors</a>

20 committers - 55% from Kaleido

# Additional Information

Technical metrics from 9/16/2021 to 12/16/2021

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical?time=%7B%22from%22:%222021-09-16T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-12-16T05:00:00.000Z%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical?time=%7B%22from%22:%222021-09-16T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-12-16T05:00:00.000Z%22%7D</a>

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

<span class="placeholder-inline-tasks"> 09-Dec-2021 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62230901"></span>
<p>Looks like you have an old template. Two things that have
changed:</p>
<ol class="incremental">
<li>In the beginning, the second question is no longer about repolinter,
but " <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);"> <a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?" </span></li>
<li><span style="color: rgb(23,43,77);text-decoration: none;">At the
bottom, the TSC member list that is provided is out of date.</span></li>
</ol>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Dec
09, 2021 21:26 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62230903"></span>
<p>I updated the TSC list</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Dec
09, 2021 21:28 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62230908"></span>
<p>Oops. I copied the most recent Fabric report. Thanks for updating the
list.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nguyer at Dec
09, 2021 21:37 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62231524"></span>
<p>Thanks for the quarterly report!  You may want to focus more on the
community in the "Project Health" category–that's what it was meant to
address.  </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Dec
16, 2021 06:35 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62231555"></span>
<p><a href="https://wiki.hyperledger.org/display/~nguyer" class="confluence-userlink user-mention" data-username="nguyer" data-linked-resource-id="51612542" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nickolaus John Guyer</a>
Another great way to visualize a project's health is through LFX
insights portal  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;quicktime=time_filter_3M" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;quicktime=time_filter_3M</a>
.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Dec 16, 2021 13:58 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62231563"></span>
<p>thanks for suggesting that <a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> , I added a
link to the technical metrics dashboard in a new section "Additional
Information". hope that's ok with you  <a href="https://wiki.hyperledger.org/display/~nguyer" class="confluence-userlink user-mention" data-username="nguyer" data-linked-resource-id="51612542" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nickolaus John Guyer</a>
:-)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jimthematrix
at Dec 16, 2021 14:20 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62231598"></span>
<p><a href="https://wiki.hyperledger.org/display/~nguyer" class="confluence-userlink user-mention" data-username="nguyer" data-linked-resource-id="51612542" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nickolaus John Guyer</a>
what's the plan for community engagement to increase maintainer
diversity?  </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by knagware9 at Dec 16, 2021 15:12 </div ></td>
</tr>
</tbody>
</table>




