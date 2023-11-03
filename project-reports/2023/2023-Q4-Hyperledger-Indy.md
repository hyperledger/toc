---
layout: default
title: 2023 Q4 Hyperledger Indy
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q4 Hyperledger Indy

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

The project continued to have little maintainer activity, with most of the
updates focused on the work necessary to deprecate the [Indy SDK] in favour of
the more modern [indy-vdr] and [indy-shared-rs] (which will soon be replaced by
[Hyperledger AnonCreds]). Indy will retain the [indy-node] ledger implementation
(with the underlying [indy-plenum] consensus code), and [indy-vdr] client code
to access the ledger. The other parts of the Indy SDK will be elsewhere, secure
storage in [Aries Askar] and [Hyperledger AnonCreds] for verifiable credential
exchange.

The highlight of the quarter was the Second Indy Ecosystem Summit held in early
September -- a follow up to the First Indy Ecosystem Summit that was discussed
in the last quarterly report. The event was again well attended, 40+
participants, and the topics covered included specific actions for moving the
project forward. Here is a
[link](https://docs.google.com/document/d/1Gkd-V17tAYQFI4ymtIGUjfQxBlgOYVj0WBdX1ZdWA_g/edit?usp=sharing)
to the materials from both summits. See the [Overall
Activity](#overall-activity-in-the-past-quarter) for more details of the
discussions.

Per the [Indy Quarterly Activity Dashboard], there were 149 commits
(up about 50% from last quarter) from 11 contributors (down about 50% from last quarter).

[Indy Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222023-07-01T08:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-09-30T07:00:00.000Z%22%7D

## Questions/Issues for the TOC

See the idea in that came out of the Second Hyperledger Indy Ecosystem Summit:

> Is there a way for the Hyperledger Foundation to enable a group to collect
funds for an open source objective, and the use those funds to enable a code
contribution?

### Issues from previous reports

#### **Diversity of Contributor Community**

See the updated type of information in the appropriate section of this report.

## Releases

- indy-vdr -  - v0.4.0-dev.13 to v0.4.0-dev.16
- indy-node-container - v1.2.5
- indy-shared-rs - v0.3.3

## Overall Activity in the Past Quarter

GitHub activity was focused on the so-called Shared Components ([indy-vdr],
[indy-shared-rs] and [aries-askar]) and the transition away from the Indy SDK. The
maintainer community has discussed the formal deprecation of the Indy SDK and
the Aries maintainers have been busy making the Shared Components the default in
Aries, in preparation for the deprecation announcement.  

At the Second Indy Ecosystem Summit, two discussions focused on paths forward.
On the technical side, [DSR Corporation](https://en.dsr-corporation.com/)
presented several ideas for evolving the Indy Node ledger component, including
evolving the current implementation, or implementing Indy transactions on
another network, such as [Hyperledger Besu](https://www.hyperledger.org/projects/besu), or
[Cosmos](https://cosmos.network/). While there is no pressing feature set needed in the
foreseeable future, the lack of maintainers on the existing code base is concerning. Those
with an opinion thought that Besu was the most interesting alternative and work has
started on defining what that might mean. This breaks into a couple of questions:

* How to write Indy (or more accurately, AnonCreds) objects on a Besu network
  (schema, credential definitions, and revocation registries)?
* Can and should the existing Indy roles be used when running on a Besu network?
* Can and should the existing Indy authorization rules be used when running on a Besu network?

The second topic raised was if and how the Indy community, as represented at the
Ecosystems Summits, can collaborate on moving the Indy technology, marketing and
regulatory environment forward?  For example, is there a way for the Hyperledger
Foundation to enable a group to collect funds for an open source objective, and
the use those funds to enable a code contribution?

## Current Plans

Continuing the move of the Aries Frameworks to [indy-vdr] and [aries-askar] and away
from [indy-sdk], which will enable its deprecation. The high priority work on
[Hyperledger AnonCreds] implementation will also drive that effort.

Investigating different paths forward for Hyperledger Indy ledger components, including
a specific look at the use of Hyperledger Besu for that purpose. What would that look
like as a technical component?

A third Hyperledger Indy Ecosystem Summit is planned, but not yet scheduled, likely
with a more focused group -- those that are operating Indy networks.

## Maintainer Diversity

There are 35 individuals on 22 Indy GitHub Teams representing at least 16 organizations.

Still needed -- a cleanup of the teams are needed as some of the individuals are
no longer active in the community. No progress was made on that cleanup this
quarter. We have the team lists, but have not queried those on the list to see
if they are still interested in being maintainers.

## Contributor Diversity

See the [Indy Quarterly Activity Dashboard] for information about contributors
this quarter. The 11 individual contributors came from at least 6 different
organizations. Attendees at the Hyperledger Indy Ecosystem Summits were from 30+
organization in 14 countries across 4 continents. Indy continues to be globally
relevant.

## Additional Information

- Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers, \#indy-vdr
- [Indy Mailing List](https://lists.hyperledger.org/g/indy)
- The edX course about Indy, Aries, AnonCreds, and Ursa ([LFS172x - Introduction
to Hyperledger Self Sovereign Identity Blockchain Solutions]) was updated
recently, with the new version launched in January 2023.
  - [LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]

[LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]: https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa
