---
layout: default
title: Hyperledger Iroha 2024 Annual Review 
parent: 2024
grand_parent: Project Updates
---

# Project Health

Our LFX Insights page is available with an [old](https://insights-v2.lfx.linuxfoundation.org/iroha/trends?selectedDateFilterType=DATERANGE&selectedDateRangeKey=1Y) and [new](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=iroha&bestPractice=false&repository=all&dateFilters=Last%2012%20Months&dateRange=2023-02-02%20to%202024-02-01&compare=PP&granularity=month&hideBots=true) interface. It must be noted that it doesn't reflect the whole picture, as we have several SDKs ([`iroha-java`](https://github.com/hyperledger/iroha-java), [`iroha-javascript`](https://github.com/hyperledger/iroha-java)) and the documentation repositiory, [`iroha-2-docs`](https://github.com/hyperledger/iroha-2-docs).

# Maintainer Diversity

Currently, the Iroha 2 core development team consists of:

* 9 Rust developers
* 2 full-time QA engineers
* 2 full-time technical writers
* 1 full-time Rust intern
* 1 community manager
* 1 project manager
* 1 DevOps

The maintenance team currently comprises SORAMITSU employees. [Gregorz Bazior](https://github.com/baziorek) (Yonix Digital Systems, AGH University of Science and Technology) is interested in Iroha 2 and maintains Iroha 1. 

Community interest is rising, and there are some minor community contributions. Moreover, our team started working with a new intern, [Asem Abdelhady](https://github.com/Asem-Abdelhady), who proved an efficient Rust developer. Diversity-wise, Kshitij Roodkee participates as a contributor.

For comparison, [this year's](https://github.com/hyperledger/iroha/blob/main/MAINTAINERS.md) `MAINTAINERS.md`, as well as [last year's version](https://github.com/hyperledger/iroha/commit/522b27bbd73e9b7306e9d6e1b7d0d0eff122b5e0?short_path=39da3bd#diff-39da3bd6270d44ea37b6ed50bd42eeb9d93ac5e1639645871a69cbe08cbe29de) is available. The number of active maintainers stayed the same.

After Iroha 2 is released, we expect more maintainers to join the project, as the mature Iroha 2 codebase would be more beneficial to new projects.

# Project Adoption

Since our acceptance into the Hyperledger Foundation, Iroha 2 has witnessed two critical adopters.

[Bokolo-cash](https://soramitsu.co.jp/bokolo-cash) is an initiative named after Bokolo, an ancient currency made from seashells that was once used in the Solomon Islands. The Central Bank of Solomon Islands (CBSI) and Soramitsu have begun a Proof-of-Concept for a Central Bank Digital Currency (CBDC). The CBSI logo uses Bokolo’s motif, which we have borrowed for our wallet app. A ceremony for the CBDC demonstration experiment took place on November 28, 2023. The Solomon Islands Prime Minister Manasseh Sogabare, Finance Minister Harry Kuma, Central Bank Governor Luke Forau, the representatives of the central banks of several countries, Ambassador Extraordinary and Plenipotentiary of Japan to the Solomon Islands Miwa Yoshiaki, the Cabinet Secretariat of the Government of Japan, and JICA attended the ceremony. As a Proof-of-Concept for a Central Bank Digital Currency (CBDC), Bokolo-cash explores use cases in domestic and foreign payments, including simulated international remittances.

Further expanding our reach, [Fraud Intelligence Limited](https://soramitsu.co.jp/fil-2023-in-review), [GitHub](https://github.com/fraud-intelligence-limited), and [Documentation](https://fraud-intelligence-limited.github.io/) utilizes Iroha 2 to combat fraud within the telecommunications industry. This blockchain-based platform fosters secure and decentralized information exchange, empowering organizations to prevent potential fraudulent activities through real-time insights. Additionally, individual developers express keen interest in leveraging Iroha 2's capabilities, for instance, reliable operation on embedded systems, including distributed computing services for devices located on space satellites. This diverse adoption underscores our commitment to providing innovative and impactful solutions within the Hyperledger ecosystem.

# Goals

## Performance Against Prior Goals

The development of the Iroha 2.0 MVP is ongoing, with the targeted release at the end of March 2024 in line with the agreed-upon product roadmap.

Given this is the first Hyperledger Iroha Annual Report, there is no 2022 Annual Report to look back on. Instead, this section highlights the project's accomplishments.

**New features**:

* Soft fork recovery
* Runtime-definable permissions
* Executor, a smart contract that functions as the backbone of Iroha 2
* Instruction visitor
* The server-side cursor for query batching
* `WSV` snapshots for fast restart without the block replay
* `WASM` permission validators

**Refactoring**:

* Domains now have owners
* The Iroha 2 schema layout has been simplified (every entry is unique)
* The [`iroha_crypto`](https://github.com/hyperledger/iroha/tree/iroha2-dev/crypto) crate superseded the Hyperledger Ursa dependency
* Block layout has been standardised
* Transaction layout has been standardised
* The data model API has been simplified and expressions have been removed
* Kagami was refactored and split into `iroha_swarm` and `iroha_wasm_builder_cli`

Our team actively pursues enhancing community engagement, promoting Hyperledger Iroha 2 into the broader IT community, and collaborating with the Hyperledger PR team.

Despite facing challenges related to a shortage of high-quality and available development resources, the team remains dedicated to the original project direction. As we work towards the MVP release, addressing challenges and seeking additional support will be pivotal for the project's success.

As stated above, this quarter marks a significant evolution for Iroha's cryptographic infrastructure development: the complete removal of Ursa's dependency from Iroha 2, the integration of its code to the [`iroha-crypto`](https://github.com/hyperledger/iroha/tree/iroha2-dev/crypto) package, and the further refactoring of the cryptographic tooling.

Initially, Iroha 2 used Ursa as a core cryptographic library to leverage its secure and reusable features. In turn, Ursa worked as an abstraction over other cryptography libraries. Iroha 2 benefited from Ursa's high cryptographic security standards. This change also minimised the need for redundant cryptographic code.

At this point, the necessary parts of Ursa are detached and fully integrated. The refactoring of the [`iroha-crypto`](https://github.com/hyperledger/iroha/tree/iroha2-dev/crypto) library itself continues.

The latest topic in Iroha's cryptographic infrastructure addressed by our team is [#4181](https://github.com/hyperledger/iroha/pull/4181); it allows the parsed keys to be stored instead of the raw bytes.

## Next Year's Goals

Our primary goal is to build upon the achievements of 2024 by successfully delivering the Hyperledger Iroha 2.0 MVP and stabilising its SDKs.

Beyond this milestone, our focus with the development team will address functional deliverables not included in the MVP but essential for the project's completeness in the post-production phase. 

Furthermore, we aspire to initiate the development of architectural upgrades, laying the groundwork for delivering Iroha 2.0 as a public blockchain. It is important to note that the Iroha 2 currently operates as a private blockchain, and the shift to a public blockchain will necessitate dedicated time for research and development. Additionally, we plan to incorporate a set of additional functional features in the post-release phase, strategically supporting the commercial efforts of Central Bank Digital Currency Proof of Concepts. We aim to advance our project's technical capabilities and foster its broader adoption and utility within the industry.

Our community has expressed an interest in using Iroha's codebase as something that can reliably run on the embedded SoCs, similar to those found in modern mobile phones. They could compile Iroha on different ARM SoCs with limited RAM and help test it in new conditions. While this isn't a priority, Rust allows such ports to function well, and the main concern would be overall performance. We are engaged in dialogue with those users to benchmark Iroha and expand its use scope.

We are also excited about the opportunity to participate in the Hyperledger [AI FAQ](https://github.com/hyperledger-labs/aifaq) project and contribute our documentation.

# Help Required

Since we expect Iroha 2 to grow, we would like to request support for our PR effort, intending to report the project's results. For now, the projects we can mention are [Bokolo Cash](https://soramitsu.co.jp/bokolo-cash), Bakong, and [Fraud Intelligence Limited](https://soramitsu.co.jp/fil-2023-in-review).

# [Project Lifecycle](https://toc.hyperledger.org/governing-documents/project-lifecycle.html) Stage Recommendation

Hyperledger Iroha should remain [graduated](https://toc.hyperledger.org/governing-documents/project-lifecycle.html#graduated).

Its code has improved with the use of Rust. Interest in Iroha 2 is growing and we expect it to gain deployments following its release.
