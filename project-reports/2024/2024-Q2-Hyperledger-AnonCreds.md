---
layout: default
title: 2024 Q2 Hyperledger AnonCreds
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2024 Q2 Hyperledger AnonCreds

Created by Stephen Curran with input from the Hyperledger AnonCreds Maintainers.

## Implementation Repositories

- [anoncreds-rs] - Rust implementation of AnonCreds
- [anoncreds-clsignatures-rs] - Rust implementation of CL Signatures used in [anoncreds-rs]. Moved from Ursa and enhanced.
- [anoncreds-v2-rs] - Rust draft implementation of AnonCreds v2 -- **new contribution this quarter**

[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs
[anoncreds-clsignatures-rs]: https://github.com/hyperledger/anoncreds-clsignatures-rs
[anoncreds-v2-rs]: https://github.com/hyperledger/anoncreds-v2-rs

### Specifications

- [AnonCreds Specification] published from the repository [anoncreds-spec]
- [AnonCreds Methods Registry] published from the repository [anoncreds-methods-registry]
- [AnonCreds v2.0 Specification] published from the repository [anoncreds-spec-v2]

[anoncreds-spec]: https://github.com/hyperledger/anoncreds-spec
[AnonCreds Specification]: https://hyperledger.github.io/anoncreds-spec/
[anoncreds-methods-registry]: https://github.com/hyperledger/anoncreds-methods-registry
[AnonCreds Methods Registry]: https://hyperledger.github.io/anoncreds-methods-registry
[anoncreds-spec-v2]: https://github.com/hyperledger/anoncreds-spec-v2
[AnonCreds v2.0 Specification]: https://hyperledger.github.io/anoncreds-spec-v2/

### Web and Wiki Pages

- [Hyperledger AnonCreds Website Home Page]
- [Hyperledger AnonCreds Wiki Home Page]

[Hyperledger AnonCreds Website Home Page]: https://www.hyperledger.org/use/anoncreds
[Hyperledger AnonCreds Wiki Home Page]: https://wiki.hyperledger.org/display/ANONCREDS/

## Project Health

Things slowed down significantly on the AnonCreds project this past quarter and
we're considering what steps to take next to change the current trajectory of
the project. The broader issues are driven by two key issues.

- The eIDAS2 / EUDI initiatives in Europe that have
deemed that security trumps privacy, and having "selective disclosure"
is "good enough".
- There are various groups (including Hyperledger AnonCreds) working independently on
  what's next after AnonCreds for maximally privacy preserving verifiable
  credentials.

On the first, there are groups in Europe that would like to see more privacy
preserving credentials in place, but they are very much in the minority. For
example, concerns have been raised in [Europe about privacy being at the heart
of the European digital identity] efforts and in the [US by the ACLU and EFF].
The reasons outlined are exactly why the collaborators working on AnonCreds
continue to evolve the capabilities. It is not clear if the privacy regulators
have weighed in on the initiatives.

On the second, we see a need to try to bring together some of these groups to
work collaboratively. The goals are the same, the underlying signature schemes
are the same, so the question is how can we generate some synergy on the work?

[Europe about privacy being at the heart of the European digital identity]: https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/issues/66
[US by the ACLU and EFF]: https://www.eff.org/document/10-16-2023-aclu-eff-epic-comments-re-tsa-nprm-mdls

The [AnonCreds Quarterly Activity Dashboard] shows the activity on the project
repositories from January to March 2024, with 45 commits and 15 contributors in
the quarter. Those counts are down substantially from the last Quarterly Report
(2023-Q4) and from the previous quarter (Oct-Dec 2023).

[AnonCreds Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=anoncreds&repository=&dateFilters=Last%20Quarter&dateRange=2024-01-01%20to%202024-03-31&compare=PP&granularity=week&hideBots=true&routedFrom=Github

## Questions/Issues for the TOC

None.

## Releases

- [anoncreds-rs] -- v0.2.0
- [anoncreds-clsignatures-rs] — v0.2.4, v0.3.0, v0.3.1, v0.3.2

## Overall Activity in the Past Quarter

Coding for the quarter focused enabling the use of AnonCreds v1 in W3C
Verifiable Credential Data Model ([VCDM]) format. This was triggered by a "Code
With Us" procurement from BC Gov that was won by [DSR Corporation] for the
[AnonCreds Rust] work, [Animo Solutions] for the adding support for the format
in the [Credo-TS] and [Bifold Wallet] libraries (formerly Aries Framework
JavaScript and Aries Bifold React Native, respectively and now part of the [Open
Wallet Foundation]), and What's Cookin for adding support the for the format in
the [Aries Cloud Agent Python] library.

As announced in the last Quarterly Report, the contribution of the new AnonCreds
v2 code base, and underlying cryptography in [Agora], a Hyperledger Labs,
represents a big opportunity to advance AnonCreds and the idea of maximally
privacy-preserving verifiable credentials for everyday use. While we have
covered the new libraries and investigated how the "proof of concept" code might
evolve into an AnonCreds v1 replacement, to date we have had no significant
efforts on the project. As stated in the last Quarterly Report, we need to
assemble the set of collaborators looking to accomplish that goal that are
willing to have developers do the work needed. Yet another presentation at
[Internet Identity Workshop] got some interest, going over the capabilities
enabled by AnonCreds v2, and a "[To Do List]" of things we as a community need
to work on. However, there is still no full time development happening.

Few attendees have been at the recent AnonCreds Working Group meetings.

There have been additional, significant contributions of code in the Agora
project -- [audited cryptographic libraries].

[Agora]: https://labs.hyperledger.org/labs/agora.html
[To Do List]: https://docs.google.com/presentation/d/1-07WrKtLxIf6ymdmQyU3ssg0R4XrGJkMBAxIE9i6NMU/edit#slide=id.g28a13545521_0_5
[audited cryptographic libraries]: https://github.com/hyperledger-labs?q=agora

[AnonCreds Rust]: https://github.com/hyperledger/anoncreds-rs
[AnonCreds CL Signatures]: https://github.com/hyperledger/anoncreds-clsignatures-rs
[Credo-TS]: https://github.com/openwallet-foundation/credo-ts
[Bifold Wallet]: https://github.com/openwallet-foundation/bifold-wallet
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx
[Internet Identity Workshop]: https://docs.google.com/document/d/1xicI8Prdgo12Ha3ctZWdie7spCqgDiZT43RjIT3LApA/edit

## Current Plans

Continued evolution of the [AnonCreds Rust] library. Developing marketing and
collaboration efforts on AnonCreds V2 and the [anoncreds-v2-rs] library or
another approach to the next generation of maximally privacy preserving
verifiable credentials.

## Maintainer Diversity

Project Maintainers are from three different organizations: Animo Solutions, BC
Gov, and SICPA, plus an individual contributor.

## Contributor Diversity

Contributions in the quarter have come from at least 13 different organizations.

## Additional Information

- Key channels on Hyperledger Discord: \#anoncreds, \#anoncreds-spec,
\#anoncreds-rs
- [AnonCreds Mailing List](https://lists.hyperledger.org/g/anoncreds)
- Meetings pages
  - [AnonCreds Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+Working+Group)
