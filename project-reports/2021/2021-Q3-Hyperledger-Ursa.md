---
layout: default
title: 2021 Q3 Hyperledger Ursa
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Ursa

Created by Hart Montgomery, last modified by Gari Singh on Oct 16, 2021

# Project Health

The health of Ursa has stabilized, although it continues to be mixed. 
Our contributions were especially low this quarter:  pretty much only
some basic upkeep stuff was done.  However, some of this is due to the
fact that we have been working on some pretty huge feature improvements
coming soon, and these will be contributed in the near future.  We will
explain more on this later.

We have not done as much as we would have liked this quarter to better
optimize community outreach efforts.  Ry and David B have committed to
helping us, and we will work with them  this fall to get moving on
outreach.  Unfortunately, we are heavily dependent on a small handful of
core contributors, and if they get busy (which happened this summer),
then large-scale progress tends to slow down.

However, despite contributions being down, Ursa meetings are still
well-attended and communication channels are still active.  It seems
like many people in Hyperledger (and outside communities) are still
interested in using and learning about cryptography, but just not
interested in building novel cryptosystems.  We have also garnered more
interest from the Aries community, mostly through discussing a BBS+
LD-proof vulnerability (essentially, a proof construction leaks more
information than is desirable).  This is an interesting case where a
higher-layer use pattern causes undesirable security properties.  More
communication between the Aries and Ursa contributors is a step in the
right direction towards Ursa health, and, in our opinion, the health of
Hyperledger as a whole.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes.</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? No, sorry.</span>

# Questions/Issues for the TSC

We don't have any current issues or questions for the TSC.

We say something like this in pretty much every report, but we want to
reiterate that we are always interested in getting in touch with others
who want to use cryptography, and particularly so for people that want
to use non-standardized crypto like threshold signatures or zero
knowledge proofs. If this describes you, please feel free to get in
touch with us.

Yes, that was a cut and paste, and yes, we will continue to post it.
Please talk to us!

# Releases

We did not have a release since the last report (our last release was in
May).  However, we should have a new release very soon (perhaps by the
time you read this), so we will maintain at least a not unreasonable
release cadence.

# Overall Activity in the Past Quarter

Our communication channels continue to be relatively active (they're
obviously not Fabric-levels of active, but for us, things move). We have
noticed a recent uptick in traffic, which has been nice and maybe
correlated with the HGF. The email list doesn't see a lot of traffic but
we get a number of questions on rocketchat that are usually answered
quickly.

We didn't have a lot of big code contributions show up:  there was
basically just maintenance work.

On the other hand, there has been a lot of work done recently (with the
intention of contributing it to Ursa) that has not made it in to Ursa
yet.  In particular, we expect to add to Ursa some exciting new zero
knowledge proof functionality in the form of a "compiler" that takes
R1CS representations of statements and can "compile" them into ZK proofs
using a number of different backend systems.  This will enable us to
keep high-level, application layer crypto code the same while switching
ZK backends as the ZK proof systems themselves improve and change. 
Although this has not been contributed yet, we have talked extensively
about it, and certain members of the Ursa community (Avradip, and
especially Mike) have spent a lot of time on it.  So we think this
qualifies as overall activity even if it hasn't made its way to Ursa
yet.

# Current Plans

Our immediate plans involve getting our new ZK code merged into Ursa. 
This should allow people to use ZK proofs more easily, and we know th"at some companies that use Hyperledger are planning on putting this library
to work in practice (Fujitsu, for one).  

At some point this year, we'll work on adding post-quantum
implementations. The timeline for this depends a bit on NIST though.  We
also need to see when people start demanding post-quantum crypto, as
this hasn't happened to a large degree in the blockchain space yet
(possibly because some post-quantum protocols, like zero-knowledge
proofs, are extremely expensive computationally).

In terms of community management, we our discussing with Ry and David B
about how to better do community outreach so that we can find more
contributors and users. We recognize that it is hard to find talented
cryptographers and cryptographic engineers with time to contribute, but
we need to expand our contributor base and so are going to make a
concerted effort to do so.

# Maintainer Diversity

Mike Lodder (Independent)

Brent Zundel (Evernym Inc.)

Dave Huseby (Independent)

Hart Montgomery (Fujitsu)

Dan Middleton (Intel)



We have more maintainers, but this is the group that generally
participates actively.  

# Contributor Diversity

Here is the link from LF analytics:  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D</a>
.  

Our contribution levels are low this quarter, but we expect to see a
number of substantial contributions hit soon (e.g. the ZK proof
framework we have mentioned earlier).

# Additional Information

We don't have a whole lot else to say!  

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






