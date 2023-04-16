---
layout: default
title: 2023 Q2 Hyperledger Fabric
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q2 Hyperledger Fabric

# Project Health

Hyperledger Fabric is fairly mature and stable with a new v2.5 Long-term support (LTS) release.
There is less churn and fewer commits than in years past, with continued focus on quality and support.
New features get proposed, approved, and implemented based on a community RFC process.
Mailing list activity is down a bit compared to prior years.
PRs and mailing list questions are generally turned around quickly.
There is significant Discord activity.

# Questions/Issues for the TOC

None.

# Releases

LTS releases:
- v2.5 is the current LTS release with patch releases approximately quarterly.
- v2.2 is the prior LTS releases, critical fixes will be backported through 2023.

The Fabric [v2.5 announcement](https://lists.hyperledger.org/g/fabric/message/11754) encouraged users to upgrade to v2.5 so that they can keep getting fixes and updates that will eventually be targeted for v2.5.x releases only.
The announcement also indicated that the legacy Fabric SDKs (known as Fabric SDK for Node v2.2, Fabric SDK for Java v2.2, Fabric SDK for Go v1.0) are deprecated.
Users of the legacy SDKs are encouraged to evaluate the Fabric Gateway client API as a replacement.
The Fabric Gateway client API is the recommended SDK for client applications when using Fabric v2.4 or v2.5, and is available in Go, Node, and Java programming languages.

[Releases](https://github.com/hyperledger/fabric/releases) past quarter:

- Fabric v2.2.10 - February 17, 2023
- Fabric v2.4.8 - January 26, 2023
- Fabric v2.4.9 - March 1, 2023
- Fabric v2.5.0 - March 31, 2023

Fabric CA

- Fabric CA v1.5.6 - March 31, 2023

# Overall Activity in the Past Quarter

The project delivered a new v2.5.0 LTS release this quarter with the following improvements:
- Purge Private Data History feature that helps organizations meet GDPR requirements with the ability to delete private data while preserving a hash of the data on the blockchain.
- ARM support was added for Fabric binaries and images to help with the rising prevalence of Mac M1 ARM architecture in the developer community.
- Upgraded to Go 1.20 and other dependency updates to keep on a good footing with respect to dependency vulnerabilities.

The project delivered fixes to the Fabric v2.2 (prior LTS) and v2.4 releases. See [release notes](https://github.com/hyperledger/fabric/releases) for details.

SmartBFT consensus algorithm has been integrated into the Fabric ordering service (main branch) for an eventual Fabric v3.0 preview release.

Fabric v2.5 performance study led to a [performance blog](https://www.hyperledger.org/blog/2023/02/16/benchmarking-hyperledger-fabric-2-5-performance) and [performance considerations documentation](https://hyperledger-fabric.readthedocs.io/en/latest/performance.html).

Work continues on [fabric-admin-sdk](https://github.com/hyperledger/fabric-admin-sdk) that will help with programatic channel and chaincode management. Targeting a Go SDK first.

Additional Fabric repositories have shifted CI from Azure Pipelines to Github Actions.

# Current Plans

The project expects to maintain and support v2.5 for an extended time period
and encourages all users to upgrade to v2.5 so that they can keep getting fixes that will eventually be targeted for v2.5 only.

Fabric v3.0 release development has started with initial SmartBFT consensus integration.
The project intends to release a `preview` release so that users can try out the initial SmartBFT feature.
The plan is to get feedback on the SmartBFT feature, and also refactor the ordering service
so that there will be one orderer binary per consensus algorithm, which will be much more
extensible than the current approach of having one orderer binary that supports N consensus algorithms.
The project intends to refactor other code as well in an eventual v3.0 release,
and also remove some of the heritage features that have already been announced as deprecated in the [v2.x release notes](https://github.com/hyperledger/fabric/releases/tag/v2.5.0).
The refactoring work will take significant time, therefore most users are encouraged to use v2.5 which will be maintained and supported for an extended time period.

# Maintainer Diversity

7 of 8 [maintainers](https://github.com/hyperledger/fabric/blob/main/MAINTAINERS.md) from IBM. Jay Guo retired (non-IBM), Yoav Tock (IBM) added.

# Contributor Diversity

Year to year comparison, by commit:

- Q1 2022 - 326 commits. 79% from IBM.
- Q1 2023 - 439 commits. 84% from IBM.

Year to year comparison, by contributor:

- Q1 2022 - 65 contributors. 35% from IBM.
- Q1 2023 - 52 contributors. 31% from IBM.

# Additional Information

https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222023-01-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-04-01T05:00:00.000Z%22%7D
Insights dashboard link
