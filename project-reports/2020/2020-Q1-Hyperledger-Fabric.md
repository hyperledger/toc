---
layout: default
title: 2020 Q1 Hyperledger Fabric
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q1 Hyperledger Fabric

Created by Christopher Ferris, last modified by Gari Singh on Feb 07, 2020

# Project

## Hyperledger Fabric

# Project Health

Fabric continues to grow and mature. Our v1.4.4 release was delivered
mid-November and v2.0-beta mid-December. We have experienced a slight
decrease in the diversity of contributors with IBM comprising 41.7% of
the contributors over the past quarter (-1.3%). All of the main project
repositories have been transitioned to GitHub from Gerrit, and the CI/CD
has also been transitioned to Azure Pipelines. Hopefully the new GitHub
contributions will make it easier to attract and retain new
contributors. We also discussed changes to the documentation review
process to allow for greater diversity of maintainers who are focused
primarily on the documentation, given that much of that work has been
done in the Fabric Documentation WG, but not visible to the commit
review process.

# Questions/Issues for the TSC

Diversity of maintainers and contributors improved slightly this past
quarter. New documentation maintainers team created that should enable
those focused exclusively on documentation to become more involved in
the review process for documentation.

# Releases

As noted, we released v1.4.4 mid-November with some minor enhancements
to address administrative issues. We also bumped the versions of Go and
Node. We released v2.0-beta mid December that incorporates the new
chaincode lifecycle, a new chaincode launching mechanism, some
performance improvements, and improvements to private data that enable
new decentralized application patterns. There was also some considerable
refactoring of the validation pipeline which necessitated removing the
FabToken feature that was previewed in v2.0-alpha. We do plan to revisit
the token design in the coming releases post 2.0. Additionally, there
was a large amount of tech debt addressed in the areas of automated
test, CI, and code cleanup. We plan to formally release v2.0 next week
given that the testing of v2.0-beta has gone well.

# Overall Activity in the Past Quarter

There were 790 commits from 90 engineers representing 20 entities in the
past quarter. Mailing list activity for the quarter remained fairly
robust at ~225 emails. RocketChat also remained quite active.
<a href="https://stackoverflow.com/questions/tagged/hyperledger-fabric" class="external-link" rel="nofollow">StackOverflow</a> also added
another 300 questions, remaining a very popular means of engagement.

# Current Plans

The maintainers have adopted an RFC process to manage new feature
discussion and agreement.The new
<a href="https://github.com/hyperledger/fabric-rfcs/" class="external-link" rel="nofollow">fabric-rfcs</a> repo holds the
specifics, and there's a
<a href="https://hyperledger.github.io/fabric-rfcs/" class="external-link" rel="nofollow">splash page</a> that makes
navigating the substance easier.

The maintainers plan to continue the quarterly release strategy post
v2.0, and there will likely be a v1.4.5 in February continuing the LTS
support.

The maintainers are also in the process of revising the LTS strategy for
Fabric. It was felt that we need to continue LTS support for the 1.4
release stream until we feel comfortable that the feature set for a new
LTS release is worth making a new (and overlapping) LTS commitment.
Current thinking is that we hope to have v2.2 at end of Q2 become the
next LTS release, and that there will be an overlapping of LTS support
for the 1.4 release stream. Expect an RFC outlining the new LTS strategy
once v2.0 has been released.

# Maintainer Diversity

As noted, we have modified the documentation review process to enable
those who are focused on docs to contribute. As such we have added
additional maintainers for the docs tree including one non-IBMer. Again,
we continue to encourage others to engage in reviewing PRs with the
hopes that we can add more.

# Contributor Diversity

We have experienced a slight increase in the diversity of contributors
with IBM comprising 41.7% of the contributors over the past quarter
(-1.7%). We are still actively interested in growing contributions and
expect the transition from Gerrit to GitHub will lower the barrier for
contributions.

# Additional Information

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
<td><span id="comment-29032550"></span>
<p>Thanks for the nice report.  Would it be possible to get more
detailed information on the contributor statistics, particularly by company?  I'm hoping for things like contributors/company, lines of
code/ company, commits/company, or stuff like that.</p>
<p>The reason for this is as follows:  personally, I'd like to advocate
for more resources at my company for Hyperledger.  The more statistics I
have that show how much other companies are doing (and how relatively
little we are doing), the easier this case is to make to management. 
Thanks!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Jan
23, 2020 01:57 </div ></td>
</tr>
</tbody>
</table>




