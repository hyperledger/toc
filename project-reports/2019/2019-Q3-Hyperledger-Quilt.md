---
layout: default
title: 2019 Q3 Hyperledger Quilt
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Quilt

Created by David Fuelling, last modified by Mark Wagner on Sep 26, 2019

# Project Health

Project health over Q1/Q2 of 2019 has been poor, although I (David
Fuelling) would like this to improve in Q3 2019 and beyond. Some things
that have changed over the past month that are important to note:

1\) The TSC decided that the Quilt project should be limited to
Interledger (ILP) Java, which is its current charter (i.e., the "reboot" <a href="https://lists.hyperledger.org/g/quilt/topic/32846626" class="external-link" rel="nofollow">will not proceed</a> ). While I
supported the reboot and at the time was unable to assume leadership of
the Quilt project, I am now in a position to actively maintain the
project, especially since it will be limited to an Interledger Java
focus.

2.) There has been renewed interest in Interledger Java, even over the
past month. First, organizational support is expanding around ILP Java,
so I expect there to be at least 3 full-time engineers (myself included)
with bandwidth to focus on Quilt and Java software built around Quilt by the end of Q3 2019. Additionally, the project has recently had a new
unaffiliated contributor who has <a href="https://github.com/hyperledger/quilt/pulls?utf8=%E2%9C%93&amp;q=+is%3Apr+author%3Asudheesh001+" class="external-link" rel="nofollow">begun submitting PRs</a> , so by the end of Q3, I expect project health to be improved as compared to H1
2019.

# Issues

Given the various potential changes discussed in Q1/Q2 2019 in the Quilt
project, there is confusion around the focus of the project, who will
lead it and maintain it, and what its future will be. I am interested in
revitalizing the Quilt project and begin shipping ILP code around it.
However, if the TSC feels that this effort is too late, or the charter
of the project doesn't align with the broader focus of Hyperledger, then
this is potentially something to clarify.

To this end, I sometimes find it difficult to know what is expected by the TSC in terms of tasks or reports that project maintainers should be
delivering. This is likely just because I have never filled this role
before (prior to the reboot these tasks were performed by a maintainer
who is no longer able to contribute), but I was unaware of
<a href="https://wiki.hyperledger.org/display/HYP/TSC+Project+Updates" rel="nofollow">this page</a> , as an example. Are there other TSC
reporting requirements of the project lead other than these reports?

# Releases

Quilt has had only <a href="https://oss.sonatype.org/content/repositories/snapshots/org/interledger/" class="external-link" rel="nofollow">SNAPSHOT releases</a> thus far.
However, we are targeting a 1.0 release of Quilt Core (see <a href="https://github.com/hyperledger/quilt/issues?q=is%3Aopen+is%3Aissue+label%3Av1.0" class="external-link" rel="nofollow">remaining tasks here</a> ) by the
end of Q3. Follow-on deliverables will be identified after this
release. 

# Overall Activity in the Past Quarter

Activity over the past quarter started off light. However, in late
August/early-september, activity picked-up ( <a href="https://github.com/hyperledger/quilt/pulls?utf8=%E2%9C%93&amp;q=+is%3Apr+author%3Asudheesh001+" class="external-link" rel="nofollow">5 PRs</a>  were merged). From mid
Sept to the end of the month, participation and activity 
<a href="https://github.com/hyperledger/quilt/projects/2" class="external-link" rel="nofollow">has been very robust</a> , with
many tasks completed towards providing Interledger <a href="https://github.com/interledger/rfcs/blob/master/0029-stream/0029-stream.md" class="external-link" rel="nofollow">STREAM</a> support in the Quilt
library (this will allow Quilt clients to interact with Interledger
Connectors for the first time!).

# Current Plans

We are currently planning to release <a href="https://github.com/hyperledger/quilt/issues?q=is%3Aopen+is%3Aissue+label%3Av1.0" class="external-link" rel="nofollow">v1.0 of Quilt</a> by Sept 30th,
2019. This will include core libraries to support ILP sender & receiver
functionality, including support for the <a href="https://github.com/interledger/rfcs/blob/master/0029-stream/0029-stream.md" class="external-link" rel="nofollow">STREAM</a> protocol, which will be
a large enabler for applications built on top of Quilt libraries. Th"at said, today's Quilt is currently limited to core-libraries underpinning
ILP (IL-DCP, BTP, Core packets, OER serialization, etc). Over the coming
month we will be discussing potential additional contributions to the
project, including an ILP Sender, ILP Receiver, and possibly an ILP
Connector/Router as well.

# Maintainer Diversity

Two new maintainers have been added in Q3: (
<a href="https://github.com/nhartner" class="external-link" rel="nofollow">https://github.com/nhartner</a> ) and (
<a href="https://github.com/theotherian" class="external-link" rel="nofollow">https://github.com/theotherian</a> ). Including myself,
there are now three maintainers. While our technical diversity is
strong, we are all funded by the same company, so from this perspective
diversity is low.

# Contributor Diversity

Currently contributions are coming from developers at 
<a href="https://xpring.io/" class="external-link" rel="nofollow">Ripple/Xpring</a> and the University of Washington
(e.g.,  <a href="https://github.com/sudheesh001" class="external-link" rel="nofollow">https://github.com/sudheesh001</a> ), with some less
regular contributions coming from developers at 
<a href="https://coil.com/" class="external-link" rel="nofollow">Coil</a> .

# Additional Information

Not at this time.

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
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
<td><span id="comment-16324533"></span>
<p>Thanks for the update, David. Probably a good idea to subscribe to
the tsc and maintainers lists.</p>
<p><a href="https://lists.hyperledger.org/g/tsc/topics" class="external-link" rel="nofollow">https://lists.hyperledger.org/g/tsc</a><br />
<br />
<a href="https://lists.hyperledger.org/g/maintainers" class="external-link" rel="nofollow">https://lists.hyperledger.org/g/maintainers</a></p>
<p>If you aren't sure about a maintainer process you can ask on the
community architects channel on chat or email:</p>
<p><a href="https://chat.hyperledger.org/channel/community-architects" class="external-link" rel="nofollow">https://chat.hyperledger.org/channel/community-architects</a></p>
<p>community-architects@ <a href="http://hyperledger.org" class="external-link" rel="nofollow">hyperledger.org</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by dan.middleton@intel.com at Aug 13, 2019 11:41 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-20023371"></span>
<p>I don't think anybody has an interest in killing this project if it
can live. So, I encourage you to take the time to try and make progress
and see what comes out of it.</p>
<p>To answer your question about what is expected from the TSC I would
say that we primarily want to make sure the project still has a
heartbeat. <img src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<p>Thanks.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Sep
23, 2019 13:06 </div ></td>
</tr>
</tbody>
</table>




