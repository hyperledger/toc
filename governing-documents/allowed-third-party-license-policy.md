---
layout: default
title: Hyperledger Foundation Allowed Third Party Licenses
parent: Governing Documents
grand_parent: Hyperledger TOC
nav_order: 3
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Hyperledger Foundation Allowed Third Party Licenses

Hyperledger Foundation's IP policy is set forth in the [Hyperledger Foundation charter], section 12.

Hyperledger Foundation project dependencies that are licensed under Apache-2.0 do not require
further license review or approval, since they are under the same license as
the Hyperledger Foundation itself.

The IP policy in the [Hyperledger Foundation charter] allows the Hyperledger Foundation Governing
Board to review and approve other non-Apache-2.0 licenses on an exception basis.

To streamline this process, licenses for some components are allowed as per
the Hyperledger Foundation Allowlist License Policy (adopted by the Hyperledger Foundation
Governing Board on 2019-04-02).

Components that are not under Apache-2.0, and that do not satisfy the Allowlist License Policy, remain subject to review and exception approval by the Governing Board.

## Hyperledger Foundation Allowlist License Policy

A third-party component under a non-Apache 2.0 license will be deemed automatically approved by the Governing Board for use in a Hyperledger Foundation project as an exception to the Hyperledger Foundation Intellectual Property Policy, if **all** of the following apply:

1. it is fully licensable under the approved licenses set forth in [Approved Licenses] (including combinations with Apache-2.0); AND

2. it is either not stored in the Hyperledger repo, or else stored unmodified in a designated third-party folder in source code form; AND

3. it has indications of substantial use outside Hyperledger because either:

 * the component is part of the applicable programming language's standard library; or
 * the component was created on GitHub at least 12 months ago and has at least 10 stars or 10 forks.

### Approved Licenses for Allowlist

To be approved as "allowlisted," a third-party component must be fully
licenseable under one or more of the following licenses, and must meet the
other allowlist criteria set forth in the [Allowlist License Policy] above.

License IDs refer to the SPDX License List at https://spdx.org/licenses, except
where a URL is specified below for licenses that are not on the SPDX License
List.

Approved Licenses:

 * BSD-2-Clause
 * BSD-2-Clause-FreeBSD
 * BSD-3-Clause
 * MIT
 * ISC
 * Python-2.0
 * BSL-1.0 (Boost)
 * bzip2-1.0.6
 * OLDAP-2.7, -2.8 (Open LDAP)
 * PostgreSQL
 * TCL (TCL/TK)
 * W3C
 * X11
 * Zlib
 * Google patent license for Golang (https://golang.org/PATENTS)
 * References to being in the "public domain" (excluding CC0-1.0)

For fonts: OFL-1.0, OFL-1.1

For documentation: CC-BY-1.0, CC-BY-2.0, CC-BY-2.5, CC-BY-3.0

[Allowlist License Policy]: #Hyperledger-Foundation-Allowlist-License-Policy
[Approved Licenses]: #approved-licenses-for-allowlist
[Hyperledger Foundation Charter]: https://github.com/hyperledger/toc/blob/gh-pages/governing-documents/charter.md
