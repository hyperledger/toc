---
layout: default
title: 2020 Q4 Hyperledger Transact
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Transact

Created by Andrea Gunderson, last modified by Gari Singh on Feb 05, 2021

# Project

Hyperledger Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a>

# Project Health

Health is good. Transact has been fully integrated into the Sawtooth
Validator, replacing the Python transaction execution platform.

# Questions/Issues for the TSC

No issues currently.

# Releases

Since project creation, the project has had 19 releases. The current
release is 0.3.6. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> :
<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow"><span>https://crates.io/crates/transact/versions</span></a>

# Overall Activity in the Past Quarter

Continued incremental improvements to the initial code base. Additional
activity shown below. The primary method of discussion continues to be
held in RocketChat.

-   Replaced the signing module in libtransact with cylinder
-   Updated to the Scheduler and Executor APIs to improve usage
-   Made various bug fixes and improvements

# Current Plans

Next steps include:

-   Stabilize SQLite database support
-   Add a next-generation smart contract API / simplified smart
contracts (cross-project with Sawtooth, in progress)
-   Add PostgreSQL database support
-   Further develop the Transact SDK for JavaScript

# Maintainer Diversity

The maintainer diversity currently matches that of the initial project
sponsor companies.

# Contributor Diversity

There were a total of 5 contributors in the last quarter, up from 3 last
quarter.

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
<td><span id="comment-41585939"></span>
<p>Re: "Replaced the  <span style="color: rgb(23,43,77);">signing module
in libtransact with cylinder </span>"</p>
<p>The initial project proposal lists that the Hyperledger Transact
[quote from the proposal] " <span>will include pluggable support (not
implementations) for signing and hashing, with built-in support for Ursa</span>". How is the abstraction supported for users of Transact to
choose between ursa and cylinder?</p>
<p>Ref:  <a href="https://docs.google.com/document/d/13d0cMReGOhK13BbdgMOFZy_prUzqWBXWc4nlI7mehpY/edit" class="external-link" rel="nofollow">https://docs.google.com/document/d/13d0cMReGOhK13BbdgMOFZy_prUzqWBXWc4nlI7mehpY/edit</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by arsulegai at Nov 16, 2020 09:42 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41585966"></span>
<p>Do you have any insights into the impact (positive or negative) on
the change in Sawtooth? I'm thinking of code size and performance in
particular.</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Nov
16, 2020 13:13 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41585967"></span>
<p>At the last TSC call we decided to request the project reports to
include relevant data from the LF Insights tool to make it easier to get
that information while reviewing reports (see <a href="https://wiki.hyperledger.org/display/TSC/Add+Insights+dashboard+reference+to+quarterly+reports">Add
Insights dashboard reference to quarterly reports</a> ). Although we're
still looking into some of the details on how this would best be
implemented, in the meantime, please add the following link to your
report (and from then on carry over the link with rolling dates so th"at it is scoped to the last 3 months):</p>
<p><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard?time=%7B%22from%22:%222020-08-12T22:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-11-11T23:00:00.000Z%22%7D" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ftransact/dashboard?time=%7B%22from%22:%222020-08-12T22:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-11-11T23:00:00.000Z%22%7D</a></p>
<p>Thanks.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Nov
16, 2020 13:28 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41585978"></span>
<p>From a code size perspective, this removes a lot of Python code from
Sawtooth (and Sawtooth 2 will be 100% Rust, so this is an important
step). From a performance perspective – we don't have performance data
yet, as we are going to do performance testing/analysis of Sawtooth
after the rest of the python is removed. We believe Transact is
significantly faster but there are a lot of other factors which impact
Sawtooth's performance as well, so we will need to collect the data and
iterate on the hot spots.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Nov 16, 2020 15:08 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41585979"></span>
<p>This abstraction is now delegated to cylinder, but otherwise it
remains true.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Nov 16, 2020 15:11 </div ></td>
</tr>
</tbody>
</table>




