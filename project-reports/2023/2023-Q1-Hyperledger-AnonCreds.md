---
layout: default
title: 2023 Q1 Hyperledger AnonCreds
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q1 Hyperledger AnonCreds

Created by Stephen Curran.

## Implementation Repositories

- [anoncreds-rs] - Rust implementation of AnonCreds

[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs

### Specifications

- [AnonCreds Specification] published from the repository [anoncreds-spec]
- [AnonCreds Methods Registry] published from the repository [anoncreds-methods-registry]

[anoncreds-spec]: https://github.com/hyperledger/anoncreds-spec
[AnonCreds Specification]: https://hyperledger.github.io/anoncreds-spec/
[anoncreds-methods-registry]: https://github.com/hyperledger/anoncreds-methods-registry
[AnonCreds Methods Registry]: https://hyperledger.github.io/anoncreds-methods-registry

### Web and Wiki Pages

- [Hyperledger AnonCreds Website Home Page]
- [Hyperledger AnonCreds Wiki Home Page]

[Hyperledger AnonCreds Website Home Page]: https://www.hyperledger.org/use/anoncreds
[Hyperledger AnonCreds Wiki Home Page]: https://wiki.hyperledger.org/display/ANONCREDS/

## Project Health

This is the first report from the Hyperledger AnonCreds project. The project was
announced on November 15, 2022 with this [Hyperledger blog post announcement].

[Hyperledger blog post announcement]: https://www.hyperledger.org/blog/2022/11/15/announcing-hyperledger-anoncreds-open-source-open-specification-privacy-preserving-verifiable-credentials

Response to the extraction of the AnonCreds capabilities from Indy and their use with other ledgers
has been generally positive, including an uptick in attendance and activity on the AnonCreds specification.

## Questions/Issues for the TSC

## Releases

- [anoncreds-rs] -- none

## Overall Activity in the Past Quarter

The Rust implementation of AnonCreds was created by duplicating the repo of its previous home in the [indy-shared-rs](https://github.com/hyperledger/indy-shared-rs) repository, and the subsequent removal of the "non-AnonCreds" parts
of the repo. The focus of the maintainers and contributors is aligning the implementation with the "ledger-agnostic"
elements of the specification, and updating the specification to align with the implementation. The volume of changes
to the implementation to be ledger-agnostic has been surprisingly small. Only one Indy-specific data element needed to
be removed from the AnonCreds API, and most of the changes have been to clean variable names to align their name to their meaning. The most significant single change was in the writing and reading of Revocation Registry state.

In addition to developing the Rust implementations, wrappers for JavaScript and Python have been created/evolved and GitHub Actions have been created to automated builds and release publishing.

On November 28, 2022, we had a presentation from Mike Lodder who has been involved with AnonCreds since the early
days of the Indy implementation. He provided a proposal for how to evolve AnonCreds from the current v1.0 specification to a v2.0 that retains (and extends in some places) the key privacy preserving features of AnonCreds with updated cryptographic primitives. The meeting agenda, notes and recordings are available [here](https://wiki.hyperledger.org/display/ANONCREDS/2022-11-28+AnonCreds+Specification+Working+Group+Meeting). Definitely worth listening to the presentation!

There is no AnonCreds Quarterly Activity report available on the LFX Insights page. We will update this report to include the report when it becomes available. We do have [this information](https://insights-v2.lfx.linuxfoundation.org/anoncreds/trends) for the rolling past year activity on the project.

[AnonCreds Quarterly Activity Dashboard]: https://insights-v2.lfx.linuxfoundation.org/anoncreds/trends?selectedDateFilterType=DATERANGE&selectedDateRangeKey=90D

## Current Plans

Work on the first release is nearing completion -- the first goal of the project. This work, combined with the efforts
in the Hyperledger Indy project to eliminate the Indy SDK will mean the quick adoption of AnonCreds into the Aries frameworks. in parallel with the specification and implementation effort is the integration of AnonCreds with other
projects, including [Cheqd](https://cheqd.io) and [Cardano](https://cardano.org/).

Documentation updates in the Rust implementation repo needs attention.

## Maintainer Diversity

Will consider how to get information on maintainer diversity for the next quarterly report.

## Contributor Diversity

Will consider how to get information on contributor diversity for the next quarterly report.

## Additional Information

- Key channels on Hyperledger Discord: \#anoncreds, \#anoncreds-spec,
\#anoncreds-rs
- [AnonCreds Mailing List](https://lists.hyperledger.org/g/anoncreds)
