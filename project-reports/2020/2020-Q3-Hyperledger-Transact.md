---
layout: default
title: 2020 Q3 Hyperledger Transact
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Transact

Created by Andrea Gunderson, last modified by Dan Middleton on Aug 20, 2020

# Project

Hyperledger Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a>

# Project Health

Health is good. This quarter, the focus is on components that will use
Transact. Work is underway to have Hyperledger Sawtooth and libsawtooth
make use of Transact's transaction execution platform, which is a part
of the ongoing effort to replace the Python codebase with Rust.  This
integration effort will result in changes to Transact, by way of bug
fixes and minor API changes as needed.

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 12 releases. The current
release is 0.2.4. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> : 

<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow"><span>https://crates.io/crates/transact/versions</span></a>

Release 0.2.5 is planned for updating Sawtooth support to the newest
version of the Sawtooth Rust SDK.

# Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion continues to be
held in RocketChat.

-   Stabilized of the "contract-archive" feature for loading smart
contracts from smart contract archive (.scar) files.
-   Update Sawtooth compatibility to the newest version of the Sawtooth
Rust SDK

# Current Plans

Next steps include:

-   Replace the existing transaction execution platform in the Sawtooth
validator with Transact.
-   Stabilize SQLite database support
-   Add a next-generation smart contract API / simplified smart
contracts (cross-project with Sawtooth, in progress)
-   Add PostgreSQL database support
-   Further develop the Transact SDK for JavaScript

# Maintainer Diversity

The maintainer diversity currently matches that of the initial project
sponsor companies.

# Contributor Diversity

Due to efforts being geared towards Sawtooth's adoption of Transact,
contributors in the Transact repositories were low, with only 3
contributors.

# Additional Information



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
<td><span id="comment-38142850"></span>
<p>While I know the intent was for Transact to be used by multiple
consumers (and on the Fabric side it just did not work out), it seems
that most of the focus is really around Sawtooth.  At this point, does
it make sense for Transact to simply become part of the Sawtooth family?
 I'm not saying this because of lack of intent, but just because of the
reality of how things are playing out.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mastersingh24
at Aug 11, 2020 20:53 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-38142867"></span>
<p>I'de like this to be discussed in the general case before the TSC. 
This is one case of a project being folded in when it only applies to
one DLT. </p>
<p>But I am looking down the horizon and could conceivably see projects
that may be Ethereum focused that are not strictly speaking part of a
Besu node but would be a bad fit for the other DLTs.  EthCluster in
Hyperledger Labs is one example, one of the three private ethereum
transaction enclaves is another possibility.  If those were to come to
the main project area should they become top level projects or
sub-repositories as part of Besu?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Aug 12, 2020 03:40 </div ></td>
</tr>
</tbody>
</table>




