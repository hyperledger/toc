---
layout: default
title: 2020 Q2 Hyperledger Ursa
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Ursa

Created by Hart Montgomery, last modified by Gari Singh on Jun 11, 2020

# Project

This is the report of the Ursa project.  

# Project Health

Ursa has been in a relatively stable state recently, which is nice
considering the Sovrin foundation let go of all of its technical staff,
some of whom contributed extensively to Ursa (and thankfully still
are).  We are continuing work on "fancy" crypto primitives like zero
knowledge proofs.  We have substantially improved the efficiency of some
of our elliptic-curve based primitives recently, which should hopefully
make adoption more compelling.

# Questions/Issues for the TSC

We are always interested in getting in touch with others who want to use
cryptography, and particularly so for people that want to use
non-standardized crypto like threshold signatures or zero knowledge
proofs.  If this describes you, please feel free to get in touch with
us.

# Releases

We've had two releases since the last report, which focused on BBS+
signatures.

April 29:  bbs-v0.3.0

May 18:  bbs-v0.4.0

# Overall Activity in the Past Quarter

-   Added and improved BBS+ signatures
-   Switched our core pairings library from Milagro to pairing-plus
(Apache 2.0 licensed).  This gives us both much better efficiency
and probably more security, since pairing-plus seems to be better
maintained than the Apache-licensed version of Milagro.
-   Implemented efficient "hash to curve" functionality.

# Current Plans

-   Add WASM support for BBS+ signatures.
-   Continue with our work on trusted hardware.

# Maintainer Diversity

<u>Current Active Maintainers:</u>

-   Mike Lodder (Sovrin Foundation)
-   Brent Zundel (Evernym Inc.)
-   Dave Huseby (Linux Foundation)
-   Hart Montgomery (Fujitsu)
-   Dan Middleton (Intel)
-   Cam Parra (Kiva)
-   Dan Anderson (Intel)
-   Jon Geater (Jitsuin)

# Contributor Diversity

<u>Current Contributor Affiliations</u> :

-   Evernym, Inc
-   Intel
-   BCGov
-   Iqlusion
-   Jitsuin
-   Fujitsu

We would especially like to note that our most prolific contributor
(Mike Lodder) is now an independent contributor (so if you are hiring,
take note).  In addition, we would like to thank the BCGov team for
contributing quite a bit this quarter.

# Additional Information

Ursa meeting attendance has increased a bit as of late, although this
has not directly translated (hopefully yet) into more contributors.  

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
<td><span id="comment-31202638"></span>
<p>Hart, great report!</p>
<p>I am very much appreciate that you actully listed the maintainers,
not just "same as last time" or "same as it ever was" or whatever.</p>
<p>Also a nice touch to list the companies contributing.</p>
<p><br />
</p>
<p>Thanks</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mwagner at Jun 11, 2020 01:26 </div ></td>
</tr>
</tbody>
</table>




