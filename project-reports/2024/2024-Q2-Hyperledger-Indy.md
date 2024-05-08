---
layout: default
title: 2024 Q2 Hyperledger Indy
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
- [indy-besu] -- :new:

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
- [indy-sdk] -- Deprecated

[indy-vdr]: https://github.com/hyperledger/indy-vdr
[indy-shared-rs]: https://github.com/hyperledger/indy-shared-rs
[indy-cli-rs]: https://github.com/hyperledger/indy-cli-rs
[indy-sdk]: https://github.com/hyperledger/indy-sdk
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

The project continued to have steady contributor activity. Per the
[Indy Quarterly Activity Dashboard], in the months January through March, 2024 there
were 145 commits (about the same as the previous quarterly report quarterly, and
up from the previous quarter) from 34 contributors (up significantly from the
previous quarterly report quarter, but down about 20% from last quarter).

[Indy Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=indy&repository=&dateFilters=Last%20Quarter&dateRange=2024-01-01%20to%202024-03-31&compare=PP&granularity=week&hideBots=true&routedFrom=Github

## Questions/Issues for the TOC

From the previous quarterly report:

> See the idea that came out of the Second Hyperledger Indy Ecosystem Summit:
>
> Is there a way for the Hyperledger Foundation to enable a group to collect
funds for an open source objective, and the use those funds to enable a code
contribution?

This was answered in the review of that last quarterly report. The best option
available is through the Linux Foundations [LFX Crowdfunding Platform]. Some
work is being done in the Besu community towards such a process, but the
administrative and legal overhead is high, beyond what is appropriate for Indy.

[LFX Crowdfunding Platform]: https://lfx.linuxfoundation.org/tools/crowdfunding/

### Issues from previous reports

#### **Diversity of Contributor Community**

See the updated type of information in the appropriate section of this report.

## Releases

Release since the last quarterly report -- those after September 30, 2023:

- indy-node - v1.13.2
- indy-plenum - v1.13.1
- indy-vdr -  - v0.4.1
- indy-node-container - None
- indy-shared-rs - v1.1.0, v1.1.1

## Overall Activity in the Past Quarter

A key focus in this past quarter has been on
completing the official release of Indy supporting Ubuntu 20.24, including the
considerable release pipeline work done in achieving that release. The pipeline
work is paying off in the work started on a release of Indy supporting Ubuntu
22.04.

There were also improvements made to the underlying "shared components" that
replace the archived Indy SDK. Notably, caching of transactions was put into
Indy VDR so that it need not be re-implemented at the higher levels.

Progress was also made on the [Indy Besu] implementation of Indy capabilities on
a Besu base, and in defining the Indy Besu updates to the [Indy DID Method].

[Indy Besu]: https://github.com/hyperledger/indy-besu
[Indy DID Method]: https://github.com/hyperledger/indy-did-method

Since the last quarterly report there have been two more Indy Ecosystem Summits
(3 and 4) that focused on (3) collaborating on work in general, and (4)
collaborating on work to achieve the addition of a specific feature -- "Ledger
Redaction". "Collaborating" in this context is coming up with a way to
crowd-source funding for a specific feature and then to use the collected funds
to get the specific feature merged into the appropriate open source
repositories. For those interested "Ledger Redaction" means the ability to flag
specific transactions as being redacted such that requests for resolving those
transactions return a "Not Found" result. This capability, tricky on a ledger
for obvious reasons, is important for compliance and liability reasons, enabling
redaction for GDPR scenarios and for handling the writing of "illegal content"
to the ledger.

## Current Plans

The maintainers would like to see the publication of an official Indy release
supporting Ubuntu 22.04. the work is well underway, with [indy-plenum] work
complete, and a "rinse and repeat" of the dependency changes in [indy-node].

[Indy Besu] work continues and gain interest.

We'd like to see progress on the Ledger Redaction feature as described above --
including both the work itself, and on a reusable mechanism for funding that
work.

## Maintainer Diversity

There are 35 individuals on 22 Indy GitHub Teams representing at least 16 organizations.

Still needed -- a cleanup of the teams are needed as some of the individuals are
no longer active in the community. No progress was made on that cleanup this
quarter. We have the team lists, but have not queried those on the list to see
if they are still interested in being maintainers.

## Contributor Diversity

See the [Indy Quarterly Activity Dashboard] for information about contributors
this quarter. The 34 individual contributors came from at least 14 different
organizations.

## Additional Information

- Key channels on Hyperledger Discord: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers, \#indy-vdr
- [Indy Mailing List](https://lists.hyperledger.org/g/indy)
