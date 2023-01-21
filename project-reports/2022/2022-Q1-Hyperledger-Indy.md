---
layout: default
title: 2022 Q1 Hyperledger Indy
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Indy

Created by Stephen Curran, last modified by Angelo De Caro on Mar 24, 2022

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

As with the previous quarter, work on the Indy DLT (indy-node and
indy-plenum) continued slowly this quarter with a focus only on the
CI/CD capabilities and upgrading to Ubuntu 20.04. Good progress was made
and on the project and we (think we) can see the light at the end of the
tunnel.  Accomplishments:

-   All three of the relevant repos (indy-node, indy-plenum and
indy-test-automation) have been updated to support GitHub Actions
CI/CD and Jenkins. Jenkins will be dropped once we have a fully
tested artifacted generated.
-   A circular dependency in indy-test-automation with indy-node and
code in the Sovrin Foundation r epos has been broken.
-   A working Ubuntu 20.04 artifact has been produced and deployed as a
node on the IdUnion Indy network test instance.
-   Documentation has been updated for how to deploy a network and how
to deploy a new node on a running network.
-   Quick start Indy developer environments have been defined for Indy
using containers and on GitPod.

Left to do:

-   Investigation of a potential intermittent bug on a network with a
mix of Ubuntu 16.04 and 20.04 nodes (likely something in libsodium).
-   Automation of a tagged release to produce published artifacts.

As noted last report, work on the CI/CD and OS Upgrade has prevented
progress on new features – blocking most notably the upgrade to the new
"did:indy" DID Method. However, the new documentation and containerized
developer environments will be a huge help for developers.

A course put on by Hyperledger and Indicio aimed at getting new
developers started on Indy happened today (2022.02.03) and interest was
high – there was a waiting list to attend. We're hoping that translates
into developers working on the project.

BC Gov launched a "Code With Us" challenge for $CDN70k to get work on
the  "did:indy" method started. The challenge was won by two respondents
– Indicio for the Indy Node/Plenum work and
<a href="https://wiki.hyperledger.org/display/~domwoe" class="confluence-userlink user-mention" data-username="domwoe" data-linked-resource-id="36734205" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dominic Wörner</a>  for the
Indy VDR (Client) work. They have started their work by evaluating the
specification and the existing code base to see if there "code-friendly" adjustments needed to the spec (
<a href="https://github.com/hyperledger/indy-did-method" class="external-link" rel="nofollow">https://github.com/hyperledger/indy-did-method</a> ) to
map out the changes to be made to the code. From there, let the coding
begin! A team of interested parties are now meeting weekly to watch (and
hopefully) help with the progress and to discuss the specification.

<span style="color: rgb(23,43,77);">This quarter has also seen an
increased focus on the use of the verifiable credentials mechanism found
in Hyperledger Indy–AnonCreds as a "long term" approach versus the plan
this time last year of moving to the W3C VC 1.x data model. After a lot
of effort in moving to the W3C VC data model, practical limitations have
meant that for those wanting to deploy solutions today, AnonCreds has
been found by many to be the better approach. In response to that, a
number in the Indy/Aries community have started the process of making
AnonCreds not just open source, but also an open standard, and to remove
a perception by some of it being proprietary. We expect that a v1.0
specification will be produced fairly quickly that (more or less)
documents what we have today, and in parallel or soon after, we'll work
on an AnonCreds v2.0 that retains all the capabilities of AnonCreds, but
based on "newer" approaches, such as replacing CL-Signatures with BBS+
Signatures. Note that although AnonCreds is currently a part of
Hyperledger Indy, AnonCreds itself is more relevant at the higher levels
of the Trust over IP stack, and thus is more of a concern of Aries
contributors and those using the Aries in building and deploying real
world applications. </span>

Work continues this quarter on the new client-side Indy library
indy-vdr, with 1 tagged releases (0.3.4), and on indy-shared-rs (0.3.1).
More teams are deploying that code and contributing to the code base.
The indy-sdk CI/CD process was blocked for a period of time this
quarter, but that was recently fixed and PRs continue to trickle in, but
no release was completed.

The interest in deploying instances of Indy continues to be strong, with
lots of questions on Hyperledger Chat from people learning to run their
own instances. There are no significant bugs that are pending action,
and little demand for new functionality (beyond the "did:indy" method)
from the user base. Indy "just works". 

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222021-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-12-31T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2021-10 to
2021-12)</a> , there were 68 commits from 9 contributors. which is about
the same as last quarter.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : Steady progress, with GHAs implemented, the test automation
process updated and the Ubuntu upgrade nearing completion.

### **Diversity of Contributor Community**

**Update** : Contributor community diversity remains a top of mind issue
with the maintainers. The Hyperledger Staff (particularly 
<a href="https://wiki.hyperledger.org/display/~davidwboswell" class="confluence-userlink user-mention" data-username="davidwboswell" data-linked-resource-id="2392933" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Boswell</a> and
<a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> – thanks!) and
Indicio worked on getting an "Indy Contributors" course in place th"at was run today.. We have also had a number of new contributors joining
Aries projects that have a reliance on Indy.  As noted, interest and
contributions to indy-vdr continues to increase.

# Releases

-   indy-did-method (first draft)
-   indy-vdr 0.3.4
-   indy-shared-rs 0.3.1

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
<td><span id="comment-62238104"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> – I was
really happy to see that so many people signed up for the Aries and Indy
workshops.  I'll be really interested to hear from you and the other
project maintainers how those helped and if it brought more people into
the community.  Please feel free to share any thoughts or observations
about anything you see coming out of those workshops.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Feb 04, 2022 00:10 </div ></td>
</tr>
</tbody>
</table>




