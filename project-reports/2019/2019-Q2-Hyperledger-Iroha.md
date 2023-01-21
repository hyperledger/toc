---
layout: default
title: 2019 Q2 Hyperledger Iroha
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q2 Hyperledger Iroha

Created by Sara Garifullina, last modified by Kelly M Olson on Apr 18, 2019

<span style="letter-spacing: 0.0px;"> </span>

# Project

Hyperledger Iroha

# Project Health

During the last several months we released several Release Candidates,
tested them and prepared Iroha's performance for the v1.0 release.

-   Significantly reduced memory consumption
-   Implemented load tests
-   Moved to native client libraries
-   Implemented peer interaction testing framework
-   Performance improvements

Regarding the load tests, we have been using machines generously
provided by CNCF <a href="https://github.com/cncf/cluster/issues/109" class="external-link" rel="nofollow">https://github.com/cncf/cluster/issues/109</a> .

We received approval from TSC to move to v1.0! Community is active,
questions are asked and answered. We've also got in contact with
different developers after HK Bootcamp and very excited for the future
contacts with them. 

We also have our own weekly call now! Join us every Wednesday at 10am
GMT. 

# Issues

Still have DCO issue that is blocking the release. Diversity is not
enough. 

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0_rc3" class="external-link" rel="nofollow" style="text-decoration: none;">Hyperledger Iroha v1.0 Release Candidate
3</a>  - on February, 11th

<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0_rc4" class="external-link" rel="nofollow" style="text-decoration: none;">Hyperledger Iroha v1.0 Release Candidate
4</a>  - on March, 1st

<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0_rc4_hf1" class="external-link" rel="nofollow">Hyperledger Iroha v1.0 Release
Candidate 4 Hotfix 1 version</a>  - on March, 5th

<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0_rc5" class="external-link" rel="nofollow">Hyperledger Iroha v1.0 Release
Candidate 5</a>  - on March, 21st

# Overall Activity in the Past Quarter

We had some active discussions regarding the release with active members
of the HL community. Our maintainer attended HK Bootcamp and through
that we've met HK HL Community and are having a remote meetup with them
in a week, on April 24. Questions are being replied to in chats so more
people could use Iroha in their work. We receive many questions about
SDKs nowadays. 

We also fixed DCO issue that was blocking the release of 1.0 and had a
HL Iroha meetup in Tokyo! 

# Current Plans

Release the production-ready version is a \#1 goal for the team at the
moment. We hope it will bring us new users and new contributors, make
our community stronger. Projects built on Iroha are also being released
into production. The plan for the nearest future is to make Iroha fully
BFT and then start working on custom commands. Moreover, the following
features are planned: include support for Ursa library, improve the
granularity of permission model, introduce TLS node-node and client-node
encryption, support for consistent network-wide configuration parameters
stored in the ledger, stateful validation of genesis block, statistics
API.

# Maintainer Diversity

No changes were made though we will be changing the maintainers list
after the release, clarifying some rules for becoming a maintainer,
which might help us diversify the community. 

# Contributor Diversity

Contributors are still mainly Soramitsu employees and some individual
contributors also help us (for example, with translations).

After 1.0 we hope to diversify the community of contributors as well. 



Updates since the last report:

**Documentation and translation**

New contributors

Ivan (
<a href="mailto:ivan.gutierrez@tecnalia.com" class="external-link" rel="nofollow">ivan.gutierrez@tecnalia.com</a> ) Spanish

Vadim ( <a href="mailto:reutskiy@soramitsu.co.jp" class="external-link" rel="nofollow">reutskiy@soramitsu.co.jp</a> ) Russian

Mercedes Regueiro (
<a href="mailto:mercedes.enllave@gmail.com" class="external-link" rel="nofollow">mercedes.enllave@gmail.com</a> ) Spanish

Zhenhua Zhao (
<a href="mailto:zhao.zhenhua@gmail.com" class="external-link" rel="nofollow">zhao.zhenhua@gmail.com</a> ) Chinese (simplified)

Yang Cheng ( <a href="mailto:cystone@aliyun.com" class="external-link" rel="nofollow">cystone@aliyun.com</a> ) Chinese (simplified)

Caozhao ( <a href="mailto:caozhao@gmail.com" class="external-link" rel="nofollow">caozhao@gmail.com</a> ) Chinese (simplified)

Resetarsi ( <a href="mailto:resetarsi@gmail.com" class="external-link" rel="nofollow">resetarsi@gmail.com</a> ) Korean

pikatos ( <a href="mailto:pikatos@gmail.com" class="external-link" rel="nofollow">pikatos@gmail.com</a> ) French

Lira.lemur ( <a href="mailto:lira.lemur@gmail.com" class="external-link" rel="nofollow">lira.lemur@gmail.com</a> ) Russian

**Code contributions**

Commits from 2019-01-23 to 2019-04-15: 139

Committers from 2019-01-23 to 2019-04-15: 19

Domains from 2019-01-23 to 2019-04-15: 8

# Additional Information

n/a

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span> </span></span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner </span> </span> </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span> </span></span> </span> </span> </span> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-9109998"></span>
<p>Do you feel you have an effective plan in place to resolve the DCO
issues? Who in Iroha is responsible for resolving and who is responsible
at HL for verifying? </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by dan.middleton@intel.com at Apr 18, 2019 12:56 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-9110003"></span>
<p>It was already resolved with the help of Ry and David from HL's
side.<br />
The commits were squashed:<br />
https://lists.hyperledger.org/g/iroha/message/104</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Apr
18, 2019 13:04 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-9110008"></span>
<p>I have helped to resolve it recently: <a href="https://github.com/hyperledger/iroha/commit/6c77597ab55163667931591e774f6a04d91b403b" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/commit/6c77597ab55163667931591e774f6a04d91b403b</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lebdron at Apr 18, 2019 13:18 </div ></td>
</tr>
</tbody>
</table>




