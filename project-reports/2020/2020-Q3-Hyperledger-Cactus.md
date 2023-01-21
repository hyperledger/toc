---
layout: default
title: 2020 Q3 Hyperledger Cactus
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q3 Hyperledger Cactus

Created by Jonathan Hamilton, last modified by Gari Singh on Oct 22, 2020

# <span style="letter-spacing: 0.0px;">Hyperledger Cactus Quarterly Report </span>

# Project Health

Cactus continues to build momentum and has a solid group of sustained
contributors, in addition to the core Maintainers.    We have presented
at several Hyperledger meetups, including the Tokyo & London meetups,
which had significant turnout (&gt;50) attendees) despite Covid /
virtual setup.  We also presented at multiple sessions of the
Hyperledger Member summit and solicited further interest there. 
Ultimately, while we aspire to further community involvement, we see the
project participation growing at a moderate and manageable pace.

# Questions/Issues for the TSC

We don't have any issues or questions for the TSC at this time.  As we
roll out interfaces for different Hyperledger blockchains, though, we
would appreciate reviews and comments from people affiliated with said
blockchains.  So please expect contact from us in the future!

# Releases

We have made material progress towards a 0.2 Release, but have yet to
finalize the scope.  The project's aspirations are well articulated in
the whitepaper, but not yet clearly mapped across release milestones. 
Therefore, we will put extra focus into roadmapping out key features
early in Q4 and soliciting community inputs to guide our release
objectives.

# Overall Activity in the Past Quarter

- We have explored and initiated the development of Ursa being
compiled to Javascript (which we intend to use in Cactus which is a
NodeJS+Browser project at heart)
- Researched the security aspect of the plugin architecture from the
point of view that malicious plugins could be installed if someone
tricked the administrators of a Cactus node to do so. Special thanks
to <a href="https://wiki.hyperledger.org/display/~cliveb" class="confluence-userlink user-mention" data-username="cliveb" data-linked-resource-id="6429493" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Clive Boulton</a> for
bringing this up to begin with and the continued support during our
exploration
- Created a fabric all in one (AIO) docker container image and the one
for corda is not far behind. These allow us to have self-contained
test automation where each test case can be pulled up with a brand
new, clean slate ledger if necessary.
- The ledger connectors are not far behind from being completed
either, but we still have some kinks to work out and alignment
to make among the maintainers as to how exactly we would want
them to fit into the current architecture of the project so this
part is still work in progress.
- The fabric AIO image still has a to do item for it regarding the
peer containers port mapping functionality. This is not a
blocker issue because we can restrict the test execution to
one-at-a-time instead of parallel execution and therefore the
randomized port publishing feature of Docker is not necessary
for the fabric AIO container to work properly.
- In the spirit of open source, we contributed to other (non
Hyperledger) projects while in the process of developing certain
features for Cactus itself (OpenAPI generator, webpack to name a
couple)
- Introduced an initial implementation of a cross-platform (NodeJS,
Browser) signature generation and validation component. 
- We intend this to be superseded by the Ursa Javascript build
once that is available on npm as a package (stay tuned) 
- Initiated the draft for a research paper we'll write collaboratively
as a team. Special thanks to 
<a href="https://wiki.hyperledger.org/display/~RafaelAPB" class="confluence-userlink user-mention" data-username="RafaelAPB" data-linked-resource-id="6426601" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Rafael Belchior</a> for
organizing.

# Current Plans

Our plans are essentially the following:

1. Make headway with the performance benchmarks as the research paper
depends on this as well
2. Make progress on the research paper's first edition
3. Merge all of the functionality from the Fujitsu and Accenture
solutions into our plugin architecture.
1. In-Progress
4. Add functionality for immediately needed use cases
1. Comprehensive examples for said use cases
5. Design future architectures for things that are needed to scale
Cactus to bigger use cases, such as identity management.

# Maintainer Diversity

We currently have four maintainers.  They are:

Shingo Fujimoto – Fujitsu

Jonathan Hamilton – Accenture

Peter Somogyvari – Accenture

Takuma Takeuchi – Fujitsu

We are more than open to adding additional maintainers outside of the
core Accenture/Fujitsu group, and hopefully in the not too distant
future.

# Contributor Diversity

We recommend the following for detailed contributor information:  
<a href="https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard" class="external-link" rel="nofollow">https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard</a>
.  Thanks Ry!

That being said, our contributors are as follows:

Rafael Belchior – Technico Lisboa

Patrick Erichsen – Target

Shingo Fujimoto – Fujitsu

Jonathan Hamilton – Accenture

Tracy Kuhrt – Accenture

Hart Montgomery – Fujitsu

Sownak Roy – Accenture

Peter Somogyvari – Accenture

Takuma Takeuchi – Fujitsu

Doris Benda

Dilum Bandara

程阳 – Aliyun

Suyu Ku - Accenture

Jacob Weate - Accenture

# Additional Information

Thanks for reading this!  

# Reviewed by
- ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
- 🔲 <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
- ✅
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
- ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>


## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41584309"></span>
<blockquote>
<p>We have explored and initiated the development of Ursa being compiled
to Javascript</p>
</blockquote>
<p>You may want to consider trying WebAssembly rather than rewriting /
compiling to JavaScript.  This would actually work for both browsers and
NodeJS, although you can also consider a native module for NodeJS.  This
would allow you to leverage a majority of the Rust code and focus on
wrappers.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by mastersingh24
at Oct 22, 2020 14:14 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41584348"></span>
<p>Thank you Gari! We have indeed swerved onto the Web Assembly path
since then, thanks to some help from  <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a> who has
shown me this <a href="https://github.com/mattrglobal/bbs-signatures" class="external-link" rel="nofollow">repo</a>  which demonstrates a
working solution of pretty much everything (from the build/tooling
standpoint) that we'd need (Node+Browser as you mentioned and the
ability to work with Webpack as well). </p>
<p>Node native addons is very tempting because it would reduce upfront
effort of just having something that works at least on the back-end, but
we definitely want something universal (Node+Browser) right out of the
gate so that certain common APIs are callable in browser applications as
well. The other thing that speaks against Node native addons is th"at they can break across versions/OSs, basically losing out on the benefits
of Javascript in this sense.</p>
<p>Here's a link to a GH issue where we've been conversing about some
finer details as well, in case you are interested. We welcome everyone
to chip in to the discussion:  <a href="https://github.com/hyperledger/cactus/issues/296" class="external-link" rel="nofollow">https://github.com/hyperledger/cactus/issues/296</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by k93uwmrkxc3j5fr78wy7myj8k76p9c at Oct 22, 2020 16:11 </div ></td>
</tr>
</tbody>
</table>




