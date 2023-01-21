---
layout: default
title: 2022 Q4 Hyperledger Iroha
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q4 Hyperledger Iroha

Created by Victor Gridnevsky, last modified by Jim Zhang on Dec 01, 2022

# Project Health

While the active maintainance of Iroha 1 stopped and no major releases
are planned at this time, it still receives regular contributions from
outside the core development team. 
<a href="https://github.com/baziorek" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Grzegorz Bazior</span></a>  is actively  contributing himself, both with code and
support, and organizing contributions from his students. The Iroha 2
team is doing bug triage for both projects and implements security fixes
for Iroha 1.

All Iroha 2 developers are now fully onboarded and at maximum
productivity. We have implemented a crude delineation of
responsibilities, and implemented all processes for long-term
development. We are following a timed release cadence, with  <span class="ui-comment-inline-span">a </span>  Long-term supported release
planned at critical stability milestones. Iroha 2 repository is well
organised, with branch protection rules enforced for all main branches (
**`iroha2-stable `** ,  **`iroha2-dev `** ,  **`iroha2-lts `** , 
**`iroha2-staging `** ) as well as a common 
<a href="https://en.wikipedia.org/wiki/CI/CD" class="external-link" rel="nofollow" style="text-decoration: none;">CI/CD</a>  pipeline with
thorough testing/linting and API verification systems. Iroha 1 and Iroha
2 branches may soon switch places due to the limited maintainance of
Iroha 1.

An interaction between Iroha and Ursa teams was established and updates
are being implemented.

## Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">None. </span>

## Releases

<span style="color: rgb(23,43,77);">Releases past quarter: </span>

-   `v2.0.0-pre-rc.4 `  (internal)
-   `v2.0.0-pre-rc.5 `  (internal)
-   <a href="https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre.rc.6" class="external-link" rel="nofollow" style="text-decoration: none;"><code>v2.0.0-pre-rc.6 (LTS) </code></a>
-   `v2.0.0-pre-rc.7 `  (internal)

Timed:

-   v2.0.0-pre-rc.9

## Overall Activity in the Past Quarter

### Iroha v1

-   Sample config update: max\_rounds\_delay was replaced with
proposal\_creation\_timeout in
<a href="https://github.com/hyperledger/iroha/pull/1662" class="external-link" rel="nofollow">#1662</a>
-   Compile errors with G++11 in Iroha 1 were fixed in
<a href="https://github.com/hyperledger/iroha/pull/1765" class="external-link" rel="nofollow">#1765</a>
-   Documentation was improved in
<a href="https://github.com/hyperledger/iroha/pull/2475" class="external-link" rel="nofollow">#2475</a> and 
<a href="https://github.com/hyperledger/iroha/pull/2494" class="external-link" rel="nofollow">#2494</a>
-   Building was fixed in
<a href="https://github.com/hyperledger/iroha/pull/2902" class="external-link" rel="nofollow">#2902</a> and 
<a href="https://github.com/hyperledger/iroha/pull/2906" class="external-link" rel="nofollow">#2906</a>

### Iroha v2

-   Outstanding PR count: 9, all of which are new.  PRs are
approximately closed in a week.
-   A new QA process is implemented. It focuses on the defect
reproduction and MWE generation. 100% of the tickets are filed as
bugs and are re-tested.
-   New Sumeragi consensus was implemented, tested and merged into the
lts branch; it focuses on ironing out the previous p2p actor problem
and it improves the performance.
-   P2P module restructuring leads to the stability improvements.
-   Ursa preliminary cleanup is in progress.
-   Kura inspector CLI is stable and working.
-   Docker and docker-compose configuration was improved
-   WASM: there’s an ongoing work regarding the compilation time, file
size, security, introspection and documentation.
-   Iroha configuration parser handles the default values better,
covering more edge-cases.
-   The documentation was updated to RC10
-   An initial implementation of  `iroha_swarm ` by our intern, Michael
-   A Blockchain explorer demo was implemented
-   A new JSON logging mode improves the diagnostic process.
-   A new feature for Kagami: synthetic genesis blocks
-   A syntax block generation tool was added
-   Load test generation tool was added (both statistic and
representative)
-   Kagami UX:
-   Better help messages,
-   More subcommands,
-   Easier generation of keys given passphrase
-   CVE in  `SignatureCheckCondition `  fixed
-   Permission validators can be registered at run-time and
user-generated with run-time upgradeability.
-   What changed regarding the Kagami UX?
-   Run-time permission validators implementation (?)
-   Sumeragi optimisation (what was changed?)
-   WASM dynamic linkage: FFI interface 95% finished.
-   Fully functional events:
-   Scoped
-   Global
-   Event-based
-   Time-based
-   By-call
-   With event processing
-   QA testing roadmap (De-containerised tests, CI Tests for SDK
compatibility)
-   The Websocket connections are closed cleanly
-   Error states are reported with more information and with better
feedback to the user

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

A practice of working with interns was established and will continue.

Since the last time, Jonathan Plasse contributed a fix (
<a href="https://github.com/hyperledger/iroha/pull/2670" class="external-link" rel="nofollow">#2670</a> ) for issue 
<a href="https://github.com/hyperledger/iroha/issues/2667" class="external-link" rel="nofollow">#2667</a> , "Refactor
&Option&lt;T&gt; to Option&lt;&T&gt;".

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
-   🔲 <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
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
-   🔲 <span class="placeholder-inline-tasks" style="color: rgb(94,108,132);">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks">11-Nov-2022 </span>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-78021927"></span>
<p><a href="https://wiki.hyperledger.org/display/~vgridnevsky" class="confluence-userlink user-mention" data-username="vgridnevsky" data-linked-resource-id="71699145" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Victor Gridnevsky</a> – If
we can do anything to help you share about the work you're doing with
Iroha and get people interested in contributing, we're happy to help.  I
think there's a lot we could do to get people interested.  For instance,
we've recently run workshops for other Hyperledger projects and those
have had a lot of interest – each of those have had over 400 people sign
up for them and many more are watching the recordings after the event
and people are learning how to use the projects and how to get
involved.  If you'd be interested, let me know and we can talk more.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Nov 11, 2022 16:52 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-78021929"></span>
<p>The Contributor Diversity section seems like a change to our project
reporting template. I believe this section is supposed to be maintainer
diversity. Could you comment on the organizational diversity of the
maintainers?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Nov
11, 2022 17:10 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-78021931"></span>
<p>Just checked template. Seems there is a contributor diversity section
too. Looks like the maintainer diversity section was dropped. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Nov
11, 2022 17:13 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-78022084"></span>
<p>Thanks, fixed!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by vgridnevsky
at Nov 17, 2022 08:31 </div ></td>
</tr>
</tbody>
</table>




