---
layout: default
title: 2021 Q1 Hyperledger Avalon
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Avalon

Created by Eugene Yarmosh, last modified by Arun S M on Apr 29, 2021

<span style="color: rgb(23,43,77);">Prepared by Eugene (Yevgeniy) Yarmosh </span>

# Project

<a href="https://wiki.hyperledger.org/display/avalon/Hyperledger+Avalon" rel="nofollow">Hyperledger Avalon</a>

# Project Health

The project health is good. The team made a significant progress,
particularly, finalizing functionality related to SGX DCAP attestation
and scalable key management isolation from the workload execution.
T-Systems engineers demonstrated an integration of SGX based Scone
runtime with Avalon.

Divya Taori became a new project maintainer. T-Systems and Kaleido
developers are planning to become project maintainers in Q2 2021.

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Favalon/dashboard?time=%7B%22from%22:%222020-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-31T08:00:00.000Z%22%7D" class="external-link" rel="nofollow">LF Analytics for Q4</a>  

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Not yet,
planned for Q2/2021 </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?  Not yet,
planned for Q2/2021 </span>

# Questions/Issues for the TSC

There are no issues for the TSC currently.

# Releases

Last release was done in July 2020. No new releases have been done
during 2021 Q1.

The team has made a significant progress finalizing key functionality
that addresses new SGX capabilities and key usages and is on-track to
have a new release within following two quarters. 

# Overall Activity in the Past Quarter

The project development was focused on the following areas

-   Completion of the worker pool implementation
-   Finalize DCAP attestation support
-   Key management enclave replication (final part of the worker pool
scalability design)
-   Secure cross-worker (Graphene) communication channel
-   Multi-threading support for the key management enclave
-   Multi-tenancy (dedicated worker instances per requester)
-   Improved Python SDK as a separate subproject

Avalon team participated in the following activities:

-   Continued regular Avalon Technical Forum calls with a good community
participation   
-   Presented Hyperledger Avalon at Kaleido Tech Tuesday Webinar
-   Continuously utilized email and rocket chat for community support

Number of Avalon presentations at the industry forums has been
relatively low during last two quarters and this is clearly an area th"at requires a lot of attention.

# Current Plans

The team is working towards release 0.7 that includes

-   Scone runtime integration (including documentation and samples)
-   Finalizing functionality by addressing corner cases
-   Integration with K8S with emphasis on end-to-end ease of use
-   Updating documentation, tutorials and examples
-   Improving test coverage and CI
-   Switch from master to main branch and Implement repolinter.json in
all Avalon repositories

The team needs to identify more suitable industry events for a broader
project enabling. 

# Maintainer Diversity

We welcome Swati Kasera from Wipro as a new project maintainer. Kaleido
is planning to become a project maintainer and bring their cloud-native
manageability expertise for blockchain and confidential computing
services. T-Systems is also considering joining Avalon project as a
maintainer with focus on Scone integration.   

# Contributor Diversity

Contributor diversity is gradually improving. We see an interest from
Kaleido and contributions from T-Systems.

# Additional Information

None at this time.

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
-   ✅ <span class="placeholder-inline-tasks">
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
<td><span id="comment-50135389"></span>
<p>The following sentence isn't finished: "Number of Avalon
presentations at the industry forums has been relatively low during last
two quarters and this is clearly an area that requires a lot of a"</p>
<p>Why are you having these really long release cycles? Last release was
July 2020 and you expect the next one to be in 2 quarters? That's over a
year in between. Shouldn't you aim at a more regular cadence?</p>
<p>We are requesting projects to link to their Insights dashboard for
the last quarter. So for this report you should have something like
this:</p>
<p><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Favalon/dashboard?time=%7B%22from%22:%222020-12-31T23:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-03-31T22:00:00.000Z%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Favalon/dashboard?time=%7B%22from%22:%222020-12-31T23:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-03-31T22:00:00.000Z%22%7D</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Apr
07, 2021 06:50 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-50135439"></span>
<p>Arnaud, thank you for the feedback. The sentence is fixed and an
analytics link is added.</p>
<p>The gap between releases is partially due to nature of the
capabilities the team is working on, but also a side effect of our plans
to split the project into two parts - blockchain focused and
confidential computing focused. The planning have taken longer time than
expected, but we are on the path to complete it in Q2.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by EugeneYYY at Apr 07, 2021 16:14 </div ></td>
</tr>
</tbody>
</table>




