---
layout: default
title: 2019 Q3 Hyperledger Transact
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Transact

Created by Mark Ford, last modified by Arnaud J Le Hors on Aug 29, 2019

## Project

Hyperledger Transact -
<a href="https://github.com/hyperledger/transact" class="external-link" rel="nofollow">https://github.com/hyperledger/transact</a>

# Project Health

Health is good. There is a surprising level of interest in the project;
we expected less interest as a library project, but are glad to the
interest is high, which is encouraging for library projects in general.
There are ongoing planning discussions about the path to support
Transact by the various projects, including Fabric, Sawtooth, and Grid.

## Issues

No issues currently.

## Releases

Since project creation, the project has had 6 releases. The current
release is 0.1.5. The releases are available on
<a href="http://crates.io" class="external-link" rel="nofollow">crates.io</a> : 

<a href="https://crates.io/crates/transact/versions" class="external-link" rel="nofollow">https://crates.io/crates/transact/versions</a>

## Overall Activity in the Past Quarter

Much of the activity in the past quarter has focused on project setup
and incremental improvements to the initial code base. The primary
method of discussion is RocketChat.

## Current Plans

Next steps include:

-   Add network transport support for smart contract engines (with
transaction processor compatibility)
-   Add Go SDK support (for smart contract engines and client
batch/transaction creation)
-   Expand Fabric integration details and support

## Maintainer Diversity

The maintainer diversity currently matches that of the initial project
sponsor companies.

There has been additional interest in contributing to the Go SDK, which
may lead to additional maintainers.

## Contributor Diversity

Similar to maintainer diversity, since active contributors are likely to
become maintainers at this early stage.

## Additional Information

None.

## Reviewed by
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Arnaud Le Hors </span> </span>
-   🔲 <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Binh Nguyen </span> </span>
-   ✅ <span style="color: rgb(0,0,0);">Christopher Ferris </span>
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span>
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Hart Montgomery </span> </span>
-   🔲 <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span>
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Mark Wagner </span> </span>
-   🔲 <span style="color: rgb(0,0,0);">Mic Bowman </span>
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span>
-   ✅ <span style="color: rgb(94,108,132);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-16326690"></span>
<p>I'm getting feedback that it is difficult to get engaged. I also have
been unable to find any documentation that really articulates more than
general technical detail of how it is intended to be integrated into
DLTs. Also, have not found the set of development items (JIRAs or GH
issues) that a n00b could start work on.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by ChristopherFerris at Aug 29, 2019 12:16 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-16326759"></span>
<p>I'm a bit surprised by the high number of releases. What is driving
this rate? I couldn't easily find release notes that would tell me wh"at each new release brings. Is that available somewhere?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Aug
29, 2019 14:08 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-16326763"></span>
<p>The projects using the Rust library "libtransact" as a component are
using the published versions off of crates.io, which requires that we do
releases. As a library project, we expect a higher rate of point
releases than the higher-order projects.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Aug 29, 2019 14:24 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-16326764"></span>
<p>A good path to get engaged is RocketChat #transact. Fleshing out JIRA
issues is a great idea.</p>
<p>The JIRA backlog, which we could flesh out some more, is here - <a href="https://jira.hyperledger.org/secure/RapidBoard.jspa?rapidView=232&amp;view=planning.nodetail&amp;quickFilter=621&amp;epics=visible" class="external-link" rel="nofollow">https://jira.hyperledger.org/secure/RapidBoard.jspa?rapidView=232&amp;view=planning.nodetail&amp;quickFilter=621&amp;epics=visible</a></p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by amundson at Aug 29, 2019 14:29 </div ></td>
</tr>
</tbody>
</table>




