---
layout: default
title: 2020 Q1 Hyperledger Ursa
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Ursa

Created by Mike Lodder, last modified by Gari Singh on Apr 27, 2020

# Project Health

Ursa is growing in adoption in projects, its feature offering, and
contributor diversity. We have released three more versions since last
update.

# Questions/Issues for the TSC



# Releases

v0.3.0 Dec 5 2019

v0.3.1 Jan 22 2020

v0.3.2 Feb 10 2020

# Overall Activity in the Past Quarter

-   Added key exchange for Curve25519 and K256
-   Allowed more methods over FFI
-   Allowed more methods over WASM
-   Adjusted how features can be included to be more flexible

# Current Plans

-   Add ECIES encryption
-   Add signatures and key exchange for P224, P256, P384, P521
-   Implement more FFI for zmix
-   Finish designing hardware API
-   Implement CDLNT signatures (allows threshold based issuance and
verification)
-   Add pw\_hash methods
-   Implement Simplified SWU hash-to-curve

# Maintainer Diversity



Current active maintainers

-   Mike Lodder (Sovrin Foundation)
-   Lovesh Harchandani (Evernym Inc.)
-   Brent Zundel (Evernym Inc.)
-   Dave Huseby (Linux Foundation)
-   Hart Montgomery (Fujitsu)
-   Dan Middleton (Intel)
-   Cam Parra (Kiva)
-   Dan Anderson (Intel)
-   Jon Geater (Jitsuin)

# Contributor Diversity

Our contributor list has been relatively static, although we are
optimistic of adding new contributors in the near future (e.g., for
hardware support).

Current Contributors

-   Sovrin Foundation
-   Evernym, Inc
-   Intel
-   BCGov
-   Iqlusion
-   Jitsuin
-   Fujitsu

# Additional Information



# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
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
<td><span id="comment-31195504"></span>
<p>What projects are using Ursa?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Mar
10, 2020 14:12 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31195539"></span>
<p>Indy and Aries actively use Ursa.  Ursa also currently supports Iroha
and Transact.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Mar
10, 2020 16:07 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-31197649"></span>
<p><a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>  sounds
like a good blog post on HL interoperability?  <img
src="emoticons/wink.svg" class="emoticon emoticon-wink" data-emoticon-name="wink" alt="(wink)" /> Would you or someone else be
willing to write that up? </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by jramps9 at Apr 08, 2020 15:42 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31197666"></span>
<p>I think Mike Lodder  <a href="https://wiki.hyperledger.org/display/~MikeLodder" class="confluence-userlink user-mention" data-username="MikeLodder" data-linked-resource-id="6422957" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mike Lodder</a> would be
the person best suited for this–he knows more about the interfaces than
I do!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Apr
08, 2020 17:33 </div ></td>
</tr>
</tbody>
</table>




