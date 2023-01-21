---
layout: default
title: 2019 Q4 Hyperledger Burrow
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Burrow

Created by Sean Young, last modified by Angelo De Caro on Nov 13, 2019

# Project Health

Our last update mentioned that there was a lack of documentation, which
was inhibiting new users. This has mostly been rectified and now
documentation requests are for more obscure features.

# Questions/Issues for the TSC

Some work has gone toward promoting burrow, for example  <a href="https://www.hyperledger.org/blog/2019/10/08/burrow-the-boring-blockchain" class="external-link" rel="nofollow">https://www.hyperledger.org/blog/2019/10/08/burrow-the-boring-blockchain</a>

We are always looking for further to promote burrow. Suggestions are
welcome.

# Releases

-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.28.0" class="external-link" rel="nofollow">v0.28.0</a>  Burrow now
remembers contact ABIs (and other metadata), bond and unbond
transactions, many fixes.
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.28.1" class="external-link" rel="nofollow">v0.28.1</a>  Burrow node js
module in main repo
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.28.2" class="external-link" rel="nofollow">v0.28.2</a>  burrow vent
decodes evm events before applying any filters
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.29.0" class="external-link" rel="nofollow">v0.29.0</a>  web3 support,
IdentifyTx, lots of new documentation. natives contracts are first
class contracts.
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.29.1" class="external-link" rel="nofollow">v0.29.1</a> bug fixes
-   <a href="https://github.com/hyperledger/burrow/releases/tag/v0.29.2" class="external-link" rel="nofollow">v0.29.2</a> bug fixes

# Overall Activity in the Past Quarter

<span style="color: rgb(23,43,77);">There has been plenty of
development, the vast majority from Monax employees, including: </span>

-   <span style="color: rgb(23,43,77);">lots of documentation has been
written and it can be read at 
<a href="https://hyperledger.github.io/burrow" class="external-link" rel="nofollow">https://hyperledger.github.io/burrow</a> . </span>
-   <span style="color: rgb(23,43,77);">web3 support </span>
-   <span style="color: rgb(23,43,77);">metadata for contract. The
metadata includes  ABI, source file, contract name and compiler
version. This stored on-chain. As a result  it is no longer
necessary to manage ABIs in files. </span>
-   <span style="color: rgb(23,43,77);">"native" contracts (written in
go and compiled into the burrow binary are now first class
contracts. This means that burrow supports Solidity (EVM) contracts,
WASM (e.g. solang) contracts, and native golang contract which can
all call each other. </span>
-   <span style="color: rgb(23,43,77);">New command "burrow accounts" which lists all the contract names, ABI etc for all accounts.</span>
-   <span style="color: rgb(23,43,77);">state is now serialised in
protobuf, rather than go-amino </span>
-   The <a href="https://www.npmjs.com/package/@hyperledger/burrow" class="external-link" rel="nofollow">node npm to interact with
burrow</a> has been merged into main burrow repo.
-   Work on identifyTx, bond, and unbond transactions.
-   Many other issues have also been solved.

# Current Plans

We need to have a push on explaining Burrow and documenting. A lot has
already been done towards this goal.

Now that golang native contracts (called "natives") are first class
contracts it is planned that burrow functionality which unique to burrow
(e.g. name reg, governance) will be implemented as natives so that the
can be called from regular call transactions, or from solidity, or from
our deploymen tool, burrow deploy.

Otherwise plans are unchanged since last update.

# Maintainer Diversity

<span style="color: rgb(23,43,77);">No new maintainers. We have 4 from
Monax, 2 non-Monax </span>

# Contributor Diversity

No new no-Monax contributers.

# Additional Information

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-24774516"></span>
<p>Nice work on the documentation</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mastersingh24
at Nov 08, 2019 08:22 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24774782"></span>
<p>Very interesting the work on supporting multiple contract languages.
Great  <img src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by angelo.decaro
at Nov 13, 2019 08:25 </div ></td>
</tr>
</tbody>
</table>




