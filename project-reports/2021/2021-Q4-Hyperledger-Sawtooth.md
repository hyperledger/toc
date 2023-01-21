---
layout: default
title: 2021 Q4 Hyperledger Sawtooth
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Sawtooth

Created by Andrea Gunderson, last modified by Bobbi Muscara on Nov 04, 2021

# Project Health

Hyperledger Sawtooth
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow"><span>https://sawtooth.hyperledger.org/ </span></a>

In the last quarter work was done to simplify some aspects of Sawtooth
Sabre in preparation for it being moved to Transact. SQLite, PostgreSQL
and LMDB support for ReceiptStore in sawtooth-lib has been stabilized.
The design can be found <a href="https://www.splinter.dev/community/planning/libsawtooth_receipt_store.html" class="external-link" rel="nofollow"><span>here </span></a> .

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">?  Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span>
1.  LICENSE - yes
2.  CODE\_OF\_CONDUCT.md - no
3.  SECURITY.md - yes
4.  README.md - yes
5.  MAINTAINERS.md - yes
6.  CONTRIBUTING.md - yes
7.  CHANGELOG - yes, but called
<a href="http://RELEASE_NOTES.md" class="external-link" rel="nofollow">RELEASE_NOTES.md</a>

# Questions/Issues for the TSC

No new issues.

# Releases

-   Sawtooth Library v0.6.6 - 8/31/2021
-   Sawtooth Library v0.6.7 - 10/07/2021

# Overall Activity in the Past Quarter

The community continues to discuss Sawtooth-related issues on
Rocketchat. Live working sessions have also been used on a monthly basis
to discuss the future of Sawtooth, with participation from the
community.

Sawtooth Updates:

-   Stabilized SQLite and PostgresSQL support for the ReceiptStore in
sawtooth-lib
-   Removed smart permission and Pike from Sabre. Pike has been moved to
Grid and had a major update, and Smart Permissions are currently not
used anywhere but did rely heavily on Pike.
-   Community bug fixes

# Current Plans

The following work is currently in progress:

-   Move portions of Sawtooth Sabre to Hyperledger Transact
-   Migrate to Github Issues, away from JIRA.
-   Rewriting the Sawtooth CLI in Rust
-   Refreshing the Sawtooth website and documentation

The following work is currently planned:

-   Create a new consensus library that will be used by the Sawtooth
validator
-   Initialize a Sawtooth service for Splinter
-   Improve Sabre performance

Plans will continue to be developed as part of the working sessions.

# Maintainer Diversity

Maintainers are distributed across
<a href="http://bitwise.io/" class="external-link" rel="nofollow"><span>Bitwise </span></a> IO, Cargill, Intel, and Walmart
Labs.

# Contributor Diversity

Commits from 2021-07-20 to 2021-10-26 :  102

Committers from 2021-07-20 to 2021-10-26 :  6

Domains from 2021-07-20 to 2021-10-26 :  2

# Additional Information

Insights: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-20T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-10-26T05:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-20T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-10-26T05:00:00.000Z%22%7D</span></a>  

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



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62226753"></span>
<p>Do we have a data matrix about how many enterprise customers using
Sawtooth? We have data &amp; stories about Hyperledger fabric , Indy,
Aries but Hyperledger Sawtooth DLT we don't have such data. I have faced
such questions from the community about Sawtooth as project in
production deployment.</p>
<p>I don't know whether this is right place to ask this question. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by knagware9 at Nov 03, 2021 17:34 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62226819"></span>
<p>Probably a question to the Hyperledger staff? What is the source for
data and stories about other projects?</p>
<p>On top of my mind, I know personally following projects are using
Hyperledger Sawtooth - Indian CBSE 10th and 12th results are captured on
it, BondEvalue, Panini's NFT, Tel Aviv Stock Exchange etc.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Nov 04, 2021 12:11 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62226887"></span>
<p>As I mentioned on the TSC call, there are examples in the community
about people sharing what they've built with Sawtooth.  Here is the
recording of a presentation about an NFT marketplace built with Sawtooth
that was shared at the Media and Entertainment SIG.  I think there's a
question here of how to better surface things that are happening across
the community so people can find out about this if they aren't actively
involved in a specific group.</p>
<p><a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=41594922">Panini
NFTs on Hyperledger Sawtooth-</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at Nov 04, 2021 14:55 </div ></td>
</tr>
</tbody>
</table>




