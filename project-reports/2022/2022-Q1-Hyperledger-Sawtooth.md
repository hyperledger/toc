---
layout: default
title: 2022 Q1 Hyperledger Sawtooth
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Sawtooth

Created by Andrea Gunderson, last modified by Jim Zhang on Mar 24, 2022

<span style="letter-spacing: 0.0px;"> Hyperledger Sawtooth
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow"><span>https://sawtooth.hyperledger.org/ </span></a></span>

# Project Health

In the last quarter work a number of releases have been made including
last quarter's stabilized features. Work has begun on moving Sawtooth
Sabre into the Transact Library. Design work has begun on next
generation block publishing, block management and pending batch queue,
as part of the Sawtooth 2 effort.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes</span>
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

No new issues.

# Releases

-   Sawtooth Library v0.7.0 - 11/29/21
-   Sawtooth Library v0.7.1 - 11/29/21
-   Sawtooth Library v0.7.2 - 12/13/21
-   Sawtooth Sabre v0.8.1 - 11/29/21

# Overall Activity in the Past Quarter

Design and implementation of core pieces of Sawtooth 2 has started, with
the Sawtooth Library being the primary area of activity. The components
being built are intended for general use when building distributed
ledgers in Rust. This includes replacing traditionally non-library code
like Sawtooth's journal concepts with similar but generalized library
versions.

Sawtooth's website (
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow">https://sawtooth.hyperledger.org/</a> ) is undergoing
renovation, and a "refresh" branch in the sawtooth-docs repository
contains the new site. The site is being converted from sphinx-doc rst
files to Jekyll markdown files, with a new theme and navigation. The
amount of existing documentation for Sawtooth makes this a very large
undertaking.

The community continues to discuss Sawtooth-related issues on
Rocketchat, though there are probably too many channels for the amount
of discussion. The monthly live working sessions continue and now
primarily focus on design documents for Sawtooth 2-related work.

# Current Plans

The following work is currently in progress:

-   Move portions of Sawtooth Sabre to Hyperledger Transact
-   Improve Sabre performance
-   Sawtooth 2 component designs
-   Refreshing the Sawtooth website and documentation
-   Migrate to Github Issues, away from JIRA.
-   Rewriting the Sawtooth CLI in Rust (paused)



The following work is currently planned:

-   Create a new consensus library that will be used by the Sawtooth
validator
-   Initialize a Sawtooth service for Splinter



Plans will continue to be developed as part of the working sessions.

# Maintainer Diversity

Maintainers are distributed across
<a href="http://bitwise.io/" class="external-link" rel="nofollow"><span>Bitwise </span></a> IO, Cargill, Intel, and Walmart
Labs.

# Contributor Diversity

Commits from 2021-10-26 to 2022-01-26 :  228

Committers from 2021-10-26 to 2022-01-26 :  7

Domains from 2021-10-26 to 2022-01-26 :  1

# Additional Information

Insights <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222021-10-26T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-01-26T06:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222021-10-26T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-01-26T06:00:00.000Z%22%7D</span></a>

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
-   ✅ <span class="placeholder-inline-tasks">
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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 26-Jan-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62237221"></span>
<p>Adding a <span> <a href="http://CODE_OF_CONDUCT.md" class="external-link" rel="nofollow">CODE_OF_CONDUCT.md</a> file to
every repo is a very simple task. Please, make sure this gets done.</span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Jan
27, 2022 07:21 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62237376"></span>
<p>Created  <a href="https://github.com/hyperledger/sawtooth-core/pull/2418" class="external-link" rel="nofollow">PR #2418</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Jan
28, 2022 16:06 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62237377"></span>
<p>I'm planning to put up PRs for the other repos later today.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by agunde at Jan
28, 2022 16:11 </div ></td>
</tr>
</tbody>
</table>




