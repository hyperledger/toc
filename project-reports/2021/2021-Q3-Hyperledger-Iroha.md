---
layout: default
title: 2021 Q3 Hyperledger Iroha
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q3 Hyperledger Iroha

Created by Sara Garifullina, last modified by Arun S M on Nov 01, 2021

# Project Health

We are doing pretty well - both Iroha versions are being developed,
there is a status update on every community meeting. Community is happy
to welcome the contributions from the interns. New features are being
implemented and general community communication seems to be going well. 

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Last 2
library repos left. We do not have permissions to rename anything
there or change default branches. We will ask the LF support team to
do that instead.  </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented the Common Repository Structure in
all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?  </span>

# Questions/Issues for the TSC

We believe CRS was somehow implemented by the HL team, but maybe we are
wrong?  

# Releases

Last release (
<a href="https://github.com/hyperledger/iroha/releases/tag/1.2.1" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.2.1</a>
) was on March 19, currently we are already testing the new release th"at will include new features such as new DB. 

# Overall Activity in the Past Quarter

Chats are relatively active. With the internship projects and new
features being developed we are pretty active. Questions are being
answered. We are also working on a process of how questions about client
libraries will be replied as libraries require some more qualifications
but as of now everything is going smoothly. Community meetings keep
happening every 2 weeks. 

1.  RocksDB was integrated to store Iroha's state
2.  WSVChecker tool was implemented to check consistency of Iroha state
after migration from PosgresDB to RocksDB
3.  Tool that migrates database from Postgres backend to RocksDB backend
is being implemented
4.  Other minor improvements: further replacement of RXCPP with custom
Subscription engine, consensus optimizations, stability improvements

For Iroha2 overall we have been working hard on client libraries and
network stability:

1.  Multiple consensus fixes
2.  Actor framework integration
3.  Java client lib finished
4.  JS client lib finished
5.  iOS client lib nearly finished

# Current Plans

For Iroha 1 the plan is to release the version with a new DB option. We
are very close to it. We have every reason to plan finishing internships
successfully and have new Cactus integration and some other features. 

After that we will work on new features that will be part of the 1.3.1
release:

1.  Syncing node – back up node that does not participate in consensus,
but may process queries and propagate transactions
2.  Optimize storage – integrated key-value storage already speeds up
transaction processing, but we may further improve performance by introducing in-memory caches for the most frequently accessible data



For Iroha 2 - development is going forward, new features are being
implemented. Pre-release scope is defined and its date is in discussion.
Internship is progressing successfully.

The features currently in development and planned for near future:

1.  Python Client Library
2.  Triggers
3.  WASM Integration Prototyping
4.  Migration to custom p2p networking lib

# Maintainer Diversity

<a href="https://github.com/orgs/hyperledger/teams/iroha-maintainers/members" class="external-link" rel="nofollow">https://github.com/orgs/hyperledger/teams/iroha-maintainers/members</a>
 - for both Iroha 1 and Iroha 2 development teams. 

# Contributor Diversity

Contributors are represented by Soramitsu employees and also individual
contributors helping both with code and helping out in chats. 

# Additional Information

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-56722331"></span>
<p>Surely <a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> should be able
to help answer or get answers to the sysadmin questions.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at Aug
06, 2021 19:59 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-56723112"></span>
<p>done done done</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ryjones at Aug 12, 2021 14:07 </div ></td>
</tr>
</tbody>
</table>




