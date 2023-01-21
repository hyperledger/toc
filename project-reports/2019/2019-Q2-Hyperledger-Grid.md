---
layout: default
title: 2019 Q2 Hyperledger Grid
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q2 Hyperledger Grid

Created by Andrea Gunderson, last modified by Mark Wagner on May 22, 2019

# Project

Hyperlegder Grid 
<a href="https://grid.hyperledger.org/" class="external-link" rel="nofollow">https://grid.hyperledger.org/</a>

# Project Health

Health is good.  Sponsors along with new contributors have begun design
work including collaborating on the initial RFCs.  Monthly contributor
calls have generated further interest.   <span style="color: black;">Several contributors have agreed to collaborate on
Grid design and implementation via agile sprints leveraging the
community tools provided by Hyperledger. </span>

# Issues

<span style="color: black;">The contributors are currently working on
defining cross-company sprint planning activities. As part of this, the
team needs to decide whether to use JIRA or Github Issues. This
discussion is on-going. Community input is welcome on \#grid. </span>

# Releases

No prior releases.

# Overall Activity in the Past Quarter

Chat on Rockchat and pull request engagement is increasing as more
information about Grid is becoming available. The mailing list is
underutilized.

See community calendar <a href="https://wiki.hyperledger.org/community/calendar-public-meetings" rel="nofollow">https://wiki.hyperledger.org/community/calendar-public-meetings</a>
for occurrences of our Grid Contributors Meeting.

The project is very active. Some highlights:

-   Track and Trace demo application has been fully integrated into
Grid.
-   Pike integration is in-progress but mostly complete.
-   Architectural components such as the Grid daemon and Grid SDK have
been added to the project.
-   Discussions on future direction and features have occurred
throughout the quarter and continue to increase.
-   There are several in-progress RFCs related to current and future
direction of features.

# Current Plans

Specific plans include:

-   Implement GS1 Product / Product Catalog framework
-   Complete Pike implementation into Grid
-   Complete migration of Track and Trace demo app to Rust 
-   Integrate Track and Trace demo app into Pike
-   Finish implementation of Grid Schema

# Maintainer Diversity

The Grid maintainers are currently:



Andi Gunderson

Anne Chenette

Boyd Johnson

Dan Middleton

Darian Plumb

Dave Cecchi

James Mitchell

Peter Schwarz

Ryan Banks

Ryan Beck-Buysse

Shawn Amundson



We anticipate adding additional maintainers as contributions increase in
areas currently in development.

# Contributor Diversity

<span style="color: black;">In addition to the initial sponsoring
organizations (Cargill, Intel, Bitwise IO), two additional organizations
have begun contributing to Grid this quarter: Target and GS1. In total,
there are 14 active contributors to Grid across five active
organizations. </span>

# Additional Information

<span style="color: black;">Hyperledger Grid was discussed in the ProM"at conference keynote session.  </span>

<span style="color: black;">Several times in the past quarter,
Hyperledger Grid's contributors have received positive feedback from the
extended Enterprise/Business community on the project's name. </span>

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span> </span></span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner </span> </span> </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span> </span></span> </span> </span> </span> </span>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-9110900"></span>
<p>When we approved Grid, it was made clear to the TSC members that it
was not an application/solution, but rather components that could be
used in one. This report sure makes it sound like it is a solution. Am I
reading this incorrectly?</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by ChristopherFerris at May 02, 2019 14:03 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-12419080"></span>
<p>I don't see anything that wasn't in the proposal.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at May 09, 2019 04:39 </div ></td>
</tr>
</tbody>
</table>




