---
layout: default
title: 2024 Q3 Hyperledger Iroha
parent: 2024
grand_parent: Project Updates
---

# Project Health

Iroha 2 continues to make steady progress in Q3. One more pre-MVP version was released, [pre-RC 22.0](https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.22.0). Current focus is on fixing performance issues, ironing out the API, updating the SDKs and documentation.

Community activity is healthy: potential users and contributors express interest in the project, questions are being answered regularly, issues are being assigned to contributors, and we merged 5 community PRs since the last update. Project updates are sent out every two weeks.

# Overall Activity in the Past Quarter

In the past quarter, we rolled out Iroha `2.0.0-pre-rc.22.0`. Although pre-RC 21 was initially intended to be the final pre-MVP version, we have delayed the MVP release to address performance issues. Python SDK has been updated to the latest version, and significant progress has been made on the [Java](https://github.com/hyperledger/iroha-java/pull/431) and [JavaScript](https://github.com/hyperledger/iroha-javascript/pull/199) SDKs.

### Highlights

- **Key-centric Accounts**: Accounts are now [identified by a primary key](https://wiki.hyperledger.org/display/iroha/Key-centric+accounts+structure), with future support for aliases.
- **Filtered Queries**: Queries in smart contracts [can now be filtered](https://github.com/hyperledger/iroha/pull/4544). An [open PR](https://github.com/hyperledger/iroha/pull/4833) introduces type-safe queries.
- **Custom Instructions**: Added support for custom instructions via [executor upgrades](https://github.com/hyperledger/iroha/pull/4645), allowing users to expand the instruction set beyond the built-in ISI.
- **On-chain `Parameter` API**: Refined for better type-safety and differentiation between built-in and custom parameters.
- **New `ConfigReader` API**: Introduced for improved configuration debugging, error-reporting, and logging.
- **Removed genesis signing.**: The signed genesis block is now provided to peers on startup, simplifying network initialization and improving consensus speed and security.
- **Shallow data model**: [reduced nesting in the data model](https://github.com/hyperledger/iroha/issues/3921), enhancing performance and memory usage.
- Added initial support for **multi-signature transactions** via triggers, with an example [here](https://github.com/hyperledger/iroha/pull/4788).
- Improved UX with **new crate names**: `irohad` for the peer crate/binary, and `iroha` for the client crate/CLI.

# Releases

The following releases occurred in the past quarter:

- [Iroha 2.0.0-pre-rc.22.1](https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.22.1) – July 30th, 2024
- [Iroha 2.0.0-pre-rc.22.0](https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.22.0) – July 26th, 2024

# Maintainer Diversity

Since the last update, [Alexandra Zorina](https://github.com/a-zorina) has joined Iroha as a Technical Writer.

# Contributor Diversity

Most contributions in the past quarter were made by the core maintainers, with sporadic contributions by community members.

# Current Plans

Our main goal for the next quarter remains to deliver [RC 1](https://github.com/hyperledger/iroha/milestone/4), a feature-complete MVP. Additionally, there is an ongoing effort to overhaul the documentation and complete updating the SDKs.

# Questions/Issues for the TOC

None.