---
layout: default
title: 2019 Q4 Hyperledger Transact
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Transact

Created by Mark Ford, last modified by Nathan George on Mar 31, 2020

# Project Health

Health is good. A lot of continued interest in the project and
development continues on new features. New users of Transact include the
new libsawtooth library (in the sawtooth-core repo) and Splinter (
<a href="https://github.com/Cargill/splinter" class="external-link" rel="nofollow">https://github.com/Cargill/splinter</a> ).

## Issues

No issues currently.

## Releases

Since project creation, the project has had 6 releases. The current
release is 0.1.5. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> : 

<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow">https://crates.io/crates/transact/versions</a>

## Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion continues to be
held in RocketChat.

-   Added an Intro method to convert receipt::StateChange to a
state::StateChange. This was done to address the problem that a
transaction receipt state change enum cannot be used as is when
applying updates to state, a method was provided to convert between
the two.
-   Added a Redis-backed database implementation of Transact's Database
trait. It is available behind an experimental feature flag,
"redis-db".  This is part of an initiative to explore more
cloud-friendly storage formats.
-   Discussion topics and some cross-project commits, at the recent
Maintainer Summit (October 8-10th), evidenced that there was notably
broad interest in projects designed for cross-use like Transact.

## Current Plans

Next steps include:

-   Define and implement simplified smart contract SDK for Sabre
(cross-project w/Sawtooth, in-progress)
-   Add Redis database support (in-progress)
-   Add PostgreSQL database support
-   Add network transport support for smart contract engines (with
transaction processor compatibility)

## Maintainer Diversity

The maintainer diversity currently matches that of the initial project
sponsor companies.

## Contributor Diversity

Similar to maintainer diversity, since active contributors are likely to
become maintainers at this early stage.

## Additional Information

None.

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

##

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-24774914"></span>
<p>Is anyone tracking CVE issues ?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mwagner at Nov 14, 2019 13:24 </div ></td>
</tr>
</tbody>
</table>




