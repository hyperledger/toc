---
layout: default
title: 2021 Q1 Hyperledger Iroha
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Iroha

Created by Sara Garifullina, last modified by Gari Singh on Mar 17, 2021

# Project

Hyperledger Iroha

# Project Health

Currently, there are 2 teams working on Iroha - Iroha v1 and Iroha v2.
Iroha 1 team is less active and mostly works on providing and
maintaining a stable 1.2 version, fixing some issues with the release
while team Iroha 2 is actively working on creation of the newer version.
Community is active and appropriate, we are happy to have contributors
who help the new users to resolve any difficulties with using Iroha. 

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? Not yet,
will do </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">?  Not yet, will
do </span>

# Questions/Issues for the TSC

Are there any newsletters we could subscribe to to learn about important
TSC solutions without following all the discussions in TSC group?

What are the due dates for renaming the master branch and adding
repoliner?

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.2.0" class="external-link" rel="nofollow">HL Iroha v1.2</a>

# Overall Activity in the Past Quarter

For Iroha 1: 

We worked to release 1.2 and now to stabilise it as well as possible. 

1.  With the help from Diva.exchange developers we fixed several
stability issues when network is slow and some peers are
disconnected
2.  Improved performance by optimising some sql scripts
3.  Improving Iroha to migrate between different versions with as
minimum downtime as possible
4.  Working on switching to KV database that expected to bring huge
performance boost

For Iroha 2: 

1.  Introduced Permissions model
2.  Introduced Multisignature accounts and transactions
3.  Developed MVP of client library in Java
4.  Simplified network startup with genesis block
5.  Multiple usability improvements and bug fixes

We kept our bi-weekly community calls going - some of the interesting
presentations are in our wiki. 

# Current Plans

Iroha 1 plans:

1.  Finish version migration feature
2.  Introduce KV database
3.  Replace rxcpp dependency with custom subscription engine

Overall, we plan to stay on the same path: stabilising and improving
Iroha v1, maintain it and work on Iroha v2's new features. We want to
keep the communication with our amazing contributors and help others use
Iroha for their projects. Hopefully, we will also be able to make some
interesting content about how to use Iroha. 

# Maintainer Diversity

One new Rust developer for Iroha 2 project - Ivan Rybin. 

Sonoko Mizuki is an independent contributor maintainer to Iroha 2

# Contributor Diversity

diva.exchange team is still contributing a lot into Iroha, as well as
Baziorek. Also, please see maintainer diversity regarding this. 

# Additional Information

Nothing special at the moment. 

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
-   ✅ <span class="placeholder-inline-tasks">
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
<td><span id="comment-41592362"></span>
<p>You may want to link  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Firoha/dashboard" class="external-link" rel="nofollow">https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Firoha/dashboard</a>
.</p>
<p>Thanks!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Feb
09, 2021 21:05 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41592479"></span>
<p>Answering the questions</p>
<ol class="incremental">
<li>We would love to have project maintainers attend the TSC meetings.
But we have this as an open question. Solutions could be meeting
recordings, mailing list subscription, regular meeting, Rocket.Chat all
of which are great for healthy community.</li>
<li>2 quarters from now.</li>
</ol>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Feb 11, 2021 14:49 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41592480"></span>
<p>Just a curious question: The summary that states V1 team and V2 team
is interesting. Are those two different protocol implementation in V1
and V2, or is it a major breaking change? I would be interested in Iroha
team presenting to the TSC  <img src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Feb 11, 2021 14:52 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41592527"></span>
<p>FYI, we discussed your questions on the TSC call and I can offer the
following info:</p>
<ol class="incremental">
<li>The volume of email on the TSC list is actually quite low and
shouldn't create a barrier for anyone to follow but as far as
resolutions are concerned the best is to check <a href="https://wiki.hyperledger.org/display/TSC/TSC+Meetings+2021" rel="nofollow">the records of the meetings</a> and <a href="https://wiki.hyperledger.org/display/TSC/TSC+Decision+Log" rel="nofollow">the decision log</a> .</li>
<li>As Arun pointed out, this was set to the second quarter but we're
still working on the details on implementing the repolinter
resolution.</li>
</ol>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Feb
11, 2021 16:20 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41592572"></span>
<p>Hello Arun! </p>
<p>I am extremely sorry I missed today's meeting and it is totally my
fault and not the team's - I usually present each update personally. I
am ready to answer all the questions here though, or on the next meeting
if there is time. </p>
<p>Regarding the 2 teams - yes, Iroha v2 is on Rust which was welcomed
by the community, so it makes sense to have 2 teams. </p>
<p>We could present this on one of the next meetings, if you like  <img
src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /> </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Feb
11, 2021 22:10 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41592573"></span>
<p>Hello Arnaud and thank you!</p>
<p>I tried to follow the email list but I missed the solution regarding
the renaming of the branches, that is why I thought that maybe there is
some sort of a newsletter with critical level information for the
projects.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Feb
11, 2021 22:15 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41592574"></span>
<p>I tried a few times to open the link but it is only infinitely
loading. Could you please clarify if I am doing something wrong and wh"at does this link leads to? Should I wait a little more (it's been loading
for about 10 minutes now)?</p>
<p><br />
</p>
<p>upd: not working from Germany but US VPN helped  <img
src="emoticons/wink.svg" class="emoticon emoticon-wink" data-emoticon-name="wink" alt="(wink)" /> </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by SaraG at Feb
11, 2021 22:26 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41592592"></span>
<p>I face similar issue in India. Another issue that I face is that it
expects me to login sometimes.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Feb 12, 2021 03:36 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41592593"></span>
<p>Thank you  <img src="emoticons/smile.svg" class="emoticon emoticon-smile" data-emoticon-name="smile" alt="(smile)" /> I will look forward to it. If there is a video
available I am happy to go through it as well.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Feb 12, 2021 03:38 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41592922"></span>
<p>That is incredibly weird.  I have no idea why it would be
geographically restricted, but oh well.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Feb
17, 2021 19:26 </div ></td>
</tr>
</tbody>
</table>




