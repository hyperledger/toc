---
layout: default
title:  Release Signing
parent: Governing Documents
grand_parent: LFDT TAC
nav_order: 10
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Securing and Verifying Releases

The LF Decentralized Trust (LFDT) emphasizes a structured approach to governance, particularly in the context of artifact signing for its projects. Artifacts, which are essential outputs from each release, include binaries, container images, checksum files, documentation, provenance metadata, and software bills of materials (SBOM).

LFDT has a holistic approach to governing the security of projects and implements the highest levels of standards. The objective is to establish a consistent and secure approach to signing artifacts, leveraging industry-standard tools and practices while allowing flexibility for individual project implementations. Software verification processes are made available to ensure the integrity and authenticity of all artifacts throughout their lifecycle. A monitoring framework is introduced to score the project, rating the release process.

This initiative aligns with efforts to establish a secure software supply chain for LFDT projects and achieve full [SLSA (Supply Chain Levels for Software Artifacts) compliance](https://slsa.dev/spec/v1.0/levels) in the release process.

This governance framework prioritizes understanding the "what" of artifact signing, which includes:
- The importance of signing artifacts to ensure their integrity and authenticity.
- The necessity of meeting security standards, such as SLSA compliance.

The technical "how" of implementing will be left to the discretion of individual projects, allowing for flexibility and innovation.

## LFDT Project Compliance

1. The LFDT Technical Advisory Committee (TAC) standardizes the signing of artifacts using tools from the Linux Foundation’s digital signing project, [OpenSSF Sigstore](https://openssf.org/projects/sigstore/).
2. Each project must document the process of verifying the artifacts using [OpenSSF Sigstore](https://openssf.org/projects/sigstore/). The project must have a file called `RELEASE.md`.
3. Each project must enable and apply for a Sigstore's scorecard. The project must capture the scorecard's result and generate a badge visible on the README.md file.
4. An LFDT incubation project will follow at least SLSA Level 1, while graduated projects will meet at least SLSA Level 2.

## Responsibilities
- **Project Team:**
  - Add a `RELEASE.md` file containing the build and release process of artifacts. Capture the information such as versioning followed, steps to reproduce the build, current release process, resources for verifying the signed artifacts at the least.
  - Generate the scorecard and upload as a badge on `README.md` file.
  - Each project will be responsible for the technical integration of Sigstore's cosign and scorecard into its build process. This approach allows projects to adapt the implementation to their specific needs while adhering to the overarching governance framework.
  - Projects may opt to utilize existing infrastructure, such as Rekor, to record immutable copies of their build artifacts. This adds an additional layer of integrity and auditability to the signing process.
  - Enable tools, process and scans to catch the unintentional leakage of build secrets.
  - Enable branch protection rules for monitoring artifact releases.
- **LFDT Staff:**
  - The LFDT staff will maintain and secure the signing keys and the relevant infrastructure necessary for managing these keys. This centralization ensures a high level of security and reliability for key management practices.
  - Scan for SBOM compliance.

## General Recommendations

As a general rule of guidance, the project may ask the following questions to determine the compliance level.

### SLSA Level 1
The focus is on documenting the build and artifact release process. The goal is to have an audit record of incorporating new processes.
- Is the build environment and tools documented?
- Is the project leveraging automated security checks to identify vulnerabilities in the build process?
- Is there version control in place for the source code and build scripts?
- Are all changes to the build process tracked and reviewed by authorized personnel?
- Do you have a release process, and are you granting access only to the maintainers, following the principles of least privilege for generating the artifacts?

### SLSA Level 2
The focus is to ensure that the artifacts generated are verifiable. Any tampering in the generated artifacts must be caught by the user of the artifacts.
- Is the signing process incorporated for the artifacts?
- Is the signing integrated into the CI pipeline?
- Is auditing in place for regularly monitoring and auditing the signing practices and build process?
- Is a trusted tool (e.g., cosign) used to sign the artifacts?
- Is the build process reproducible, ensuring that the build generates consistent artifacts from the same source code?
- Is there provenance metadata that details how each artifact was built and its dependencies?

### SLSA Level 3
The focus is to ensure that the build environment is verified and trusted.
- Is there access control implemented to secure the build environment?
- Do you validate the signatures and checksums of all dependencies before ingesting them in the build stage?
- Do you sign the output of every step in your build pipeline to provide a verifiable guarantee?
- Do you use separate build workers/containers for each step in your build pipeline?
- Do you network isolate your build workers and pipeline as much as possible?
- Are you securing the keys and injecting them just in time?
- Are you leveraging an immutable record for the verification of signed artifacts?
