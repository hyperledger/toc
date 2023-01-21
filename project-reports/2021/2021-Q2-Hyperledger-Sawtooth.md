---
layout: default
title: 2021 Q2 Hyperledger Sawtooth
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Sawtooth

Created by Andrea Gunderson, last modified by David Enyeart on Apr 30, 2021

# Project Health

The primary focus of the last quarter was a new initiative to address
older PRs and start migrating from JIRA to Github Issues.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? </span>
Mostly, a few left <span style="letter-spacing: 0.0px;"></span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? No - mostly in
compliance with exception of
<a href="http://ChangeLog.md/NOTICES" class="external-link" rel="nofollow">ChangeLog.md/NOTICES</a> ; probably the repolinter
config should only warn on these.
<a href="http://ChangeLog.md" class="external-link" rel="nofollow">ChangeLog.md</a> is unnecessary as the repositories
have good commit history (a.k.a changelog) and release notes are
published in addition (
<a href="http://RELEASE_NOTES.md" class="external-link" rel="nofollow">RELEASE_NOTES.md</a> ). NOTICES is appropriate mostly
for binary distributions or when other project's code is included,
which does not apply to many repos.</span>

# Questions/Issues for the TSC

No new issues.

# Releases

-   Sawtooth Sabre v0.7.1 - 12/21/2020
-   Sawtooth SDK GO v0.1.4 - 3/12/2021

# Overall Activity in the Past Quarter

The community continues to discuss Sawtooth-related issues on
Rocketchat. Live working sessions have also been used on a monthly basis
to discuss the future of Sawtooth, with participation from the
community.

The \`master\` branches for most of the Sawtooth repos have been renamed
to \`main\`.

Sawtooth Updates:

-   Added a trait for enforcing admin permissions to the Sabre
transaction processor. This will allow for using Sabre without
requiring Sawtooth Settings. 
-   Added list/show commands for contracts to the \`sabre\` CLI.

For many existing PRs, fresh feedback was given, they were closed due to
inactivity (with a request to re-open if they are still relevant), and
or they were merged. For migrating from JIRA to Github Issues, every
story is being reviewed and either migrated or closed (if it no longer
applies).

# Current Plans

The following work is currently in progress:

-   Rewriting the Sawtooth CLI in Rust
-   Refreshing the Sawtooth website and documentation
-   Move portions of Sawtooth Sabre to Hyperledger Transact
-   Migrate to Github Issues, away from JIRA.



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

Commits from 2020-12-31 to 2021-03-31 :  54

Committers from 2020-12-31 to 2021-03-31 :  7

Domains from 2020-12-31 to 2021-03-31 :  3

# Additional Information

Insights: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard?time=%7B%22from%22:%222021-01-27T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-04-21T12:50:37.577Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fsawtooth/dashboard?time=%7B%22from%22:%222021-01-27T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-04-21T12:50:37.577Z%22%7D</span></a>

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
-   ✅ <span class="placeholder-inline-tasks">
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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-51610272"></span>
<p>Thanks for calling out possible improvements in
`repolinter.json`.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Apr 29, 2021 07:12 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-51610330"></span>
<p>Indeed. All PRs welcome! <img src="emoticons/wink.svg" class="emoticon emoticon-wink" data-emoticon-name="wink" alt="(wink)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Apr
29, 2021 13:21 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-51610443"></span>
<p>I never hesitate on that  <a href="https://github.com/hyperledger-labs/hyperledger-community-management-tools/pull/67" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/hyperledger-community-management-tools/pull/67</a>
  <img src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Apr 29, 2021 16:03 </div ></td>
</tr>
</tbody>
</table>




