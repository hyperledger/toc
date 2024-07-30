---
layout: default
title: 2024 Q3 Hyperledger Aries
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
nav_exclude: true
---

## Project Health

Work on [Hyperledger Aries] continues at a healthy pace, with lots of activity
in all of the Aries and the related-OWF sub-communities. [Aries Cloud Agent
Python] continues to move to its 1.0.0 release, and the community around
[Aries-VCX] is again growing, with lots of work happening in moving the
implementation forward. [Open Wallet Foundation]-hosted [Credo-TS] and [Bifold
Wallet] continue to evolve rapidly. [Animo Solutions], key maintainers of
[Credo-TS], were selected by the German Government as a funded participate in
the [Funke] ("sparkle") initiative to create innovative wallet prototypes in
preparation for the promised German [EUDI Wallet] to be released by 2026.
Exciting times!

[Funke]: https://www.sprind.org/en/challenges/eudi-wallet-prototypes/
[Animo Solutions]: https://animo.id/
[EUDI Wallet]: https://digital-strategy.ec.europa.eu/en/policies/eudi-wallet-implementation

[Hyperledger Aries]: https://www.hyperledger.org/projects/aries
[Credo-TS]: https://github.com/openwallet-foundation/credo-ts
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx
[Open Wallet Foundation]: https://openwallet.foundation/
[Indy VDR]: https://github.com/hyperledger/indy-vdr
[AnonCreds RS]: https://github.com/hyperledger/anoncreds-rs

## Questions/Issues for the TOC

None at this time.

## Releases

The following Aries releases occurred in the last two quarters (including the
time covered by the Annual Report and so not yet reported):

- [Aries Cloud Agent Python] -- 0.11.1, 0.12.0, 0.12.1
- [Aries Askar] -- None
- [Aries VCX] -- v0.64.0

Interoperability status can be seen
here: [https://aries-interop.info](https://aries-interop.info).

## Overall Activity in the Past Quarter

Per the [Aries Activity Dashboard] for the months of April-June 2024, Aries
codebases had 3185 Commits and 275 contributors representing at least 28
organizations.  The numbers do include the repositories
that have moved from Hyperledger to the Open Wallet Foundation, as well as some
obsolete (but unchanging) repositories. Per Ry Jones there is not a good way for
us to control the included list of repos.

[Aries Activity Dashboard]: https://insights.lfx.linuxfoundation.org/foundation/lf-decentralized-trust/overview/github?project=aries&routedFrom=Github&bestPractice=false&dateFilters=Last%20Quarter&dateRange=2024-04-01%20to%202024-06-30&compare=PP&granularity=week&hideBots=true

- The [Indy SDK] has been removed from ACA-Py, eliminating the older component in favour of newer and more capable
  replacements ([Aries Askar], [Indy VDR], and [AnonCreds RS]). Good to see that
  transition!
  - **NOTE: THIS DOES NOT REMOVE INDY SUPPORT FROM ACA-PY!**
- Support for AnonCreds in W3C VCDM Format in Aries has been implemented in [Aries Cloud Agent Python].
- Work has begun on adding [DIDComm v2] support in [ACA-Py].

[Aries Askar]: https://github.com/hyperledger/aries-askar
[Indy SDK]: https://github.com/hyperledger/indy-sdk
[DIDComm v2]: https://identity.foundation/didcomm-messaging/spec/
[ACA-Py]: https://aca-py.org

## Aries Framework Reports

### [Aries VCX]

Work on Aries VCX has been picked up by a new set of maintainers, and lots of updates have been happening.

### [Aries Cloud Agent Python]

[Aries Cloud Agent Python] (ACA-Py) work in the quarter has focused on the
upcoming Release 1.0.0. Almost everything is in place and as this is being
written, the last PR for the release is being reviewed. Real Soon Now! Details
about the updates and changes in the release can be found about about the
release from the [ACA-Py Release Candidate changelog].

The maintainers of ACA-Py are in the process of adding a Long Term Support (LTS)
policy for the project, modelled on the Hyperledger Fabric LTS approach. We have
two LTS versions at this time (0.11.x and 0.12.x). Once stabilized, there will
be a 1.x LTS minor release declared as well.

Transitioned the sourcing of the ACA-Py documentation site [https://aca-py.org]
to be from the ACA-Py repo itself.

[https://aca-py.org]: https://aca-py.org

[ACA-Py Release Candidate changelog]: https://github.com/hyperledger/aries-cloudagent-python/blob/main/CHANGELOG.md

## Current Plans

- Releasing v1.0.0 of ACA-Py.
- Deploying support for [AnonCreds in W3C Verifiable Credentials Data Model Standard] format.
- Continuing working to add support for [DIDComm V2].
- Adding support for the [`did:tdw` DID Method], including support for rooting AnonCreds Verifiable Credentials using a `did:tdw` DID

[AnonCreds in W3C Verifiable Credentials Data Model Standard]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/7afcbd7c-2bbc-41ed-bf27-b6ba6e2903c5
[`did:tdw` DID Method]: https://bcgov.github.io/trustdidweb/

## Maintainer Diversity

There are currently 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations.

## Contributor Diversity

In the quarter there were commits from 275 individuals representing at least 28 organizations.

## Additional Information

None
