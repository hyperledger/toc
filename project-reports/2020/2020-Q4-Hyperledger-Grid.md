---
layout: default
title: 2020 Q4 Hyperledger Grid
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Grid

Created by Andrea Gunderson, last modified by Gari Singh on Feb 05, 2021

# Project

Hyperledger Grid: <a href="https://www.hyperledger.org/projects/grid" class="external-link" rel="nofollow">https://www.hyperledger.org/projects/grid</a>

# Project Health

Health is good. Focus and discussion is currently around preparing Grid
for its initial release, an integration component meant to interface
with external systems, and designing a default schema for GS1 products.

# Questions/Issues for the TSC

-   There are no specific issues at the moment.

# Releases

-   No prior releases.

# Overall Activity in the Past Quarter

The Location smart contract was completed and its functionality can be
accessed via the CLI and REST API, and the Location RFC was approved.
Initial work has started on an integration component meant to interface
with external ERP systems. 

The Grid SDK was refactored to adopt more modular patterns. Database
functionality was split into modules for each individual Grid feature,
each supporting PostgreSQL and SQLite database backends. Error handling
in the SDK was also revamped to be more consistent between modules.
Finally, various bug fixes and enhancements for the CLI and REST API
were completed to prepare Grid for it’s initial release.

Documentation was added to the Grid website that adds content regarding
running Grid on Sawtooth. This includes documentation on setting up an
environment and using Grid features. Additionally, database schema
reference information is now available on the website.

The main source of asynchronous engagement is still the Hyperledger Ch"at <a href="https://chat.hyperledger.org/channel/grid" class="external-link" rel="nofollow"><span>#grid channel </span></a> and
RFC PRs. Grid community meetings continue, with a schedule of one every
4 weeks.

# Current Plans

Preparing for the initial 0.1 release

Designing and implementing an integration component for external systems

Purchase order RFC

# Maintainer Diversity

Davey Newhall was added as a maintainer of the Grid and Grid Website
repositories. There are 19 maintainers across the different repos.

We anticipate adding additional maintainers as contributions increase
for areas currently in development.

# Contributor Diversity

Contributor diversity remains steady with previous quarters, with some
share of the project's overall diversity coming from non-developer
participation in their areas of expertise.

Sponsoring organizations that are actively contributing to Grid include
Cargill, Target, GS1, and Bitwise IO. Additional contributions come from
individual contributors.

# Additional Information

Insights from September 3rd to December 3rd 2020

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard?time=%7B%22from%22:%222020-09-03T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-03T06:00:00.000Z%22%7D" class="external-link" rel="nofollow"><span>https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fgrid/dashboard?time=%7B%22from%22:%222020-09-03T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-03T06:00:00.000Z%22%7D</span></a>

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
-   ✅ <span class="placeholder-inline-tasks">
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
<td><span id="comment-41587541"></span>
<p><a href="https://wiki.hyperledger.org/display/~agunde" class="confluence-userlink user-mention" data-username="agunde" data-linked-resource-id="5505201" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Andrea Gunderson</a>   :
Are there thoughts about moving this project to Active from Incubation?
Or promotion for the 1.0 release? Or am I reading too much into "initial
release"?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Dec
02, 2020 22:06 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41587542"></span>
<p>The initial release is 0.1 – not 1.0. There will be many 0.x releases
before we consider a 1.0 release. No promotion expected for this
release, though maybe we should consider a blog post.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Dec 02, 2020 22:24 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41587696"></span>
<p>You should definitely do a blog post!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Dec
03, 2020 23:32 </div ></td>
</tr>
</tbody>
</table>




