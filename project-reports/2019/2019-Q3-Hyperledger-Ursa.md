---
layout: default
title: 2019 Q3 Hyperledger Ursa
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Ursa

Created by Hart Montgomery, last modified by Troy Ronda on Sep 26, 2019

# Project Health

Ursa is moving forward, slowly but surely.  We have released two
versions-v0.1 and v0.1.1–since the last update. 

<u>Projects:</u>   Ursa is currently the only crypto library in use for
Indy-SDK (i.e., the Indy crypto library is no longer used in this case)
and Indy maintainers and contributors are working towards using Ursa for
all of their cryptography.  We have also been recently notified that an
intern has completed work on integrating Ursa into Iroha, which is more
good news (this was done by the Iroha team, so they deserve the credit
here–not us) ( <a href="https://github.com/hyperledger/iroha/commit/b3adc310e9c797c9dd5c99e4a7b518f2c5cf50f0" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/commit/b3adc310e9c797c9dd5c99e4a7b518f2c5cf50f0</a>
).

# Questions/Issues for the TSC

While this is more for project maintainers than the TSC (although the
overlap is heavy), we'd like to use this time to ask maintainers of
projects that aren't currently using <span class="inline-comment-marker" ref="10b12f7f-9367-4202-a198-01c6906a0ec4">Ursa </span> <span class="inline-comment-marker" ref="fb509bfa-c852-4b29-800e-c5ea25ea588c">what kind of features would
convince them to use Ursa. </span>  The more feedback we get, the better
we can do as a project.

The issue of the lack of dunking booth funding is also deeply concerning
to us, although we recognize that this is a governing board issue rather
than a TSC issue. 

# Releases

We made two releases since the last update:

v0.1.0 :  March 21

v0.1.1:  April 24

These releases are early releases that are targeted at replacing the
Indy crypto libraries while still preserving interfaces needed for
eventual Sawtooth use.

# Overall Activity in the Past Quarter

New Documents:

1.  Anonymous Credentials:  we have been formulating an implementation
for anonymous credentials, which has gone through multiple
iterations.
2.  Threshold issuance credentials:  we plan to add these once we
standardize an API.

New RFCs:

1.  Encryption API:  we have built an API for modular (symmetric)
encryption.  This will allow us to "plug and play" symmetric key
encryption protocols and block ciphers once implemented.
2.  Delegatable credentials and z-mix are in the pipeline.

New Code:

1.  Camenisch-Schoup Verifiable Encryption:
2.  Pointcheval-Sanders (PS) signatures:
3.  Much more "in the pipeline."
# Current Plans

We have a lot of work in progress, both in our base crypto library and
in our zero knowledge-focused zmix library.  Some things include:

1.  Continue work on our modular interfaces.  This is necessary so th"at we can make a better case for Sawtooth and Fabric to use Ursa. 
Example interfaces that still need work are our encryption/block
cipher interface and our "zk-signature" interface for PS and BBS+
signatures.

# Maintainer Diversity

Current active maintainers

-   Mike Lodder (Sovrin Foundation)
-   Lovesh Harchandani (Evernym Inc.)
-   Dave Huseby (Linux Foundation)
-   Hart Montgomery (Fujitsu)
-   Shawn Amundson (Bitwise)
-   Dan Middleton (Intel)
-   Cam Parra (Kiva)

New maintainers

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
-   Bitwise
-   <a href="https://anonyome.com/" class="external-link" rel="nofollow" style="text-decoration: none;text-align: center;">Anonyome Labs,
Inc.</a>
-   IdentOS
-   Jitsuin
-   Fujitsu

# Additional Information

# Reviewed by
-   ✅Angelo De Caro
-   ✅Arnaud J Le Hors
-   ✅Christopher Ferris
-   ✅Dan Middleton
-   ✅Gari Singh
-   ✅Hart Montgomery
-   ✅Mark Wagner
-   ✅Nathan George
-   ✅Swetha Repakula
-   ✅Tracy Kuhrt
-   ✅Troy Ronda



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-20024076"></span>
<p>An implementation of delegatable credentials in go:  <a href="https://github.com/IBM/dac-lib" class="external-link" rel="nofollow">https://github.com/IBM/dac-lib</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by angelo.decaro
at Sep 26, 2019 14:23 </div ></td>
</tr>
</tbody>
</table>




