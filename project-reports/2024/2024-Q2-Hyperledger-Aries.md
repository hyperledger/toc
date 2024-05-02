---
layout: default
title: 2024 Q2 Hyperledger Aries
parent: 2024
grand_parent: Project Updates
has_children: false
has_toc: false
nav_exclude: true
---

# Project Health

The newly divided [Hyperledger Aries] continues at a healthy pace, seeing lots of
activity in most of the Aries sub-communities, albeit with some in different
homes. As covered in the [Aries Annual Report], the former Aries Framework
JavaScript and Aries Bifold (mobile wallet) are now housed at the
[Open Wallet Foundation] as [Credo-TS] and [Bifold Wallet], respectively.
[Aries Cloud Agent Python] and a set of related Aries repositories remain very
active within the [Hyperledger Foundation], with new releases and plans to
(finally!) publish a 1.0 version.

ACA-Py was recently celebrated as a runner-up in the
[Future of Government Awards] "Open Source Creation" category by the UN Development
Programme, the AWS Institute and Public Digital. This is a global award with and
ACA-Py was competing against over 300 nominated open source projects.

A new, human friendly publication of the [Aries RFCs] was created. This long
overdue addition is an alternative to navigating the [Aries RFCs repository],
which is pretty horrible. The new, GitHub Action-generated site includes a
specific list of the subset of RFCs that make up [Aries Interop Profile 2.0].
While this is a great start, there remains more work to be done to complete the
publication -- a [list of todos].

[Future of Government Awards]: https://futureofgovernment.com/en
[Aries RFCs]: https://hyperledger.github.io/aries-rfcs
[Aries RFCs repository]: https://github.com/hyperledger/aries-rfcs
[list of todos]: https://github.com/hyperledger/aries-rfcs/issues/825
[Aries Interop Profile 2.0]: https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0302-aries-interop-profile#aries-interop-profile-version-20

The [Aries VCX] framework has recently lost its primary supporter, [ABSA] and as
a result is "available" for other sponsors to pick up as a mature, capable, open
source Aries Framework, written in Rust. At least one of the lead maintainers is
a contractor and as such, might also be interested in continuing the ground
breaking work the team has been doing.  We'll monitor the activity around Aries
VCX to see if the repository needs to be archived, or if another interested
party will be developing it further.

The [Aries Framework Go] repository has also been abandoned by its previous
organizational sponsor [Gen Digital] and archived. Some of the code
within the repository, notably the [BBS Signatures Go] implementation has been
extracted from the archived repository.

[Hyperledger Aries]: https://www.hyperledger.org/projects/aries
[Aries Annual Report]: https://toc.hyperledger.org/project-reports/2024/2024-annual-Hyperledger-Aries.html
[Credo-TS]: https://github.com/openwallet-foundation/credo-ts
[Bifold Wallet]: https://github.com/openwallet-foundation/bifold-wallet
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx
[ABSA]: absa.co.za
[Aries Framework Go]: https://github.com/hyperledger/aries-framework-go
[Gen Digital]: https://www.gendigital.com
[BBS Signatures Go]: aries-bbs-go
[Open Wallet Foundation]: https://openwallet.foundation/
[Hyperledger Foundation]: https://hyperledger.org

# Questions/Issues for the TOC

Suggestions on what to do with [Aries VCX]. One thought is
a Webinar on what the code base contains to publicize the fact
that the it is "up for grabs" for anyone interested.

# Releases

The following Aries releases occurred in the last two quarters (including the
time covered by the Annual Report and so not yet reported):

- [Aries Cloud Agent Python] -- 0.10.4, 0.10.5, 0.11.0
- [Credo-TS] -- v0.4.2, v0.5.0, v0.5.1 (will remove this from future reports)
- [Aries Askar] -- v0.3.0, v0.3.1
- [Aries VCX] -- v0.59.1, v0.60.0, v0.61.0, v0.62.0, v0.63.0
- [Aries Bifold] -- v1.0.0-alpha.108-215

Interoperability status can be seen
here: [https://aries-interop.info](https://aries-interop.info).

# Overall Activity in the Past Quarter

Per the [Aries Activity Dashboard] for the months of January-March 2024, Aries
codebases had 698 PRs (up 40%) from 155 contributors (down -5%). Those numbers
are up significantly from the previous Quarterly Report (2023-Q4). The numbers
do include the repositories that have moved from Hyperledger to the Open Wallet
Foundation, as well as some obsolete (but unchanging) repositories. Per Ry Jones
there is not a good way for us to control the included list of repos.

[Aries Activity Dashboard]: https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=aries&repository=all&dateFilters=Last%20Quarter&dateRange=2024-01-01%20to%202024-03-31&compare=PP&granularity=week&hideBots=true

* Load testing on ACA-Py as a server component produced good results. BC Gov's
  tests showed that we had more than enough issuing capacity for our needs for
  the forseeable future. The [Aries Akrida] tool developed and released by
  [Indicio PBC] in response to a BC Gov "Code With Us" [Aries Load Test Generator]
  open source procurement has proven to be an extremely capable Aries/DIDComm
  load testing tool. Easy to use and very powerful!
* The PR for removing the [Indy SDK] from ACA-Py is in review and will soon
  be merged, eliminating the older component in favour of newer and more capable
  replacements ([Aries Askar], [Indy VDR], and [AnonCreds-RS]). Good to see that
  transition!
  * **NOTE: THIS DOES NOT REMOVE INDY SUPPORT FROM ACA-PY!**
* Support for AnonCreds in W3C VCDM Format in Aries has been implemented in
  [Credo-TS] and [Bifold Wallet], with the PR to add support in [ACA-Py]
  expected to be merged soon.
* Work has begun on adding [DIDComm v2] support in [ACA-Py].
* We expect to soon start on adding support for a new, web-based DID Method,
  "Trust DID Web" (did:tdw) to [ACA-Py] and [Credo-TS] shortly. `did:tdw`
  combines the simplicity of `did:web` with features expected only with a
  ledger-based DID Method.

[Aries Askar]: https://github.com/hyperledger/aries-askar
[Indy SDK]: https://github.com/hyperledger/indy-sdk
[Hyperledger AnonCreds]: https://github.com/hyperledger/anoncreds-rs
[Aries Cloud Agent Python plugins]: https://github.com/hyperledger/aries-acapy-plugins
[Indicio PBC]: https://indicio.tech
[Aries Akrida]: https://github.com/Indicio-tech/aries-akrida
[Aries Load Test Generator]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/51d7c289-51a8-4307-939c-5a4271c7b2b6

## Aries Framework Reports

### [Aries VCX]

Work continued on Aries VCX through the end of the quarter, and through the end of April,
but has no longer funded. To be determined if someone else picks up the work, or if
the Framework will be archived.

It is a lot of great code!

### ~~Aries Framework JavaScript~~ [Credo-TS]

The former Agent Framework JavaScript has moved to the Open Wallet Foundation
(OWF) as [Credo-TS]. Reporting on the framework has shifted to OWF.

### [Aries Cloud Agent Python]

[Aries Cloud Agent Python] (ACA-Py) work in the quarter included the following highlights:

* Completion of [Aries Interop Profile 2.0](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0302-aries-interop-profile#aries-interop-profile-version-20)
* Completion of work to enable the transition from the use of unqualified DIDs, and to [DIDComm V2].
* Support for the ledger-agnostic [Hyperledger AnonCreds].
* Maintenance and performance optimizations.
* Evolving the release management processes of the [Aries Cloud Agent Python plugins] repository -- an "app
  store" for modular extensions to ACA-Py.
* A very large volume of updates, enhancements, fixes.
* Load testing of deployed instances of ACA-Py.
* Deprecation announcements about older features we want to see phased out.
* Preparation for the v1.0.0 release of ACA-Py.
* Exploratory work on adding [DIDComm v2] support to ACA-Py.

# Current Plans

* Release v1.0.0 of ACA-Py.
* Completing the work on eliminating the use of the [Indy SDK] in favor of the
  [Aries Askar]/[Indy VDR]/[Hyperledger AnonCreds] components across frameworks and deployments of those
  frameworks.
* Continuing the execution of the [Community Coordinated Update] to convert the use of [Unqualified DIDs to use `did:peer` DIDs].
* Finalizing and deploying support for [AnonCreds in W3C Verifiable Credentials Data Model Standard] format.
* Continuing working to add support for [DIDComm V2].

[Community Coordinated Update]: https://github.com/hyperledger/aries-rfcs/tree/main/concepts/0345-community-coordinated-update
[Unqualified DIDs to use `did:peer` DIDs]: https://github.com/hyperledger/aries-rfcs/pull/793
[AnonCreds in W3C Verifiable Credentials Data Model Standard]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/7afcbd7c-2bbc-41ed-bf27-b6ba6e2903c5

# Maintainer Diversity

There are currently 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations.

# Contributor Diversity

In 2023Q3 there were contributions from 64 individuals representing at least 18 organizations.

# Additional Information

None
