---
layout: default
title: 2023 Q2 Hyperledger AnonCreds
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2023 Q2 Hyperledger AnonCreds

Created by Stephen Curran.

## Implementation Repositories

- [anoncreds-rs] - Rust implementation of AnonCreds
- [anoncreds-clsignatures-rs] - Rust implementation of CL Signatures used in [anoncreds-rs]. Moved from Ursa.

[anoncreds-rs]: https://github.com/hyperledger/anoncreds-rs
[anoncreds-clsignatures-rs]: https://github.com/hyperledger/anoncreds-clsignatures-rs

### Specifications

- [AnonCreds Specification] published from the repository [anoncreds-spec]
- [AnonCreds Methods Registry] published from the repository [anoncreds-methods-registry]
- [AnonCreds v2.0 Specification] published from the repository [anoncreds-spec-v2]

[anoncreds-spec]: https://github.com/hyperledger/anoncreds-spec
[AnonCreds Specification]: https://hyperledger.github.io/anoncreds-spec/
[anoncreds-methods-registry]: https://github.com/hyperledger/anoncreds-methods-registry
[AnonCreds Methods Registry]: https://hyperledger.github.io/anoncreds-methods-registry
[anoncreds-spec-v2]: https://github.com/hyperledger/anoncreds-spec-v2
[AnonCreds v2.0 Specification]: https://hyperledger.github.io/anoncreds-spec-v2/

### Web and Wiki Pages

- [Hyperledger AnonCreds Website Home Page]
- [Hyperledger AnonCreds Wiki Home Page]

[Hyperledger AnonCreds Website Home Page]: https://www.hyperledger.org/use/anoncreds
[Hyperledger AnonCreds Wiki Home Page]: https://wiki.hyperledger.org/display/ANONCREDS/

## Project Health

The project is healthy with a lot of work going on in the code base ([anoncreds-rs]) to
complete the transition of the Rust implementation from an Indy repository to an
AnonCreds repository. In doing that, the implementation has been made ledger-agnostic, and the
[AnonCreds Specification] adjusted to align with the implementation. Happily, the
changes were relatively small and helped to clarify the specification.

## Questions/Issues for the TSC

None.

## Releases

- [anoncreds-rs] -- [v0.1.0-dev.1] through [v0.1.0-dev.12] (12 releases)

[v0.1.0-dev.1]: https://github.com/hyperledger/anoncreds-rs/releases/tag/v0.1.0-dev.1
[v0.1.0-dev.12]: https://github.com/hyperledger/anoncreds-rs/releases/tag/v0.1.0-dev.12

## Overall Activity in the Past Quarter

The AnonCreds project has made significant progress on three fronts this quarter:

- The [anoncreds-rs] implementation evolved significantly has it was added as
  dependencies in [Aries Framework JavaScript] and later, into [Aries Cloud
  Agent Python], replacing the previous Indy libraries. The work was focused
  more on the wrappers for JavaScript and Python to enable using the component
  in the Aries frameworks, and CI/CD updates. Adjustments to certain library
  calls were made to enable ledger-agnosticism, particularly around the handling
  of revocation registries. Several groups have already demonstrated the use of
  the library with other than Hyperledger Indy-hosted objects, including ones
  hosting objects on [Cheqd](https://cheqd.io), [Cardano](https://cardano.org/),
  and using [did:web](https://learn.mattr.global/tutorials/dids/did-web).
- As adjustments to the implementation were made, alignment was made with the
  AnonCreds v1.0 specification. The adjustments were minor and were done such that
  existing, issued AnonCreds credentials would still be useable.
- Work began in the AnonCreds v2.0 specification (see below for details)

An AnonCreds v2.0 Working Group has begun meeting bi-weekly to discuss the "next
generation" of AnonCreds.  So far we have discussed the AnonCreds data objects,
including what would be published by the issuer to the Ledger, credentials, and
presentations, plus a potential revocation scheme ([ALLOSAUR], [ALLOSAUR Summary]) that could be
used. The design that Mike Lodder has defined enables the use of several cryptographic
suites to sign the credentials. The working group is now discussing the details of
how to transition the proposals into the v2.0 Specification.

The [AnonCreds Quarterly Activity Dashboard] shows the activity on the repo,
with 238 commits by 18 contributors in the quarter. The majority of the recent
work has been in the wrappers (JavaScript and Python) in order to reference the
component in the [Aries Framework JavaScript] and [Aries Cloud Agent Python]
Aries Frameworks.

[ALLOSAUR]: https://eprint.iacr.org/2022/1362
[ALLOSAUR Summary]: https://sam-jaques.appspot.com/allosaur
[AnonCreds Quarterly Activity Dashboard]: https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fanoncreds/dashboard;subTab=technical?time=%7B%22from%22:%222023-01-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-03-31T07:00:00.000Z%22%7D
[Aries Framework JavaScript]: https://github.com/hyperledger/aries-framework-javascript
[Aries Cloud Agent Python]: https://github.com/hyperledger/aries-cloudagent-python

## Current Plans

Work continues on getting a final `v0.1.0` release completed with the details in
the wrappers stabilized. With the end-of-life of the Hyperledger Ursa project, a
new AnonCreds repository is needed to host the CL-Signatures code used in
[anoncreds-rs], and producing artifacts from that new repository. In theory,
that should be a straightforward transfer of code from the existing Ursa
repository.

On the specifications side, completing the v1.0 specification has slowed, as the
final work to be completed is the documentation of the cryptographic math used
in the processing. For that work, the project has proposed a Hyperledger Mentorship
be awarded, as documented in the [AnonCreds Mentorship proposal]. As well, work
will soon begin on filling in the details of the [AnonCreds v2.0 Specification]
as a formal document.

[AnonCreds Mentorship proposal]: https://wiki.hyperledger.org/display/INTERN/Document%2C+Review%2C+and+Implement+Hyperledger+AnonCreds+ZKP+Cryptographic+Primitives

## Maintainer Diversity

Project Maintainers are from three different organizations: Animo Solutions, BC Gov, and SICPA.

## Contributor Diversity

Contributions in the quarter have come from at least 8 different organizations, including Animo Solutions, Roots ID, Indicio and BC Gov.

## Additional Information

- Key channels on Hyperledger Discord: \#anoncreds, \#anoncreds-spec,
\#anoncreds-rs
- [AnonCreds Mailing List](https://lists.hyperledger.org/g/anoncreds)
- Meetings pages
    - [AnonCreds Specification Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+Specification+Working+Group)
    - [AnonCreds v2.0 Working Group](https://wiki.hyperledger.org/display/ANONCREDS/Meetings%3A+AnonCreds+v2.0+Working+Group)
