---
layout: default
title: 2023 Q1 Hyperledger Indy
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q1 Hyperledger Indy

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
- [indy-shared-rs]
- [indy-sdk]

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[indy-shared-rs]: https://github.com/hyperledger/indy-shared-rs
[indy-sdk]: https://github.com/hyperledger/indy-sdk
[Indy SDK]: https://github.com/hyperledger/indy-sdk
[Aries Askar]: https://github.com/hyperledger/aries-askar

### **Specifications**

- [did:indy Specification], [did:indy Specification source repository]
- [did:indy Networks]
- [Indy HIPE] (Hyperledger Indy Project Enhancements)

[did:indy Specification]: https://hyperledger.github.io/indy-did-method/
[did:indy Specification source repository]: https://github.com/hyperledger/indy-did-method
[did:indy Networks]: https://github.com/hyperledger/indy-did-networks
[Indy HIPE]: https://github.com/hyperledger/indy-hipe

## Project Health

A major milestone was hit in the Hyperledger Indy project this quarter.  The
Indy Node Continuous Integration/Continuous Delivery (CI/CD) pipeline to
automate the build, testing and publishing of the Indy ledger artifacts was
completed. We now have Indy Node release candidates in place based on Ubuntu
20.04, and being used in live Indy instances. The process is fully automated,
including the execution of the [indy-test-automation] tests. Tags in either
[indy-node] or its dependent [indy-plenum] trigger the full pipeline and
artifact publication.

At the end of the quarter, the Indy/Aries community began a push to eliminate
the use of the [Indy SDK] in favor of the so-called shared components, [Indy
VDR] (the client ledger interface to Indy networks), [indy-shared-rs] (an
AnonCreds implementation and Indy client utilities) and [Aries Askar] (secure
storage and key management service). BC Gov announced a series of five "Code
With Us" opportunities to facilitate this transition, each focused on a
transition of the use of the [Indy SDK] to the shared components. This is a
significant transition, as the [Indy SDK] is difficult to maintain and release,
and has some demonstrated performance issues. The shared components address
these concerns, by breaking up the Indy SDK into its component parts, each with
wrappers and an end-to-end CI/CD pipeline. Apples-to-apples testing of the [Indy
SDK
performance](https://github.com/lissi-id/acapy-load-test-results/blob/main/AcaPy_0-7-4/Endurance_Test/04-0_7_3_indy-200rpm/report-test-results-0-END.pdf)
and the [shared components
performance](https://github.com/lissi-id/acapy-load-test-results/blob/main/AcaPy_0-7-4/Endurance_Test/02-0_7_4_askar_0_2_5-200rpm/report-test-results-0-6.pdf)
shows that the shared components are both faster and more stable.

The AnonCreds Rust implementation previously in [indy-shared-rs] has been moved
to the new Hyperledger AnonCreds project and the [anoncreds-rs] repository. In
the shared components migration from the Indy SDK talked about above, the
[anoncreds-rs] AnonCreds implementation will be used. A pair of Indy AnonCreds
Methods will remain, one based on the existing Indy AnonCreds objects
identifiers, and one based on the new "did:indy" object identifiers. This change
will simplify the transition to "did:indy".

[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs

Per the [Indy Quarterly Activity Dashboard], there were 100 commits
(almost double from last quarter) from 13 contributors (up one).

[Indy Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Findy/dashboard;subTab=technical?time=%7B%22from%22:%222022-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-12-31T07:00:00.000Z%22%7D

## Questions/Issues for the TSC

### Issues from previous reports

#### Build Pipelines

**Update** : The Ubuntu upgrade is complete, producing releases and
compatibility with the Ubuntu 16.04 instance has been tested. To be removed from
the next report.

#### **Diversity of Contributor Community**

**No Update** : Little change this quarter in contributor community. Lots
of interest, but core maintainers continue to do most of the work.

## Releases

- indy-node (Ubuntu 20.04) – v1.13.2-rc4

## Overall Activity in the Past Quarter

In the past quarter (as in the previous quarter), ledger code
development focused on code management – upgrading the Indy Node and
Plenum CI/CD pipeline and upgrading Indy Node to run on Ubuntu 20.04.
A particular focus was on the [indy-test-automation] pipeline, and
enabling its use for both Indy Node releases and for the downstream
Sovrin Node releases.

Much activity occurred in extracting the AnonCreds Rust implementation
from the [indy-shared-rs] repository to the standalone [anoncreds-rs]
repository.

## Current Plans

With the new CI/CD Indy Node and Plenum pipelines complete, and the
Ubuntu 20.04 indy-node upgrade available, the core maintainers are
focused on their downstream releases.

The Aries Frameworks are moving to [indy-vdr] and [aries-askar] and away from
[indy-sdk]. As that happens, adjustments and additions will be made to the newer
repositories. The high priority work on Hyperledger AnonCreds implementation
will also drive that effort.

A focus on pushing the "did:indy" DID Method is enabled by the upgrade of Indy
Node to the new Ubuntu 20.04-based releases.

## Maintainer Diversity

No change the Maintainers this quarter.

## Contributor Diversity

See the [Indy Activity Quarterly Dashboard] for information about contributors
this quarter.

## Additional Information

- Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers, \#indy-vdr
- [Indy Mailing List](https://lists.hyperledger.org/g/indy)
- The edX course about Indy, Aries, AnonCreds, and Ursa ([LFS172x - Introduction
to Hyperledger Self Sovereign Identity Blockchain Solutions]) was updated
recently, with the new version launched in January 2023.

   - [LFS172x - Introduction to Hyperledger Self Sovereign Identity Blockchain Solutions]: https://www.edx.org/course/identity-in-hyperledger-aries-indy-and-ursa
