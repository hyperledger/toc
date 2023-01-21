---
layout: default
title: 2020 Q3 Hyperledger Caliper
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Caliper

Created by Nick Lincoln, last modified by Gari Singh on Oct 22, 2020

# Project

<a href="https://github.com/hyperledger/caliper" class="external-link" rel="nofollow" style="text-decoration: underline;">Hyperledger
Caliper</a>

# Project Health

-   The core code-base has been reworked to make it cleaner and more
modular. All components now behave like plugins, following a general
schema. Because of this, contributors can easily add new features in
a well-defined, localized manner, without being familiar with the
entire code-base.
-   The documentation pages have been improved to provide hands-on
tutorials about setting up Caliper with well-known examples of
different DLTs. These are to be expanded.
-   <span style="color: rgb(23,43,77);">Community relations mainly
happen on Rocket.Chat, and the questions are answered in detail, and
on time. Furthermore, there is an increasing contributor/user
interest related to the supported DLTs (Besu, Ethereum, Fabric v2).</span>

# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">There are no issues at this time.</span>

# Releases

Working on releasing 0.4.0, within which the core code has been
significantly refactored. Expect to release end of September 2020

# Overall Activity in the Past Quarter

**Project stats (since the last report)**

-   Issues closed: 62
-   PRs merged:53

**Development-related **

-   Keeping up with Fabric 2.x releases
-   Core code refactor for clarity and modularisation
-   Terminology changes/consolidations (adapter→connector,
master→manager, callback→workload module, using "contract" everywhere)
-   Simplification of the SUT connector API, with accompanying
documentation to make the implementation of new connectors and
maintenance of current connectors easier.

# Current Plans

v0.5 will include enhancements, including but not limited to

-   Replacement of fabric connector
-   Splitting out of configuration files to enable better use of shared
configuration options


We intend to increase unit test code coverage, to augment the existing
integration test suite

We would like to increase the maintainer list for target connectors,
having at least one point of contact per Hyperledger SUT to assist in
the development and maintenance of SUT connectors.

# Maintainer Diversity

<span style="color: rgb(23,43,77);">The list of maintainers remained
unchanged since the last report. </span>

# Contributor Diversity

There are 40 contributors, 20 with noteworthy contributions.  <span style="color: rgb(23,43,77);">To the best of our knowledge, contributors
are from various companies/organizations, such as Huawei, IBM, Intel,
Soramitsu, Budapest University of Technology and Economics, Monax, and
the University of Oregon. </span>

# Additional Information

Following from the refactor to be included within the 0.4 release, and
the intended additions within the 0.5 release, the maintainers would
like to work towards a 1.0 release

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






