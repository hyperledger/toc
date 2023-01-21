---
layout: default
title: 2020 Q2 Hyperledger Indy
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Indy

Created by Lynn Bendixsen, last modified by Gari Singh on Jun 11, 2020

# Projects

##### **Distributed Ledger**

-   <a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>indy-node </span></a>
-   i <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>ndy-plenum </span></a>

##### **Client Tool**

-   i
<a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>ndy-sdk </span></a>
-   <a href="https://github.com/hyperledger/indy-vdr" class="external-link" rel="nofollow"><span>indy-vdr </span></a>
-   <a href="https://github.com/andrewwhitehead/indy-credx" class="external-link" rel="nofollow"><span>indy-credx </span></a>
(to be transitioned to Hyperledger)
-   <a href="https://github.com/andrewwhitehead/indy-shared-rs" class="external-link" rel="nofollow"><span>indy-shared-rs </span></a>
(to be transitioned to Hyperledger)

##### **Shared Components**

-   I
<a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>ndy-hipe </span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>Indy-test-automation</span></a>

# Project Health

Indy is a healthy project. Indy’s codebase has 26582 commits from 189
unique contributors. This represents an increase of 7 contributors this
quarter and about 696 additional commits. Forums and chat channels are
monitored and a variety of participants are contributing helpful
responses to questions.

A recent focus has been on breaking up the single indy-sdk client tool
into separate components:

-   indy-vdr for ledger interactions
-   indy-credx for anonymous verifiable credential exchange
-   indy-shared-rs for shared client tool utilities

These new libraries provide an easier, more modular integration for
Aries Agents (the primary consumers of indy client artifacts) and are
more accessible for developers wanting to contribute to the project and
use the artifacts of the project. Work has started on an Aries Secure
Storage repository that on completion will enable the depreciation of
the indy-sdk in favour of these new components.

Work has also begun on the number one request from the Indy community—a
“jurisdiction-scale” verifiable credential revocation mechanism.

As well, a plan has been formulated (but not yet executed) for migrating
the Indy (especially the indy-sdk) CI/CD pipelines from their current
Jenkins-basis to GitHub Actions.

# Questions/Issues for the TSC

We continue to track some of the same issues as in <a href="https://wiki.hyperledger.org/display/HYP/2019+Q4+Hyperledger+Indy" rel="nofollow"><span>previous quarters </span></a> .

### **Measuring the size and make-up of our user community**

Update:

Modest progress with this effort in the past quarter.

-   Moved from JIRA to GitHub Issues for issue tracking, making easier
to measure the size of the community engagement.

Future work planned:

-   Work with Hyperledger to get analytics about web sites, and Rocket
Chat usage. 
-   Generate standardized statistics on GitHub Issue tracking.

### **Build Issues**

Update:

A <a href="https://wiki.hyperledger.org/display/CICD/Sovrin+resource+migration" rel="nofollow"><span>plan </span></a> was formulated for transitioning
from the current Jenkins-based pipeline to GitHub Actions with the
option of tactical deployment of Azure Pipelines.  The necessity to get
off of Jenkins has increased because of the current reliance on Sovrin
Foundation’s AWS resources that are at risk because of the financial
status of the Foundation. Resources from BC Gov have been identified for
the first part of the work, but it’s not their highest priority, and
little progress has been made to date. Access to resources from other
teams have decreased for the next few months because of COVID-19 related
projects.

Future work planned:

-   Getting resources for the project that can make it their highest
priority.

### **Diversity of Contributor Community**

Update:

As agent implementers have moved to the Aries project, Indy was left
with few contributors to the ledger, mostly from a single organization.
The health of the project requires broadening this list. Progress on
that goal was made this quarter as many of the contributions have come
in from new core developers and project leads from other organizations
(notably, BC Gov, Kiva and Mattr Global).  The transition off of Jira
and onto GitHub Issues was a step in trying to expand contributions by making it easier to see where contributions would be welcomed.  The
first GitHub issues raised have attracted some attention, so initial
feedback on the change is positive.

Future work planned:

-   Current initiatives are being led by different organizations, which
we hope will become consistent contributors in the future.

# Releases

**February 2020:**

##### None 

### **March 2020:**

##### **Indy SDK 1.14.3**

-   LibVCX:

-   -   Removed connection\_handle from functions to get protocol
messages.
-   Added ability to accept a duplicate connection by redirecting to
the already existing one instead of forming a duplicate
connection.
-   Added a new function
vcx\_disclosed\_proof\_decline\_presentation\_request to
explicitly reject a presentation request.
-   Added a new function vcx\_connection\_info to get information
about connection.

-   Bugfixes

-   -   Fix proof verification in case of credential attribute encoded
value contains leading zeros (IS-1491).
-   Fix artifacts at <a href="http://repo.sovrin.org" class="external-link" rel="nofollow">repo.sovrin.org</a> for Ubuntu 18.04
-   others minor bugfixes

##### **Indy SDK 1.15.0**

-   Correction for Fix proof verification in case of credential
attribute encoded value contains leading zeros (IS-1491). Indy
1.14.3 changes "0" to "" which leads to proof rejection.
-   LibVCX: Supported protocol\_version: 3.0 which actually is an
alternative to combination of settings: protocol\_version: 2.0 and
communication\_method: aries.
-   LibVCX: Fixed compatibility between proprietary (protocol\_version:
2.0/1.0) and aries communication protocols (protocol\_version: 3.0).
-   Bugfixes

### **April 2020:   **

##### **None**

# Overall Activity in the Past Quarter

In the past quarter, efforts have been largely focused on creating
replacement components for the indy-sdk, enabling its depreciation of
favour of several separate components. Verifiable Credential Revocation
2.0 work has started, building on the cryptography built into Ursa. A
preliminary design has been defined and tech spikes started to evaluate
the feasibility of that plan. Plans for migrating from Jenkins to GitHub
Actions-based CI/CD have been formulated but not executed.

# Current Plans

Revocation, continued working on breaking up the indy-sdk, and the
migration of CI/CD pipelines will be the primary focus of efforts this
quarter. Most of the work will have to be done with limited input from
the previous core team (who are busy on other projects in the space),
which will be an interesting experiment. That said, Indy is very stable
right now, and there is not a pressing need from the community for a lot
more than is being planned.

# Maintainer Diversity

The bi-weekly Indy Maintainers call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. A recent increase in the number of
participants on the call has been encouraging, although that has yet to
translate into more commits from outside developers.

# Contributor Diversity

COVID-19 efforts have restricted Evernym from being able to contribute
significantly to the code base in recent weeks and that is anticipated
to go on for the next few months. The Sovrin Foundation was forced to
let go of their paid staff (including Indy contributors) and is
operating on a volunteer basis.  While that has slowed down efforts on
the project, the current highest priority items (mentioned earlier -
revocation, the break-up of the indy-sdk and the CI/CD migration)
continue to move forward through the efforts of other contributors and
key guidance from the Evernym team.

# Additional Information

-   Key channels on Hyperledger Rocket Chat: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers

-   Join the Indy Mailing List:
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow">https://lists.hyperledger.org/g/indy</a>

# <span style="letter-spacing: -0.01em;">Reviewed by </span>

-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






