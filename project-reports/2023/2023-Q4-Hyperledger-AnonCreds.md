---
layout: default
title: 2023 Q4 Hyperledger AnonCreds
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q4 Hyperledger AnonCreds

Created by Stephen Curran and the Hyperledger AnonCreds Maintainers.

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

The project continues to make good progress in enabling the use of maximum
privacy-preserving credentials in large ecosystems. With the completion last
quarter of the first official release (0.1.0), much of the coding focus has been
on integrating it into different Aries Frameworks, and making adjustments in the
library and in the wrappers to enable that. In addition, updates continue in the
underlying [anoncreds-clsignatures-rs] library, addressing both flaws in the
design and implementation, and in making performance and usability improvements
in the library. The addition of the recently contributed AnonCreds v2 draft code
base will be extremely helpful in adding to the Hyperledger AnonCreds momentum.

While there has been a push to get verifiable credentials in use with ZKP
capabilities and unlinkability, there has recently been push back on the lack of
privacy preserving capabilities being proposed in some of the current schemes
that are moving forward. These include concerns raised in [Europe about privacy being at the heart of the European digital identity] efforts
and in the [US by the ACLU and EFF]. The reasons outlined are exactly why the
collaborators working on AnonCreds continue to evolve the capabilities.

[Europe about privacy being at the heart of the European digital identity]: https://github.com/eu-digital-identity-wallet/eudi-doc-architecture-and-reference-framework/issues/66
[US by the ACLU and EFF]: https://www.eff.org/document/10-16-2023-aclu-eff-epic-comments-re-tsa-nprm-mdls

The [AnonCreds Quarterly Activity Dashboard] shows the activity on the project
repositories, with 97 commits by 12 contributors in the quarter. Those counts are
each up by about 50% from last quarter.

[AnonCreds Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fanoncreds/dashboard;subTab=technical?time=%7B%22from%22:%222023-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-09-30T07:00:00.000Z%22%7D

## Questions/Issues for the TOC

None.

## Releases

- [anoncreds-rs] -- v0.2.0-dev.1
- [anoncreds-clsignatures-rs] — v0.1.0, v0.2.0, v0.2.1, v0.2.2, v0.2.3

## Overall Activity in the Past Quarter

Coding for the quarter focused on enabling the use of the [AnonCreds Rust] in
the various Aries frameworks, including [Aries VCX], [Aries Framework
JavaScript] and [Aries Bifold]. Work is continuing on adding support in [Aries
Cloud Agent Python] for the new library. Much of the coding in the [AnonCreds Rust] library
itself was on integrating the [AnonCreds CL Signatures Rust] library, and on the
wrappers that enabled use in the Aries frameworks.

The [Hyperledger Mentorship program] enabled the creation of an [AnonCreds
Mentorship project], that resulted in our bringing on [Aritra Bhaduri] who has
been extremely effective at updating the [AnonCreds Specification] to include
details of the cryptographic operations occurring during the issuing, receiving,
presenting, and verifying (with revocation) of AnonCreds verifiable credentials
and presentations. This gets us through the last major hurdle in completing the
AnonCreds v1 specification. Remaining is an editorial pass through the entire
specification for cleanup and consistency -- the easy stuff! And, since all of the
objects and operations will remain in AnonCreds v2, the v1 specification is a
huge head start towards the creation the v2 specification. Huge thanks and
appreciation of the efforts by Aritra who has done an outstanding job!

[Hyperledger Mentorship program]: https://wiki.hyperledger.org/display/INTERN/Hyperledger+Mentorship+Program
[Aritra Bhaduri]: https://github.com/aritroCoder
[AnonCreds Mentorship]: https://wiki.hyperledger.org/display/INTERN/Document%2C+Review%2C+and+Implement+Hyperledger+AnonCreds+ZKP+Cryptographic+Primitives

The contribution of the new AnonCreds v2 code base, and underlying cryptography
in [Agora], a Hyperledger Labs represents a big opportunity to advance AnonCreds
and the idea of maximum privacy-preserving verifiable credentials for everyday
use. We need to assemble the set of collaborators looking to accomplish that
goal that are willing to have developers do the work needed. A presentation at
[Internet Identity Workshop] got good interest, going over the capabilities
enabled by AnonCreds v2, and a "[To Do List]" of things we as a community need to
work on.

[Agora]: https://labs.hyperledger.org/labs/agora.html
[To Do List]: https://docs.google.com/presentation/d/1-07WrKtLxIf6ymdmQyU3ssg0R4XrGJkMBAxIE9i6NMU/edit#slide=id.g28a13545521_0_5

[AnonCreds Rust]: https://github.com/hyperledger/anoncreds-rs
[AnonCreds CL Signatures]: https://github.com/hyperledger/anoncreds-clsignatures-rs
[Aries Framework JavaScript]: https://github.com/hyperledger/aries-framework-javascript
[Aries Bifold]: https://github.com/hyperledger/aries-mobile-agent-react-native
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx

## Current Plans

Continued evolution of the [AnonCreds Rust] library, completion of the
[AnonCreds Specification], and ramping up marketing and collaboration efforts
on AnonCreds V2 and the [anoncreds-v2-rs] library.

## Maintainer Diversity

Project Maintainers are from three different organizations: Animo Solutions, BC
Gov, and SICPA, plus an individual contributor.

## Contributor Diversity

Contributions in the quarter have come from at least 8 different organizations,
including Animo Solutions, ID Lab of Canada, Roots ID, 2060.io, Indicio and BC Gov.

## Additional Information

- Key channels on Hyperledger Discord: \#anoncreds, \#anoncreds-spec,
\#anoncreds-rs
- [AnonCreds Mailing List](https://lists.hyperledger.org/g/anoncreds)
- Meetings pages
    - [AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+Specification+Working+Group)
    - [AnonCreds v2.0 Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+v2.0+Working+Group)
