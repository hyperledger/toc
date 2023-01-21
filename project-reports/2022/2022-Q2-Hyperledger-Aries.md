---
layout: default
title: 2022 Q2 Hyperledger Aries
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q2 Hyperledger Aries

Created by Stephen Curran, last modified by Grace Hartley on May 24, 2022

<span style="letter-spacing: 0.0px;"> </span> <span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Aries

# Project Health

Hyperledger Aries continues to grow stronger in terms of activity by contributors and in the interest from those using Aries in various use
cases. It has an extremely diverse and global community. In addition to
the steady progress made in most of the sub-projects, a number of
significant events occurred in the project including:

-   Rapid progress on Aries Framework JavaScript continues, with key AIP
v2.0 PRs merged (e.g. support for Credential Exchange V2 and W3C VC
Standard credentials) or in process.
-   Aries Bifold, the community-developed react native mobile Wallet App
built on Aries Framework JavaScript, also continues to evolve
rapidly, with impressive deployment-specific pipelines that allow
going from Bifold, overlaying instance specific code and publishing
the result to the iOS and Android stores. This powerful
approach allows rapid iteration of published products with the
changes being put in exactly the right place – AFJ, AFJ-Extension,
Aries Bifold (all of which benefit the entire community) or to the
deployment specific instance. This gets away from the
"fork-and-forget" model, enabling proper open source development for
a UX-focused project.
-   The community is stress testing the Aries frameworks and some issues
have been reported, and addressed, as you will see. The addition of
an open source 
<a href="https://github.com/My-DIGI-ID/aries-cloudagent-loadgenerator" class="external-link" rel="nofollow">Aries Load Generator</a> tool
(which I think will be moving to Hyperledger) provides an amazing
tool for exploring these issues. The combination of the load test
generator and some focused work in
<a href="https://github.com/hyperledger/aries-askar" class="external-link" rel="nofollow">Aries Askar</a> both addressed
the intermittent problems and boosted Askar performance by 11% in
the process.  Very cool!
-   The load test generator also enables an easy way to do a direct
comparison of the old IndySDK and the new Aries Askar and shared
components. As seen by these results, Askar is far more stable
than the Indy SDK (doesn't slow over time) and is about twice as
fast as the Indy SDK – the differences are stark!  See the
follow test run results for <a href="https://github.com/lissi-id/acapy-load-test-results/blob/main/AcaPy_0-7-3/Without%20Multitenancy/Revokable/Full%20Flow%20Constant%20Load/13%20AcaPy%200_7_3%20indy_wallet/report-test-results.pdf" class="external-link" rel="nofollow">ACA-Py 0.7.3+IndySDK</a>
and <a href="https://github.com/lissi-id/acapy-load-test-results/blob/main/AcaPy_0-7-4/Endurance_Test/0_7_4-200rpm/report-test-results-0-6.pdf" class="external-link" rel="nofollow">ACA-Py 0.7.4+Askar</a>
-   Both the 
<a href="https://aries-interop.info/" class="external-link" rel="nofollow">Aries Agent Test Harness</a>  and the 
<a href="https://github.com/hyperledger/aries-mobile-test-harness" class="external-link" rel="nofollow">Aries Mobile Test Harness</a>
continue to evolve with more contributions provided this past
quarter in making them work together and in expanding the tests
being run.
-   Attendance at the regular communities meetings is up, with 35+
people at recent Aries Cloud Agent Python User Group meeting.
-   Work has begun in integrating DIDComm V2 into the Aries frameworks –
some design and some implementation work. We think this will
progress slowly as interest is clearly in what people can do
**today** but these proof-of-concepts demonstrate that Aries
frameworks are well designed to enable such evolutions.

There continues to be lots of delivered, verified code, let alone the
increases in participation and use of Aries.

As mentioned in the last report, the focus on making AnonCreds a
standard vs. a de facto standard is gaining momentum. The standard
drafting process is going will, producing
<a href="https://anoncreds-wg.github.io/anoncreds-spec/" class="external-link" rel="nofollow">this work in progress spec</a> ,
with a strong contingent working regularly to evolve it.

The Indy/Aries stack continues to be the global leader in SSI/verifiable
data solutions.

# Questions/Issues for the TSC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python Release 0.7.4-rc0, 0.7.4-rc1
-   Aries Framework JavaScript – 0.2.0-alpha
-   Aries Askar 0.2.5
-   Aries VCX Releases 0.28.0 through 0.45.0

Interoperability status can be seen here: 
<a href="https://aries-interop.info" class="external-link" rel="nofollow">https://aries-interop.info</a> . 

# Overall Activity in the Past Quarter

Per the  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222022-01-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-03-31T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the first quarter of 2022 (Jan-March), Aries codebases had 1.37k commits
(up significantly) from 60 contributors (up slightly).

Community participation is extremely active in Discord channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

Coordination with the DIF DIDComm working group is healthy, with regular
reports being shared.

Project work in main repos is healthy and active. A potential concern
raised last quarter was the lack of activity in the Aries Framework .NET
repository, but even that had some activity this quarter, with a couple
of interesting PRs completed and merged.

# Current Plans

-   A continued focus on building common code for mobile wallet apps
using both Aries Framework JavaScript and Aries VCX.
-   Based on feedback from the community – a lot of effort has gone into
stress testing Aries – especially Aries Cloud Agent Python, with
good results.
-   A split focus between deploying more production solutions and moving
the Aries frameworks forward to use new protocols – AIP 2.0 and
DIDComm v2.
-   A focus on standardizing AnonCreds to provide increased comfort of
the solid foundation in Aries and use beyond Aries.

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
-   Call attendance for each is typically in the 15-20 range, up
somewhat lately. 
-   Most organizations have only one attendee; it is rare for more than
three to attend from the same organization.
-   Cross codebase interoperability efforts indicate cross-organization
cooperation.

# Additional Information

Nothing

# Submission date

04-May-2022

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
-   🔲 <span class="placeholder-inline-tasks"> <a href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7" class="confluence-userlink user-mention" data-username="8a9ebdad74c3ca030175df13fdb500d7" data-linked-resource-id="62239223" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">user-74455</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
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
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>




