---
layout: default
title: 2023 Q4 Hyperledger Fabric
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q4 Hyperledger Fabric

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

LTS releases:
- v2.5 is the current LTS release with patch releases approximately quarterly.
- v2.2 is the prior LTS releases, critical fixes will be backported through 2023.

The Fabric [v2.5 announcement](https://lists.hyperledger.org/g/fabric/message/11754) encouraged users to upgrade to v2.5 so that they can keep getting fixes and updates that will eventually be targeted for v2.5.x releases only.
The announcement also indicated that the legacy Fabric SDKs (known as Fabric SDK for Node v2.2, Fabric SDK for Java v2.2, Fabric SDK for Go v1.0) are deprecated.
Users of the legacy SDKs are encouraged to evaluate the Fabric Gateway client API as a replacement.
The Fabric Gateway client API is the recommended SDK for client applications when using Fabric v2.4 or v2.5, and is available in Go, Node, and Java programming languages.

[Releases](https://github.com/hyperledger/fabric/releases) past quarter:

- Fabric v2.2.13 - August 2, 2023
- Fabric v2.5.3 - June 14, 2023
- Fabric v2.5.4 - August 2, 2023
- Fabric v3.0.0-preview - September 1, 2023

# Overall Activity in the Past Quarter

The project delivered fixes to the Fabric v2.2 (prior LTS) and v2.5 (current LTS) releases. See [release notes](https://github.com/hyperledger/fabric/releases) for details.

A v3.0.0-preview release was created to gather feedback on the new SmartBFT consensus algorithm that is being developed for the Fabric ordering service (main branch).

An initial v0.0.0 of Go [fabric-admin-sdk](https://github.com/hyperledger/fabric-admin-sdk) has been released to help with programatic channel and chaincode management.
The project is evaluating the use of this admin SDK in a new and improved [fabric-cli](https://github.com/hyperledger/fabric-cli) that may eventually replace the original peer CLI commands.

The Hyperledger Fabric Certified Practitioner exam has been released.

# Current Plans

The project expects to maintain and support v2.5 for an extended time period
and encourages all users to upgrade to v2.5 so that they can keep getting fixes that will eventually be targeted for v2.5 only.
There are upcoming fix releases for v2.2.14 and v2.5.5.

Concerning v3.0, plan is to get feedback on the v3.0.0-preview release with the SmartBFT feature, and also refactor the ordering service
so that there will be one orderer binary per consensus algorithm, which will be much more
extensible than the current approach of having one orderer binary that supports N consensus algorithms.
The project intends to refactor other code as well in an eventual v3.0 release,
and also remove some of the heritage features that have already been announced as deprecated in the [v2.x release notes](https://github.com/hyperledger/fabric/releases/tag/v2.5.0).
The refactoring work will take significant time, therefore most users are encouraged to use v2.5 which will be maintained and supported for an extended time period.

# Maintainer Diversity

7 of 8 [maintainers](https://github.com/hyperledger/fabric/blob/main/MAINTAINERS.md) from IBM.

There is a good pipeline of potential maintainers as the project has seen increased contributions from organizations such as Hitachi, Oracle, GoLedger, and IntellectEU.


# Contributor Diversity

Year to year comparison, by commit:

- Q3 2022 - 320 commits. 72% from IBM.
- Q3 2023 - 177 commits. 61% from IBM.

Year to year comparison, by contributor:

- Q3 2022 - 47 contributors. 36% from IBM.
- Q3 2023 - 36 contributors. 33% from IBM.

# Additional Information

[Insights dashboard link](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222023-07-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-10-01T05:00:00.000Z%22%7D)
