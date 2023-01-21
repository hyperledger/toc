---
layout: default
title: 2022 Q2 Hyperledger Grid
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q2 Hyperledger Grid

Created by Shannyn Telander, last modified by Angelo De Caro on Jul 21, 2022

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
1.  master → main: Yes
2.  slave → replicas: N/A
3.  blacklist → denylist: N/A
4.  whitelist → allowlist: Yes
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages?  </span> </span> The documentation
is inclusive but the statement has not been added. <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);"></span> </span>

# Questions/Issues for the TSC

-   Grid's documentation/website (
<a href="https://grid.hyperledger.org/" class="external-link" rel="nofollow">https://grid.hyperledger.org/</a> ) is difficult to
find starting from
<a href="https://www.hyperledger.org/" class="external-link" rel="nofollow">https://www.hyperledger.org/</a> . 

# Releases

-   Grid 0.3.3 - 4/1/2022

# Overall Activity in the Past Quarter

Continued work on the design and began implementation of components for
the 0.4 release. This includes a batch submitter, which submits batches
to the DLT, and a queuer for this component to decide which batches the
submitter will claim. A DLT monitor component will track the status of a
submitted batch. Also, the REST API is undergoing redesign to support
submitting batches as JSON. The batch store has also been designed to be
updated to support all of these components. 

The main source of asynchronous engagement is now on Discord, while RFC
PRs remain.

# Current Plans

Current work is focused on implementing batch tracking within Grid. The
main goal of this work is to make interaction with the DLTs simpler and
more familiar for any user. Batch tracking within Grid maintains a
robust history of a batch’s lifecycle. Overall, batch tracking includes
several components that will oversee the submission of batches as well
as monitor a batch after it has been submitted to a DLT. This
functionality is planned for the Grid 0.4 release. 

# Maintainer Diversity

Maintainers are the same as the previous quarter.

# Contributor Diversity

Contributor diversity remains steady with previous quarters, with some
share of the project's overall diversity coming from non-developer
participation in their areas of expertise. 

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors. 

There were a total of 5 contributors in the last quarter.

# Additional Information

Insights from February 25th 2022 to May 23rd 2022

  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222022-02-25T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-05-23T05:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard;subTab=technical?time=%7B%22from%22:%222022-02-25T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-05-23T05:00:00.000Z%22%7D</span></a>

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

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 24-May-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62253936"></span>
<p><a href="https://wiki.hyperledger.org/display/~satelander" class="confluence-userlink user-mention" data-username="satelander" data-linked-resource-id="13865151" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Shannyn Telander</a></p>
<p>&gt; and a queuer for this component to decide which batches the
submitter will claim</p>
<p>Do you happen to have some more information about the implementation
specifics of the queuer here? As-in, is it an in-memory queue in a
single process or is it something much more robust like an entire Kafka
deployment? (I'm just curious)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by Peter Somogyvari at May 24, 2022 15:34 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62253954"></span>
<p>Certainly! The queuing component will look into Grid's database to
ascertain which batch's still need to be submitted to a DLT, basically.
It's one of the more simple components to the batch submitter, as it's
main concern is to determine which batches need to be submitted or
re-submitted. The queuer will produce a list/iterator of the items it
finds in the DB to be fed to the submitter and sent off to the backend
DLT. We have some design documents concerning these components on the
community section of the Grid site. You can find more information on the
queuing strategies here:  <a href="https://grid.hyperledger.org/community/planning/batch_queuer_strategies.html" class="external-link" rel="nofollow">https://grid.hyperledger.org/community/planning/batch_queuer_strategies.html</a>
. And the planning document for the batch submitter gives information on
how all of the sub-components (including the queuer) interact:  <a href="https://grid.hyperledger.org/community/planning/batch_submitter.html" class="external-link" rel="nofollow">https://grid.hyperledger.org/community/planning/batch_submitter.html</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by satelander at May 24, 2022 18:15 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62254056"></span>
<p>Please, list the maintainers and their affiliations, or at least the
affiliations. The info on contributors is great.</p>
<p>Thanks.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at May
25, 2022 13:58 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62254200"></span>
<p><a href="https://wiki.hyperledger.org/display/~satelander" class="confluence-userlink user-mention" data-username="satelander" data-linked-resource-id="13865151" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Shannyn Telander</a> –
Thanks for flagging that the Grid documentation is hard to find from the
Hyperledger site.  We welcome feedback like this so we can make the site
better.  I did share this feedback with our designer and she
incorporated it into the work she's done on creating new designs for the
project content on the site.  You can see the mockups she's done at: <a href="https://wiki.hyperledger.org/display/TF/Strawman+Proposal">Strawman
Proposal</a> .  If you have feedback on those mockups, feel free to
comment on that wiki page or if you'd like to talk through them with me
I'd be happy to find time to review these with you and discuss them on a
call.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at May 26, 2022 14:58 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62254212"></span>
<p>Great, we will take a look at the mockups and send on any feedback!
Thank you  <img src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /> </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by satelander at May 26, 2022 16:17 </div ></td>
</tr>
</tbody>
</table>




