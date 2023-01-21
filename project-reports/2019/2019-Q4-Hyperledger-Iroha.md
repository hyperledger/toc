---
layout: default
title: 2019 Q4 Hyperledger Iroha
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q4 Hyperledger Iroha

Created by Sara Garifullina, last modified by Nathan George on Mar 31, 2020

# Project Health

During the last quarter we managed to release new version and a patch
that made the project more stable as well as added some new features to
Iroha. Internships this year were great – both HL and interns from
Innopolis University – all of their projects were successful to
different extent. Community is relatively active, new projects use
Iroha. Overall, everything is well, with no drastic highs or lows. 

# Questions/Issues for the TSC

1\) We would really like to revive the discussion we started some time
ago with  <a href="https://wiki.hyperledger.org/display/~dhuseby" class="confluence-userlink user-mention" data-username="dhuseby" data-linked-resource-id="2392216" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Huseby</a> and 
<a href="https://wiki.hyperledger.org/display/~ryjones" class="confluence-userlink user-mention current-user-mention" data-username="ryjones" data-linked-resource-id="1180149" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Ry Jones</a> about wh"at help we could gather with resources for a huge Iroha testing on 100
nodes. There was an option of creating a simulation or getting the <span class="inline-comment-marker" ref="9175bf3f-75f1-4a1e-b1d1-b8f933873b77">infrastructure from CNCF</span>, because the more interest the project gets, the more questions
we receive on the performance – it is really important on this stage of
project development to have good data on the performance. 

2\) <span class="inline-comment-marker" ref="1325e80e-6ca5-4c3b-ad57-62aa3ff07b06">Hoping that Ry was able to
track down who is in charge of the HL's  </span> <span style="color: rgb(34,34,34);"> <span class="inline-comment-marker" ref="1325e80e-6ca5-4c3b-ad57-62aa3ff07b06">Transifex </span>:  </span>
<a href="https://www.transifex.com/hyperledger/public/" class="external-link" rel="nofollow">https://www.transifex.com/hyperledger/public/</a>  – we
cannot continue using the service that we have now (it is impossible to
decently automate it). There is also an option of using one of the
open-source localisation tools if HL could provide the infrastructure –
all projects could benefit from that (
<a href="https://wiki.hyperledger.org/display/~SaraG" class="confluence-userlink user-mention" data-username="SaraG" data-linked-resource-id="2392239" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Sara Garifullina</a>  has
some ideas of what could be used). 

3\) Another question was the <span class="inline-comment-marker" ref="972b80f4-8c0a-4895-b2ec-e6cf3407dd86">security audit </span>. It
was agreed with  <a href="https://wiki.hyperledger.org/display/~dhuseby" class="confluence-userlink user-mention" data-username="dhuseby" data-linked-resource-id="2392216" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Huseby</a> that we
will have it after we integrate Ursa into Iroha  – but there appears to
be a misunderstanding about it to be a cause for the next major release.
Integration of Ursa did not require that (and so the checklist th"at includes the audit) but at the same time, we did not have an audit for
quite a while now. How can we resolve that? 

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.1.0" class="external-link" rel="nofollow" style="text-decoration: underline;">Hyperledger Iroha v1.1</a>  – 24th
of July

<a href="https://github.com/hyperledger/iroha/releases/tag/1.1.1" class="external-link" rel="nofollow" style="text-decoration: underline;">Release 1.1.1</a>  – 20th of
September

# Overall Activity in the Past Quarter

Questions are being answered, as well as e-mails. It might be
interesting to notice that we've been receiving more advanced questions
recently that might mean deeper interest in the project. We also
restructured documentation (also might have helped with easier
questions) and added HL Google Analytics code so we could check the
interest.

As for the technical updates: 

In our 1.1 we included new API features such as:  <span style="color: rgb(36,41,46);">RemovePeer command, GetPeers
query, CompareAndSetAccountDetail command as well as the respective
permissions </span>

<span style="color: rgb(36,41,46);">Added Postgres options </span>

<span style="color: rgb(36,41,46);">Integrated vcpkg for dependencies</span>

<span style="color: rgb(36,41,46);"> <span class="inline-comment-marker" ref="fdae7435-5f01-476d-98e9-3bc9cac03c33">Together with interns,
integrated HL Ursa, Explorer, Burrow! </span>  </span>

<span style="color: rgb(36,41,46);">Were accepted and integrated support
for <a href="https://github.com/google/oss-fuzz" class="external-link" rel="nofollow">OSS-Fuzz</a></span>

<span style="color: rgb(36,41,46);">We are also trying to rework the
storage (huge refactoring that is taking some time) </span>

<span style="color: rgb(36,41,46);">Work on new TUI (instead of the
outdated CLI) is almost finished! </span>

# Current Plans

As mentioned before – we are working on some major refactoring that will
allow Iroha to be quicker and even more efficient. As for releases, we
are planning on having one very soon – when HL Burrow integration is
finalised. It will have all of the new integrations and EVM provided by Burrow. 

Also, we are working on making a pluggable BFT consensus – currently it
is in research state. Also, we are hoping to fix CI issues or join HL in
the universal CI for all of the projects. 

Hopefully, we'll have some news on Iroha certification, too. 

# <span class="inline-comment-marker" ref="0bf481d4-e63f-46c5-b372-329b538044eb">Maintainer Diversity </span>

<a href="https://wiki.hyperledger.org/display/~ekovalev" class="confluence-userlink user-mention" data-username="ekovalev" data-linked-resource-id="16327533" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Eugene Kovalev</a>  
<a href="https://github.com/ekovalev" class="external-link" rel="nofollow">https://github.com/ekovalev</a>

Artyom Gorbachov 
<a href="https://github.com/art-gor" class="external-link" rel="nofollow">https://github.com/art-gor</a>

# Contributor Diversity

Currently, it is Soramitsu + another Japanese company currently starting
to work with Iroha

+new individual contributor: 
<a href="https://github.com/ericcurtin" class="external-link" rel="nofollow">https://github.com/ericcurtin</a>

# Additional Information

We went to Moscow Bootcamp and hope to see new faces among our community
after it! 

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
<td><span id="comment-22382853"></span>
<p>I really appreciate that the report mentions activities for
integrating other Hyperledger projects. I would suggest to report also
activities, if any, in the opposite direction the one that says: We have
this component that can be reused in this and this way  <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by angelo.decaro
at Oct 17, 2019 13:14 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-24117300"></span>
<p>Great seeing several of the Iroha maintainers / contributors at the
Moscow summit. It seemed there was a lot of engagement in your
sessions.</p>
<p>Regarding security audit, I believe our policy is to do that ahead of
major releases for each project.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by dan.middleton@intel.com at Oct 21, 2019 06:24 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-24772983"></span>
<p>Check with <span>Rich Zhao </span> who is leading the effort in China
to translate Fabric docs as to ownership of hyperledger transifex.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by ChristopherFerris at Oct 24, 2019 14:14 </div ></td>
</tr>
</tbody>
</table>




