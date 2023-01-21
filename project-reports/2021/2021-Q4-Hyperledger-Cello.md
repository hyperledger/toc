---
layout: default
title: 2021 Q4 Hyperledger Cello
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Cello

Created by Baohua Yang, last modified by Artem Barger on Dec 16, 2021

# Project Health

<span style="color: rgb(23,43,77);">Overall health is OK with working on the coming v1.0 release.  </span>

<span style="color: rgb(23,43,77);">The project is following the plan to
for 1.0 release with new architecture. </span>

1.  <span style="color: rgb(51,51,51);">Continue with the new dashboard;</span>
2.  <span style="color: rgb(51,51,51);">Finish new agent design and
docker agent implementation; </span>
3.  <span style="color: rgb(51,51,51);">Continue the  <span style="color: rgb(23,43,77);text-decoration: none;">API Engine</span>; </span>
4.  <span style="color: rgb(51,51,51);">Finish two demos: creating
nodes, new cliSDK; </span>
5.  <span style="color: rgb(23,43,77);text-decoration: none;">The
internship project goes well with
<a href="https://wiki.hyperledger.org/display/~yuanmao" class="confluence-userlink user-mention" data-username="yuanmao" data-linked-resource-id="51612598" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Yuanmao Zhu</a> <span style="color: rgb(34,34,34);text-decoration: none;">.  </span></span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow" style="text-decoration: none;">Have you switched from
master to main in all your repos</a> </span> ? yes
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow" style="text-decoration: none;">Have
you implemented the Common Repository Structure in all your repos</a></span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span>
1.
<a href="https://github.com/hyperledger/cello/blob/main/LICENSE" class="external-link" rel="nofollow">LICENSE</a> - yes
2.   <a href="https://github.com/hyperledger/cello/blob/main/CODE_OF_CONDUCT.md" class="external-link" rel="nofollow">CODE_OF_CONDUCT.md</a>   -
yes
3.
<a href="https://github.com/hyperledger/cello/blob/main/SECURITY.md" class="external-link" rel="nofollow">SECURITY.md</a>   - yes
4.
<a href="https://github.com/hyperledger/cello/blob/main/README.md" class="external-link" rel="nofollow">README.md</a>   - yes
5.
<a href="https://github.com/hyperledger/cello/blob/main/MAINTAINERS.md" class="external-link" rel="nofollow">MAINTAINERS.md</a>   - yes
6.
<a href="https://github.com/hyperledger/cello/blob/main/CONTRIBUTING.md" class="external-link" rel="nofollow">CONTRIBUTING.md</a>   - yes
7.
<a href="https://github.com/hyperledger/cello/blob/main/CHANGELOG.md" class="external-link" rel="nofollow">CHANGELOG</a> - yes

# Issues

No.

# Releases

Still working on v1.0.0 (In plan at the end of Dec) with new features
of:

-   New distributed governing model and new architecture;
-   Support fabric  2.2 LTS.

# Overall Activity in the Past Quarter

This quarter, we mainly have been focusing on Development of API engine
and front end.

-   Completed the front end basic work;
-   Finish the new backend agent (based on Docker);
-   Continued development of API engine.
-   node APIs are done;
-   channel APIs are almost done;
-   chaincode APIs are on-going.
-   Two <a href="https://wiki.hyperledger.org/display/cello/2021-11-13" rel="nofollow">demos</a> are done on the backend API workflow, and
cli SDK.

# Current Plans

Next steps include:

-   Finish the remaining APIs in API server;
-   Finish the dashboard change.

<span style="font-size: 24.0px;letter-spacing: -0.01em;">Maintainer
Diversity </span>

Current there are 3 maintainers, and those active developers who
contribute to cello continuously (3 month) may be nominated as new
maintainers. 

-   Baohua Yang (Oracle)
-   Haitao Yue (YiJianTianShu Technology)
-   Qiang Xu (H3C)

# Contributor Diversity

<span style="color: rgb(51,51,51);">This quarter, we have <span style="color: rgb(23,43,77);text-decoration: none;"> a total of 20
commits from 3 contributors. </span> </span>

# Additional Information

Insights from Oct 1, 2021  to  <span style="color: rgb(23,43,77);text-decoration: none;"> Dec 6 2021 ,</span> <span style="letter-spacing: 0.0px;">can be found at  </span> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fcello/dashboard;subTab=technical?time=%7B%22from%22:%222021-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-12-06T08:00:00.000Z%22%7D" class="external-link" rel="nofollow">Cello stats for last quarter.</a>

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

<span class="placeholder-inline-tasks"> 06-Dec-2021 </span>




