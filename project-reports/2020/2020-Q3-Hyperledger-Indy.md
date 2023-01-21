---
layout: default
title: 2020 Q3 Hyperledger Indy
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Indy

Created by Stephen Curran, last modified by Troy Ronda on Aug 20, 2020

# <span style="letter-spacing: 0.0px;">Projects </span>

##### **Distributed Ledger**

-   <a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>indy-node </span></a>
-   <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>indy-plenum </span></a>

##### **Client Tool**

-   <a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>indy-sdk </span></a>

##### **Shared Components**

-   <a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>indy-hipe </span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>indy-test-automation</span></a>
-   Soon to be added:
<a href="https://github.com/bcgov/indy-node-monitor" class="external-link" rel="nofollow">indy-node-monitor</a>

# Project Health

Indy is a healthy project, but has a current lack of contributors.  The
maintainers are working to address that issue.

Per the
<a href="https://lfanalytics.io/projects/hyperledger%2Findy/dashboard" class="external-link" rel="nofollow">Indy Activity Dashboard</a> ,
Indy’s codebase has 21,028  commits from 238 unique contributors. This
quarter there were 61 commits from 8 contributors.

# Questions/Issues for the TSC

We continue to track some of the same issues as in <a href="https://wiki.hyperledger.org/display/HYP/2020+Q1+Hyperledger+Indy" rel="nofollow"><span>previous quarters </span></a> .

### **Measuring the size and make-up of our user community**

Update: Thanks to the awesome work of 
<a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> , the
<a href="https://lfanalytics.io/projects/hyperledger%2Findy/dashboard" class="external-link" rel="nofollow">Indy Activity Dashboard</a> shows
the activity in the Indy community.

### **Build Issues**

Update: No Progress - issue repeated.

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

Update: No progress - issue repeated.

As agent implementers have moved to the Aries project, Indy was left
with few contributors to the ledger who all primarily come from a single
organization. The health of the project requires broadening this list.

Future work planned:

-   Current initiatives are being led by different organizations, which
we hope will become consistent contributors in the future.
-   New: Developer Conference planned for September, 2020:  [Indy
Interop-a-thon - Making "Network of Networks" Real](https://wiki.hyperledger.org/pages/viewpage.action?pageId=36734079)

# Releases

### **June 2020:**

##### Indy Node 1.12.3

-   A response to an identified security vulnerability that if exploited
could take down an Indy network instance.

# Overall Activity in the Past Quarter

In the past quarter, ledger development has slowed to the release of a
security fix. Some work has occurred in the indy-sdk, but no releases
are planned. The difficulty in releasing is a challenge for the
community.

# Current Plans

There is little ledger activity occurring. Previous work on "rich
schemas" to support W3C VCs has been put on hold and will likely be
replaced with a focus on BBS+ ZKPs, which likely has the benefit of
eliminating (well, deprecating) features from Indy vs. adding. Our focus
for client libraries is to break LibIndy into separate components th"at can be evolved to fit the proposed Aries architecture. Work on an
improved revocation has progressed slowly, delayed within the Ursa
community.

We are planning an " [Indy Interop-a-thon - Making "Network of Networks" Real](https://wiki.hyperledger.org/pages/viewpage.action?pageId=36734079)
" virtual conference.  Details of the goal of the conference can be
found in the link.

The need for a better CI/CD solution is rising. There are currently no
active maintainers available to drive releases. Resources can be called
on for help, but there are no active participants available to do th"at independently.

# Maintainer Diversity

The weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. The Maintainers who work exclusively on
Indy is decreasing as many of them move on to help with the Hyperledger
Aries project. We are hoping the <a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=36734079" rel="nofollow">Indy virtual conference</a> in September will trigger an
increase in maintainers.

# Contributor Diversity

The team at British Columbia Government is leading the effort to evolve
LibIndy, although that is largely at the lower levels – not yet in Indy
(e.g. at the Rust crates layer). ABSO continues to contribute, as do
members of several other organizations.

# Additional Information

-   Key channels on Hyperledger Rocket Chat: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
-   🔲Angelo De Caro
-   ✅Arnaud J Le Hors
-   ✅Christopher Ferris
-   🔲Dan Middleton
-   🔲Gari Singh
-   ✅Hart Montgomery
-   ✅Mark Wagner
-   ✅Nathan George
-   ✅Swetha Repakula
-   🔲Tracy Kuhrt
-   ✅Troy Ronda






