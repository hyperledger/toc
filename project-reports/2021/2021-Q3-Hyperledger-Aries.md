---
layout: default
title: 2021 Q3 Hyperledger Aries
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Aries

Created by Stephen Curran, last modified by Angelo De Caro on Dec 09, 2021

<span style="letter-spacing: 0.0px;"> </span> <span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Aries

# Project Health

Hyperledger Aries continues to garner a lot of activity from
contributors and a lot of interest from those wanting to use Aries in
various use cases. It has an extremely diverse and global community.
There were significant milestones accomplished within Aries this past
quarter, including the approval by the community of the Aries Interop
Profile (AIP) 2.0, which extends the AIP 1.0 from 2020 to achieve Aries
stated goal of being both ledger and verifiable credential form"at agnostic.

The new capabilities that are included in AIP 2.0 have been added to
some of the Aries frameworks, allowing for opportunities to interoperate
with products and tools from other verifiable credential ecosystems. A
collaborative effort (called WACI-PEx) started at the Internet Identity
Workshop is bringing together teams from the W3C, DIF and Hyperledger
Aries communities.

# Questions/Issues for the TSC

None.

# Releases

The following releases occurred in the last quarter:

-   Aries Interop Profile 2.0
-   Aries Cloud Agent Python Release 0.7.0 (early July)
-   Major release adding support for W3C Standard BBS+ verifiable
credentials, DIF Presentation Exchange, a pluggable DID
Resolver, Indy Endorser handling
-   Adds support for running the new "shared components" (indy-vdr,
indy-shared-rs and aries-askar), allowing operation without the
Indy SDK.
-   Aries Framework JavaScript – many regular "unstable" releases th"at are leading up to the 0.1.0 release
-   Now used as the basis for the new Aries Bifold ( <a href="https://github.com/hyperledger/aries-mobile-agent-react-native)" class="external-link" rel="nofollow">https://github.com/hyperledger/aries-mobile-agent-react-native)</a>
 open source wallet.
-   Aries Askar 0.2.0, 0.2.1 (early July)
-   Aries VCX Releases 0.17.0, 0.18.0, 0.19.0
-   Aries Mobile Agent Xamarin (Aries-MAX) 0.1.0
-   Lots of activity on this open source wallet.

Interoperability status can be seen here: 
<a href="https://aries-interop.info" class="external-link" rel="nofollow">https://aries-interop.info</a> . Aries Agent Test Harness
extended to support testing W3C Standard Verifiable Credentials and DIF
Presentation Exchange. In addition, work is underway for adding test
agents based on three other frameworks, expanding the community of
products that are verified to be interoperable.

The Hyperledger Labs " <a href="https://github.com/hyperledger-labs/business-partner-agent" class="external-link" rel="nofollow">Business Partner Agent</a> " project is an application that is built on Aries (ACA-Py) that is
extremely active and interesting. It forsees a future where
organizations run Aries agents that allow for the secure interchange of
authentic data between business partners – supply chain participants,
customers, suppliers, etc. This includes a company sharing basic, public
information (as verifiable credentials) about itself for all those th"at are interested. Instead of relying on Google-ing for information about a
company, ask it and get back verifiable credentials; authentic data.

# Overall Activity in the Past Quarter

Per the  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222021-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-06-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the first quarter of 2021, Aries codebases had 871 commits (up
substantially from last quarter) from 49 contributors.

Community participation is extremely active in rocketchat channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

Coordination with the DIF DIDComm working group is healthy, with regular
reports being shared.

Project work in main repos is healthy and active.

# Current Plans

-   Most Aries teams are focused on adding the core capabilities of AIP
2.0 to their code bases.
-   Work is active to extend Aries beyond support just Indy ledgers and
Indy AnonCred verifiable credentials to supporting other ledgers and
other verifiable credential formats – most notably BBS+ signatures,
supporting ZKPs and selective disclosure.
-   ACA-Py and AF-Go have working code
-   The Aries Mobile Agent React Native (aka Bifold) built on Aries
Framework JavaScript has been extremely active is becoming the open
source wallet a larger community rallied behind.
-   Aries Framework JavaScript is nearing AIP 1.0-complete, and once
there, will quickly move on to replicating the AIP 2.0 features
already part of other frameworks, especially support for W3C
Standard BBS+ Verifiable Credentials.
-   Interoperability testing continues to be a key focus.

# Maintainer Diversity

Aries is a multi-codebase effort, and each codebase has its own set of
maintainers. The diversity of maintainers closely matches contributors,
with notes below.  Cross framework collaboration is increasing. For
example, work is happening on interop testing capabilities across the
Python, Go, .NET, Rust and JavaScript frameworks, with two developers of
proprietary Aries implementations joining in as well.

As interest in verifiable credentials has increased with COVID-19 use
cases (proof of testing, proof of immunization and mobile medical
workforces), interest and attendance has increased, as have deployments
of Aries-based implementations.

# Contributor Diversity

In addition to the code contribution statistics (above), here are a few
indicators of our current diversity:

-   We hold two community calls on Wednesdays: weekly at noon Pacific to
cover US and Pacific contributors, and biweekly at 7am Pacific to
cover US and European contributors.
-   Call attendance for each is typically in the 15-20 range.
-   Most organizations have only one attendee; it is rare for more than
3 to attend from the same organization.
-   Cross codebase interoperability efforts indicate cross-organization
cooperation.

# Additional Information

Related activity to Aries is occurring in
<a href="https://identity.foundation/" class="external-link" rel="nofollow">DIF</a> (Decentralized Identity Foundation), the
<a href="https://trustoverip.org/" class="external-link" rel="nofollow">Trust over IP Foundation</a> , and especially in their <a href="https://wiki.trustoverip.org/pages/viewpage.action?pageId=73790" class="external-link" rel="nofollow">Good Health Pass</a> initiative,
and in <a href="https://www.lfph.io/" class="external-link" rel="nofollow">Linux Foundation Public Health</a> (LFPH).

# Submission date

06-Aug-2021

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7" class="confluence-userlink user-mention" data-username="8a9ebdad74c3ca030175df13fdb500d7" data-linked-resource-id="62239223" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">user-74455</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~tracy" class="confluence-userlink user-mention" data-username="tracy" data-linked-resource-id="2392240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






