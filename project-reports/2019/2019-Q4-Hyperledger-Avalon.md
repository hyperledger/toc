---
layout: default
title: 2019 Q4 Hyperledger Avalon
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Avalon-Project-Update

Created by Eugene Yarmosh, last modified by Nathan George on Mar 31, 2020

<span style="letter-spacing: 0.0px;">Prepared by Eugene (Yevgeniy)
Yarmosh </span>

# Project Health

The Avalon project has grown well in its first quarter.  We are
establishing community processes that include regular (every other week)
meetings, JIRA, etc. We have completed direct model (JRPC), developed
hello-world tutorial, improved project documentation, and added more use
cases. Initial integration with Ethereum blockchain was completed. The
focus is on integrating Hyperledger Fabric and porting Ethereum JAVA
connector to PYTHON to improve code consistency. The team is evaluating
options for separating key management from work order processing and on
scalable worker orchestration. 

# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">There are no issues for the TSC at this time. </span>

# Releases

October 2019 - Release 0.4. This release was focused on baseline
end-to-end functionality for direct model.

The plan for minor releases (0.5, 0.6, 0.7, ...) to be done roughly
quarterly in 2020.

The team doesn't yet plan patch releases (e.g. 0.4.1, 0.4.2), but it may
change in the near future to better capture intermediate progress.    

# Overall Activity in the Past Quarter

Hyperledger Avalon transitioned from Hyperledger Lab - Trusted Compute
Framework (TCF).

-   Completed core implementation for the direct model (via JSON RPC)
that also fully reusable for integration with blockchain 
-    Added initial Ethereum support (Solidity smart contracts and JAVA
connector)
-   Started integration of Hyperledger Fabric
-   Implemented hello-world tutorial and several end-to-end examples
-   Updated project documentation
-   Implemented baseline inside-out API
-   Started evaluation of Kubernetes as a foundation for scalable worker
execution orchestration
-   Evaluated Graphene as a candidate for integration with Avalon
-   Established CI/CD build infrastructure
-   Established a bi-weekly contributor call



Avalon team participated in the following activities:

-   Presented the Hyperledger meet-up at Ethereum Devcon V in Japan
-   Presented Avalon at Architecture WG
-   Presented at Hyperledger meet-up in Bangalore, India
-   Submitted a workshop proposal that was approved to present at the
Hyperledger Global Forum

# Current Plans

The Avalon project has several upcoming priorities:

-   0.5 Release, scheduled for March 2020. The focus of this release is
on:
-   Integrate Avalon with Hyperledger Fabric
-   Port Ethereum connector from JAVA to python 
-   Add a security layer to inside-out API
-   Implementation policy based worker encryption key
-   Define of architecture for separation of key management from
workload processing 
-   Define architecture for the scalable orchestration layer
-   The Avalon team is also focusing on improving project documentation
that is relatively thin at this time. Immediate goals are to build
up content in the project WiKi, document Avalon architecture
(current and upcoming plans), and simplify/streamline overall
project structure and build process   
-   Another important area is continuing engagement with its community
to grow the diversity of its maintainer and contributor base.
Primary mechanisms are to grow attendance for its regular
contributor calls and present Avalon to developers through
Hyperledger (Global Forum, meet-ups) and other industry venues.

# Maintainer Diversity

Since Avalon is a new Hyperledger project, its maintainers is the same
as it was when the project was hosted as TCF Hyperledger Lab.  Based on
the activity going within the Avalon community and our current plans we
anticipate that the maintainers list will be extended by release 0.5
after more community members make substantial contributions to the
project. 

# Contributor Diversity

Avalon includes active contributors from five organizations.  The Avalon
Developer Forum calls we established every other week during last
quarter have been well attended by members from different organizations.
We are reaching out to all original Avalon project sponsors and we also
see members joining the community from organizations that have not been
on the original project sponsor list.

We will present Avalon workshop at the Hyperledger Global Forum in the
spring of 2020 to attract additional contributors to the project. We
also plan to utilize EEA,  Hyperledger meet-ups, and other industry
venues to bring more contributes to the project. 

# Additional Information

None at this time.

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
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-24779673"></span>
<p>Thank you for the detailed report!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Dec
19, 2019 06:51 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24779727"></span>
<p>I noticed there is only on meeting documented are the other meetings
happening online?  Where are those taking place? </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Silona at Dec
19, 2019 15:15 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24779982"></span>
<p><a href="https://wiki.hyperledger.org/display/~Silona" class="confluence-userlink user-mention" data-username="Silona" data-linked-resource-id="2392164" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Silona Bonewald</a>  This
is correct. There is only one meeting Avalon Developer Forum so far th"at happens every other Tuesday at 6:30am Pacific Time. We plan to add
Architectural Forum meeting and potentially more as needed in Q1
2020.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by EugeneYYY at Dec 27, 2019 19:17 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24780142"></span>
<p>I was commenting more on the fact that I did not see any meeting
notes for any of those meetings.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Silona at Jan
03, 2020 23:37 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24780143"></span>
<p>For example here - <a href="https://wiki.hyperledger.org/display/avalon/2019-10-22+Meeting+notes">2019-10-22
Meeting notes</a>   to avoid anti-trust issues.  Meetings should be
documented and recorded.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Silona at Jan
03, 2020 23:38 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-29033448"></span>
<p><a href="https://wiki.hyperledger.org/display/~Silona" class="confluence-userlink user-mention" data-username="Silona" data-linked-resource-id="2392164" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Silona Bonewald</a>  I just
realized I missed your follow up comment. Avalon meeting recording can
be found at  <a href="https://wiki.hyperledger.org/display/avalon/Meetings">https://wiki.hyperledger.org/display/avalon/Meetings</a>
. For example, recording of the latest call from Jan 28th is at  <a href="https://wiki.hyperledger.org/display/avalon/2020-01-28+Avalon+Monitor">https://wiki.hyperledger.org/display/avalon/2020-01-28</a>
.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by EugeneYYY at Jan 30, 2020 18:15 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-29033453"></span>
<p>Right now your meetings are just the recordings which isn't very
friendly to new people joining.  Also the wiki page hasn't been updated
and edited.  If you need a walkthru please ping me on chat and we can
schedule a time for me to explain confluence.  <a href="https://wiki.hyperledger.org/display/~EugeneYYY" class="confluence-userlink user-mention" data-username="EugeneYYY" data-linked-resource-id="13862799" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Eugene Yarmosh</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Silona at Jan
30, 2020 19:25 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-29033484"></span>
<p><a href="https://wiki.hyperledger.org/display/~Silona" class="confluence-userlink user-mention" data-username="Silona" data-linked-resource-id="2392164" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Silona Bonewald</a>  Thanks
for the feedback. I am updating the wiki with the recording of the
sessions after every meeting, which happens once in two weeks.</p>
<p>Agree with you that it can be made more user friendly by adding some
notes.</p>
<p>A walkthru of confluence and best practices to update the wiki will
really help us. </p>
<p>Thanks for this support</p>
<p>Harsha </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by s02 at Jan
31, 2020 02:38 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-29033543"></span>
<p>ok I DM'd you on Chat with my calendar info - grab a time with me</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Silona at Jan
31, 2020 18:20 </div ></td>
</tr>
</tbody>
</table>




