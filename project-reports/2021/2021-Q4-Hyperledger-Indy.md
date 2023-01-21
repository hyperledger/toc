---
layout: default
title: 2021 Q4 Hyperledger Indy
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Indy

Created by Stephen Curran, last modified by Angelo De Caro on Dec 09, 2021

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

# Project Health

The work on the Indy DLT (indy-node and indy-plenum) continued slowly
this quarter with a focus only on the CI/CD capabilities and upgrading
to Ubuntu 20.04. A small team of 3 working on the project. Again this
quarter no new functionality was added to Indy. The transition of the
CI/CD from an older, undocumented Jenkins/manual process to a GHA-based
CI/CD pipeline has been slow but seems to have turned a corner. The work
on the CI/CD and OS Upgrade has prevented progress on new features –
blocking most notably the upgrade to the new "did:indy" DID Method.

The "did:indy" method has a new repo (
<a href="https://github.com/hyperledger/indy-did-method" class="external-link" rel="nofollow">https://github.com/hyperledger/indy-did-method</a> ) and
the spec has been moved from a HackMD document to.a published 
<a href="https://hyperledger.github.io/indy-did-method/" class="external-link" rel="nofollow">specification</a> . The task
backlog to implement the new DID Method is still to be created, and work
will start once the CI/CD and Ubuntu upgrades are sufficiently stable.

Work has accelerated this quarter on the new client-side Indy library
indy-vdr, with 3 tagged releases. More teams are deploying that code and
contributing to the code base. Non indy-sdk or indy-shared-rs tags were
created.

The interest in deploying instances of Indy continues to be strong, with
lots of questions on Hyperledger Chat from people learning to run their
own instances. There are no significant bugs that are pending action,
and little demand for new functionality (beyond the "did:indy" method)
from the user base. Indy "just works". 

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-09-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2021-07 to
2021-09)</a> , there were 72 commits from 14 contributors. which is up a
little from the last quarter.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : Steady progress, with GHAs implemented, the test automation
process updated and the Ubuntu upgrade nearing completion.

### **Diversity of Contributor Community**

**Update** : Contributor community diversity remains a top of mind issue
with the maintainers. The Hyperledger Staff (particularly 
<a href="https://wiki.hyperledger.org/display/~davidwboswell" class="confluence-userlink user-mention" data-username="davidwboswell" data-linked-resource-id="2392933" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Boswell</a> and
<a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> – thanks!)
working on getting an "Indy Contributors" course in place for early in
2022 in conjunction with the
<a href="https://trustoverip.org" class="external-link" rel="nofollow">ToIP Foundation</a> . We have also had a number of new
contributors joining Aries projects that have a reliance on Indy.  We
expect that to result in a focus on the "did:indy" work that is needed.
As noted, interest and contributions to indy-vdr have increased.

# Releases

-   indy-did-method (first draft)
-   indy-vdr 0.3.1, 0.3.2, 0.3.3

# Overall Activity in the Past Quarter

In the past quarter (as in the previous quarter), ledger code
development focused on code management – upgrading the Indy Node and
Plenum CI/CD pipeline and upgrading Indy Node to run on Ubuntu 20.04.  

There has been some progress on the new Indy DID Method, but not code.
The work left at the end of the last two quarters remains (albeit now as
a repo vs. HackMD doc): wrapping up the specification and defining the
backlog of work for indy-node, indy-sdk and indy-vdr. With the CI/CD
work blocking progress on indy-node, it's been difficult to convince
contributors in the community to work on the DID Method if it is so hard
to test and impossible to release.

# Current Plans

The push will be to complete the new CI/CD Indy Node and Plenum
pipelines, the Ubuntu 20.04 upgrade, and tools to make it easier to do
Indy Node development. In parallel, we expect coding to begin on the
"did:indy" method.

# Maintainer Diversity

The bi-weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. Topics and attendance has dropped
recently, mostly because of the lack of topics other than "how is the
CI/CD work coming along?"
# Contributor Diversity

Work has begun on putting together an "Indy Contributors" course for
presentation in early 2022. The edX course about Indy, Aries and Ursa (
<a href="https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa" class="external-link" rel="nofollow">here</a> ) was updated early in
2021 (this was missed in the last Quarterly report – even though the
author of the quarterly report was the course creator...).

# Additional Information

-   Key channels on Hyperledger Rocket Chat: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
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
-   ✅ <span class="placeholder-inline-tasks"> <a href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7" class="confluence-userlink user-mention" data-username="8a9ebdad74c3ca030175df13fdb500d7" data-linked-resource-id="62239223" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">user-74455</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
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
<td><span id="comment-62227781"></span>
<p>I realize this is probably not really the place to discuss the Indy
DID method but I have to ask:</p>
<p>While I understand the interest in having a dynamic resolution
mechanism isn't it counter productive to depend on a centralized service
like github given that the premise was that depending on a domain name
was considered unacceptable because users don't have full control over
it?</p>
<p>Isn't depending on a specific service under the control of a single
corporation even worse than depending on the DNS which is under the
control of ICANN?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Nov
11, 2021 07:43 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62228325"></span>
<p>Are there any plans to provide a JS native SDK implementation for
indy or is the long term plan to have the NodeJS SDK be a wrapper around
the bindings for other languages (it was either Python or C++ IIRC)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Peter Somogyvari at Nov 15, 2021 21:24 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62228359"></span>
<p>Hi  <a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></p>
<p><br />
</p>
<p>There is a nodejs wrapper for the Indy SDK, along with several others
(list <a href="https://github.com/hyperledger/indy-sdk/tree/master/wrappers" class="external-link" rel="nofollow">here</a> ).  All of the Indy
client-side apps (indy-sdk, indy-vdr and indy-shared-rs) are implemented
in Rust and thus have a C FFI that is possible and wrappers in various
languages.</p>
<p><br />
</p>
<p>The primary use of a JavaScript wrapper is to enable using the
indy-sdk in an Aries Framework – notably Aries Framework JavaScript,
which is under intense development right now to enable an open source
Aries wallet.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Nov 16, 2021 03:54 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62228360"></span>
<p>Yup...we understand the, shall we say, awkwardness of that approach. 
The goal will be to enable better approaches over time, particular the
idea of cross-registration of networks on the networks themselves.  We
did discuss that option, and we're open to other techniques for
DID-component-to-configuration-file mappings.</p>
<p>For now, the driver to punt on that issue is that we need the first
two features of the DID Method ASAP (multi-network identifiers and full
DIDDoc support) much sooner than a proper and robust discovery
mechanism, particularly while we expect discovery to be more "word of
mouth" driven in the initial implementations.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Nov 16, 2021 04:01 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62228467"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> Thank
you for the information! Are there any plans to add a wasm-pack build
target to the code that's implemented in Rust providing the C FFI?
(which would enable the code to be loaded without the NodeJS gyp
binding/linking/compilation/etc. steps)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Peter Somogyvari at Nov 17, 2021 01:04 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62228565"></span>
<p><a href="https://wiki.hyperledger.org/display/~Peter Somogyvari" class="confluence-userlink user-mention" data-username="Peter Somogyvari" data-linked-resource-id="31202399" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a>
interesting comment. I'm not a Rust person, but have talked to the folks
that built this and that option has not been raised.  From what I have
understood (until now), there was not a wasm option, and generally, not
a better way to use generally use the library other than via FFI. Th"at said, I do know about (but not the details) a way to use a Rust library
in Python that provides more of a "Python native" interface – allowing
things like shared access to data vs. the typical FFI "make a copy" approach.</p>
<p>I'll ask around if that is possible with this codebase.</p>
<p>Thanks!  </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Nov 18, 2021 00:05 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62228569"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> Thank
you for the detailed answers and the asking around, very much
appreciated! And please also note (just in case) that I'm merely asking
these questions for my own information.</p>
<p>My (entirely selfish) reason for advocating for wasm adoption is
because I happen to be a maintainer of a project that uses NodeJS so it
makes life simpler from that perspective.  <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by Peter Somogyvari at Nov 18, 2021 00:17 </div ></td>
</tr>
</tbody>
</table>




