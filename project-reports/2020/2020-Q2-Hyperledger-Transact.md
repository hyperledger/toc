---
layout: default
title: 2020 Q2 Hyperledger Transact
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Transact

Created by Peter Schwarz, last modified by Gari Singh on Jun 11, 2020



# Project

Hyperledger Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a>

# Project Health

Health is good. A lot of continued interest in the project and
development continues on new features. New development includes a Go
SDK, initiated by a community user.

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 12 releases. The current
release is 0.2.4. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> : 

<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow">https://crates.io/crates/transact/versions</a>

# Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion continues to be
held in RocketChat.

-   Initial implementation of a Go SDK, found at <a href="https://github.com/hyperledger/transact-sdk-go" class="external-link" rel="nofollow"><span>https://github.com/hyperledger/transact-sdk-go</span></a>
-   Stabilization of the "contract-archive" feature for loading smart
contracts from smart contract archive (.scar) files.

# Current Plans

Next steps include:

-   Stabilize SQLite database support
-   Add next-generation smart contract API / simplified smart contracts
(cross-project w/Sawtooth, in-progress)
-   Add PostgreSQL database support
-   Further develop Transact SDK for JavaScript

# Maintainer Diversity

The maintainer diversity currently matches that of the initial project
sponsor companies.

# Contributor Diversity

There are new contributors, primarily related to the new Go SDK.

# Additional Information

None

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-31202580"></span>
<p>Maybe it is just me, but I don't see much if any activity for
Transact. The last commit on Transact repo was May 4, the last Jira
update was October 19, 2019. The mailing list is unused except for spam,
and the RC chat is sparse at best.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by ChristopherFerris at Jun 10, 2020 18:47 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31202610"></span>
<p>Most of the activity has been in consuming/using it. Transact is a
mature enough library that a lot of the use cases in the last few months
have been satisfied and didn't cause a need for additional feature
development. As those ledgers evolve, we expect Transact to evolve to
meet their needs.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Jun 10, 2020 21:08 </div ></td>
</tr>
</tbody>
</table>




