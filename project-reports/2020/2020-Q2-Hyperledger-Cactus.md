---
layout: default
title: 2020 Q2 Hyperledger Cactus
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q2 Hyperledger Cactus

Created by Hart Montgomery, last modified by Nathan George on Aug 20, 2020

# <span style="letter-spacing: 0.0px;">Hyperledger Cactus Quarterly Report </span>

# Project Health

As a brand new project, Hyperledger Cactus seems to be building
momentum.  We have had a number of new people (outside of the core
Accenture/Fujitsu group that founded Cactus) participate in our meetings
and, in some cases, even contribute.  We have presented in the
architecture and identity working groups, where we have also garnered a
good amount of project interest.  Mostly, however, we are just thrilled
to be done with the initial bureaucracy around getting a project
approved and set up, and are very happy that we can finally spend most
of our time on the architecture and code.

# Questions/Issues for the TSC

We don't have any issues or questions for the TSC at this time.  As we
roll out interfaces for different Hyperledger blockchains, though, we
would appreciate reviews and comments from people affiliated with said
blockchains.  So please expect contact from us in the future!

# Releases

We have not had any notable releases of the combined Cactus codebase,
although there are previous releases of the BIF and ConnectionChain.  We
hope to have a full Cactus release in the not too distant future.

The releases will be pushed to npm and in a monorepo format but under
the npm scope of  ***@hyperledger*** meaning that the project name will
not be the npm scope but rather just a prefix prior to the package name.
This makes it much wordier for the package names, but the upside is th"at we are consistent with the global Hyperledger npm scope. So the package
names will be like this for exmaple:

-   @hyperledger/cactus-cmd-api-sever,
-   @hpyerledger/cactus-common
-   @hyperledger/cactus-sdk,
-   etc.. 

It is not too late to change the package naming theme if the TSC would
rather have us our own npm scope such as:

-   @cactus/cmd-api-server
-   @cactus/common
-   @cactus/sdk

Which is easier to read (less verbose), but may be confusing to users
who expect all legit Hyperledger projects to publish under the
same @hyperledger npm scope.

# Overall Activity in the Past Quarter

The focus of the project at this point has mostly been getting all of
the infrastructure set up and working on a modular, combined
architecture.  There has been quite a bit of coding going into this as
well, but the priorities have been focused on infrastructure.

# Current Plans

Our plans are essentially the following:

1.  Finalize our plugin architecture, down to minute specifications
needed for implementation.
2.  Merge all of the functionality from the Fujitsu and Accenture
solutions into our plugin architecture.
3.  Add functionality for immediately needed use cases.
4.  Design future architectures for things that are needed to scale
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

That being said, our contributors are (in lexicographical order) as
follows:

Rafael Belchior – Technico Lisboa

Patrick Erichsen – Target

Shingo Fujimoto – Fujitsu

Jonathan Hamilton – Accenture

Tracy Kuhrt – Accenture

Hart Montgomery – Fujitsu

Sownak Roy – Accenture

Peter Somogyvari – Accenture

Takuma Takeuchi – Fujitsu

程阳 – Aliyun


# Additional Information

Thanks for reading this!  

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~ChristopherFerris" class="confluence-userlink user-mention" data-username="ChristopherFerris" data-linked-resource-id="2392402" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Christopher Ferris</a>
-   🔲
<a href="https://wiki.hyperledger.org/display/~dan.middleton@intel.com" class="confluence-userlink user-mention" data-username="dan.middleton@intel.com" data-linked-resource-id="6427025" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Dan Middleton</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~swetharepakula" class="confluence-userlink user-mention" data-username="swetharepakula" data-linked-resource-id="5505323" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Swetha Repakula</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>






