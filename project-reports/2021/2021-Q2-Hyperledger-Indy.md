---
layout: default
title: 2021 Q2 Hyperledger Indy
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Indy

Created by Stephen Curran, last modified by Arun S M on May 15, 2021

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

Very little has changed in the overall summary, so the following is
essentially the same as the last quarter: Indy is a healthy project,
particularly at the deployments and business interest level, but
continues to be short on contributors.  Interest has <s>increased</s>
 maintained in the quarter, with <s>more</s> contributors on the
specific initiatives of the team, and <s>a lot more</s>  continued
participation at the bi-weekly the Contributors meeting. The current
work focuses on modernizing the CI/CD process to use GitHub Actions (and
eliminate reliance on specific people and infrastructure) for indy-node,
indy-plenum and indy-sdk, and upgrading the dependencies for indy-node
artifacts to run on Ubuntu 20.04. Coming soon will be a code-focused
effort to add support for the new "did:indy" DID Method that will align
Indy with the pending W3C DID Core Specification.

Work has proceeded, with releases, on the replacements for Indy SDK –
indy-vdr and indy-shared-rs.  Those will lead up to a new capability to
run Aries agents (notably at first, Aries Cloud Agent Python agents) run
without need for the indy-sdk.

The CI/CD work is very close to completion, and a new Ubuntu 20.04
version of Indy is expected Real Soon Now. The completion of that work
will make it much easier to evolve Indy.

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard?time=%7B%22from%22:%222021-01-01T00:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-03-31T23:59:59.254Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2021-01 to
2021-03)</a> , there were 121 commits from 20 contributors. which is up
slightly from the last quarter.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : The end is in sight on changing the CI/CD pipelines from
Jenkins to GitHub Actions for indy-node, indy-plenum and indy-sdk. CD is
all that is left. This has been the focus of the community during this
period as without this, the ability to release products is extremely
limited.

### **Diversity of Contributor Community**

**Update** : This remains a top of mind issue with the maintainers.  We
are considering a "Contributor Campaign" in conjunction with Hyperledger
Staff to build attention to both Indy and the new "did:indy" DID Method.

# Releases

-   indy-sdk 1.16.0
-   indy-shared-rs 0.2.3
-   indy-vdr 0.2.0

# Overall Activity in the Past Quarter

In the past quarter, ledger code development has slowed as we focus on
code management – upgrading the Indy Node and Plenum CI/CD pipeline and
upgrading Indy Node to run on Ubuntu 20.04.  The main code related
activity was done by a team focused on being able to remove ledger
plugins from a running instance of Indy.

Work on defining the new Indy DID Method is largely complete, with the
key decisions all made.  Left is wrapping up the specification and
defining the backlog of work for indy-node, indy-sdk and indy-vdr.

# Current Plans

( ***Note* – little changed** ) The push will to (finally!) complete the
new CI/CD Indy Node and Plenum pipelines, and the Ubuntu 20.04 upgrade.
In parallel, we'll try to wrap up the "did:indy" DID Method
specification and generate a backlog of work to be added to Indy Node,
Indy VDR and Indy SDK.  We anticipate that next quarter, with the
ability to easily release code, addressing the DID Method backlog will
be the focus.  We also expect to see a renewed interest in that work as
Indy deployments spin up in both North America (Indicio Network) and
Europe (IDUnion).

# Maintainer Diversity

( ***Note* – no change** ) The bi-weekly Indy Contributors call
continues to be the medium by which maintainers coordinate work, discuss
critical issues to the Indy codebase, and agree on HIPEs. The core
maintainers are in close contact, and the new maintainers are gaining
experience and confidence with the components.

# Contributor Diversity

( ***Note* – no change** ) We've had several organizations join the Indy
Contributors call and some are doing the work on the upcoming release
(code changes) and the CI/CD pipeline. Interest in Indy has been rising
because of the demand for verifiable credentials related to the various
COVID-19 use cases, such as travel and back to work plans.

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
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






