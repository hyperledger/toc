---
layout: default
title: 2022 Q3 Hyperledger Indy
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Indy

Created by Stephen Curran, last modified by Tracy Kuhrt on Aug 29, 2022

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

# Project Health

This quarter we achieved a quality Ubuntu 20.04-based Hyperledger Indy
release candidate – a big milestone. The Release Candidate includes both
Indy Plenum and Indy Node, each of which were built, tested and
published using a modern, automated CI/CD pipeline. The maintainers are
working on the downstream plugins to enable deployment on existing
networks. Several new networks that are starting up have been deployed
using the new release candidates. This release is also the hold up for
the deployment of \`did:indy\`.

The community worked a lot this quarter on a couple of reported
vulnerabilities (CVEs). Both can be addressed in the current (pre-Ubuntu
20.04) and later versions, and fixes have been created. One is a
documentation advisory for configuring Indy nodes. It is still being
finalized, but is close to completion. The second is a new release of
Indy that is now available and ready for all "pure Indy" deployments.
Downstream releases are in process. The pain of producing this
(hopefully) final Ubuntu 16.04-based release demonstrates why the need
for the modern CI/CD pipeline is so desperately needed.

Much progress has been made this quarter in defining AnonCreds ZKP-based
verifiable credentials (which started life in Indy) as an open standard
(see the  <a href="https://anoncreds-wg.github.io/anoncreds-spec/" class="external-link" rel="nofollow">spec</a>  being created). Much
progress has been made recently in making AnonCreds ledger agnostic,
meaning that it is not dependent on Hyperledger Indy, but can be
supported by other ledgers and mechanisms. That change will reduce the
resistance to the use of AnonCreds by those thinking it is
"proprietary", but should also help Indy, as it is the easiest way to
deploy the capability.

The interest in deploying instances of Indy continues to be strong, with
lots of questions on Hyperledger Chat from people learning to run their
own instances.

Per the <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222022-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-06-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Indy Activity Dashboard (2022-04 to
2022-06)</a> , there were 133 commits from 16 contributors. both of
which are about the same as last quarter. However, that does not count
the CVE repos that are still private until the vulnerabilities have been
deployed in production instances.

# Questions/Issues for the TSC

## Issues from previous reports:

### Build Pipelines

**Update** : The Ubuntu upgrade is complete and producing releases –
including a release candidate. Awaiting final testing and downstream
artifacts to be tested before declaring the release ready.

### **Diversity of Contributor Community**

**Update** : Little change this quarter in contributor community. Lots
of interest, but the core maintainers continue to do most of the work.

# Releases

-   indy-plenum (Ubuntu 16.04) – CVE release
-   indy-plenum (Ubuntu 16.04) – v1.13.2-rc2
-   indy-node (Ubuntu 16.04) – CVE release
-   indy-node (Ubuntu 16.04) – v1.13.1-rc0, v1.13.2-rc2

# Overall Activity in the Past Quarter

In the past quarter (as in the previous quarter), ledger code
development focused on code management – upgrading the Indy Node and
Plenum CI/CD pipeline and upgrading Indy Node to run on Ubuntu 20.04. 

# Current Plans

With the new CI/CD Indy Node and Plenum pipelines complete, and the
Ubuntu 20.04 upgrade available, the core maintainers are focused on
their downstream releases.

# Maintainer Diversity

The bi-weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. Topics and attendance has increased
recently, with more and more interested parties showing up, and new
contributors weighing in on the conversations.

# Contributor Diversity

From the last report: The "Indy Contributors" course was presented in
early 2022 and was extremely well received. The edX course about Indy,
Aries and Ursa ( <a href="https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa" class="external-link" rel="nofollow">here</a> ) was updated early in
2021 (this was missed in the last Quarterly report – even though the
author of the quarterly report was the course creator...).

# Additional Information

-   Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
-   🔲 <span class="placeholder-inline-tasks">
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



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71699470"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> Thank
you for the report! A quick question: Do you plan on adding Ubuntu 22.04
(LTS) support anytime soon?</p>
<p>The reason for my curiosity is selfish as usual: Cactus has the Indy
CLI as a build dependency and we were looking into moving our dev
containers to be Ubuntu 22 based (up from the current Ubuntu 20)</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by Peter Somogyvari at Aug 08, 2022 19:48 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-71699473"></span>
<p>The CLI is part of the indy-sdk and so likely – but not certain –
works on 22.04 already.  I'll see what I can find out from the
Maintainers.</p>
<p><br />
</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Aug 08, 2022 20:05 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-71699521"></span>
<p>Looks like it is a follow on task to the Ubuntu 20.04 work for
indy-node. This came up on Discord today, and the issue was support for
libsodium18.  AFAIK, what we are using on Ubuntu 20.04 for indy-node is
working, so I would assume the same update would work with the CLI.</p>
<p><br />
</p>
<p>Discord Message:  <a href="https://discord.com/channels/905194001349627914/905205711850594336/1006443729856503818" class="external-link" rel="nofollow">https://discord.com/channels/905194001349627914/905205711850594336/1006443729856503818</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Aug 10, 2022 01:28 </div ></td>
</tr>
</tbody>
</table>




