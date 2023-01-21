---
layout: default
title: 2019 Q3 Hyperledger Fabric
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q3 Hyperledger Fabric

Created by Christopher Ferris, last modified by Mic Bowman on Jul 25, 2019

# Project

Hyperledger Fabric

# Project Health

Fabric continues to grow and mature. Our  <a href="https://lists.hyperledger.org/g/fabric/topic/announcement_hyperledger/32537763?p=,,,20,0,0,0::recentpostdate%2Fsticky,,,20,2,0,32537763" class="external-link" rel="nofollow">v1.4.2</a> release was delivered on
July 22nd. We have experienced a slight increase in the diversity of
contributors with IBM comprising 39.6% of the contributors over the past
quarter (-3.4%), though we are still looking to increase diversity of
the maintainers.

# Issues

As noted, while the diversity of contributions and contributors is
increasing, we need to do better. We know that we need to be more
responsive to CRs coming from new contributors and the maintainers are
looking to make this a priority. We are also seeking to grow diversity
of maintainer-ship, however, this is an earned designation that comes
from having non-maintainers performing sustained and constructive code
reviews (augmenting the maintainers, and often serving as a triage).

# Releases

As noted, we released v1.4.2 last week with the major new feature being
the migration from Kafka to Raft consensus. We are hoping that operators
will take advantage of the new migration capability to move off of the
more complex Kafka deployments.

# Overall Activity in the Past Quarter

There are a good mix of questions in chat, email and on 
<a href="https://stackoverflow.com/questions/tagged/hyperledger-fabric" class="external-link" rel="nofollow" title="https://stackoverflow.com/questions/tagged/hyperledger-fabric">Stackoverflow</a>
 – now over <span style="color: rgb(36,39,41);">4k </span> questions (an
increase of over 400 since April) for the 'hyperledger-fabric' tag, with
the majority being answered. The questions themselves continue to be
increasingly sophisticated, which is also a good sign.

There has also been a good deal of new major contributions being
proposed and started. Fabric performance (which for a DLT is actually
pretty decent) is receiving lots of interest with various proposals for
optimizations that can yield significant performance improvements.
Additionally, there's ongoing work on a new command-line interface and
more.

# Current Plans

We are looking next at the <a href="https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=11700" class="external-link" rel="nofollow">2.0 release</a> , and over the next
couple of weeks we hope to firm up plans for exactly when (and what) we
deliver 2.0.

# Maintainer Diversity

<a href="https://gerrit.hyperledger.org/r/c/fabric/+/31934" class="external-link" rel="nofollow">Added Jay Guo</a> , IBM for his
contributions to the Raft consensus and demonstrated consistent
constructive reviews over a sustained period.

# Contributor Diversity

We have experienced a slight increase in the diversity of contributors
with IBM comprising 39.6% of the contributors over the past quarter
(-3.4%), though we are still looking to increase diversity of the
maintainers. Number of organizations represented increased by 2.

# Additional Information

The CI/CD proposal from the CI/CD committee was reviewed in this week's
bi-weekly Fabric Contributors meeting and there was general consensus
that CircleCI would be adequate for our needs (though someone did raise
the issue of successive patches that Gerrit handles well, but for which
GitHub requires a manual hack). The maintainers plan a vote on adoption
of the proposed CircleCI approach that was prototyped for the fabric
repository.

# Reviewed by
-   ✅ <span style="color: rgb(0,0,0);">Arnaud Le Hors </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Baohua Yang </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Binh
Nguyen </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Christopher Ferris </span> </span></span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Dan Middleton </span> </span> </span></span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Hart
Montgomery </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Kelly Olson </span> </span> </span></span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mark
Wagner </span> </span> </span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Mic Bowman </span> </span> </span></span> </span> </span> </span> </span>
-   ✅ <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Nathan George </span> </span> </span></span> </span> </span> </span> </span>
-   🔲 <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);"> <span style="color: rgb(0,0,0);">Silas Davis </span> </span> </span></span> </span> </span> </span> </span>






