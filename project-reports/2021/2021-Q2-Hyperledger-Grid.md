---
layout: default
title: 2021 Q2 Hyperledger Grid
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Grid

Created by Andrea Gunderson, last modified by David Enyeart on Jul 29, 2021

<span style="letter-spacing: 0.0px;font-size: 24.0px;">Project Health</span>

Health is good. New functionality to support GDSN data for Grid Product
has been added. Documentation is being refined and expanded. Pike 2 has
been implemented. Purchase Order implementation continues to progress.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? no</span>

# Questions/Issues for the TSC

There are no specific issues at the moment.

# Releases

No new release, working toward a 0.2 release.

# Overall Activity in the Past Quarter

The Pike v2 RFC was approved and merged. We completed work on the new
version of the Pike smart contract. This new version includes
functionality for role delegation, updated functionality for agents and
organizations, as well as an index of alternate organization IDs.

Started work on a new version of the Product smart contract. This
includes updates to functionality around uploading new products and wh"at constitutes a Grid Product. This introduces requirements built around
the GS1 GDSN standard.

Began work towards stabilizing various Grid features.

The main source of asynchronous engagement is still the Hyperledger Ch"at <a href="https://chat.hyperledger.org/channel/grid" class="external-link" rel="nofollow"><span>#grid channel </span></a> and
RFC PRs.

# Current Plans

Reviewing and stabilizing Splinter support, database, Pike 2 and Product
GDSN features for a 0.2 release of Grid. Working towards Purchase order
design and implementation which will likely be in the 0.3 release.

# Maintainer Diversity

Maintainers remain the same as the previous quarter. There are 19
maintainers across the different repos.

# Contributor Diversity

Contributor diversity remains steady with previous quarters, with some
share of the project's overall diversity coming from non-developer
participation in their areas of expertise.

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors.

# Additional Information

Insights from February 24th 2021 to May 25th 2021

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard?time=%7B%22from%22:%222021-02-24T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-05-25T05:00:00.000Z%22%7D&amp;filter=%23%2Fdashboard%2FGit%3Fembed%3Dtrue%26_g%3D(refreshInterval:(pause:!t,value:0),time:(from:%272020-12-03T06:00:00.000Z%27,to:%272021-02-24T06:00:00.000Z%27))" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard?time=%7B%22from%22:%222021-02-24T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-05-25T05:00:00.000Z%22%7D&amp;filter=%23%2Fdashboard%2FGit%3Fembed%3Dtrue%26_g%3D(refreshInterval:(pause:!t,value:0),time:(from:%272020-12-03T06:00:00.000Z%27,to:%272021-02-24T06:00:00.000Z%27))</span></a>

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>






