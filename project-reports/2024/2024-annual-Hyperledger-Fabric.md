---
layout: default
title: 2024 Annual Review Hyperledger Fabric
parent: 2024
grand_parent: Project Updates
---

# Project Health

Hyperledger Fabric is fairly mature and stable with a v2.5 Long-term support (LTS) release.
There is less churn and fewer commits than in years past, with continued focus on quality and support.
New features get proposed, approved, and implemented based on a community RFC process.
Mailing list activity is down a bit compared to prior years.
PRs and mailing list questions are generally turned around quickly.
There is significant Discord activity.

[LFX Insights report for 2023](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=fabric&bestPractice=false&repository=&dateFilters=Last%20Year&dateRange=2023-01-01%20to%202023-12-31&compare=PP&granularity=month&hideBots=true)

Highlights from the 2023 Insights report:
- 392 contributors (-32% from 2022)
- 1295 commits (-39% from 2022)
- 52% of code activities were performed by 5 people (from IBM)
- 81% of code activities were performed by 1 organization (IBM)
- Total of 112 organizations contributed, which indicates that there are many contributors and organizations with small contributions

Top 5 contributing organizations:
1. IBM (79.48%)
2. Hitachi, Ltd (4.92%)
3. Hyperledger Labs (4.49%)
4. Eternyze IT Services (3.37%)
5. Oracle Corporation (1.58%)

# Maintainer Diversity

Majority of maintainers are from IBM, but there is some good progress towards more diversity:
- 7 of 8 maintainers of core Fabric are from IBM (6 of 8 were IBM in 2022)
- 1 IBM maintainer has been inactive for 3 months and is therefore a candidate for retirement.
- 1 Hitachi contributor and 1 Oracle contributor have become significantly more active in second half of 2023 and are therefore on a path towards becoming maintainers.

While there are many small contributors from various organizations, we'd like to encourage them to make larger contributions and work towards becoming a maintainer.

[Maintainers file for core Fabric](https://github.com/hyperledger/fabric/blob/main/MAINTAINERS.md)

# Project Adoption

Based on what we see in mailing list and Discord there is significant adoption activity.
Several large vendors and several smaller companies have commercial offerings based on Hyperledger Fabric, as well as consulting services.

# Goals

## Performance Against Prior Goals

2023 goals:
- Release Fabric v2.5 as the next long-term support (LTS) release (COMPLETED)
- Make progress towards a Fabric v3.0 release wth byzantine fault tolerant ordering service (COMPLETED - v3.0.0-preview released)
- Shift CI from Azure Pipelines to Github Actions in all repositories (COMPLETED)
- Create a Hyperledger Fabric Certified Practitioner exam (COMPLETED)
- Increase diversity of maintainers (IN PROGRESS)

Other noteworthy accomplishments in 2023:
- [Fabric Ecosystem guide](https://wiki.hyperledger.org/display/fabric/Ecosystem)
- Initial [fabric-admin-sdk](https://github.com/hyperledger/fabric-admin-sdk) implementation for chaincode and channel management

## Next Year's Goals

2024 goals:
- Shift users to Fabric v2.5 as the actively maintained long-term support (LTS) release, and to Gateway SDKs as the actively maintained SDKs
- Provide maintenance releases at least quarterly
- Release Fabric v3.0 with a production quality byzantine fault tolerant ordering service
- Increase diversity of maintainers

## Help Required

We continue to work with Hyperledger staff to identify contributors and potential maintainers outside of IBM.

# Project Lifecycle Stage Recommendation

Graduated status still makes sense for Hyperledger Fabric.
