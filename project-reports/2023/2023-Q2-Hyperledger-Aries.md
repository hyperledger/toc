---
layout: default
title: 2023 Q2 Hyperledger Aries
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
nav_exclude: true
---

# Project Health

Hyperledger Aries has seen a lot of activity overall, especially in the
[Aries Framework
JavaScript](https://github.com/hyperledger/aries-framework-javascript), [Aries
Bifold](https://github.com/hyperledger/aries-mobile-agent-react-native) (mobile
wallet), and [Aries VCX](https://github.com/hyperledger/aries-vcx) communities.
Lots of progress being made in those projects!

The following are the highlights from this past quarter:

-   Lots of activity towards integrating [Hyperledger AnonCreds] into
    all of the Aries Frameworks to enable ledger-agnostic implementations.
    - Aries Bifold using [Hyperledger AnonCreds] has been demonstrated, as
    has deployments of [Aries Framework JavaScript] using AnonCreds objects
    rooted in [cheqd.io] and [Cardano].
    - BC Gov published an [AnonCreds Code With Us Opportunity] to integrate
    [Hyperledger AnonCreds] into [Aries Cloud Agent Python]. [Indicio]
    won that Opportunity and is working the implementation.
- An implementation of [OpenID4VCs] (issuance) with [Aries Framework JavaScript]
has been completed. This is the first experiment in using [OpenID4VCs] with Aries.
The community is also considering the feasibility of issuing and presenting [ISO
mdocs] verifiable credentials using Aries Frameworks.
-   The effort to move off the Indy SDK continued this quarter with the
    following results:
    - BC Gov published an [Askar Code With Us Opportunity] to create a
    conversion script from Indy SDK to [Aries Askar] storage. [Indicio]
    won that Opportunity, completed that implementation, and the
    result has been used to convert a production system.
    - [Animo Solutions] won a similar [AFJ Askar Code With Us Opportunity] and
    has demonstrated a deployment of [Aries Bifold] using Aries Askar storage.
-   After being awarded a BC Gov [Mobile Verifier Code With Us] opportunity, [DSR]
    implemented in the Aries Bifold wallet the ability for one wallet to request
    a presentation from another wallet, and for two wallets to establish a connection
    and communicate (messaging and presentation requests).
-   Discussions continue on Aries Interop Profile (AIP) v3.0, which extend
    AIP 2.0 to be based on DIDComm V2, and a number of Aries community
    members contributed to a DIDComm V2.0 Connect-a-thon at IIW.
-   Continued good progress was made in the community on the use of [Overlays
    Capture Architecture](https://oca.colossi.network/) (OCA) to power the
    on-screen display of credentials, as mentioned in previous reports. An Aries
    RFC has been proposed and gone through a couple of iterations, with good
    feedback -- [OCA for Aries RFC
    PR](https://github.com/hyperledger/aries-rfcs/pull/755), [OCA for Aries RFC
    (proposed)](https://github.com/swcurran/aries-rfcs/tree/oca4aries/features/0755-oca-for-aries)
    and [OCA for Aries Style Guide
    (proposed)](https://github.com/swcurran/aries-rfcs/tree/oca4aries/features/0756-oca-for-aries-style-guide).
    -   OCA has been implemented in [Aries Bifold]. However, we have had a
    challenge in figuring out the best way to distribute OCA Bundles. As a short
    cut around the problem the community has created a GitHub [OCA Bundles
    repository], with a governance model allowing anyone to submit a (valid) OCA
    Bundle for their credential type. The repo is currently in the BC Gov
    GitHub organization, but may be moved as OCA Bundles become more prevalent in the
    community. A tool, the [OCA Explorer] has been built to make it easy to see
    and evolve OCA Bundles implementations. Check it out!

[Aries Framework JavaScript]: https://github.com/hyperledger/aries-framework-javascript
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python
[Aries Bifold]: https://github.com/hyperledger/aries-mobile-agent-react-native
[Aries VCX]: https://github.com/hyperledger/aries-vcx
[Aries Askar]: https://github.com/hyperledger/aries-askar
[Hyperledger AnonCreds]: https://github.com/hyperledger/anoncreds-rs
[AnonCreds Code With Us Opportunity]:  https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/6b720b90-133e-49a8-bb33-bb97c5d222bf
[Askar Code With Us Opportunity]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/5992f66c-b2ac-4b2a-a3a3-3eb3473e9eca
[AFJ Askar Code With Us Opportunity]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/b454a434-69fd-42fa-a90d-3ce614d5523b
[Mobile Verifier Code With Us]: https://marketplace.digital.gov.bc.ca/opportunities/code-with-us/1b4e02e9-8a2e-4970-9f12-fb2f0a827ea1
[OpenID4VCs]: https://openid.net/openid4vc/
[ISO mdocs]: https://www.iso.org/standard/74910.html
[cheqd.io]: https://cheqd.io/
[Cardano]: https://cardano.org/
[Animo Solutions]: https://animo.id
[Indicio]: https://indicio.tech
[DSR]: https://dsr-corporation.com

[OCA Bundles repository]: https://github.com/bcgov/aries-oca-bundles
[OCA Explorer]: https://bcgov.github.io/aries-oca-bundles/

## Aries Framework Reports

### [Aries VCX]

- Rewrite of [Aries messages crate](https://github.com/hyperledger/aries-vcx/tree/main/messages)
    - Performance improvements
    - Overall code quality improvements
- Rewrite of NodeJS wrapper
    - unlocked upgrade to NodeJS 18
    - 20x FFI performance improvement
    - significantly improved safety and maintainability
- Enabled usage of aries-vcx with [Aries Askar] plugged-in
- Enabled opt-in usage of credx library for proof verifier (libindy)
- Adoption of new approach building Aries state machines
    - fully leverages power of Rust typing system
    - so far applied on Connection protocol (other protocols in progress/pending)
- Interop compatibility improvements
- 2 projects rolled into LFX mentorship program
    - [aries-vcx based mediator service](https://wiki.hyperledger.org/display/INTERN/aries-vcx+based+message+mediator)
    - [uniffi based mobile wrapper](https://wiki.hyperledger.org/display/INTERN/aries-vcx+next-gen+mobile+wrapper)
- Break down of repo into smaller crates, decoupling of mediation from Connection protocol, other general refactoring

[Aries VCX]: https://github.com/hyperledger/aries-vcx

### [Aries Framework JavaScript]

[Aries Framework JavaScript] has made significant progress in the first
quarter of 2023. The bulk of the work has been towards implementing
ledger-agnostic AnonCreds, with an initial implementation for Hyperleger Indy,
and the work on [cheqd.io] integration started. The integration of the new shared
components (Aries Askar, AnonCreds RS and Indy VDR) has been implemented.

All the work has been going into preparation for the 0.4.0 release of Aries
Framework JavaScript, which will be the first release of the framework that is
truly ledger-agnostic. 

In addition, work has been done to expand the supported exchange protocols to
include OpenID4VCI, allow credentials to be received and shared using different
protocols.

### [Aries Cloud Agent Python]

[Aries Cloud Agent Python] v0.8.0 was released in 2023Q1, with contributions
from 32 individuals. Work this quarter was focused on enabling upgrades
of existing deployments to [Aries Askar], the use of ACA-Py
as an Aries Mediator (the [Aries Mediator Service] repository), updating
ACA-Py to use Hyperledger AnonCreds, and the launch of a new ACA-Py
documentation site [aca-py.org]

[aca-py.org]: https://aca-py.org/
[Aries Mediator Service]: https://github.com/hyperledger/aries-mediator-service

The Indy/Aries stack continues to be the global leader in SSI/verifiable
data solutions, with AnonCreds the most used credential format.

# Questions/Issues for the TOC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python -- 0.8.0-rc0, 0.8.0
-   Aries Framework JavaScript -- v0.3.2, v0.3.3, 0.3.4-alpha0 to 0.3.4-alpha17, 0.4.0-alpha18 to 0.4.0-alpha95
-   Aries Askar -- v0.2.8
-   Aries VCX Releases -- v0.3.4, v0.4.0-dev1 to v0.4.0-dev12
-   Aries Framework Go -- v0.1.9

Of the 28 Aries repositories, all but 3 have been updated in 2023.

Interoperability status can be seen
here: [https://aries-interop.info](https://aries-interop.info).

# Overall Activity in the Past Quarter

Per the [Aries Activity Dashboard](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222023-01-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-03-31T07:00:00.000Z%22%7D) for the first three months of 2023, Aries
codebases had 442 PRs (up 11%) from 81 contributors (up 21%).

# Current Plans

-   Continuing the work on eliminating the use of the Indy SDK in favor of the
    Aries Askar/Indy VDR/anoncreds-rs across frameworks and deployments of those
    frameworks.
-   Continued expansion of features in mobile wallet apps, including building on
    the wallet-to-wallet support added in Q1, and expanding support for OCA to
    enable beautifully displayed credentials.
-   Continue the work to adding ledger agnostic Hyperledger AnonCreds support in
    all of the active Aries Frameworks.
-   Promotion of a place for issuers to publish and wallets/verifiers to use
    Overlays Capture Architecture (OCA) bundles.
-   Rust [DID resolver, DID parser](https://github.com/hyperledger/aries-vcx/pull/812) in Aries VCX
    - Not specific to Aries
    - Currently implementing did:sov only, did:indy, did:web will be added next

# Maintainer Diversity

There are currently 62 people on the 48 Hyperledger Aries teams representing at least 19 organizations.

# Contributor Diversity

In Q1 there were contributions from 81 individuals representing at least 16 organizations.

# Additional Information

Nothing

# Submission date

03-May-2023

# Reviewed by

-   🔲 Arnaud J Le Hors
-   🔲 Arun S M
-   🔲 Bobbi Muscara
-   🔲 David Enyeart
-   🔲 Jim Zhang
-   🔲 Marcus Brandenburger
-   🔲 Peter Somogyvari
-   🔲 Ramakrishna V
-   🔲 Stephen Curran
-   🔲 Timo Glastra
-   🔲 Tracy Kuhrt
