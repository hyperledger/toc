---
layout: default
title: 2023 Q2 Hyperledger Indy
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q2 Hyperledger Indy

Created by Stephen Curran.

## Sub-Projects

### **Distributed Ledger**

- [indy-node]
- [indy-plenum]
- [indy-test-automation]
- [indy-node-monitor]
- [indy-node-container]

[indy-node]: https://github.com/hyperledger/indy-node
[indy-plenum]: https://github.com/hyperledger/indy-plenum
[indy-test-automation]: https://github.com/hyperledger/indy-test-automation
[indy-node-monitor]: https://github.com/hyperledger/indy-node-monitor
[indy-node-container]: https://github.com/hyperledger/indy-node-container

### **Client Tools**

- [indy-vdr]
- [indy-shared-rs] -- for AnonCreds, [Hyperledger AnonCreds] should be used
- [indy-sdk] -- Deprecated

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[indy-shared-rs]: https://github.com/hyperledger/indy-shared-rs
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

The project is relatively healthy, with a moderate number of updates
from a range of organizations. An exercise in the Indy Contributors
call resulted in an [Indy Roadmap] defining the direction of the project
the community would like to see.

[Indy Roadmap]: https://hackmd.io/GeRP00i0Sj-7z4zXn2MB5g?view

Per the [Indy Quarterly Activity Dashboard], there were 97 commits
(the same as last quarter) from 24 contributors (almost double last quarter).

[Indy Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222023-01-01T08:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-03-31T07:00:00.000Z%22%7D

## Questions/Issues for the TSC

None

### Issues from previous reports

#### **Diversity of Contributor Community**

See the updated type of information in the appropriate section of this report.

## Releases

- indy-node (Ubuntu 20.04) – v1.13.2-rc5, v1.13.2-rc6
- indy-plenum (Ubuntu 20.04) - v1.13.1-rc4
- indy-vdr - v0.3.4, v0.4.0-dev.1 to v0.4.0-dev.12
- indy-node-container - v1.2.4
- indy-test-automation - v0.9.0, v0.9.1, v0.9, v0.9.2, v0.10.0, v0.11.0, v0.11, v0.11.1
- indy-cli-rs - v0.1.0
- indy-shared-rs - v0.3.2
- indy-sdk-react-native - v0.3.1

## Overall Activity in the Past Quarter

Much of the progress this quarter focused on [indy-vdr] and the movement of
Aries Frameworks from using the [indy-sdk] to using the so-called shared
components, including [indy-vdr], [aries-askar] and [anoncreds-rs]. The move
away from the [Indy SDK] triggered updates and releases of a lot of Indy
artifacts from a variety of repositories. See the list of releases
[here](#releases). A significant conversion of a deployed agent (an Aries
mediator) from the Indy SDK to Askar once again demonstrated the performance and
stablity benefits of such a change.

Further progress was made on the Indy CI/CD pipeline automation and on the new
Ubuntu 20.04 release. Work on completing that task has been slowed because of
the nature of the final task -- deciding what changes in the Indy Node/Indy
Plenum `ubuntu-16.04` (formerly `main`) and `stable` branches need to be
cherry-picked onto the new new (Ubuntu 20.04) `main` branch. The nature of the
work restricts those capable of making the decisions, and those folks are busy
on other tasks in the community.

Some progress was made by those with significant production deployments of Indy
(such as [Sovrin], [Indicio] and the Canadian Public Sector ([CANdy])) towards
moving them to the Ubuntu 20.04 release -- mostly in the area of testing out the
migration of the networks and creating documentation.

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[aries-askar]: https://github.com/hyperledger/aries-askar
[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs
[Sovrin]: https://sovrin.org
[Indicio]: https://indicio.tech/
[CANdy]: https://candyscan.idlab.org/

## Current Plans

With the new CI/CD Indy Node and Plenum pipelines complete, and the Ubuntu 20.04
[indy-node] release candidate upgrade available, the core maintainers are
focused on their downstream releases.

The Aries Frameworks are moving to [indy-vdr] and [aries-askar] and away from
[indy-sdk]. As that happens, adjustments and additions will be made to the newer
repositories. The high priority work on Hyperledger AnonCreds implementation
will also drive that effort.

A focus on pushing the "did:indy" DID Method is enabled by the upgrade of Indy
Node to the new Ubuntu 20.04-based releases.

## Maintainer Diversity

There are 35 individuals on 22 Indy GitHub Teams representing at least 16 organizations.

That said, cleanup of the teams are needed as some of the individuals are no longer active in the community.

## Contributor Diversity

See the [Indy Quarterly Activity Dashboard] for information about contributors
this quarter. The 24 individual contributors came from at least 11 different organizations.

## Additional Information

- Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers, \#indy-vdr
- [Indy Mailing List](https://lists.hyperledger.org/g/indy)
- The edX course about Indy, Aries, AnonCreds, and Ursa ([LFS172x - Introduction
to Hyperledger Self Sovereign Identity Blockchain Solutions]) was updated
recently, with the new version launched in January 2023.
  - [LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]

[LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]: https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa
