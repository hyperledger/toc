---
layout: default
title: 2019 Q3 Hyperledger Iroha
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Iroha

Created by Sara Garifullina, last modified by Mark Wagner on Jul 18, 2019

# Project Health

After the production-ready release the community is very active, new
projects start using Iroha as solution for their backend. People
exchange information, help each other, although most of the advanced
help is still on the maintainers. We also receive proposals for new
features from the community members. 

**New features:**  

Configurable validators

Synchronization improvements

Passing updated peer list on initialization

<span class="s1">Peer management options: added RemovePeer command and
GetPeers query </span>

<span class="s1">TLS: client-to-peer and peer-to-peer </span>

CompareAndSetAccountDetail command

Executor Integration Test Framework for testing business logic



We also work closely with HL interns and engaged interns from the
Innopolis University (Innopolis, Russia). Great results are expected. 

<span style="font-size: 24.0px;letter-spacing: -0.01em;">Issues </span>

There are no specific issues at the moment. There are questions such as
diversity and consensus improvements architecture but we are addressing
them already and see progress in that. 

# Releases

<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0" class="external-link" rel="nofollow" style="text-decoration: underline;">Hyperledger Iroha v1.0</a>  on May,
7th

<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.1" class="external-link" rel="nofollow" style="text-decoration: underline;">Release 1.0.1</a>  on June, 24th

# Overall Activity in the Past Quarter

We receive questions through mailing lists from time to time and use
them for sending out important information. Chat channels are much more
active - mostly active members of the community are communicating their
questions and try to help newcomers. There is a very positive experience
of community members starting working on projects together. All the
questions are being answered either by the community members or the
maintainers. 

Currently, we are working on 1.1 version of Iroha that will include new
features such as new queries and permissions as well as refactoring
changes to create a stronger and more secure system. There has been a
slight delay with this release but we are planning to have it as soon as
small fixes are made that prevent it at the moment.

# Current Plans

We have some major plans, currently: consensus improvements, support for
Burrow (EVM) (already in process), support for WASM, improved permission
model (in progress including the ideas from the community), support for
Ursa (also in progress), complex object support, support for
Explorer, improved reporting capabilities using the
database, integration with Polkadot. We also hope to collaborate with
the community more.

# Maintainer Diversity

We have an addition in Iroha team: Eugene Kovalev (architecture
specialist)

# Contributor Diversity

New code contributors: 

<span style="color: rgb(36,41,46);">Alexander Andryukov (
<a href="https://github.com/Exctues" class="external-link" rel="nofollow">https://github.com/Exctues</a> ) </span>

Yash Chaudhary (
<a href="https://github.com/yash2code" class="external-link" rel="nofollow">https://github.com/yash2code</a> )

Alexander Matson (
<a href="https://github.com/alexmat2on" class="external-link" rel="nofollow">https://github.com/alexmat2on</a> ) - HL intern working
on Ursa integration

Ivan Tyulyandin (
<a href="https://github.com/IvanTyulyandin" class="external-link" rel="nofollow">https://github.com/IvanTyulyandin</a> ) - HL intern
working on Burrow integration

Artyom Yurin (
<a href="https://github.com/hyperledger/iroha/pulls/artyom-yurin" class="external-link" rel="nofollow">https://github.com/artyom-yurin</a>
) - Innopolis University intern, working on configuration in the ledger

Ruslan Tushov (
<a href="https://github.com/hyperledger/iroha/pulls/turuslan" class="external-link" rel="nofollow">https://github.com/turuslan</a> ) -
HL intern working on Explorer integration

<span style="color: rgb(36,41,46);">Leonid Lygin  </span>(
<a href="https://github.com/hyperledger/iroha/pulls/ionagamed" class="external-link" rel="nofollow">https://github.com/ionagamed</a>
) - intern from Innopolis University working on TLS





Non-code contributors: 

<a href="https://wiki.hyperledger.org/display/~jsiegrist" class="confluence-userlink user-mention" data-username="jsiegrist" data-linked-resource-id="16320987" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">John Siegrist</a>

<a href="https://wiki.hyperledger.org/display/~sudomann" class="confluence-userlink user-mention" data-username="sudomann" data-linked-resource-id="16321453" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Will Njundong</a>

Bobby Jackson


<span style="letter-spacing: 0.0px;">and other members of the community
from our chats that are not here yet but share their Iroha use
experience helping us as well as sharing their ideas.  </span>



<span style="font-size: 24.0px;letter-spacing: -0.01em;">Additional
Information </span>

Work with interns is going very well so we hope to have integration with
several HL projects very soon thanks to the interns' effort and hard
work as well as helpful guidance from
<a href="https://wiki.hyperledger.org/display/~igor-egorov" class="confluence-userlink user-mention" data-username="igor-egorov" data-linked-resource-id="16320299" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Igor Egorov</a> and 
<a href="https://wiki.hyperledger.org/display/~lebdron" class="confluence-userlink user-mention" data-username="lebdron" data-linked-resource-id="9109570" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Andrei Lebedev</a>  

# Reviewed by
-   🔲 <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span> </span></span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner </span> </span> </span> </span> </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span> </span></span> </span> </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span> </span></span> </span> </span> </span> </span>






