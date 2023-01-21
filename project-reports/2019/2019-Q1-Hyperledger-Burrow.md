---
layout: default
title: 2019 Q1 Hyperledger Burrow
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q1 Hyperledger Burrow

Created by Sean Young, last modified by Silas Davis on Feb 21, 2019

# Project Health

<span style="color: rgb(51,51,51);">Project health is largely the same
as in previous update. We have added some unique features around dump
and restore (our chain reset mechanism) and we have a number of casual
contributors. We still lack maintainer diversity outside of Monax. There
is a steady flow of interest and we are pushing plenty of code relating
to our continued heavy use of Burrow. </span>

# Issues

<span style="color: rgb(51,51,51);">The biggest areas of help would be
with tooling and documentation.  </span>

# Releases

-   v0.23.3: Emergency bug fix

-   v0.23.2: Fixed issue with checkpointing whereby RWTree would load
its readTree from one version lower than it should.

# Overall Activity in the Past Quarter

Vent has been merged into burrow. Vent  <span style="color: rgb(51,51,51);">dynamically creates SQL database tables
from EVM events according to some specification files maintaining its
offset in the chain as it goes. In addition, we can dump the chain state
using a new dump tool. This state can then be provided as an initial
state for a new chain. This allows us to make backwards incompatibility
changes. Several backwards incompatible changes will be needed for
supporting new features like the proposal mechanism. The proposal
mechanism has received further fixes to make it production ready.</span>

# Current Plans

Create Q1 2019 Burrow Roadmap.

<table class="wrapped confluenceTable">
<tbody>
<tr class="header">
<th class="confluenceTh">Work item</th>
<th class="confluenceTh">Effort (1, 2, 3, 5, 8, 13)</th>
<th class="confluenceTh">Priority</th>
</tr>

<tr class="odd">
<td class="confluenceTd">NameReg extension to support authenticated
namespaces (including design)</td>
<td class="confluenceTd">13</td>
<td class="confluenceTd">Medium</td>
</tr>
<tr class="even">
<td class="confluenceTd">Burrow-side ABI registry mechanism (probably
based on above)</td>
<td class="confluenceTd">8</td>
<td class="confluenceTd">Low</td>
</tr>
<tr class="odd">
<td class="confluenceTd">Prototype 'new train'  <a href="https://github.com/go-interpreter/wagon" class="external-link" rel="nofollow" title="https://github.com/go-interpreter/wagon">WASM
execution</a></td>
<td class="confluenceTd">13</td>
<td class="confluenceTd">Low</td>
</tr>
<tr class="even">
<td class="confluenceTd">Implement token economics primitives</td>
<td class="confluenceTd">13</td>
<td class="confluenceTd">Medium</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
</tbody>
</table>



We have an active side project looking at using modern compiler tooling
to compile Solidity to WASM and are interested in being part of any
future movement to share code/structures through WASM execution and
interfaces. To that end we are planning to look into the possibility of
mounting Go wagon as a WASM interpreter next to our EVM.

We have also been building much business-process-on-a-blockchain
functionality with the combination of Burrow and 
<a href="https://github.com/agreements-network/blackstone" class="external-link" rel="nofollow" title="https://github.com/agreements-network/blackstone">Blackstone</a>
 our BPM engine implemented in Solidity and Node.JS. We are looking at improving Burrow's native abilities as a process-focussed blockchain.
We'd like to explore the possibility of Hyperledger being host to the
Blackstone project in some form - it should have relevance to fabric-evm
and sawtooth-seth.

# Maintainer Diversity

We have added one maintainer from Monax and have a strong candidate
outside Monax in Pierrick Hymbert who has become a contributor and has
expressed interest in maintainership.

Current maintainers are:

-   Greg Hill (Monax)

-   Silas Davis (Monax)

-   Sean Young (Monax)

-   Casey Kuhlman (Monax)

-   Tyler Jackson (Monax)

# Contributor Diversity

We have received bug reports and pull requests from the Fabric team. 
<span class="inline-comment-marker" ref="c0dd88cc-c2dd-4cbd-b99f-0fc7a5f36dc5">There have been several</span> 

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
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
<td><span id="comment-6424270"></span>
<p>reviewed</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by ChristopherFerris at Feb 14, 2019 13:21 </div ></td>
</tr>
</tbody>
</table>




