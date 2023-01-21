---
layout: default
title: 2020 Q2 Hyperledger Quilt
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Quilt

Created by David Fuelling, last modified by Gari Singh on Jun 11, 2020

# Project

Hyperledger
<a href="https://wiki.hyperledger.org/display/quilt/Hyperledger+Quilt" rel="nofollow">Quilt</a>

# Project Health

<span style="color: rgb(23,43,77);">Project health over Q2 has been
good. We had two dot-releases of the library (
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.2.0" class="external-link" rel="nofollow">v1.2.0</a> in April and
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.3.0" class="external-link" rel="nofollow">v1.3.0</a> in May). Both versions
included <span style="color: rgb(29,28,29);">bug fixes, several security
enhancements, and quality improvements. Of note are enhancements to the
STREAM sender implementation to make STREAM payments more efficient. </span>No new contributors or maintainers joined the project during this
quarter but we maintained the same core group of contributors. </span>

# Questions/Issues for the TSC

There are no issues at this time.

# Releases

Quilt had two releases in Q2:

-   Quilt  
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.2.0" class="external-link" rel="nofollow">v1.2.0</a> : Bug fixes and
quality improvements.
-   Quilt  
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.3.0" class="external-link" rel="nofollow">v1.3.0</a> : Bug fixes,
security enhancements, improvements to STREAM payment sender.

# Overall Activity in the Past Quarter

<span style="color: rgb(23,43,77);">This past quarter was mainly focused
on bug-fixes, minor improvements, and minor security improvements.</span>

# Current Plans

The team is currently working to productionalize the  
<a href="https://connector.interledger4j.dev/" class="external-link" rel="nofollow" style="text-decoration: none;">Java Connector</a>   and
enhance it with Wallet functionality to be able to store and track
Interledger transactions. A dev implementation can experimented with at <a href="https://xpring.io" class="external-link" rel="nofollow">https://xpring.io</a> . Using feedback from this process,
we will potentially introduce new functionality into the Quilt library
as it makes sense – in particular, we are focusing on building an
implementation of
<a href="https://openpayments.dev/" class="external-link" rel="nofollow">Open Payments</a> specification, which enable eCommerce
and P2P payment flows over Interledger. It is possible that some of
these primitives will be ported into Quilt once we finish our POCs in
the Connector project.

Finally, a third-party independent security review of both the Quilt
libraries and Java Connector projects was completed. While I can't share
the actual audit results publicly, the audit found no major security
issues. The v1.3.0 release of Quilt rectifies any concerns that were
identified in that audit, although nothing in previous versions of Quilt
should be considered insecure or problematic. I plan to setup time with
David H. to go through the audit issues in more detail.

# Maintainer Diversity

<span style="color: rgb(23,43,77);">Maintainer diversity is unchanged
with four full-time people maintaining the project. While our technical
diversity is strong, we are all funded by the same company, so from this
perspective maintainer diversity is low. </span>

# Contributor Diversity

<span style="color: rgb(23,43,77);">Contributor diversity is unchanged.</span>

# Additional Information

<span style="color: rgb(23,43,77);">Not at this time. </span>

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






