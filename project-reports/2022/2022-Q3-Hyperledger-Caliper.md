---
layout: default
title: 2022 Q3 Hyperledger Caliper
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Caliper

Created by Dave Kelsey, last modified by Jim Zhang on Nov 03, 2022

<span style="letter-spacing: 0.0px;"> </span>

# Project Health

-   3 maintainers
-   PRs continuously submitted and merged
-   2 Mentorship projects accepted and currently in progress
-   Questions on Discord and on Github regularly answered
-   Switched to monthly contributor calls (discussion happens mostly on
Discord as needed)

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? → Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? → Yes </span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? You can
optionally
<a href="https://github.com/petermetz/gh-action-dci-lint#usage" class="external-link" rel="nofollow">use the DCI Lint tool</a> to
make this a recurring action on your repo. → Yes (only remnants in
the changelog and third-party configurations/references) </span></span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? → Yes ( <a href="https://hyperledger.github.io/caliper/vNext/contributing/#inclusive-language-guidelines" class="external-link" rel="nofollow">https://hyperledger.github.io/caliper/vNext/contributing/#inclusive-language-guidelines</a>
)</span> </span>

# Questions/Issues for the TSC

Not at this time.

# Releases

v0.5.0 (at 2022.05.19.), plus continuous publishing of unstable releases
after every merged PR:

-   npm: 
<a href="https://www.npmjs.com/package/@hyperledger/caliper-cli/v/0.5.0" class="external-link" rel="nofollow">https://www.npmjs.com/package/@hyperledger/caliper-cli/v/0.5.0</a>
-   DockerHub:  <a href="https://hub.docker.com/layers/caliper/hyperledger/caliper/0.5.0/images/sha256-3a7df18ef6a17a8c851dac19241049be2375dc892643c576932f360ca9d7198c?context=explore" class="external-link" rel="nofollow">https://hub.docker.com/layers/caliper/hyperledger/caliper/0.5.0/images/sha256-3a7df18ef6a17a8c851dac19241049be2375dc892643c576932f360ca9d7198c?context=explore</a>

# Overall Activity in the Past Quarter

List of merged PRs (16):  <a href="https://github.com/hyperledger/caliper/pulls?q=is%3Apr+merged%3A2022-06-28..2022-09-22+" class="external-link" rel="nofollow">https://github.com/hyperledger/caliper/pulls?q=is%3Apr+merged%3A2022-06-28..2022-09-22+</a>

Summary of activities:

-   Optimise github action pipelines (caliper and caliper-benchmarks) to
improve time to verify and merge and also substantially reduce
resources used and thus reduce overall power consumption
-   Improve github action pipelines: code coverage reports
-   Increase robustness of Prometheus integration
-   vscode extension (Attila to provide more detail)
-   Other bug and documentation fixes

# Current Plans

-   Efforts will be focused mainly on the proper execution of mentorship
projects.
-   Overview and decrease the issue backlog.
-   Preliminary design of architectural changes (as part of striving
towards v1)

# Maintainer Diversity

<a href="https://github.com/hyperledger/caliper/blob/f1634b511f782b3ee74829972402adcbff806eaa/MAINTAINERS.md" class="external-link" rel="nofollow">Current maintainers</a>

# Contributor Diversity

<span style="color: rgb(23,43,77);">Contributions from maintainers,</span>Francesco Vlacancich, and current project mentees Eravatee Raje
and Rinish Sam.

# Additional Information

N.A.

# Reviewed By

-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>  </span>
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

<span class="placeholder-inline-tasks"> 22-Sep-2022 </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71701528"></span>
<p><a href="https://wiki.hyperledger.org/display/~davidkel" class="confluence-userlink user-mention" data-username="davidkel" data-linked-resource-id="16327281" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dave Kelsey</a> – If the
Caliper team is interested in finding more contributors to help out with
the project, we're happy to support you with that.  There are a lot of
ways we can share with the community about what Caliper is and how
people can get involved.  When we've done this for other projects and
labs it does bring more people into the those community channels.  For
reference, I reviewed the meetups we've done and just see one meetup in
the last three years that had information about Caliper in it so I think
we're in a situation where many people who might be interested in this
project just haven't heard about it.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by davidwboswell
at Sep 22, 2022 17:26 </div ></td>
</tr>
</tbody>
</table>




