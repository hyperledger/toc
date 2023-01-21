---
layout: default
title: 2019 Q1 Hyperledger Indy
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q1 Hyperledger Indy

Created by Lynn Bendixsen, last modified on Feb 07, 2019

<span style="letter-spacing: 0.0px;font-size: 24.0px;">Projects </span>

##### <span style="color: rgb(51,51,51);">Distributed Ledger </span>

-   <a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">indy-node</span></a>

-   <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">indy-plenum </span></a>

##### <span style="color: rgb(51,51,51);">Client Tools </span>

-   <a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">indy-sdk</span></a>

-   <a href="https://github.com/hyperledger/indy-agent" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">indy-agent </span></a>

##### <span style="color: rgb(51,51,51);">Shared Components </span>

-   <a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">Indy-hipe</span></a>

-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span style="color: rgb(17,85,204);">Indy-test-automation </span></a>

-   <a href="https://github.com/hyperledger/indy-crypto" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">indy-crypto </span></a>

# Project Health

<span style="color: rgb(51,51,51);">The contributors to Hyperledger Indy
spent this past quarter working on these key initiatives: </span>

1.  Addressing ledger stability concerns raised during testing and
during production outages of client networks.

2.  Adding ledger monitoring to continue preparation for widespread
usage.

3.  Maturing agent standards to build ecosystem compatibility.

4.  Developing reference agents so that they are usable by new
participants in the ecosystem.

5.  Documentation improvements to enhance ease of use and encourage new
contributors.

<span style="color: rgb(51,51,51);">These efforts have yielded
significant results. </span>

1.  Ledger monitoring scripts have been implemented and real time
notifications are in place and operational on some ledgers.

2.  Work has accelerated significantly on agent standardization.
Multiple implementations of agents are nearing the ability to
connect to each other thanks to efforts from members of the
community from many different organizations. An Agent
“Connect-a-thon” is scheduled for this month (February) to
demonstrate the ability to connect different agents, resolve any
remaining issues, and determine next steps as a community. See <a href="https://docs.google.com/document/d/1dfGj5yjpSHzRF6UVPv7Ld1PTFme3fsXEwpLs0_e6NGA/edit#heading=h.ssygez1ks54i" class="external-link" rel="nofollow"><span style="color: rgb(17,85,204);text-decoration: underline;">Agent
Connectathon Agenda </span></a> .

3.  Superb effort has been put in to consolidate the Hyperledger-Indy
documentation for ease of use. See
<a href="http://hyperledger-indy.readthedocs.io/" class="external-link" rel="nofollow"><span style="color: rgb(19,103,154);">hyperledger-indy.readthedocs.io</span></a> and
<a href="http://doc.sovrin.org/" class="external-link" rel="nofollow"><span style="color: rgb(19,103,154);">doc.sovrin.org</span></a> .

4.  Indy’s codebase has surpassed  <span style="color: rgb(0,0,0);">17,000 </span> commits from  <span style="color: rgb(0,0,0);">143 unique </span> contributors.

<span style="font-size: 24.0px;letter-spacing: 0.0px;">Issues </span>

Our top issues from last quarter continue to be our central concerns,
but we have made some useful progress.

### <span style="color: rgb(0,0,0);">Ensure quality releases for downstream users </span>

Improvements over last quarter have been made for this issue. Releases
and deployment have been consistent and timely as improvements to the
ledger have been tested and delivered.

<span style="color: rgb(51,51,51);">Progress made: </span>

-   <span style="color: rgb(51,51,51);">Continued improvements in the CI
/ CD pipeline have provided more reliable releases with consistent
versions of components. </span>

<span style="color: rgb(51,51,51);">Further remediation planned: </span>

-   <span style="color: rgb(51,51,51);">The Indy team will continue to
focus on providing releases that can be immediately deployed
downstream. </span>

-   <span style="color: rgb(51,51,51);">The team is being more
deliberate about preserving backwards compatibility. (More work is
still needed here) </span>

### <span style="color: rgb(0,0,0);">Inconsistent documentation </span>

<span style="color: rgb(51,51,51);">Documentation quality and
consolidation remains an important issue, but significant progress has
been made to improve. </span>

<span style="color: rgb(51,51,51);">Progress made: </span>

-   In the past quarter we published consolidated documentation to
shared sites: 
<a href="http://hyperledger-indy.readthedocs.io/" class="external-link" rel="nofollow"><span style="color: rgb(17,85,204);text-decoration: underline;">hyperledger-indy.readthedocs.io</span></a> and
<a href="http://doc.sovrin.org/" class="external-link" rel="nofollow"><span style="color: rgb(17,85,204);text-decoration: underline;">doc.sovrin.org</span></a> .

<span style="color: rgb(51,51,51);">Further remediation planned: </span>

-   <span style="color: rgb(51,51,51);">Publish the getting started
resources somewhere that is public and likely to be found. </span>

-   <span style="color: rgb(51,51,51);">Continue to consolidate
redundant documentation and reworking it for different user levels.</span>

### <span style="color: rgb(0,0,0);">Incompatible agent implementations </span>

<span style="color: rgb(51,51,51);">Efforts are ongoing to increase
interoperability between existing agent implementations and future
implementations. </span>

<span style="color: rgb(51,51,51);">Progress made: </span>

-   Wire level message formatting has been established and merged into
the Indy-SDK.

-   An Agent “Connect-a-thon” will be held this month (February 19-22)
demonstrating the ability of different agent implementations to
connect and communicate over accepted protocols.

-   Preliminary tests for connection protocol are implemented in the
agent test suite and are ready for testing.

-   Maintainers of libVCX have committed to implement the community
approved protocols outlined in HIPEs.

<span style="color: rgb(51,51,51);">Further remediation planned: </span>

-   Continue standardizing agent communication protocols, including
credential exchange.

-   Mature the agent test suite.

### <span style="color: rgb(0,0,0);">Measuring the size and make-up of our user community </span>

<span style="color: rgb(51,51,51);">We began making progress on this
issue by measuring the number of developers creating solutions by contributing to indy github projects. </span>

<span style="color: rgb(51,51,51);">Progress made: </span>

-   We are measuring GitHub contributors and can produce a week-by-week
graph of contributors added over the last year.

<span style="color: rgb(51,51,51);">Further remediation planned: </span>

-   <span style="color: rgb(51,51,51);">Work with Hyperledger to get
analytics about web sites, and Rocket Chat usage. </span>

-   <span style="color: rgb(51,51,51);letter-spacing: 0.0px;">Begin
measuring usage of the Sovrin forums: new contributors, questions
asked, and questions answered </span>

-   <span style="color: rgb(51,51,51);letter-spacing: 0.0px;">Measure
Indy tags on Stack Overflow. </span>

### <span style="color: rgb(0,0,0);">Build Issues </span>

Progress made:

-   Significant effort has been made to move the building of client
libraries and reference agents to the Sovrin Foundation and this
work is nearing completion.

Further remediation planned:

-   CI/CD pipelines will target prebuilt dependencies instead of
building them from source.

-   <span style="letter-spacing: 0.0px;">CI/CD pipelines will be put in
place first before additional code changes are made. </span>

# Releases

<span style="color: rgb(51,51,51);font-size: 16.0px;font-weight: bold;letter-spacing: 0.0px;">November
2018: </span>

##### <span style="color: rgb(51,51,51);">Indy SDK 1.6.8 </span>

-   Fix State Proof verification for some types of GET requests to the
ledger

-   Additional clean-up for secrets in logs

-   Update CLI help

### <span style="color: rgb(51,51,51);">December 2018: </span>

##### <span style="color: rgb(51,51,51);">Indy SDK 1.7.0 </span>

-   Added VCX - a library built over libindy for Verifiable Credentials
eXchange. API is EXPERIMENTAL.

-   -   Mobile builds are not currently available - they will be added
in future releases.

-   Added Logging API

-   -   Added function indy\_get\_logger for plugins to give their
logging to libindy.

-   Added function indy\_set\_logger for client apps and wrappers to
receive logs from libindy

-   Integrated libindy logging into Slf4j for Java wrapper and into
python logging facade.

-   Updated API of Rust wrapper. Now there is not three methods for each
API call, there is only one that returns Future.

-   Introduced multithreading for Wallet API and CRED\_DEF generation.

-   Bug fixes

##### <span style="color: rgb(51,51,51);">Indy Node 1.6.79 </span>

-   <span style="color: rgb(51,51,51);">Fixes to improve stability.</span>

-   Output of validator-info changed and enhanced to meet growing need.

-   Bug fixes

##### <span style="color: rgb(51,51,51);">Indy Node 1.6.80 </span>

-   Initial hotfixes for network stability issues.

-   Pool restart will now work regardless of whether there is consensus
on the ledger.

##### <span style="color: rgb(51,51,51);">Indy Node 1.6.82 </span>

-   Additional hotfixes for improved stability.

### <span style="color: rgb(51,51,51);">January 2019:    </span>

<span style="color: rgb(51,51,51);letter-spacing: 0.0px;">No new
releases </span>

# Overall Activity in the Past Quarter

**<span style="color: rgb(51,51,51);letter-spacing: 0.0px;">General</span>**

-   Graduation from incubation status only requires 3 more action items:

-   <span style="letter-spacing: 0.0px;">An Indy use cases document
(a community effort just started with  </span> <a href="https://docs.google.com/document/d/1EMiqzdd-6TB2puzamDGJSLrDTwUz_QW46xdEp2FLnbI/edit?usp=sharing" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;"><span style="color: rgb(17,85,204);">this
doc </span> </a> <span style="letter-spacing: 0.0px;">) </span>

-   Confirmation that indy projects implement perfect forward
secrecy

-   Automated code coverage collection

-   This is very difficult considering our tech stack. There is
active development on this front and it will hopefully be
implemented soon.

**<span style="color: rgb(51,51,51);letter-spacing: 0.0px;">Indy Node</span>**

-   Significant focus on performance and stability. Several
stability fixes have been implemented and ledgers are running better
than ever.

-   Continued research into a future ledger architecture.

**<span style="color: rgb(51,51,51);">Indy SDK </span>**

-   Release of experimental LibVCX.

-   Started work to support HIPEs defining Agent to Agent compatibility.

-   The Indy team continues to work with other Hyperledger teams to
transition from the indy-crypto component to Hyperledger Ursa.

##### **<span style="color: rgb(51,51,51);">Indy Agent </span>**

-   Many HIPEs moved to accepted status.

-   Significant iterations on and discussion surrounding several HIPEs.

-   <span style="color: rgb(0,0,0);">Increased collaboration with new
contributors in the community. </span>

# Current Plans

<span style="color: rgb(51,51,51);">Additional organizations are making
ongoing contributions. This is shown by the shared </span>
<a href="https://wiki.hyperledger.org/projects/indy/roadmap" rel="nofollow"><span style="color: rgb(0,136,0);">Running Roadmap</span></a> <span style="color: rgb(51,51,51);"> for Hyperledger Indy.</span>

##### <span style="color: rgb(51,51,51);">General </span>

-   Incubation status graduation.

-   -   <span style="color: rgb(0,0,0);">Complete the three items
mentioned earlier in this document and apply for graduation.</span>

-   Continue to refine documentation.

-   -   Consolidate documentation for onboarding contributors.

-   Network stability of the first production deployment (Sovrin).

-   <span style="color: rgb(34,34,34);">Schema improvements! </span>
-   <span style="color: rgb(34,34,34);">We are currently working on
enhanced schemas that will be compatible with the W3C Verifiable
Credentials standards.  </span> <span style="color: rgb(34,34,34);"> Our current credentials use
schemas that are simple flat lists of untyped strings and this
effort will allow complex data structures such as those
available from
<a href="http://schema.org/" class="external-link" rel="nofollow"> 
<span style="color: rgb(17,85,204);">schema.org </span></a> .</span>
-   <span style="color: rgb(34,34,34);">New encoding methods (to
convert properties to signature values) and presentation (proof)
requests will be able to preserve privacy and security through
zero-knowledge proofs (ZKP) while maintaining the cryptographic
assurances that the credential values have not been modified.
The new encoding methods will expand the number of credential
values that can be used in predicate proofs, such as "greater
than", "less-than-or-equal", etc. </span>
-   <span style="color: rgb(34,34,34);">Schema re-use between
Verifiable Credential issuers will promote interoperability.</span>

-   <span style="color: rgb(34,34,34);">Indy Catalyst </span>
-   <span style="color: rgb(34,34,34);">The OrgBook implemented as
part of British Columbia's Verifiable Organization Network (VON)
is being contributed to Hyperledger as Indy Catalyst. It
provides a template for bootstrapping credential ecosystems
built on Indy. </span>

##### <span style="color: rgb(51,51,51);">Indy Node </span>

-   <span style="color: rgb(0,0,0);">Consume official builds of
Hyperledger Ursa (the shared crypto-lib), as they are approved.</span>

-   <span style="color: rgb(0,0,0);">Further improvements to automated
testing. </span>

-   <span style="color: rgb(34,34,34);">Audit ledger </span>
-   <span style="color: rgb(34,34,34);">As we moved permission
management to the config ledger, we identified the need for an
audit ledger to make it easy to verify what permissions were in
place with each write. </span>
-   <span style="color: rgb(34,34,34);">The audit ledger will also
ensure deterministic catch-up between ledgers which resolves
some BFT consensus corner cases. </span>

-   <span style="color: rgb(0,0,0);">Research into Ledger 2.0 </span>

-   <span style="letter-spacing: 0.0px;">We are confident that Indy
Node can scale to millions of users, but we have identified a
number of problems with the existing implementation that will
limit future scalability. Solutions are likely to require
fundamental architectural changes. </span>

-   <span style="color: rgb(0,0,0);">Improve the stability and
performance of View Change, Catch-up, and Replication. </span>

-   <span style="color: rgb(0,0,0);">Establish a cache for reads,
such as observer nodes. </span>

-   We are recruiting contributors from various organizations to
assist in designing the future of the ledger and starting
implementation.

-   <span style="color: rgb(0,0,0);">Broader OS support. </span>

<span style="color: rgb(51,51,51);font-weight: 600;letter-spacing: 0.0px;">Indy
SDK </span>

-   <span style="color: rgb(0,0,0);">Broader OS support. </span> <span style="color: rgb(34,34,34);"></span>

-   The SDK is being updated to comply with HIPEs documenting
interoperability standards which we call  <span style="color: rgb(0,0,0);">Agent to Agent compatibility. </span>

-   <span style="color: rgb(0,0,0);">Consume official builds of
Hyperledger Ursa (the shared crypto-lib), as they are approved.</span>

-   <span style="color: rgb(34,34,34);letter-spacing: 0.0px;">LibVCX,
the credential exchange library, is available in Indy SDK as an
experimental API. We are evolving that API to respond to community
feedback. </span>

-   These efforts are likely to require backwards incompatible changes
to the API, requiring an Indy SDK 2.0.

<span style="color: rgb(0,0,0);font-weight: 600;letter-spacing: 0.0px;">Indy
Agent </span>

-   Standardizing agent-to-agent protocol through an agent test suite.

-   Tests associated with each major aspect of the protocol.

-   Multiple interoperable agents in the community.

-   Mobile agents from the Sovrin Foundation and Evernym, and web
agents from BC.gov, BYU, and StreetCred.

-   <span style="color: rgb(0,0,0);">Addition of a reference cloud
agent. </span>

# Maintainer Diversity

<span style="color: rgb(0,0,0);"> <span style="color: rgb(51,51,51);">Indy maintainers remain active in
developing and contributing to working group calls and public
discussions. The bi-weekly Indy Maintainers Circle call has consistently
been the medium by which maintainers coordinate work, discuss critical
issues to the Indy codebase, and resolve HIPEs. The Indy Agent call
continues to be the focus of much attention, and the Overlays Working
Group also continues to receive a lot of interest </span> <span style="color: rgb(51,51,51);">. </span> </span>

# Contributor Diversity

<span style="color: rgb(0,0,0);"> <span style="color: rgb(51,51,51);">Hyperledger Indy continues to see
contributions from developers and organizations around the world. Our
weekly Working Group call is normally attended by two dozen people
representing nearly a dozen organizations. Please note the number of
contributors and contributions listed in the Project Health section
above. </span> </span>

# <span style="color: rgb(51,51,51);font-size: 16.0px;font-weight: bold;letter-spacing: 0.0px;">POCs, Pilots, Projects </span>

##### <span style="color: rgb(51,51,51);">Sovrin </span>

<a href="http://www.sovrin.org/" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">http://www.sovrin.org </span></a>

<span style="color: rgb(51,51,51);">Sovrin is the first instantiation of
the Indy codebase and is currently moving from the provisional network
phase of development to production usage. </span>

##### <span style="color: rgb(51,51,51);">Verifiable Organizations Network </span>

<a href="https://von.pathfinder.gov.bc.ca/" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">https://von.pathfinder.gov.bc.ca</span></a>

<span style="color: rgb(51,51,51);">The Province of British Columbia,
the Government of Ontario, and Public Services and Procurement Canada
are ready to launch their trusted digital network of verifiable data
about organizations. </span>

##### <span style="color: rgb(51,51,51);">Brigham Young University </span>

<a href="https://www.byu.edu/" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">https://www.byu.edu/ </span></a>

<span style="color: rgb(51,51,51);">The University is building an agent
to manage student credentials throughout their experience at the
university. </span>

##### <span style="color: rgb(51,51,51);">Evernym </span>

<a href="https://www.evernym.com/" class="external-link" rel="nofollow"><span style="color: rgb(43,115,183);">https://www.evernym.com/ </span></a>

<span style="color: rgb(51,51,51);">Evernym is creating applications
that will make it easy for organizations and users to issue, hold, and
verify credentials through the Sovrin network. </span>

# Additional Information

-   <span style="color: rgb(51,51,51);">Join the Indy Mailing List:</span> <span style="color: rgb(43,115,183);">
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow">https://lists.hyperledger.org/g/indy</a> </span>

<!-- -->

-   <span style="color: rgb(51,51,51);">Join the Indy Working Group
Calls: every Thursday 8am PT, 9am MT, 11am ET, 4pm BST (Join from
PC, Mac, Linux, iOS or Android: </span>
<a href="https://zoom.us/j/232861185" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;"><span style="color: rgb(43,115,183);">https://zoom.us/j/232861185 </span></a>
<span style="color: rgb(51,51,51);">) </span>




