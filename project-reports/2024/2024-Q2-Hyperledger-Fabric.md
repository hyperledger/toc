---
layout: default
title: 2024 Q2 Hyperledger Fabric
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2024 Q2 Hyperledger Fabric

# Project Health

Hyperledger Fabric is fairly mature and stable with a v2.5 Long-term support (LTS) release.
There is less churn and fewer commits than in years past, with continued focus on quality and support.
New features get proposed, approved, and implemented based on a community RFC process.
Mailing list activity is down a bit compared to prior years.
PRs and mailing list questions are generally turned around quickly.
There is significant Discord activity.

# Questions/Issues for the TOC

None.

# Releases

LTS release:
- v2.5 is the current LTS release with patch releases at least quarterly.
- Note that v2.2 has reached end of maintenance and all users are encouraged to update to v2.5 to continue receiving fixes and security updates.

[Releases](https://github.com/hyperledger/fabric/releases) past quarter:

- Fabric v2.2.15 - February 19, 2024 (last v2.2.x release)
- Fabric v2.5.6 - February 19, 2024
- Fabric v2.5.7 - April 15, 2024
- Fabric v3.0.0-beta - March 14, 2024

# Overall Activity in the Past Quarter

The project delivered fixes to the Fabric v2.2 and v2.5 releases. See [release notes](https://github.com/hyperledger/fabric/releases) for details.

The SmartBFT consensus algorithm integration into the Fabric ordering service was completed and delivered in the v3.0.0-beta release in March. The SmartBFT consensus algorithm itself was moved into [hyperledger-labs](https://github.com/hyperledger-labs/SmartBFT).

Also included in the v3.0.0-beta release is a new feature to query all approved chaincodes on a channel.

The last remnants of Azure Pipelines were removed, the transition to Github Actions is now 100% complete, and there was much rejoicing.

# Current Plans

The project continues to maintain and keep Fabric v2.5 current.

The project is working through final items required for a v3.0 release:
- Completion of SmartBFT tests
- Removal of features that were deprecated long ago, e.g. v1 lifecycle, specifying orderer endpoints at global level, configtxgen --outputAnchorPeersUpdate  flag, fabric-tools image
- Channel config updates

# Maintainer Diversity

7 of 9 [maintainers](https://github.com/hyperledger/fabric/blob/main/MAINTAINERS.md) from IBM. A maintainer from Hitachi was added this quarter.

# Contributor Diversity

- 53% of code activities were performed by top 7 contributors. Remaining 47% performed by 180 other contributors.
- IBM contributors accounted for 81% of activity.
- Of top 10 contributors, 6 of 10 from IBM.

In summary, the project remains top-heavy from IBM but has good depth of smaller contributors.

# Additional Information

[Insights dashboard link](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview/github?project=fabric&repository=all&routedFrom=Github&dateFilters=Last%20Quarter&dateRange=2024-01-01%20to%202024-03-31&compare=PP&granularity=week&hideBots=true)
