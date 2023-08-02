---
layout: default
title: 2023 Q3 Hyperledger Indy
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q3 Hyperledger Indy

Created by Stephen Curran and the Hyperledger Indy Maintainers.

## Sub-Projects

### **Distributed Ledger**

- [indy-node]
- [indy-plenum]
- [indy-test-automation]
- [indy-node-monitor]
- [indy-node-container]
- [indy-blssignatures-rs] - added this quarter

[indy-node]: https://github.com/hyperledger/indy-node
[indy-plenum]: https://github.com/hyperledger/indy-plenum
[indy-test-automation]: https://github.com/hyperledger/indy-test-automation
[indy-node-monitor]: https://github.com/hyperledger/indy-node-monitor
[indy-node-container]: https://github.com/hyperledger/indy-node-container
[indy-blssignatures-rs]: https://github.com/hyperledger/indy-blssignatures-rs

### **Client Tools**

- [indy-vdr]
- [indy-shared-rs] -- for AnonCreds, [Hyperledger AnonCreds] should be used
- [indy-cli-rs] -- new, Indy CLI based on Indy VDR, not Indy SDK
- [indy-sdk] -- Deprecated

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[indy-shared-rs]: https://github.com/hyperledger/indy-shared-rs
[indy-cli-rs]: https://github.com/hyperledger/indy-cli-rs
[indy-sdk]: https://github.com/hyperledger/indy-sdk
[Indy SDK]: https://github.com/hyperledger/indy-sdk
[Aries Askar]: https://github.com/hyperledger/aries-askar
[Hyperledger AnonCreds]: https://github.com/hyperledger/anoncreds-rs

### **Specifications**

- [did:indy Specification], [did:indy Specification source repository]
- [did:indy Networks]
- [Indy HIPE] (Hyperledger Indy Project Enhancements)

[did:indy Specification]: https://hyperledger.github.io/indy-did-method/
[did:indy Specification source repository]: https://github.com/hyperledger/indy-did-method
[did:indy Networks]: https://github.com/hyperledger/indy-did-networks
[Indy HIPE]: https://github.com/hyperledger/indy-hipe

## Project Health

The project had less activity this quarter than previously, with fewer updates
from (most) of the same organizations. The community had an Indy Ecosystem
Summit on June 29, 2023, with over 50 participants talking about what they are
doing with Indy. A follow up meeting to be held on September 7, 2023 is planned
to convert the interest expressed in the first meeting into action, ideally
based on the [Indy Roadmap].

[Indy Roadmap]: https://hackmd.io/GeRP00i0Sj-7z4zXn2MB5g?view

Per the [Indy Quarterly Activity Dashboard], there were 97 commits
(the same as last quarter) from 24 contributors (almost double last quarter).

[Indy Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222023-04-01T08:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-06-30T07:00:00.000Z%22%7D

## Questions/Issues for the TOC

None

### Issues from previous reports

#### **Diversity of Contributor Community**

See the updated type of information in the appropriate section of this report.

## Releases

- indy-vdr -  - v0.4.0-dev.13 to v0.4.0-dev.16
- indy-node-container - v1.2.5
- indy-shared-rs - v0.3.3

## Overall Activity in the Past Quarter

Activity was focused on the so-called Shared Components ([indy-vdr],
[indy-shared-rs] and [aries-askar]) and the transition away from the Indy SDK. The
maintainer community has discussed the formal deprecation of the Indy SDK and
the Aries maintainers have been busy making the Shared Components the default in
Aries, in preparation for the deprecation announcement.  

The archiving of the Hyperledger Ursa project triggered a refresh of the underlying
CL-Signatures code base (now [anoncreds-clsignatures-rs]), and a number of
improvements along with a couple of bug fixes. The release as part of
indy-shared-rs was the first upgrade to CL Signatures in several years, and
included a speed up of 50% in creating a revocation registry, and 25% in the
other revocation operations (issuance and revocation).

[anoncreds-clsignatures-rs]: https://github.com/hyperledger/anoncreds-clsignatures-rs

Little changed with the Indy Node implementation beyond further deployments of
the software and confirmation of its stability. However, no migrations of
existing networks to the Ubuntu 20.04 release have been performed. Testing,
experimenting and documenting that process continues.

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[aries-askar]: https://github.com/hyperledger/aries-askar
[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs

## Current Plans

The second Indy Ecosystem Summit in September will be a key event as we look to
see indications of contributions to the Indy code base and progress on the
deployment of the new network releases.

The Aries Frameworks are rapidly moving to [indy-vdr] and [aries-askar] and away
from [indy-sdk], which will enable its deprecation. The high priority work on
[Hyperledger AnonCreds] implementation will also drive that effort.

Progress is being made on enabling the "did:indy" DID Method in [indy-vdr]. Its
use requires the upgrade of Indy networks to use the new Ubuntu 20.04-based
releases.

## Maintainer Diversity

There are 35 individuals on 22 Indy GitHub Teams representing at least 16 organizations.

That said, cleanup of the teams are needed as some of the individuals are no longer active in the community.

## Contributor Diversity

See the [Indy Quarterly Activity Dashboard] for information about contributors
this quarter. The 18 individual contributors came from at least 9 different organizations.

## Additional Information

- Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers, \#indy-vdr
- [Indy Mailing List](https://lists.hyperledger.org/g/indy)
- The edX course about Indy, Aries, AnonCreds, and Ursa ([LFS172x - Introduction
to Hyperledger Self Sovereign Identity Blockchain Solutions]) was updated
recently, with the new version launched in January 2023.
  - [LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]

[LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]: https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa
