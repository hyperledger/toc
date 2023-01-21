---
layout: default
title: 2022 Q1 Hyperledger Grid
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Grid

Created by Shannyn Telander, last modified by Jim Zhang on Mar 24, 2022

<span style="letter-spacing: 0.0px;"> </span> Hyperledger Grid:
<a href="https://www.hyperledger.org/projects/grid" class="external-link" rel="nofollow"><span>https://www.hyperledger.org/projects/grid</span></a>  

# Project Health

Health is good. Grid v0.3 was released and roadmap items for release 0.4
are beginning development.

# Required Information

1.  <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow"><span>Have you switched from master to main in all your
repos </span></a> ? Yes 
2.  <a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow"><span>Have you implemented repolinter.json in all your
repos </span></a> ? Yes
3.  Has your project implemented these inclusive language changes listed
below to your repo? You can optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow"><span>use the DCI Lint tool</span></a> to make this a recurring action on your repo.
1.  master → main: Yes
2.  slave → replicas: N/A
3.  blacklist → denylist: N/A
4.  whitelist → allowlist: Yes
4.  Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow"><span>Inclusive Language Statement </span></a> to
your project's documentation and/or Wiki pages?: No

# Questions/Issues for the TSC

-   Grid's documentation/website (
<a href="https://grid.hyperledger.org/" class="external-link" rel="nofollow">https://grid.hyperledger.org/</a> ) is difficult to
find starting from
<a href="https://www.hyperledger.org/" class="external-link" rel="nofollow">https://www.hyperledger.org/</a> . 

# Releases

-   Grid 0.2.3 - 12/20/2021
-   Grid 0.3.1 - 1/28/2022
-   Grid 0.3.2 - 2/3/2022

# Overall Activity in the Past Quarter

Features enter Grid as experimental, then go through a formal review
process to stabilize them. Several features were stabilized:

-   Xsd-downloader
-   Purchase-order
-   Client-reqwest
-   Data-validation
-   Workflow

Work towards stabilizing additional Grid features continues.

Completed work on version 1 of Grid Purchase Order, including smart
contract, state-delta export, REST API endpoints, database schema, store
implementation, etc. This provides functionality for managing a purchase
order throughout its lifecycle for agents involved in the purchasing and
selling process.

Continued work on the design of components for the 0.4 release. This
includes a batch submitter, which submits batches to the DLT, and a
queuer for this component that decides which batches the submitter will
claim. A DLT monitor component will track the status of a submitted
batch. Also, the REST API is undergoing redesign to support submitting
batches as JSON. The batch store has also been designed to be updated to
support all of these components. 

The main source of asynchronous engagement has been moved to Discord,
while RFC PRs remain.

# Current Plans

Current work is focused on design and development for batch tracking
within Grid. The main goal of this work is to make interaction with the
DLT simpler and more familiar for the user, as they would now be able to
submit transactions to the REST API using simple JSON. Overall, batch
tracking includes several components that will oversee the submission of
batches as well as monitoring the batch through its lifecycle, from
submitting the changes to the changes being committed to state. This
functionality is planned for the 0.4 release.

# Maintainer Diversity

We have added one maintainer, Lee Bradley, since the previous update.
There are 20 maintainers across the different repos. 

# Contributor Diversity

Contributor diversity remains steady with previous quarters, with some
share of the project's overall diversity coming from non-developer
participation in their areas of expertise. 

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors. 

We have had one new contributor since the last update.

# Additional Information

Insights from November 25th 2021 to February 25th 2022

  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222021-11-25T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-02-25T06:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222021-11-25T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-02-25T06:00:00.000Z%22%7D</span></a>

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 23-Feb-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62241065"></span>
<p><a href="https://wiki.hyperledger.org/display/~satelander" class="confluence-userlink user-mention" data-username="satelander" data-linked-resource-id="13865151" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Shannyn Telander</a> –
That's good feedback about the Grid documentation being hard to find
from the Hyperledger site.  I'm tagging <a href="https://wiki.hyperledger.org/display/~b.thomas" class="confluence-userlink user-mention" data-username="b.thomas" data-linked-resource-id="62238877" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ben Thomas</a> on this so
he's aware.  We're starting to think about updates to make to the site
this year and this is good input to have for that process.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Feb 23, 2022 17:55 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62243338"></span>
<p>I believe this is the result of a lack of a consistent policy and
practice with regard to where documentation is found across projects.
The TSC should discuss this.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Mar
10, 2022 08:12 </div ></td>
</tr>
</tbody>
</table>




