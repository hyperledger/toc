---
layout: default
title: 2024 Q3 Hyperledger Fabric
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2024 Q3 Hyperledger Fabric

# Project Health

Hyperledger Fabric is fairly mature and stable with a v2.5 long-term support (LTS) release.
There is less churn and fewer commits than in years past, with continued focus on quality, maintenance, and support.
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
- Fabric v2.5.8 - May 21, 2024
- Fabric v2.5.9 - June 18, 2024
- Fabric v3.0.0-beta - March 14, 2024

# Overall Activity in the Past Quarter

The project delivered patch releases for the Fabric v2.5 long-term support release. See [release notes](https://github.com/hyperledger/fabric/releases) for details.

v3.0 development is nearing completion. The following enhancements were made this quarter:
- Support for cryptographic algorithm Ed25519 for transaction signing and verification (in addition to the existing ECDSA support).
- SmartBFT automated testing completed.
- Features that were [marked as deprecated in Fabric v2](https://github.com/hyperledger/fabric/releases/tag/v2.5.9) have been removed in preparation for an official Fabric v3 release.

A v2 API became available for Go chaincodes. Essentially, the same API support was maintained while updating protocol buffer bindings to APIv2. Users are encouraged to utilize the v2 API for new Go chaincodes. See the July contributor meeting [recording](https://youtu.be/fytjclm2Rks) for details and see fabric-samples repository for the simple [edit](https://github.com/hyperledger/fabric-samples/blob/main/asset-transfer-basic/chaincode-go/chaincode/smartcontract.go#L7) to utilize v2.

The project added the [OpenSSF Scorecard](https://scorecard.dev/viewer/?uri=github.com/hyperledger/fabric) and improved score in multiple categories.

# Current Plans

The project continues to maintain and keep Fabric v2.5 current.

The project is working on final items for a v3.0 release, namely the removal of the legacy v1 chaincode lifecycle that has been deprecated since v2.0.

The project is updating its charter to align with LF Decentralized Trust. 

# Maintainer Diversity

6 of 9 [maintainers](https://github.com/hyperledger/fabric/blob/main/MAINTAINERS.md) from IBM.

# Contributor Diversity

- 53% of code activities were performed by top 4 contributors. Remaining 47% performed by 185 other contributors.
- IBM contributors accounted for 82% of activity.
- Of top 10 contributors, 7 of 10 from IBM.

In summary, the project remains top-heavy from IBM but has good depth of smaller contributors.

# Additional Information

[Insights dashboard link](https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/overview/github?project=fabric&routedFrom=Github&bestPractice=false&repository=all&dateFilters=2024-04-01%20to%202024-07-01&dateRange=2024-04-01%20to%202024-07-01&compare=PP&granularity=week&hideBots=true)
