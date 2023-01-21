---
layout: default
title: 2019 Q4 Hyperledger Indy
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Indy

Created by Lynn Bendixsen, last modified by Angelo De Caro on Nov 13, 2019

# <span style="letter-spacing: 0.0px;">Projects </span>

##### **Distributed Ledger**

-   I
<a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>ndy-node </span></a>
-   I <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>ndy-plenum </span></a>

##### **Client Tool**

-   I
<a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>ndy-sdk </span></a>

##### **Shared Components**

-   I
<a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>ndy-hipe </span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>Indy-test-automation</span></a>

# Project Health

Indy is a healthy project. Indy’s codebase has 23962 commits from 177
unique contributors. This represents an increase of 7 contributors this
quarter and about 2,000 additional commits. We had commits from 41
different authors in the last three months. Forums and chat channels are
monitored and a variety of participants are contributing helpful
responses to questions.

# Questions/Issues for the TSC

We continue to track the same issues as in [previous
quarters](2019-Q3-Hyperledger-Indy_16323202.html) .

### Incompatible agent implementations

Update:

The launch of project Aries had the intended effect of focusing
attention on standards for agent implementations. We will continue to
support that effort as we migrate portions of Indy SDK into Aries core
libraries. We will not be tracking this as an issue in our future
quarterly reports.

### Measuring the size and make-up of our user community

Update:

We played a bit with tools for counting contributors, but no other
significant progress.

Future work planned:

-   We expect that the Indy contributor community will continue to
shrink as much of the attention shifts to Aries.
-   Work with Hyperledger to get analytics about web sites, and Rocket
Chat usage. 
-   Begin measuring usage of the Sovrin forums: new contributors,
questions asked, and questions answered
-   We will also explore the use of Github's contributor tool. 

### <span class="inline-comment-marker" ref="bd990036-02cb-4e9e-9a70-2e985685cfb1">Build Issues </span>

Update:

Our transition to the GitLab CI build pipeline managed by the Sovrin
Foundation is going slower than expected. The Indy SDK pipeline is
complex, and GitLab's integration with GitHub is not yet mature. We have
found credible solutions to the problems we have seen, but the project
has not had sufficient developer focus to come to completion. We are
still relying on the Jenkins instance managed by the Sovrin Foundation
for our production CI / CD pipeline.

Future work planned:

-   We need a new commitment from the various teams who have expressed
interest.

# Releases

**August 2019:**

##### **Indy SDK 1.11.0**

-   Enhancements and bugfixes added for TAA and Endorser txns
-   Updated Indy-SDK CI/CD pipelines to test, to build and to publish
Android artifacts for Libvcx.
-   Improved state proof verification to support pagination.
-   Bugfixes

##### **Indy SDK 1.11.1**

-   Supported endorsing of transactions in Indy-CLI and Libvcx.
-   Added new functions to Anoncreds API to rotate credential
definition.
-   Added sign/verify with payment address functions to Libvcx.
-   Supported state proof verification for GET\_TXN request.
-   Extended config parameter of indy\_open\_pool\_ledger function.
-   Extended Libvcx initialization config to accept pool configuration.
-   Supported new platforms Ubuntu 18.04 and Centos:
-   Bugfixes

##### **Indy Node 1.9.1**

-   New DIDs can be created without endorsers
-   Transaction authors don't need to be endorsers
-   TAA acceptance should use date, not time
-   Bug fixes

##### **Indy Node 1.9.2**

-   Stability fixes
-   Endorser support fixes and improvements
-   Improving GET\_TXN to be able to query just one node the same way as
for other GET requests

### **September 2019:**

-   No Releases

### **October 2019:   **

##### **Indy SDK 1.12.0**

-   Minimal *EXPERIMENTAL * support of Fully-Qualified identifiers:
-   omit or set "1.0" to use unqualified identifiers.
-   set "2.0" to use fully qualified identifiers.

<!-- -->

-   added correspondent did qualify command to Indy-CLI.

-   -   general format of fully-qualified identifier is
&lt;prefix&gt;:&lt;method&gt;:&lt;value&gt;.
-   extended did\_info parameter of
indy\_create\_and\_store\_my\_did function to accepts optional
method\_name filed. This field should be used to create fully
qualified DID.
-   all functions can work with fully-qualified identifiers (new
way) as well as with unqualified.
-   added a new function -- indy\_to\_unqualified -- that gets
unqualified form of a fully qualified identifier.
-   proof requests now support versioning (ver field) -- now it
specifies whether restrictions are full qualified or not.
-   The same format of identifiers will be used in generated proof
and must be used for proof verification.
-   added a new function -- indy\_qualify\_did -- that updates DID
stored in the wallet to make it fully qualified, or to do other
DID maintenance.
-   all functions in Ledger API can accept fully-qualified
identifiers but always return results in an unqualified form.
-   extended VCX provisioning config to accept optional did\_method
filed. This field should be used to create fully qualified DIDs.

-   Migrated Android onto the API v21 and NDK 20.

-   Supported MacOS builds for Indy CLI.

-   The default value of Protocol Version was changed on 2. Henceforth
indy\_set\_protocol\_version function should be called if you are
going to work with Indy-Node 1.3 and less.

-   Bugfixes

##### **Indy Node 1.10.0**

-   PBFT View Change implementation (not enabled yet) and corresponding
code improvements
-   BLS multi-signature fixes and improvements
-   The latest version of ZMQ library support
-   Stability fixes

# Overall Activity in the Past Quarter

Key activity over the past quarter:

-   Migrating large parts of indy-agent, indy-hipe and indy-sdk to
Aries, including infrastructure such as Jira issues.
-   Improving the ledger to make it more stable, performant, provably
correct, and easy to maintain. We made a lot of progress and are
really pleased with Plenum.

Our contributor community collaborates a lot on Jira issues, in pull
requests, using Rocket Chat, and in weekly meetings. But we don't use
the mailing list very much. We do not have clear analytics, but the
majority of questions appear to receive answers within a few days.

# Current Plans

-   We are increasingly pushing contributors who want to add new
features to the Indy SDK to focus instead on the Aries libraries.
This impacts the language wrappers the most.
-   However, we are continuing to maintain Indy SDK and wrappers for
existing users to allow them a smooth transition, including adding
compatibility for Aries protocols to LibVCX.
-   The next round of ledger work will remove the RBFT replicas, instead
implementing Aardvark BFT. This addresses a number of issues we see
with replicas, and should significant improve performance and
scalability giving us headroom in the adoption of production Indy
networks for some time to come.
-   Other initiatives include improving CI / CD (as described above),
adding support for W3C DID and Verifiable Credential primitives, and
adopting the new approach to revocation provided by Ursa's anoncreds
2.

# Maintainer Diversity

The weekly Indy Maintainers call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. In the past quarter, the teams at the
Sovrin Foundation and at Kiva have been much more involved in
maintaining Indy. There is a proposal to start cross-organizational
reviews of pull requests in order to increase knowledge sharing, but we
don't yet have commitments from sufficient organizations.

# Contributor Diversity

Fewer people work on Indy now that many contributors focus instead on
Ursa and Aries. Evernym still sponsors the majority of development, but
the developers at the Sovrin Foundation are confident in the code base.
Developers from the government of British Columbia, Deutsche Telekom,
and Kiva are increasingly familiar with the code base on a deep level.

**POCs, Pilots, Projects**

There are now too many Indy projects to list them all here. Recent
public disclosures include:

-    <a href="https://sovrin.org/use-case-spotlight-onfido-to-provide-self-sovereign-identity-verification-services/" class="external-link" rel="nofollow">Onfido</a> and <a href="https://www.evernym.com/blog/teaming-up-with-b-social-curve-monese-and-seedrs-to-test-decentralized-identity/" class="external-link" rel="nofollow">UK FinTech ecosystem</a>
-    <a href="https://sovrin.org/use-case-spotlight-enterprise-identity-access-with-esatus-self/" class="external-link" rel="nofollow">esatus</a>
-    <a href="https://www.cubroadcast.com/episodes/corelation-forum-interviews-desert-financials-amstutz-and-culedgers-ainsworth-leverage-blockchain-for-cus" class="external-link" rel="nofollow">CULedger and Desert Financial</a>
-   <a href="https://farmerconnect.com/2019/09/18/farmer-connect-sa-announces-blockchain-collaboration/" class="external-link" rel="nofollow">Farmer Connect</a>

# Additional Information

-   Key channels on Rocket Chat: \#indy, \#indy-sdk, \#indy-node,
\#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

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
<td><span id="comment-24773598"></span>
<p>A few people reviewed the document while we were still modifying it.
First error: we should have marked the title as DRAFT. Second error: I
got confused and cleared your checkbox. Sorry about that.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by esplinr at Oct 30, 2019 20:38 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24773642"></span>
<p>Are we good to review now <a href="https://wiki.hyperledger.org/display/~esplinr" class="confluence-userlink user-mention" data-username="esplinr" data-linked-resource-id="6423128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Richard Esplin</a> ?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Oct
30, 2019 21:25 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24773644"></span>
<p>Thanks for asking Tracy.  This document is now ready for review.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lbendixsen at Oct 30, 2019 21:37 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24773661"></span>
<p>I believe Indy has geographically diverse maintainers. How well does
the maintainer call work given disparate timezones and have you
experimented with mail list, chat, or Jira coordination rather than
voice calls?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Oct 31, 2019 09:18 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24773662"></span>
<p>Will your Aardvark implementation be from scratch or is it making use
of an existing library?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Oct 31, 2019 09:19 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24773668"></span>
<p>We rotate time slots for meetings, having one week in the morning US
and the next week late in the afternoon for the US.  We try to review
the last calls business each week to keep those only attending one “in
the know” along with posting recordings and keeping notes.  The email
list still isn’t very active compared to Rocket.Chat.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nage at Oct
31, 2019 13:15 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24773669"></span>
<p>It is essentially the existing RBFT implementation with redundant
replicas turned off.  There are still some maintainers holding out hope
for the RBFT implementation but the cost of the replicas with Pythons
GIL seems to be negating their benefit.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nage at Oct
31, 2019 13:17 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24773670"></span>
<p>We still have trouble getting new contributors into the core of the
ledger code and wonder if promoting Plenum as a stand-alone framework
would help but are unsure if this would be helpful or simply increase
project overhead.  (Previous drafts of this report contain more
information but it was removed to give us a chance to have a better
discussion amongst the current project maintainers.)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nage at Oct
31, 2019 13:20 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24773675"></span>
<p>An opportunity for consolidation, maybe?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ChristopherFerris at Oct 31, 2019 13:41 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24773692"></span>
<p>We are always open to consolidation discussions.  Interested parties
should introduce themselves in <a href="https://chat.hyperledger.org/channel/indy-ledger-next" class="external-link" rel="nofollow">https://chat.hyperledger.org/channel/indy-ledger-next</a>
.  The Sovrin Foundation is also putting together an  <a href="https://wiki.hyperledger.org/display/AriesConnect/Aries+Connect-a-thon">Aries
Connect-a-thon</a> in December where the main architects are present if
anyone wants to have an in-person conversation.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nage at Oct
31, 2019 14:22 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24773694"></span>
<p><span style="color: rgb(68,68,68);">Sawtooth could provide BFT &amp;
Finality but would need to add state proofs. <span>  </span></span><br />
<span style="color: rgb(68,68,68);">or likewise, Fabric could add BFT
and state proofs. </span></p>
<p><span style="color: rgb(68,68,68);">Just food for thought as
contributors could put work into those integrations vs. similar work in
Plenum </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Oct 31, 2019 14:29 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24773719"></span>
<p>Evaluating other Hyperledger ledgers is definitely on our list of
research tasks. We also hope that other teams evaluate the benefits of
Plenum, and consider adding the additional features they need for their
use cases.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by esplinr at Oct 31, 2019 15:33 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24773720"></span>
<p>I love the engagement from the TSC on this quarterly report. It
increases our motivation for preparing these regular reports. Thank
you!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by esplinr at Oct 31, 2019 15:34 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24774519"></span>
<p>Probably more overhead than you'll want unless you really want this
to be used by others outside of Indy</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by mastersingh24
at Nov 08, 2019 08:28 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24774738"></span>
<p>Plenum is a proven general purpose ledger, and we would love for it
to be used outside of Indy. Especially if those users become
contributors.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by esplinr at Nov 12, 2019 23:12 </div ></td>
</tr>
</tbody>
</table>




