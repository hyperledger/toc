---
layout: default
title: 2019 Q2 Hyperledger Indy
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q2 Hyperledger Indy

Created by Lynn Bendixsen</span>, last modified by Binh Nguyen</span> on Apr 25, 2019

# <span style="letter-spacing: 0.0px;">Project</span>

##### **Distributed Ledger**

-   <a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>indy-node</span></a>
-   <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>indy-plenum</span></a>

##### **Client Tools**

-   <a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>indy-sdk</span></a>
-   <a href="https://github.com/hyperledger/indy-agent" class="external-link" rel="nofollow"><span>indy-agent</span></a>

##### **Shared Components**

-   <a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>Indy-hipe</span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>Indy-test-automation</span></a>
-   <a href="https://github.com/hyperledger/indy-crypto" class="external-link" rel="nofollow"><span>indy-crypto</span></a>

<span style="font-size: 24.0px;letter-spacing: 0.0px;">Project
Health</span>

The contributors to Hyperledger Indy spent this past quarter working on
these key initiatives:

1.  Hyperledger INDY has graduated from incubation status.
2.  Developing reference agents so that they are usable by new
participants in the ecosystem.
3.  Schema improvements are now in a proposed overview HIPE for
community comment and feedback.
4.  Ursa updated to 0.1.1 which means Indy-SDK can begin using it.
5.  Major breakthroughs on Agent Interoperability with 6 independent
agent implementations passing the Agent Test Suite and more
discussions on Credentials Exchange and other key protocols.

Indy’s codebase has 20 ,000 commits from 164 unique contributors. This
represents an increase of 19 contributors this quarter and nearly 3,000
additional commits. Forums and chat channels are monitored and responses
to questions are frequent, timely, and helpful.

# Issues

While we have resolved some issues during the past quarter, some of our
top issues from last quarter continue to be our central concerns. As
noted below, we continue to make useful progress.

### **Incompatible agent implementations**

Efforts are ongoing to increase interoperability between existing agent
implementations and future implementations.

Progress made:

-   6 Independent Agent implementations are passing the Agent Test
Suite.
-   Routing and Credentials tests will shortly enter the Agent Test
Suite.

Further remediation planned:

-   Continue standardizing agent communication protocols, including
credential exchange.

### **Measuring the size and make-up of our user community**

We began making progress on this issue by measuring the number of
developers creating solutions by contributing to indy github projects.

Progress made:

-   We are measuring GitHub contributors and can produce a week-by-week
graph of contributors added over the last year.

Further remediation planned:

-   Work with Hyperledger to get analytics about web sites, and Rocket
Chat usage.
-   Begin measuring usage of the Sovrin forums: new contributors,
questions asked, and questions answered
-   Measure Indy tags on Stack Overflow.

### **Build Issues**

The current Jenkins CI pipeline has become slow, bloated, and difficult
to maintain and extend.

Progress made:

-   The building of client libraries and reference agents has moved to
the Sovrin Foundation and this work is nearing completion.

Further remediation planned:

-   Move from Jenkins to Gitlab CI for simpler configuration, greater
security, and allowing third parties to contribute build resources.

# Releases

### **February 2019:**

##### **Indy SDK 1.8.0**

-   Added NETWORK\_MONITOR role to nym transaction builder
-   Updated Libindy wrappers for automatically getting error details
-   Bugfixes

##### **Indy SDK 1.8.1**

-   Bugfixes

##### **Indy Node 1.6.83**

-   Added network maintenance role

-   Bugfixes

-   -   Node on Sovrin TestNet did not upgrade automatically
-   Node that does not upgrade spams the config ledger
-   Node can't order after view change and catch up
-   A role that has been removed can't be added back

### **March 2019:**

##### **Indy SDK 1.8.2**

-   Added auth\_rule feature
-   Set default freshness threshold to 600 seconds
-   Send GET requests to two Nodes
-   Bugfixes

### **April 2019:   **

##### **Indy Node 1.7.0**

-   Added multi-signature auth\_rule feature
-   Audit Ledger

# Overall Activity in the Past Quarter

##### **General**

-   Indy has graduated from incubation status.
-   Schema improvements are now in a proposed overview HIPE for
community comment and feedback.

##### **Indy Node**

-   Audit ledger feature is now complete.
-   Multi-sign auth\_rules have been added to increase security.
-   Several new stability fixes have been implemented.
-   Continued research into a future ledger architecture.

##### **Indy SDK**

-   Continued work to support HIPEs defining Agent to Agent
compatibility.
-   Hyperledger Ursa updated to 0.1.1 which means Indy-SDK can begin
using it.

##### **Indy Agent**

-   Incredible progress on interoperability with the Connectathon and
Test Suites.
-   Acceptance of connection, basic message, and trust ping HIPEs.
-   Credentials Exchange HIPE and provisional 0.1 version in active
development.
-   HIPE Discussion and Improvements on several other subjects.
-   Significant reference agent development continues.



# Current Plans

##### **General**

-   Add the Hyperledger Aries project
-   Continue to refine documentation
-   Schema improvements

##### **Indy Node**

-   Consume official builds of Hyperledger Ursa, as they are approved.
-   Audit ledger adoption and improvement.
-   Continue research into Ledger 2.0
-   Broader OS support.

##### Indy SDK

-   Broader OS support.
-   Consume official builds of Hyperledger Ursa, as they are approved.

##### Indy Agent

-   Credentials Exchange protocol in the Test Suite
-   Introducing agents to other agents
-   Routing & Agencies
-   Test Suite improvements for automated testing



# Maintainer Diversity

Indy maintainers remain active in developing and contributing to working
group calls and public discussions. The bi-weekly Indy Maintainers
Circle call has consistently been the medium by which maintainers
coordinate work, discuss critical issues to the Indy codebase, and
resolve HIPEs. The Indy Agent call continues to be the focus of much
attention, and the Overlays Working Group also continues to receive a
lot of interest.

# Contributor Diversity

Hyperledger Indy continues to see contributions from developers and
organizations around the world. Our weekly Working Group call is
normally attended by two dozen people representing nearly a dozen
organizations. Indy’s codebase has 20 ,000 commits from 164 unique
contributors. This represents an increase of 19 contributors this
quarter and nearly 3,000 additional commits.

### **POCs, Pilots, Projects**

##### **Sovrin**

<a href="http://www.sovrin.org/" class="external-link" rel="nofollow"><span>http://www.sovrin.org</span></a>

Sovrin is the first instantiation of the Indy codebase.

##### **Verifiable Organizations Network**

<a href="https://von.pathfinder.gov.bc.ca/" class="external-link" rel="nofollow"><span>https://von.pathfinder.gov.bc.ca</span></a>

The Province of British Columbia, the Government of Ontario, and Public
Services and Procurement Canada have a trusted digital network of
verifiable data about organizations.

##### **Brigham Young University**

<a href="https://www.byu.edu/" class="external-link" rel="nofollow"><span>https://www.byu.edu/</span></a>

The University is building an agent to manage student credentials
throughout their experience at the university.

##### **Evernym**

<a href="https://www.evernym.com/" class="external-link" rel="nofollow"><span>https://www.evernym.com/</span></a>

Evernym is creating applications that will make it easy for
organizations and users to issue, hold, and verify credentials through
the Sovrin network.

# Additional Information

-   Join the Indy Mailing List:
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow"><span>https://lists.hyperledger.org/g/indy</span></a>

<!-- -->

-   Join the Indy Working Group Calls: every Thursday 8am PT, 9am MT,
11am ET, 4pm BST (Join from PC, Mac, Linux, iOS or Android:
<a href="https://zoom.us/j/232861185" class="external-link" rel="nofollow"><span>https://zoom.us/j/232861185</span></a> )

# Reviewed by
-   🔲 <span style="color: rgb(0,0,0);">Arnaud Le Hors</span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang</span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen</span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris</span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton</span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery</span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson</span> </span> </span></span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner</span> </span> </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman</span> </span> </span> </span></span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George</span> </span> </span></span> </span> </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis</span> </span> </span></span> </span> </span> </span> </span>






