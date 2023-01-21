---
layout: default
title: 2021 Q2 Hyperledger Iroha
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Iroha

Created by Sara Garifullina, last modified by Gari Singh on May 26, 2021

# Project Health

Everything is going ok: there are 2 lines of development - of Iroha v1
(on C++, production ready) and Iroha v2 (in Rust, in development). There
are internship projects for both of them.  Work is being done, updates
are provided to the community every 2 weeks on the community meetings
from both lines of development.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Switched in
the main repository, others (library repositories) are not yet</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? We believe
that  <a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> added it
to the repos. </span>

# Questions/Issues for the TSC

While moving to main branch we've realised that we have DCO issues th"at were not reported by the DCO tool before. Also, from where does the DCO
tool gets what it expects in the sign-off?

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.2.1" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.2.1</a>

# Overall Activity in the Past Quarter

In general, communication is going smoothly, we try to answer questions
that come to the chat and also hold our bi-weekly meetings
synchronously. 

Regarding some more technical developments:

Iroha v1:

-   Performance degradation fix
-   Stability fixes that handle cases when other nodes are not
accessible or have slow connection
-   Performance metrics endpoint using prometheus (currently in
support/1.2.x branch)
-   Replacement RxCPP dependency with custom subscription engine for
more predictable thread management (currently in test and review)
-   Key-Value storage (currently under review)

Iroha v2: 

-   Introduced lockfree data structures
-   Introduced Grantable permissions
-   Added Roles
-   Deployed longevity stand
-   Increased significantly linting strictness
-   Covered several DOS attack vectors
-   Improved error reporting
-   Introduced transaction, block and message versioning support
-   Added pagination for queries

# Current Plans

Iroha 1:

-   Introduce UDP-based peer-to-peer gossiping to boost networking
-   Improve ordering service and consensus to improve performance

Iroha 2:

-   Record telemetry and display it as a web app
-   Prometheus endpoint
-   Researching possibility of migrating async runtime to Tokio
-   Researching Triggers for our smart contract language
-   Implement autogeneration of client libs data model

# Maintainer Diversity

Our contributor <a href="https://wiki.hyperledger.org/display/~baziorek" class="confluence-userlink user-mention" data-username="baziorek" data-linked-resource-id="31203253" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grzegorz Bazior</a>
(Grzegorz) is now a maintainer and already helped us a lot by helping
others in the chat, adding new functionality to Python library and by mentoring one of the internship projects. 

Another addition to the team is Ivan Kuvaldin who developed the metrics
feature. 

# Contributor Diversity

Core team still consists of Soramitsu team as well as contributors from
other companies, such as Grzegorz and Sonoko Mizuki.

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-51611266"></span>
<p>Could you please provide a bit more info on the DCO check failure?
Was the sign-off totally missing, badly formed, or something else?</p>
<p><a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> can tell
exactly how the check works but as far as I know it's merely a check on
the commit log based on a regular expression.</p>
<p>Thanks.</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by lehors at May
12, 2021 08:35 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-51611268"></span>
<p>the check just looks to see if there is an SoB line. Plus, some
people have over-ridden it.</p>
<p><br />
</p>
<blockquote>
<p><span class="s1">commit b4d1fc8a3a28818efd467fa4e3f8a80f18d4d016</span></p>
<p><span class="s1">Author: kamilsa &lt;kamilsa16@ <a href="http://gmail.com" class="external-link" rel="nofollow">gmail.com</a> &gt; </span></p>
<p><span class="s1">Date:   Fri Mar 26 10:16:28 2021 +0300 </span></p>
<p><br />
</p>
<p><span class="s1">    Missing docs from master (#892) </span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    * Add peer documentation </span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    Signed-off-by: Sara &lt;lira.lemur@ <a href="http://gmail.com" class="external-link" rel="nofollow">gmail.com</a> &gt; </span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    * issue template fix </span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    Signed-off-by: Sara &lt;lira.lemur@ <a href="http://gmail.com" class="external-link" rel="nofollow">gmail.com</a> &gt; </span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    * fix in documentation </span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    Signed-off-by: Sara G &lt;sara@Sara.dell&gt;</span></p>
<p><span class="s1">     </span></p>
<p><span class="s1">    Co-authored-by: Sara &lt;lira.lemur@ <a href="http://gmail.com" class="external-link" rel="nofollow">gmail.com</a> &gt; </span></p>
<p><span class="s1">    Co-authored-by: Sara G &lt;sara@Sara.dell&gt;</span></p>
</blockquote>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ryjones at May 12, 2021 08:45 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-51611386"></span>
<p>We had this issue with some commits, where there was a sign-off but
with other credentials of the same people, so to make it work we had to
rebase it. It was something like this:</p>
<p>Expected "kuvaldini j***@ukr.net", but got "Ivan Kuvaldin
k***@soramitsu.co.jp</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at May
13, 2021 09:36 </div ></td>
</tr>
</tbody>
</table>




