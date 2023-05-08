---
layout: default
title: 2023 Q2 Hyperledger Iroha
parent: 2023
grand_parent: Project Updates
---

# Project Health

Currently, active maintenance of Iroha 1 has stopped and there are no plans for major releases. However, discussions to release the current RC continue because it will require more than one team switching from everyday tasks to focus on this.

All Iroha 2 developers are now fully onboarded and at maximum productivity.

Since development of the Ursa project has been discontinued, the Iroha team is rewriting its essential parts to integrate in the Iroha codebase. In addition, thanks to Arun S M, the Iroha 2 BCE team will start collaborating with the Blockchain Explorer, a Hyperledger Lab, team.

# Questions/Issues for the TOC

None.

# Releases

Past quarter releases:

* v2.0.0-pre-rc.13 (internal)
* v2.0.0-pre-rc.14 (internal)
* v2.0.0-pre-rc.15 (internal)

# Overall Activity in the Past Quarter

According to the [Iroha Activity Dashboard](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Firoha/dashboard;subTab=technical?time=%7B%22from%22:%222023-01-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-03-31T07:00:00.000Z%22%7D) for the first quarter of 2023 (January-March), the Iroha repo has 129 PRs submitted by 28 contributors.

## Iroha v1

We are restoring the old documentation for the Iroha v1 project using a different hosting solution, as the previous solution was terminated. This is going to be used temporarily for support of the deprecated version of Iroha v1 documentation. 

Iroha 1 has its own mentorship project: "[Extend queries with optional arguments](https://mentorship.lfx.linuxfoundation.org/project/06a25b14-a56e-4294-a89d-05f1dc74106c)".
The mentors on this project are: [Andrzej Gruntowski](https://github.com/andprogrammer), [Grzegorz Bazior](https://github.com/baziorek) and [Aleksandr Petrosyan](https://github.com/appetrosyan).

## Iroha v2

### Code updates

Builtin validators were replaced with runtime validators. Now it is possible to plug in any kind of custom user-defined validation. Work is ongoing to finalise the architecture of permission verifiers. 

The `WASM` smartcontracts now have a logging feature, which is intended to help with debugging. ([#3264](https://github.com/hyperledger/iroha/pull/3264))

A new pipeline event has been added: "transaction expired" ([#3010](https://github.com/hyperledger/iroha/issues/3010), [`067842`](https://github.com/hyperledger/iroha/commit/06784290b192d2d942426763874d4cc49d0485f0)) which improves transaction processing under a high load.

Topology rotation was rewritten:
- Previously, it was possible for the leader to manipulate the block and affect the topology in the next consensus round
- Topology is not calculated based on hash of the current block anymore, it's determined from the previous topology and the view change index

The `iroha_client_cli` output is now machine readable, leading to improved tests.

The dependency on the unstable feature `default_alloc_error_handler` is not needed anymore in WASM smart contracts. It was fixed by using the stable default allocator handler ([#3303](https://github.com/hyperledger/iroha/pull/3303)) [^1]:

- Iroha doesn't depend on any unstable features anymore
- `data_model` structs are now opaque to the client / `WASM` code
- This was an effort to maximize portability and maintain the same API for client apps and `WASM` smartcontracts
- All fields have been made opaque and can be accessed through getter functions

The Iroha 2 schema was refactored:

- Every name in the codebase is globally unique
- Prefixes from type names have been removed
- The schema file is now sorted lexicographically

Legacy configurations have been added to Iroha. ([#3183](https://github.com/hyperledger/iroha/commit/ac32c4934d43ef85445a5e9c70711f1582be3269))

The `AssetDefinition` now has a logo field. ([#3389](https://github.com/hyperledger/iroha/pull/3389))

Iroha 2 now uses Tokio actors. This allows us to use industry standard instrumentation to diagnose deadlocks, starvation and other previously undiagnoseable problems. ([#3362](https://github.com/hyperledger/iroha/issues/3362))

Additionally an SDK based off of using `iroha_client_cli` and a common JSON API was proposed, and will be merged.

### Documentation updates

We have conducted a revision of the original Iroha v2 tutorial to identify issues and outdated content. We have onboarded two new technical writers and have constructed a roadmap of advanced explanations. Work is underway for addition of detailed iroha_client_cli documentation as well as additional elements regarding architectural design. We plan to expand the tutorial with a section that was used as a formal reports for one of our internal projects.

### Mentorships

There are three mentorship streams currently accepting mentees for Iroha 2.

* [Hyperledger - Iroha 2 FFI client library bindings](https://mentorship.lfx.linuxfoundation.org/project/8a6b5853-369c-48e6-9445-98520a8c28dc)
* [Hyperledger - Iroha 2 blockchain explorer update](https://mentorship.lfx.linuxfoundation.org/project/24e1907b-c8e0-488c-aa24-1fbddb9df886)
* [Hyperledger - Iroha 2 DSL](https://mentorship.lfx.linuxfoundation.org/project/cda1496b-0c36-4c1b-98b5-dee5d95f494a)

# Maintainer Diversity

Currently, the Iroha 2 core development team consists of [SORAMITSU](https://soramitsu.co.jp/) employees:

* 8 Rust engineers + 1 tech lead
* 1 front-end developer
* 3 full-time QA engineers (functional and load testing/benchmarking)
* 1 full-time technical writer
* 1 full-time DevOps
* 1 community manager who also handles front-end, back-end, DevOps and writing tasks as needed

Iroha 2 core team is actively working on attracting talents through [Hyperledger Mentorship Program](https://wiki.hyperledger.org/display/INTERN/Hyperledger+Mentorship+Program) as shown above to considerably boost the maintainer diversity.

Gregorz Bazior (Yonix Digital Systems, AGH University of Science and Technology) maintains Iroha 1 and he is also interested in Iroha 2.

# Contributor Diversity

The practice of working with interns has been established and will continue.

[^1]: [Default `alloc` error handler](https://blog.rust-lang.org/2023/03/09/Rust-1.68.0.html#default-alloc-error-handler)
