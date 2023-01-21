---
layout: default
title: 2019 Q2 Hyperledger Burrow
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q2 Hyperledger Burrow

Created by Sean Young, last modified by Arnaud J Le Hors on May 23, 2019

# Project Health

<span style="color: rgb(51,51,51);">Project health is largely the same
as in previous update.  </span> <span style="color: rgb(51,51,51);">We
have a number of casual contributors. We still lack maintainer diversity
outside of Monax. There is a steady flow of interest and we are pushing
plenty of code relating to our continued heavy use of Burrow. </span>

# Issues

<span style="color: rgb(51,51,51);">The biggest areas of help would be
with tooling and documentation.  </span>

# Releases

-   v0.25.1: minor fixes to make deployment via helm easier
-   v0.25.0: burrow configure can generate config for every validator,
making it easy to run many validators for local testing, burrow
deploy can execute deploy scripts concurrently, no concensus
testing/development mode.
-   v0.24.1 - v0.24.6: minor bugfixes and dependencies upgrades (e.g.
tendermint)
-   v0.24.0: Implemented EVM opcodes, burrow deploy can print emitted
EVM events, burrow deploy can use keystore names rather than
addresses and burrow vent can do projection mapping, all state now
stored in a mutable forest.

# Overall Activity in the Past Quarter

<span style="color: rgb(51,51,51);">We have implemented some EVM opcodes
and upgraded our tests to use Solidity 0.5.4 and improved our deploy
tool to increase concurrency. All state is now stored in a mutable
forest so proof can be given for contract state root (not implemented
yet, just the plumbing). Lots of porcelain updates to burrow deploy
tool. </span>

# Current Plans



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
<td class="confluenceTd"><span style="color: rgb(31,35,38);">Secure
access to Burrow chain </span></td>
<td class="confluenceTd">5</td>
<td class="confluenceTd">Medium</td>
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

We have added one maintainer from Monax and have a new
maintainer, Pierrick Hymbert, from outside Monax

Current maintainers are:

-   Greg Hill (Monax)

-   Silas Davis (Monax)

-   Sean Young (Monax)

-   Casey Kuhlman (Monax)

-   Tyler Jackson (Monax)

-   Pierrick Hymbert

# Contributor Diversity

Interest remains high and lots of in-depth questions are being asked on
rocketchat.

# Additional Information

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span> </span></span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner </span> </span> </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span> </span></span> </span> </span> </span> </span>






