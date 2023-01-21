---
layout: default
title: 2020 Q3 Hyperledger Iroha
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Iroha

Created by Sara Garifullina, last modified by Gari Singh on Sep 17, 2020

<span style="letter-spacing: 0.0px;"> </span>

# Project

Hyperledger Iroha

# Project Health

We are working to release 1.2 finished version – there is already a
release candidate. Community is helping to find issues and reports them,
communication in chats, mails and calls (yes, we revived community calls
and do little presentations on them now) is doing great. Internship
projects – not so well.

We are already working on a new v2 Iroha (in Rust!) and community is
excited about it. We also had a security audit. 

# Questions/Issues for the TSC

It would be great to have CI for s390x architecture. It seems th"at Hyperledger Jenkins previously had such machines. Is it possible to get
one currently?

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.2.0-rc.1" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha/releases/tag/1.2.0-rc.1</a>
 - June 10th, 2020

# Overall Activity in the Past Quarter

We receive questions in chats and mail lists regularly and do our best
to answer them all. We are happy to see that people from the community
step in when help is needed to newcomers. 

Regarding new development – we are trying to polish the v1.2 – it
already includes HL Burrow EVM, soon Iroha will support several HSM
modules (Securosys and Utimaco) that allow more secure key storage for
nodes. 

Iroha also supports client side HSMs - namely Tangem cards. 

Iroha will be able to run on IBM LinuxONE servers. We also have
internship projects. Unfortunately, not all results are satisfactory.

Some development shifted towards v2 – it already has some basic
functionality (it was already demonstrated on community meetings):
Consensus, synchronisation, bridge implementations and others. 

# Current Plans

1\) Finish 1.2 release

2\) Finalise internship projects

3\) Work on v2 that will have a much wider functionality especially
regarding interoperability 

# Maintainer Diversity

<a href="https://github.com/vmarkushin" class="external-link" rel="nofollow">Vladislav Markushin</a> is helping with bridge
functionality on Iroha v2

# Contributor Diversity

People on the chats are more active (they report issues, help out and
work on different projects on Iroha) but no more company contributors at the moment. We try to talk about Iroha on different events to give the
possible contributors as many chances to hear about us as possible.

# Additional Information

Nothing special

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
<td><span id="comment-36733624"></span>
<p>Do you have a link that you could share on v2 and what is expected in
that release?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by tkuhrt at Jul
22, 2020 15:32 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-36733878"></span>
<p>Hello, yes! </p>
<p>Development process is 100% open and most of the info is located
here:  <a href="https://wiki.hyperledger.org/display/iroha/Iroha+2">Iroha 2</a>  +
a little demo here: <a href="https://wiki.hyperledger.org/display/iroha/Iroha+Demo+Videos">Iroha
Demo Videos</a>  </p>
<p>I'll do my best to bring people working on Iroha 2 to the TSC
meeting, so if any questions occur, they could answer them. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jul
26, 2020 10:53 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-36734330"></span>
<p>Some updates on this: we have managed to resolve the issue with
internships and also added some details about HSM functionality. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Jul
30, 2020 12:20 </div ></td>
</tr>
</tbody>
</table>




