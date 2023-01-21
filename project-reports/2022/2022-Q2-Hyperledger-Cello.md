---
layout: default
title: 2022 Q2 Hyperledger Cello
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q2 Hyperledger Cello

Created by Baohua Yang, last modified by Peter Somogyvari on Aug 09, 2022

<span style="letter-spacing: 0.0px;"> </span>

# Project Health

<span style="color: rgb(23,43,77);">Overall health is OK with working on
the coming v1.0 release.  v1.0.0-alpha2 is released on May 30, 2022.
v1.0.0-beta is planed this quarter. </span>

<span style="color: rgb(23,43,77);">The 1.0 release is with new
architecture. </span>

1.  <span style="color: rgb(51,51,51);">The new dashboard is almost
done; </span>
2.  <span style="color: rgb(51,51,51);">New agent design and docker
agent implementation are done; </span>
3.  <span style="color: rgb(51,51,51);">Continue the  <span style="color: rgb(23,43,77);text-decoration: none;">API Engine</span>; </span>

<span style="color: rgb(23,43,77);text-decoration: none;">On the other
hand, the internship project attracts 100+ applicants, and
review/selection is done with lots of work. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? **Yes**
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? **Yes**</span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. **Yes**</span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages?  **Yes, we have a PR open for
adding the statement to our main
<a href="http://README.md" class="external-link" rel="nofollow">README.md</a> file: 
<a href="https://github.com/hyperledger/cello/pull/450" class="external-link" rel="nofollow">https://github.com/hyperledger/cello/pull/450</a>**</span> </span>

# Issues

No.

# Releases

<span style="color: rgb(23,43,77);">v1.0.0-alpha2 is done in May, 2022.</span>

<span style="color: rgb(23,43,77);">Plan a v1.0.0-beta release this
quarter. </span>

# Overall Activity in the Past Quarter

This quarter, we mainly have been focusing on the implementation of API
engine and front end.

-   Completed the front end basic work on the deployment operations;
-   Finish the new backend agent (based on Docker);
-   Finish the cli SDK for dashboard usage.
-   Continued development of API engine.
-   node APIs are done;
-   channel APIs are almost done;
-   chaincode APIs are on-going.

# Current Plans

Next steps include:

-   Finish the v1.0.0-beta release in the 2nd quarter of 2022.

<span style="font-size: 24.0px;letter-spacing: -0.01em;">Maintainer
Diversity </span>

Current there are 3 maintainers, and those active developers who
contribute to cello continuously (3 month) may be nominated as new
maintainers. 

1 maintainer (Qiang Xu) is retired this quarter and a new one is
nominated (Yuanmao Zhu).

-   Baohua Yang (Oracle)
-   Yang Feng (H3C)
-   Yuanmao Zhu (Coinbase)

# Contributor Diversity

<span style="color: rgb(51,51,51);">This quarter, we have <span style="color: rgb(23,43,77);text-decoration: none;"> a total of 22
commits from 3 contributors. </span> </span>

# Additional Information

Insights from  <span style="color: rgb(23,43,77);text-decoration: none;"> Feb 26 2022 to May
31 2022 , </span> <span style="letter-spacing: 0.0px;">can be found at </span> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fcello/dashboard;subTab=technical?time=%7B%22from%22:%222022-02-27T08:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-05-31T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Cello stats for last quarter.</a>

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
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

<span class="placeholder-inline-tasks"> 31-May-2022 </span>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-62254631"></span>
<p>Hi,  <a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> : It looks
like you are using an old template of the project report. There are two
additional questions in the required information:</p>
<ol class="incremental">
<li><span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to make
this a recurring action on your repo. </span> </span>
<ol class="incremental">
<li>master → main</li>
<li>slave → replicas</li>
<li>blacklist → denylist</li>
<li>whitelist → allowlist</li>
</ol></li>
<li><span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages?<br /></span> </span></li>
</ol>
<p><span style="color: rgb(23,43,77);text-decoration: none;">Also, Hart
is no longer required to review the project reports. Can you please let
us know the answers to the above questions. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at May
31, 2022 16:56 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62254639"></span>
<p>Update the content, and add the inclusive language statement at  <a href="https://github.com/hyperledger/cello/pull/450" class="external-link" rel="nofollow">https://github.com/hyperledger/cello/pull/450</a> .</p>
<p>Thanks!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at May
31, 2022 18:26 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-62254930"></span>
<p>hi  <a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a> , I assume
enhancing the docs is part of the release 1.0 activities? It looks like
the published version of the docs hasn't moved much, would highly
encourage the team to work on making the docs more filled in so new
comers and potential contributors can get started.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jimthematrix
at Jun 02, 2022 15:26 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-62255105"></span>
<p>Nice suggestion, will bridge the message with the team!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at Jun
02, 2022 22:33 </div ></td>
</tr>
</tbody>
</table>




