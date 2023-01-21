---
layout: default
title: 2020 Q3 Hyperledger Besu
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Besu

Created by Grace Hartley, last modified by Gari Singh on Sep 17, 2020

# Project

Hyperledger Besu

# Project Health

Hyperledger Besu remains a strong project with a growing community
network of contributors. This quarter the team has focused on fostering
its community as well as many performance improvements, included in the
Hyperledger Besu 1.5 Release, which was launched on July 15th. The team
is currently building towards its 1.6 Release.

# Questions/Issues for the TSC

There are no issues at this point. The Hyperledger Besu team does have a
question for the TSC:

-   **Release Versioning:** Our Hyperledger Besu team is currently
proposing switching from Semantic Versioning for Releases to CalVer.
Instead of using  Major.Minor.Patch, Besu would use  <span style="color: rgb(29,28,29);">Year.Quarter.PatchNumber or
Year.Month.PatchNumber. For example, instead of 1.5.2 and 1.6.0 we
would have something like 20.3.2 and 20.4.0 or 20.8.2 and 20.10.0.
We would like to gain the TSC’s feedback on this change. </span>

# Releases

Hyperledger Besu has completed eight bi-weekly patch releases (1.4.6 on
10 Jun, 1.5RC1 on 17 Jun, 1.5-RC2 on 30 Jun, 1.5 on July 15, 1.5.1 RC on
22 Jul, 1.5.1 on 29 Jul, 1.5.2 on 13 Aug, and 1.5.3 on 27 Aug)

Some functional improvements include:

**Production-Ready Features:**

-   **Privacy: ** The most recent set of privacy enhancements include:

-   Ability to add and remove members from privacy groups.
-   Filters and subscriptions for private contracts.
-   Web3j and web3js support for private transactions and filters.

-   **Performance**

-   Added native encryption libraries to provide optimization
optionality
-   EVM execution improvements
-   Improved logs querying performance 
-   Improved transactions per second (TPS) performance by 33%

-   **Parity Tracing APIs** : Performed additional testing

**Early Access Features:**

-   **EIP-1559 Support: ** <span style="color: rgb(65,64,67);">Hyperledger Besu has been one of the
clients leading the implementation of EIP-1559, a major upgrade to
Ethereum’s transaction fee market.  </span>
-   **Ephemeral Testnet YOLO: ** <span style="color: rgb(65,64,67);">In
preparation for the next network upgrade, Berlin, an ephemeral
testnet called YOLO was launched with two new EIPs enabled:  </span>
<a href="https://eips.ethereum.org/EIPS/eip-2315" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-2315</a> <span style="color: rgb(65,64,67);">, which adds subroutines to the EVM,
and  </span>
<a href="https://eips.ethereum.org/EIPS/eip-2537" class="external-link" rel="nofollow" style="text-decoration: none;">EIP-2537</a> <span style="color: rgb(65,64,67);">, which introduces a new precompile
for the BLS12-381 curve. </span>
-   **<span style="color: rgb(65,64,67);">DNS Support </span>**
-   **<span style="color: rgb(65,64,67);">State back-up and restore
option </span>**

<span style="color: rgb(36,41,46);">Go to the 
<a href="https://github.com/hyperledger/besu/releases" class="external-link" rel="nofollow" style="text-decoration: none;">Changelog</a>  for more details. </span>

# Overall Activity in the Past Quarter

A few high-level activities include:

-   The Hyperledger Besu 1.5 Release Overview blog was published <a href="https://www.hyperledger.org/blog/2020/07/16/announcing-hyperledger-besu-1-5-available-now" class="external-link" rel="nofollow">here</a> .
-   Hyperledger Besu 1.5. Performance Blog was published <a href="https://www.hyperledger.org/blog/2020/08/06/hyperledger-besu-1-5-performance-enhancements" class="external-link" rel="nofollow">here</a> . This gives a
detailed look at the performance upgrades and metrics to Besu in the
past quarter.
-   Continue to run our bi-weekly contributor calls and grow the
attendance.
-   We have been using the Hyperledger tools consistently and with
continued success.

As a part of participating in the Hyperledger community, the Besu team
has participated in the community by:

-   Continuing to work on Besu’s support of Caliper.
-   Presented Hyperledger webinar on Hyperledger Besu on August 4th.
-   Mark Wagner led the Hyperledger mentorship project to have Besu run
on OpenShift with Josh Fernandes' help. The mentorship proejct was
completed last week with the work completed. 

# Current Plans

1.  The project team remains currently working towards its 1.6 Release,
scheduled for mid-October. The 1.6 Release is expected to include
the following features:

2.  1.  Berlin network upgrade preparation
2.  P2P improvements
3.  Performance improvements and testing for privacy groups
4.  Bonsai Tries

3.  Similar to last quarter, Besu is also continuing to engage with its
community and grow the diversity of its maintainer and contributor
base. The team is also looking forward to participating at the
Hyperledger Member Summit.

# Maintainer Diversity

Our maintainer diversity remained fairly consistent from the prior
quarter.  We continue to have maintainers from four different
organizations. 

The four organizations include:

-   ConsenSys (PegaSys)
-   Web3Labs
-   Chainsafe
-   Splunk (maintainer was formerly at Machine Consultancy)

The new maintainers this quarter include:

-   Stefan Pingel (ConsenSys)
-   David Mechler (ConsenSys)

We had a one maintainer transition to Emeritus in the last quarter.

The maintainers breakdown is currently:

-   16% non-ConsenSys - This is a slight decrase from 21% in the prior
quarter

# Contributor Diversity

<span style="color: rgb(29,28,29);">Commits from 2020-06-08 to
2020-08-28 : 216 </span>

<span style="color: rgb(29,28,29);">Committers from 2020-06-08 to
2020-08-28 : 26 (9 non-PegaSys) </span>

<span style="color: rgb(29,28,29);">Identified Orgs  2020-06-08 to
2020-08-28 : 5 + 4 independent </span>

# Additional Information

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   🔲
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-39617655"></span>
<p>Regarding the question, the <a href="https://wiki.hyperledger.org/display/TSC/Release+Taxonomy">Release
Taxonomy</a> specifies that releases within Hyperledger are done
according to semvar. I assume that in order to change this, we would
need to make this a formal decision. Can you provide information on the
benefits of moving away from semvar?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Aug
31, 2020 15:05 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-39617820"></span>
<p>Yes, we expect it would take TSC approval.  Would a stand alone pitch
be better?<br />
<br />
SemVer is great for libraries, especially where multiple release streams
are maintained for compatibility.  But because Besu is committed to
Ethereum Mainnet compatibility there is only one release stream th"at matters: does it sync to mainnet?  We think that a CalVer versioning for
the main DLT release itself would better signal how aligned we are to
the continually moving target of mainnet compatibility. We think it will
also more clearly communicate multiple release streams should not be
expected.</p>
<p>If Besu independently controlled what mainnet looked like we could
better align chain versions to SemVer, but while some Besu maintainers
participate in Ethereum mainnet co-ordination we don't control the
composition of the mainnet.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Sep 01, 2020 20:53 </div ></td>
</tr>
</tbody>
</table>




