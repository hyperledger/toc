---
layout: default
title: 2021 Q2 Hyperledger Burrow
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q2 Hyperledger Burrow

Created by Silas Davis, last modified by David Enyeart on Jul 29, 2021

<span style="letter-spacing: 0.0px;font-size: 24.0px;">Project Health</span>

Burrow is doing better than ever before. We've added some significant
features and <a href="https://github.com/hyperledger/burrow/pull/1488" class="external-link" rel="nofollow">random people from the internet are
fixing our off-by-ones</a> . We also have a new team, Damascus Mile,
with funding from the UK Cabinet Office who are building out a logistics
platform on top of Burrow.

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">?
yes</span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?
yes </span>

# Questions/Issues for the TSC

No issues, but would like to call out Typescript code generation (AKA
solts) along with the improved Javascript/Typescript client gives a
*vastly*   improved application-building experience (here is an <a href="https://github.com/hyperledger/burrow/blob/1f0dcffb3c70beb7ede57a09f26dd39c79a8c6f3/js/src/solts/sol/Eventer.abi.ts" class="external-link" rel="nofollow">example of the generated code</a>
). <a href="https://www.npmjs.com/package/@hyperledger/burrow" class="external-link" rel="nofollow">@hyperledger/burrow</a> now exposes
a \`build\` function that takes a Solidity source tree and generates
strongly typed bindings for Burrow that embed the contract bytecode,
ABI, metadata, and allows you to deploy the contract, stream events, and
call functions all via a strongly typed interfaces. Kudos to 
<a href="https://wiki.hyperledger.org/display/~gregdhill" class="confluence-userlink user-mention" data-username="gregdhill" data-linked-resource-id="6426971" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gregory Hill</a> for
building the original solts.

Um, as ever, this is <a href="https://github.com/hyperledger/burrow/blob/main/js/src/solts/build.ts#L24-L31" class="external-link" rel="nofollow">not very well documented</a>
¯\\\_(ツ)\_/¯ <span class="emoji">. </span>

# Releases

-   0.31.1 - Web3 and Vent fixes
-   0.31.2 - Dump/restore fixes
-   0.31.3 - Dump/restore improvements
-   0.32.0 - Burrow.js rewrite in Typescript, better ABI library, core
state cache concurrency fix
-   0.32.1 - Improved errors and Javascript type coercion
-   0.33.0 - Introduced Solidity-to-Typescript client-side code
generation, fixed client-side events, fixed finite stream bounds
-   0.33.1 - Inline JS source maps and fixed BytesNN typing
-   0.34.0 - Simplified JS codegen Provider interface (supporting other
implementations), codegen fixes

See
<a href="https://github.com/hyperledger/burrow/blob/main/CHANGELOG.md" class="external-link" rel="nofollow">https://github.com/hyperledger/burrow/blob/main/CHANGELOG.md</a>
for more details.

# Overall Activity in the Past Quarter

Chat remains relatively quiet generating a handful of messages per
month. Github has seen some small but deep patches which seems to
indicate there is some 'serious' usage going on. Damascus Mile has
chosen to use Burrow as an ideal 'root stock' for their logistics
project - hopefully evidence of Burrow's effort to be extensible and
modular. Development activity has picked up quite a bit over previous
two quarters.

# Current Plans

Two major roadmap items are in play:

1.  State-splitting - providing a better way to divide account state
while preserving commitments/proofs. Also the possibility of
projecting out some state in an 'export' while preserving proofs.
The relevance being around state channels/optimistic roll-ups where
we would like to be able to provide a more granular subset of state
than our current single global state root allows.
2.  Providing more practical support for WASM contracts (including
AssemblyScript being given our Typescript leanings) by providing
client library support and doing more testing.

# Maintainer Diversity

We have added Ommi Shimizu from Monax.

**Active Maintainers**

<table class="wrapped confluenceTable">
<thead>
<tr class="header">
<th class="confluenceTh">Name</th>
<th class="confluenceTh">GitHub</th>
<th class="confluenceTh">email</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td class="confluenceTd">Greg Hill</td>
<td class="confluenceTd"><a href="https://github.com/gregdhill" class="external-link" rel="nofollow">@gregdhill</a></td>
<td class="confluenceTd"><a href="mailto:gregorydhill@outlook.com" class="external-link" rel="nofollow">gregorydhill@outlook.com</a></td>
</tr>
<tr class="even">
<td class="confluenceTd">Sean Young</td>
<td class="confluenceTd"><a href="https://github.com/seanyoung" class="external-link" rel="nofollow">@seanyoung</a></td>
<td class="confluenceTd"><a href="mailto:sean@mess.org" class="external-link" rel="nofollow">sean@mess.org</a></td>
</tr>
<tr class="odd">
<td class="confluenceTd">Casey Kuhlman</td>
<td class="confluenceTd"><a href="https://github.com/compleatang" class="external-link" rel="nofollow">@compleatang</a></td>
<td class="confluenceTd"><a href="mailto:casey.kuhlman@monax.io" class="external-link" rel="nofollow">casey.kuhlman@monax.io</a></td>
</tr>
<tr class="even">
<td class="confluenceTd">Silas Davis</td>
<td class="confluenceTd"><a href="https://github.com/silasdavis" class="external-link" rel="nofollow">@silasdavis</a></td>
<td class="confluenceTd"><a href="mailto:silas.davis@monax.io" class="external-link" rel="nofollow">silas.davis@monax.io</a></td>
</tr>
<tr class="odd">
<td class="confluenceTd">Ommi Shimizu</td>
<td class="confluenceTd"><a href="https://github.com/ommish" class="external-link" rel="nofollow">@ommish</a></td>
<td class="confluenceTd"><a href="mailto:ommi.shimizu@monax.io" class="external-link" rel="nofollow">ommi.shimizu@monax.io</a></td>
</tr>
</tbody>
</table>

# Contributor Diversity

We have had around five new individual contributors this quarter and
interest in using us from Damascus Mile.

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
<td><span id="comment-51612910"></span>
<p>Is there an LFX insights link?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by shemnon at Jun 02, 2021 17:12 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-51612933"></span>
<p><a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fburrow/dashboard?time=%7B%22from%22:%222021-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-06-01T06:59:59.000Z%22%7D" class="external-link" rel="nofollow">Insights (linuxfoundation.org)</a>
 for April and May 2021</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by tkuhrt at Jun
02, 2021 17:46 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-51612935"></span>
<p>Are we not requiring the report to have it in-report anymore?</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Jun 02, 2021 17:48 </div ></td>
</tr>
</tbody>
</table>




