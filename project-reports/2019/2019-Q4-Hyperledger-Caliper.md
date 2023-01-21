---
layout: default
title: 2019 Q4 Hyperledger Caliper
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Caliper

Created by Attila Klenik, last modified by Nathan George on Mar 31, 2020

# Project Health

Since the first published release, the maintainers are working on
improving the quality of the core code-base. Besides the obvious reasons
for this, we also expect that a cleaner code-base will lower the entry
barrier for new contributors.

Community relations mainly happen on Rocket.Chat, and the questions are
answered in detail, and on time. Furthermore, there is an increasing
contributor interest related to the supported DLTs (both improving
recent adapters and implementing new ones, like for Corda).

# Questions/Issues for the TSC

There are no issues at this time.

# Releases

v0.2.0 was released on 25th October (on npm and DockerHub), see the
<a href="https://github.com/hyperledger/caliper/releases/tag/v0.2.0" class="external-link" rel="nofollow">GitHub release page</a> . 

v0.3.0 is coming soon.

# Overall Activity in the Past Quarter

-   **Project stats (since the last report)**
Issues closed: 27
PRs merged: 73
-   **Development-related**
-   Exposed Prometheus metrics about client-side observations
-   Added highly flexible logging subsystem
-   Added platform support for Ethereum, Hyperledger Besu and
FISCO-BCOS (all of them community contributions)
-   Released v0.2.0
-   Consolidated CI tests
-   Improved the result reporting, including embedded charts
-   Deprecated the Composer support
-   Added Yeoman generators for Caliper-related benchmark artifacts
(plugin skeletons, configuration files)

# Current Plans

Current development efforts are focusing on the following, core
code-base related tasks (for the v0.3.0 release):

-   Reimplementing the distributed workload generation (which was
removed in a previous release) using MQTT
-   Cleaning up the communication and dataflow in the worker and manager
modules
-   Resulting in a highly modular architecture, which is easily
extensible
-   Increasing workload generation performance by pushing
aggregation tasks from the workers to the manager
-   Preparing a CI/CD for a rolling unstable release upon every merged
PR (so the stable releases will have robust feature sets) 

Subsequent releases will target the improvement of platform supports,
starting with the existing adapters.

# Maintainer Diversity

The list of maintainers remained unchanged since the last report.

# Contributor Diversity

There are currently 30 contributors to the repository, 17 of them with
more than one commit. To the best of our knowledge, contributors are
from various companies/organizations, such as Huawei, IBM, Intel,
Soramitsu, Budapest University of Technology and Economics, Monax and
the University of Oregon. The maintainers are also keeping in touch with
other companies who are mainly interested in expanding the platform
support of Caliper (e.g., with Corda).

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
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






