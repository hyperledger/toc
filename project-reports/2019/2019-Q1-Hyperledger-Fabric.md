---
layout: default
title: 2019 Q1 Hyperledger Fabric
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q1 Hyperledger Fabric

Created by Christopher Ferris, last modified by Brian Behlendorf on Jan 31, 2019

# Project Health

Fabric continues to grow and mature. Our v1.4 LTS (Long Term Support)
release was delivered on January 11th. We have experienced a slight
increase in the diversity of contributors with IBM comprising 45% of the
contributors over the past quarter (-4%).

There are a good mix of questions in chat, email and on
<a href="https://stackoverflow.com/questions/tagged/hyperledger-fabric" class="external-link" rel="nofollow" title="https://stackoverflow.com/questions/tagged/hyperledger-fabric">Stackoverflow</a>
– now 3,450 questions (an increase of ~500 since October) for the
'hyperledger-fabric' tag, with the majority being answered. The
questions themselves continue to be increasingly sophisticated, which is
also a good sign.

There has also been a good deal of new major contributions being
proposed and started. Fabric performance (which for a DLT is actually
pretty decent) is receiving lots of interest with various proposals for
optimizations that can yield significant performance improvements.
Additionally, there's ongoing work on a new command-line interface and
more.

# Issues

One issue that has been addressed recently is the aging of Gerrit CRs.
Often times, when someone submits a CR, there is no follow-up of review
comments, or someone submits a draft CR and lets it linger in the CR
backlog. This can be a turn-off for new contributors. Hence we have
adopted a new CR aging policy that will endeavor to apply some objective
criteria and automatically abandon CRs after they have been idle for two
successive 2-week periods without activity (note that the policy is in
force, the automation still needs to be implemented).

# Releases

As noted, Hyperledger Fabric 1.4 LTS was released on January 11th. This
is the project's first long term support release. What this means for
users is that the maintainers pledge to back port fixes to this release
for one year. We hope that this will give users confidence in deploying
to more production contexts.

# Overall Activity in the Past Quarter

email traffic dipped in the last month of 4Q, but remains strong. The
RocketChat traffic seems to have increased as well, but there are so
many channels to track it is hard to get a sense for how much of an
increase there's been.
<a href="https://stackoverflow.com/questions/tagged/hyperledger-fabric" class="external-link" rel="nofollow" title="https://stackoverflow.com/questions/tagged/hyperledger-fabric">Stackoverflow</a>
traffic icontinues apace, reaching over 3,500 questions, an increase of
over 500 in the last quarter.

# Current Plans

With version 1.4 LTS just released, the project is working on 1.4.1 and
2.0.0 releases. The project maintains a
<a href="https://wiki-archive.hyperledger.org/projects/fabric/roadmap" class="external-link" rel="nofollow" title="projects:fabric:roadmap">release roadmap</a> , and maintains a <a href="https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=10104" class="external-link" rel="nofollow">JIRA dashboard</a> to track
specific items.

v2.0.0 is the 2019 target release for more substantial new features,
including an enhanced chaincode lifecycle, a raft consensus mechanism
(stepping stone to full BFT ordering service), and deeper token support.

We hold playback meetings for design reviews and intend to continue
regular maintainer hangouts (see community calendar) every other week to
track the release plan's progress against objectives.

# Maintainer Diversity

Maintainer diversity was static though there is potential on the
horizon.

# Contributor Diversity

As previously noted, contributor diversity grew in 4Q. IBM now
represents 45% of the contributors with some new more substantial
contributions being proposed.

# Additional Information

n/a



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-5505200"></span>
<p>Question... what is the barrier to developing the BFT ordering
service? Is there a particular architectural challenge or is it just a
prioritization of features/development resources?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by MicBowman at Jan 31, 2019 15:53 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-6423308"></span>
<p>No specific barrier. Fabric ordering service was designed so th"at various consensus algos could be plugged in but this had never really
been tested. When the team started looking into implementing BFT they
realized the API wouldn't quite cut it so they decided to implement RAFT
as a first step. The idea is that the revised API will then be more
suitable to implementing BFT and having RAFT also provides for a lighter
alternative to KAFKA.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Feb
07, 2019 07:59 </div ></td>
</tr>
</tbody>
</table>




