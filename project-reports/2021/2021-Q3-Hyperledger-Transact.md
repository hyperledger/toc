---
layout: default
title: 2021 Q3 Hyperledger Transact
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Transact

Created by Andrea Gunderson, last modified by Gari Singh on Oct 16, 2021

# Project Health

Health is good. Work continues to focus on improving performance of SQL
database support, as well as continued work on workload tools that can
be leveraged by different distributed ledgers for performance and
stability testing.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented the Common Repository Structure in
all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? no</span>

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 20 releases. The current
release is 0.3.7. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> :
<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow"><span>https://crates.io/crates/transact/versions</span></a>

# Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion continues to be
held in RocketChat.

-   Experimental support of SQLite and Postgres merkle-radix tree has
been added. Along with state pruning.
-   An example application that uses the command family workload to
submit transactions directly to sabre was added.
-   Improved workload command rate submission to be more accurate.
-   Modified workload to handle a TooManyRequests response and slow the
submission rate until able to submit transactions again.
-   Added \`command\` as a workload type to the transact workload
subcommand.

# Current Plans

Next steps include:

-   Move Sawtooth Sabre (wasm engine) into Transact
-   Complete and stabilize SQL database support
-   Reorganization of the project's crate structure
-   Setup a documentation site to help explain/advocate the project



Future:

-   Add a next-generation smart contract API / simplified smart
contracts (cross-project with Sawtooth, in progress)
-   Further develop the Transact SDK for JavaScript

# Maintainer Diversity

The maintainer diversity currently matches that of the initial project
sponsor companies.

# Contributor Diversity

There were a total of 6 contributors in the last quarter, one more than
last quarter.

# Additional Information

Insights from  May 25th 2021 to August 25 2021

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222021-05-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-08-25T14:00:47.782Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222021-05-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-08-25T14:00:47.782Z%22%7D</span></a>

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
<td><span id="comment-56724037"></span>
<blockquote>
<p><span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow" style="text-decoration: none;">Have you implemented the
Common Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? no </span></p>
</blockquote>
<p><span style="color: rgb(23,43,77);text-decoration: none;"> <a href="https://wiki.hyperledger.org/display/~agunde" class="confluence-userlink user-mention" data-username="agunde" data-linked-resource-id="5505201" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Andrea Gunderson</a> : </span>When do you expect to implement the common repository
structure?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Aug
25, 2021 17:03 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-56724038"></span>
<p>FYI, here is the common repository structure definition: <a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">https://tsc.hyperledger.org/repository-structure.html</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Aug
25, 2021 17:09 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-56724050"></span>
<p>This question used to be specifically about repolinter, which we have
no plans to implement in our CI flow. However, the projects we are
involved with including Transact are consistent with the majority of the
repo structure doc Arnaud linked. (And have been for years, as most of
this stuff isn't new.)</p>
<p>There are a few minor deviations we don't plan to address currently:
RELEASE_NOTES.md instead of CHANGELOG, and SPDX headers (which we've
debated in the past and are not approved by our contributors which
require full header text as suggested by the license). Those are the
only deviations though AFAIK.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Aug 25, 2021 18:06 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-56724061"></span>
<p><a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a> /  <a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a>  : We need to
get the project report template updated to point to this link instead of
the one pointed to currently.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Aug
25, 2021 19:38 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-56724064"></span>
<p>done</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ryjones at Aug 25, 2021 20:08 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-56724124"></span>
<p>Hi Shawn,<br />
I brought this question up for discussion a few weeks ago. On the
`RELEASE_NOTES.md` instead of `CHANGELOG`: There was a suggestion from
the TSC to include `CHANGELOG` as a mandatory file and the contents of
this file can be a link to RELEASE_NOTES.md file. This is to have common
repository structure, still give flexibility for projects to maintain
how the information is captured.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Aug 26, 2021 13:55 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-58851813"></span>
<p>Per SPDX recommendations the full text and the SPDX headers are OK
and in fact some cases preferred.  Hyperledger Besu does full text plus
SPDX headers.</p>
<p><a href="https://spdx.github.io/spdx-spec/appendix-V-using-SPDX-short-identifiers-in-source-files/" class="external-link" rel="nofollow">https://spdx.github.io/spdx-spec/appendix-V-using-SPDX-short-identifiers-in-source-files/</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Sep 02, 2021 14:02 </div ></td>
</tr>
</tbody>
</table>




