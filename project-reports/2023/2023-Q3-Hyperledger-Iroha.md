---
layout: default
title: 2023 Q3 Hyperledger Iroha
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
---

# Project Health

Currently, active maintenance of Iroha 1 has stopped and there are no plans for major releases.
The release `2.0.0-pre-rc.18` is officially merged and stable as of July 31th.

All Iroha 2 developers are now fully onboarded and at maximum productivity.

The integration of Ursa essential parts to the Iroha codebase continues.

# Questions/Issues for the TSC

- No indexing on [2023](https://wiki.hyperledger.org/display/TSC/2023+Project+Updates) page
- LFX interface [caused problems](https://community.lfx.dev/t/lfx-mentorship-platform-issues/2130) for candidate vetting/selection, and internship allocations

# Releases

Past quarter releases:
* v2.0.0-pre-rc.15
* v2.0.0-pre-rc.16
* v2.0.0-pre-rc.17
* v2.0.0-pre-rc.18

Iroha 1 is in maintenance mode. No releases are planned until the completion of the internship project.

# Overall Activity in the Past Quarter

According to the [Iroha Activity Dashboard](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Firoha/dashboard;subTab=technical?time=%7B%22from%22:%222023-04-01T06:38:18.000Z%22,%22type%22:%22absolute%22,%22to%22:%222023-07-31T21:00:00.000Z%22%7D) for the third quarter of 2023 (April-June), the Iroha repo has 228 PRs submitted by 44 contributors.

## Iroha v1

The project is in maintenance mode. It has a minor breakage for outdated platforms. The fix is to update the build system to `ninja` from `CMake`, but it is held off so as not to interfere with the internship project and the restoration of the CI for the last releases of the v1 branch, which is planned to happen in Q4 2023 or Q1 2024.

### Mentorship program

- Iroha 1: [extend queries with optional arguments](https://wiki.hyperledger.org/display/INTERN/Iroha+1%3A+extend+queries+with+optional+arguments) — [Tomasz Grun](https://github.com/dominious1)

# Iroha v2

## Overall comments

The team has been focused on providing a stable base for internal projects, mainly on improving the UI/UX, optimisations and stability improvements. In addition to that, the mentorships are progressing well.

The maintainers' main focus was establishing reliable integration tests via `pytest` and `allure` to supplement the bare-bones Rust testing infrastructure.

Major developments have been made in the supporting SDKs, as well as supporting tools; namely, 
the block squash tool is now capable of graceful handling of the `pre-rc.9` to `pre-rc.18` inclusive upgrades.
Field deployment of this tool allowed us to identify flaws in the deserialisation pipeline ([#3330](https://github.com/hyperledger/iroha/issues/3330)).

The capabilities of `kagami` have been greatly expanded. The blockchain explorer is in progress of being updated to work with the latest Iroha thanks to [Kshitij Roodkee](https://github.com/horizenight), our mentee, who is mentored by [Dmitry Balashov](https://github.com/0x009922/).

Some procedural changes; due to a pile-up of long-lived and difficult to resolve pull requests, mainly due to the complexity of the Runtime upgradeable validator and later Executor systems, every Monday, a thorough *PR triage* with assignment is performed. This is synchronised with the relevant updates from the two mentees working on the core repository.

The SDK compatibility has been raised as a prime concern. As such we are designing a comprehensive SDK compatibility system, with test coverage and a feature matrix. Anticipating the move to dynamic linkage, we also prepare coherence tests, which should identify double coverage of the same feature set, and supplements to support `async` co-operative non-blocking concurrency through the FFI boundary.

The work on the FFI for WASM smartcontracts is temporarily halted, as [Marin Veršić](https://github.com/mversic) had been promoted to technical lead on a parallel project, involved greatly with the `iroha-java` SDK.

## Upcoming activities: 

- ISA restructuring 
- Account restructuring
- Private and Public blockchain executors

## Maintainer Diversity

Currently, the Iroha 2 core development team consists of:

* 8 Rust developers + 1 PM + 1 tech lead
* 1 front-end developer
* 2 full-time QA engineers
* 2 full-time technical writers
* 1 part-time DevOps
* 1 community manager who also handles front-end, back-end, DevOps and writing tasks as needed

The maintenance team is currently comprised of SORAMITSU employees. [Gregorz Bazior](https://github.com/baziorek) (Yonix Digital Systems, AGH University of Science and Technology) is interested in Iroha 2 and maintains Iroha 1.

## Contributor Diversity

The practice of working with interns has been established and will continue.
We've got some interest from a potential security-oriented intern and we're in the process of discussing the topics to tackle.

## Features

- WIP migration to [runtime Executor](https://wiki.hyperledger.org/display/iroha/Promote+Iroha+Runtime+Validator+into+Iroha+Runtime+Executor)
- Use of `nightly-2023-06-25` toolchain
- Initial [`nix` packaging as flake](https://github.com/hyperledger/iroha/pull/3426)
- WasmTime optimisations [via caching of build artifacts](https://github.com/hyperledger/iroha/pull/3661)
- Improved platform support for Mac M1 and [linux-x86-{musl,glibc}](https://github.com/hyperledger/iroha/pull/3711)
- 12 minor Bug fixes
- [Incorrect topology rejected early](https://github.com/hyperledger/iroha/pull/3667)
- [`kagami` subcommand to generate local `docker-compose`](https://github.com/hyperledger/iroha/pull/3585) files
- [Fix for communication deadlock](https://github.com/hyperledger/iroha/pull/3394)
- Mentorship program
  - [FFI client library bindings](https://wiki.hyperledger.org/display/INTERN/Project+Plan+-+Iroha+2%3A+FFI+client+library+bindings) — [Orange Ng](https://github.com/orangeng)
  - [DSL](https://wiki.hyperledger.org/display/INTERN/Iroha+2%3A+DSL) — [Yasser Arguelles Snape](https://github.com/RealNeGate)
  - [Blockchain explorer update](https://wiki.hyperledger.org/display/INTERN/Iroha+2%3A+blockchain+explorer+update) — [Kshitij Roodkee](https://github.com/horizenight)

# Prior reports

* [2023, Quarter 1](https://toc.hyperledger.org/project-reports/2023/2023-Q1-Hyperledger-Iroha.html)
* [2023, Quarter 2](https://toc.hyperledger.org/project-reports/2023/2023-Q2-Hyperledger-Iroha.html)