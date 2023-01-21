---
layout: default
title: 2021 Q4 Hyperledger Besu
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q4 Hyperledger Besu

Created by Danno Ferrin, last modified by Angelo De Caro on Jan 20, 2022

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Besu remains a strong
project with a growing community network of contributors. This quarter
the team has focused on the Ethereum Mainnet "merge" update, library
refactoring, and Quorum and QBFT compatibility. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> ? - Yes
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? - Yes </span>

# Questions/Issues for the TSC

None

# Releases

-   21.10.0-RC1 - 4 Oct 2021
-   21.10.0-RC2 - 12 Oct 2021
-   21.10.0-RC3 - 15 Oct 2021
-   21.10.0-RC4 - 28 Oct 2021
-   21.10.0 - 1 Nov 2021
-   21.10.1 - 8 Nov 2021
-   21.10.2 - 15 Nov 2021
-   21.10.3 - 10 Dec 2021
-   21.10.4 - 16 Dec 2021
-   21.10.5 - 20 Dec 2021
-   22.1.0-RC1 - 16 Dec 2021

There were more releases this quarter than typical due to 4 separate
CVEs (one Besu related, three Log4J related).  The 21.10.x line will
remain "open" for security updates until 22.1.0 releases.

# Overall Activity in the Past Quarter

-   **EVM Library
**Work by Hedera Hashgraph has resulted into the separation of the
EVM code into a stand-alone library, used by both Hedera and
Hyperledger Besu.
-   **QBFT
**Interoperable with GoQuorum.
Validators can be managed via smart contracts - allowing operators
to quickly change validators if there is a problem (HA).
-   **Mainnet Merge Offsite
**Multiple Besu maintainers attended an offsite in Q4 with all the
major Ethereum Mainnet consensus and execution layer clients,
resulting in an initial proof of concept for the merge.
-   **Privacy code hardening
**Addressing tech debt in privacy code. Consolidation of naming
("onchain" privacy deprecated in favour of "flexible" privacy).
-   **EVM Performance
**Hedera has worked to roughly triple the throughput of the EVM.
-   **JWT Authentication
**Added support for additional (and stronger) authentication
algorithms (default was RSA).
-   **Logging and Developer experience improvements
**Improvements in response to community feedback. More work to do
here.

# Current Plans

-   **"The Merge" **Ethereum Mainnet expects to merge the current mainnet chain into
the Beacon chain in an event called "Docking" or "The Merge."  This
is expected to occur in the first half of 2022. Principal work is
mostly done and is expected to finish in Q1.
-   **Shanghai Fork**
The first fork after The Merge is expected to add some long overdue
EVM improvements, such as the Ethereum Object Format.
-   **Developer experience
**Planning to add a workstream to specifically focus on developer
experience, allowing prioritization of issues alongside feature
work.
-   **Tracing APIs
**Parity-style Tracing APIs, requested by Infura 

# Maintainer Diversity

Three maintainers were moved to emeritus status due to inactivity (David
Mechler, Edward Mack, and Trent Mohay).  Seven new maintainers were
added (Daniel Lehrner, Diego López León, Fabio Di Fabio, Frank Li, Jiri
Peinlich, Simon Dudley, Taccat Isid)

Maintainers are employed by the following organizations:

-   ConsenSys Quorum (FKA PegaSys)
-   ETC Cooperative
-   Hedera Hashgraph
-   Splunk 

The maintainers breakdown is:

-   20% not currently employed by ConsenSys (6 of 29) - This is a slight
improvement from prior quarters, however this includes two who have
not made contributions since leaving ConsenSys. This will drop to
14% if we do not retain their participation.

# Contributor Diversity

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fbesu/dashboard;subTab=technical?time=%7B%22from%22:%222021-09-22T06:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-12-22T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">LFX Analytics from 22  Sep to 22
Dec, 2021</a>

(report generated prior to close of 3 month window)

Commits from  2021-09-22 to 2021-12-22 : 309+

Committers from 2021-12-22 to 2021-12-22: 33  (9 non-ConsenSys)

Identified Orgs  2021-12-23 to 2021-12-21:  6

# Additional Information

None as of the due date for this report.

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
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 20-Dec-2021 </span>






