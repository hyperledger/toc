---
layout: default
title: 2021 Q3 Hyperledger Indy
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Indy

Created by Stephen Curran, last modified
by Arun S M on Nov 01, 2021

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

# Project Health

The work on the Indy DLT (indy-node and indy-plenum) slowed this quarter
to a focus only on the CI/CD capabilities and upgrading to Ubuntu 20.04;
no new functionality was added. The transition of the CI/CD from an
older, undocumented Jenkins/manual process to a GHA-based CI/CD pipeline
has been slow. The work on the CI/CD and OS Upgrade has prevented any
progress on new features – blocking most notably the upgrade to the new
"did:indy" DID Method. With the change of the W3C DID Specification to
"Proposed Standard" it is appropriate that work start (and finish)
soon.  In addition to the CI/CD work, the team is add some tooling to
make it much easier to get started doing development on the project. The
goal is to promote the tribal knowledge about the projects into easily
followed steps to deploy for development, make changes, debug and run
tests. To be clear, these changes are focused on making it easier to
make changes to the DLT code itself.

On a positive note, the interest in deploying instances of Indy
continues, with lots of questions on Hyperledger Chat from people
learning to run their own instances. Further, there are no significant
bugs that are pending action, and no demand for new functionality from
the user base. Indy "just works".  For example, the Sovrin networks
(MainNet, StagingNet and BuilderNet, operated by more than 50
organizations) is celebrating its 5th birthday this month, and coming up
to 2 years without an outage. Even demand for the new "did:indy" DID
Method is moderate at best. 

Work has proceeded on the replacements for Indy SDK – indy-vdr and
indy-shared-rs, with a tagged release of both projects.  

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222021-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-06-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2021-04 to
2021-06)</a> , there were just 34 commits from 7 contributors. which is
a significant drop from the last quarter.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : Work was not completed last quarter as expected on this
task. We'll see how it goes this quarter...

### **Diversity of Contributor Community**

**Update** : Contributor community diversity remains a top of mind issue
with the maintainers.  We are considering a "Contributor Campaign" in
conjunction with Hyperledger Staff to build attention to both Indy and
the new "did:indy" DID Method. The need is not for "drive-by" devs doing
their first commit, but rather those that are building their businesses
on Indy and should be contributing to the evolution of the project. To a
degree, the project is a victim of its quality and completeness, as
mentioned in the "Project Health" section.

# Releases

-   indy-sdk 1.16.0
-   indy-shared-rs 0.3.0
-   indy-vdr 0.3.0

# Overall Activity in the Past Quarter

In the past quarter, ledger code development has slowed as we focus on
code management – upgrading the Indy Node and Plenum CI/CD pipeline and
upgrading Indy Node to run on Ubuntu 20.04.  

There was no progress on the new Indy DID Method. The work left at the
end of the last quarter remains: wrapping up the specification and
defining the backlog of work for indy-node, indy-sdk and indy-vdr. With
the CI/CD work blocking progress on indy-node, it's very difficult to
convince contributors in the community to work on the DID Method if it
is so hard to test and impossible to release.

# Current Plans

The push will be to complete the new CI/CD Indy Node and Plenum
pipelines, the Ubuntu 20.04 upgrade, and tools to make it easier to do
Indy Node development. Until that is completed, there will not be
changes to the functionality.

# Maintainer Diversity

The bi-weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. Topics and attendance has dropped
recently, somewhat due to holidays, but also due to the lack of topics
other than "how is the CI/CD work coming along?"
# Contributor Diversity

See the comments in the "Issues" section (above). With work limited to
CI/CD work on the Indy DLT side, there is little else to be done until
that is complete.

# Additional Information

( ***Note* – no change** )

-   Key channels on Hyperledger Rocket Chat: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a>
-   ✅ <span style="color: rgb(23,43,77);">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a>  </span>
-   ✅ <a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






