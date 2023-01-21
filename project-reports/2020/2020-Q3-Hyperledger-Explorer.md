---
layout: default
title: 2020 Q3 Hyperledger Explorer
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Explorer

Created by jeeva sang, last modified by Gari Singh on Sep 17, 2020

# Project

<a href="https://github.com/hyperledger/blockchain-explorer" class="external-link" rel="nofollow">Hyperledger Explorer</a>

# Project Health

<span style="color: rgb(23,43,77);">Project health is green. </span>
<span style="color: rgb(23,43,77);"> We use all of the following to help
keep project health green. Questions asked via rocket chat are being
answered in a timely manner. For greater efficiency in this regard, the
FAQ page is updated with every release. </span>

# Questions/Issues for the TSC

No issues currently.

# Releases

v1.1.2 (13 Aug 2020)

-   <span style="color: rgb(36,41,46);">Add user management feature</span>
-   <span style="color: rgb(36,41,46);">Reduce container image size</span>
-   <span style="color: rgb(36,41,46);">Add fabric 1.4.8 / 2.2.0 support</span>
-   <span style="color: rgb(36,41,46);">Update example of connection
profile for docker setup </span>

v1.1.1 (17 Jul 2020)

-   <span style="color: rgb(36,41,46);">Publish new simple landing page
on Github   </span>
-   <span style="color: rgb(36,41,46);">Add configuration for mutual TLS
support   </span>
-   <span style="color: rgb(36,41,46);">Add PEM string format support
for the connection profile </span>
-   <span style="color: rgb(36,41,46);">Add Fabric CA support to
retrieve credential for admin access to the fabric network </span>

v1.1.0 (01 Jul 2020)

-   <span style="color: rgb(36,41,46);">Support for Hyperledger Fabric
v2.1.1 </span>
-   <span style="color: rgb(36,41,46);">Support for Hyperledger Fabric
v1.4.6 as well in the same codebase </span>
-   <span style="color: rgb(36,41,46);">Fix segfault in Explorer
container </span>
-   <span style="color: rgb(36,41,46);">Making Hyperledger Explorer
compatible to Amazon Managed Blockchain Network </span>

# Overall Activity in the Past Quarter

Discussions happened via rocket chat and questions are being answered on
time.

We have added functionality to support the latest fabric v2.1 and v2.2
with v1.4.6 in the same codebase itself, making  <span style="color: rgb(36,41,46);">Hyperledger Explorer compatible with
Amazon Managed Blockchain Network and reduce the container image size.</span>

Added new features for User Management

# Current Plans

-   Migration of implementation to Typescript 
-   Add new GUI for user management
-   Apply ACL rule of network to Hyperledger Explorer user management
-   <span style="color: rgb(23,43,77);">Unifying 2 platforms
(fabric/iroha) support into master branch </span>
-   <span style="color: rgb(23,43,77);">Add new peer metrics view based
on the information collected via prometheus </span>
-   Continue on bug fixes, help community in configuring HLExplorer and
troubleshooting.  

# Maintainer Diversity

<span style="color: rgb(23,43,77);">We've had a few spot contributors
added.  </span> <span style="color: rgb(23,43,77);">No new maintainers
were added. We really need the community to come forward and contribute.</span>

<span style="color: rgb(23,43,77);">Please find here the maintainers
list.  <a href="https://github.com/hyperledger/blockchain-explorer/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow">https://github.com/hyperledger/blockchain-explorer/blob/master/MAINTAINERS.md</a></span>

# Contributor Diversity

Current main contributors are from DTCC and Fujitsu. We have 4 unique
contributors on Github and 6 unique reporters on JIRA in this quarter.

We have started conversation about <a href="https://wiki.hyperledger.org/pages/viewpage.action?pageId=31198839" rel="nofollow">Contribute-a-thon</a> for Hyperledger Explorer project
with  <a href="https://wiki.hyperledger.org/display/~davidwboswell" class="confluence-userlink user-mention" data-username="davidwboswell" data-linked-resource-id="2392933" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Boswell</a> and 
<a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a>

And we had some proposals for Hyperledger Explorer as below:

-   <a href="https://github.com/litong01/minifabric" class="external-link" rel="nofollow">minifab</a> project is offering Hyperledger Explorer
support as one of their features and we think it will be a good
mutual reference. 
-   <a href="https://github.com/saanvijay/hyperledger-explorer-made-easy" class="external-link" rel="nofollow">hyperledger-explorer-made-easy</a>
project is a kind of utility tool for easy setup of Hyperledger
Explorer. After evaluating this tool and having consensus for
merging it into Explorer repo within the team, we might get it
included into Explorer as one of the official features.

# Additional Information

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   🔲
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






