---
layout: default
title: 2022 Q1 Hyperledger Besu
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Besu

Created by Danno Ferrin, last modified by Bobbi Muscara on Apr 07, 2022



# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Besu remains a strong
project with a growing community network of contributors. This quarter
the team has passed a major milestone for the Ethereum Mainnet "merge" update as well as supporting the Ethereum Classic Mystique Hard Fork.</span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? - Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? - Yes </span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? - Yes </span></span>
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? - Yes ( [Point
5](https://wiki.hyperledger.org/display/BESU/Documentation+style+guide)
)</span> </span>

# Questions/Issues for the TSC

None at this time

# Releases

-   21.10.5 - 19 Dec 2021
-   21.10.6 -  4 Jan 2022
-   22.1.0-RC2 - 6 Jan 2022
-   21.0.7 - 13 Jan 2022
-   21.0.8 - 16 Jan 2022
-   21.0.9 - 19 Jan 2022
-   22.1.0-RC3 - 25 Jan 2022
-   22.1.0-RC4 - 30 Jan 2022
-   22.1.0 - 16 Feb 2022
-   22.1.1 - 24 Feb 2022
-   22.1.2 - 15 Mar 2022

More releases occurred than typical for the 22.10.x cycle because an ETC
hard fork occurred during the 22.1.x release cycle, some fixes related
to merge testing, and one regression.

# Overall Activity in the Past Quarter

-   **Mainnet Paris Upgrade
**Previously known as "the merge" a critical test event known as
"kiln testnet" successfully occurred, with Besu fully
participating.
Key areas include synchronization and consensus layer communication
APIs.
-   **QBFT
**Marked as production ready
-   **EVM Library
**Investigated removing the "Gas" object to reduce short lived
object garbage collection.
-   **Tracing**
Exposed new tracing methods and added revert reason to traces.

# Current Plans

-   **Migration to Java 17**
In the 22.7.x cycle Besu will move to Java 17 as the required JVM.
-   **Paris Upgrade
**Paris will ship when it's ready, but final preparations are at hand.
-   **Shanghai Fork**
The first fork after The Merge is expected to add some long overdue
EVM improvements, such as the Ethereum Object Format.
-   **Developer experience
**Planning to add a work stream to specifically focus on developer
experience, allowing prioritization of issues alongside feature
work.

# Maintainer Diversity

One maintainer was moved to Emeritus status this quarter (Vijay
Michalik), reducing the non-consensys maintainer share to 17.8% (5 of
28).

Corporate distribution is unchanged from the last quarters report
(ConsenSys, Splunk, Hedera, ETC Co-operative)

# Contributor Diversity

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fbesu/dashboard;subTab=technical?time=%7B%22from%22:%222021-12-16T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-03-24T06:00:00.000Z%22%7D" class="external-link" rel="nofollow">LFX Insights Report</a>   

# Additional Information

Hyperledger, the Ethereum Foundation, and ConsenSys are still working
through the final agreements and documentation for the Client Incentive
Program. But, in this quarter, the community agreed on following
Proposal \#4 for setting up the program.

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

<span class="placeholder-inline-tasks"> 23-Mar-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62246418"></span>
<blockquote>
<p><span style="color: rgb(23,43,77);">Hyperledger, the Ethereum
Foundation, and ConsenSys are still working through the final agreements
and documentation for the Client Incentive Program. But, in this
quarter, the community agreed on following Proposal #4 for setting up
the program. </span></p>
</blockquote>
<p><span style="color: rgb(23,43,77);">What is proposal #4? </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Mar
28, 2022 20:56 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62246419"></span>
<blockquote>
<p>One maintainer was moved to Emeritus status this quarter (Vijay
Michalik), reducing the non-consensys maintainer share to 17.8% (5 of
28).</p>
</blockquote>
<p>Are there plans to turn this metric around? What can be done to
reduce the Consensys maintainer share and increase the non-Consensys
maintainer share?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Mar
28, 2022 20:57 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62246438"></span>
<p>It'd be beneficial to clarify in the section about that the big
merge, that it is mainly involving the public side of things, for Teku
and Besu to run together in order to support PoS on the mainnet, as I'm
not sure this is clear to someone who may not be following the "Eth2" project closely.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jimthematrix
at Mar 28, 2022 22:09 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62246580"></span>
<p>Here's the wiki page -  <a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=62239637">[WIP]
Proposal #4</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Mar 29, 2022 14:41 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62246581"></span>
<p>Teku is not the only beacon chain client that works with Besu. There
are 5 different Consensus Layer (CL) clients: Nimbus, Lighthouse, Teku,
Prysm, and Loadstar.  The Kiln merge has a page listing how people could
participate in that event ( <a href="https://notes.ethereum.org/@launchpad/kiln#Which-versionbranch-do-I-use" class="external-link" rel="nofollow">https://notes.ethereum.org/@launchpad/kiln#Which-versionbranch-do-I-use</a>
). I expect similar documentation from the EF for the next testnet
merges and the mainnet merge.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Mar 29, 2022 14:46 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62246983"></span>
<p>need more clarity on this incentive program, it looks like some
transaction fees in Eth will be shared among Hyperledger, Consenys and
other maintainers. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by knagware9 at Mar 31, 2022 13:44 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62246987"></span>
<p><img src="emoticons/thumbs_up.svg" class="emoticon emoticon-thumbs-up" data-emoticon-name="thumbs-up" alt="(thumbs up)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jimthematrix
at Mar 31, 2022 14:04 </div ></td>
</tr>
</tbody>
</table>




