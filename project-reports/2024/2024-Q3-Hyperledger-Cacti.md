---
layout: default
title: 2024 Q3 Hyperledger Cacti
parent: 2024
grand_parent: Project Updates
---


# Project Health

- The project is in good health!
- Multiple mentorship projects are underway, namely [Enabling Enterprise Organizational Blockchain Interoperability](https://wiki.hyperledger.org/display/INTERN/Enabling+Enterprise+Organizational+Blockchain+Interoperability) and [Cacti: Core Operators Modules for DLTs](https://wiki.hyperledger.org/display/INTERN/Cacti%3A+Core+Operators+Modules+for+DLTs).
- `v2.0.0-rc.2` was released a couple weeks ago and `v2.0.0-rc.3` is not far behind (hopefully next week)!
- Major efforts are underway to integrate the codebase further
- We continue to promote interoperability protocol standardization by contributing to, and implementing, the candidate [IETF SATP specification](https://datatracker.ietf.org/doc/draft-ietf-satp-core/) using different combinations of Cacti modules. We conducted a [workshop on May 23, 2024](https://wiki.hyperledger.org/display/events/Standardizing+DLT+Interoperation%3A+Implementing+IETF+Secure+Asset+Transfer+Protocol+in+Hyperledger+Cacti) to discuss the protocol and demonstrate the associated Cacti capabilities.
- Enabled the [OpenSSF Scorecard](https://scorecard.dev/viewer/?uri=github.com%2Fhyperledger%2Fcacti) for the project.

LFX Insights (Beta) Link:
https://insights.lfx.linuxfoundation.org/foundation/hyp/overview/github?project=cacti&routedFrom=Github&bestPractice=false

# Questions/Issues for the TOC

No questions for the TOC.

# Releases

- v2.0.0-rc.2 - issued
- v2.0.0-rc.3 - upcoming

# Overall Activity in the Past Quarter

- Most of our activity comes from the Discord channel. The daily pair programming calls are well attended by mentees, existing contributors and would-be contributors alike.
- Questions are answered in a mostly timely fashion though it's not perfect we do make a conscious effort to respond quickly.
- The CI performance optimizations are still ongoing, but we are close to having a solution to dynamic diff analysis which makes it so that our CI jobs only run tests of a package that had changes in itself or its dependency tree of packages.
- We now have more than 60 packages in the monorepo total.
- The release automation that published packages to npmjs.com and ghcr.io has been fixed, we no longer have to manually run publishing scripts.
- New features are being worked on as we speak. Most of the development here focuses on IETF-SATP. More information on the [Cacti discord channel](https://discord.com/channels/905194001349627914/908379338716631050).

# Current Plans

1. Work is being done on a Cacti example that combines the Harmonia Lab smart contracts and the Cacti Corda JVM connector plugin together. Once this is ready, we hope to show it off to the Harmonia Lab maintainers and seek further partnership and collaboration between the two groups.
2. Cactus & Weaver Integration - we work on this ourselves and also have a mentorship project underway for the same.
3. Documentation revamp and updating process is ongoing.
4. There are dozens of branches with build process improvements and test stability fixes (we have flaky tests that are too resource intensive for the free tier GitHub runners but we can't move to the paid tier due to our CI taking 8 to 10 hours of compute time to run).
5. We are working on improving our OpenSSF Scorecard numbers.

# Maintainer Diversity

We have 8 active maintainers from 4 different organizations total:

- Izuru Sato 
- Michal Bajer 
- Peter Somogyvari 
- Takuma TAKEUCHI 
- Jagpreet Singh Sasan 
- Venkatraman Ramakrishna 
- Sandeep Nishad 
- Rafael Belchior 

# Contributor Diversity

Source: https://insights.lfx.linuxfoundation.org/foundation/hyp/reports/organizations?project=cacti&routedFrom=Github&bestPractice=false

|name                                       |Active Days|Activities count|Activities percent|
|-------------------------------------------|-----------|----------------|------------------|
|Accenture Global Solutions Limited         |277        |3.45K           |64.08%            |
|Ework Group                                |162        |821             |15.21%            |
|International Business Machines Corporation|101        |434             |8.04%             |
|Fujitsu Limited                            |90         |233             |4.32%             |
|Blockdaemon                                |63         |269             |4.99%             |
|INESC-ID                                   |34         |62              |1.15%             |
|ZAUBAR                                     |14         |52              |0.96%             |
|Hex Trust                                  |13         |20              |0.37%             |
|Blazpay                                    |13         |18              |0.33%             |
|Hyperledger                                |11         |49              |0.91%             |
|Cheesecake Labs                            |9          |19              |0.35%             |
|Reliance Jio Infocomm Limited              |8          |15              |0.28%             |
|Infosys Limited                            |7          |8               |0.15%             |
|TUBITAK UEKAE                              |4          |7               |0.13%             |
|Foogle Tech Software                       |3          |5               |0.09%             |
|SAITM22                                    |3          |4               |0.07%             |
|Samsung Electronics Co. Ltd.               |2          |4               |0.07%             |
|SeeWise.AI                                 |2          |2               |0.04%             |
|Rapid Innovation                           |2          |2               |0.04%             |
|GitHub                                     |1          |2               |0.04%             |
|Signify Holding                            |1          |1               |0.02%             |
|Individual - No Account                    |1          |1               |0.02%             |
|Bank of New York Mellon                    |1          |1               |0.02%             |
|Texas A And M University                   |1          |1               |0.02%             |
|Zeeve Inc                                  |1          |1               |0.02%             |



# Additional Information
- Different collaborations with the academia and industry are still taking place. In particular, one of them is [Portugal's BLOCKCHAIN.PT project](https://www.hyperledger.org/blog/portugals-blockchain.pt-uses-hyperledger-cacti-as-its-interoperability-framework).
