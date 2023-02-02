---
layout: default
title: 2023 Q1 Hyperledger Cacti
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# 2023 Q1 Hyperledger Cacti

Created by Takuma Takeuchi, last modified by David Enyeart on Jan 19, 2023

# Project Health

-   Cactus and Weaver were merged to one project "Cacti."  The
maintainers almost completed the first code merge and will release
the first Cacti v2-alpha (tentative name) in Q1 2023.
-   The maintainers are also discussing the new architecture of Cacti
toward Cacti-V2 in order to combine the strengths of the original
Cactus and Weaver to achieve a more flexible interoperability tool.
-   Cacti has newly supported the interoperability with Iroha V2 and
Ubiquity SDK.
-   Weaver now supports organizational identity syncing and event
pub/sub across Fabric networks, and atomic swaps involving
ERC-standard tokens in Besu networks with Fabric and Corda
networks.  These will be merged in Cacti V2-alpha release on Q1
2023.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? **Yes**
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? **Yes**</span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. **Yes, we use DCI-Lint as
part of our CI**</span>
	1.  master → main
	2.  slave → replicas
	3.  blacklist → denylist
	4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages?  **Yes**</span>

# Questions/Issues for the TSC

-   None at the moment.

# Releases

* 	v1.1.x: to fix the GitHub workflow errors
* 	[v1.1.3](https://github.com/hyperledger/cactus/tree/v1.1.3)
* 	[v1.1.2](https://github.com/hyperledger/cactus/tree/v1.1.2)
* 	[v1.1.1](https://github.com/hyperledger/cactus/tree/v1.1.1)

	
# Overall Activity in the Past Quarter

1.  Major Cactus updates as merged pull-requests
1.  interoperability with ledgers:
1.   \[new\_feature\] Iroha: add support for Iroha V2
    1.  interoperability with ledgers:
        1.   \[new\_feature\] Iroha: add support for Iroha V2
            1.  <a href="https://github.com/hyperledger/cactus/commit/db789690b64d68b3dda70578127338bdc02e92bd" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/db789690b64d68b3dda70578127338bdc02e92bd</a>
            2.  <a href="https://github.com/hyperledger/cactus/commit/6ff6aac7fff4669fca873ef40ae6b0818e70b5ec" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/6ff6aac7fff4669fca873ef40ae6b0818e70b5ec</a>
        2.  \[new\_feature\] Ubiquity SDK: initial version
            1.  <a href="https://github.com/hyperledger/cactus/commit/7c597907910bd5cac919c855a3bfa9e533b6d5dd" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/7c597907910bd5cac919c855a3bfa9e533b6d5dd</a>
        3.  \[update\] Fabric: add WatchBlocks endpoint
            1.  <a href="https://github.com/hyperledger/cactus/commit/0f670855b0fa0fd33f71bf5a1814fb6fcac2c7b6" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/0f670855b0fa0fd33f71bf5a1814fb6fcac2c7b6</a>
        4.  \[update\] Fabric: add transactions signed on the client
side
            1.  <a href="https://github.com/hyperledger/cactus/commit/0b34ca3d35a39826c05cc047e480d377c1c52bef" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/0b34ca3d35a39826c05cc047e480d377c1c52bef</a>
        5.  \[update\] ODAP: decouple the gateway implementation from
any ledger
            1.  <a href="https://github.com/hyperledger/cactus/commit/6975fefd4994cc9c6dd7d649dc2d6400646a59ae" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/6975fefd4994cc9c6dd7d649dc2d6400646a59ae</a>
    2.  support features:
        1.  \[update\] support multiple business-logic-plugins in the
single server
            1.  <a href="https://github.com/hyperledger/cactus/commit/0f670855b0fa0fd33f71bf5a1814fb6fcac2c7b6" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/commit/0f670855b0fa0fd33f71bf5a1814fb6fcac2c7b6</a>
2.   Major Weaver updates as merged pull requests (\* These will be
merged in Cacti V2-alpha release in Q1 2023)
    1.  ERC-token support for Besu networks engaging in asset swaps
        1.  <a href="https://github.com/hyperledger-labs/weaver-dlt-interoperability/pull/299" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/weaver-dlt-interoperability/pull/299</a>
    2.  Identity syncing across Fabric networks using
organization-specific agents running a flow
        1.  <a href="https://github.com/hyperledger-labs/weaver-dlt-interoperability/pull/322" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/weaver-dlt-interoperability/pull/322</a>
        2.  <a href="https://github.com/hyperledger-labs/weaver-dlt-interoperability/pull/316" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/weaver-dlt-interoperability/pull/316</a>
3.  Created a draft architecture diagram for Cacti as a fusion of Cactus
and Weaver, with the goal of providing a flexible or customizable
interoperability toolkit 
    1.  The architecture has been brushed-up among weekly maintainer
calls.  This will be started to be referred on the next release
(Cacti V2-beta on Q1-Q2)
    2.  The architectural evolution is called out in two distinct
phases:
        1.  A common platform and toolkit with Cactus and Weaver modules
and libraries coexisting and solving similar purposes
        2.  An integrated platform and toolkit with similar-purpose
modules and libraries from Cactus and Weaver fused into
common Cacti modules and libraries

# Current Plans

1.  Release plan:
    1.  Cacti V2-alpha (Q1): The first proto version of Cacti combining
the original Cactus and Weaver
    2.  Cacti V2-beta (Q1-Q2): The first version of Cacti based on the
new architecture (combined with the strengths of Cactus and
Weaver)
2.  Other features:
    1.  Cacti Transaction GUI feature (Q1)
    2.  DID registry-based identity management for cross-network data
sharing
    3.  Automated relay-based asset swaps using cross-network events
    4.  Supporting data sharing (with proof generation and validation)
in for Fabric PDCs
    5.  Supporting data sharing (with proof generation and validation)
in Besu networks
3.  Standardization:
    1.  Track the Secure Asset Transfer (SAT) group's efforts toward
forming an official IETF Working Group
    2.  If it becomes an official WG, influence and comply (i.e., in
Cacti code) with protocol drafts (eventually RFCs) for
interoperability standards

# Maintainer Diversity

-   As is required, you can find our current maintainer list here:  
<a href="https://github.com/hyperledger/cactus/blob/main/MAINTAINERS.md" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/blob/main/MAINTAINERS.md</a>
.

<!-- -->

-   Our existing maintainers are:
-   Jagpreet Singh Sasan (Accenture)
-   Jonathan Hamilton (Accenture)
-   Peter Somogyvari (Accenture)
-   Izuru Sato (Fujitsu)
-   Takuma Takeuchi (Fujitsu)
-   Sandeep Nishad (IBM)
-   Venkatraman Ramakrishna (IBM)

# Contributor Diversity

-   <a href="https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard" class="external-link" rel="nofollow">https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard</a>
Our contributor strength has increased in this quarter compared to
the previous quarter, which is great news!

# Additional Information

-   N/A

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a>
-   ✅ Bobbi Muscara
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~bur" class="confluence-userlink user-mention" data-username="bur" data-linked-resource-id="29033442" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Marcus Brandenburger</a>
 
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a>  </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~TimoGlastra" class="confluence-userlink user-mention" data-username="TimoGlastra" data-linked-resource-id="31199909" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Timo Glastra</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~vramaiitkgp" class="confluence-userlink user-mention" data-username="vramaiitkgp" data-linked-resource-id="16325996" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ramakrishna V</a>  </span>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-80775772"></span>
<p><a href="https://wiki.hyperledger.org/display/~Peter Somogyvari" class="confluence-userlink user-mention" data-username="Peter Somogyvari" data-linked-resource-id="31202399" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a> –
That's great to hear about plans for Cacti v2.  If I remember correctly
there was a mention last year that the Cacti maintainers may be
interested in running a new Cacti workshop this year to cover what's new
in the v2 release.  I'll be happy to help with that and I think th"at would be a great way to introduce people to all the new features.  Let
me know if you'd like to talk more about this and we can come up with a
plan.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Jan 17, 2023 17:16 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-80775823"></span>
<p>The "Reviewed By" list needs to be update to the new TOC
membership.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Jan
18, 2023 07:49 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-80775825"></span>
<p>Well, I updated it.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Jan
18, 2023 07:50 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-80775826"></span>
<p><a href="https://wiki.hyperledger.org/display/~davidwboswell" class="confluence-userlink user-mention" data-username="davidwboswell" data-linked-resource-id="2392933" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Boswell</a> Yes, we'd
like to talk to our (current and future) users about the merge, the set
of features and options they get to pick from, and a description of the
architecture. The last workshop (early November) I think covered the
Cactus features; in the next edition, we can talk about both Cactus and
Weaver features within Cacti, and our roadmap towards integrating the
two sets.<br />
<br />
The maintainers can discuss and come up with a suitable time frame for
the next workshop. Tentatively, I'll propose mid-February.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vramaiitkgp
at Jan 18, 2023 09:09 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-80775838"></span>
<blockquote>
<p><span style="color: rgb(23,43,77);">Cactus and Weaver were merged to
one project "Cacti." </span></p>
</blockquote>
<p><span style="color: rgb(23,43,77);">While the Hyperledger website
already shows Cacti as project, there are still two github projects. Is
there already a plan to create github.com/hyperledger/cacti and continue
efforts there? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by bur at Jan
18, 2023 15:06 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-80775850"></span>
<p>Yes, Marcus. There is a process we've outlined to do that. It's been
held up because there have been several pending PRs in Weaver which
needed to be merged before we could do the final port. Hopefully any day
now.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vramaiitkgp
at Jan 18, 2023 17:08 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-80775852"></span>
<p>The template was updated, but this looks like a copy-paste</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ryjones at Jan 18, 2023 18:58 </div ></td>
</tr>
</tbody>
</table>




