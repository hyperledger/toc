---
layout: default
title: 2020 Q3 Hyperledger Ursa
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Ursa

Created by Hart Montgomery, last modified by Troy Ronda on Oct 01, 2020

# Project

This report covers Hyperledger Ursa.

# Project Health

<span style="color: rgb(23,43,77);">Ursa has been in a relatively stable
state recently.  Contributions have been down a little bit, some of
which we attribute to the "summer of COVID" and others due to the fact
that some users of Ursa are happy with the existing primitives and want
to work on things that are more immediate to their business needs.  We
have recently seen a surge in Ursa usage by groups outside of
Hyperledger, although unfortunately we have not been able to use this to
increase our contributor base. </span>

# Questions/Issues for the TSC

We say something like this in pretty much every report, but we want to
reiterate that w <span style="color: rgb(23,43,77);">e are always
interested in getting in touch with others who want to use cryptography,
and particularly so for people that want to use non-standardized crypto
like threshold signatures or zero knowledge proofs.  If this describes
you, please feel free to get in touch with us. </span>

# Releases

We released 0.3.4 on Jul 7, 2020 0.3.5 Aug 19, 2020 this quarter, and
bbs 0.4.0 on Jul 7, 2020.  Internally, we are on v0.3.6.

The new releases include

-   BBS+ work with wasm
-   Shamir secret sharing
-   BLS signature integration with Signer interface

# Overall Activity in the Past Quarter

We implemented a number of exciting new features in the past quarter,
although these are not reflected yet in our current releases&gt;

-   We added WASM support for BBS+ signatures as we indicated in our
plans in the last report.  The BBS+ signature code is probably our
most popular feature, as a number of people outside Hyperledger seem
to be using this.
-   Upgraded all of our external dependencies on crypto primitives to
the latest versions and ensured compatibility.
-   Implemented our own version of Shamir secret sharing.  Existing
versions don't have the flexibility that we need in Ursa.  For those
unaware, Shamir secret sharing (and some other tricks) are widely
used across group-based threshold cryptography.  We have demand for
threshold crypto implementations, so this is something that we are
currently working towards.
-   Perhaps most importantly, we agreed to an RFC that details the
project structure for the zero knowledge proofs.  This will guide
Ursa going forward.
-   We did not make much progress on trusted hardware this quarter,
unfortunately.

# Current Plans

We have a number of things that we want to build and/or design:

-   Threshold cryptography:  we would like to have threshold signatures
and other threshold crypto primitives.  We are planning on working
towards building these.
-   tBLS
-   Feldman VSS
-   Pedersen VSS
-   Accumulator work
-   RSA
-   ECC
-   Post-quantum cryptography:  now that the NIST competition is in the
final round, we feel like it is time to start providing options for
post-quantum crypto primitives in Ursa.  Luckily, many of the teams
behind these new key exchange protocols and signature schemes have
written their code in Rust, so hopefully integration should be
straightforward.  This will probably necessitate some work on our
configuration options for the "base" Ursa primitives.
-   Hyperledger Cactus is potentially interested in using Ursa.  This
will require effort from both sides, but we may aim to work on our
node.js wrappers to help them.

# Maintainer Diversity

<u>Current Active Maintainers:</u>

-   Mike Lodder (Independent)
-   Brent Zundel (Evernym Inc.)
-   Dave Huseby (Linux Foundation)
-   Hart Montgomery (Fujitsu)
-   Dan Middleton (Intel)
-   Cam Parra (Kiva)
-   Dan Anderson (Intel)
-   Jon Geater (Jitsuin)

Some of these maintainers are obviously more active than others.

# Contributor Diversity

<u>Current Contributor Affiliations</u> :

-   Independent (thanks Mike!)
-   Evernym, Inc
-   Intel
-   BCGov
-   Iqlusion
-   Fujitsu
-   Innopolis University (thanks Iroha team!)
-   MediConCen Limited



This list is inexact and may be missing some people, but should be
representative (lots of people don't have company information listed,
and some are mostly working as contractors).  If you should be
represented here and are not, please add yourself!  We would also like
to thank Ry and others that made collecting all of this information easy
with Community Bridge!

# Additional Information

We have received more academic interest in Ursa recently, which has been
a very positive development.  In particular, we had a meeting with Prof.
Anna Lysyanskaya, an IACR fellow and famous cryptographer, to discuss
our CL signatures and open problems regarding anonymous credentials.  We
can hopefully get more academic interest in Ursa and use this to stay on
the cutting edge of safe cryptography. 

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






