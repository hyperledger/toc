---
layout: default
title: 2021 Q4 Hyperledger Aries
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Aries

Created by Stephen Curran, last modified by Angelo De Caro on Dec 09, 2021

<span style="letter-spacing: 0.0px;"> </span> <span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Aries

# Project Health

Hyperledger Aries continues increase quarter-on-quarter, in terms of
activity by contributors and in the interest from those wanting to use
Aries in various use cases. It has an extremely diverse and global
community. In addition to the steady progress made in all the
sub-projects, a number of significant events occurred in the project
including:

-   Substantial progress on Aries Framework JavaScript and its
capability as the foundation of an Bifold, and Aries React Native
mobile wallet.
-   An "Aries Mobile Summit" is planned this month (organized by the
Aries Working Group) to increase mobile and web wallet delivery
velocity.
-   Substantial progress on the Aries VCX framework, a Rust-based
framework suitable for use in a number of server-side and mobile use
cases.
-   The addition of a new non-Hyperledger, but still complete open
source implementation of the Aries Interop Profile RFCs by the FIndy
(Finland) project.
-   Three new frameworks (including Aries VCX and Findy) added to the
<a href="https://aries-interop.info/" class="external-link" rel="nofollow">Aries Agent Test Harness</a> , and a significant
increase in the number of passing tests across all frameworks. The
Test Harness has become the go to way to achieve and prove
interoperability.
-   Aries Interop v2.0 implementations in Aries Framework Go and Aries
Cloud Agent Python, including passing Aries Agent Test Harness test
cases using most AIP 2.0 protocols, including exchanging W3C
Standard Verifiable Credentials.

There is probably a more to talk about in terms of delivered, verified
code, let alone the increases in participation and use of Aries.

Another highlight in the community – Aries contributing to solutions for
Climate Change.  The Hyperledger Labs " <a href="https://github.com/hyperledger-labs/business-partner-agent" class="external-link" rel="nofollow">Business Partner Agent</a> " project continues to be an exemplar application built on Aries (ACA-Py).
As mentioned in the last quarterly report, BPA forsees a future where
organizations run Aries agents that allow for the secure interchange of
authentic data between business partners – supply chain participants,
customers, suppliers, etc. A collaboration based on BPA by BC Gov
(Mines), IBM, the Open Earth Foundation and others was highlighted at the ongoing COP26 Conference on Climate Change. The following videos
talk about what is possible using verifiable data to enable trust
amongst parties sharing crucial data about Climate Change.

-   BC’s Mines Digital Trust video presented at COP26 
<a href="https://www.youtube.com/watch?v=q0Jml3isSh8" class="external-link" rel="nofollow" style="text-decoration: none;">https://www.youtube.com/watch?v=q0Jml3isSh8</a>
-   Reactions at COP26:
-   “Such systems can be really effective if it is adopted world
wide, do you think the UNFCCC Global Innovation Hub can support
in that aspect by promoting such type of approach for carbon
footprint so that it can be used globally.”
-   Massamba Thioye, Project Executive, UNFCCC Global Innovation
Hub 
<a href="https://youtu.be/8Jo8PhhouGQ?t=27119" class="external-link" rel="nofollow" style="text-decoration: none;">https://youtu.be/8Jo8PhhouGQ?t=27119</a>
  -
-   “What we just showed is extremely relevant to what’s happening
across this conference… how do we have transparency alongside
data privacy… to have a subnational government not only very
excited to test it but also fully focused on open source and
open standards - which is also something I would like to see a
lot more jurisdictions focusing on.”
-   Martin Wainstein, Executive Director, Open Earth Foundation 
<a href="https://youtu.be/8Jo8PhhouGQ?t=27659" class="external-link" rel="nofollow" style="text-decoration: none;">https://youtu.be/8Jo8PhhouGQ?t=27659</a>
  –
-   “Thank you so much for blowing my mind… we aren’t just talking
about how to start, you are already hard at work.”
-   Catherine Atkin, Director, Stanford Centre for Legal
Informatics (CodeX) Climate Data Policy Initiative 
<a href="https://youtu.be/8Jo8PhhouGQ?t=29863" class="external-link" rel="nofollow" style="text-decoration: none;">https://youtu.be/8Jo8PhhouGQ?t=29863</a>
-   “Really impressed with the work you are doing and what is
happening in the public and private sector can come together.”
-   Anna Stanley, Manager, Climate Action, World Business
Council for Sustainable Development 
<a href="https://youtu.be/8Jo8PhhouGQ?t=30287" class="external-link" rel="nofollow" style="text-decoration: none;">https://youtu.be/8Jo8PhhouGQ?t=30287</a>
-   IBM Media Release: <a href="https://www.ibm.com/blogs/blockchain/2021/11/building-a-digital-trust-ecosystem-for-mining-in-british-columbia/" class="external-link" rel="nofollow">Building a digital trust ecosystem
for mining in British Columbia IBM Supply Chain and Blockchain Blog</a>

# Questions/Issues for the TSC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python Release 0.7.1, 0.7.2Rc0
-   Aries Framework JavaScript – many regular "unstable" releases th"at are leading up to the 0.1.0 release
-   New, related repo Aries Framework JavaScript Extensions th"at supports React Native components for use in Aries RN Mobile
Wallets.
-   Aries Askar 0.2.2
-   Aries VCX Releases 0.20.0, 0.21.0, 0.22.0, 0.23.0
-   Aries Framework Go Release 0.17.0

Interoperability status can be seen here: 
<a href="https://aries-interop.info" class="external-link" rel="nofollow">https://aries-interop.info</a> . Aries Agent Test Harness
(again) extended to support testing more W3C Standard Verifiable
Credentials and DIF Presentation Exchange. In addition. three new
frameworks were added to the daily interop runs, and a fourth was in
work.

# Overall Activity in the Past Quarter

Per the  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-09-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the second quarter of 2021, Aries codebases had 1000 commits from 68
contributors. Both numbers are up substantially from last quarter, 28%
and 39% respectively.

Community participation is extremely active in rocketchat channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

Coordination with the DIF DIDComm working group is healthy, with regular
reports being shared.

Project work in main repos is healthy and active.

# Current Plans

-   There has been a significant growth in building common code for
mobile wallet apps using both Aries Framework JavaScript and Aries
VCX.
-   The "Current Plans" mentioned in the last quarterly report saw
implementation this quarter – with much more work planned.
-   Most Aries teams are focused on adding the core capabilities of AIP
2.0 to their code bases.
-   Work is active to extend Aries beyond support just Indy ledgers and
Indy AnonCred verifiable credentials to supporting other ledgers and
other verifiable credential formats – most notably BBS+ signatures,
supporting ZKPs and selective disclosure.
-   ACA-Py and AF-Go have working code, including executing test
cases.

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
-   Call attendance for each is typically in the 20-25 range.
-   Most organizations have only one attendee; it is rare for more than
three to attend from the same organization.
-   Cross codebase interoperability efforts indicate cross-organization
cooperation.

# Additional Information

Related activity to Aries is occurring in
<a href="https://identity.foundation/" class="external-link" rel="nofollow">Decentralized Identity Foundation</a> (DIF), the
<a href="https://trustoverip.org/" class="external-link" rel="nofollow">Trust over IP Foundation</a> , and especially in their <a href="https://wiki.trustoverip.org/pages/viewpage.action?pageId=73790" class="external-link" rel="nofollow">Good Health Pass</a> initiative,
and in <a href="https://www.lfph.io/" class="external-link" rel="nofollow">Linux Foundation Public Health</a> (LFPH).

# Submission date

09-Nov-2021

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
<td><span id="comment-62227587"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> – The
information about Aries being used to address Climate Change is really
interesting.  Is there someone involved in that you could point me to? 
It would be great if they could present this to the Climate Action and
Accounting Special Interest Group.  That could be a group of people who
would be interested in using and contributing to Aries if they knew more
about this.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Nov 09, 2021 18:27 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62227945"></span>
<p>FYI, Stephen connected me to the right person over email and I
connected him to the Climate Action and Accounting SIG Chairs.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell
at Nov 11, 2021 22:09 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62228411"></span>
<p>Hyperledger Aries is really great project to build SSI systems, TOIP,
DIF also have   Indy Aries tech stack.</p>
<p>I want to highlight challenges which I faced using Aries Javascript,
As a mentor to one of the mentorship project" support fabric as a ledger
to Aries"( <a href="https://wiki.hyperledger.org/display/INTERN/Hyperledger+Fabric+-+Hyperledger+Aries+Integration+to+support+Fabric+as+Blockchain+ledger">Hyperledger
Fabric - Hyperledger Aries Integration to support Fabric as Blockchain
ledger</a> ). My mentee added a feature to support fabric as a ledger in
Aries Javascript but building AFJ locally is very challenging, we have
spent so much time to get  AFJ working in the local machine. </p>
<ol class="incremental">
<li>Building Hyperledger Aries Javascript is very challenging and lots
of issues are faced, documentation is not clear like how someone can
build AFJ locally.</li>
<li><span style="letter-spacing: 0.0px;">Currently, AFJ only supports
did, schema and credential definition as domain transactions.
Revocations not supported yet.   </span></li>
</ol>
<p><span style="letter-spacing: 0.0px;">I </span></p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by knagware9 at Nov 16, 2021 15:50 </div ></td>
</tr>
</tbody>
</table>




