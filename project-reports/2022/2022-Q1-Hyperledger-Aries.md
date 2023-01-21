---
layout: default
title: 2022 Q1 Hyperledger Aries
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q1 Hyperledger Aries

Created by Stephen Curran, last modified by Angelo De Caro on Mar 24, 2022

<span style="letter-spacing: 0.0px;"> </span> <span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Aries

# Project Health

Hyperledger Aries continues to grow stronger in terms of activity by contributors and in the interest from those using Aries in various use
cases. It has an extremely diverse and global community. In addition to
the steady progress made in most of the sub-projects, a number of
significant events occurred in the project including:

-   Progress on Aries Framework JavaScript in implementing Aries Interop
v2.0 (AIP 2.0), and its capability as the foundation of an Bifold,
an Aries React Native mobile wallet.
-   An "Aries Mobile Summit" was held and significant progress as been
made in open source mobile wallet delivery velocity. There are now
Aries React Native mobile wallets being deployed by various groups
into the App Stores.
-   A new repo "aries-mediator-service" has been created that can be
used by mobile Wallet providers as an Aries Mediator to enable
communication between the mobile wallet and all other Aries agent.
The repo is built on the latest ACA-Py release configured to act as
an Aries mediator.
-   Continued progress on the Aries VCX framework toward AIP 2.0, a
Rust-based framework suitable for use in a number of server-side and
mobile use cases.
-   Continued evolution of the open source implementation of the Aries
Interop Profile RFCs by the FIndy (Finland) project.
-   The <a href="https://aries-interop.info/" class="external-link" rel="nofollow">Aries Agent Test Harness</a> , continues to be a
focal point for the community in verifying interoperability, with
ongoing adjustments based on test results as the various frameworks
evolve.
-   A new
<a href="https://github.com/hyperledger/aries-mobile-test-harness" class="external-link" rel="nofollow">Aries Mobile Test Harness</a>
was added for automating the testing of Aries Mobile Wallets.

There continues to be lots of delivered, verified code, let alone the
increases in participation and use of Aries.

This quarter has also seen an increased focus on the use of the
verifiable credentials mechanism found in Hyperledger Indy–AnonCreds as
a "long term" approach versus the plan this time last year of moving to
the W3C VC 1.x data model. After a lot of effort in moving to the W3C VC
data model, practical limitations have meant that for those wanting to
deploy solutions today, AnonCreds has been found by many to be the
better approach. In response to that, a number in the Aries community
have started the process of making AnonCreds not just open source, but
also an open standard, and to remove a perception by some of it being
proprietary. We expect that a v1.0 specification will be produced fairly
quickly that (more or less) documents what we have today, and in
parallel or soon after, we'll work on an AnonCreds v2.0 that retains all
the capabilities of AnonCreds, but based on "newer" approaches, such as
replacing CL-Signatures with BBS+ Signatures.  Note that although
AnonCreds is currently a part of Hyperledger Indy, AnonCreds itself is
more relevant at the higher levels of the Trust over IP stack, and thus
is more of a concern of Aries contributors and those using the Aries in
building and deploying real world applications.

# Questions/Issues for the TSC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python Release 0.7.2, 0.7.3
-   Aries Framework JavaScript – a transition from "unstable" tags, to
"alpha" tags, and version 0.1.0
-   <a href="https://github.com/hyperledger/aries-framework-javascript-ext" class="external-link" rel="nofollow">Aries Framework JavaScript
Extensions</a> was tagged multiple times by feature
-   Aries Askar 0.2.3, 0.2.4
-   Aries VCX Releases 0.24.1 through 0.29.0

Interoperability status can be seen here: 
<a href="https://aries-interop.info" class="external-link" rel="nofollow">https://aries-interop.info</a> . 

# Overall Activity in the Past Quarter

Per the  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222021-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-12-31T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the fourth quarter of 2021 (Oct-Dec), Aries codebases had 900 commits
from 58 contributors. Both numbers are slightly down from last quarter,
about 10% each – most likely a reflection of the holiday season vs.
interest.

Community participation is extremely active in rocketchat channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

Coordination with the DIF DIDComm working group is healthy, with regular
reports being shared.

Project work in main repos is healthy and active. A potential concern is
the lack of activity in the Aries Framework .NET repository, which has
gone largely dormant. It was a popular Aries framework in the beginning,
and was the basis for the well known Aries Wallets in the market. This
is likely due to a combination of factors, including the focus on React
Native (and hence Aries Framework JavaScript) over Xamarin by mobile app
developers, the use of Aries Cloud Agent Python and Aries VCX on the
server side, and the focus of the main contributor to Aries Framework
.NET shifting to other products.

# Current Plans

-   There has been a significant growth in building common code for
mobile wallet apps using both Aries Framework JavaScript and Aries
VCX.
-   This is the same as in the last quarterly report – it was
correct this past quarter and will continue to be so as Aries
Framework JavaScript implements Aries Interop Profile 2.0 and
mobile wallets are released.
-   Most Aries teams are focused on adding the core capabilities of AIP
2.0 to their code bases. the work is nearing completion in Aries
VCX, Aries Framework JavaScript and Aries Cloud Agent Python.
-   A focus on standardizing AnonCreds to provide increased comfort of
the solid foundation in Aries and use beyond Aries.
-   The ACA-Py team is looking at what more needs to be done to jump to
an ACA-Py 1.0.0 release.

# Maintainer Diversity

Aries is a multi-codebase effort, and each codebase has its own set of
maintainers. The diversity of maintainers closely matches contributors,
with notes below.  Cross framework collaboration continues to increase
through the use of the Aries Agent Test Harness. For example, interop
tests are executed daily across the Python, Go, .NET, Rust (VCX) and
JavaScript frameworks, plus two non-Hyperledger implementations of
Aries.

# Contributor Diversity

In addition to the code contribution statistics (above), here are a few
indicators of our current diversity:

-   We hold community calls each Wednesday at 7am Pacific to cover (the
mostly) US and European contributors.
-   Call attendance for each is typically in the 10-12 range, down
somewhat lately. However, in the quarter there was the very
well-attended Aries Mobile Summit (5 weekly 2 hour sessions) and
other Aries framework specific calls.
-   Most organizations have only one attendee; it is rare for more than
three to attend from the same organization.
-   Cross codebase interoperability efforts indicate cross-organization
cooperation.

# Additional Information

Nothing

# Submission date

03-Feb-2022

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
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62243297"></span>
<p>Interesting development of  <span style="color: rgb(23,43,77);">AnonCreds vs. W3C VC spec, can I ask where
the standardizing work is being done? is that with a particular standard
organization (since Hyperledger doesn't do standard work)? Sorry I
couldn't find this information online. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by jimthematrix
at Mar 10, 2022 04:23 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62243386"></span>
<p>The work is happening just in the <a href="https://github.com/AnonCreds-WG/anoncreds-spec" class="external-link" rel="nofollow">AnonCreds Working Group</a> in
GitHub using the <a href="https://github.com/CommunitySpecification/1.0" class="external-link" rel="nofollow">Community Specification License
v1.0</a> .  The license is the specification equivalent to an Open
Source license for code. But contributing to the repo, participants are
agreeing to the license. The license comes from the Linux Foundation JDF
folks.<br />
<br />
We tried to use either DIF or ToIP (both JDF, so largely the same as CS
1.0) but reached a stalemate when some important contributors were not
able to collaborate within DIF and others couldn't do so within ToIP.
Rather than losing any collaborators, we started the work under the CS
1.0 license.  Current expectation is that we will go to IETF to create
an Internet Draft when ready, but we'll see.<br />
<br />
Meetings are open by invitation right now, with recordings being made
and available for those that know the link (unlisted on YouTube).  I
have on my to do list to use the repo Wiki to track the meetings –
meeting link, agenda, results and recordings.<br />
<br />
We are just now at the stage of documenting the "v0.1" spec. th"at matches the AnonCreds spec in Hyperledger Indy.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Mar 10, 2022 12:33 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62245872"></span>
<p><span style="color: rgb(23,43,77);">got it, thanks Stephen for the
background on that. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jimthematrix
at Mar 24, 2022 17:21 </div ></td>
</tr>
</tbody>
</table>




