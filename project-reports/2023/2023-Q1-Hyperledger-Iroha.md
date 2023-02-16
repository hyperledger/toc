---
layout: default
title: 2023 Q1 Hyperledger Iroha
parent: 2023
grand_parent: Project Updates
---

# Project Health

Currently, the active maintenance of Iroha 1 has stopped, and there are no plans for major releases. There are discussions on releasing the current RC, but this is undecided because it will require more than one team to switch from their everyday tasks to focus on this.
 
All Iroha 2 developers are now fully onboarded and at maximum productivity.

Some work with the Ursa team is ongoing. Thanks to Arun S M, the Iroha 2 BCE team will start collaborating with the Hyperledger Blockchain Explorer team.

# Questions/Issues for the TSC

None.

# Releases

Past quarter releases:

* v2.0.0-pre-rc.9

The release for the [`Iroha v2.0.0-pre-rc.13`](https://github.com/hyperledger/iroha/pull/3134) is planned for February 16th.

# Overall Activity in the Past Quarter

According to the [Iroha Activity Dashboard](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Firoha/dashboard;subTab=technical?time=%7B%22from%22:%222022-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-12-31T07:00:00.000Z%22%7D) for the fourth quarter of 2022 (October-December), the Iroha repo has 143 PRs submitted from 28 contributors.

## Iroha v1

Documentation restoration is in progress.

While DevOps issues temporarily prevent us from fixing it on the default URL, a [forked repository](https://iroha-1-fork.readthedocs.io/en/latest/) is available for the Iroha 1 documentation. This information has been announced to the community.

## Iroha v2

Outstanding PR count: 13, most of which are new. PRs are reviewed and merged in about a week and a half.

To save RAM, the responsibility for storing blocks has been delegated to Kura to keep blocks on disk when they are not in use.

Sumeragi has been restructured; faulty peers are now better supported.

As part of the Sumeragi refactoring, a custom actor pattern was removed from the codebase. Iroha development has moved away from asynchronous Rust code due to its unpredictability. Now Iroha uses manual locks, resulting in sleeping idle code and improved performance.

Soft forks are now being detected and resolved.

Configuration update in progress: whole-chain parameters such as those pertaining to Sumeragi and queue settings as a new type of [Iroha Special Instructions (ISI)](https://hyperledger.github.io/iroha-2-docs/guide/blockchain/instructions.html). Benefits include better semantics and easier sharing through existing consensus mechanisms between peers.

WASM permission validators ([#2596](https://github.com/hyperledger/iroha/issues/2596)) are now supported. The support of inbuilt validators will be removed soon, so only the WASM permission token will be used for the definition parameters ([#2689](https://github.com/hyperledger/iroha/issues/2689)).

The client-side block streaming mechanism now exists as a proof-of-concept. JavaScript SDK already supports it, Java SDK has support in the works.

There is now a query that shows the total amount of assets: `FindAssetTotalQuantitiyBeAssetDefinitionId`.

[JSON version 5](https://json5.org/) is now supported.

The syntax for the `genesis.json` has been simplified and improved.

Observing peers are now brought into consensus to validate if the previous consensus fails.

FFI on the client side is a work in progress. It will be ready in the next Iroha release and dynamic linkage will be supported soon.

# Maintainer Diversity

Currently, the Iroha 2 core development team consists of:

* 8 Rust developers + 1 tech lead
* 1 front-end developer
* 2 full-time QA engineers (functional and load testing/benchmarking)
* 1 full-time technical writer
* 1 full-time DevOps
* 1 community manager who also handles front-end, back-end, DevOps and writing tasks as needed

The maintenance team now consists of the Soramitsu employees. Gregorz Bazior (Yonix Digital Systems, AGH University of Science and Technology) is interested in Iroha 2 and maintains Iroha 1.

# Contributor Diversity

The practice of working with interns has been established and will continue.
