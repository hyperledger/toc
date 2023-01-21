---
layout: default
title: 2020 Q4 Hyperledger Avalon
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Avalon

Created by Eugene Yarmosh, last modified by Gari Singh on Feb 05, 2021

<span style="letter-spacing: 0.0px;"> <span style="color: rgb(23,43,77);">Prepared by Eugene (Yevgeniy) Yarmosh</span> </span>

# Project

<a href="https://wiki.hyperledger.org/display/avalon/Hyperledger+Avalon" rel="nofollow" style="text-decoration: none;">Hyperledger Avalon</a>

# Project Health

The project health is good. The team focused on improving integration
with K8S, worker pool scalability, multitenancy support and Graphene
runtime integration.

Divya Taori became a new project maintainer.

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Favalon/dashboard?time=%7B%22from%22:%222020-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-31T08:00:00.000Z%22%7D" class="external-link" rel="nofollow">LF Analytics for Q4</a>

# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">There are no issues for the TSC
currently. </span>

# Releases

Last release was done in July 2020.  <span style="color: rgb(23,43,77);">No new releases have been done during Q4.</span>

<span style="color: rgb(23,43,77);">Due to the nature and complexity of
the currently built capabilities the team decided to postpone the
release to Q1/2021 in order to get to an appropriate completeness point
function-wise.  </span>

# Overall Activity in the Past Quarter

The project development was focused on the following areas

-   Work-order Processing Enclave (WPE) implementation
-   Kubernetes integration with elastic compute support
-   Extending SGX attestation model to support 3 <sup>rd</sup>   party
attestation (aka DCAP)
-   Worker attestation support for SGX KSS (Key Sharing and Separation)
as a steppingstone for supporting multi-tenancy (aka dedicated
worker instances for tenants without any code changes)
-   Integration of high-level LibOS runtimes Graphene as worker
processing enclave
-   CentOS Support (in addition to Ubuntu)
-   Improving test <span style="color: rgb(0,0,0);">automation </span>
and CI
-   CII Best Practices Badge Complete

Avalon team participated in the following activities:

-   Continued regular Avalon Technical Forum calls every other week with
a good community participation   
-   Presented Hyperledger Avalon at EEA Financial Services SIG
-   Continuously utilized email and rocket chat for community support

There were lower number of Avalon presentations at the industry forums,
partially, due to some event cancellations. This is an area needs to
focus in 2021. 

# Current Plans

The team is working towards release 0.7 that includes

-   Completion of the worker pool implementation
-   Finalize DCAP attestation support
-   Key management enclave replication (final part of the worker pool
scalability design)
-   Secure cross-worker (Graphene) communication channel
-   Multi-threading support for the key management enclave
-   Multi-tenancy (dedicated worker instances per requester)
-   Improved Python SDK as a separate subproject
-   Improving test coverage and CI

The team also evaluation plans to increase number Avalon presentations
at various industry events. 

# Maintainer Diversity

Divya Taori from Wipro became a Hyperledger Avalon maintainer.     

# Contributor Diversity

<span style="color: rgb(23,43,77);">Contributor diversity is gradually
improving. ASUS joint the project and contributed during the previous
quarter. We have an interest in contributing starting from Q1/2021 from
China Unicom. </span>

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>






