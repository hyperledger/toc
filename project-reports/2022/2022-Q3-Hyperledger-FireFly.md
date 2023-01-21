---
layout: default
title: 2022 Q3 Hyperledger FireFly
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger FireFly

Created by Ray Chen, last modified by Jim Zhang on Nov 03, 2022

<span style="letter-spacing: 0.0px;"> </span>

# Project Health

We achieved a significant milestone this quarter with the release of
Hyperledger FireFly 1.1.

This release makes it possible for FireFly users to deploy multiple
blockchain applications connecting to multiple chains, including leading
public blockchains like Ethereum, Polygon, Avalanche, Optimism, BNB
Chain, Arbitrum, Moonbeam, Fantom and more.



**Hyperledger FireFly 1.1 Highlights**

-   Web3 Gateway Mode: Use Web3 Gateway Mode to connect to public
blockchains including Ethereum, Polygon, Avalanche, Optimism, BNB
Chain, Arbitrum, Moonbeam, and Fantom.
-   Public Blockchain Support: Leverage new tools to simplify public use
cases, including FireFly Transaction Manager, FireFly Signer, and
Enhanced Gateway Support.
-   Consortium Mode: Use Consortium Mode to build multi-party business
networks where data needs to be agreed to and shared among the
group.
-   Multi-tenant Support: Use new namespace isolation to segregate and
configure API security, identity broadcasting, on-chain data
indexing, and data sharing.
-   Multiple Instances of Plugins: Use several instances of each type of
plugin in a single FireFly node.
-   Pluggable API Security: Enable API Security at several levels and on
any service or namespace.



We've also seen an uptick in new community members this quarter
participating in discussions in Discord with 87 people versus 71 the
previous quarter.

Contributors are very active in the project and since June, excluding
merges, we’ve had 18 authors push 513 commits to main.

There are currently 586k lines of code for Hyperledger FireFly across 19
repositories, with a total of 6.4K commits to date.

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
make this a recurring action on your repo. Yes </span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? Yes</span> </span>

# Questions/Issues for the TSC

No questions for the TSC

# Releases

July:

<a href="https://github.com/hyperledger/firefly/releases/tag/v1.0.3" class="external-link" rel="nofollow">FireFly 1.0.3</a>

August:

<a href="https://github.com/hyperledger/firefly/releases/tag/v1.0.4" class="external-link" rel="nofollow">FireFly 1.0.4</a>

September:

<a href="https://github.com/hyperledger/firefly/releases/tag/v1.1.0" class="external-link" rel="nofollow">FireFly 1.1.0</a>

The full list of releases can be found at:
<a href="https://github.com/hyperledger/firefly/releases" class="external-link" rel="nofollow">https://github.com/hyperledger/firefly/releases</a>

# Overall Activity in the Past Quarter

The Discord is very active and project maintainers answer questions
regularly. Some metrics for the last 90 days of activity.

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd" style="text-align: left;"><p><strong>Dimension</strong></p></td>
<td class="confluenceTd" style="text-align: left;"><p><strong>Link to
Insights</strong></p></td>
</tr>
<tr class="even">
<td class="confluenceTd" style="text-align: left;"><p><span>PR
Activities </span></p></td>
<td class="confluenceTd" style="text-align: left;"><p><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=pull-request-management%2Fgithub-pr%2Foverview" class="external-link" rel="nofollow" style="text-decoration: none;"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=pull-request-management%2Fgithub-pr%2Foverview</span></a></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd" style="text-align: left;"><p><span>Contributor
Strength </span></p></td>
<td class="confluenceTd" style="text-align: left;"><p><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;quicktime=time_filter_3M" class="external-link" rel="nofollow" style="text-decoration: none;"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;quicktime=time_filter_3M</span></a></p></td>
</tr>
<tr class="even">
<td class="confluenceTd" style="text-align: left;"><p><span>Commit
Activities </span></p></td>
<td class="confluenceTd" style="text-align: left;"><p><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=source-control%2Fcommits%2Foverview" class="external-link" rel="nofollow" style="text-decoration: none;"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffirefly/dashboard;subTab=technical;v=source-control%2Fcommits%2Foverview</span></a></p></td>
</tr>
</tbody>
</table>

# Current Plans

-   Active: Enhanced connector framework structure 
-   active development on new public chain connectors for Ethereum
and Bitcoin
-   Active: Namespace isolation
-   Allows single FireFly SuperNode to talk to multiple blockchains 
-   Major step towards multi-tenancy support
-   Active: New operation modes for Gateway and Consortium 
-   Explicit multi-chain support
-   Active: Revamped docs site
-   Major updates throughout for v1.1
-   Public chain support instructions
-   Top level version toggle
-   Multi-language support starting with Chinese
-   Automated API and object reference sections
-   Queued: Enhanced API Security model

Please see the GitHub project board for our most updated plans:
<a href="https://github.com/orgs/hyperledger/projects/4/views/7" class="external-link" rel="nofollow">https://github.com/orgs/hyperledger/projects/4/views/7</a>

# Maintainer Diversity

<span style="color: rgb(23,43,77);">No new maintainers in this quarter.
10/10 maintainers are from Kaleido.  <a href="https://github.com/orgs/hyperledger/teams/firefly-committers/members" class="external-link" rel="nofollow" style="text-decoration: none;">https://github.com/orgs/hyperledger/teams/firefly-committers/members</a></span>

# Contributor Diversity

Contributions in Q3 including code, documentation, or other
contributions:

Active contributors from Kaleido: 11

Active contributors from other organizations: 7

# Additional Information

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

<span class="placeholder-inline-tasks"> 23-Sep-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71701571"></span>
<p>For maintainer diversity, can you comment on organizational diversity
across maintainers?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Sep
23, 2022 18:31 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71702285"></span>
<p>This has been answered with: " <span style="color: rgb(23,43,77);">10/10 maintainers are from Kaleido</span>"</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Oct
13, 2022 14:07 </div ></td>
</tr>
</tbody>
</table>




