---
layout: default
title: 2021 Q3 Hyperledger Explorer
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Explorer

Created by jeeva sang, last modified by Troy Ronda on Nov 04, 2021

# Project Health

<span style="color: rgb(23,43,77);text-decoration: none;">Project health
is green. </span> <span style="color: rgb(23,43,77);text-decoration: none;"> We use all of the
following to help keep project health green. Questions asked via rocket
chat are being answered on time. For greater efficiency in this regard,
the FAQ page is updated with every release. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yet to verify</span>

# Questions/Issues for the TSC

None

# Releases

<span style="color: rgb(23,43,77);">Releases this quarter: </span>

-   v1.1.7 - July 05, 2021
-   v1.1.8 - August 16, 2021

<span style="color: rgb(23,43,77);">v1.1.7 added bug fixes: </span>

Bug Fixes and Updates

-   <a href="https://jira.hyperledger.org/browse/BE-876" class="external-link" rel="nofollow" style="text-decoration: none;">BE-876</a> Stop unnecessary discovery
request (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/255" class="external-link" rel="nofollow" style="text-decoration: none;">#255</a> )
-   Bugfix: tailing ampersand sign prevents container from restarting (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/254" class="external-link" rel="nofollow" style="text-decoration: none;">#254</a> )
-   <a href="https://jira.hyperledger.org/browse/BE-857" class="external-link" rel="nofollow" style="text-decoration: none;">BE-857</a> Change invoking function
of lifecycle scc to allow non-admin client access (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/252" class="external-link" rel="nofollow" style="text-decoration: none;">#252</a> )
-   Bugfix: timeout error crashing explorer (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/253" class="external-link" rel="nofollow" style="text-decoration: none;">#253</a> )
-   Bugfix: disable enableAuthentication auth auto login using wrong
network key issue (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/250" class="external-link" rel="nofollow" style="text-decoration: none;">#250</a> )

<span style="color: rgb(23,43,77);">v1.1.8 added bug fixes: </span>

Bug Fixes and Updates

-   BE-880 Fix incorrect multi-process logging (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/260" class="external-link" rel="nofollow" style="text-decoration: none;">#260</a> )
-   docs: add code snippet for admin cert modification (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/257" class="external-link" rel="nofollow" style="text-decoration: none;">#257</a> ) (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/258" class="external-link" rel="nofollow" style="text-decoration: none;">#258</a> )



# Overall Activity in the Past Quarter

The project has released for  <span style="color: rgb(23,43,77);">bug
fixes </span>



# Current Plans

-   Add more information on the Hyperledger Fabric network to get more
insight from data
-   Endorsement Policy
-   Metrics exposed by each peer via Prometheus

-   Raise Explorer to the powerful next level Ledger Data Query
Platform 

-   -   Track historical operations for any specific state
-   Automatically analyzing schema of the ledger state

-   Continue on bug fixes, help community in configuring HLExplorer and
troubleshooting

-   Integrate the additional features mentioned in the "Contributor
Diversity" section into Explorer



# Maintainer Diversity

<span style="color: rgb(23,43,77);">No new maintainers were added. We
really need the community to come forward and contribute. </span>

<span style="color: rgb(23,43,77);">Please find here the maintainers
list.  <a href="https://github.com/hyperledger/blockchain-explorer/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow" style="text-decoration: none;">https://github.com/hyperledger/blockchain-explorer/blob/master/MAINTAINERS.md</a></span>



# Contributor Diversity

The current main contributors are from DTCC and Fujitsu. We have 3
unique contributors on   <a href="https://github.com/hyperledger/blockchain-explorer/graphs/contributors?from=2021-06-01&amp;to=2021-10-30&amp;type=c" class="external-link" rel="nofollow">Github</a> <a href="https://jira.hyperledger.org/issues/?jql=project%20%3D%20BE%20AND%20created%20%3E%3D%202020-08-25%20AND%20created%20%3C%3D%202020-11-30%20ORDER%20BY%20reporter%20ASC%2C%20priority%20DESC%2C%20updated%20DESC" class="external-link" rel="nofollow" style="text-decoration: none;"><span>  </span></a> in this quarter.

And we had some proposals for Hyperledger Explorer as below:

-   **New contributions**
-   EasyDoser
-   This is the outcome of one of the Hyperledger Internship
programs. The integration of this feature into Explorer will
offer more visibility of the network to users.
-   <a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=29035323" rel="nofollow" style="text-decoration: none;">Ease endorsement
operations for Hyperledger based products (EasyDoser)</a>
-   LedgerDataRefiner
-   Fujitsu Lab. has proposed integrating their open-sourced
ledger data analytics tool into Explorer. We have started
the discussion on how to proceed with this contribution.
-    
<a href="https://github.com/FujitsuLaboratories/Ledger-Data-Refiner" class="external-link" rel="nofollow" style="text-decoration: none;">https://github.com/FujitsuLaboratories/Ledger-Data-Refiner</a>
-   WIP contributions
-   <a href="https://github.com/litong01/minifabric" class="external-link" rel="nofollow" style="text-decoration: none;">minifab</a>
-   This project is offering Hyperledger Explorer support as one
of their features and we think it will be a good mutual
reference. 
-   <a href="https://github.com/saanvijay/hyperledger-explorer-made-easy" class="external-link" rel="nofollow" style="text-decoration: none;">hyperledger-explorer-made-easy</a>
-   This is a kind of utility tool for the easy setup of
Hyperledger Explorer. After evaluating this tool and having
a consensus for merging it into the Explorer repo within the
team, we might get it included in Explorer as one of the
official features.



# Additional Information

<span style="color: rgb(23,43,77);text-decoration: none;">The insight
chart can be found at   </span> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fexplorer/dashboard" class="external-link" rel="nofollow" style="text-decoration: none;"><span style="color: rgb(23,43,77);">Explorer </span> stats for the last
quarter</a> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fcello/dashboard;subTab=technical?time=%7B%22from%22:%222020-08-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-11-01T07:00:00.000Z%22%7D" class="external-link" rel="nofollow" style="text-decoration: none;text-align: left;">.</a>

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>






