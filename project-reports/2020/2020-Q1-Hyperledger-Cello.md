---
layout: default
title: 2020 Q1 Hyperledger Cello
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Cello

Created by Baohua Yang, last modified by Gari Singh on Apr 27, 2020

# Project Health

<span style="color: rgb(51,51,51);">Due to the vacations and
corona-virus disease,  we have canceled numbers of weekly meetings in
Feb. The meeting will start since the 2nd week of Mar. </span>

<span style="color: rgb(51,51,51);">Now we are re-designing the
architecture and finishing the features for v1.0. </span>

<span style="color: rgb(51,51,51);">There is new members to join the
project like Dixing, and he is getting familiar with the project.</span>

# Issues

The implementation of the new governing model is not as quick as planed.
We are lacking of front end developers, will recruit some candidates.

# Releases

<span class="inline-comment-marker" ref="bc2132d9-465b-45fe-99e5-d3ad837fb085">v1.0.0 (In plan) </span>

-   New governing model;
-   Support fabric v1.4 LTS and 2.0 experimentally;
-   Support k8s operator agent.

# Overall Activity in the Past Quarter

-   <span style="letter-spacing: 0.0px;">Design the new governing model;</span>
-   Re-designed and the dashboard workflow for the new APIs;
-   Updated the document for the new architecture.

# Current Plans

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd">Finish the new dashboard implementation</td>
<td class="confluenceTd">High</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p>Finish the workflow with the k8s operator
agent</p></td>
<td class="confluenceTd">High</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p>Fix all github related warnings and optimize
the process</p></td>
<td class="confluenceTd">Medium</td>
</tr>
<tr class="even">
<td class="confluenceTd">Support HLF 1.4 LTS and later version</td>
<td class="confluenceTd">Medium</td>
</tr>
</tbody>
</table>

# Maintainer Diversity

Current there are 4 maintainers, and those active developers who
contribute to cello continuously (3 month) will be nominated.

-   Baohua Yang (Oracle)
-   Haitao Yue (IBM)
-   Tong Li (IBM)
-   Jiahao Chen (VMware)

# Contributor Diversity

<span style="color: rgb(51,51,51);">Not changed too much. We have one
new active member. </span>

# Additional Information

N/A

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
<td><span id="comment-31195522"></span>
<p>Could you describe the new "governing model" a little bit?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by dan.middleton@intel.com at Mar 10, 2020 15:24 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-31195897"></span>
<p><a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>  , Yes,
the major purpose is to allow the members of a blockchain network to
govern their own resource separately, and Cello would like  to provide
this convenience, especially they want to collaborate together to have
business transactions with blockchain ledgers. More details can be found
at  <a href="https://docs.google.com/document/d/1Dw6cEKaul6FenORNkDcxvPDDKwpl0A5EmcJBlqAWJoU/" class="external-link" rel="nofollow"><img
src="plugins/servlet/confluence/placeholder/unknown-macro" class="wysiwyg-unknown-macro" /></a> .</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by baohua at Mar
12, 2020 21:32 </div ></td>
</tr>
</tbody>
</table>




