---
layout: default
title: 2021 Q4 Hyperledger Ursa
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Ursa

Created by Hart Montgomery, last modified
by Danno Ferrin on Jan 20, 2022

# Project Health

This was a difficult quarter for Ursa–probably the worst quarter for it
ever.  Not a lot got done due to a combination of factors, which
included core contributors being too busy to contribute (or, in some
cases, people leaving contributing organizations) and the holiday period
slowing everything to a crawl.

However, not all is gloom and doom:  there is renewed interest from end
users of Ursa (particularly through Aries) and we will do a security
audit soon.  As such, we are planning on soliciting contributions from
companies related to these end users (i.e. people using Aries) and some
of these folks have already agreed to help (thanks Cam and others!). 
This transition will not be immediate but hopefully Ursa will come out
of it stronger than ever.

We are also still planning on incorporating some rather large
contributions soon (hopefully by the time you will be reading this),
including a nice new zero knowledge framework.  These have just been
bogged down due to the holidays and lack of contributor availability.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">?  Yes.</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?  No, we are
undergoing a (very slow) migration to a different repo structure and
things aren't totally done yet, so we haven't modified the old repos
to support the CRS.  Sorry about this.  The new repo structure will
have the CRS implemented though. </span>

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

We were planning on releasing this quarter, but did not get around to it
due to the aforementioned issues.  We are planning on rectifying this in
the next quarter.

# Overall Activity in the Past Quarter

Our communication channels continue to be relatively active (they're
obviously not Fabric-levels of active, but for us, things move). The
email list doesn't see a lot of traffic but we get a number of questions
on rocketchat that are usually answered quickly.

Our big code contributions got stalled.  We plan on getting these in
soon.  In particular, we expect to add to Ursa some exciting new zero
knowledge proof functionality in the form of a "compiler" that takes
R1CS representations of statements and can "compile" them into ZK proofs
using a number of different backend systems.  This will enable us to
keep high-level, application layer crypto code the same while switching
ZK backends as the ZK proof systems themselves improve and change. 
Although this has not been contributed yet, we have talked extensively
about it, and certain members of the Ursa community (Avradip, and
especially Mike) have spent a lot of time on it.  

# Current Plans

Our immediate plans involve getting our new ZK code merged into Ursa. 
This should allow people to use ZK proofs more easily, and we know th"at some companies that use Hyperledger are planning on putting this library
to work in practice (Fujitsu, for one).   We also have a backlog of some
relatively routine maintenance work.  As we mentioned before, we also
are planning on working on a security audit soon.

Assuming we have bandwidth, at some point this year, we'll work on
adding post-quantum implementations. The timeline for this depends a bit
on NIST though.  We also need to see when people start demanding
post-quantum crypto, as this hasn't happened to a large degree in the
blockchain space yet (possibly because some post-quantum protocols, like
zero-knowledge proofs, are extremely expensive computationally).

In terms of community management, we our discussing with Ry and David B
about how to better do community outreach so that we can find more
contributors and users. We recognize that it is hard to find talented
cryptographers and cryptographic engineers with time to contribute, but
we need to expand our contributor base and so are going to make a
concerted effort to do so.

# Maintainer Diversity

Mike Lodder (Independent)

Brent Zundel (Evernym Inc.)

Dan Anderson (Intel)

Cam Parra (Kiva)

Hart Montgomery (Fujitsu)

Dan Middleton (Intel)



We have more maintainers, but this is the group that generally
participates actively.  

# Contributor Diversity

Here is the link from LF analytics:   <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D" class="external-link" rel="nofollow" style="text-decoration: none;">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D</a>
.  

It's not pretty, but hopefully will be better next quarter.

# Additional Information

We don't really have much to add.  This quarter has been a struggle but
we aim to turn things around soon.

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 04-Jan-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62233940"></span>
<p>Hi Ursa Team, </p>
<p>Ursa project is all about " <span style="color: rgb(23,43,77);">A
shared cryptographic library that enables people (and projects) to avoid
duplicating cryptographic work across projects, increasing security in
the process." and mainly to avoid duplicating efforts of cryptographic
work across projects, right?  URSA project at which stage now to use
with other hyperledger projects? I think URSA is great project when it
prvoides this feature to any blockchain project to use URSA library for
modular cryptography.  </span></p>
<p><span style="color: rgb(23,43,77);">I think this year 2022 URSA
project should be in state to use with other hyperledger projects who
are need in modular crypto service. </span></p>
<p><span style="color: rgb(23,43,77);">Just checking and going through
fabric RFC which is working on modular crypto-service in fabric.  </span></p>
<p><a href="https://github.com/hyperledger/fabric-rfcs/pull/34" class="external-link" rel="nofollow">https://github.com/hyperledger/fabric-rfcs/pull/34</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by knagware9 at Jan 04, 2022 09:34 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62233999"></span>
<p>Hi Kamlesh,</p>
<p>Yes, you are right.  The goal of Ursa is to serve as a modular crypto
service, and that is generally how it is used by projects and code th"at do currently use Ursa.</p>
<p>One of the biggest reasons that Fabric hasn't used Ursa at all is the
difficulty of calling Rust code from go code.  It's pretty common to
call Rust code from C code, but unfortunately all of the C to go
interfaces (at least the ones that I know, anyway) have a ton of
overhead and are not very practical to use.  There has been some work on
a go wrapper for Ursa, but the developers working on that have ceased
contributing.  More fundamentally, Fabric also doesn't use a lot of
"fancy" cryptography like threshold signatures or any kind of proofs,
which are the most commonly used features of Ursa.  Projects like Aries
or Indy that require these more complicated crypto primitives are
typically the kinds of projects that use Ursa.</p>
<p>You can also see my comments in that RFC you linked on the Fabric
modular crypto service.  I think they still stand, even though they are
quite old at this point.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jan
04, 2022 19:37 </div ></td>
</tr>
</tbody>
</table>




