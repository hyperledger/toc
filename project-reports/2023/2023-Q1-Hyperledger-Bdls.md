---
layout: default
title: 2023 Q1 Hyperledger Bdls
parent: 2023
grand_parent: Project Updates
---


# Project Health

- Initialize the work on the Fabric fork for the effort of integrating the Bdls with Fabric as its own BFT consensus protocol.
- Bdls imported successfully to the Fabric fork and actively in progress into a fully integrated BFT protocol.
- Bdls continues to grow.
- Bdls Mentorship program proposal has been submitted to be part of the Mentorship Projects 2023.

# Required Information


- Have you switched from master to main in all your repos? Yes
- Have you implemented the [Common Repository Structure](../guidelines/repository-structure.md) in all your repos? Yes
- Has your project implemented these inclusive language changes listed below to your repo? You can optionally [use the DCI Lint tool](https://github.com/petermetz/gh-action-dci-lint#usage) to make this a recurring action on your repo. Yes
  - master → main
  - slave → replicas
  - blacklist → denylist
  - whitelist → allowlist
- Have you added an [Inclusive Language Statement](https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example) to your project's documentation and/or Wiki pages?

# Questions/Issues for the TSC

non

# Releases

release 1.0

# Overall Activity in the Past Quarter

* Implemented the Chain, Consenture interface.
* Adding the required orderer/server/main.go running the orderer service using the bdls protocol.

# Current Plans

* Extracting the Orderer member list for the Quram contribution.
* Researching the possibility of switching the signing algorithm for Fabric message.
* Addressed the need to research the possibility of using Caliper as a Fabric stander performance test after Bdls successfully integrated.

# Maintainer Diversity

[Ahmed Al Salih](https://github.com/ahmed82)

# Contributor Diversity

* Many community members are interested in collaborating regarding gaining skills in integrating a BFT protocol into Fabric. Waiting for the approval of the mentorship project to start collaborating.
# Additional Information

non

