---
layout: default
title: 2021 Q4 Hyperledger Iroha
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Iroha

Created by Sara Garifullina, last modified by Angelo De Caro on Dec 09, 2021

# Project Health

Everything is on track - Iroha 1 keeps maintained. Bugs are fixe, some
smaller new features and refactoring are done. Iroha 2 is in very active
development with a big team. Together with the Hyperledger Team we
shared a survey that should help make good design decisions on certain
features. 

Community is doing good, internships are done - just some small issues
need to be fixed for releases. 

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes.</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes? </span>

# Questions/Issues for the TSC

No questions for now. 

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.3.0-rc.1" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.3.0-rc.1</a>
 - Pre-release, need to have some small fixes done, such as tests. Also,
Iroha Libraries releases are planned soon.

# Overall Activity in the Past Quarter

Communications are on track - questions are answered; there are plans
for discussing plans for Iroha with active community members. Questions
are replied (thanks to our community for a lot of help there!). About
the technical accomplishments, here they are: 

## v1

Worked on fixing small issues and improved stability of Iroha for
releasing it:

1.  Improved crash tolerance of the nodes; 
2.  Fixed memory issues;
3.  Run sequence of high-load tests with different network
configurations. 

## v2

1.  Core maintainers team expanded
2.  All client libraries finished - now they will be periodically
updated
3.  Introduced p2p library to increase performance
4.  Improved transaction gossiping
5.  Introduced metadata to entities in WSV
6.  Introduced Query Permissions

# Current Plans

## v1

1.  Special Iroha mode: synchronising the nodes without taking part in
consensus
2.  Improve processes for Multi-signature transactions and ordering
service
3.  Customise cache for RocksDB

## v2

### Near Future

1.  Actively preparing for the pre-release
2.  Longevity stand
3.  Stress testing

### General Plans

1.  On chain Triggers functionality
2.  Transaction fees
3.  Staking for Sumeragi consensus

# Maintainer Diversity

Most of the new people joined the Iroha 2 team: 

Marin Versic (@mversic), Sato (@ <span style="color: rgb(87,96,106);">s8sato </span>), Aleksander Petrosyan (@
<span style="color: rgb(87,96,106);">appetrosyan) - all joined Soramitsu
but represent a diverse international developers from all around the
world.  </span>

# Contributor Diversity

We are happy to be working closely the last quarter with 
<a href="https://wiki.hyperledger.org/display/~baziorek" class="confluence-userlink user-mention" data-username="baziorek" data-linked-resource-id="31203253" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grzegorz Bazior</a>   and
his team. Hopefully, we'll continue working on Iroha together.  

# Additional Information

# Reviewed By

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 08-Nov-2021 </span>






