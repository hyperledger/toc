---
layout: default
title: 2024 Annual Review Hyperledger Cacti
parent: 2024
grand_parent: Project Updates
---

# Project Health

[Hyperledger Cacti LFX Insights page](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=cactus&repository=all&dateFilters=Last%20Year&dateRange=2023-01-01%20to%202023-12-31&compare=PP&granularity=month&hideBots=true)

1. We've been (mostly) steadily adding new contributors each month with a quick break during the Summer.
2. The pull request lead time has been reduced to 15 days which is great news, previously this was well above 20, meaning that we've had a 60% decrease overall. 
3. What we especially needed to improve on with pull request lead times was the waiting for review state, in which, pull requests should not spend more than 48 hours according to our self-imposed limit and we are closing in on hitting this milestone with the waiting for review state lasting 2.76 days on average.
4. We've resolved ~670 issues but 1070 were opened. This can be seen through many different lenses. One of them is that more than 30% of the currently open issues are "good first" issues that we mostly keep open as bait for new contributions in order to grow the community.
5. We've produced a consolidated (albeit not completely integrated) documentation website
6. The project received graduated status as of Q3 2023!

# Maintainer Diversity

- We currently have 7 maintainers from 3 different companies and 3 different continents (scheduling synchronous meetings is fun :-))
- The number of maintainers is up from an earlier 6. Our newest maintainer is Michal Bajer from Fujitsu who is doing an excellent job of collaborating with the rest of the maintainers and his presence is a big improvement to code quality!

# Project Adoption

The detailed answer about adoption has been published earlier and can be read through this link:
https://github.com/hyperledger/hyperledger-hip/blob/gh-pages/HIPs/graduated/cacti.md#real-world-use

# Goals

## Performance Against Prior Goals

### Goal: Code Level Integration of Cactus & Weaver

We've made some progress on updating the documentation and more closely integrating the original components (formerly separate code-bases) that now make up the project (all maintainer organizations brought in some code of their own that was originally standalone).
There's more work to be done on this in the new year, but we are more optimistic than ever.

### Goal: Growing the Community

1. We've had interest and actual contributions from multiple new organizations such as Huawei and Infosys.
2. We are working on a closer collaboration with the Harmonia Lab maintainers (R3 & Adhara) as well. 
3. Hosted a successful workshop in mid-November of 2023 describing interop and demonstrating Cacti to a wide audience of devs,
4. Cacti maintainer (Ramakrishna) got invited for a presentation on interop and the Cacti journey in the [Blockchain India TechFest 2023 in Bangalore](https://www.inblockchainweek.com/ibw2023/index.php)

Overall this goal was a success and we expect more to come in the coming year.

## Next Year's Goals

The main theme is to carry on with the integration work with our multi-phase plan:
1. Packaging as a monorepo, 
2. Eliminating and merging redundant packages,
3. Finally consolidating packages as per our target architecture (this may be too ambitious for 2024, given other priorities in the roadmap). 
4. Adding more plugins for other forms of DLTs and also legacy/centralized systems that need to trade assets.

## Help Required

We could use the help of the community at large and the TOC specifically as well in
encouraging and demonstrating more reuse and interdependence of Hyperledger projects, especially in terms of using Cacti for interoperability. 
As a precedent, Dave Enyeart's Fabric ecosystem web page (which he started late last year) explicitly mentions Cacti as part of the ecosystem as it helps Fabric interlink with other DLTs.

# Project Lifecycle Stage Recommendation

`Graduated`