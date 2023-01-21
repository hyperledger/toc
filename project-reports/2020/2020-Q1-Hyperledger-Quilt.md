---
layout: default
title: 2020 Q1 Hyperledger Quilt
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Quilt

Created by David Fuelling, last modified by Gari Singh on Apr 27, 2020

# Project

<a href="https://github.com/hyperledger/quilt" class="external-link" rel="nofollow" style="text-decoration: none;">Hyperledger Quilt</a>

# Project Health

<span style="color: rgb(23,43,77);">Project health over Q1 has been
good. We had a new dot-release of version 1 of the library, and a few
patch releases. Additionally, we have engaged an independent third party
to perform a security audit of the library. No new contributors or
maintainers joined the project during this quarter. </span>

# Questions/Issues for the TSC

There are no issues at this time.

# Releases

Quilt had three releases in Q1:

-   Quilt  
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.1.0" class="external-link" rel="nofollow">v1.1.0</a> : Adjusted the API
for network communication settings; misc bug fixes.
-   Quilt  
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.1.0" class="external-link" rel="nofollow">v1.1.</a> 1: <span style="color: rgb(36,41,46);">Fix packet-expiry computation in
STREAM Sender (See   </span>
<a href="https://github.com/hyperledger/quilt/issues/432" class="external-link" rel="nofollow" style="text-decoration: none;text-align: left;">#432</a> <span style="color: rgb(36,41,46);">). </span>
-   Quilt  
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.0.3" class="external-link" rel="nofollow">v1.0.3</a> : A maintenance
release fixing a few outstanding bugs; deprecating unused features
and general library cleanup.

# Overall Activity in the Past Quarter

This past quarter was mainly focused on bug-fixes and API improvements
as we deploy the Quilt library into actual systems such as the
<a href="https://connector.interledger4j.dev/" class="external-link" rel="nofollow">Java Connector</a> . We had three releases to fix bugs
and make minor improvements in response to this feedback. In addition,
we are kicking off a third-party independent security review of Quilt
and hope to publish findings in Q2.

# Current Plans

The team is currently working to productionalize the
<a href="https://connector.interledger4j.dev/" class="external-link" rel="nofollow">Java Connector</a> and enhance it with Wallet
functionality to be able to store and track Interledger transactions. A
dev implementation can be found at 
<a href="https://wallet.ilpv4.dev" class="external-link" rel="nofollow">https://wallet.ilpv4.dev</a>  and a test/mainnet
implementation of this wallet will be hosted and supported at <a href="https://xpring.io" class="external-link" rel="nofollow">https://xpring.io</a> . Using feedback from this process,
we will potentially introduce new functionality into the Quilt library
as it makes sense. To this end, we plan on having a 1.2 release during
Q2, but no exact date has been determined.

One goal of the Xpring wallet is to demonstrate the cross-asset exchange
capabilities of Interledger. To this end we hope to setup and start
experimenting with a fabric testnet to demonstrate cross-chain fungible
asset transfers between two fabric networks. More details to come on
this POC.

Finally, a third-party independent security review of both the Quilt
libraries and Java Connector projects is underway. Results of these
audits will be published to the Quilt wiki once they the reports are
completed and any critical security vulnerabilities, if any, are
patched.

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
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
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
<td><span id="comment-31195421"></span>
<p>Is the security audit being performed through Hyperledger? cc: <a href="https://wiki.hyperledger.org/display/~dhuseby" class="confluence-userlink user-mention" data-username="dhuseby" data-linked-resource-id="2392216" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Huseby</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Mar
09, 2020 16:37 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31195525"></span>
<p>Glad to see the Fabric network comment. I think it's important th"at Quilt show good integration with Hyperledger projects.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Mar 10, 2020 15:26 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-31201488"></span>
<p><a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> not HL.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dhuseby at May 29, 2020 20:05 </div ></td>
</tr>
</tbody>
</table>




