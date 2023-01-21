---
layout: default
title: 2021 Q1 Hyperledger Indy
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Indy

Created by Stephen Curran, last modified by Gari Singh on Mar 17, 2021

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

Indy is a healthy project, particularly at the deployments and business
interest level, but continues to be short on contributors.  Interest has
increased in the quarter, with more contributors on the specific
initiatives of the team, and a lot more participation as the bi-weekly
the Contributors meeting. The current work focuses on modernizing the
CI/CD process to use GitHub Actions (and eliminate reliance on specific
people and infrastructure) for indy-node, indy-plenum and indy-sdk, and
upgrading the dependencies for indy-node artifacts to run on Ubuntu
20.04. Coming soon will be a code-focused effort to add support for the
new "did:indy" DID Method that will align Indy with the pending W3C DID
Core Specification.

A new repository was added to indy, contributed by the Government of
British Columbia – indy-shared-rs – which is a client library th"at provides in Rust a set of utilities for interacting with an Indy ledger.
It is part of the process of breaking up the indy-sdk.

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard?time=%7B%22from%22:%222020-11-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-01-31T08:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2020-11 to
2021-01)</a> , there were 52 commits from 15 contributors. which is in
line with the last quarter. I don't think those statistics include the
indy-shared-rs library.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : Good progress is being made on converting the CI/CD
pipelines from Jenkins to GitHub Actions, for indy-node, indy-plenum and
indy-sdk. This has been the focus of the community during this period as
without this, the ability to release products is extremely limited.

### **Diversity of Contributor Community**

**Update** : This remains a top of mind issue with the maintainers.  On
the last Indy Contributors call, we are considering a "Contributor
Campaign" in conjunction with Hyperledger Staff to build attention to
both Indy and the new "did:indy" DID Method.

# Releases

### None.

# Overall Activity in the Past Quarter

In the past quarter, ledger code development has slowed as we focus on
code management – upgrading the Indy Node and Plenum CI/CD pipeline and
upgrading Indy Node to run on Ubuntu 20.04.  The main code related
activity was done by a team focused on being able to remove ledger
plugins from a running instance of Indy.

Work continues on defining the Indy DID Method, with some good progress
being made.  We're nearing completion of that work – and nearing a need
for some new ledger code development efforts, particularly in Indy Node.

A release of the Indy SDK has been prepared and will be released
shortly. As well, the Indy SDK CI/CD pipelines have been migrated to
GitHub Actions and the existing pipelines will soon be retired.  As
well, the Verifiable Credential Exchange (VCX) component of the Indy SDK
has been pulled from the Indy SDK and moved to it's own repo in Aries.
The code was focused on Aries protocols, and so the move makes a lot of
sense.  This continues to the trend towards Indy just being a ledger for
decentralized identity and the Trust over IP stack vs. covering the
Agent and above layers of the stack.

As noted above, a new component, indy-shared-rs was contributed to
better support agents that want to interact with Indy ledgers without
depending on the entire Indy SDK.

# Current Plans

The push will continue this quarter to complete the new CI/CD Indy Node
and Plenum pipelines, and the Ubuntu 20.04 upgrade. In parallel, we'll
try to wrap up the "did:indy" DID Method specification and generate a
backlog of work to be added to Indy Node.  We anticipate that next
quarter, with the ability to easily release code, addressing the DID
Method backlog will be the focus.

# Maintainer Diversity

The bi-weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. The core maintainers are in close contact,
and the new maintainers are gaining experience and confidence with the
components.

# Contributor Diversity

We've had several organizations join the Indy Contributors call and some
are doing the work on the upcoming release (code changes) and the CI/CD
pipeline. Interest in Indy has been rising because of the demand for
verifiable credentials related to the various COVID-19 use cases, such
as travel and back to work plans.

# Additional Information

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
-   🔲 <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41593040"></span>
<p>You may already have plan for these, but bringing them up</p>
<ol class="incremental">
<li><span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow" style="text-decoration: none;">Have you switched from
master to main in all your repos</a> ? </span></li>
<li><span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow" style="text-decoration: none;">Have you implemented
repolinter.json in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span></li>
</ol>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Feb 18, 2021 13:31 </div ></td>
</tr>
</tbody>
</table>




