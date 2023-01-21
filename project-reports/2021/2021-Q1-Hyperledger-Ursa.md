---
layout: default
title: 2021 Q1 Hyperledger Ursa
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Ursa

Created by Hart Montgomery, last modified by Arun S M on Apr 29, 2021

# Project

This report covers the Hyperledger Ursa project.

# Project Health

The health of Ursa has been mixed recently.  Contributions have slowed
down.  There are two core reasons for this.  First, our most prolific
contributor, Mike Lodder, has spent less time on Ursa recently.  This
has had an outsized effect on our project since Mike has done so much
for us (thanks Mike!).  Second, a lot of our core contributors came from
the Indy/Aries groups.  It seems like that these projects are happy with
the cryptography tools currently in Ursa and thus are not spending time
working on Ursa.

However, despite contributions being down, Ursa meetings are still
well-attended and communication channels are still active.  It seems
like many people in Hyperledger (and outside communities) are still
interested in using and learning about cryptography, but just not
interested in building novel cryptosystems.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes!  </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? No.   </span>

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

We haven't had any releases since our last quarterly report.  Our last
release was Dec. 20th.

We anticipate another release once we finish our refactoring.

# Overall Activity in the Past Quarter

Our communication channels continue to be relatively active (they're
obviously not Fabric-levels of active, but for us, things move).  The
email list doesn't see a lot of traffic but we get a number of questions
on rocketchat that are usually answered quickly.

Some accomplishments (code-wise) for the past quarter:

1.  Implementation of a go interface for BBS+ signatures.  This will
allow arguably our most popular primitive to be used in go
projects.  Thanks to Mikaela for leading this!
2.  Replacing some older rust base-crypto dependencies with the new k256
crate.  This substantially increased the efficiency of a number of
our primitives.  Thanks to a face familiar to
the TSC–Dan Middleton–for handling this!

# Current Plans

We have a lot of stuff in the pipeline.  We'll list some things here:

1.  Perhaps most notably, we are doing a large reorganization.  All of
our "fancy" crypto was structured in the form of a library we called
zmix, which was originally designed to be an extensible zero
knowledge proof system.  However, the people that designed that,
while excellent, moved on from Ursa a while ago.  In the meantime,
people have used Ursa in different ways than the zmix design
originally anticipated.  As such, we are rearchitecting Ursa to
better reflect how people are actually using Ursa today.  Mike and
Brent, in particular, have done a great job getting this going. 
Mikaela is planning on working on this some as well.
2.  At some point, we should have a zero knowledge library
contribution.  The goal would be to enable flexible use of ZK proofs
in a way that the underlying proof cryptography can be switched out
in a modular manner.

At some point this year, we'll work on adding post-quantum
implementations.  The timeline for this depends a bit on NIST though.

# Maintainer Diversity

<u>Active Maintainers:</u>

Mikaela Tarkocheva (Scoir)
Philip Feairheller (Scoir)
Mike Lodder (Independent)
Brent Zundel (Evernym Inc.)
Dave Huseby (Independent)
Hart Montgomery (Fujitsu)
Dan Middleton (Intel)


We have more maintainers, but this is the group that generally
participates actively.  We note that we are super excited to have Dave
Huseby in a non-LF capacity.

# Contributor Diversity

Here is the link from LF analytics:   <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D</a>
.

As we discussed before, contributions are down, which the link shows. 
Use of Ursa has probably gone up, but we don't have effective ways of
tracking or verifying this.

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>






