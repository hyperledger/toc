---
layout: default
title: 2021 Q1 Hyperledger Cactus
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Cactus

Created by Hart Montgomery, last modified by Gari Singh on Feb 05, 2021

<span style="letter-spacing: 0.0px;"> This is the 2021 Q1 Hyperledger
Cactus quarterly report.  We will cover more than a quarter's worth of
material, though, since Cactus was left off the 2020 Q4 calendar.</span>

# Project Health

Cactus continues to progress as a project.  While we have not added any
new major contributors or maintainers, Cactus continues to build
momentum and has maintained all of its core members.  We are also
particularly excited about an academic group of people led by Rafael
that are looking at Cactus from a theoretical as well as practical
perspective, and we think this academic effort has the potential to add
a lot to the project.  The Cactus maintainers (and even some
non-maintainer contributors) have given a number of talks and
presentations on Cactus to outside audiences, which has bolstered
interest. 

# Questions/Issues for the TSC

We don't have any issues or questions for the TSC at this time.  We've
said it before, but we'll say it again:  as we roll out interfaces for
different Hyperledger blockchains, though, we would appreciate reviews
and comments from people affiliated with said blockchains.  So please
expect contact from us in the future!  We are presenting at the TSC
meeting on the due date of this report, so we hope the TSC members will
have questions for us then!

# Releases

We've had two releases since our last report.  We released v0.2 as
promised in December, and very recently v0.3.  The changes in these
releases are best described as moving towards a modular, efficient
blockchain integration platform that can be used with both the Accenture
and Fujitsu applications (as well as others).  The precise changes in
each release are much too long for this report, but thankfully Peter has
done a wonderful job of documenting them here (
<a href="https://github.com/hyperledger/cactus/releases" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/releases</a> ). 
Please take a look if you'd like to see all of the release details.

# Overall Activity in the Past Quarter

We have made a concerted attempt to improve our response times and
responses on communication tools.  While some of our contributors have
always been excellent (e.g. Peter), as a project, we thought we could do
better, and have been making an effort which thus far seems to be
working. 

The number of technical changes that we've made and the improvements
we've completed are quite numerous and varied.  We've worked on the
testing infrastructure, validation, examples, and CII badging, just to
name a few things.

# Current Plans

Our goal is to move forward with incremental releases targeting more and
more features of our modular architecture.

Over the next quarter, one of our major foci will be the ledger plugin
module.  This is (in a nutshell) the part of Cactus responsible for
integration with each different ledger, and can be viewed as
a "connector"–it's not responsible for any business logic.  Our goal is
to complete modular, interoperable ledger plugins for a variety of
supported blockchains in a number of different languages, which would
allow us to start using Cactus in many different novel applications.  We
are also aiming to make Cactus more workable across platforms, including
offering Windows support.

If you'd like to see a detailed list of things we're working on, please
check out our github issues (
<a href="https://github.com/hyperledger/cactus/issues" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/issues</a> ).  We
have 100+ issues currently, so this is a very detailed list.  But if
you're curious (or want to add an issue of your own), please feel free
to check it out.

# Maintainer Diversity

We still have four maintainers.  They are:

Shingo Fujimoto – Fujitsu

Jonathan Hamilton – Accenture

Peter Somogyvari – Accenture

Takuma Takeuchi – Fujitsu

We are more than open to adding additional maintainers outside of the
core Accenture/Fujitsu group, and hopefully in the not too distant
future.

# Contributor Diversity

<span style="color: rgb(23,43,77);">We recommend the following for
detailed contributor information:   </span>
<a href="https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard" class="external-link" rel="nofollow" style="text-decoration: none;">https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard</a>
<span style="color: rgb(23,43,77);">.  Thanks Ry! </span>

<span style="color: rgb(23,43,77);">Our contributor list is starting to
get too long to efficiently list in this report.  We encourage you to
check out the above link if you'd like to see all of the information. 
However, the organizations that lead contributors are still Accenture
and Fujitsu, with other notable contributions coming from those at Red
Hat and the University of Lisbon.  We have also 5 contributors whose
affiliations are unknown to the initial author of this report.   We hope
that the academic interest in Cactus will drive more contributors.  </span>

# Additional Information

We are looking forward to our presentation to the TSC!  Thanks for your
time.

We also note that there is an IBM interoperability project that is in
the process of being open-sourced as well.  We are working with the
developers of that project to look at common ground between Cactus and
their code/project philosophy. 

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41590325"></span>
<p>As an aside–we will have several maintainers of Cactus attending
tomorrow's TSC meeting for the presentation.  So we should be more than
able to answer any questions in the meeting.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Jan
14, 2021 00:42 </div ></td>
</tr>
</tbody>
</table>




