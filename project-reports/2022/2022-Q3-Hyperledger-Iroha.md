---
layout: default
title: 2022 Q3 Hyperledger Iroha
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Iroha

Created by Victor Gridnevsky, last modified on Oct 13, 2022

# Project Health

Iroha 1 is no longer actively maintained, and no major releases are
planned at this time. However, Iroha 1 still receives regular
contributions from outside the core development team, 
<a href="https://github.com/baziorek" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Grzegorz Bazior</span></a>  contributing himself, and organizing contributions from his
students. The Iroha 2 team is doing bug triage for both projects and
implements security fixes for Iroha 1.

Iroha 2 is ramping up production. All developers are now fully onboarded
and at maximum productivity. We have implemented a crude delineation of
responsibilities, and implemented all processes for long-term
development. We are following a timed release cadence, with  <span class="ui-comment-inline-span">a </span>  Long-term supported release
planned at critical stability milestones. Iroha 2 repository is well
organised, with branch protection rules enforced for all main branches (
**`iroha2-stable `** ,  **`iroha2-dev `** ,  **`iroha2-lts `** , 
**`iroha2-staging `** ) as well as a common
<a href="https://en.wikipedia.org/wiki/CI/CD" class="external-link" rel="nofollow">CI/CD</a> pipeline with thorough testing/linting and API
verification systems.

Work is underway to bring the supporting libraries up to feature parity
with the Rust library. Particular efforts are made to improve the Iroha
Python library to be available for testing and automation. Additionally,
a Hyperledger Cactus plugin is developed based on the Iroha typescript
library. Additional tooling is made for improving the UX, and the
Blockchain explorer is nearing the minimum viable product state.
Finally, Iroha Kotlin is going to be used as a basis for a public test
network, where we will analyse real-world usage statistics and use the
data-driven optimisation approaches to further improve Iroha 2.

## Questions/Issues for the TSC

We have a few issues in relation to Hyperledger Ursa. For example, due
to its release cadence and relative lull in development activity, we had
had to hold back a few dependencies in order to remain binary compatible
with the  **`Errors `**  returned from Ursa methods. Our automated
auditing tools have identified several deprecations as well as
unmaintained libraries which cannot be simply “version bumped” into
Ursa.

<a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=2393113" rel="nofollow" style="text-decoration: none;"><span>Ry Jones </span></a>
 suggested that we take over some of the maintenance burden,
particularly ensuring that the code quality of Ursa is up to the same
high standards that we ensure for Iroha 2 (linting, reviews, release
timing, auditing, fresh dependencies, dependency pruning, automated
feature flag coherence testing, property-based testing, fuzzing,
functional testing, coverage, modularity).

We would also like to involve more people in the development of Iroha
v2, particularly interns and community members. We would like to plan
and discuss a few key issues with  <a href="https://wiki.hyperledger.org/spaces/viewspace.action?key=~davidwboswell" rel="nofollow" style="text-decoration: none;"><span>David Boswell</span></a>  and design a new internship programme that would involve
Iroha 2.

## Releases

Last release reported  <a href="https://wiki.hyperledger.org/display/TSC/2022+Q2+Hyperledger+Iroha" rel="nofollow" style="text-decoration: none;"><span>here </span></a>  "at May 26, 2022.

Timed releases:

-   `v2.0.0-pre-rc.4 `  (internal)
-   `v2.0.0-pre-rc.5 `  (internal)
-   <a href="https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre.rc.6" class="external-link" rel="nofollow" style="text-decoration: none;"><code>v2.0.0-pre-rc.6 (LTS) </code></a>
-   `v2.0.0-pre-rc.7 `  (internal, TBR)

## Overall Activity in the Past Quarter

### Iroha v1

Merged  <a href="https://github.com/baziorek" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Grzegorz Bazior</span></a> ’s PRs:

-   <a href="https://github.com/hyperledger/iroha/pull/2494" class="external-link" rel="nofollow" style="text-decoration: none;"><span>#2494 </span></a> : Update
documentation: AddPeer with  **`syncing_node `**  option
-   <a href="https://github.com/hyperledger/iroha/pull/2475" class="external-link" rel="nofollow" style="text-decoration: none;"><span>#2475 </span></a> : Many
documentation changes, corrections, etc.

### Iroha v2

#### Performance enhancements

We have made several changes to both how we measure performance and how
we improve it.

We now use profiling as a mandatory step: if something causes a
performance regression of more than 10% in throughput and/or latency, we
don’t allow it to be merged.

Based off of that we triggered a series of simplifications and
optimisations which led to increased performance in the 
**`iroha2-staging `**  branch. It is our best bet to increase
throughput.

#### WASM dynamic linkage

Dynamic linkage of WASM binaries allows us to

-   Save space on-chain, since smartcontracts are stored in binary
-   Disallow direct allocations and direct memory manipulations
enhancing security
-   Allow manipulation of opaque objects only, enforcing invariants,
netting even more security
-   Increase the number of available methods and functions

#### New functionality

-   Additional tooling (genesis block builder GUI)
-   Sorting / filtering / pagination of queries, as well as several
additional query types (block headers)

#### Improvements

-   Better permission validation system
-   Trigger improvements (scope, performance, strong typing)
-   Better deployment scheme (fully static linkage, much smaller 
<a href="https://www.docker.com/" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Docker </span></a>  container)
-   Kura API improvements
-   <a href="https://github.com/hyperledger/iroha-python" class="external-link" rel="nofollow" style="text-decoration: none;"><span class="ui-comment-inline-span">Iroha-Python </span></a> <span class="ui-comment-inline-span">   currently works correctly with
Iroha 2 </span>
-   Run-time modular permission validation
-   Simplified Expression subsystem
-   Stability, performance improvements, bug fixes, actor system
improvements
-   Technical debt reduction
-   Testing coverage improvements
-   Introduction of other testing methods (property-based testing,
fuzzing, failure point testing)
-   Better UX (more readable error messages, tutorial, on-peer
documentation)

## Current Plans

-   Resolve Ursa issues by possibly hiring a new developer, who will
address the security issues in it.
-   Improve the contributing process for community members by tracking
PRs with a bot.
-   Involve more community members by producing more content related to
Iroha v2 (blog posts, video demo, tutorial content).
-   Record a detailed demonstration video on Hyperledger Iroha use
with CLI.
-   Integrate examples into the documentation, so the users have fresh
examples easily available and tested. Integrate language-specific
guides into articles with a custom code component.

## Maintainer Diversity

As of writing the Iroha 2 core development team consists of:

-   8 Rust developers + 1 tech lead
-   1 front-end developer
-   2 full-time QA engineers (functional and load testing/benchmarking)
-   1 full-time technical writer
-   1 full-time DevOps
-   1 community manager, who also handles front-end, back-end, DevOps
and writing tasks as needed

Currently, the maintainer team consists of the Soramitsu employees. 
<a href="https://github.com/baziorek" class="external-link" rel="nofollow" style="text-decoration: none;">Gregorz Bazior</a>  (Yonix
Digital Systems, <span style="color: rgb(0,0,0);">AGH University of
Science and Technology </span>) is interested in Iroha 2 and maintains
Iroha 1.

## Contributor Diversity

A new intern working on reimplementing iroha-swarm as a plugin to Kagami
(Iroha 2’s example generation program).

We have had several contributions (
<a href="https://github.com/hyperledger/iroha/pull/2264" class="external-link" rel="nofollow" style="text-decoration: none;"><span>#2264 </span></a> , 
<a href="https://github.com/hyperledger/iroha/pull/2285" class="external-link" rel="nofollow" style="text-decoration: none;"><span>#2285 </span></a> , 
<a href="https://github.com/hyperledger/iroha/pull/2326" class="external-link" rel="nofollow" style="text-decoration: none;"><span>#2326 </span></a> ) from 
<a href="https://github.com/omkar-mohanty" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Omkar Mohanty</span></a>  (intern) , <span class="ui-comment-inline-span">   Tejas
(intern), who has shown interest, but has not contributed code directl</span> y and 
<a href="https://github.com/ritikBhandari" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Ritik Bhandari</span></a>  who contributed the code that was part of 
<a href="https://github.com/hyperledger/iroha/pull/2214" class="external-link" rel="nofollow" style="text-decoration: none;"><span>PR#2125 </span></a>  (add query
for  **`FindAssetDefinitionById `** ).

On the Python side of Iroha, we’ve had valuable input about ergonomics
of the Iroha 2 Python 
<a href="https://github.com/hyperledger/iroha-python/tree/iroha2" class="external-link" rel="nofollow" style="text-decoration: none;"><span>library </span></a>  from 
<a href="https://github.com/baziorek" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Gregorz Bazior</span></a>  (Yonix Digital Systems, <span style="color: rgb(0,0,0);">AGH University of Science and Technology</span>) .

# Reviewed By

-   🔲 <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>  </span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks">18-Aug-2022, added the review
section at 1-Sep-2022 </span>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71700273"></span>
<p><a href="https://wiki.hyperledger.org/display/~vgridnevsky" class="confluence-userlink user-mention" data-username="vgridnevsky" data-linked-resource-id="71699145" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Victor Gridnevsky</a> : If
this is ready for review by the TSC, please add the TSC as reviewers to
the bottom of the web page similar to what you see in the template.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Aug
23, 2022 18:00 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71700758"></span>
<p><a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> excuse me,
I've added the review section.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vgridnevsky
at Sep 01, 2022 10:56 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71700824"></span>
<ul class="incremental">
<li><blockquote>
<a href="https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre.rc.6" class="external-link" rel="nofollow" style="text-decoration: none;"><code>v2.0.0-pre-rc.6 (LTS) </code></a>
</blockquote></li>
</ul>
<p>I am not sure how a release candidate (rc) is marked as a long-term
support (LTS) version. Can you explain how that works?</p>
<p>From <a href="https://en.wikipedia.org/wiki/Long-term_support" class="external-link" rel="nofollow">wikipedia</a> :</p>
<blockquote>
<p><strong>Long-term support</strong> <span style="color: rgb(32,33,34);"> <span>  </span>( </span>
<strong>LTS</strong> <span style="color: rgb(32,33,34);">) is a <span> </span> </span> <a href="https://en.wikipedia.org/wiki/Product_lifecycle_management" class="external-link" rel="nofollow" style="text-decoration: none;" title="Product lifecycle management">product lifecycle management</a>
<span style="color: rgb(32,33,34);"> <span>  </span> </span> <a href="https://en.wikipedia.org/wiki/Policy" class="external-link" rel="nofollow" style="text-decoration: none;" title="Policy">policy</a>
<span style="color: rgb(32,33,34);"> <span>  </span>in which a <span> </span> </span> <a href="https://en.wikipedia.org/wiki/Stable_release" class="external-link" rel="nofollow" style="text-decoration: none;" title="Stable release">stable release</a> <span style="color: rgb(32,33,34);"> <span>  </span>of <span>  </span> </span>
<a href="https://en.wikipedia.org/wiki/Computer_software" class="external-link" rel="nofollow" style="text-decoration: none;" title="Computer software">computer software</a> <span style="color: rgb(32,33,34);"> <span>  </span>is <span>  </span> </span>
<a href="https://en.wikipedia.org/wiki/Software_maintenance" class="external-link" rel="nofollow" style="text-decoration: none;" title="Software maintenance">maintained</a> <span style="color: rgb(32,33,34);"> <span>  </span>for a longer period of
time than the standard edition. The term is typically reserved for
<span>  </span> </span> <a href="https://en.wikipedia.org/wiki/Open-source_software" class="external-link" rel="nofollow" style="text-decoration: none;" title="Open-source software">open-source software</a> <span style="color: rgb(32,33,34);">, where it describes a software edition
that is supported for months or years longer than the software's
standard edition. </span></p>
</blockquote>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Sep
01, 2022 15:27 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71700899"></span>
<p>The versions that were previously marked as release candidate and
currently marked as LTS will be supported for a longer period of time. I
am ready to discuss further versioning details and we can address
those thoroughly on a TSC meeting.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vgridnevsky
at Sep 06, 2022 11:03 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71700957"></span>
<p>For maintainer diversity the report is not asking about the
maintainer's skillsets, it is asking about their corporate
affiliations.  Can you add in some verbiage about the affiliations?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Sep 07, 2022 16:21 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71701002"></span>
<p>I will address this question soon.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vgridnevsky
at Sep 09, 2022 06:16 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71701428"></span>
<p>Rereading this report, it occurs to me that the " <span>Questions/Issues for the TSC" don't really seem to be questions.
Indeed every one of them appears to already include a solution or at least a direction to follow. Am I missing something here?<br /></span></p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Sep
22, 2022 12:25 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71702265"></span>
<p>Certainly, with Ursa we have a result we want in mind, but there are
open questions about the whole process. Ursa is a cryptographic library,
so it needs to be very reliable for the security reasons. Moreover,
Iroha relies on it heavily. Involving more people in Ursa development
would've helped then. With all the discussions we had, we understand the
answer to why Ursa is in its current state, but we are not sure on how
to effeciently improve both projects in parallel. Sadly, yesterday's
Ursa meeting only included me and Aleksandr. Involving more people with
cryptographic knowledge would've been great.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vgridnevsky
at Oct 13, 2022 09:34 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71702301"></span>
<p><a href="https://wiki.hyperledger.org/display/~vgridnevsky" class="confluence-userlink user-mention" data-username="vgridnevsky" data-linked-resource-id="71699145" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Victor Gridnevsky</a> – I'm
sorry to hear that yesterday's Ursa meeting only included you and
Aleksandr.  As we discussed on our call, I think we can do much more to
drive participation in Ursa's community calls and with Ursa in general
if we start talking more about the project to the community. </p>
<p>We have seen increases in meeting attendance and activity around
other projects and labs when those groups share what they're doing with
the community. Very little has been done in the past though to talk
about what Ursa is, why it is important and how people can get involved,
so people don't know much about the project. </p>
<p>There are a number of things we can do to help with this, including
working with you and others involved in the project on meetups,
workshops, blog posts and more.  This presentation has a range of
suggestions about how to raise your profile and invite more people to
get involved and we're happy to help with any of these ideas.</p>
<p><a href="https://docs.google.com/presentation/d/13nji_R-op77ERT-AV3-CbOOZwAOjtvq33RRGnjpL3Gc/edit?usp=sharing" class="external-link" rel="nofollow">https://docs.google.com/presentation/d/13nji_R-op77ERT-AV3-CbOOZwAOjtvq33RRGnjpL3Gc/edit?usp=sharing</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at Oct 13, 2022 15:36 </div ></td>
</tr>
</tbody>
</table>




