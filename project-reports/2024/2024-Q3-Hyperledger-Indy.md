---
layout: default
title: 2024 Q3 Hyperledger Indy
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
---

Created by Stephen Curran with input from the Hyperledger Indy Maintainers.

## Sub-Projects

### **Distributed Ledger**

- [indy-node]
- [indy-plenum]
- [indy-test-automation]
- [indy-node-monitor]
- [indy-node-container]
- [indy-blssignatures-rs]
- [indy-besu]

[indy-node]: https://github.com/hyperledger/indy-node
[indy-plenum]: https://github.com/hyperledger/indy-plenum
[indy-test-automation]: https://github.com/hyperledger/indy-test-automation
[indy-node-monitor]: https://github.com/hyperledger/indy-node-monitor
[indy-node-container]: https://github.com/hyperledger/indy-node-container
[indy-blssignatures-rs]: https://github.com/hyperledger/indy-blssignatures-rs
[indy-besu]: https://github.com/hyperledger/indy-besu

### **Client Tools**

- [indy-vdr]
- [indy-shared-rs] -- for AnonCreds, [Hyperledger AnonCreds] should be used
- [indy-cli-rs] -- new, Indy CLI based on Indy VDR, not Indy SDK

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[indy-shared-rs]: https://github.com/hyperledger/indy-shared-rs
[indy-cli-rs]: https://github.com/hyperledger/indy-cli-rs
[Hyperledger AnonCreds]: https://github.com/hyperledger/anoncreds-rs

### **Specifications**

- [did:indy Specification], [did:indy Specification source repository]
- [did:indy Networks]
- [Indy HIPE] (Hyperledger Indy Project Enhancements)
- [indy-did-method]

[did:indy Specification]: https://hyperledger.github.io/indy-did-method/
[did:indy Specification source repository]: https://github.com/hyperledger/indy-did-method
[did:indy Networks]: https://github.com/hyperledger/indy-did-networks
[Indy HIPE]: https://github.com/hyperledger/indy-hipe
[indy-did-method]: https://github.com/hyperledger/indy-did-method

## Project Health

The project less contributor activity over the quarter. Per the [Indy Quarterly
Activity Dashboard], in the months April through June, 2024 there were 426
commits (down about 50%) and 77 contributors (down about 30%). Work was focused
on dependabot updates, the [Indy Besu] efforts (which is not included in the LFX
data), and client performance improvements in digital credential wallets.

[Indy Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/overview/github?project=indy&routedFrom=Github&bestPractice=false&dateFilters=Last%20Quarter&dateRange=2024-04-01%20to%202024-06-30&compare=PP&granularity=week&hideBots=true

## Questions/Issues for the TOC

None

### Issues from previous reports

#### **Diversity of Contributor Community**

See the updated type of information in the appropriate section of this report.

## Releases

Release since the last quarterly report -- those after September 30, 2023:

- indy-node - None
- indy-plenum - v1.14.0rc0 -- first release candidate for the Ubuntu 22.04 release of Indy Plenum
- indy-vdr -  - v0.4.2, v0.4.3
- indy-node-container - v1.2.6
- indy-shared-rs - None

## Overall Activity in the Past Quarter

Work continued this quarter on the Ubuntu 22.04 version of Indy.

The [indy-vdr] work focused on improving performance in Wallets, and especially
caching immutable transactions.

Progress was made on the [Indy Besu] implementation of Indy capabilities on
a Besu base, and in defining the Indy Besu updates to the [Indy DID Method].

[Indy Besu]: https://github.com/hyperledger/indy-besu
[Indy DID Method]: https://github.com/hyperledger/indy-did-method

An Indy [Hyperledger Mentorship] project was kicked off this quarter to
implement an [Indy Read Replica] capability. We look forward to the
implementation efforts of [Bryan Elee] over the next few months on this project.

[Hyperledger Mentorship]: https://wiki.hyperledger.org/display/INTERN/Hyperledger+Mentorship+Program
[Indy Read Replica]: https://wiki.hyperledger.org/display/INTERN/Project+Plan+-+Indy+Read+Replica+Implementation
[Bryan Elee]: https://github.com/rxbryan

Two followups meetings to the most recent Indy Ecosystem Summit (#4, held April
9, 2024) were held in May, 2024 covering the technical aspects and funding
approaches to implementing Ledger Redactibility on Indy. A design was developed,
but little progress was made towards a cross-community collaboration for funding
and implementing the work. A couple of organizations have (as was suggested)
submitted a proposal for a grant to fund the effort.

## Current Plans

The maintainers would like to see the publication of an official Indy release
supporting Ubuntu 22.04. the work is well underway, with [indy-plenum] work
complete, and a "rinse and repeat" of the dependency changes in [indy-node].

[Indy Besu] work continues and gain interest.

We're now waiting on word of whether there will be a funding award for the
Ledger Redaction implementation work as described above.

## Maintainer Diversity

There are 35 individuals on 22 Indy GitHub Teams representing at least 16 organizations.

Still needed -- a cleanup of the teams are needed as some of the individuals are
no longer active in the community. No progress was made on that cleanup this
quarter. We have the team lists, but have not queried those on the list to see
if they are still interested in being maintainers.

## Contributor Diversity

See the [Indy Quarterly Activity Dashboard] for information about contributors
this quarter. The contributions came from at least 13 different
organizations.

## Additional Information

- Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers, \#indy-vdr
- [Indy Mailing List](https://lists.hyperledger.org/g/indy)
