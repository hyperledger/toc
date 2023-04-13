---
layout: default
title: 2023 Q2 Hyperledger Cacti
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# 2023 Q2 Hyperledger Cacti

## Project Health

- The first code merge of Cactus and Weaver to "Cacti" repository was completed and we released Cacti v1.2.0 in the end of March.
- The maintainers are also discussing the [new architecture of Cacti](https://github.com/hyperledger/cacti/blob/main/ROADMAP.md#cacti-v2) toward Cacti-V2 in order to combine the strengths of the original Cactus and Weaver systems to provide a more flexible interoperablity tool with several feature selection options given to network administrators. The Cacti v2-alpha, v2-beta and v2.0 release will be redesigned according to the new architecture.

# Questions/Issues for the TOC

- None at the moment.

# Releases

- v1.2.0 => https://github.com/hyperledger/cacti/tree/v1.2.0
    - including the features: merging Weaver into Cacti

# Overall Activity in the Past Quarter

1. Major update as merged pull-requests
    - merging from Cactus and Weaver:
        - [new_feature] Merge Weaver to Cacti
            - https://github.com/hyperledger/cacti/commit/4ac560a3222733a2ecf465f80f42b2007ddcb6be
            - https://github.com/hyperledger/cacti/commit/4171eebd83aba627a155509e13bd95fb50f6ae73
    - support tools:
        - [new_feature (WIP)] Cacti GUI app 
            - https://github.com/hyperledger/cacti/pull/2265
2. Created a new architecture diagram toward realizing Cacti as a more flexible interoperability toolkit
    - The architecture has been brushed-up among weekly maintainer calls. We will use this architecture as the main point of reference starting with the next release (Cacti V2-beta on Q2)
    - https://github.com/hyperledger/cacti/blob/main/ROADMAP.md#cacti-v2
    - https://github.com/hyperledger/cacti/blob/main/images/cacti-architecture-v1-merge.png
3. Submitted several proposals for the 2023 Hyperledger Mentorship Program, of which four got selected:
    - [Cacti - Polkadot connector](https://wiki.hyperledger.org/display/INTERN/Cacti+-+Polkadot+connector)
    - [Cacti: Implement Standardized Secure Asset Transfer Protocol](https://wiki.hyperledger.org/display/INTERN/Cacti%3A+Implement+Standardized+Secure+Asset+Transfer+Protocol)
    - [Cacti: Ledger Data Sharing with Proof in Besu and Ethereum](https://wiki.hyperledger.org/display/INTERN/Cacti%3A+Ledger+Data+Sharing+with+Proof+in+Besu+and+Ethereum)
    - [Cacti: Decentralized Identity Management for Trusted Interoperation](https://wiki.hyperledger.org/display/INTERN/Cacti%3A+Decentralized+Identity+Management+for+Trusted+Interoperation)

# Current Plans

1. Release plan:
    - Cacti V2-alpha (Q2): The first prototype version of Cacti combining the legacy Cactus and Weaver code bases
    - Cacti V2-beta (Q2): The first version of Cacti based on the new architecture (combining the strengths of both Cactus and Weaver)
2. Interview candidates for the Mentorship program

# Maintainer Diversity

- As is required, you can find our current maintainer list here:  https://github.com/hyperledger/cacti/blob/main/MAINTAINERS.md.

- Our existing maintainers are: 
    - Jagpreet Singh Sasan (Accenture)
    - Jonathan Hamilton (Accenture)
    - Peter Somogyvari (Accenture)
    - Izuru Sato (Fujitsu)
    - Takuma Takeuchi (Fujitsu)
    - Sandeep Nishad (IBM)
    - Venkatraman Ramakrishna (IBM)

# Contributor Diversity

- https://lfanalytics.io/projects/hyperledger%2Fcactus/dashboard
- Our contributor strength has increased in this quarter compared to the previous quarter, which is great news!

# Additional Information

- N/A
