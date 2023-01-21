---
layout: default
title: 2020 Q4 Hyperledger Sawtooth
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Sawtooth

Created by Andrea Gunderson, last modified by David Enyeart on Oct 22, 2020

# Project

Hyperledger Sawtooth
<a href="https://sawtooth.hyperledger.org/" class="external-link" rel="nofollow"><span>https://sawtooth.hyperledger.org/ </span></a>

# Project Health

The primary focus of the last quarter was integrating Hyperledger
Transact's transaction execution platform into the Sawtooth Validator.

The Sawtooth community is actively engaging in live, public working
sessions to decide Sawtooth's future. Some community members have
expressed interest in contributing to new Sawtooth features, and others
have promised to contribute enhancements and features already developed.

# Questions/Issues for the TSC

No new issues.

# Releases

-   Sawtooth Library v0.4.0 -  8/4/2020
-   Sawtooth Library v0.5.0 -  8/13/2020
-   Sawtooth Library v0.6.0 -  9/17/2020
-   Sawtooth Library v0.6.1 -  9/24/2020
-   Sawtooth Library v0.6.2 -  9/29/2020
-   Sawtooth Library v0.6.3 -  10/05/2020
-   Sawtooth Rust SDK v0.4.5 - 8/4/2020
-   Sawtooth Rust SDK v0.5.0 - 9/3/2020
-   Sawtooth Sabre v0.6.0 - 9/8/2020
-   Sawtooth PBFT v1.03 - 8/5/2020
-   Sawtooth Devmode v1.2.4 - 8/4/2020

# Overall Activity in the Past Quarter

The community continues to discuss Sawtooth-related issues on
Rocketchat. Live working sessions have also been used on a monthly basis
to discuss the future of Sawtooth, with strong participation from the
community.

The following key work has been completed in the Sawtooth codebase:

-   Sawtooth-core now uses Hyperledger Transact for transaction
execution. The Python transaction execution platform has been
removed from sawtooth-core. This replaces a large chuck of the
validator that was still written in Python and updates it to Rust.
Transact does not currently support external smart contract engines,
so the required smart contracts are now compiled in, including
Sawtooth Sabre to support uploading custom smart contracts.
-   The transact-compat feature was removed from the Rust SDK. This
feature provided a trait implementation for the Transact signer
trait for the sawtooth signer. The signer trait was removed in the
0.3 release of Transact.
-   More code has been re-written in Rust and moved to the Sawtooth
library from the Sawtooth validator. This is a continuation of the
efforts to rewrite the Sawtooth validator entirely in Rust and to
provide a library of Sawtooth components that can be used in a
variety of ledger implementations.
-   The infrastructure and theme for the Sawtooth website refresh have
been completed in a new branch.

# Current Plans

The following work is currently in progress:

-   Long running (LR) network testing of the Sawtooth validator with
Hyperledger Transact
-   Rewriting the Sawtooth CLI in Rust
-   Refreshing the Sawtooth website and documentation



The following work is currently planned:

-   Create a new consensus library that will be used by the Sawtooth
validator
-   Initialize a Sawtooth service for Splinter
-   Move portions of Sawtooth Sabre to Hyperledger Transact



Plans will continue to be developed as part of the working sessions.

# Maintainer Diversity

Maintainers are distributed across
<a href="http://bitwise.io/" class="external-link" rel="nofollow"><span>Bitwise </span></a> IO, Cargill, Intel, and Walmart
Labs.

# Contributor Diversity

Commits from 2020-07-01 to 2020-09-31 :  257

Committers from 2020-07-01 to 2020-09-31 :  8

Domains from 2020-07-01 to 2020-09-31 :  3

# Additional Information

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41583910"></span>
<p>This question is to help welcoming new contributions to the project.
The earlier TSC has decided that the sub-projects do not need formal
definition. But it will help to maintain project level document th"at mentions how these sub-projects are connected to each other and this
document shall be made public. For example, in the current report there
is mention of Hyperledger Sawtooth starting to use Hyperledger Transact
(which is categorized as library project), also there is mention of
Hyperledger Sawtooth Library releases. This could be an ambiguous
question for somebody not directly involved, unless they look into the
2.0 release planning document.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Oct 15, 2020 03:46 </div ></td>
</tr>
</tbody>
</table>




