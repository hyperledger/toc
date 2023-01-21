---
layout: default
title: 2020 Q1 Hyperledger Avalon-Project-Update
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Avalon-Project-Update

Created by Eugene Yarmosh, last modified by Gari Singh on Apr 27, 2020

Prepared by Eugene (Yevgeniy) Yarmosh

# Project Health

The Avalon team successfully accomplished its plans for this quarter and
is on track to release 0.5 version in March. This release supports proxy
model and integrates with Ethereum (Hyperledger Besu) and Hyperledger
Fabric blockchains. It also includes improved Inside-Out API
implementation, encryption key update logic, improved documentation and
tutorials. The team also completed several prototypes focused on
integration with K8S and made a progress refining Avalon architecture.
The Avalon team actively participated in Hyperledger Global Forum.
Upcoming release 0.6 will focus on adding enclave pools, key management
isolation from the transaction execution, and an initial K8S
integration. The team continues to improve its processes and building up
community.


# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">There are no issues for the TSC at this time. </span>

# Releases

March 2020 - Release 0.5. This release was focused on proxy model
implementation and integration of Hyperledger Besu and Hyperledger
Fabric blockchains.

April 2020 – a minor release 0.5.1 is planned to address few bugs and
missing corner cases.

The plan for releases (0.6, 0.7, ...) to be done roughly quarterly in
2020.

# Overall Activity in the Past Quarter

Avalon team was focused on building proxy model functionality and
exploratory activities related to future releases focused on scalability
and key management isolation.

During work on 0.5 version released in March the Avalon team

-   Integrated Hyperledger Fabric in the Avalon proxy model
-   Integrated Hyperledger Besu in the Avalon proxy model
-   Added a security layer to the inside-out API
-   Implemented policy-based worker encryption key
-   Prototyped K8S as a foundation for scalable worker execution
orchestration
-   Evaluated Occlum as a candidate for integration with Avalon
-   Added new use cases, e.g. Cold Chain presented at HGF (by WiPro)
-   Updated tutorial to include the proxy model with Fabric and Besu
-   Updated tutorial to include the inside-out API
-   Defined of architecture for separation of key management from
workload processing 
-   Defined architecture for the scalable orchestration layer
-   Improved project documentation and Wiki based on the feedback from
the last quarter

Avalon team participated in the following activities:

-   Avalon Workshop at Hyperledger Global Forum
-   Avalon project kiosk and Confidential Compute presentations at Hyperledger Global Forum
-   Trusted Compute precompiled smart contract proposal is accepted by EEA to become a part of Ethereum Enterprise Client spec
-   Avalon presentation at Hyperledger Bootcamp in Moscow
-   Avalon tech talk in Hyperledger India chapter National e-Meetup

# Current Plans

The Avalon plans include following releases

-   6 – worker pools with key management isolation
-   7 – elastic scalability and broader runtime support
-   8 – performance optimization and Avalon SDK

Next release 0.6 will focus on

-   Initial implementation of scalable worker pools
-   Key management isolation from the workorder execution
-   Baseline work order scheduler with pluggable orchestration adaptors
-   Baseline Kubernetes engine integration (without elastic compute)
-   Extending SGX attestation model to support 3 <sup>rd</sup> party
attestation (aka DCAP)
-   Prototypes for integration of high-level (e.g. LibOS based) runtimes
-   Adding attested oracles end-to-end use case (to be contributed by Chainlink)
-   Updating and refactoring CI
-   Refining Avalon Architecture with focus on scalability and
multi-tenancy

The team plans to start a more efficient use of JIRA for the project
management and will continue to build up WiKi content. In addition to
Avalon Developer Forum calls (every other weeks) the plan includes
starting a new series of Avalon Architecture Forum calls.

Grow Avalon community and increasing the diversity of its maintainer and
contributor base continues to be a priority. Since face-to-face meetups
and other venues are limited due to coronavirus, emphasis will be made
on publishing technical blogs, user case studies, and video tutorials at Hyperledger, EEA, and other suitable on-line venues.

# Maintainer Diversity

Avalon maintainers has not changed during this quarter, but we see gre"at code contributions by several team members that constitute Avalon
maintainers candidate list. Based on the recent activity and our current
plans we anticipate that the Avalon maintainers list will be extended
within couple release cycles.

# Contributor Diversity

Avalon code contributions come from multiple companies – Intel, IBM,
iExec, WiPro, Consensys/Kaleido, Santander, Espeo, and (planned for 0.6)
Chainlink. Several more companies are considering their contributions
for upcoming Avalon releases.
Avalon Developer Forum calls happens every other week attended by members from different organizations. Additionally, an Architecture
Forum is planned to start also every other week.
Avalon was presented at the Hyperledger Global Forum during Avalon
Workshop and other presentations. They generated a significant interest
from the broader Hyperledger community that is expected to result in
additional Avalon contributors. We plan to continue drive a broader
Avalon awareness via EEA, Hyperledger, and other industry venues, this
time focusing on on-line options.



# Additional Information

None at this time.

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






