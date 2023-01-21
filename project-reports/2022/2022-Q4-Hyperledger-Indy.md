---
layout: default
title: 2022 Q4 Hyperledger Indy
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q4 Hyperledger Indy

Created by Stephen Curran, last modified by Jim Zhang on Dec 01, 2022

# <span style="letter-spacing: 0.0px;">Projects </span>

##### **Distributed Ledger**

-   <a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>indy-node </span></a>
-   <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>indy-plenum </span></a>

##### **Client Tool**

-   <a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>indy-sdk </span></a>
-
<a href="https://github.com/hyperledger/indy-vdr" class="external-link" rel="nofollow">indy-vdr</a>
-    <a href="https://github.com/hyperledger/indy-shared-rs" class="external-link" rel="nofollow">indy-shared-rs</a>

##### **Shared Components**

-   <a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>indy-hipe </span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>indy-test-automation</span></a>
-    <a href="https://github.com/hyperledger/indy-node-monitor" class="external-link" rel="nofollow">indy-node-monitor</a>
-    <a href="https://github.com/hyperledger/indy-did-method" class="external-link" rel="nofollow">indy-did-method</a> -
"did:indy" <a href="https://hyperledger.github.io/indy-did-method/" class="external-link" rel="nofollow">DID Method specification</a>
-    <a href="https://github.com/hyperledger/indy-node-container" class="external-link" rel="nofollow">indy-node-container</a>

# Project Health

The road to a new pipeline and OS platform for Indy showed its promise
while overcoming some dependency pain this quarter. In upgrading Indy to
run on Ubuntu 20.04, we found a key piece of code that caused a pretty
fundamental blockchain type issue was broken on the Ubuntu 20.04 Indy. A
cryptographic signature was created and verified on across what amounted
to an unordered array
<img src="emoticons/sad.svg" class="emoticon emoticon-sad" data-emoticon-name="sad" alt="(sad)" />. When the code was changed to
newer versions of Python, the underlying array handling (C code)
produced a different ordering for the array, and hence a different
signature. Great work in the community by 
<a href="https://wiki.hyperledger.org/display/~cywolf" class="confluence-userlink user-mention" data-username="cywolf" data-linked-resource-id="16323400" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Andrew Whitehead</a> and 
<a href="https://wiki.hyperledger.org/display/~c2bo" class="confluence-userlink user-mention" data-username="c2bo" data-linked-resource-id="62236068" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christian Bormann</a>
resulted in a couple of iterations to a solution that all were happy
with (including the signatures). The effort showed the power of the new
CI/CD pipeline for indy-node, as where creating a new release artifact
previously took weeks of effort (don't ask!), it is now just a couple of
hours. This sped up the process and enabled substantially more testing
to occur. Note that although the move right now is to Ubuntu 20.04, the
pipeline makes all future updates to the OS platform and Indy itself
MUCH easier.

A deployment hold up for production Indy instances in the community is
because there are still CI/CD and Ubuntu upgrade work in the downstream
implementations of Indy. The CI/CD issues in Indy were also in the
Sovrin repos, and so the CI/CD work continues there.

The two vulnerabilities reported in the previous quarter where addressed
by the community in all of the (known) test and production instances of
Indy. An excellent concerted effort by the community in reporting,
understanding, implementing and deploying in a timely fashion the fixes.

The migration of AnonCreds out of Indy and into its own higher-profile
project will, we think, have a net positive impact on Indy. While a
portion of the code for AnonCreds leaves the project, the anticipated
expanded use of AnonCreds will result in a corresponding increase in the
use of Indy as a publishing platform for AnonCreds objects. Note that as
the migration of AnonCreds occurs, there is still the need for likely
two AnonCreds Methods code instances within Indy repos – one for the
legacy Indy identifiers, and another for did:indy identifiers. These are
important for two reasons – the smooth transition of the new library
structure for Aries Frameworks, and for the vast set of automated tests
involving AnonCreds based on Indy instances.

The production CANdy Network, an instance of Indy for governments and
broader public sector entities in Canada was launched this quarter.
Interest in deploying instances of Indy continues to be strong, with
lots of questions on Hyperledger Discord from people learning to run
their own instances. 

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222022-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-09-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2022-07 to
2022-09)</a> , there were 56 commits from 12 contributors. both of which
are down from last quarter. Knowing the importance of the work done this
quarter around the vulnerabilities and the correcting of the dependency
challenges in moving to Ubuntu 20.04 (described above), there is not a
reason to be concerned about that number. 
<img src="emoticons/warning.svg" class="emoticon emoticon-warning" data-emoticon-name="warning" alt="(warning)" />  *Checking to see if all Indy repos are accounted for
in the Dashboard.*

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : The Ubuntu upgrade is complete, producing releases and
compatibility with the Ubuntu 16.04 instance has been tested.

### **Diversity of Contributor Community**

**Update** : Little change this quarter in contributor community. Lots
of interest, but the core maintainers continue to do most of the work.

# Releases

-   indy-node (Ubuntu 16.04) – 1.12.5, 1.12.6
-   indy-node (Ubuntu 20.04) – v1.13.2-rc3

# Overall Activity in the Past Quarter

In the past quarter (as in the previous quarter), ledger code
development focused on code management – upgrading the Indy Node and
Plenum CI/CD pipeline and upgrading Indy Node to run on Ubuntu 20.04.
There was also much work done on testing of the new release, and
addressing the identified vulnerabilities that were published during the
quarter. Much was done on AnonCreds in Indy.

# Current Plans

With the new CI/CD Indy Node and Plenum pipelines complete, and the
Ubuntu 20.04 indy-node upgrade available, the core maintainers are
focused on their downstream releases.

The creation of the Hyperledger AnonCreds project means that the
indy-shared-rs has been duplicated (new instance called "anoncreds-rs"),
and the "cred-x" part of indy-shared-rs will be removed, while in the
other repo, all but "cred-x" will be removed. Work to make those two
repositories independent and aligned is a top priority in the
Indy/Aries/AnonCreds community.

The community is starting the move towards deprecating the indy-sdk by enabling the use of indy-vdr, indy-shared-rs and aries-askar across all
Aries Frameworks. There are a couple of tools still needed for that (a
migration tool from indy-wallet to Aries Askar, and an Aries Askar/Indy
VDR-based CLI for Indy) and it's overdue for that work to happen. Once
that is done, documentation and getting started material will need to be
updated.

# Maintainer Diversity

The bi-weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on larger changes. Topics and attendance has
increased recently, with more and more interested parties showing up,
and new contributors weighing in on the conversations.

# Contributor Diversity

From the last report: The "Indy Contributors" course was presented in
early 2022 and was extremely well received. The edX course about Indy,
Aries, AnonCreds and Ursa ( <a href="https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa" class="external-link" rel="nofollow">here</a> ) was updated recently
with a new version scheduled to be out in late 2022.

# Additional Information

-   Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   🔲 <span class="placeholder-inline-tasks"> <a href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7" class="confluence-userlink user-mention" data-username="8a9ebdad74c3ca030175df13fdb500d7" data-linked-resource-id="62239223" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">user-74455</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware" class="confluence-userlink user-mention" data-username="knagware" data-linked-resource-id="41590145" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-78021618"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> – If
there's interest, we'd be happy to help you reach out to more people
about how to get involved with Indy.  We did the Indy workshop in
February that drew a good crowd, but there hasn't been an Indy focused
meetup or community event since then.  Happy to help schedule and
promote more events if there's interest.  Perhaps we could do one more
technical meetup about how to use Indy as a publishing platform for
AnonCreds objects and another one looking at the CANdy Network?  And
note that if there are people in the Indy and AnonCreds communities th"at speak languages other than English we can run meetups in any
language.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Nov 03, 2022 19:25 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-78021695"></span>
<blockquote>
<p>The migration of AnonCreds out of Indy and into its own
higher-profile project will, we think, have a net positive impact on
Indy. [...] the anticipated expanded use of AnonCreds will result in a
corresponding increase in the use of Indy as a publishing platform for
AnonCreds objects. </p>
</blockquote>
<p>As support for AnonCreds on other ledgers increases it is also
possible that the use of Indy decreases (which isn't necessarily a bad
thing). Time will tell.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Nov
07, 2022 09:23 </div ></td>
</tr>
</tbody>
</table>




