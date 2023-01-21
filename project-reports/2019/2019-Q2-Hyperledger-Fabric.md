---
layout: default
title: 2019 Q2 Hyperledger Fabric
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q2 Hyperledger Fabric

Created by Christopher Ferris, last modified by Kelly M Olson on Apr 11, 2019

# Project

Hyperledger Fabric

# Project Health

Fabric continues to grow and mature. Our 
<a href="https://github.com/hyperledger/fabric/releases/tag/v1.4.1-rc1" class="external-link" rel="nofollow">v1.4.1-rc1</a>  release candidate
was delivered on March 29th (announced 30th). We have experienced a
slight increase in the diversity of contributors with IBM comprising 43%
of the contributors over the past quarter (-2%).

There are a good mix of questions in chat, email and on 
<a href="https://stackoverflow.com/questions/tagged/hyperledger-fabric" class="external-link" rel="nofollow" title="https://stackoverflow.com/questions/tagged/hyperledger-fabric">Stackoverflow</a>
 – now  <span style="color: rgb(36,39,41);">3,678 </span> questions (an
increase of 228 since January) for the 'hyperledger-fabric' tag, with
the majority being answered. The questions themselves continue to be
increasingly sophisticated, which is also a good sign.

There has also been a good deal of new major contributions being
proposed and started. Fabric performance (which for a DLT is actually
pretty decent) is receiving lots of interest with various proposals for
optimizations that can yield significant performance improvements.
Additionally, there's ongoing work on a new command-line interface and
more.

# Issues

One issue that has been addressed recently is the aging of Gerrit CRs.
Often times, when someone submits a CR, there is no follow-up of review
comments, or someone submits a draft CR and lets it linger in the CR
backlog. We have addressed much of the older CRs from 2018 and into
January of 2019. Work continues to drive down the backlog so that we can
introduce the automation.

# Releases

As noted, Hyperledger Fabric 1.4.1-rc1 was released on March 29th. This
release adds support for a Raft consensus orderer and some additional
operational metrics and health monitoring capabilities. The Fabric
maintainers expect to publish the final v1.4.1 release next week.

Overall Activity in the Past Quarter

email traffic recovered to typical levels from the dip in the last month
of 4Q18, and remains strong. The RocketChat traffic seems to have
increased as well, but there are so many channels to track it is hard to
get a sense for how much of an increase there's been. 
<a href="https://stackoverflow.com/questions/tagged/hyperledger-fabric" class="external-link" rel="nofollow" title="https://stackoverflow.com/questions/tagged/hyperledger-fabric">Stackoverflow</a>
 traffic icontinues apace, reaching over  <span style="color: rgb(36,39,41);">3,678 </span> questions, an increase of
over 225 in the last quarter.

# Current Plans

With version 1.4 LTS just released, the project is working on 1.4.1 and
2.0.0 releases. The project maintains a 
<a href="https://wiki-archive.hyperledger.org/projects/fabric/roadmap" class="external-link" rel="nofollow" title="projects:fabric:roadmap">release roadmap</a> , and maintains a 
<a href="https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=10104" class="external-link" rel="nofollow">JIRA dashboard</a>  to track
specific items.

v2.0.0 is the 2019 target release for more substantial new features,
including an enhanced chaincode lifecycle, a raft consensus mechanism
(stepping stone to full BFT ordering service), and deeper token support.
We expect an alpha drop of v2.0 next week.

We hold playback meetings for design reviews and intend to continue
regular maintainer hangouts (see community calendar) every other week to
track the release plan's progress against objectives.

# Maintainer Diversity

Maintainer diversity increased because we retired 2 maintainers (IBM and
State Street) and one of the IBM maintainers left IBM for another
company. We remain confident that there is potential on the horizon.

# Contributor Diversity

As previously noted, contributor diversity grew in 1Q 2019. IBM now
represents 43% (-2%) of the contributors with some new more substantial
contributions being proposed.

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
<td><span id="comment-6429015"></span>
<p>Glad that the PSWG could review the FastFabric work. I am sure th"at the WG would like to help in some way in improving the performance and
scalability of Fabric and all HL projects.</p>
<p>I am also interested in helping with the perf and scale efforts on a
contributor level.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mwagner at Apr 04, 2019 13:58 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-6429017"></span>
<p>Will the v2.0 alpha include support for kubernetes out of the box
?</p>
<p>ie. no more docker in docker for chaincode.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by mwagner at Apr 04, 2019 13:59 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-6429423"></span>
<p>Any update on Ursa integration or Idemix support?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nage at Apr
11, 2019 12:06 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-6429449"></span>
<p>Mark, the chaincode 2.0 that I initiated to remove chaincode docker
dependency hasn't been merged for alpha, but the pull requests are out
there if you like to explore. We are hoping to get that in for
beta. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by binhn at Apr
11, 2019 13:45 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-6429461"></span>
<p>Idemix support has been in Fabric since 1.2, finshed in 1.3 and 1.4.
We have no immediate plans for Ursa.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ChristopherFerris at Apr 11, 2019 14:00 </div ></td>
</tr>
</tbody>
</table>




