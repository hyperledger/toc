---
layout: default
title: 2021 Q1 Hyperledger Burrow
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Burrow

Created by Silas Davis, last modified by Angelo De Caro on Mar 31, 2021

# Project Health

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? </span>

<span style="letter-spacing: 0.0px;">Yes </span>

1.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? </span>

<span style="color: rgb(23,43,77);text-decoration: none;">Added
repolint.json to repo, however the repolint tool does not support node
v15 via transitive dependency:

\`\`\`</span>

error clinic@6.0.2: The engine "node" is incompatible with this module.
Expected version "^13.0.0 || ^12.0.0 || ^11.0.0 || ^10.12.0". Got
"15.11.0"
error Found incompatible module.
\`\`\`

So deferring full implementation until it does. (also doesn't build with
node v13 on NVM, so may need some better tooling here)

# Releases

\- **<a href="https://github.com/hyperledger/burrow/blob/master/CHANGELOG.md#0310" class="external-link" rel="nofollow">v0.31.0</a>** - Much goodliness -
complete eWASM support, Vent support for mainline Ethereum, Web3 fixes,
cross-smart-contract-engine calling

# Overall Activity in the Past Quarter

After a fallow period in Q4 2020 Burrow has seen the best quarter of
activity I can remember. We have made completed the
<a href="https://github.com/ewasm/design/blob/master/eth_interface.md" class="external-link" rel="nofollow">draft ewasm standard</a> supported
by Sean Young's work on (
<a href="https://github.com/hyperledger-labs/solang" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/solang</a> ) with
Burrow as a supported ledger. This means that Burrow combined with
Solang offers a complete stack for compiling and running Solidity ewasm
contracts. Since Fabric, Sawtooth, and Iroha already consume the Burrow
EVM implementation, these could easily be extended to also include the
ewasm implementation. This would make it possible to use Solang and
other ewasm tooling with those ledgers.

Vent - our Ethereum-to-SQL mapping layer now supports listening to web3
JSON-RPC chains (all mainline Ethereum clients) to build tables. This
opens up interesting possibilities for contract oracles, state channels,
and layer-2 scaling. We have continued to keep up-to-date with the
latest Tendermint.

We now also support calling between our three smart contract engines -
EVM, ewasm, and Go 'natives'. Our calling and state conventions are all
Ethereum, but provide a lot of flexibility compared to mainline Ethereum
clients.

# Current Plans

Burrow is preparing itself to support connection to multiple other
chains by supporting reading from Ethereum with Vent and we soon hope to
support Cosmos via the IBC protocol which we are poised to adopt based
on our use of Tendermint consensus.

I want to provide support for AssemblyScript (a subset of Typescript)
contracts via ewasm that can call, and be called from Solidity.

We will be extending our NameReg service to hold Burrow-global
references to external resources (like Ethereum accounts, external
tokens, and Hoard and IPFS content.

# Maintainer Diversity

We have maintained our maintainer diversity:

-   Greg Hill of
<a href="https://www.interlay.io/" class="external-link" rel="nofollow">https://www.interlay.io/</a>
-   Sean Young of <a href="https://github.com/hyperledger-labs/solang" class="external-link" rel="nofollow">https://github.com/hyperledger-labs/solang</a> and
Linux Kernel
-   Silas Davis of <a href="https://monax.io/" class="external-link" rel="nofollow">https://monax.io/</a>
-   Casey Kuhlman of <a href="https://monax.io/" class="external-link" rel="nofollow">https://monax.io/</a>

All of whom are actively contributing.

# Contributor Diversity

We have had significant contributions from:


-   <a href="https://github.com/vgrabovski-lacero-platform" class="external-link" rel="nofollow">https://github.com/vgrabovski-lacero-platform</a>
(critical EVM fixes and improvements, multiple changes)
-   <a href="https://github.com/yoongbok-lee" class="external-link" rel="nofollow">https://github.com/yoongbok-lee</a> (much expanded
ewasm support, multiple change)
-   <a href="https://github.com/bzp99" class="external-link" rel="nofollow">https://github.com/bzp99</a> (OS portability
imrpovements)

# Help from the TSC

One of the most battle-tested and potentially widely applicable parts of
burrow is Vent - our SQL mapping layer. To my knowledge nothing else
quite like it exists serving the Solidity/Ethereum community. With our
recent addition of Ethereum support I believe this component of Burrow
might be of significant value even to those not using Burrow today. It
would be useful to have an opportunity to describe briefly how this
component works, what one can do with it, and to solicit opinions on how
to attract collaborators.

I think the recent developments with Vent and our ewasm abilities could
position Burrow as a pragmatic state channel/oracle solution for public
blockchain.

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
-   🔲 <span class="placeholder-inline-tasks">
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
<td><span id="comment-41595298"></span>
<p>You may want to get in touch with Shahan Khatchadourian, he was
working on a similar sounding project before he left ConsenSys a year
ago called "Sandcastle".  Approach was a bit different (the SQL was
compiled to smart contracts if I read it correctly) but he may have some
useful insights for the implications of integrating SQL with EVM.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by shemnon at Mar 16, 2021 16:29 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41595357"></span>
<p>I'd be happy to give you 20mn on an upcoming TSC call if you'd like
to give a presentation on Vent.</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Mar
17, 2021 08:51 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41595381"></span>
<p>Thanks, I could give a little presentation tomorrow or TSC after if
you prefer</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by silasdavis at Mar 17, 2021 15:51 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41595402"></span>
<p><a href="https://wiki.hyperledger.org/display/~silasdavis" class="confluence-userlink user-mention" data-username="silasdavis" data-linked-resource-id="2393271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Silas Davis</a> this is a
great topic also to speak to the community in general once developed.
Let me know if you would like to pitch it to the wider developer
community in APAC region.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Mar 17, 2021 18:05 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41595412"></span>
<p>Okay great! There's no great magic here, but in our use of it it has
allowed building some interesting systems.<br />
<br />
The basic idea is:<br />
<br />
- EVM events (opcodes: LOG0...LOG4) (serialised similarly to function
calls) are mapped to SQL inserts/upserts/deletes<br />
- Smart contracts emit EVM events and Vent processes them through a
declarative mapping declaration into SQL tables (generated dynamically
and can be rebuilt if projection specifications (which are JSON files)
change)<br />
- The whole system uses the block height as a global clock<br />
- Reads/writes/joins to a traditional database schema can be
synchronised causally with some helpers by considering block height high
watermarks</p>
<p><br />
</p>
<p>We are using this to integrate with a traditional app and also
provide a contract oracle on Ethereum (now that Vent supports reading
from eth)<br />
<br />
I will produce a couple of slides to walk through this and share it on
the TSC list and in the Burrow repo.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by silasdavis at Mar 17, 2021 18:53 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41595413"></span>
<p>Please put us in touch either here, on list, or silas dot davis ta
monax.io</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by silasdavis at Mar 17, 2021 18:55 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41595415"></span>
<p>Yep seems like this is kind of running the pipes the other way round:
<a href="https://media.consensys.net/sandcastle-brings-sql-to-ethereum-smart-contracts-4addd1b351cd" class="external-link" rel="nofollow">https://media.consensys.net/sandcastle-brings-sql-to-ethereum-smart-contracts-4addd1b351cd</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by silasdavis at Mar 17, 2021 18:57 </div ></td>
</tr>
</tbody>
</table>




