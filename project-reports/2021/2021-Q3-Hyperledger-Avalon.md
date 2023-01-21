---
layout: default
title: 2021 Q3 Hyperledger Avalon
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Avalon

Created by Eugene Yarmosh, last modified by Nathan George on Nov 11, 2021

<a href="https://wiki.hyperledger.org/display/avalon/Hyperledger+Avalon" rel="nofollow">Hyperledger Avalon</a>

<span style="color: rgb(23,43,77);">Prepared by Eugene (Yevgeniy)
Yarmosh </span>



# Project Health

The team was focused on identifying an appropriate path that would split
Avalon main into two independent parts – blockchain connectors and
confidential computing (Intel SGX based) core. As result there were no
commits to the main repository. We continued to work on the Python SDK
sub-project and Kata/K8S prototype.  The team continued to
support General Department of Vietnam Customs project.

Analytics: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Favalon/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-09-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">link</a>

# Required Information

1.  <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> ? Yes.
2.  <a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> ? No

# Questions/Issues for the TSC

There are no issues for the TSC currently.

# Releases

There was no release in this quarter.

A release schedule will be updated Avalon split plan is finalized.

# Overall Activity in the Past Quarter

The primary focus has been on splitting Avalon main into two independent
parts – blockchain connectors and confidential computing (Intel SGX
based) core. The SGX core may be potentially hosted at Confidential
Computing Consortium while Avalon itself will focus on the blockchain
integration. This work is in progress and will continue in Q4.  

Other activities during Q3/2021

-   Avalon SDK for direct mode is merged and the package is published at <a href="https://pypi.org/project/avalon-sdk-py/" class="external-link" rel="nofollow">https://pypi.org/project/avalon-sdk-py/</a>
-   Presentation on Avalon at the Webinar organized by STPI India for
the upcoming startups/entrepreneurs with panelists from Amazon, IBM,
MathWorks and other companies.
<a href="https://apiary.stpi.in/" class="external-link" rel="nofollow">https://apiary.stpi.in/</a>
-   Continued support for the POC for General Department of Vietnam
Customs projects and a corresponding white paper is published by Intel and SAP  at  <a href="https://www.intel.com/content/www/us/en/partner/showcase/sap/protect-confidential-customs-data-brief.html" class="external-link" rel="nofollow">white-paper-link</a> .
-   Started prototyping running SGX enabled microservices in Kata
runtime under K8S
-   Started discussions with LF Edge Alvarium team on utilizing Avalon
for improved data provenance trust and confidentiality in
decentralized use cases

# Current Plans

The team is working on

-   Finalizing Avalon code base spilt into independent parts –
blockchain specific and confidential compute core with a possibility
of hosting the core at Confidential Computing Consortium
-   Engaging with LF Edge Alvarium project on the data provenance
solution
-   Defining smart contracts focused on the data provenance use cases   
-   Integrating Python SDK in the main repository
-   Improving deployment and ease-of-use in cloud native (K8S)
environment

# Maintainer Diversity

No changes to the maintainer list in this quarter.

# Contributor Diversity

No changes to the contributors list in this quarter.

# Additional Information

None at this time.

# Submission date

17-Sep-2021

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   🔲 <span class="placeholder-inline-tasks">
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
<td><span id="comment-58857515"></span>
<p>Probably a task for the next TSC, but what would this split look like
if the Intel SGX portions move to the  <span style="color: rgb(23,43,77);">Confidential Computing Consortium? Would
the code in Hyperledger be blockchain connectors to arbitrary privacy
backends?  Blockchain connectors to what would be the CCC Avalon code
only? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by shemnon at Oct 11, 2021 01:06 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-58860339"></span>
<p><a href="https://wiki.hyperledger.org/display/~EugeneYYY" class="confluence-userlink user-mention" data-username="EugeneYYY" data-linked-resource-id="13862799" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Eugene Yarmosh</a> - do you
have an answer for this question or is it still TBD within the avalon
teams?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Oct 29, 2021 02:21 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-58860735"></span>
<p>Could be interesting to see, if in case blockchain part is split as
stamping service then there is a possible collaboration across FireFly.
Potentially, Avalon becoming one of the connector through FireFly for
workloads.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Nov 01, 2021 12:41 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62226826"></span>
<p>Although I suspect the answer is the same, please, note that the
question: " <a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> ?" has been changed to: " <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);"> <a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span>"</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Nov
04, 2021 12:41 </div ></td>
</tr>
</tbody>
</table>




