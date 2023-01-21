---
layout: default
title: 2021 Q4 Hyperledger Grid
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Grid

Created by Shannyn Telander, last modified by Artem Barger on Dec 16, 2021

Hyperledger Grid: <a href="https://www.hyperledger.org/projects/grid" class="external-link" rel="nofollow"><span>https://www.hyperledger.org/projects/grid</span></a>  

# Project Health

Health is good. Finishing roadmap items for release 0.3, and roadmap
items for release 0.4 are in-progress.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">?  Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span>
1.  LICENSE - yes
2.   <a href="http://CODE_OF_CONDUCT.md" class="external-link" rel="nofollow">CODE_OF_CONDUCT.md</a> - no
3.   <a href="http://SECURITY.md" class="external-link" rel="nofollow">SECURITY.md</a> - yes
4.   <a href="http://README.md" class="external-link" rel="nofollow">README.md</a> - yes
5.   <a href="http://MAINTAINERS.md" class="external-link" rel="nofollow">MAINTAINERS.md</a> - yes
6.   <a href="http://CONTRIBUTING.md" class="external-link" rel="nofollow">CONTRIBUTING.md</a> - yes
7.  CHANGELOG - yes, but called
<a href="http://RELEASE_NOTES.md" class="external-link" rel="nofollow">RELEASE_NOTES.md</a>

# Questions/Issues for the TSC

-   There are no specific issues at the moment. 

# Releases

-   There were no releases in the past quarter.

# Overall Activity in the Past Quarter

Features enter Grid as experimental, then go through a formal review
process to stabilize them. Several features were stabilized:

-   Client
-   Rest API resources
-   Rest API Authorization support

Work towards stabilizing additional Grid features continues.



Continued work on the Purchase Order feature, including smart contract,
state-delta-export, REST API endpoints, database schema, store
implementation, etc. This includes functionality for managing a purchase
order throughout its lifecycle for agents involved in the purchasing and
selling process.



The main source of asynchronous engagement is still the Hyperledger Ch"at <a href="https://chat.hyperledger.org/channel/grid" class="external-link" rel="nofollow"><span>#grid channel </span></a> and
RFC PRs. 

# Current Plans

Current work is focused on working towards the 0.3 release. This
includes the Purchase Order and Workflow features. We are also
continuing to design and implement functionality to make integration
with external systems easier, and are planning for this functionality to
be in the 0.4 release.

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



We have had one new contributor since the last update.

# Additional Information

Insights from August 25th 2021 to November 25

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222021-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-11-25T06:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222021-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-11-25T06:00:00.000Z%22%7D</span></a>

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

<span class="placeholder-inline-tasks"> 01-Dec-2021 </span>






