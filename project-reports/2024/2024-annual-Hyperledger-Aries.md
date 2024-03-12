---
layout: default
title: 2024 Annual Review Hyperledger Aries
parent: 2024
grand_parent: Project Updates
---

# 2024 Annual Review Hyperledger Aries

## Project Health

_Guidance: Include a link to your project’s [LFX Insights page](https://insights-v2.lfx.linuxfoundation.org/projects). We will be looking for signs of consistent or increasing contribution activity. Please feel free to add commentary to add color to the numbers and graphs we will see on Insights._

Hyperledger Aries LFX Insights Page for [Calendar Year 2023](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=aries&repository=all&dateFilters=2023-01-01%20to%202023-12-31&dateRange=2023-01-01%20to%202023-12-31&compare=PP&granularity=month&hideBots=true) (v. [2022](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=aries&repository=all&dateFilters=2022-01-01%20to%202022-12-31&dateRange=2022-01-01%20to%202022-12-31&compare=PP&granularity=month&hideBots=true))  and for [Q1 2024 Oct-Dec.](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=aries&repository=all&dateFilters=2023-10-01%20to%202023-12-31&dateRange=2023-10-01%20to%202023-12-31&compare=PP&granularity=month&hideBots=true) (v. [Q4 2023](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=aries&repository=all&dateFilters=2023-07-01%20to%202023-09-30&dateRange=2023-07-01%20to%202023-09-30&compare=PP&granularity=month&hideBots=true)).

Compared to 2022, the Hyperledger Aries Pull Request count was down by about 10% to 1,530 in 2023, while the number of contributors was about the same at 137. Compared to Q4 2023, the Q1 2024 report shows Pull Requests down about 30% (to 286), and Contributors down about 20% (to 51). The reduction in the latest quarterly numbers reflects the transition of the [Credo (formerly Aries Framework JavaScript)](https://github.com/openwallet-foundation/credo-ts) repository to the [Open Wallet Foundation](https://openwallet.foundation/).

Aries remains a healthy project and one of several viable candidates for major digital trust / verifiable credential deployments. Aries excels in its maturity, focus on privacy, and enabling a lasting trusted digital relationship between parties. Further, there have been multiple demonstrations this year that regardless of where the winds push Digital Trust, the Aries codebases will be a fit.

2023 has been an interesting year in the Aries project. Aries Cloud Agent Python and Aries VCX continued to thrive, adding capabilities and supporting repositories (such as the Aries ACA-Py Plugins repo). A couple of smaller, long dormant sub-projects were archived (Aries Framework .NET and Aries Framework Go), and Agent Framework JavaScript moved to the Open Wallet Foundation. Agent Framework JavaScript remains interoperable and a close collaborator with the Aries frameworks, Aries Cloud Agent Python and Aries VCX. Current discussions are ongoing about transferring Aries Bifold to OWF as well, as it is so tied to Agent Framework JavaScript.

2024 promises to be an equally interesting year, as the relationship between Hyperledger Aries and the Open Wallet Foundation, and the Digital Trust space in general, continues to evolve.

## Maintainer Diversity

_Guidance: How many maintainers do you have, and which organisations are they from? How has the maintainers and diversity of your maintainers changed in the past year? Has the number of active maintainers increased/decreased? Has the diversity of maintainers increased/decreased? Please include a link to your existing [MAINTAINERS file](https://github.com/hyperledger/toc/blob/gh-pages/guidelines/MAINTAINERS-guidelines.md) and the MAINTAINERS file from last year (if appropriate). This is a good opportunity to ensure that your MAINTAINERS file is up to date and to retire any maintainers._

There are currently 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations. As there are still dependent projects in Hyperledger, the Agent Framework JavaScript Maintainers continue to be Aries Maintainers, despite the move of the repository to the Open Wallet Foundation.

Typical Aries [Maintainers File](https://github.com/hyperledger/aries-cloudagent-python/blob/main/MAINTAINERS.md).

## Project Adoption

_Guidance: What do you know about adoption, and how has this changed since your last review or since being accepted into Hyperledger Foundation? If you can list companies that are adopters of your project, please do so. Feel free to link to an existing ADOPTERS file if appropriate._

Information on adoption is hard to find about Aries, as there is no bar to downloading and using Aries Frameworks, few metrics tied directly to usage, and we (mostly technology-types) have not spent a lot of time trying to learn about adoption. Forks, stars, and downloads continue to be the most direct adoption metrics, with ACA-Py recently climbing over the 500 forks and 300 stars marks on GitHub. ACA-Py Docker images on [hub.docker.com](https://hub.docker.com/r/bcgovimages/aries-cloudagent) have surpassed 50m pulls.

Our sense is that adoption is climbing along with the rest of the digital trust world. As more organizations enter the space, they gravitate towards one of the “competing” communities, including Aries. In addition, Aries continues to add support enabling the use of capabilities central to other communities, such as the W3C Verifiable Credentials Data Model Standard, OpenID4VCs, SD-JWTs and so on. A goal of the Aries community is to enable long-term flexibility in the frameworks we are building to support leading protocols, verifiable credential formats and other specifications.

## Goals

_Include information about the goals that you previously set for the project in the last review or since the project proposal has been approved. How has the project performed against these goals? If your goals changed from your previous annual report, let us know what changed and why. If you have not achieved the goals that you set out, that is okay. We want to know what you have accomplished and what challenges the project is having in meeting the goals._

### Performance Against Prior Goals

_Guidance: Include information about the goals that you previously set for the project in the last review or since the project proposal has been approved. How has the project performed against these goals? If your goals changed from your previous annual report, let us know what changed and why. If you have not achieved the goals that you set out, that is okay. We want to know what you have accomplished and what challenges the project is having in meeting the goals._

As this is the first Hyperledger Aries Annual Report, there is not a 2022 Annual Report to look back on. Instead, in this section we highlight the accomplishments in the project, in no particular order.

* Transitioning to ledger agnostic implementations for DIDs generally, and for AnonCreds. Great work in adding support for Cheqd, and other ledgers.
* Support added for new/better DID Peer variations, enabling a transition away from unqualified DIDs (from the time before the DID specification).
* Significant new capabilities in Aries Bifold, including [OCA for Aries](https://github.com/hyperledger/toc/blob/gh-pages/project-reports/2023/2023-Q3-Hyperledger-Aries.md) (to make displayed [credentials beautiful](https://github.com/hyperledger/aries-rfcs/blob/main/features/0755-oca-for-aries/README.md)!), a Mobile Verifier, and innumerable UX/usability enhancements, all released into production mobile apps.
* Transition away from the indy-sdk to the newer “shared components” (Aries Askar, Indy VDR and AnonCreds).
    * The availability of the shared components made the archiving of the Ursa project much easier to manage.
* Substantial completion of Aries Interop Profile (AIP) 2.0 and initial discussions on supporting the next AIP, including DIDComm v2.0.
* Preliminary support for OpenID4VCs and SD-JWTs in some Aries frameworks.
* Much progress on production deployments of Aries, including:
    * Redis/Kafka persistent queue support,
    * a powerful Aries Load Test Generator capability (Aries Akrida) based on Locust, and
    * a scalable DIDComm mediator (aries-socketdock)
* Substantial progress on Rust components for Aries
* Continued progress on interoperability across Aries implementations

### Next Year’s Goals

_Guidance: What are the goals for the next year of the project? The goals should list what you want to achieve, not just what you know you can achieve. Feel free to include stretch goals and things that you are looking to explore in the next year. For example, are you working on major new features? Or are you concentrating on adoption, community growth, or documentation?_

Recent Aries Working Group have been spent on defining a roadmap for 2024. The following is extracted from the discussions and notes from those meetings. The ordering is from activities well underway, to “reach for the clouds” ideas:

* Completion of the Unqualified DIDs Community Coordinated Update
* Continued development and publication of Aries best practices.
    * Ideally, leading to a Long Term Support (LTS) program and an initial LTS release.
* Marketing: Publishing information about the range and maturity of Aries capabilities, and improving the overall awareness of Aries in Digital Trust and corporate circles.
    * Publishing a scalability report.
    * Information about the Aries frameworks’s flexibility in interacting with non-Indy ledgers/VDRs, and other than AnonCreds verifiable credentials.
    * Visibility of implementations and deployments
* Continue/Expand alignment / interop efforts
    * JFF PlugFest
    * Aries Interopathon
    * OWF
    * Open Agent Framework
* [Aries Interop Profile (AIP) 2](https://github.com/hyperledger/aries-rfcs/blob/main/concepts/0302-aries-interop-profile/README.md) completion / AIP 3 definition
    * DIDComm v2 / Trust Spanning Layer
* Ledger Agnostic AnonCreds support within Aries projects
* OIDC4VC Protocol support, including relevant VC formats
* Aries RFC Cleanup — Status Review and the human friendly publication of the Aries Protocol RFCs integrated with the DIDComm Protocols.
* An evolution of the 'Start Here' documentation for the Aries Frameworks

A backdrop to the activity in Aries in 2024 will be the ongoing evolution of the relationship between Aries and the Open Wallet Foundation. Given the connections between the participants in both efforts and the shared knowledge, we’re confident that there will continue to be good collaboration and a focus on interoperability across the projects.

### Help Required

_Guidance: How can the Hyperledger Foundation or the TOC help you achieve your upcoming goals?_

Keeping open the dialogue about where the components of Aries should be between Hyperledger and the Open Wallet Foundation. From a bottom up perspective, there is a diversity of opinions on that question (as indicated by the Credo/Agent Framework JavaScript and Bifold moves), and we’re very interested in the top down perspective. Likewise, the dual-interest relationship between Aries and DIF concerning DIDComm is another aspect of community effort that requires balance and coordination.

There is a lot that the Hyperledger Foundation provides that we need to be making better use of, particularly in the area of marketing / getting the word out about the capabilities of Hyperledger Aries/AnonCreds. Our challenge is that the project is driven largely by technical types, not marketers. Those that helping with marketing are doing a great job, but are often constrained by a lack of content from the technical contributors.

## Project Lifecycle Stage Recommendation

_Guidance: What stage do you think the project should be? If you think that your project meets the criteria for another stage, please explain why. (See [Project Lifecycle](https://github.com/hyperledger/toc/blob/gh-pages/governing-documents/project-lifecycle.md))_

Aries is a Graduated project and should remain so. Its codebases are rock solid, growing and improving continuously. Aries has a large base of active maintainers and contributors, and a large ecosystem of deployments around the world.

## Feedback from the TOC

[TOC Meeting Recording 2024.02.22](https://zoom.us/rec/play/uTPwYkXMCWDRs-g4GUCzxYanQNB_EhjjTsQI9eDym21owleYHrYSSsM50ori0Mw_AY9kAWEwWOP6AXY9.7TlkfQ-b57sp8nsD?canPlayFromShare=true&from=share_recording_detail&continueMode=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fzoom.us%2Frec%2Fshare%2FrlFb_G1LYVq9UPA1AWNAOButkiFoj_K6C8kjtjmd3kCSrEJ2EYd3xMXz0h30hiPl.NG_wunlc29yfLNog) -- discussion on the Aries Annual Report starts at the 3:38 mark.

### Project Health

- Pull requests down by 10%, but contributors stable
- Q4 2023 vs Q1 2024 contributors down 20% and PRs 30%, but Q1 2024 hasn't finished
- Aries Cloud Agent Python and Aries VCX thrived, Agent Framework JavaScript moved to Open Wallet Foundation
- Aries Bifold may move to OWF 
- Some old projects archived (Aries Framework .NET and Aries Framework Go)
- Would be useful to provide more context on benefits of this?

### Maintainer Diversity

- Very good — 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations.

### Project Adoption

- Hard to measure — "senses" its climbing, but little concrete data

### Goals

No previous goals to compare against — highlights from past year

- Moving toward ledger agnostic implementations and away from indy-sdk
- Embracing OpenID4VCs and SD-JWTs
- Production components being added

This coming year:

- Interop efforts
- Build greater awareness with marketing
- Additional protocol support 

### Help Required

- Relationship of components between OWF and Hyperledger, also Aries relationship with with DIF due to DIDComm
- Tech driven — need marketing help

### Lifecycle

Remain graduated — agree

### Project Suggestions

- Identifying ways to market project more effectively
- If possible, it would be useful to get more context on the OWF and DID with respect to Aries, as it seems like there's a lot of crossover between them.
