---
layout: default
title: 2020 Q1 Hyperledger Indy
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Indy

Created by Lynn Bendixsen, last modified by Christopher Ferris on Feb 13, 2020

# <span style="letter-spacing: 0.0px;">Projects </span>

##### **Distributed Ledger**

-   I
<a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>ndy-node </span></a>
-   I <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>ndy-plenum </span></a>

##### **Client Tool**

-   I
<a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>ndy-sdk </span></a>

##### **Shared Components**

-   I
<a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>ndy-hipe </span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>Indy-test-automation</span></a>

# Project Health

Indy is a healthy project. Indy’s codebase has 25886 commits from 182
unique contributors. This represents an increase of 5 contributors this
quarter and about 1900 additional commits. Forums and chat channels are
monitored and a variety of participants are contributing helpful
responses to questions.

# Questions/Issues for the TSC

We continue to track some of the same issues as in <a href="https://wiki.hyperledger.org/display/HYP/2019+Q4+Hyperledger+Indy" rel="nofollow"><span>previous quarters </span></a> .

### **Measuring the size and make-up of our user community**

Update:

We didn’t move forward with this effort in the past quarter.

Future work planned:

-   Work with Hyperledger to get analytics about web sites, and Rocket
Chat usage. 
-   Begin measuring usage of the Sovrin forums: new contributors,
questions asked, and questions answered
-   We will also explore the use of Github's contributor tool. 

### **Build Issues**

Update:

The volunteers who were working on migrating the build from Jenkins to
GitLab CI were not able to complete a functional system. The build is
complex due to the variety of target environments for LibIndy and the
requirement of running an Indy Node pool for testing. The approach taken
in Jenkins is significantly different than the approach favored by GitLab CI or Azure Pipelines, and migration will require significant
effort.

Future work planned:

-   We need a new commitment from the various teams who have expressed
interest.

### **Diversity of Contributor Community**

Update:

As agent implementers have moved to the Aries project, Indy was left
with few contributors to the ledger who all primarily come from a single
organization. The health of the project requires broadening this list.

Future work planned:

-   Current initiatives are being led by different organizations, which
we hope will become consistent contributors in the future.

# Releases

### **November 2019:**

##### Indy Node 1.11.0

-   Switch to PBFT View Change protocol
-   Stability fixes

##### Indy Node 1.12.0

-   Improve primary selection algorithm
-   Take into account transaction history when recovering state for new
nodes
-   Fix new nodes adding when there are old AUTH\_RULE or plugin
transactions

### **December 2019:**

##### **Indy SDK 1.13.0**

-   LibVCX Aries support:

-   -   Implemented Connection RFC (IS-1180)
-   Implemented Credential Issuance RFC (IS-1393)
-   Implemented Credential Presentation RFC (IS-1394)
-   Integrated Connection Protocol into Dummy Cloud Agent (IS-1392)

-   Added "names" parameter to Proof Request Revealed Attributes
(IS-1381)

-   Bugfixes:

-   -   Fixed bool representation in Java wrapper (IS-1368)

##### **Indy SDK 1.14.0 /1.14.1**

-   LibVCX Aries support:

-   Transaction author agreement changes (IS-1427):

-   -   Extended the definition of
indy\_build\_txn\_author\_agreement\_request function to accept
new parameters:
-   Added a new function
indy\_build\_disable\_all\_txn\_author\_agreements\_request to
disable all Transaction Author Agreement on the ledger.
-   new Indy-CLI commands

-   Bugfixes

##### **Indy Node 1.12.1**

-   Multiple active TAAs implementation
-   Stability fixes

### **January 2020:   **

##### **Indy SDK 1.14.2**

-   LibVCX Aries support:

-   -   Implemented Basic Message RFC (IS-1189)

-   Indy-CLI changes:

-   -   Added new command pool set-protocol-version to set a protocol
version that will be used for ledger requests (IS-1391).
-   Added new command payment-address new that does exactly the same
work as the existing payment-address create command. The new
command was added to match the naming of did new command. The
payment-address create command will be removed in future
releases (IS-1415).

-   Bugfixes

##### **Indy Node 1.12.2**

-   Stability fixes

# Overall Activity in the Past Quarter

In the past quarter, ledger development has focused on refactoring the
most complicated parts of the system. This has included a lot of bug
fixing, automated testing, documentation, and polish. Work on the client
libraries has been focused on adding support for the new Aries protocols
and planning the evolution to fit into the proposed Aries architecture.
This has also included a lot of bug fixing, documentation, and polish.
Indy Rocket-chat channels have daily activity where questions are posed
and answers are regularly given. 

# Current Plans

Ledger development is currently focused on adding support for Verifiable
Credentials as defined by the W3C working group, which we are calling
“Rich Schemas”. Our focus for client libraries is to break LibIndy into
separate components that can be evolved to fit the proposed Aries
architecture. By the end of the quarter, we would also like to be
working on improved revocation.

# Maintainer Diversity

The weekly Indy Maintainers call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. The Maintainers who work exclusively on
Indy is decreasing as many of them move on to help with the Hyperledger
Aries project.

# Contributor Diversity

Evernym is still the primary contributor to ledger development, but the
Rich Schemas effort has been led by the team at the Sovrin Foundation,
and the team at British Columbia Government is leading the effort to
evolve LibIndy. Smaller contributions have been made by representatives
from Kiva, Absa, IBM, Deutsche Telekom, and four independent
contributors.

# Additional Information

-   Key channels on Hyperledger Rocket Chat: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
-   🔲Angelo De Caro
-   ✅Arnaud J Le Hors
-   ✅Christopher Ferris
-   ✅Dan Middleton
-   🔲Gari Singh
-   ✅Hart Montgomery
-   ✅Mark Wagner
-   ✅Nathan George
-   ✅Swetha Repakula
-   ✅Tracy Kuhrt
-   ✅Troy Ronda






