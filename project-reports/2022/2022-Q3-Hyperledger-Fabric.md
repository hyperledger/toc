---
layout: default
title: 2022 Q3 Hyperledger Fabric
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Fabric

Created by David Enyeart, last modified on Jul 21, 2022

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Fabric is fairly mature
and stable with a Long-term support (LTS) release and incremental new
features being added in minor releases. There is less churn and fewer
commits than in years past, with continued focus on quality and support.
New features get proposed, approved, and implemented based on a
community RFC process. Mailing list activity is down compared to prior
years. PRs and mailing list questions are generally turned around
quickly. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? YES </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? YES </span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? YES You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. </span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? YES</span> </span>

# Questions/Issues for the TSC

None.

# Releases



v2.2 is the current LTS releases with patch releases approximately
quarterly.

Releases past quarter:

-   Fabric v2.2.6 - June 17, 2022
-   Fabric v2.2.7 - July 1, 2022
-   Fabric v2.4.4 - June 17, 2022
-   Fabric v2.4.5 - July 1, 2022

Fabric CA

-   v1.5.4 - June 17, 2022

Fabric Gateway SDKs

-   v1.1 - June 30, 2022 - Brings functional parity relative to the
legacy (deprecated) SDKs.

Additionally, legacy SDKs are regularly patched.

Upcoming releases:

-   Fabric v2.5.0 - Expected to be next LTS release

# Overall Activity in the Past Quarter



The project delivered fixes to the Fabric v2.2 and v2.4 releases, as
well as Fabric CA v1.5 release. The latest Fabric and Fabric CA releases
were updated to utilize Go 1.18.

Work is underway to implement the Purge Private Data History feature,
targeted for v2.5 later this year. Additionally for v2.5  <span class="blob-code-inner blob-code-marker">many project dependencies were
updated including a somewhat invasive update in the ordering service for
etcd and protobuf. </span>

The new Gateway SDKs were updated to support checkpointing for chaincode
events, block events, and off-line signing so that they will have parity
with the legacy (deprecated) SDKs, enabling existing users to move up to
the new Gateway SDKs that simplify application logic.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow" style="text-decoration: none;">RFCs
merged</a>   this quarter:

-   <a href="https://github.com/hyperledger/fabric-rfcs/blob/main/text/orderer-v3.md" class="external-link" rel="nofollow">Ordering service refactor for BFT
support</a>

**Related Projects**

-   **Caliper** project was updated to utilize the Fabric Gateway SDK
along with general updates, released as Caliper v0.5.
-   **Fabric-operator** - IBM contributed the kubernetes operator th"at powers IBM Blockchain Platform as a Hyperledger lab - 
<a href="https://github.com/hyperledger-labs/fabric-operator" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/fabric-operator</a>
. The intent is to socialize with the community this quarter and
determine if this lab can help to coalesce the various Fabric
deployment solutions that have been made available over the last
couple years.

# Current Plans



<span class="blob-code-inner blob-code-marker">The project is working on
a v2.5.0 release with a feature to Purge the history of private data.
The feature may help organizations meet GDPR requirements with the
ability to delete private data while preserving a hash of the data on
the blockchain. The v2.5 release is expected to become the next
long-term support release.  </span>

<span class="blob-code-inner blob-code-marker">Fabric v3.0 release was
kicked off with the merge of the ordering service refactor RFC. The
refactor is underway and will enable the addition of BFT consensus
algorithms with intent to integrate SmartBFT initially. </span>

<span class="blob-code-inner blob-code-marker">The project is working on
a workshop that will help users with Fabric deployment and application
development, with initial workshop delivery at Hyperledger Global Forum.</span>

# Maintainer Diversity

6 of 8 maintainers from IBM.

# Contributor Diversity



Year to year comparison, by commit:

-   Q2 2021 - 403 commits. 61% from IBM.
-   Q2 2022 - 319 commits. 59% from IBM

Year to year comparison, by contributor:

-   Q2 2021 - 74 contributors. 32% from IBM.
-   Q2 2022 - 54 contributors. 31% from IBM.

# Additional Information

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222022-04-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-07-01T03:00:00.000Z%22%7D" class="external-link" rel="nofollow">Insights dashboard for Q2</a> .

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   🔲 <span class="placeholder-inline-tasks">
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

<span class="placeholder-inline-tasks"> 06-Jul-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71697947"></span>
<blockquote>
<p><span class="blob-code-inner blob-code-marker">Fabric v3.0 release
was kicked off with the merge of the ordering service refactor RFC. The
refactor is underway and will enable the addition of BFT consensus
algorithms with intent to integrate SmartBFT initially. </span></p>
</blockquote>
<p><span class="blob-code-inner blob-code-marker">Such a good news <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /> </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by C0rWin at Jul
07, 2022 09:14 </div ></td>
</tr>
</tbody>
</table>




