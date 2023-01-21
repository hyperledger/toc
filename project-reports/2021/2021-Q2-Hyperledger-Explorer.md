---
layout: default
title: 2021 Q2 Hyperledger Explorer
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Explorer

Created by jeeva sang, last modified by Gari Singh on Oct 16, 2021

<a href="https://github.com/hyperledger/blockchain-explorer" class="external-link" rel="nofollow" style="text-decoration: underline;">Hyperledger Explorer</a>

# Project Health

<span style="color: rgb(23,43,77);">Project health is green. </span>
<span style="color: rgb(23,43,77);"> We use all of the following to help
keep project health green. Questions asked via rocket chat are being
answered on time. For greater efficiency in this regard, the FAQ page is
updated with every release. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? yes </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? yes </span>

# Questions/Issues for the TSC

Still, we are in incubation status only. we would like to move
from incubation to active projects. What is the procedure for promoting
this project? 

# Releases

<span style="color: rgb(23,43,77);">Releases this quarter: </span>

-   v1.1.5 - April 21, 2021
-   v1.1.6 - June 06, 2021

<span style="color: rgb(23,43,77);">v1.1.5 added features and bug fixes:</span>

New Features

-   <a href="https://jira.hyperledger.org/browse/BE-694" class="external-link" rel="nofollow" style="text-decoration: none;">BE-694</a>   Add UI link to trans (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/227" class="external-link" rel="nofollow" style="text-decoration: none;">#227</a> )
-   <a href="https://jira.hyperledger.org/browse/BE-858" class="external-link" rel="nofollow" style="text-decoration: none;">BE-858</a>   Upgrade base image of
Explorer container image (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/220" class="external-link" rel="nofollow" style="text-decoration: none;">#220</a> )
-   <a href="https://jira.hyperledger.org/browse/BE-801" class="external-link" rel="nofollow" style="text-decoration: none;">BE-801</a>   Add the steps to
configure a subdomain (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/219" class="external-link" rel="nofollow" style="text-decoration: none;">#219</a> )
-   Upgrade fabric version supported by Explorer (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/227" class="external-link" rel="nofollow" style="text-decoration: none;">#227</a> )

Bug Fixes and Updates

-   <a href="https://jira.hyperledger.org/browse/BE-862" class="external-link" rel="nofollow" style="text-decoration: none;">BE-862</a>   Fix sync error (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/228" class="external-link" rel="nofollow" style="text-decoration: none;">#228</a> )
-   Fix layout of icons on the navigation bar (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/218" class="external-link" rel="nofollow" style="text-decoration: none;">#218</a> )

<span style="color: rgb(23,43,77);">v1.1.6 added features and bug fixes:</span>

New Features

-   <a href="https://jira.hyperledger.org/browse/BE-871" class="external-link" rel="nofollow" style="text-decoration: none;">BE-871</a>   Introduce dropdown to
put together icons (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/247" class="external-link" rel="nofollow" style="text-decoration: none;">#247</a> )
-   <a href="https://jira.hyperledger.org/browse/BE-870" class="external-link" rel="nofollow" style="text-decoration: none;">BE-870</a>   display direct trans
link (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/237" class="external-link" rel="nofollow" style="text-decoration: none;">#237</a> )
-   Add typescript compilation on main. sh install (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/234" class="external-link" rel="nofollow" style="text-decoration: none;">#234</a> )
-   <a href="https://jira.hyperledger.org/browse/BE-865" class="external-link" rel="nofollow" style="text-decoration: none;">BE-865</a>  Fix Repolinter Report
Issues  (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/231" class="external-link" rel="nofollow" style="text-decoration: none;">#231</a> )

Bug Fixes and Updates

-   <a href="https://jira.hyperledger.org/browse/BE-855" class="external-link" rel="nofollow" style="text-decoration: none;">BE-855</a>   Stop unnecessary sync
process triggered by FabricEvent (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/240" class="external-link" rel="nofollow" style="text-decoration: none;">#240</a> )
-   <a href="https://jira.hyperledger.org/browse/BE-855" class="external-link" rel="nofollow" style="text-decoration: none;">BE-855</a>   Add try-catch block to
handle block in-process exception (
<a href="https://github.com/hyperledger/blockchain-explorer/pull/239" class="external-link" rel="nofollow" style="text-decoration: none;">#239</a> )

# Overall Activity in the Past Quarter

The project has released few features

-   Upgraded fabric version.
-   Upgraded the base image of the Explorer container image.
-   In UI we have added a transaction view and icon changes

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

<span style="color: rgb(23,43,77);">We've had a few spot contributors
added.  </span> <span style="color: rgb(23,43,77);">No new maintainers
were added. We really need the community to come forward and contribute.</span>

<span style="color: rgb(23,43,77);">Please find here the maintainers
list.  <a href="https://github.com/hyperledger/blockchain-explorer/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow" style="text-decoration: none;">https://github.com/hyperledger/blockchain-explorer/blob/master/MAINTAINERS.md</a></span>

# Contributor Diversity

The current main contributors are from DTCC and Fujitsu. We have 4
unique contributors on   <a href="https://github.com/hyperledger/blockchain-explorer/graphs/contributors?from=2021-01-01&amp;to=2021-06-30&amp;type=c" class="external-link" rel="nofollow">Github</a> <a href="https://jira.hyperledger.org/issues/?jql=project%20%3D%20BE%20AND%20created%20%3E%3D%202020-08-25%20AND%20created%20%3C%3D%202020-11-30%20ORDER%20BY%20reporter%20ASC%2C%20priority%20DESC%2C%20updated%20DESC" class="external-link" rel="nofollow" style="text-decoration: none;"><span>  </span></a> in this quarter.

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

<span style="color: rgb(23,43,77);">The insight chart can be found at  </span> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fexplorer/dashboard" class="external-link" rel="nofollow" style="text-decoration: none;"><span style="color: rgb(23,43,77);">Explorer </span> stats for the last
quarter</a> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fcello/dashboard;subTab=technical?time=%7B%22from%22:%222020-08-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-11-01T07:00:00.000Z%22%7D" class="external-link" rel="nofollow" style="text-decoration: none;text-align: left;">.</a>

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-51613697"></span>
<p>From the <a href="https://tsc.hyperledger.org/project-lifecycle.html" class="external-link" rel="nofollow">project lifecycle</a></p>
<blockquote>
<p><span style="color: rgb(92,89,98);">Projects seeking to graduate
from  </span> <em>Incubation </em> <span style="color: rgb(92,89,98);">must meet the criteria defined in the </span> <a href="https://tsc.hyperledger.org/project-incubation-exit.html" class="external-link" rel="nofollow" style="text-decoration: none;">Incubation Exit Criteria</a>   <span style="color: rgb(92,89,98);">document. </span></p>
</blockquote>
<p><span style="color: rgb(92,89,98);">See the following from the  <a href="https://wiki.hyperledger.org/display/TSC/TSC+Decision+Log">TSC
Decision Log</a> for example of projects that have requested moving to
Graduated status: </span></p>
<ul class="incremental">
<li><a href="https://wiki.hyperledger.org/display/TSC/Move+Besu+from+Incubation+to+Active+status">Move
Besu from Incubation to Active status</a></li>
<li><a href="https://wiki.hyperledger.org/display/TSC/Move+Hyperledger+Aries+from+Incubation+to+Active+status">Move
Hyperledger Aries from Incubation to Active status</a></li>
</ul>
<p><a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a> :
Should we re-open  <a href="https://wiki.hyperledger.org/display/TSC/Move+Hyperledger+Explorer+from+incubation+to+active+status">Move
Hyperledger Explorer from incubation to active status</a>  and have the
Explorer community update this page? Or should we have them create a new
decision log entry "Move Hyperledger Explorer from Incubation to
Graduated status"?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Jun
11, 2021 16:40 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-51613698"></span>
<p>I am in favor of creating a new page</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Jun
11, 2021 16:41 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-51613912"></span>
<p>I agree, this will give us a cleaner track record.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Jun
15, 2021 12:50 </div ></td>
</tr>
</tbody>
</table>




