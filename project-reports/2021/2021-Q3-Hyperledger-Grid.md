---
layout: default
title: 2021 Q3 Hyperledger Grid
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Grid

Created by Darian Plumb, last modified by Gari Singh on Oct 16, 2021

# Project Health

<span class="TextRun SCXW169106498 BCX0" style="color: windowtext;text-decoration: none;"> <span class="NormalTextRun SCXW169106498 BCX0">Health is good. </span> <span class="NormalTextRun SCXW169106498 BCX0"> Finished roadmap items for
release 0.2, and roadmap items for release 0.3 are in-progress
(including Purchase Order). </span> </span> <span class="EOP SCXW169106498 BCX0" style="color: windowtext;">  </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented the Common Repository Structure in
all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? No </span>

# Questions/Issues for the TSC

<span class="TextRun SCXW232517875 BCX0" style="color: rgb(0,0,0);text-decoration: none;"> <span class="NormalTextRun SCXW232517875 BCX0">There are no specific issues at the moment. </span> </span> <span class="EOP SCXW232517875 BCX0" style="color: rgb(0,0,0);">  </span>

# Releases

<span class="TextRun SCXW35360809 BCX0" style="color: rgb(0,0,0);text-decoration: none;"> <span class="NormalTextRun SCXW35360809 BCX0">Grid 0.2 is released. </span></span>

# Overall Activity in the Past Quarter

The Product v2 functionality was added and the feature was stabilized.
This new version includes functionality for adding products based around
the GS1 GDSN standard.  

Several features were stabilized:  

-   Location  
-   Pike  
-   Product  
-   Schema  
-   Postgres support  
-   Sqlite support  

Started work on the Purchase Order smart contract. This includes
functionality for managing a purchase order throughout its lifecycle for
agents involved in the purchasing and selling process.  

Continued work on the Workflow functionality. This module contains
functionality for managing state transitions within smart contracts th"at map to steps in a business workflow.  

Work towards stabilizing Grid features continues.  

The main source of asynchronous engagement is still the Hyperledger
Chat  <a href="https://chat.hyperledger.org/channel/grid" class="external-link" rel="nofollow"><span>#grid channel </span></a>
 and RFC PRs.  

# Current Plans

<span class="TextRun SCXW186510513 BCX0" style="color: rgb(0,0,0);text-decoration: none;"> <span class="NormalTextRun SCXW186510513 BCX0">Current </span> <span class="NormalTextRun SCXW186510513 BCX0">   </span> <span class="NormalTextRun SCXW186510513 BCX0">work is focused on working </span> <span class="NormalTextRun SCXW186510513 BCX0">towards Purchase
  </span> <span class="NormalTextRun SCXW186510513 BCX0">O </span> <span class="NormalTextRun SCXW186510513 BCX0">rder design and implementation
which will be in the 0.3 release. </span> <span class="NormalTextRun SCXW186510513 BCX0">   We are also continuing  </span> <span class="NormalTextRun SCXW186510513 BCX0">to  </span> <span class="NormalTextRun SCXW186510513 BCX0">design </span> <span class="NormalTextRun SCXW186510513 BCX0">   and   </span> <span class="NormalTextRun SCXW186510513 BCX0">implement   </span> <span class="NormalTextRun SCXW186510513 BCX0">functionality to make
integration with external systems easier. </span> </span> <span class="EOP SCXW186510513 BCX0" style="color: rgb(0,0,0);">  </span>

# Maintainer Diversity

<span class="TextRun SCXW233584100 BCX0" style="color: windowtext;text-decoration: none;"> <span class="NormalTextRun SCXW233584100 BCX0">Maintainers remain the same as
the previous quarter. There are 19 maintainers across the different
repos. </span> </span> <span class="EOP SCXW233584100 BCX0" style="color: windowtext;">  </span>

# Contributor Diversity

Contributor diversity remains steady with previous quarters, with some
share of the project's overall diversity coming from non-developer
participation in their areas of expertise.  

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors.  

We have two new contributors since the last update.  

# Additional Information

Insights from May 25th 2021 to August 25th 2021  

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222021-05-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-08-25T13:55:32.575Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222021-05-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-08-25T13:55:32.575Z%22%7D</span></a>  

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-56724035"></span>
<blockquote>
<p><span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow" style="text-decoration: none;">Have you implemented the
Common Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? No </span></p>
</blockquote>
<p><a href="https://wiki.hyperledger.org/display/~agunde" class="confluence-userlink user-mention" data-username="agunde" data-linked-resource-id="5505201" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Andrea Gunderson</a> When
do you expect to implement the common repository structure?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Aug
25, 2021 16:59 </div ></td>
</tr>
</tbody>
</table>




