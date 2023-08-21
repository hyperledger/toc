---
layout: default
title: 2023 Q3 Hyperledger Aries
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
nav_exclude: true
---

# Project Health

Hyperledger Aries is healthy, seeing lots of activity overall, especially in all
of the Aries communities, including [Aries Framework JavaScript], [Aries
Bifold] (mobile wallet), [Aries Cloud Agent Python], [Aries VCX] and [Aries
Framework Go]. Lots of progress being made on all of those efforts!

[Aries Framework JavaScript]: https://github.com/hyperledger/aries-framework-javascript
[Aries Bifold]: https://github.com/hyperledger/aries-mobile-agent-react-native
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries VCX]: https://github.com/hyperledger/aries-vcx
[Aries Framework Go]: https://github.com/hyperledger/aries-framework-go

# Questions/Issues for the TOC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   [Aries Cloud Agent Python] -- 0.8.1, 0.8.2, 0.9.0
-   [Aries Framework JavaScript] -- v0.4.0, v0.4.1alpha.1-20
-   [Aries Askar] -- v0.2.9
-   [Aries VCX Releases] -- v0.54.0-v0.57.1
-   [Aries Framework Go] -- v0.2.0, v0.3.0, v0.3.1,v0.3.2
-   [Aries Bifold] -- v0.0.0 - v0.1.0-alpha.53

Interoperability status can be seen
here: [https://aries-interop.info](https://aries-interop.info).

# Overall Activity in the Past Quarter

Per the [Aries Activity Dashboard] for the months of April-June 2023, Aries
codebases had 387 PRs (down 12%) from 70 contributors (down 13%).

[Aries Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222023-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-06-30T07:00:00.000Z%22%7D

* There was a lot of activity towards integrating [Hyperledger
  AnonCreds](https://github.com/hyperledger/anoncreds-rs) into all of the Aries
  Frameworks to enable ledger-agnostic implementations, with the [Aries
  Framework JavaScript] 0.4.0 as the biggest milestone. [Aries Framework
  JavaScript] 0.4.0 includes Aries Askar and the shared components, including
  [Hyperledger AnonCreds], fully integrated, and initial support for
  [OpenID4VCs] protocols.
    * [Aries Bifold] using AFJ 0.4.0 was deployed by adopters with existing
      implementations built on [Aries Framework JavaScript], including push the
      apps to Apple and Google stores. In the process, existing Mobile Wallets
      were updated on the fly from using the Indy SDK to using Askar.
    * Instances of [Aries Framework JavaScript] using non-Indy ledgers were
      deployed and are being used in live use cases.
    * The [Aries Framework JavaScript] Team put on a workshop to cover all the
      new capabilities in [Aries Framework JavaScript] 0.4.0.
* The move away from the [Indy SDK] accelerated over the quarter buoyed by the
  knowledge of the improvements and fixes made in the [AnonCreds CL Signatures]
  implementation now that it has been removed from Ursa and moved to AnonCreds.
  Three of the four Aries implementations ([Aries Cloud Agent Python], [Aries
  Framework JavaScript] and most recently, [Aries VCX]) have integrated the
  shared components in place of the Indy SDK. [Aries Framework Go] has never
  supported Indy ledgers.
* Motivated by the deprecation of the [Indy SDK], there was maintainer
  engagement across three of the Aries implementations ([Aries Cloud Agent
  Python], [Aries Framework JavaScript] and [Aries VCX]) to increase
  reusability, maintain interoperability, and expand efforts at eliminating the
  [Indy SDK].
* A new repository — [aries-socketdock] — will be a key component of a fully scalable
  Aries mediator deployment. The work by [Indicio] is a substantial improvement
  over the current strategy for managing mediator to Mobile Wallet connections
  using websockets. Next up is using [SocketDock] in a full mediator deployment.
* The Overlays Capture Architecture (OCA) Aries RFC (“[OCA for Aries]”) was merged
  and deployment of the feature expanded to include its use in production apps.

[Aries Askar]: https://github.com/hyperledger/aries-askar
[Indy SDK]: https://github.com/hyperledger/indy-sdk
[Hyperledger AnonCreds]: https://github.com/hyperledger/anoncreds-rs
[OpenID4VCs]: https://openid.net/openid4vc/
[ISO mdocs]: https://www.iso.org/standard/74910.html
[AnonCreds CL Signatures]: https://github.com/hyperledger/anoncreds-clsignatures-rs
[aries-socketdock]: https://github.com/hyperledger/aries-socketdock
[SocketDock]: https://github.com/hyperledger/aries-socketdock
[OCA for Aries]: https://github.com/hyperledger/aries-rfcs/tree/main/features/0755-oca-for-aries
[cheqd.io]: https://cheqd.io/
[Cardano]: https://cardano.org/
[Animo Solutions]: https://animo.id
[Indicio]: https://indicio.tech
[DSR]: https://dsr-corporation.com

[OCA Bundles repository]: https://github.com/bcgov/aries-oca-bundles
[OCA Explorer]: https://bcgov.github.io/aries-oca-bundles/

## Aries Framework Reports

### [Aries VCX]

* Interop compatibility improvements
    * Initial did-exchange implementation, working interop with aca-py
* Implementation of new components:
    * `did_doc` - build and work DID documents
    * `did_resolver` - infrastructure for resolving arbitrary did methods
    * `did_parser` - parse and build DIDs
    * `did_sov`, `did_web`, `did:peer` - did:sov, did:web, did:peer resolvers
    * `indy_ledger_response_parser` - data model for indy ledger responses
* Complete transition for anoncreds operations from `libindy` to `credx`
* Additional features for indy-vdr integration
    * Pluggable txn submitter (indy-vdr, indy-vdr-proxy, …)
    * Pluggable txn response caching
    * Pluggable txn signing
* 2 projects LFX mentorship program in progress:
    * [aries-vcx based mediator service](https://wiki.hyperledger.org/display/INTERN/%5Bdraft%5D+Project+Plan+-+aries-vcx+based+message+mediator+service)
    * [uniffi based mobile wrapper](https://wiki.hyperledger.org/pages/viewpage.action?pageId=98730187)

### [Aries Framework JavaScript]

[Aries Framework JavaScript] release 0.4.0 was (as noted above) a major
milestone. The smooth deployment of AFJ 0.4.0 into [Aries Bifold] was
impressive, especially the seamless upgrade of Mobile Wallets from [Indy SDK ]to
[Aries Askar] storage. The addition of [OpenID4VCs] exchange protocols expands
the use cases for [Aries Framework JavaScript]. The maintainers of the [Aries
Framework JavaScript] library are looking to coordinate efforts to support the
EU’s [EUDI/ARF] efforts in at least [Aries Framework JavaScript] and, ideally,
all Aries implementations.

[EUDI/ARF]: https://digital-strategy.ec.europa.eu/en/library/european-digital-identity-architecture-and-reference-framework-outline#:~:text=On%203%20June%202021%2C%20the%20Commission%20adopted%20a,a%20set%20of%20common%20guidelines%20and%20best%20practice

### [Aries Cloud Agent Python]

[Aries Cloud Agent Python] (ACA-Py) Release 0.9.0 was an important upgrade that changes the dependency on the now archived Hyperledger Ursa project to its updated, improved replacement, [AnonCreds CL Signatures]. ACA-Py users are strongly encouraged to use [Aries Askar] for all deployments, and to eliminate the use of the [Indy SDK]. An [Indy SDK to Askar migration document] has been added to the [aca-py.org] documentation site, and a deprecation warning added to the ACA-Py startup.

[aca-py.org]: https://aca-py.org/
[Aries Mediator Service]: https://github.com/hyperledger/aries-mediator-service
[Indy SDK to Askar migration document]: https://aca-py.org/main/deploying/IndySDKtoAskarMigration/

### [Aries Framework Go]

There was a significant uptick in activity around [Aries Framework Go] this quarter.  The focus has been on adding support for the proposed [SD-JWT] verifiable credential approach, as well as updates to the [DIF Presentation Exchange] implementation, and [VC Data Integrity Specification] handling.

[SD-JWT]: https://datatracker.ietf.org/doc/html/draft-fett-selective-disclosure-jwt
[DIF Presentation Exchange]: https://identity.foundation/presentation-exchange/
[VC Data Integrity Specification]: https://w3c.github.io/vc-data-integrity/

# Current Plans

* Completing the work on eliminating the use of the [Indy SDK] in favor of the
  [Aries Askar]/[Indy VDR]/[Hyperledger AnonCreds] across frameworks and deployments of those
  frameworks.
* Continued expansion of features in [Aries Bifold] mobile wallet apps, including building on
  the wallet-to-wallet support added in Q1, and expanding support for OCA to
  enable beautifully displayed credentials.
* Defining and executing a [Community Coordinated Update] to convert the use of [Unqualified DIDs to use `did:peer` DIDs].
* Explore and implement features aligned with the [EUDI/ARF] guidelines.

[Community Coordinated Update]: https://github.com/hyperledger/aries-rfcs/tree/main/concepts/0345-community-coordinated-update
[Unqualified DIDs to use `did:peer` DIDs]: https://github.com/hyperledger/aries-rfcs/pull/793

# Maintainer Diversity

There are currently 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations.

# Contributor Diversity

In 2023Q2 there were contributions from 70 individuals representing at least 18 organizations.

# Additional Information

None
