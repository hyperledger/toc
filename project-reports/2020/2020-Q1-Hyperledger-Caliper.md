---
layout: default
title: 2020 Q1 Hyperledger Caliper
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Caliper

Created by Attila Klenik, last modified by Gari Singh on Apr 27, 2020

# Project Health

-   The core code-base continues getting cleaner and more modular. The
goal is to make many of the internal features behave like plugins,
following a general schema. Based on this approach, contributors can
easily add new features in a well-defined, localized manner, without
being familiar with the entire code-base.
-   The documentation pages are also being improved to provide a
top-down introduction into Caliper's architecture and further
technical details. Hopefully, a quick overview of the important
parts of a Caliper project will help users navigate the available
examples easier.
-   Caliper is now continuously published to NPM and DockerHub upon
every merged PR, providing immediate access to experimental features
in the same manner as a stable release does.
-   <span style="color: rgb(23,43,77);">Community relations mainly
happen on Rocket.Chat, and the questions are answered in detail, and
on time. Furthermore, there is an increasing contributor/user
interest related to the supported DLTs (Besu, Fabric v2). </span>

# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">There are no issues at this time.</span>

# Releases

-   v0.3.0 was released on the 4th of March, 2020 (
<a href="https://github.com/hyperledger/caliper/releases/tag/v0.3.0" class="external-link" rel="nofollow">GitHub release notes</a> ).
*Fun fact: the "release button" was pressed live during Nick
Lincoln's Global Forum presentation on Caliper.*
-   v0.3.1 patch is coming soon with Fabric v2 support.

# Overall Activity in the Past Quarter

-   **Project stats (since the last report)**
-   Issues closed: 33
-   PRs merged: 58
-   **Development-related **
-   MQTT-based messaging was added for the master and worker
processes to support truly distributed Caliper deployments, i.e.
horizontal scaling.
-   Enhanced the Caliper CLI and the Docker image to make the
distributed usage easier.
-   Continuous delivery was implemented to provide unstable releases
upon every merged PR.
-   The previously deprecated Hyperledger Composer support has now
been removed.
-   The introductory pages of the documentation have been
restructured and improved.

# Current Plans

After the v0.3.1 patch for Fabric v2 support, v0.4.0 will address the
followings:

-   Identify the parts of the code-base that fit the description of a
"plugin" (like performance and resource monitors in the master
process, TX monitors in the worker processes).
-   Make such plugins as object-oriented as possible, following strict
interfaces and life-cycle management.
-   Streamline data flow in/between the Caliper processes, thus
simplifying the code-base and improving performance and robustness. 

<span style="color: rgb(23,43,77);">Subsequent releases will target the
improvement of platform supports, starting with the existing adapters.</span>

# Maintainer Diversity

<span style="color: rgb(23,43,77);">The list of maintainers remained
unchanged since the last report. </span>

# Contributor Diversity

<span style="color: rgb(23,43,77);">There are currently 32 contributors
to the repository, 17 of them with more than one commit. To the best of
our knowledge, contributors are from various companies/organizations,
such as Huawei, IBM, Intel, Soramitsu, Budapest University of Technology
and Economics, Monax and the University of Oregon. The maintainers are
also keeping in touch with other companies who are mainly interested in
expanding the platform support of Caliper (e.g., with Corda). </span>

# Additional Information

N.A.

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






