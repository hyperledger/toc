---
layout: default
title: 2020 Q2 Hyperledger Caliper
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Caliper

Created by Attila Klenik, last modified by Gari Singh on Sep 17, 2020

# Project

<a href="https://github.com/hyperledger/caliper" class="external-link" rel="nofollow" style="text-decoration: underline;">Hyperledger
Caliper</a>

# Project Health

-   The core code-base continues getting cleaner and more modular. The
goal is to make many of the internal features behave like plugins,
following a general schema. Based on this approach, contributors can
easily add new features in a well-defined, localized manner, without
being familiar with the entire code-base.
-   The documentation pages are also being improved to provide hands-on
tutorials about setting up Caliper with well-known examples of
different DLTs.
-   <span style="color: rgb(23,43,77);">Community relations mainly
happen on Rocket.Chat, and the questions are answered in detail, and
on time. Furthermore, there is an increasing contributor/user
interest related to the supported DLTs (Besu, Ethereum, Fabric v2).</span>

# Questions/Issues for the TSC

<span style="color: rgb(23,43,77);">There are no issues at this time.</span>

# Releases

-   v0.3.2 patch was
<a href="https://github.com/hyperledger/caliper/releases/tag/v0.3.2" class="external-link" rel="nofollow">released</a> addressing the
Fabric v2 support
-   v0.4.0 is coming soon

# Overall Activity in the Past Quarter

-   **Project stats (since the last report)**
-   Issues closed: 58
-   PRs merged: 79
-   **Development-related **
-   Keeping up with Fabric 2.x releases
-   User workload module improvements (OO approach), with further
incoming updates/smart features to help users write concise
benchmark logic
-   Terminology changes/consolidations (adapter→connector,
master→manager, callback→workload module, using "contract" everywhere)
-   Simplify the SUT connector API. Hopefully, this will make the
implementation of new connectors and maintenance of current
connectors easier.
-   Messaging between processes has been updated (messenger modules
are pluggable now, explicit message classes added for
transport-agnostic message handling).
-   Some modules have been made event-oriented, to loosen the
coupling with other modules. 

# Current Plans

v0.4.0 will contain a major code-base cleanup, address the followings:

-   Identify the parts of the code-base that fit the description of a
"plugin" (like performance and resource monitors in the manager
process, TX observers in the worker processes).
-   Make such plugins as object-oriented as possible, following strict
interfaces and life-cycle management.
-   Streamline data flow in/between the Caliper processes and modules,
thus simplifying the code-base and improving performance and
robustness. 

<span style="color: rgb(23,43,77);">Subsequent releases will target the
improvement of platform supports, starting with the existing adapters.</span>

# Maintainer Diversity

<span style="color: rgb(23,43,77);">The list of maintainers remained
unchanged since the last report. </span>

# Contributor Diversity

<span style="color: rgb(23,43,77);">There are currently 32 contributors
to the repository, 19 of them with more than one commit. To the best of
our knowledge, contributors are from various companies/organizations,
such as Huawei, IBM, Intel, Soramitsu, Budapest University of Technology
and Economics, Monax, and the University of Oregon. </span>

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



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-36734264"></span>
<p>It is nice to see the diversity of organizations in the contributor
list.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mwagner at Jul 29, 2020 20:13 </div ></td>
</tr>
</tbody>
</table>




