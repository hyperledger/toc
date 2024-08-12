---
layout: default
title: 2024 Q3 Hyperledger AnonCreds
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
---

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

Contributions remain slow on the AnonCreds project itself this quarter, but
there has been a significant uptake in conversations around the use of ZKP-based
verifiable credentials in the AnonCreds and other VC communities. The EU has a
requirement to use "unlinkable" (non-correlatable) verifiable credentials with
the [EUDI Wallets]. To now, the plan to meet that requirement has not been to
use ZKPs, but instead to issue a many instances of each credential and have the
holder use each credential just once, or at least, each credential with just one
verifier. Each instance is slightly different, and as a result, each verifier
gets an unlinkable credential -- although the verifiers can correlate the
credentials through the issuer. The reasons for the "no to ZKP" has been an
additional requirement that each credential be bound to a hardware key held in
the holders mobile device -- which is not possible with ZKP schemes such as CL
Signatures used in AnonCreds v1 or BBS Signatures planned for use in AnonCreds
v2. Some well-known cryptographers have [weighed in on that approach] and
[presented a paper] arguing that the "batch issue" approach is ineffective. As
well, they have proposed new scheme is being proposed that implements ZKPs using
ECDSA hardware-based keys.  The folks involved in AnonCreds are part of that
discussion, and will see how that might impact the direction of the AnonCreds
project.

[weighed in on that approach]: https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/issues/200
[presented a paper]: https://github.com/user-attachments/files/15904122/cryptographers-feedback.pdf
[EUDI Wallets]: [](https://digital-strategy.ec.europa.eu/en/policies/eudi-wallet-implementation)

The [AnonCreds Quarterly Activity Dashboard] shows the activity on the project
repositories from April to June 2024.

[AnonCreds Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/overview/github?project=anoncreds&routedFrom=Github&bestPractice=false&dateFilters=Last%20Quarter&dateRange=2024-04-01%20to%202024-06-30&compare=PP&granularity=week&hideBots=true&repository=

## Questions/Issues for the TOC

None.

## Releases

- [anoncreds-rs] -- None
- [anoncreds-clsignatures-rs] — None

## Overall Activity in the Past Quarter

There have been a couple of PRs to the new AnonCreds v2 Rust repository, including from some new contributors.

Few attendees have been at the recent AnonCreds Working Group meetings.

There have been additional, significant contributions of code in the Hyperledger Labs [Agora]
project -- [audited cryptographic libraries].

[Agora]: https://labs.hyperledger.org/labs/agora.html
[audited cryptographic libraries]: https://github.com/hyperledger-labs?q=agora

[AnonCreds Rust]: https://github.com/hyperledger/anoncreds-rs

## Current Plans

Continued evolution of the [AnonCreds Rust] library. Contributing the
conversation happening in the broader community about new ways to use ZKPs for
achieving unlinkable VCs, and determining how to leverage that work into
expanding efforts on AnonCreds, or using the resources of AnonCreds together
with those efforts.

## Maintainer Diversity

Project Maintainers are from three different organizations: Animo Solutions, BC
Gov, and SICPA, plus an individual contributor.

## Contributor Diversity

LFX Insights seems to suggest there have been contributions in the quarter from
at least 8 different organizations. But it is really hard to be sure.

## Additional Information

- Key channels on Hyperledger Discord: \#anoncreds, \#anoncreds-spec,
\#anoncreds-rs
- [AnonCreds Mailing List](https://lists.hyperledger.org/g/anoncreds)
- Meetings pages
  - [AnonCreds Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+Working+Group)
