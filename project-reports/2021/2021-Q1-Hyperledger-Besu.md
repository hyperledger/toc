---
layout: default
title: 2021 Q1 Hyperledger Besu
parent: 2021
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2021 Q1 Hyperledger Besu

Created by Grace Hartley, last modified by Arun S M on Apr 29, 2021

# Hyperledger Besu

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Besu remains a strong
project with a growing community network of contributors. This quarter
the team has focused on Ethereum protocol improvements as well as many
performance improvements, included in the Hyperledger Besu 21.1.0
Release, which was launched on February 24th. The team is currently
building towards its Q2 2021 release. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? No,
awaiting final Berlin Mainnet activation then will switch </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://wiki.hyperledger.org/display/TSC/Common+Repo+structure" rel="nofollow">Have you implemented repolinter.json in all your
repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? Yes, via
github actions. </span>

# Questions/Issues for the TSC

We continue to have issues with contributors giving up committing when
encountered with the DCO sign off, especially with  documentation
requests. Any suggestions on how to make the process easier and with
less friction would be appreciated.

One possibility is to relax the DCO check  *within*  the PR for
repositories who only do squash-merges and if the contributor makes a
clear and unambiguous statement in the PR comments that their
contribution conforms to the DCO standards. The commits to any main or
non pull-request branch, however, would still require a DCO 
`Signed-off-by ` line.

# Releases

<span style="color: rgb(23,43,77);">Hyperledger Besu has completed
seven  releases, including the quarterly major release cycle of 21.1.0.
The releases included 20.10.2 on Dec. 16th, 20.10.4 on Jan 13,
21.1.0-RC1 on Jan 27th, 21.1.0-RC2 on Feb 10th, 21.1.0 (full release) on
Feb. 24th, 21.1.1 on March 8th, 21.1.2 on March 15th. We had an extra
release in addition to our regular bi-weekly schedule because we
identified a bug related to the Berlin Hard Fork that we needed to fix.</span>

<span style="color: rgb(23,43,77);">Some functional improvements
include: </span>

**<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">Berlin Network Upgrade  </span> </span>**

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">The team has been preparing Hyperledger
Besu to be compatible with the next Ethereum hard fork, Berlin. The  </span> <a href="https://blog.ethereum.org/2021/03/08/ethereum-berlin-upgrade-announcement/" class="external-link" rel="nofollow" style="text-decoration: none;">Berlin Network upgrade <span> </span></a> <span style="color: rgb(76,76,76);">will include several
improvements to the Ethereum mainnet, such as the addition of
subroutines to the EVM, the introduction of “transaction envelopes”;
which make it easier for Ethereum to support several different kinds of
transactions, and changes in gas costs to increase the security of the
network. </span> </span>

**<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">Mainnet Launcher </span> </span>**

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">Mainnet Launcher makes it easy to create a
config file for an Ethereum client at startup </span> </span>

**<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);">Node Hibernate: </span> </span>**

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);"> This is  a proxy that monitors a node’s
API traffic and hibernates the node when inactive. This reduces
infrastructure costs by ensuring only nodes receiving API requests, or
nodes required to establish consensus are running. </span> </span>

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);"> **Bonsai Tries – Early Access**
Bonsai Tries is a new database format which reduces storage requirements
and improves performance for access to recent state. While this feature
is being developed as a way to deal with mainnet’s large state size, any
network with a comparable state could benefit from it. With Bonsai Tries
instead of a multi-trie key value store, there is one trie, one set of
indexed leafs, and a series of diffs that can be used to move the trie
forward or backwards. This will reduce chain head count and state read
and write amplification from its current 10x-20x levels to 1x-2x for
non-committed access. This feature is early access and may break between
each release, and is hence not production recommended yet. </span></span>

<span style="color: rgb(23,43,77);"> <span style="color: rgb(76,76,76);"> Go to the  
<a href="https://github.com/hyperledger/besu/releases" class="external-link" rel="nofollow" style="text-decoration: none;"><span>Changelog </span></a>   for more
details. </span> </span>

# Overall Activity in the Past Quarter

There have been some significant maintainer contributions from
decentralized maintainers

-   Bonsai Tries by Danno Ferrin in an individual capacity.
-   OpenTracing support langed provided by Antoine Tolume from Splunk.

The remainder of the maintainers have been focusing on continuing
mainnet compatibility work and adding cross-client support for GoQuorum
within the Besu codebase.

# Current Plans

1.  The project team remains currently working towards its 21.4.0
Release, scheduled forJuly of 2021. The 21.4 Release is expected to
include the following features:

2.  1.  London network upgrade
2.  EIP-1559
3.  QiBFT a cross-client BFT algorithm specified by the EEA.

3.  Similar to last quarter, Besu is also continuing to engage with its
community and grow the diversity and decentralization of its
maintainer and contributor base. 

# Maintainer Decentralization

Our maintainer decentralization had a small increase from the prior
quarter. Danno Ferrin has moved from ConsenSys to Reddit, but will
continue to contribute in a personal capacity. David Mechler has moved
to earn.com.

The four organizations include:

-   ConsenSys Quorum (FKA PegaSys)
-   Web3Labs
-   Chainsafe
-   Splunk 

We are in the process of voting on making 3 maintainers emeritus status
and adding 1 new maintainer. There were no other changes to the
maintainer roster.

Prior to the pending actions 5 of 23 (21%) maintainers were
non-ConsenSys. The maintainers breakdown if all the pending actions pass
is:

-   19% non-ConsenSys (4 of 21) - an increase of 3% from last quarter. 

# Contributor Diversity

<span style="text-decoration: none;"> <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fbesu/dashboard?time=%7B%22from%22:%222020-12-08T05:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-03-22T04:00:00.000Z%22%7D" class="external-link" rel="nofollow">LF Analytics for Besu from 8 Dec
2020 to 22 Mar 2021</a> </span>

Commits from  2020-12-08 to 2021-03-22 : 262

Committers from 2020-12-08 to 2021-03-22:  26 (13 non-PegaSys)

Identified Orgs   2020-12-08 to 2021-03-22:  5

# Additional Information

# Reviewed By

-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
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
<td><span id="comment-48758910"></span>
<p>The DCO issue has been something that we have talked about as a TSC
for pretty much forever, but have never really done anything
about.  </p>
<p>Here's my "dream" solution (not necessarily practical):  I've always
maintained that we should tie github IDs to LFIDs.  When you want to
issue a PR, you have to first create an LFID where you list your github
account (note that this linking is not necessarily public–only the LF
needs to know the connection between your LF account and github).  You
can sign some kind of generic DCO when you create an LFID.  When you
want to issue a PR to a HL repository, your github gets checked against
the approved list from the LF.  If you don't have an LFID and try to
create a PR, you are just prompted to get an LFID (which takes a couple
of minutes max, and honestly should be lower friction than dealing with
the DCO).  This also means that repeat contributors only have to deal
with DCO once, which is nice.</p>
<p>This would take a number of changes from not just us but the LF as
well, so it's not totally practical.  But I'd definitely be curious to
see if you all (as the relative newcomers to HL) have some fresh ideas
for DCO.  Thanks for the report!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Mar
22, 2021 21:44 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-48759104"></span>
<p><strong><em><span style="color: rgb(23,43,77);">... contributors
giving up committing when encountered with the DCO sign off</span></em></strong></p>
<p><br />
</p>
<p><span style="color: rgb(23,43,77);">Why are they giving up?</span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by mastersingh24
at Mar 25, 2021 07:08 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-48759132"></span>
<p>Their first PR doesn't have a DCO line, usually because they didn't
read CONTRIBUTING.md, or because they forgot to add the CLI switch or
IDE checkbox. They then see the build errors (because the DCO check in
github from hyperledger validates PRs). one of the maintainers gives the
CLI incantation to add the DCO. Contributor ghosts us.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by shemnon at Mar 25, 2021 13:58 </div ></td>
</tr>
</tbody>
</table>




