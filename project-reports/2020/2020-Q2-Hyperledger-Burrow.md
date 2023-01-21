---
layout: default
title: 2020 Q2 Hyperledger Burrow
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Burrow

Created by Silas Davis, last modified by Gari Singh on Jun 25, 2020

# Project

Hyperledger Burrow

# Project Health

All maintainers and contributors have had less time to work on Burrow
but it continues to be used and work proceeds at a reasonable pace,
though slower in the last month or so. Given the world is on fire this
state of affairs does not seem particularly surprising. Most notable is
work on eWASM and Typescript client which is important foundation for
future development. 

# Questions/Issues for the TSC

We have issues reported with our documentation, some of which our minor,
but we have limited to fix right now. I remain willing to work with
anyone who is able to provide assistance here. To work through our
tutorials with an impartial eye, and fix wrong or confusing information
or flows. We put significant effort into raising the coverage of our
docs and tutorials but never had time to do any user testing

# Releases

-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.29.4" class="external-link" rel="nofollow">v0.29.4</a> - Upgrade to
Solidity 0.5.12
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.29.5" class="external-link" rel="nofollow">v0.29.5</a> - Improve Vent
synchronisation and improve GRPC status codes, Upgrade Tendermint to
0.32.8
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.29.8" class="external-link" rel="nofollow">v0.29.8</a> - 1,2, miss a few,
99, 100 (build issues)
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.30.0" class="external-link" rel="nofollow">v0.30.0</a> - Rewrite JS
library in Typescript, fix intial commit panic
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.30.1" class="external-link" rel="nofollow">v0.30.1</a> - Governance
primitive fixes
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.30.2" class="external-link" rel="nofollow">v0.30.2</a> - Patch upstream
issue with IAVL concurrency with mutex for concurrent reads on
simulated calls
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.30.3" class="external-link" rel="nofollow">v0.30.3</a> - Expose 'burrow
compile' test fixture functionality in binary
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.30.4" class="external-link" rel="nofollow">v0.30.4</a> - Groundwork for
EVM fixes coming up in next version (ensuring valid jumps)

# Overall Activity in the Past Quarter

Had a significant bug fix from developer at CertiK with possibility of
future collaboration. Quite a few important fixes and and continued
issues.

# Current Plans

eWASM support, IBC support

# Maintainer Diversity

See: <a href="https://github.com/hyperledger/burrow/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow">https://github.com/hyperledger/burrow/blob/master/MAINTAINERS.md</a>

# Contributor Diversity

Significant contribution from CertiK



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
<td><span id="comment-31203142"></span>
<p>Can you please list the actual maintainers and contributors (or
provide links)? As I think <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> would say:
we typically don't know what it was on the last report, and having every
TSC member search for the info isn't very efficient.</p>
<p>Regarding the activity, we have a new analytics tool: <a href="https://lfanalytics.io/projects/hyperledger%2Fburrow/dashboard" class="external-link" rel="nofollow">https://lfanalytics.io/projects/hyperledger%2Fburrow/dashboard</a>
which shows 2 commits over the last 2 months. I don't know that I would
call that "a reasonable pace" but I can understand that in those
troubled months we are currently living in one may not be the most
productive.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Jun
16, 2020 13:50 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31203149"></span>
<p>I did think about adding maintainer list, but the update template
says:</p>
<p>&gt; Required: Please include the maintainers that were added since
your last report</p>
<p>so I didn't, they are here: <a href="https://github.com/hyperledger/burrow/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow">https://github.com/hyperledger/burrow/blob/master/MAINTAINERS.md</a></p>
<p><br />
</p>
<p>The tool does not appear to accurately represent the number of
commits: <a href="https://github.com/hyperledger/burrow/commits/master" class="external-link" rel="nofollow">https://github.com/hyperledger/burrow/commits/master</a>
in a way that seems odd.</p>
<p><br />
</p>
<p>We've shipped more releases this quarter that in many others, but
like I said, not much happened in May.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by silasdavis at Jun 16, 2020 14:48 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-31203157"></span>
<p>It looks like anything with the green github "verified" tag is being
labeled a bot and an empty commit.  Take those two filters off (on a
drill down page, not the front dashboard which lacks the option) and a
different chart results.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Jun 16, 2020 15:57 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31203176"></span>
<p>Taking a quick look, it seems a lot of <a href="https://github.com/hyperledger/burrow/commits?author=kwv&amp;since=2019-08-01&amp;until=2019-09-01" class="external-link" rel="nofollow">commits are of this form</a> ,
which is not a valid DCO.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ryjones at Jun 16, 2020 19:24 </div ></td>
</tr>
</tbody>
</table>




