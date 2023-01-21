---
layout: default
title: 2019 Q4 Hyperledger Besu
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Besu

Created by Danno Ferrin, last modified by Swetha Repakula on Dec 12, 2019

# Project Health

Besu is strong and growing. This quarter Besu has prioritized switching
to the Hyperledger tools and growing its community. Besu has been
successful on both fronts while also delivering its 1.3 Release in
October 2019.

# Questions/Issues for the TSC

-   RocketChat presents an unneeded point of friction bring in members
from the larger Ethereum community.  With Gitter we could send a
link directly to our project room and anyone could read it without
logging in.  Similar links for rocket chat (example:
<a href="https://chat.hyperledger.org/channel/besu" class="external-link" rel="nofollow"><span>https://chat.hyperledger.org/channel/besu</span></a> ) present a never ending loading screen unless the user
has already logged in.  

-   -   We ask the Hyperledger operations employees to enable a
configuration option that would permit read-only access to ch"at rooms without authentication (“ Allow Anonymous Read ”).

-   The Besu team is still looking for clear guidance on active status
from the TSC. Per the latest communication from the TSC, we believe
they want 3 maintainers from different organizations (Note that this
is on track to be achieved on 10 Dec). Can we gain confirmation th"at is the requirement that will enable the TSC to vote “yes” on active
status?

# Releases

Besu has released one minor version update (1.3, 3 Oct) and six
bi-weekly patch releases (1.2.4 on 23 Sep and 1.3.1 through 1.3.5 on 15
Oct, 22 Oct, 5 Nov, 5 Nov, and 20 Nov respectively).

Major functional improvements include

-   Support for Ethereum Classic and Classic testnets (from Edward Mack
and Greg Markou of Chainsafe Labs)
-   Support external mining for PoW networks (from Antoine Toulme of
<a href="http://Whiteblock.io" class="external-link" rel="nofollow">Whiteblock.io</a> )
-   Ethereum Mainnet Istanbul support
-   Added state pruning of blockchain data

# Overall Activity in the Past Quarter

Hyperledger Besu was fully transitioned from a PegaSys project to a
Hyperledger project this quarter.

-   Github repos moved to Hyperledger org
-   Bug tracking moved to the Hyperledger JIRA
-   Chat support room moved from Gitter to Hyperledger’s Rocket Ch"at -   CI/CD build infrastructure moved from Jenkins to Hyperledger’s
CircleCI
-   Established a bi-weekly contributor call



As a part of joining the Hyperledger community, the Besu team has
participated in the community by:

-   Added support for Besu in Caliper (Oct. 20)
-   Participated in the CI/CD working group conversations and sharing
our project’s research and best practices (Sep.- Oct.)
-   Attended the Maintainer summit in Minneapolis (Oct. 8-9)
-   Presented a talk at the Hyperledger booth at Sibos (Sep. 23-25) 
-   Submitted several talks and were approved to present at the
Hyperledger Global Forum (Sep. - Nov.)
-   Attended the Hyperledger meet-up at Devcon in Japan (Oct. 9)
-   Presented privacy solution at Architecture WG - Privacy
Confidentiality track (Sep. 20)
-   Presented at Hyperledger meet-up in Japan (Dec. 3)

# Current Plans

The Besu project team has several upcoming priorities:

1.  The project team is currently working towards its 1.4 Release,
scheduled for February 2019. The 1.4 Release is expected to include
the following features:
1.  Multi-tenancy
2.  End to end TLS on network protocols
3.  Public network hard forks (Muir Glacier and Aztalan potentially)
2.  The Besu team is also focusing on finalizing and publishing
performance metrics with its work on Hyperledger Caliper. Besu was
successfully integrated with Caliper in Q4 and the team is now in
the process of testing various scenarios for Caliper. We think
publishing these performance metrics will help provide the community
additional context on the project’s useability for a variety of use
cases.
3.  Besu is also continuing to engage with its community and grow the
diversity of its maintainer and contributor base. The Besu team is
hoping to continue to grow attendance for its bi-weekly contributor
calls to grow engagement across contributors.

# Maintainer Diversity

Our maintainer diversity is growing.  Early next week we should have
maintainers representing three different organizations.

-   At the beginning of the quarter Besu was still a PegaSys project, so
all the maintainers at the beginning of the quarter are PegaSys
employees.
-   Ivaylo Kirilov of Web3 Labs was added because of strong
contributions in EEA Privacy
-   Edward Mack of Chainsafe labs is in the process of being added
because of strong contributions in Ethereum Classic support.

Our process for adding Maintainers was featured on the Hyperledger Blog
as a best practice for a maintainer governance process - <a href="https://www.hyperledger.org/blog/2019/11/07/best-practices-and-lessons-learned-from-hyperledger-besu-establishing-a-maintainer-process" class="external-link" rel="nofollow"><span>https://www.hyperledger.org/blog/2019/11/07/best-practices-and-lessons-learned-from-hyperledger-besu-establishing-a-maintainer-process</span></a>

100% of current maintainers made a contribution this quarter.

# Contributor Diversity

Since the Besu project was approved by the TSC into the Hyperledger
community at the end of August 2019, there have been a total of 39 code
contributors.

-   23 contributors from <span class="inline-comment-marker" ref="27b27ec8-6436-4472-a4ea-de4dbd5605ed">PegaSys </span> (58% of
contributors)
-   16 contributors from outside of PegaSys (42% of contributors)
-   7 different organizations that can be identified
-   7 contributors whose organization were not determined.

Additionally, there have been content contributions in the community,
including technical content enablement materials.

# Additional Information

None at this time.

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
<td><span id="comment-24777798"></span>
<blockquote>
<ul class="incremental">
<li><span>The Besu team is still looking for clear guidance on active
status from the TSC. Per the latest communication from the TSC, we
believe they want 3 maintainers from different organizations (Note th"at this is on track to be achieved on 10 Dec). Can we gain confirmation
that is the requirement that will enable the TSC to vote “yes” on active
status? </span></li>
</ul>
</blockquote>
<p><span>From <a href="https://wiki.hyperledger.org/display/HYP/Project+Incubation+Exit+Criteria" rel="nofollow">Project Incubation Exit Criteria</a> :<br />
<br /></span></p>
<blockquote>
<ul class="incremental">
<li><p>The project is not highly dependent on any single contributor
(there are at least 3 legally independent committers and there is no
single company or entity that is vital to the success of the
project)</p></li>
</ul>
</blockquote>
<p><br />
</p>
<p>The key criteria that most were commenting on was “there is no single
company or entity that is vital to the success of the project”. With 19
of 20 maintainers coming from one company, the concern is that if th"at one company pulls out their support then there is only 1 maintainer from
the project.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Dec
03, 2019 08:40 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24777883"></span>
<p>As noted in the maintainer diversity, we have a maintainer from
Chainsafe that is coming on board as a maintainer when the nomination
window closes next Tuesday.  That will then have maintainers from 3
companies, PegaSys, Web3 Labs, and Chainsafe, filling the 3 maintainers
criteria. </p>
<p>As far as sponsoring companies (those who pay people to work) ETC
Cooperative will be funding work, mostly through chainsafe.  So if
ConsenSys were to pull out (we won't) ETC Co-Operative would be able to
keep the project alive, like they already do for some of the other ETC
clients.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Dec 03, 2019 15:40 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24777897"></span>
<p>2/21 = 9.5% maintainers that are not part of PegaSys doesn’t meet the
“there is no single company or entity that is vital to the success of
the project” portion of the requirement though.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Dec
03, 2019 16:34 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24777904"></span>
<p>If there were less PegaSys maintainers would that satisfy your
concern?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Dec 03, 2019 17:08 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24778070"></span>
<p>This isn't a serious question, is it? Obviously, artificially
balancing the number of maintainers by removing PegaSys employees
wouldn't address the crux of the problem, would it?</p>
<p>If anything, the fact that this question was raised shows the
challenge of trying to define an objective measure in this case. Any
hard number will evidently lend itself to possible gaming. This is very
much the kind of manipulation <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a> has
been warning us about when discussing election eligibility.</p>
<p>I honestly don't know what to make of this. :-/</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Dec
04, 2019 13:03 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24778075"></span>
<p>When the objection is expressed in percentages this is the incentive
it brings.  But on the other hand we would like some guidance as to when
we should ask again, so we don't ask too early.  Without some measure it
boils down to "when the TSC feels like it" and it's hard to measure when
the proposal should be raised again with that form of a standard.  We
have had Bob Somerwille of ETC cooperative state he would finance besu
development if needed if ConsenSys were to pull out.  I have yet to hear
any TSC member address this and instead every time this is mentioned the
subject is changed to the number of maintainers.</p>
<p>There was also an objection expressed earlier in a different forum
that too many maintainers may present a security challenge in coding
reviews, so this isn't the first time we've heard the "Too many PegaSys
maintainers" concern, and we've heard it in more than just a diversity
context.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Dec 04, 2019 15:04 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24778895"></span>
<p>As clarification, do you mean that "too many PegaSys maintainers" will lead to a security challenge or in general too many maintainers
lead to that challenge? Specifically what is the security concern?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swetharepakula at Dec 12, 2019 00:14 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24779164"></span>
<p>I think the concern was too many maintainers in general.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Dec 15, 2019 05:21 </div ></td>
</tr>
</tbody>
</table>




