---
layout: default
title: 2022 Q4 Hyperledger Cacti
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q4 Hyperledger Cacti

Created by Takuma Takeuchi, last modified by Danno Ferrin on Nov 04, 2022

# Project Health

-   Cactus and Weaver were merged to one project "Cacti." Now we are
preparing for moving codes and making the new Cacti repository.
-   On the original Cactus repository, we released Cactus v1.1.0 th"at resolved the issues from the comprehensive security audit of Cactus
v1.
-   Cacti new architecture diagram is now discussed among the
maintainers and this will be determined soon.

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
make this a recurring action on your repo. **Yes, we use DCI-Lint as
part of our CI**</span> </span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages?  **Yes**</span> </span>

# Questions/Issues for the TSC

-   None at the moment.

# Releases

-   v1.1.0 =&gt;
<a href="https://github.com/hyperledger/cactus/tree/v1.1.0" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/tree/v1.1.0</a>

# Overall Activity in the Past Quarter

1.  We achieved the project merging of Cactus and Weaver. We are
preparing the initial repository including Cactus and Weaver codes.
2.  We aim to bring as much Hyperledger interoperability work efforts
together as possible to make the total output greater than the
individual sums (code reuse enablement, shared testing
infrastructure expertise, benchmarks, release management, etc.)
3.  The plan is to leverage our mono-repo project structure in order to
make the above plans as painless/as low overhead as possible since
we want to actively prevent bogging down everybody involved with
administrative changes/refactorings/breaking changes required in the
name of collaboration
4.  We continue to put effort into academic research (namely a research
group within Hyperledger; several Hyperledger Summer Internships
with a research component have been proposed and accepted).

# Current Plans

1.  The maintainers are planning the Cacti new architecture that is
combined with the strengths of Cactus and Weaver. They will
determine the Cacti v2 release plan and largely refactor the codes
as the architecture.

2.  They are also planning about some supporting tools such as ledger
explorer interface of Cacti.

# Maintainer Diversity

-   As is required, you can find our current maintainer list here:  
<a href="https://github.com/hyperledger/cactus/blob/main/MAINTAINERS.md" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/blob/main/MAINTAINERS.md</a>
.

<!-- -->

-   Our existing maintainers are:
-   Jagpreet Singh Sasan (Accenture) \*  from the original Cactus
-   Jonathan Hamilton (Accenture) \*  from the original Cactus
-   Peter Somogyvari (Accenture) \* from the original Cactus
-   Izuru Sato (Fujitsu) \* from the original Cactus
-   Takuma Takeuchi (Fujitsu) \* from the original Cactus
-   Sandeep Nishad (IBM) \* from Weaver
-   Venkatraman Ramakrishna (IBM) \* from Weaver

<!-- -->

-   Note that Sandeep and Venkatraman from the Weaver project were
officially welcomed to Cacti maintainers in the last quarter
(September).

# Contributor Diversity

-   <a href="https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard" class="external-link" rel="nofollow">https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard</a>
Our contributor strength has increased in this quarter compared to
the previous quarter, which is great news!

# Additional Information

-   N/A

# Reviewed By

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
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




