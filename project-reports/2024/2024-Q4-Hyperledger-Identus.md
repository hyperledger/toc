---
layout: default
title: 2024 Q3 Hyperledger Identus
parent: 2024
grand_parent: Project Updates
nav_exclude: true
---

Created by Javier Ribó with input from other maintainers


# Project Health

The project is still new to the Hyperledger Ecosystem and continues to have steady growth of contributors.
The project can now be found on the LFX dashboard which can now be checked for health insights. In the last quarter we have seen an increase on the number of github issues created while the active contributors have gone down 8%.


# Questions/Issues for the TOC

Is there a way to access funds for open source contributions and development? 


# Releases

  * Identus V2.13
    * Cloud Agent v1.39.0
    * PRISM Node v2.5.0
    * Mediator v1.0.0
    * Apollo Crypto Library v1.4.3
    * Edge Agent SDK Swift v6.1.0
    * Edge Agent SDK TypeScript v6.1.0
    * Edge Agent SDK KMP v4.0.0
    * Documentation Portal v1.110

  * In the coming days the following releases are planned:
    * Prism Node 3.0.0
    * Mediator 1.0.0
    * Cloud Agent 1.40.0


# Overall Activity in the Past Quarter

During the previous quarter the team has been focusing on the following:
1. Connectionless Issuance and Verification of VC via DIDCommV2
2. DID Prism AnonCreds method to resolve the resources from the DID Prism URL (for the schema and credential definition)
3. Crypto Agility of the DID Prism Method (added Ed25519 cryptography suite)
4. Transitioning the project from the IOHK to the Hyperledger organization
5. OID4VCI specification implementation in the Cloud Agent and SDKs (for JWT VC only)
6. Major refactoring: 
    a. improved error handling in the Cloud Agent, the Mediator, and SDKs, 
    b. added Problem Report protocol to other protocols,
    c. Background jobs are replaced with the message queue (in-memory or Kafka)
7. SD-JWT-VC implementation in the Cloud Agent and SDKs
8. Status List revocation implementation in JWT VC
9. Improved documentation with the Quick Start Guide and Tutorials



# Current Plans

As the IOG team that acted as maintainers of Identus has scaled down, the objective during this quarter will be to encourage more participation from the community in both development, governance and community engagement
The team will be focusing on simplifying the deployment and documentation of our stack, we will no longer be pursuing some of the features we were working on which were more intended for Enterprise use-cases, but instead we are going to focus on what our community members need, one very important one is having diversity of choice on the Prism NODE, universal resolver and VDR

The Community is encouraged to log feature requests, issues etc and this is then incorporated into a roadmap that is transparent for everyone to see https://github.com/orgs/hyperledger/projects/48



# Maintainer Diversity

We currently have 7 maintainers from which 3 are from outside of IOG, and we are constantly working on onboarding new members to the community by making workshops, community calls and partnering with some projects

# Contributor Diversity

At the moment, the main contributors of source code is IOG at a 75% of the contributions.
The remaining of the contributions are shared across other organizations.
Other organizations have given additional on feature request ideas such as Ahau and Socious. While we have other organizations such as C-Sign developing books specifically aimed at developers wanting to develop with Identus. The book is expected to be completed next year https://identusbook.com/book/



# Additional Information

NA
