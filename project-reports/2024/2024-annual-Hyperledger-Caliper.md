---
layout: default
title: 2024 Annual Review Hyperledger Caliper
parent: 2024
grand_parent: Project Updates
---

# Project Health

[LFX Insights for Hyperledger Caliper](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=caliper&bestPractice=false)

# Maintainer Diversity

[Hyperledger Caliper maintainers](https://github.com/hyperledger/caliper/blob/3fafbf5f3f0048db432792f328643c4e22f7d519/MAINTAINERS.md) in 2024 Q1 (unchanged compared to the previous year):
* Dave Kelsey (IBM UK)
* Attila Klenik (NTCA|BME, Hungary)

Maintainer activities mainly consisted of reviewing contributions, answering question/issues, and keeping the runtime environment up-to-date.

# Project Adoption

1. Adoption in performance testing production-grade systems is unknown.
2. The current feature set was driven by academic (BME, Hungary) and general-purpose performance measurement works (IBM UK) for Hyperledger Fabric networks.

# Goals

## Performance Against Prior Goals

1. There wasn't any major feature development for Caliper in the last year. 
2. The Fabric connector is the most popular among the supported integrations. Accordingly, the corresponding module was improved in terms of robustness and keeping up with new Fabric versions/features. The Fabric integration is deemed flexible and mature enough to test production-grade networks. 
3. The other connectors' state, however, deteriorated a bit (or more), either because lack of community interest or the lack of experts that could maintain/improve the given connector. The FISCO-BCOS integration, for example, was dropped because of incompatibility with current LTS Node.JS versions.
4. Currently, only Fabric and Ethereum-like platforms (e.g., Besu) are supported by Caliper. The Ethereum-like platform support is quite rigid and limited, it'd need a major update.

Overall, Caliper has a relatively strong and stable core and Fabric-related feature set, but it also has some rotting/half-ready/experimental parts that clutter the code-base and hinders its progress towards a stable release. The plan for the previous year was to reduce the latter, with minimal success.

## Next Year's Goals

2024 must be all about moving Caliper towards its first stable and major release. This must happen at two front, both supported by a corresponding LFX Mentorship project:
1. The feature set must be cleaned up and made more robust (via rigorous testing). See the [Hyperledger Caliper testability and robustness improvement](https://mentorship.lfx.linuxfoundation.org/project/e267822f-2186-4630-a08e-303cd0710705) project.
2. The documentation (both user-level and developer-level) must be improved in content and underlying technology stack. See the [Hyperledger Caliper documentation platform update](https://mentorship.lfx.linuxfoundation.org/project/692477cb-e620-40fe-b02a-f2a7894db67f) project.

These will give Caliper a clear scope and a consolidated issues list, which are needed to invite new contributors (beside the mentorship projects). 

Learning more about the adoption of Caliper in production-grade projects would also help with feature/usability decisions, but this is currently a gray area.

## Help Required

1. Methods and forums to survey a project's adoption: would help focus the development effort.
2. A webinar (series) about Caliper and its industry usages (from the adopters themselves). David Boswell already initiated a discussion about this and offered help, so the ball's in the Caliper team's court now.

# Project Lifecycle Stage Recommendation

Maintainer suggestion: keeping the current (Incubation) state and see whether the mentorship projects can revitalize and move forward the Caliper project.
