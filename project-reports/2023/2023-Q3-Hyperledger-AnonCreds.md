---
layout: default
title: 2023 Q3 Hyperledger AnonCreds
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q3 Hyperledger AnonCreds

Created by Stephen Curran and the Hyperledger AnonCreds Maintainers.

## Implementation Repositories

- [anoncreds-rs] - Rust implementation of AnonCreds
- [anoncreds-clsignatures-rs] - Rust implementation of CL Signatures used in [anoncreds-rs]. Moved from Ursa and enhanced.

[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs
[anoncreds-clsignatures-rs]: https://github.com/hyperledger/anoncreds-clsignatures-rs

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

The project continues to make good progress, with the maintainers and
contributors completing version 0.1.0 of the AnonCreds Rust implementation and
that library being used in downstream applications.

The [AnonCreds Quarterly Activity Dashboard] shows the activity on the project
repositories, with 52 commits by 8 contributors in the quarter. Those counts are
much lower than last quarter, reflecting the shift from implementing AnonCreds
to using AnonCreds in the downstream implementations.

> NOTE: As of 2023.08.02 only some of the AnonCreds repositories are visible on
LFX Insights. The additional repositories are being added.

[AnonCreds Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fanoncreds/dashboard;subTab=technical?time=%7B%22from%22:%222023-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-06-30T07:00:00.000Z%22%7D

## Questions/Issues for the TOC

None.

## Releases

- [anoncreds-rs] -- v0.1.0-dev.13 through v0.1.0-dev.19 and v0.1.0 (final)
- [anoncreds-clsignatures-rs] — initial release 0.1 published to crates.io


## Overall Activity in the Past Quarter

The highlight of the quarter was the completion of the 0.1.0 release of the
Hyperledger [AnonCreds Rust] implementation and its subsequent deployment in the
[Aries Framework JavaScript] Release 0.4.0 code base. Aries Framework JavaScript
0.4.0 is already in use in several production environments, including in [Aries
Bifold]-based apps released through Google Play and the iOS App Store. The Aries
Framework JavaScript implementation supports multiple AnonCreds publication
platforms beyond Hyperledger Indy, including at least [Cheqd.io] and [Cardano].

[AnonCreds Rust]: https://github.com/hyperledger/anoncreds-rs
[Aries Framework JavaScript]: https://github.com/hyperledger/aries-framework-javascript
[Aries Bifold]: https://github.com/hyperledger/aries-mobile-agent-react-native
[Cheqd.io]: https://cheqd.io/
[Cardano]: https://cardano.org/

Work on embedded the [AnonCreds Rust] implementation in [Aries Cloud Agent Python]
has stalled, and the maintainers of that library are reorganizing that effort.
The maintainers of the [Aries VCX] implementation recently connected with the
AnonCreds maintainers with an offer to help with the AnonCreds implementation to
make it easier to consume in the (Rust) Aries VCX code base.

[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx

The transition of the Ursa CL Signatures library to the [AnonCreds CL
Signatures] was completed quickly and smoothly, with a number of enhancements
and fixes made to the library during the transition. These are the first
enhancements to the code base in several years. For example, code optimizations
were found that improved the revocation registry generation process by about
50%, and the handling of other revocation processes by about 25%. Bugs in the
library were also identified and fixed, and new releases of downstream libraries
(including [Aries Cloud Agent Python]) published in early July (just after the
end of the quarter).

[AnonCreds CL Signatures]: https://github.com/hyperledger/anoncreds-clsignatures-rs

Work continued on the v1.0 specification, albeit more slowly with the alignment
with the [AnonCreds Rust] 0.1.0 implementation complete. At the end of the
quarter, [Aritra Bhaduri] joined the project via the Hyperledger Mentorship
Program. Aritra is documenting the cryptographic algorithms in the specification
and ensuring alignment with the implementation. Work continued on the v2.0
specification, with a complete “draft” pass completed in meetings and work ready
to start on the specification details—minus any decisions on Revocation. What to
use for the next generation revocation scheme continues to be a challenge.

[Aritra Bhaduri]: https://github.com/aritroCoder

## Current Plans

Implementation work is focused primarily on the downstream projects that use
Hyperledger AnonCreds. Work is continuing on improving the CL Signatures
implementation.

On the specifications side, completing the v1.0 specification is focused on the
documentation of the cryptographic algorithms used in the processing, as
mentioned earlier. As well, work can begin on filling in the details of the
[AnonCreds v2.0 Specification] as a formal document.

## Maintainer Diversity

Project Maintainers are from three different organizations: Animo Solutions, BC
Gov, and SICPA.

## Contributor Diversity

Contributions in the quarter have come from at least 8 different organizations,
including Animo Solutions, Roots ID, 2060.io, Indicio and BC Gov.

## Additional Information

- Key channels on Hyperledger Discord: \#anoncreds, \#anoncreds-spec,
\#anoncreds-rs
- [AnonCreds Mailing List](https://lists.hyperledger.org/g/anoncreds)
- Meetings pages
    - [AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+Specification+Working+Group)
    - [AnonCreds v2.0 Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+v2.0+Working+Group)
