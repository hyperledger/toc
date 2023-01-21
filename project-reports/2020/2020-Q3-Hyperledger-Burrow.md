---
layout: default
title: 2020 Q3 Hyperledger Burrow
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Burrow

Created by Silas Davis, last modified by Troy Ronda on Oct 01, 2020

# Project

Hyperledger Burrow

# Project Health

This quarter has certainly been a fallow quarter for Burrow, mostly as a
consequence of Covid and in the case of Monax the need to refocus on our
product built on top of Burrow. We do have more work planned and another
developer coming in to work on the SQL mapping layer Vent at the end of
this year to extend its functionality.



Inevitably this raises considerations that have lingered around Burrow
and the level of development activity from a wider community. I think it
would be premature at this stage to talk about end-of-life for Burrow as
I am aware of other companies taking an interest (such as CertiK).
However I think the next two quarters will be critical for Burrow and on
that timescale we should revisit this question and decide whether there
is a realistic prospect of Burrow leaving incubation (chiefly in having
sufficient contribution-weighted contributor diversity).

I do expect Q1 2021 to be quite active in terms of work that Monax needs
to do on Burrow so one way or another Burrow does need an active
development home in the medium term, but I defer to the TSC to judge
whether Hyperledger is that home. If we are able to garner greater
community involvement then I think it could, but so far with the time
and resources I have available to me for community building that has not
really happened.

# Questions/Issues for the TSC

Just any reflections on the above.

# Releases

\- <a href="https://github.com/hyperledger/burrow/releases/tag/v0.30.5" class="external-link" rel="nofollow">[v0.30.5]</a> Provide
\`BytesToHex\` for Vent projections

# Overall Activity in the Past Quarter and Current Plans

There has been a certain amount of thinking activity away from lines of
code:

-   Paper design for some features to Vent that make it more capable to
form projections over events - generated columns, literal columns,
JSON support. You can define Solidity events (via EVM log) and form
log-structured tables or realised projections (using SQL upsert
idioms) to reflect your blockchain-stored evidence in a traditional
SQL schema read-only, combined with other write tables, blended with
views
-   Idea to support event emission via AssemblyScript WASM constracts
-   Using JSON Schema and tooling from the Typescript world
(particularly the excellent
<a href="https://github.com/gcanti/io-ts" class="external-link" rel="nofollow">https://github.com/gcanti/io-ts</a> ) to generate
smart contract stub code, event schema, and database mappings



The theme of all this design work is geared towards emphasising a
schema-first (OpenAPI spec/JSON schema) and code-generation heavy way of
working with event streams and having Burrow specialise in storing
streams of events with relatively lightweight (much more lightweight
that what we have typically done in Solidity) contracts to maintain
integrity of our events. Also the idea to move away from Solidity/EVM
and provide a way of working with events in AssemblyScript (keeping the
events isomoporphic to Solidity events).

# Maintainer Diversity

See: <a href="https://github.com/hyperledger/burrow/blob/master/MAINTAINERS.md" class="external-link" rel="nofollow">https://github.com/hyperledger/burrow/blob/master/MAINTAINERS.md</a>

# Contributor Diversity

No new contributors

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
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
<td><span id="comment-39619113"></span>
<p>Personally, I think we need to think about changing / removing the
diversity criteria.  What concerns me more is the long-term
sustainability and maintainability of projects.  I think that's a major
part of the intent behind the diversity criterion.<br />
<br />
And I believe Sawtooth / Transact intend to continue using the Burrow
EVM and fabric-evm-chaincode still exists as well.<br />
So definitely not the time to discuss end of life IMHO.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mastersingh24
at Sep 17, 2020 11:56 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-39619126"></span>
<p>I agree with Gari. The EVM is a very good piece of software, well
defined and self contained to be used in other projects. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by angelo.decaro
at Sep 17, 2020 12:18 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-39619127"></span>
<p>Burrow ewasm support is not far from being complete. Sawtooth and
fabric-evm-chaincode may be interested in adopting this feature as
well.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by seanyoung at Sep 17, 2020 12:20 </div ></td>
</tr>
</tbody>
</table>




