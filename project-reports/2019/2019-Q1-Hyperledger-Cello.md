---
layout: default
title: 2019 Q1 Hyperledger Cello
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q1 Hyperledger Cello

Created by Haitao Yue, last modified by xianting lei on Jul 04, 2019

# Project Health

<span style="color: rgb(51,51,51);">Project health is largely the same
as in previous update. We are making a very large architectural design
change (support consortium governing), and there are many (10+)
participants in the weekly meeting and actively discuss new issues.</span>

# Issues

There are no major issues at this time. But definitely it would be nice
to have more diversity.

# Releases

-   v0.9.0: Support v1.1/v1.2 fabric in k8s agent, Add v1.3 capabilities
to ansible agent.

# Overall Activity in the Past Quarter

-   Support kubernetes agent for fabric 1.1/1.2 network deployment.
-   Improved user experience for user dashboard.
-   Design the new architecture to support blockchain governing.
-   Bug fixes and documentation improvement.

# Current Plans

<table class="confluenceTable">
<tbody>
<tr class="header">
<th class="confluenceTh">Work Item</th>
<th class="confluenceTh">Effort (1, 2, 3, 5, 8, 13)</th>
<th class="confluenceTh">Priority</th>
</tr>

<tr class="odd">
<td class="confluenceTd">Use new framework to unify all the api
interface, separated from operator dashboard</td>
<td class="confluenceTd">13</td>
<td class="confluenceTd">High</td>
</tr>
<tr class="even">
<td class="confluenceTd">Unified development framework for operator
&amp; user dashboard</td>
<td class="confluenceTd">8</td>
<td class="confluenceTd">Medium</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p>Organize fabric network dynamically in free
mode</p></td>
<td class="confluenceTd">13</td>
<td class="confluenceTd">High</td>
</tr>
<tr class="even">
<td class="confluenceTd">Add fabric network metrics monitor</td>
<td class="confluenceTd">13</td>
<td class="confluenceTd">Low</td>
</tr>
<tr class="odd">
<td class="confluenceTd">Support fabric 1.4 and later version</td>
<td class="confluenceTd">8</td>
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

<span style="color: rgb(51,51,51);"> <span style="background-color: rgb(245,245,245);">We received many feature
requests and bug reports from both large and small companies, such as
H3C. </span> </span>

# Additional Information

Developers still consider to support more blockchain types like
sawtooth, it will be planed after 1.0 release.

Cello projects will send two maintainers to attend the HK bootcamp, and
welcome to come to drop advices.

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span> </span></span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner </span> </span> </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span> </span></span> </span> </span> </span> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-6424899"></span>
<p>How do the plans for Fabric to support Kubernetes out of the box
impact the long term plans for Cello?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mwagner at Feb 20, 2019 18:52 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-6424917"></span>
<p>I believe Sawtooth and perhaps others are intending to support this
as well, so +1 to this question.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by kelly_ at Feb
20, 2019 20:58 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-6425032"></span>
<p><a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>  In the
version 1.0 development, for consortium governing, the docker agent will
be implement first, the main feature for 1.0 is consortium governing
mode, and for version 1.1 will focus on support Kubernetes out of box
for fabric. <a href="https://wiki.hyperledger.org/display/~kelly_" class="confluence-userlink user-mention" data-username="kelly_" data-linked-resource-id="2393195" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kelly M Olson</a>  and 1.2
later version will consider to support sawtooth or others</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hightall at Feb 21, 2019 13:56 </div ></td>
</tr>
</tbody>
</table>




