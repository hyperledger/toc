---
layout: default
title: 2022 Q2 Hyperledger Indy
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q2 Hyperledger Indy

Created by Stephen Curran, last modified by Grace Hartley on May 24, 2022

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
-    <a href="https://github.com/hyperledger/indy-node-container" class="external-link" rel="nofollow">indy-node-container</a>
<img src="emoticons/add.svg" class="emoticon emoticon-plus" data-emoticon-name="plus" alt="(plus)" /> NEW!

# Project Health

<span style="letter-spacing: 0.0px;">In a change from the previous
quarters, contributions to Indy ticked up this quarter – a good thing! 
The project is getting a lot of external attention and that is
(finally!) changing into contributor interest.  Attendance is up
significantly at community meetings, a new repo was added (
<a href="https://github.com/hyperledger/indy-node-container" class="external-link" rel="nofollow">indy-node-container</a>  – a
containerized instance of Indy Node for easier deployment). As well, the
first  major addition to Indy in some time was added – an implementation
of did:indy in  </span>
<a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>indy-node </span></a> , with the following
features:

-   Indy clients (e.g. Aries Agents) can add full DID Standard DIDDocs
to an Indy DID published on the ledger. This had not been supported
in Indy prior to this because Indy pre-dated the DID Standard.
-   A client can indicate a new DID is self-certifying, with the ledger
verifying that the DID (the identifier) was derived from the initial
verkey (public key) of the key pair associate with the DID
-   The <a href="https://github.com/hyperledger/indy-did-method" class="external-link" rel="nofollow">did-indy-method</a> repository
and <a href="https://hyperledger.github.io/indy-did-method/" class="external-link" rel="nofollow">published spec</a> have been
updated to match the implementation.
-   Changes were added to indy-vdr to implement the "network of
networks" support so that a DID will contain an extra "namespace" element indicating on which Indy network the object is to be found.
-   A mechanism has been defined based on the concept of DID URLs as a
mechanism for providing identifiers for other AnonCred objects
beyond DIDs: schemas, CredDefs and Revocation Registries.
-   The use of the ATTRIB transaction was deprecated in favour of the
(somewhat) less arbitrary DIDDoc feature of DIDs. The use of ATTRIBs
may be used for other purposes in the future, but we'd like to stop
the "wild, wild west" days of using ATTRIB for anything.

A BC Gov "Code With Us" challenge for $CDN70k was create to get work on
the "did:indy" method done. The challenge was won last quarter and
implemented this quarter by two respondents –
<a href="https://indicio.tech/" class="external-link" rel="nofollow">Indicio</a> for the Indy Node/Plenum work and
<a href="https://wiki.hyperledger.org/display/~domwoe" class="confluence-userlink user-mention" data-username="domwoe" data-linked-resource-id="36734205" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dominic Wörner</a>  for the
Indy VDR (Client) work. They completed the plan worked and their changes
have been merged into the relevant code bases. Kudos to all of the
participants and the progress it represents!

<span style="letter-spacing: 0.0px;">On the less good news front, the
CI/CD upgrade and Ubuntu 20.04 effort moved forward, but is still not
complete.  Just as was stated in the last quarterly report, there is
still work to do, but progress was made – including some significant
updates.  The big items to complete remain the same: </span>

-   Investigation of a potential intermittent bug on a network with a
mix of Ubuntu 16.04 and 20.04 nodes (likely something in libsodium).
-   Automation of a tagged release to produce published artifacts.

As mentioned in the last report, the focus on making AnonCreds a
standard vs. an open source implementation de facto standard is gaining
momentum. The standard drafting process is going will, producing this
work in progress
<a href="https://anoncreds-wg.github.io/anoncreds-spec/" class="external-link" rel="nofollow">spec</a> , with a strong contingent
working regularly to evolve it.

Work continues this quarter on the new client-side Indy library
indy-vdr, and on indy-shared-rs, although no new releases were tagged.
The Aries Cloud Agent Python project has made the use of the shared
components (along with
<a href="https://github.com/hyperledger/aries-askar" class="external-link" rel="nofollow">Aries Askar</a> ) as the
recommended default for ACA-Py. The stability and performance results
are much better than with Indy SDK.

The interest in deploying instances of Indy continues to be strong, with
lots of questions on Hyperledger Chat from people learning to run their
own instances. There are no significant bugs that are pending action,
and little demand for new functionality (beyond the "did:indy" method)
from the user base. Indy "just works". 

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222022-01-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-03-31T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2022-01 to
2022-03)</a> , there were 135 commits from 20 contributors. both of
which are double the numbers from last quarter.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : Steady progress, with GHAs implemented, the test automation
process updated and the Ubuntu upgrade nearing completion.

### **Diversity of Contributor Community**

**Update** : Contributor community diversity remains a top of mind issue
with the maintainers. We're seeing improvements beginning as more
deployments begin (notably Aries deployments) and the importance of the
underlying ledger utility is understood. We need more, but in this
quarter, there was improvement seen.

# Releases

-   indy-did-method (completed)

# Overall Activity in the Past Quarter

In the past quarter (as in the previous quarter), ledger code
development focused on code management – upgrading the Indy Node and
Plenum CI/CD pipeline and upgrading Indy Node to run on Ubuntu 20.04. 
Unlike previous quarters, there was also work completed on the did:indy
DID Method and effort put into providing stable indy-node containers.

# Current Plans

The push will be to complete the new CI/CD Indy Node and Plenum
pipelines, the Ubuntu 20.04 upgrade.

# Maintainer Diversity

The bi-weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. Topics and attendance has increased
recently, with more and more interested parties showing up, and new
contributors weighing in on the conversations.

# Contributor Diversity

The "Indy Contributors" course was presented in early 2022 and was
extremely well received. The edX course about Indy, Aries and Ursa ( <a href="https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa" class="external-link" rel="nofollow">here</a> ) was updated early in
2021 (this was missed in the last Quarterly report – even though the
author of the quarterly report was the course creator...).

# Additional Information

-   Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>






