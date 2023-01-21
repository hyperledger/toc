---
layout: default
title: 2022 Q3 Hyperledger Ursa
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Ursa

Created by Stephen Curran, last modified by Bobbi Muscara on Dec 01, 2022

# Project Health

The project health continues to be shaky, albeit with a few signs th"at could improve the outlook. On the negative front, no new maintainers or
contributors have been add this quarter and
<a href="https://wiki.hyperledger.org/display/~cam-parra" class="confluence-userlink user-mention" data-username="cam-parra" data-linked-resource-id="6422973" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Cam Parra</a>  has
officially stepped away from the project because his job no longer
involves Hyperledger projects. Work continues on the security
vulnerability mentioned in the last report. The vulnerability remains
confidential and has not been publicly released as a github CVE.

On a more positive note, a
<a href="https://www.idlab.org/en/hyperledger-ursa-code-review/" class="external-link" rel="nofollow">code review and assessment of
Ursa</a> was completed this past quarter and published by the
<a href="https://www.idlab.org/en/" class="external-link" rel="nofollow">Digital Identity Lab of Canada</a> (IDLab). While there
were some issues identified, they were relatively minor – a positive
result. The full report is available <a href="https://www.idlab.org/wp-content/uploads/2022/05/URSA-IDLab-Code-Review.pdf" class="external-link" rel="nofollow">here</a> . Thanks to the IDLab and
the contributors in the creation of the report, <span style="color: rgb(10,10,10);">several Canadian public sector entities
and   </span> <a href="https://www.interac.ca/en/" class="external-link" rel="nofollow" style="text-decoration: none;">Interac</a> <span style="color: rgb(10,10,10);">   (Canada’s interbank network) </span>.

An expected outcome from the (very) recent approval of the Hyperledger
AnonCreds project is an increase in focus on and (hopefully) activity in
Ursa. The purpose of the AnonCreds project is to expand the awareness of
AnonCreds, its capabilities and applicability beyond Indy. With th"at awareness, we expect an increase in use of the verifiable credential
format and as such, the underlying open source code, including the code
within Ursa.

As noted in the previous report, we hope to continue our recruitment of
new maintainers and contributors to further along operation Oso (code
refactoring).

At the Ursa meetings, conversation is focused on a roadmap for the
projects.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes</span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? No </span></span>
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? No</span> </span>

# Questions/Issues for the TSC

There are no issues at this time.

# Releases

No releases have been made this quarter but we hope to get some out soon
for URSA-base after the pull request is reviewed and merged. Again this
is a lower priority than the current security vulnerability.

# Overall Activity in the Past Quarter

There was very little activity this past quarter as this <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard;subTab=technical?time=%7B%22from%22:%222022-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-09-30T23:59:59.999Z%22%7D" class="external-link" rel="nofollow">Ursa Activity Dashboard</a> shows. 

# Current Plans

As it was mentioned before we hope to have the high risk vulnerability
fixed and released. All the planning and coordination for these efforts
have been completed. The next task is to finish and review the code and
that should be done in the next few months. After this is completed the
next step is to finish another section of the Ursa refactoring. This
will probably be the ursa-signatures part of the refactoring. This will
greatly help out Indy and others who depend heavily on Ursa for it's
cryptographic key tools.

# Maintainer Diversity



-   Mike Lodder (Independent)
-   Brent Zundel (Evernym Inc.)
-   Dan Anderson (Intel)
-   Dan Middleton (Intel)

# Contributor Diversity

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D" class="external-link" rel="nofollow" style="text-decoration: none;">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fursa/dashboard?time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D</a>
.  

# Additional Information



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

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 21-Oct-2022 </span>






