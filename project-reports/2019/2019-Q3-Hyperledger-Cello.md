---
layout: default
title: 2019 Q3 Hyperledger Cello
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Cello

Created by Baohua Yang, last modified on Nov 08, 2019

# Project Health

<span style="color: rgb(51,51,51);">Project health is largely the same
as in previous update. The community is making  changes to make Cello
more of a production ready tool. Features and capabilities are now more
based on common use cases and behaviors of the Blockchain applications.
Weekly meetings often see 10+ participates and often run about 60
minutes due to discussions and questions.</span>

# Issues

There are no major issues at this time. There is increasing requirement
for the new features of the planed v1.0.0 release.

# Releases

-   v0.9.0: Support v1.1/v1.2 fabric in k8s agent, Add v1.3 capabilities
to ansible agent.
-   v1.0.0: Most of the changes to the project are towards this release.
We like to be very cautious and prudent on this release and will not
rush it out.

# Overall Activity in the Past Quarter

-   Ansible agent continued with many features additions:
-   Continue working on Interop artifacts generation, join request,
orderering system endpoints and certificates integration
-   Added agent creation function on user dashboard
-   Adding Fabric K8S operators with the Intership
-   Talk with Justitia proposal submmitter to bring the proposed
functions/idea into cello and/or basically merge its work into Cello
-   Keep working on the new governing model and relevant APIs.
-   Based new and future cello work on fabric 1.4.2 (community decision)
-   Designed and implemented the new dashboard for the new APIs.
-   Updated the document for the new architecture.
-   Bug fixes.

# Current Plans

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd">Use new framework to unify all the user
interface panels</td>
<td class="confluenceTd">High</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p>Organize and manage fabric network
dynamically</p></td>
<td class="confluenceTd">High</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p>Adopt the Interop working group channel
expansion method</p></td>
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
maintain the similar rate as Q2. Lot of discussions on bringing user
management components from a third party which already has the function
in their product. </span>

# Additional Information

N/A

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);">Baohua Yang </span>
-   ✅ <span style="color: rgb(0,0,0);">Binh Nguyen </span>
-   ✅ <span style="color: rgb(0,0,0);">Christopher Ferris </span>
-   ✅ <span style="color: rgb(0,0,0);">Dan Middleton </span>
-   ✅ <span style="color: rgb(0,0,0);">Hart Montgomery </span>
-   🔲 <span style="color: rgb(0,0,0);">Kelly Olson </span>
-   ✅ <span style="color: rgb(0,0,0);">Mark Wagner </span>
-   ✅ <span style="color: rgb(0,0,0);">Mic Bowman </span>
-   ✅ <span style="color: rgb(0,0,0);">Nathan George </span>
-   ✅ <span style="color: rgb(0,0,0);">Silas Davis </span>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-16324880"></span>
<p>Please look into CII ahead of your release. Also please review the
draft release requirements (which include CII). They are only in draft
form now, but your project would only benefit from adopting as many as
possible.</p>
<p><a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=16321784">Issue
2: What are the criteria for a "First Major Release"?</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by dan.middleton@intel.com at Aug 15, 2019 15:10 </div ></td>
</tr>
</tbody>
</table>




