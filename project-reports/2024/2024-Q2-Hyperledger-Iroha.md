---
layout: default
title: 2024 Q2 Hyperledger Iroha
parent: 2024
grand_parent: Project Updates
---

# Project Health

Iroha 2 continues to make steady progress in Q2. The final version before the MVP, [pre-RC 21](https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.21), was released recently, paving the way for the forthcoming [RC 1](https://github.com/hyperledger/iroha/milestone/4). Going forward, our focus remains on scalability, stability, security, and improved TPS. Meanwhile, Iroha 1 had another release, [1.6.0](https://github.com/hyperledger/iroha/releases/tag/1.6.0), containing efforts from the mentorship project, as well as multiple enhancements and bugfixes. 

Community activity looks healthy: potential users and contributors express interest in the project, questions are being answered regularly, issues are being assigned to contributors, and there have been closed PRs from community members since the last update. We launched a call for contributors to draw more attention to Iroha, and we hope that interest will grow after we deliver RC 1.

# Overall Activity in the Past Quarter

In the past quarter, we rolled out Iroha 2 pre-RC 21, which is the final release before a feature-complete MVP (RC 1). This version introduced major API changes, requiring considerable migration from our users and developers.

### Highlights

- **Expressions removed from the core API.** From now on, Iroha Special Instructions (ISI) are executed directly without evaluation. This simplifies common usage significantly, and renders illegal instructions unrepresentable. In more complicated scenarios (with querying, iteration, etc.), smart contracts can be used. In the future, users will be able to define custom expression systems via the Executor to express use cases not covered by ISI.

- **Configuration Overhaul RFC mostly implemented.** The previous API was clunky, but now it is much easier to get started using Iroha. TOML config files are now used instead of JSON.

- **New World State View implemented.** WSV is the in-memory storage used by Iroha. Previously, WSV often had to be cloned completely – this has been replaced with a more granular copy-on-write mechanism. This made transactions much faster, and reduced both memory usage and number of allocations.

- **Filtering API simplified.** This was previously a big pain point in the API.

- **Numerics simplified.** We consolidated the various numeric types used in assets into a single arbitrary-precision `Numeric` type, simplifying the data model. The numeric type is backed by the [`rust_decimal`](https://docs.rs/rust_decimal/latest/rust_decimal/) crate.

- **Queries in smart contracts are now lazy.** Executing a query from a smart contract doesn't return a full response anymore. Instead, it returns a paginated response using a database cursor. This has reduced the memory usage of smart contracts drastically.

- **Profiler integrated into Iroha.** Since a performance degradation of a long-running Iroha peer was noticed by our QA team, it became necessary to integrate a profiler to track this issue down. This allowed us to discover that Iroha wasted a lot of time calculating hashes and cloning the WSV (should be taken care of with the new WSV implementation).

Furthermore, [Iroha 1.6.0](https://github.com/hyperledger/iroha/releases/tag/1.6.0) and its corresponding [Python SDK update](https://github.com/hyperledger/iroha-python/releases/tag/1.6.0) were released, primarily consisting of efforts from the mentorship project, as well as other features and bugfixes.

Apart from the releases, some version control related changes have been made: 
- Iroha 2 branches are now default in our repositories, improving discoverability
- the branching model has been simplified, pull requests target the `main` branch now
- the `stable` branch has been deprecated in favor of tag-based releases
- Conventional Commits are now enforced in pull requests

Speaking of community activity, we merged PRs from two new contributors in the last quarter (a bugfix and a documentation improvement), and two more were assigned issues to work on. Community members ask questions regularly in the Telegram chat (mainly on usage and encountered issues), newcomers have expressed interest in using Iroha, and some potential contributors have asked about contributing, but are yet to actually participate.

# Releases

The following releases happened in the past quarter:

- [Iroha 2.0.0-pre-rc.21.1](https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.21.1) – May 3rd, 2024
- [Iroha 2.0.0-pre-rc.21](https://github.com/hyperledger/iroha/releases/tag/v2.0.0-pre-rc.21) – April 19th, 2024
- [Iroha 1.6.0](https://github.com/hyperledger/iroha/releases/tag/1.6.0) – April 5th, 2024
  - [Python SDK 1.6.0](https://github.com/hyperledger/iroha-python/releases/tag/1.6.0) – April 12th, 2024

# Maintainer Diversity

Since the last update, two new maintainers joined Iroha:
- [Nurzhan Sakén](https://github.com/nxsaken), Community Manager
- [Dmitry Murzin](https://github.com/dima74), Developer

# Contributor Diversity

Most contributions in the past quarter were made by the core maintainers, with sporadic contributions by community members.

Recently, we launched [a call for contributors](https://www.iroha.tech/contribute) which should hopefully bring some attention to Iroha and motivate folks to join the project.

# Current Plans

Our main goal for the next quarter is to deliver [RC 1](https://github.com/hyperledger/iroha/milestone/4), which will be a feature-complete MVP. We are also working on updating the Java, JavaScript, and Python SDKs to reflect the latest pre-RC 21 version, as well as the documentation.

There is room for improvement in contributor and maintainer diversity. We plan to integrate more recommendations from the [Project Best Practices](https://toc.hyperledger.org/guidelines/project-best-practices.html) in the next quarter, focusing on accessibility and documentation. This should make contributing a better-defined and more smooth experience, possibly improving contributor retention. We expect an increased interest in Iroha after the release of RC 1.

Since we are getting close to the first Release Candidate, we will be moving the Iroha 2 newsletter from our internal mailing list to the Hyperledger Iroha mailing group, which was used mainly for Iroha 1 updates in the past.

# Questions/Issues for the TOC

None.