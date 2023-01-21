---
layout: default
title: 2020 Q3 Hyperledger Sawtooth
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Sawtooth

Created by Andrea Gunderson, last modified by Gari Singh on Sep 17, 2020

# Project

Hyperledger Sawtooth
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow"><span>https://sawtooth.hyperledger.org/ </span></a>

# Project Health

The primary focus of the last quarter was starting to work in earnest on
the next generation of Sawtooth. This marks a return to active
development on the core platform.

The Sawtooth community is actively engaging in live, public working
sessions to decide Sawtooth's future. Some community members have
expressed interest in contributing to new Sawtooth features, and others
have promised to contribute enhancements and features that are not yet
open source.

# Questions/Issues for the TSC

No new issues.

# Releases

-   Sawtooth Core v1.2.5 - 7/1/2020
-   Sawtooth Rust SDK v0.4.4 - 5/5/2020

# Overall Activity in the Past Quarter

The community continues to discuss Sawtooth-related issues on Rocketch"at and the mailing list. Live working sessions have also been used on a
semi-regular basis to discuss the future of Sawtooth, with strong
participation from the community.

Development on the core platform has substantially picked up with a
number of code contributions. The following key work has been completed
in the Sawtooth codebase:

-   The majority of the Rust code has been moved from the validator in
the sawtooth-core repository to the sawtooth library in the new
sawtooth-lib repository. This is the first big step toward the next
major version of Sawtooth.
-   The Transact compatibility feature (\`transact-compat\`) was
stabilized and made available for the Sawtooth Rust SDK v0.4.4
release. This moves Sawtooth another step closer to fully adopting
Hyperledger Transact.
-   A major bug in the validator that was affecting the decoding of
state values in some edge cases was fixed and released with Sawtooth
v1.2.5.
-   Building and linting has been enhanced by the addition of a justfile
to the sawtooth-core and sawtooth-sdk-rust repositories.

# Current Plans

Plans will continue to be developed as part of the working sessions.

The following work is currently planned:

-   Replace the direct use and export of protobufs in the Sawtooth
library with protocol structs written in Rust
-   Replace the Transaction Execution Platform (TEP) implementation in
the Sawtooth validator with Hyperledger Transact
-   Initialize a Sawtooth service for Splinter
-   Move portions of Sawtooth Sabre to Hyperledger Transact

Maintainers are investigating options for defining some
easy-to-get-started work to attract a wider set of low-volume
contributors.

# Maintainer Diversity

Maintainers are distributed across
<a href="http://bitwise.io/" class="external-link" rel="nofollow"><span>Bitwise </span></a> IO, Cargill, Intel, and Walmart
Labs.

# Contributor Diversity

Commits from 2020-03-01 to 2020-06-30 :  190

Committers from 2020-03-01 to 2020-06-30 :  10

Domains from 2020-03-01 to 2020-06-30 :  4

# Additional Information

None

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






