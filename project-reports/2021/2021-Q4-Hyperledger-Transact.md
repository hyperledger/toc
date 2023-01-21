---
layout: default
title: 2021 Q4 Hyperledger Transact
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Transact

Created by Andrea Gunderson, last modified by Artem Barger on Dec 16, 2021

<span style="font-size: 24.0px;letter-spacing: 0.0px;"> Hyperledger
Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a></span>

# Project Health

Health is good. In the last quarter there were 8 releases (including a
0.4 release), a new maintainer, and a lot of new features completed.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span>
1.  LICENSE - yes
2.   <a href="http://CODE_OF_CONDUCT.md" class="external-link" rel="nofollow">CODE_OF_CONDUCT.md</a> - no
3.   <a href="http://SECURITY.md" class="external-link" rel="nofollow">SECURITY.md</a> - yes
4.   <a href="http://README.md" class="external-link" rel="nofollow">README.md</a> - yes
5.   <a href="http://MAINTAINERS.md" class="external-link" rel="nofollow">MAINTAINERS.md</a> - yes
6.   <a href="http://CONTRIBUTING.md" class="external-link" rel="nofollow">CONTRIBUTING.md</a> - yes
7.  CHANGELOG - yes, but called
<a href="http://RELEASE_NOTES.md" class="external-link" rel="nofollow">RELEASE_NOTES.md</a>

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 28 releases. The current
release is 0.4.1. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> :
<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow"><span>https://crates.io/crates/transact/versions</span></a>

# Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion continues to be
held in RocketChat .

-   Completed and stabilized support of SQLite and Postgres merkle-radix
tree.
-   Stabilized \`transact workload\` command for performance and
stability testing. 

# Current Plans

Next steps include:

-   Move Sawtooth Sabre (wasm engine) into Transact
-   Reorganization of the project's crate structure
-   Setup a documentation site to help explain/advocate the project

Future:

-   Add a next-generation smart contract API / simplified smart
contracts (cross-project with Sawtooth, in progress)
-   Further develop the Transact SDK for JavaScript

# Maintainer Diversity

Over the last quarter, Isabel Tomb was added as a new Maintainer and
Eloá Franca Verona was retired.

# Contributor Diversity

There were a total of 6 contributors in the last quarter.

# Additional Information

Insights from  August 25 2021 to November 25 2021

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222021-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-11-25T06:00:00.000Z%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard;subTab=technical?time=%7B%22from%22:%222021-08-25T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-11-25T06:00:00.000Z%22%7D</a>

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

<span class="placeholder-inline-tasks"> 01-Dec-2021 </span>






