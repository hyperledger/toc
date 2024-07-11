---
layout: default
title: Common Repository Structure
parent: Guidelines
grand_parent: LF Decentralized Trust TAC
nav_order: 1
---
# Common Repository Structure

Hyperledger projects are required to maintain a standard set of files in each repository. This
document describes the required and recommended files.

## Required Files with Specified Content

Repositories MUST have these files with the specific content in the linked files, or a file with a
link to the specified content with minimal exposition. These files MUST be at the root of the
repository.

-   [`LICENSE`](https://www.apache.org/licenses/LICENSE-2.0.txt) - https://www.apache.org/licenses/LICENSE-2.0.txt\
    (Unless an exception has been made by the Hyperledger Governing Board)
-   [`CODE_OF_CONDUCT.md`](https://tac.lfdecentralizedtrust.org/code-of-conduct.html) - https://tac.lfdecentralizedtrust.org/code-of-conduct.html
-   [`SECURITY.md`](https://wiki.hyperledger.org/display/SEC/Defect+Response) - https://wiki.hyperledger.org/display/SEC/Defect+Response

## Required Files with Variable Content

Repositories MUST have these files. Named files MUST be at the root of the repository, and may have
format suffixes such as `.md`, `.rst`, or `.txt`.

-   `README` \
    A description of the project and contain information or links to information such as
    -   A reference to the Apache license (required).
    -   The current and important past releases
    -   Documentation for developers and users
-   `MAINTAINERS` \
    A list of all current maintainers with contact info. [A separate document](MAINTAINERS-guidelines.md)
    covers the specifics.
-   `CONTRIBUTING` \
    Directions on how to contribute code to the project, or a pointer to the Wiki page with that information.
-   `CHANGELOG` \
    A human readable list of recent changes. Changes should at least include the current release. This
    file may be maintainer curated or mechanically produced.
-   Continuous Integration / Continuous Delivery (CICD) configurations \
    Configurations needed to run CICD on Hyperledger provided systems.

## Recommended

Repositories SHOULD have these files. Named files SHOULD be at the root of the repository

-   `NOTICE`
    -   As per section 4 subsection d of the
        [Apache License, Version 2](https://www.apache.org/licenses/LICENSE-2.0)
-   Apache License Header information in each source code file. \
    For new files added to Hyperledger repositories they SHOULD include the snippet `SPDX-License-Identifier: Apache-2.0` as part of the header. 
    (see the [Copyright and Licencing Policy](https://wiki.hyperledger.org/display/TSC/Copyright+and+License+Policy))
-   Build files consistent with the implementation language, such as...
    -   For JavaScript/Node.js a `package.json` file
    -   For Ruby a `Gemfile` file
    -   For Java one of a Maven `pom.xml`, an Apache Ant `build.xml`, or a Gralde `build.gradle`
        file
    -   For Python `setup.py` and `requirements.txt` files
    -   For Go `go.mod` and optionally `go.sum` 
    -   For Rust a `cargo.toml` file
    -   For multi-lingual repositories a `Makefile` or executable `build.sh` script
    -   For other languages, other standard build files a practitioner of the language would expect.
-   Testing code \
    Code to test the code in the repository (such as unit tests), in a location appropriate for the language.
    \
    Not all repositories can be tested (homebrew, docs), which is the only reason this is a SHOULD.

## Prohibited

Repositories MUST NOT have these files

-   Executable binaries and shared library files built by code in the repository \
    This includes `.exe`, `.dll`, `.so`, `.a` and `.dylib` files not otherwise part of a third party
    library.

# Tooling

In order to help automate checks a repolinter file and supporting scripts can be found in
[Hyperledger Community Management Tools](https://github.com/hyperledger-labs/hyperledger-community-management-tools/tree/main/repo_structure).
Note that where the two repositories and tooling differ this document takes precedence.
