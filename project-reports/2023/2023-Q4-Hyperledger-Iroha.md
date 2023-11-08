
---
layout: default
title: 2023 Q4 Hyperledger Iroha
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# Project Health

Active maintenance of Iroha 1 has stopped and there are no plans for major releases.

All Iroha 2 developers are now fully onboarded and at maximum productivity.

The integration of Ursa's essential parts to the Iroha codebase continues.

# Questions/Issues for the TSC

None.

# Releases

Past quarter releases:

* v2.0.0-pre-rc.19
* v2.0.0-pre-rc.20 (LTS)

Iroha 1 is in maintenance mode. There are no plans for new releases until the completion of the internship project.

# Overall Activity in the Past Quarter

## Iroha v1

- Upgrade libraries in VCPKG
- Repair the MacOS build

## Iroha v2

### Overall comments

Over the last quarter, the Iroha 2 team has focused on API stability as a prerequisite for the LTS release. Our team updated the SDKs to support the `RC20` release.

Our team has made a significant change in the Iroha stucture, the validator has been promoted to executor, a smart contract that is Iroha's backbone.
Not only does the executor control which operations are allowed to be applied, but it also applies them.
This executor integration improves Iroha’s performance and it also allows arbitrary blockchain manipulation during transaction execution.
When there’s a call to the executor to validate and then execute some transaction or ISI,
it can manipulate the [`world state view`](https://hyperledger.github.io/iroha-2-docs/guide/glossary.html#world-state-view-wsv) in any way necessary.
For example, let’s say that during the account registration, you also want to mint some assets for that new account, the executor will now allow adding such a feature.

Kagami has been refactored and split into multiple tools, namely `iroha_swarm` and `iroha_wasm_builder_cli`.

Domains now have owners. The account that creates a domain becomes its owner. Additionally, domain ownership can be transferred to another account.

The Query request builder has been introduced in the Iroha client API.

Several consensus bugs have been identified and fixed.

### Upcoming activities

* ISA restructuring
* WSV refactoring
* Configuration RFC
* Oracle RFC
* Account restructuring

### Mentorship program

The mentees are positive about the knowledge they gain during the process.
* [Yasser Arguelles Snape](https://github.com/RealNeGate) learned about the Rust procedural macros in a relatively short period of time, gaining useful experience while writing a [DSL](https://wiki.hyperledger.org/display/INTERN/Iroha+2%3A+DSL).
* [Kshitij Roodkee](https://github.com/horizenight) learned a lot of useful things about Vue and Rust while working on the [Blockchain Explorer](https://wiki.hyperledger.org/display/INTERN/Iroha+2%3A+blockchain+explorer+update). In addition to learning technical skills, he claims to have improved soft skills too, such as his collaboration skills, the principle of structuring PRs, and appropiately addressing comments.
* [Orange Ng](https://github.com/orangeng) shared that he learned a lot during the [FFI mentorship project](https://wiki.hyperledger.org/display/INTERN/Project+Plan+-+Iroha+2%3A+FFI+client+library+bindings), especially about the Rust language and parsing the source code. He is enjoying the mentorship program and works on his soft skills as well.

At the moment, their mentorship continues, so it's too early to announce the final results.

# Maintainer Diversity

Currently, the Iroha 2 core development team consists of:

* 9 Rust developers
* 2 full-time QA engineers
* 2 full-time technical writers
* 1 community manager
* 1 project manager
* 1 DevOps

The maintenance team is currently comprised of SORAMITSU employees. [Gregorz Bazior](https://github.com/baziorek) (Yonix Digital Systems, AGH University of Science and Technology) is interested in Iroha 2 and maintains Iroha 1.

# Contributor Diversity

The practice of working with interns is now established and will continue.
There is interest from a potential security-oriented intern, and we're in the process of discussing the topics to tackle.

# Features

# Prior reports

* [2023, Quarter 1](https://toc.hyperledger.org/project-reports/2023/2023-Q1-Hyperledger-Iroha.html)
* [2023, Quarter 2](https://toc.hyperledger.org/project-reports/2023/2023-Q2-Hyperledger-Iroha.html)
* [2023, Quarter 3](https://toc.hyperledger.org/project-reports/2023/2023-Q3-Hyperledger-Iroha.html)
