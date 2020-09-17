---
layout: default
title:  Release Taxonomy
nav_order: 7
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Release Taxonomy

Releases at Hyperledger can be done either according to [SemVer](#SemVer) or via [CalVer](#CalVer).

## SemVer

Projects using SemVer follow the system outlined at [semver.org](https://semver.org) [taxonomy][^1]. In addition to the semantic versioning scheme, where we use MAJOR.MINOR.PATCH numbering, following the established guidance given in the semver specification, it is also strongly encouraged that projects should use the following tags, as permitted by semver:

* [preview](#preview)
* [alpha](#alpha)
* [beta](#beta)
* [rcN](#rcn) (release candidate N - where N is 1-n incremented for each candidate)
* snapshot-&lt;sha&gt;[^2] for interim, possible unstable builds

### preview

Not feature complete, but most functionality is implemented. Any missing functionality that is committed to the production release is identified, and there are specific people working on those features. Not heavily performance tuned, but performance testing has started with the first few hotspots identified and perhaps even addressed. No highest priority issues are in an open state. First-level developer documentation provided to help new developers with the learning curve.

### alpha

Feature complete, for all features committed to the production release. Ready for Proof of Concept-level deployments. Performance can be characterized in a predictable way, so that basic PoC's can be done within the bounds of published expectations. APIs are documented. First attempts at end-user documentation have been made. Developer documentation is further advanced. No highest priority issues are in an open state.

### beta

Feature complete for all features committed to the production release, perhaps with optional features when safe to add. Ready for Pilot-level engagements. Performance is very well characterized and active optimizations are being done, with a target set for the Production release. No highest priority or high priority bugs are in an open state. Developer documentation is complete; end-user documentation is mostly done.

### rcN

For a forthcoming production release, we will prepare multiple candidate releases intended to be heavily tested by the community. As we cycle through resolving uncovered issues, we will issue another when no remaining highest or high priority issues remain, and repeat until we feel confident in releasing a production release, with no qualifier. e.g. 1.0.

## CalVer

Projects may opt to use the [CalVer](https://calver.org) release taxonomy.  Projects that opt in must meet these criteria:

- The project has a regular or semi-regular release schedule that is oriented around release dates.
- If there are different points in time where different release processes are used, those need to be documented.
- The project has an established policy for introducing breaking changes.
  - This policy must allow users sufficient time to adapt to the changes.
  - This policy must include the channels used to communicate this (such as prominent placement in CHANGELOG files).
  - Some period of backward compatibility should exist.

[^1]: Note that this is **not** about exiting incubator status.

[^2]: Further, for interim, possibly unstable builds working towards a tagged release, we will append the first seven (7) characters of the SHA-1 hash of the latest commit for the branch from which the build is produced, so that we can identify the commit level of a given test, etc. e.g. 0.6-snapshot-36e99cd
