---
layout: default
title: 2019 Q4 Hyperledger Cello
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Cello

Created by Baohua Yang, last modified by Nathan George on Mar 31, 2020

# Project Health

<span style="color: rgb(51,51,51);">Project health is largely the same
as in previous update. Now we are re-designing the architecture and
finishing the features for v1.0. Weekly meetings often see around
participates and often run more than 60 minutes due to discussions and
questions.</span>

# Issues

There are no major issues at this time. The entire project has been
migrated to github, the developers are getting familiar with the new
process.

# Releases

-   v0.9.0: Support v1 fabric in k8s agent, Add v1.3 capabilities to
ansible agent.
-   <span class="inline-comment-marker" ref="bc2132d9-465b-45fe-99e5-d3ad837fb085">v1.0.0 (In plan) </span>:
Most of the changes to the project are towards this release. Support
fabric v1.4 LTS. Support k8s operator agent.

# Overall Activity in the Past Quarter

-   <span style="letter-spacing: 0.0px;">Support on fabric 1.4 LTS
(community decision) </span>
-   Designed and implemented the new dashboard for the new APIs.
-   Updated the document for the new architecture.
-   Internship: We have an internship project to design the new k8s
operator agent for Cello.

# Current Plans

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd">Finish the new dashboard design</td>
<td class="confluenceTd">High</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p>Finish the workflow with the k8s operator
agent</p></td>
<td class="confluenceTd">High</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p>Fix all github related warnings and optimize
the process</p></td>
<td class="confluenceTd">Medium</td>
</tr>
<tr class="even">
<td class="confluenceTd">Support HLF 1.4 LTS and later version (The
ansible agent part is finished)</td>
<td class="confluenceTd">Medium</td>
</tr>
</tbody>
</table>

# Maintainer Diversity

Current there are 4 maintainers, and those active developers who
contribute to cello continuously (3 month) will be nominated.

-   Baohua Yang (Oracle)
-   Haitao Yue (IBM)
-   Tong Li (IBM)
-   Jiahao Chen (VMware)

# Contributor Diversity

<span style="color: rgb(51,51,51);">Contributions to the projects
maintain the similar rate as Q3. Lot of discussions on bringing user
management components from a third party which already has the function
in their product. </span>

# Additional Information

N/A

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
<td><span id="comment-24774950"></span>
<p>Can you clarify whether those releases are complete or planned? A
first major release requires a TSC approval process. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by dan.middleton@intel.com at Nov 14, 2019 15:15 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24775054"></span>
<p>OK, Dan. There is no major release in Q4.</p>
<p>Sure will follow the process for further release plan.</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at Nov
15, 2019 01:13 </div ></td>
</tr>
</tbody>
</table>




