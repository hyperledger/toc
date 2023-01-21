---
layout: default
title: 2021 Q2 Hyperledger Ursa
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Ursa

Created by Hart Montgomery, last modified by Gari Singh on Oct 16, 2021

# Project Health

The health of Ursa has continued to be mixed.  Contributions have not
picked up dramatically.  Our core maintainers and contributors have
continued to be quite busy, and a lot of progress on things we want to
accomplish has been slow.  To combat this, we are working with Ry and
David B to better optimize community outreach efforts (well, really put
them together in the first place).  We haven't done a good job on a lot
of things in this area, and think that we can improve with their help. 
We also saw a lot of interest in Ursa due to the global forum (no
contributions yet, but people joining our channels) so we hope that we
can build on this momentum. 

However, despite contributions being down, Ursa meetings are still
well-attended and communication channels are still active.  It seems
like many people in Hyperledger (and outside communities) are still
interested in using and learning about cryptography, but just not
interested in building novel cryptosystems.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow" style="text-decoration: none;">Have you switched from
master to main in all your repos</a> </span> ? Yes!  
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow" style="text-decoration: none;">Have you implemented
repolinter.json in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? No.   </span>

# Questions/Issues for the TSC

We don't have any current issues or questions for the TSC.

We say something like this in pretty much every report, but we want to
reiterate that w <span style="color: rgb(23,43,77);">e are always
interested in getting in touch with others who want to use cryptography,
and particularly so for people that want to use non-standardized crypto
like threshold signatures or zero knowledge proofs.  If this describes
you, please feel free to get in touch with us. </span>

Yes, that was a cut and paste, and yes, we will continue to post it. 
Please talk to us!

# Releases

We had a minor release (v0.3.6) in May.  We are still working towards
our refactoring, and will have a major release when that happens, but
have just been slow.  Our core contributors and code reviewers have been
very, very busy.

# Overall Activity in the Past Quarter

Our communication channels continue to be relatively active (they're
obviously not Fabric-levels of active, but for us, things move).  We
have noticed a recent uptick in traffic, which has been nice and maybe
correlated with the HGF.  The email list doesn't see a lot of traffic
but we get a number of questions on rocketchat that are usually answered
quickly.  

Some accomplishments (code-wise) for the past quarter:

1.  We released v0.3.6.  Thanks Mike!
2.  We added some optimizations to the BBS+ signature suite (these are
not cryptographic in nature).  Thanks to Andrew Whitehead for
handling this!
3.  We cleaned up some of our test cases.  Thanks Nathan!

# Current Plans

We have a lot of stuff in the pipeline.  We'll list some things here:

1.  Perhaps most notably, we are *still * doing a large reorganization. 
It's been slow.  All of our "fancy" crypto was structured in the
form of a library we called zmix, which was originally designed to
be an extensible zero knowledge proof system.  However, the people
that designed that, while excellent, moved on from Ursa a while
ago.  In the meantime, people have used Ursa in different ways than
the zmix design originally anticipated.  As such, we are
rearchitecting Ursa to better reflect how people are actually using
Ursa today.  Mike and Brent, in particular, have done a great job
getting this going.  
2.  At some point, we should have a zero knowledge library
contribution.  The goal would be to enable flexible use of ZK proofs
in a way that the underlying proof cryptography can be switched out
in a modular manner.

At some point this year, we'll work on adding post-quantum
implementations.  The timeline for this depends a bit on NIST though.

In terms of community management, we our discussing with Ry and David B
about how to better do community outreach so that we can find more
contributors and users.  We recognize that it is hard to find talented
cryptographers and cryptographic engineers with time to contribute, but
we need to expand our contributor base and so are going to make a
concerted effort to do so.

# Maintainer Diversity

<u>Active Maintainers:</u>

Mike Lodder (Independent)
Brent Zundel (Evernym Inc.)
Dave Huseby (Independent)
Hart Montgomery (Fujitsu)
Dan Middleton (Intel)


We have more maintainers, but this is the group that generally
participates actively.  

# Contributor Diversity

Here is the link from LF analytics:   <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D" class="external-link" rel="nofollow" style="text-decoration: none;">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D</a>
.

We are hoping to see a bump from the HGF and outreach efforts so that we
can increase this.

# Additional Information

Dan Middleton is back in the dunking booth!

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
-   ✅ <span class="placeholder-inline-tasks">
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
<td><span id="comment-54657065"></span>
<p>FYI, Mike Klein added Hyperledger Ursa to this list for projects in
the Zero Knowledge Space –  <a href="https://zk.contact/" class="external-link" rel="nofollow">ZK Contacts</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Jun
21, 2021 21:35 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-54657068"></span>
<p>Thanks for letting us know!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jun
21, 2021 22:11 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-54657242"></span>
<p>"We aren't sure why this is still required in the template."</p>
<p>Actually if you hadn't just copied over your previous report you
would have seen that it's not. <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Jun
23, 2021 06:59 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-54657247"></span>
<p>Got me!  </p>
<p>That's what I get for doing these late at night  <img
src="emoticons/wink.svg" class="emoticon emoticon-wink" data-emoticon-name="wink" alt="(wink)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jun
23, 2021 07:11 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-54657621"></span>
<p>Updated to delete it.  Although maybe that erased the review
marks?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jun
29, 2021 16:18 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-54657684"></span>
<p>What's the latest progress of supporting ZK based privacy protection
in Ursa?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at Jun
30, 2021 05:26 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-54657704"></span>
<p>I guess it depends on what you want to support.</p>
<p>Our most exciting feature is probably coming soon, though:  a more
general-purpose way to write ZK proofs in a (mostly) back-end agnostic
way.  It's a sort of compiler for ZK proofs.  Hopefully this will be
ready by the next quarter.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jun
30, 2021 13:52 </div ></td>
</tr>
</tbody>
</table>




