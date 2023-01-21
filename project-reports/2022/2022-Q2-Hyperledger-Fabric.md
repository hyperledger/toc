---
layout: default
title: 2022 Q2 Hyperledger Fabric
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q2 Hyperledger Fabric

Created by David Enyeart, last modified by Angelo De Caro on May 19, 2022

<span style="letter-spacing: 0.0px;"> </span> <span style="font-size: 24.0px;letter-spacing: 0.0px;">Project Health </span>

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
inclusive language changes listed below to your repo? YES. You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. </span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? YES (already had one, but replacing
it with the TSC recommended guidelines in 
<a href="https://github.com/hyperledger/fabric/pull/3344" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric/pull/3344</a>
)</span> </span>

# Questions/Issues for the TSC

None.

# Releases

v2.2 is the current LTS releases with patch releases approximately
quarterly.

Releases past quarter:

-   Fabric v2.2.5 - January 28, 2022
-   Fabric v2.4.2 - January 28, 2022
-   Fabric v2.4.3 - February 25, 2022

Additionally, SDKs are regularly patched.

Upcoming releases:

-   v2.5.0 - Expected to be next LTS release

# Overall Activity in the Past Quarter



The project delivered fixes to the v2.4.x release, primarily hardening
the new Fabric Gateway feature that was delivered in v2.4.0. The new
Gateway SDKs are also being updated to support checkpointing for
chaincode events, block events, and off-line signing so that they will
have parity with the legacy SDKs, enabling existing users to move up to
the new Gateway SDKs that simplify application logic.

Additionally the Fabric v2.2.5 and v2.4.2 releases, and Fabric CA v1.5.3
release updated Fabric to utilize Go 1.17.

Work is underway to implement the Purge Private Data History feature.

<a href="https://github.com/hyperledger/fabric-rfcs/tree/master/text" class="external-link" rel="nofollow" style="text-decoration: none;">RFCs
merged</a>   this quarter:

-   <a href="https://github.com/hyperledger/fabric-rfcs/pull/48" class="external-link" rel="nofollow" style="text-decoration: underline;">Byzantine Fault Tolerant block
replication and block signature verification</a>

Other   <a href="https://github.com/hyperledger/fabric-rfcs/pulls" class="external-link" rel="nofollow" style="text-decoration: none;">RFCs
are in review</a>  , most notably a proposed refactoring of the ordering
service nodes to support Byzantine Fault Tolerant ordering.

Finally, project samples have been updated including:

-   Asset transfer samples with new Gateway SDK -   <a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow" style="text-decoration: none;">https</a> <a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow" style="text-decoration: none;">://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.</a>
<a href="https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html" class="external-link" rel="nofollow" style="text-decoration: none;">html</a>
-   Kubernetes Test Network -   <a href="https://github.com/hyperledger/fabric-samples/tree/main/test-network-k8s" class="external-link" rel="nofollow" style="text-decoration: none;">https://github.com/hyperledger/fabric-samples/tree/main/test-network-k8s</a>

# Current Plans



**<span class="blob-code-inner blob-code-marker">Releases </span>**

<span class="blob-code-inner blob-code-marker">The project is working on
a v2.5.0 release with a feature to Purge the history of private data.
The feature may help organizations meet GDPR requirements with the
ability to delete private data while preserving a hash of the data on
the blockchain. The v2.5 release is expected to become the next
long-term support release. As such, many project dependencies are being
updated including a somewhat invasive update in the ordering service for
etcd and protobuf. </span>

<span class="blob-code-inner blob-code-marker">Discussion about a future
Fabric v3.0 release was kicked off. The proposal is to refactor some
Fabric components so that new features can be more easily added on top,
most notably a proposed BFT ordering service. </span>

**Documentation**

Fabric community documentation meetings have been resumed with initial
focus on the following Fabric documentation areas:

-   Certificate management (expirations, renewals)
-   Chaincode as a service

**Performance**

Update Caliper client for Fabric gateway SDK (nearing completion).

# Maintainer Diversity

<span style="color: rgb(23,43,77);">With some inactive maintainers
retired, we now have 6 of 8 maintainers of core Fabric from IBM. </span>

# Contributor Diversity

Year to year comparison, by commit:

-   Q1 2021 - 780 commits. 73% from IBM.
-   Q1 2022 - 326 commits. 79% from IBM

Year to year comparison, by contributor:

-   Q1 2021 - 80 contributors. 51% from IBM.
-   Q1 2022 - 75 contributors. 31% from IBM.

# Additional Information

<span style="color: rgb(23,43,77);">Link to the Fabric dashboard: <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222022-01-01T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-04-01T03:00:00.000Z%22%7D" class="external-link" rel="nofollow">Q1 2022</a> </span>

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 21-Apr-2022 </span>






