---
layout: default
title: 2019 Q2 Hyperledger Cello
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q2 Hyperledger Cello

Created by Tong Li, last modified on Aug 14, 2019

# Project Health

<span style="color: rgb(51,51,51);">Project health is largely the same
as in previous update. The community is making  changes to make Cello
more of a production ready tool. Features and capabilities are now more
based on common use cases and behaviors of the Blockchain applications.
Weekly meetings often see 10+ participates and often run over the
allocated 30 minutes due to discussions and questions. In some cases,
very well run pass 1 hour mark.</span>

# Issues

There are no major issues at this time.

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
-   Talk with Justitia proposal submmitter to bring the proposed
functions/idea into cello and/or basically merge its work into Cello
-   Added agent creation function on user dashboard
-   Adding Fabric K8S operators with the Intership
-   Continue improving user experience for user dashboard.
-   Based new and future cello work on fabric 1.4.2 (community decision)
-   Design the new architecture to support blockchain governing.
-   Bug fixes and documentation improvement.

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
<td class="confluenceTd">Adopt the Interop working group channel
expansion method</td>
<td class="confluenceTd">Low</td>
</tr>
<tr class="even">
<td class="confluenceTd">Support fabric 1.4 and later version (if using
ansible agent, this is done already)</td>
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
maintain the similar rate as Q1. Lot of discussions on bringing user
management components from a third party which already has the function
in their product.</span>

# Additional Information



# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);">Baohua Yang </span>
-   ✅ <span style="color: rgb(0,0,0);">Binh Nguyen </span>
-   ✅ <span style="color: rgb(0,0,0);">Christopher Ferris </span>
-   ✅ <span style="color: rgb(0,0,0);">Dan Middleton </span>
-   ✅ <span style="color: rgb(0,0,0);">Hart Montgomery </span>
-   ✅ <span style="color: rgb(0,0,0);">Kelly Olson </span>
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
<td><span id="comment-13861038"></span>
<p>Can you please comment on Cello development regarding designing for
security and designing for accessibility?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by dan.middleton@intel.com at May 14, 2019 12:56 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-13861041"></span>
<p>Cello is a tool to deploy and manage a blockchain network such Fabric
network. Its self is secured by common security measures such as TLS and
user name and password just like any other common applications. In terms
of security of the fabric network or any other network, we use what each
production provides. For example, you can set up fabric using tls and
certificates, cello will provide options for users to do that. In terms
of the accessibility, our user interface team is using a very popular
framework and I believe it is baked in the framework. But I am not 100%
sure if we have done anything special. That will need to be deferred to
<a href="https://wiki.hyperledger.org/display/~hightall" class="confluence-userlink user-mention" data-username="hightall" data-linked-resource-id="6423839" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Haitao Yue</a> for a better
answer.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tongliofcary
at May 14, 2019 13:15 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-13861863"></span>
<p>For the RESTful APIs by Cello, there are typical security mechanism
like token to protect the service.</p>
<p>There's no plan for accessibility now. It should be post the v1.0
release.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at May
23, 2019 14:23 </div ></td>
</tr>
</tbody>
</table>




