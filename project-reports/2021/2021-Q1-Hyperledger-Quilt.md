---
layout: default
title: 2021 Q1 Hyperledger Quilt
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Quilt

Created by David Fuelling, last modified by Danno Ferrin on May 06, 2021

<span style="letter-spacing: 0.0px;"> </span>

# Project Health

Project health is unchanged from the previous quarter (I would mark it
as **neutral-to-unhealthy** ). Contributors have dropped to just one
(me, David Fuelling, the primary maintainer) due to changing priorities
at the companies that have historically funded development of
Interledger and Quilt. Contributions to the project over Q1 were also
*neutral* : there were only two commits to the project, although one
introduced substantial new functionality in the form of
<a href="https://github.com/hyperledger/quilt/pull/479" class="external-link" rel="nofollow">ILP-Pay</a> (a port of the <a href="https://github.com/interledgerjs/interledgerjs/tree/master/packages/pay" class="external-link" rel="nofollow">JS client application</a> of the
same name) allowing for more robust micro-payment sending using the <a href="https://github.com/interledger/rfcs/blob/master/0029-stream/0029-stream.md" class="external-link" rel="nofollow">STREAM</a> protocol.

That said, my own ability to contribute to Quilt will likely be reduced
during Q2 and Q3, so while no major bugs have been identified in Quilt,
adding new features is not currently a high priority because there are
no external customers or developers seeking to deploy Quilt or the Java
ILP Connector, at the moment. Until this changes, I will likely focus my
priorities elsewhere.

On the bright side, however, there are a number of developer-grant
programs spinning-up that will focus on Interledger (e.g.,
Coil/Mozilla's 
<a href="https://www.grantfortheweb.org/" class="external-link" rel="nofollow">Grant for the Web</a> ) and crypto in-general, so it will
be interesting to see how developer and/or corporate interest in
Interledger evolves over 2021. If this increases, it's likely that I
will have more cycles to contribute, and also likely others who have
historically contribute to the project would also have cycles to
contribute to Quilt.

That said, if project health continues in this direction, we should
consider moving Quilt into a dormant/maintenance state potentially, or
become more comfortable with few contributions (at least over the short
term 1 or 2 quarters)

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Not yet,
but there is an issue filed to perform this change (see
<a href="https://github.com/hyperledger/quilt/issues/481" class="external-link" rel="nofollow">here</a> ). </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Not fully, but
see this <a href="https://github.com/hyperledger/quilt/issues/435" class="external-link" rel="nofollow"> issue</a> that is
half-complete. </span>

# Questions/Issues for the TSC

What happens to a project when it goes through a "lull" in
contributions, such as what Quilt is experiencing now? There was some
discussion awhile back by the TSC around "project states", but I haven't
been tracking the TSC closely enough to know the current state of these
discussions, or current HL process. Any pointers would be helpful.

# Releases

No new releases.
<a href="https://github.com/hyperledger/quilt/releases/tag/v1.3.1" class="external-link" rel="nofollow">Most recent release was August,
2020</a> .

# Overall Activity in the Past Quarter

Outside of the primary contributor, there is no developer activity
(e.g., no new issues filed in Q1, no external participants via email or
community call).

# Current Plans

See the "Project Health" section above. Quilt development will likely be
paused for some months.

# Maintainer Diversity

No new maintainers. David Fuelling is the primary maintainer, though
technically
<a href="https://github.com/hyperledger/quilt/blob/master/pom.xml#L62" class="external-link" rel="nofollow">these people</a> are the core
maintainer group and can address bugs. However, nobody has new
functionality planned.

# Contributor Diversity

Contributor diversity is low, and unchanged.

# Additional Information

None at this time.

# Reviewed By

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
<td><span id="comment-51610297"></span>
<p>Any idea how many people are actually using Quilt?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mastersingh24
at Apr 29, 2021 07:59 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-51610302"></span>
<p>Don't know. Maybe maintainers/Hyperledger staff can get it. But we
could think of introducing a `dormant` state for project. I see a
request here not to go to end of life but rather stack the current
release for a while until an external force to do so is available.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Apr 29, 2021 08:05 </div ></td>
</tr>
</tbody>
</table>




