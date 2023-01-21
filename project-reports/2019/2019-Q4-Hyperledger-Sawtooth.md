---
layout: default
title: 2019 Q4 Hyperledger Sawtooth
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Sawtooth

Created by Mark Ford, last modified by Gari Singh on Nov 08, 2019

# Project Health

New features:

-   Focus has been on stability, performance and regression testing for
the upcoming 1.2 release. The features contained in the 1.2 release
were originally reported in previous 2019 Sawtooth quarterly
updates.

Bug fixes:

-   The ongoing transition of the codebase from Python to Rust changed
the dynamics of calls across the FFI boundary. This led to some
complex performance regressions which showed up during
long-running-network testing with PoET consensus. Detailed
instrumentation of the FFI calls suggested targeted optimizations to
reduce or <span class="inline-comment-marker" ref="01a57708-8a62-45ff-81cf-9ed487cef530">eliminate expensive
boundary crossings </span>. Final long-running-network tests with
these changes are wrapping up, which should culminate in a 1.2
release shortly.

Blog content:

-   <a href="https://www.hyperledger.org/blog/2019/09/19/2019-summer-mentee-project-update-developing-explorer-capabilities-for-hyperledger-sawtooth" class="external-link" rel="nofollow"><span>2019 Summer Mentee Project
Update: Developing Explorer Capabilities for Hyperledger Sawtooth</span></a>
-   <a href="https://www.hyperledger.org/blog/2019/10/01/all-the-farms-an-agricultural-supply-chain-story" class="external-link" rel="nofollow"><span>All the Farms: An
agricultural supply chain story </span></a>

# Issues

New issues

-   None

# Releases

-   Sawtooth PBFT 1.0
-   Sawtooth 1.2 (coming soon)

# Overall Activity in the Past Quarter

See the community calendar <a href="https://wiki.hyperledger.org/community/calendar-public-meetings" rel="nofollow"><span>https://wiki.hyperledger.org/community/calendar-public-meetings</span></a> for occurrences of our Sawtooth Contributors Meeting.

# Current Plans

Continuing development on:

-   Sawtooth 1.2 release
-   Rewrite of remaining Python components in Sawtooth Core in Rust
-   Getting Sawtooth Rust SDK to 1.0
-   Getting Sawtooth Sabre to 1.0

# Maintainer Diversity

Maintainers are roughly evenly distributed across
<a href="http://bitwise.io/" class="external-link" rel="nofollow"><span>Bitwise.io </span></a> , Cargill, Intel, with
T-Mobile on Next Directory.  No new maintainers have been added in this
quarter.

# Contributor Diversity

Commits from 2019-07-01 to 2019-09-30 :  225

Committers from 2019-07-01 to 2019-09-30 :  27

Domains from 2019-07-01 to 2019-09-30 :  12

# Additional Information



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
<td><span id="comment-22382137"></span>
<p>Woud you, or someone from the Sawtooth team, be interested in coming
to a Perf and Scale Working Group meeting to discuss the performance
issues ?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mwagner at Oct 10, 2019 11:36 </div ></td>
</tr>
</tbody>
</table>




