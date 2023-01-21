---
layout: default
title: 2022 Q1 Hyperledger Ursa
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Ursa

Created by Cam Parra, last modified by Peter Somogyvari on May 03, 2022

<span style="letter-spacing: 0.0px;"> </span> <span style="font-size: 24.0px;letter-spacing: 0.0px;">Project Health </span>

After many changes with contributors and leaders the project is
undergoing a revival and restructuring. The meetings are now being
planned and directed by Cam Parra. This was done since Hart Montgomery
changed his role to CTO at HyperLedger and could no longer perform those
duties. The project has lost a lot of momentum with losing one of it's
main contributors. The good news is that a plan to refactor the code
base named Operation Oso has been agreed upon and started. This work
item sets to simplify and make it easier to contribute to the project
and make the components of the library more reusable. This work has been
proposed and has started but it's moving slowly.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? YES</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? YES</span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? No but in the
works </span> </span>
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? No</span> </span>

# Questions/Issues for the TSC

 W <span style="color: rgb(29,28,29);">e aren't as connected to all the
projects as we would like. So we would be really grateful if the TSC
members could help us gather feedback about Ursa. We would appreciate
this feedback and especially know how we can help integrate Ursa into
their projects.</span>

# Releases

No releases have been made this quarter but we hope to get some out soon
for URSA-base which is the first part of the refactoring being done in
Project Oso

# Overall Activity in the Past Quarter

As mentioned before the activity in this project has slowed down due to
many changes in the contributors and leaders. We are currently working
to fix that by attracting new contributors. This is being done by making
the meetings more new comer friendly and leaving time for others to
participate by asking questions. We believe that this will help us get
input and code from people who would normally be too afraid to do so
because of the intensity of the project. We continue to see the
maintainers show up in the meetings and show interest in the group. They
contribute not just to the calls but are very activate on the past pull
requests.

We have currently one outstanding pull request which is to add a zero
knowledge language to URSA. That still has work to be done as it does
not meet standards of the code base but is being worked on by the
maintainers to merge it.

# Current Plans

Operation OSO is the current plan that has been agreed upon by the
active maintainers. Like mentioned above this refactoring is being done
so that the project can be more reusable and simpler. The first step to
do this will be the refactoring of the key components (not cryptographic
keys) of URSA and group them into their own package. This will setup the
code base to continue the refactoring in the other components of URSA
such as signatures and Zero knowledge proofs. Also this is not just a
separation and simplification of code. This will break up the components
into their own Rust crates. This will allow users to pick and choose
what part of URSA they need and want to implement. This will be a game
changer for IOT and those needing to run cryptographic primitives on
restricted systems.

For recruitment and participation on the project we will be taking steps
to become more accessible and transparent with the work. The meeting
will be more new comer friendly as mentioned above and allow for others
to voice their concerns as well as propose solutions to whatever need
they may have. We also plan on bringing in more contributors and
implementer from different HL projects so that they can offer their
insight on how URSA is being used and how it can change.

# Maintainer Diversity

-   Mike Lodder (Independent)
-   Brent Zundel (Evernym Inc.)
-   Dan Anderson (Intel)
-   Cam Parra (Kiva)
-   Dan Middleton (Intel)

# Contributor Diversity

Here is the link from LF analytics:   <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D" class="external-link" rel="nofollow" style="text-decoration: none;">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D</a>
.  

# Additional Information

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

<span class="placeholder-inline-tasks"> 16-Mar-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62244480"></span>
<p><a href="https://wiki.hyperledger.org/display/~cam-p+1" class="confluence-userlink user-mention" data-username="cam-p 1" data-linked-resource-id="62231189" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Cam Parra</a> – Glad to see
that there are efforts to make Ursa more newcomer friendly.  If you'd
like help with recruitment, we'd be happy to talk with you more about
ways we could support you.  For instance, we haven't shared much about
Ursa in channels such as the developer newsletter or in meetups where
there might be people who'd like to get involved.</p>
<p>And glad to hear you'll be doing more to connect with other HL
projects.  I'd also encourage you to reach out to the Special Interest
Groups where there could also be people who are interested.  For
instance, you mention work in Ursa that will be a game changer for IOT
and this could be of interest to the Telecom SIG and maybe other
groups.  That group is interested in this topic – for instance, last
year they wrote a solutions brief about Decentralized ID and Access
Management (DIAM) for IoT Networks.</p>
<p><a href="https://www.hyperledger.org/wp-content/uploads/2021/02/HL_LFEdge_WhitePaper_021121_3.pdf" class="external-link" rel="nofollow">https://www.hyperledger.org/wp-content/uploads/2021/02/HL_LFEdge_WhitePaper_021121_3.pdf</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Mar 16, 2022 22:36 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62244593"></span>
<p>I see we're targeting 2 categories of folks to participate. The
consumers of the project and contributors to the project. For the
consumers part, should we plan for how to showcase the usage part of it?
It is difficult for non-cryptographers to know what they're looking for.
Breaking it down in a way that can be consumed will help.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Mar 17, 2022 14:04 </div ></td>
</tr>
</tbody>
</table>




