---
layout: default
title: 2020 Q3 Hyperledger Grid
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Grid

Created by Andrea Gunderson, last modified by Gari Singh on Sep 17, 2020

# Project

<span style="letter-spacing: 0.0px;">
<a href="https://www.hyperledger.org/projects/grid" class="external-link" rel="nofollow">Hyperledger Grid
https://www.hyperledger.org/projects/grid</a> </span>

# Project Health

<span class="TextRun SCXW60004811 BCX0" style="color: rgb(0,0,0);">
<span class="NormalTextRun SCXW60004811 BCX0">Health is good. Focus and
discussion is currently on adding business capabilities. Work is
underway to define a GS1-compatible Location capability which will be
leveraged by the other higher-order capabilities in the future. Other
features are actively being discussed. </span> </span> <span class="EOP SCXW60004811 BCX0" style="color: rgb(0,0,0);">  </span>

# Questions/Issues for the TSC

<span class="TextRun SCXW176884302 BCX0" style="color: rgb(0,0,0);">
<span class="NormalTextRun SCXW176884302 BCX0">There are no specific
issues   </span> <span class="NormalTextRun AdvancedProofingIssueV2 SCXW176884302 BCX0">at the
moment </span> <span class="NormalTextRun SCXW176884302 BCX0">. </span></span> <span class="EOP SCXW176884302 BCX0" style="color: rgb(0,0,0);">  </span>

# Releases

<span class="TextRun SCXW134541264 BCX0" style="color: rgb(0,0,0);">
<span class="NormalTextRun SCXW134541264 BCX0">No prior releases.</span> </span> <span class="EOP SCXW134541264 BCX0" style="color: rgb(0,0,0);">  </span>

# Overall Activity in the Past Quarter

Much activity has focused on the Location feature. Work included writing
and reviewing the Locations RFC and beginning development on the
Locations smart contract.  

Work was also started on updating Grid database code with modular
patterns designed to allow the easy support of multiple database
backends. PostgreSQL and SQLite are the first two to be supported.  

The Grid website got a fresh theme and the infrastructure to
build/publish it has been simplified to encourage contributions.  

The main source of asynchronous engagement is still the Hyperledger
Chat  <a href="https://chat.hyperledger.org/channel/grid" class="external-link" rel="nofollow"><span>#grid channel </span></a>
 and RFC PRs. Grid community meetings have resumed, with a schedule of
one every 4 weeks. Work on grooming the backlog of issues and reflecting
current work on Grid's project board has been a priority.  

# Current Plans

Adding support for storing locations via a smart contract with a focus
on supporting GS1 locations.  

Refactoring and moving the daemon database module into the Grid SDK and
adding  Sqlite  support as well as in-memory implementations to
facilitate testing.  

Publishing RFCs outlining support for inventory functionality.  

# Maintainer Diversity

The list of active maintainers for Hyperledger Grid currently remains
unchanged. There are 18 maintainers across the different repos.   

We anticipate adding additional maintainers as contributions increase
for areas currently in development.   

# Contributor Diversity

Several new subject-matter experts have joined as contributors, which
has increased the range of knowledge and thought leadership within the
community.  

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors.  

# Additional Information

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






