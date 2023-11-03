---
layout: default
title: 2023 Q4 Hyperledger Aries
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
nav_exclude: true
---

# Project Health

[Hyperledger Aries](https://www.hyperledger.org/projects/aries) continues at a
healthy pace, seeing lots of activity in most of the Aries
sub-communities, including [Aries Framework JavaScript], [Aries Bifold] (mobile
wallet), [Aries Cloud Agent Python] and [Aries VCX]. Lots of progress being made
on all of those efforts!

While not a risk to the progress being made in the various open source Aries
communities, the question of moving some of the Aries projects from the
[Hyperledger Foundation] to the [Open Wallet Foundation] (OWF) was raised this quarter. A fork
of a long dormant Aries project (the .NET Framework) has been created in the OWF. A more
interesting situation is the transfer of the actively maintained [Aries
Framework JavaScript] repository from Hyperledger to OWF that has been
[proposed by some Aries Framework JavaScript maintainers]. It's an interesting topic, and
we'll no doubt see more discussion and action related to Aries and the OWF in coming months.

[Aries Framework JavaScript]: https://github.com/hyperledger/aries-framework-javascript
[Aries Bifold]: https://github.com/hyperledger/aries-mobile-agent-react-native
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx
[Aries Framework Go]: https://github.com/hyperledger/aries-framework-go
[proposed by some Aries Framework JavaScript maintainers]: https://github.com/hyperledger/aries-framework-javascript/discussions/1586
[Open Wallet Foundation]: https://openwallet.foundation/
[Hyperledger Foundation]: https://hyperledger.org

# Questions/Issues for the TOC

None.

# Releases

The following Aries releases occurred in the last quarter:

- [Aries Cloud Agent Python] -- 0.10.0, 0.10.1, 0.10.2, 0.10.3
- [Aries Framework JavaScript] -- v0.4.0, v0.4.1alpha.5-34, v0.4.1, v0.4.2, v0.5.0alpha57-58
- [Aries Askar] -- v0.3.0-dev1
- [Aries VCX Releases] -- v0.58.0-v0.61.0
- [Aries Bifold] -- v1.0.0-alpha.34-130

Interoperability status can be seen
here: [https://aries-interop.info](https://aries-interop.info).

# Overall Activity in the Past Quarter

Per the [Aries Activity Dashboard] for the months of July-September 2023, Aries
codebases had 402 PRs (up 5%) from 64 contributors (down 9%).

[Aries Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222023-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-09-30T07:00:00.000Z%22%7D

* There continues to be activity towards completing the integration of
  [Hyperledger AnonCreds] into most of the Aries Frameworks to enable
  ledger-agnostic implementations, with the [Aries Framework JavaScript]
  evolving their existing implementation and [Aries VCX] and [Aries Cloud Agent
  Python] working on an initial implementation.
* The move away from the [Indy SDK] continues to accelerate. Deprecation
  announcements have been published, and we would expect support to be dropped
  by the frameworks as soon as continuing its use adds complexity to a feature.
* The Government of British Columbia launched a "Code With Us" open source
  procurement for an [Aries Load Test Generator] for stress testing Aries issuers,
  verifiers, and mobile agent mediators. [Indicio PBC] was awarded the work, and
  have prepared the [Aries Akrida] repository in response to the challenge. The
  repository is expected to move into the Hyperledger GitHub organization soon.

[Aries Askar]: https://github.com/hyperledger/aries-askar
[Indy SDK]: https://github.com/hyperledger/indy-sdk
[Hyperledger AnonCreds]: https://github.com/hyperledger/anoncreds-rs
[OpenID4VCs]: https://openid.net/openid4vc/
[Aries Cloud Agent Python plugins]: https://github.com/hyperledger/aries-acapy-plugins
[Indicio PBC]: https://indicio.tech
[Aries Akrida]: https://github.com/Indicio-tech/aries-akrida
[Aries Load Test Generator]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/51d7c289-51a8-4307-939c-5a4271c7b2b6
[SD-JWTs]: https://datatracker.ietf.org/doc/draft-ietf-oauth-selective-disclosure-jwt/

## Aries Framework Reports

### [Aries VCX]

**Accomplishments**

* Finished migration from legacy indysdk components to maintained components indy-vdr and credx
* Ongoing efforts to add support for V2 versions of issue-credential and presentation protocols to enable wider varieties of VC formats.
* Big portion of dev effort was dedicated to refactoring, improving developer experience, making tests cleaner, stabler and more efficient.
* The two ongoing mentorship projects shaping up nicely:
    * [aries-vcx based mediator service](https://wiki.hyperledger.org/display/INTERN/%5Bdraft%5D+Project+Plan+-+aries-vcx+based+message+mediator+service)
    * [uniffi based mobile wrapper](https://wiki.hyperledger.org/pages/viewpage.action?pageId=98730187)

**2023Q4 Planning**

* Completion and stabilization of V2 issuance/presentation protocols
* Stabilization of new reusable components created in 2023, such as did, did_document, did_peer, did_exchange and others. On the same note, general improvement of developer onboarding of these components, as they will be adopted also outside of Aries context.
* Completion of our two 2023 mentorship projects
* Progress on work to migrate from credx to [anoncreds-rs] to enable implementation of non-indy anoncreds methods

### [Aries Framework JavaScript]

This quarter, [Aries Framework JavaScript] development was focused on two
trends. On one side, making fixes and optimizations for 0.4.x release, following
feedback from first adopters of it. Among those, we can highlight expanding
support for the DIDComm Out-of-Band connection establishment flows and support
for [Aries Askar] profiles in multi-tenancy scenarios. On the other side,
preparing for the next major releases: 0.5.0 (expected for Q4 2023) and 0.6.0
(expected for Q1 2024). Work towards those releases include supporting
[SD-JWTs], the latest drafts of [OpenID4VCs] (issuance and presentation) and
[DIDComm V2], are well underway.

A topic of discussion in the [Aries Framework JavaScript] community is the
possibility of the transfer of the [Aries Framework JavaScript] repository (and
likely some related repositories) from the [Hyperledger Foundation] to the [Open
Wallet Foundation] that has been [proposed by some Aries Framework JavaScript
maintainers]. The issue is not yet finalized, and discussions are continuing.

[DIDComm V2]: https://identity.foundation/didcomm-messaging/spec/

### [Aries Cloud Agent Python]

[Aries Cloud Agent Python] (ACA-Py) work in the quarter included the following highlights:

* Making some foundational updates to the CI/CD pipeline (upgrading the minimum support Python version, switching to [Poetry] for package management, and [ruff] for linting).
* Adding support for [SD-JWTs] format verifiable credential -- signing and verifying.
* Work to enable the upcoming transitions from the use of unqualified DIDs, and to [DIDComm V2].
* Adding support for the ledger-agnostic [Hyperledger AnonCreds].
* Maintenance and performance optimizations.
* Creation of the [Aries Cloud Agent Python plugins] repository -- an "app
  store" for modular extensions to ACA-Py.

[Poetry]: https://python-poetry.org/
[ruff]: https://docs.astral.sh/ruff/

### [Aries Framework Go]

After an active previous quarter, activity slowed this quarter on [Aries
Framework Go]. In checking with the primary maintainers (from [Gen
Digital](https://www.gendigital.com/)) about this change, we were told that the
current maintainers will not be continuing to evolve the framework. As such,
we'll consult with the community and either change the maintainers or archive
the repository.

# Current Plans

* Completing the work on eliminating the use of the [Indy SDK] in favor of the
  [Aries Askar]/[Indy VDR]/[Hyperledger AnonCreds] components across frameworks and deployments of those
  frameworks.
* Continuing the execution of the [Community Coordinated Update] to convert the use of [Unqualified DIDs to use `did:peer` DIDs].
* Adding support for [AnonCreds in W3C Verifiable Credentials Data Model Standard] format.
* Load testing Aries components.
* Planning for a transition to [DIDComm V2].

[Community Coordinated Update]: https://github.com/hyperledger/aries-rfcs/tree/main/concepts/0345-community-coordinated-update
[Unqualified DIDs to use `did:peer` DIDs]: https://github.com/hyperledger/aries-rfcs/pull/793
[DID Core Specification]: https://www.w3.org/TR/did-core/
[AnonCreds in W3C Verifiable Credentials Data Model Standard]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/7afcbd7c-2bbc-41ed-bf27-b6ba6e2903c5

# Maintainer Diversity

There are currently 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations.

# Contributor Diversity

In 2023Q3 there were contributions from 64 individuals representing at least 18 organizations.

# Additional Information

None
