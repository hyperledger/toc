---
layout: default
title:  Security Policy
parent: Governing Documents
grand_parent: LF Decentralized Trust TAC
nav_order: 10
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

This document outlines the Hyperledger security vulnerability disclosure policy
that all Hyperledger projects **MUST** follow. The associated
[security-template.md] file is a "best practices" security vulnerability
disclosure policy that project Maintainers **SHOULD** use for
publishing the security policy and procedures for their project by copying the
file into their project repositories and updating it according to the
instructions in the document. This document includes the "best practices" text,
and defines how project Maintainers can use alternatives to the best practices for their project. A project's resulting
alternative policy **MUST** adhere to the Hyperledger security vulnerability
disclosure policy.

[security-template.md]: /governing-documents/security-template.md

All project repositories **MUST** have a published security vulnerability disclosure
policy or have link to a common policy document for the project. In rare cases,
a repository within a project **MAY** have a policy different from the project, as
long as the repository policy also adheres to this Hyperledger security
vulnerability disclosure policy.

## About This Document

This policy borrows heavily from the recommendations of the OpenSSF
Vulnerability Disclosure working group. For up-to-date information on the latest
recommendations related to vulnerability disclosures, please visit the [GitHub
of that working group](https://github.com/ossf/wg-vulnerability-disclosures).

## Outline:

This document has the following sections:

1. [What is a Vulnerability Disclosure Policy?](#what-is-a-vulnerability-disclosure-policy)
2. [Vulnerability Disclosure Processes and Associated Rules](#vulnerability-disclosure-process-and-associated-rules)
3. [“People” Infrastructure](#people-infrastructure)
4. [Report Intakes](#report-intakes)
5. [CNA/CVE Reporting](#cnacve-reporting)
6. [Embargo List](#embargo-list)
7. [(GitHub) Security Advisories](#github-security-advisories)
8. [Private Patch Deployment Infrastructure](#private-patch-deployment-infrastructure)

In each of these sections, and in the associated [security-template.md], the
current Hyperledger "best practices" are defined. In some sections are
alternatives (tagged "**Alternative:**") that projects may want to use. When
projects vary from the current Hyperledger best practices, the documented alternatives
**MUST** adhere to this policy.

## What Is a Vulnerability Disclosure Policy?

No piece of software is perfect. All software (at least, all software of a
certain size and complexity) has bugs. In open source development, members of
the community or the public find bugs and report them to the project. A
vulnerability disclosure policy explains how this process functions from the
perspective of the project.

This vulnerability disclosure policy explains the rules and guidelines for
Hyperledger Projects. It is intended to act as both a reference for
outsiders–including both bug reporters and those looking for information on the
project’s security practices–as well as a set of rules that maintainers and
contributors have agreed to follow.

## Vulnerability Disclosure Process and Associated Rules

All Hyperledger projects, including this project, follow the associated process
and rules for vulnerability disclosures. We note that this outline is derived
from the [OpenSSF maintainers guide](https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md).

Each project will have a security team (for more details, see the
[people infrastructure](#people-infrastructure) below). The security team
will be comprised of maintainers or contributors to the project who are
knowledgeable about security and is responsible for responding to and
helping to fix security vulnerabilities.

The security team (see [people infrastructure](#people-infrastructure) for
details) for this project will do the following for each reported vulnerability:

1. Acknowledge receipt (see [Report Intakes](#report-intakes) for more) of the
issue to the reporter within 2 business days.

2. Assess the issue. Engage with the reporter to ask any outstanding questions
about the report and how to reproduce it. If the report is not considered a
vulnerability, then the reporter should be informed and this process can be
halted. If the report is still a regular bug (just not a security
vulnerability), the reporter should be informed (if necessary) of the regular
process for reporting bugs.

3. Some issues may require more time and resources to correct. If a
particular report is more complex, discuss an embargo period with the reporter.
The embargo period should be negotiated with the reporter and must not be
longer than 90 days.

4. Create a patch for the issue (see the [Private Patch Deployment
Infrastructure](#private-patch-deployment-infrastructure) section).

5. Request a CVE for the issue (see the [CNA/CVE Reporting](#cnacve-reporting) section).

6. Decide the date of public release.

7. If applicable, notify members of the embargo list of the upcoming patch
and release, as described above.

8. Cut a new (software) release in which the bug is fixed..

9. Publicly disclose the issue within 48 hours after the release. It is
recommended that this is done through GitHub security advisories (see the
[(GitHub) Security Advisories](#github-security-advisories) section for
more details).

## “People” Infrastructure

This section details the required basic vulnerability disclosure infrastructure
for all Hyperledger projects. There are quite a few necessary pieces of infrastructure,
and we go through them in detail here.

**Security team:** Projects **MUST** have a security response team of at
least three maintainers. This response team shall be set up BEFORE incidents
happen so that people know who to contact and how to contact them when an
emergency issue arises. It can be difficult to track down someone with unique
knowledge (e.g. in a particular area of cryptography) who is capable of
fixing a problem in a short period of time.

1. Each security team member will be a member of the
[Hyperledger Foundation security email list](mailto:security@lists.hyperledger.org),
and, in general, any Hyperledger-wide security infrastructure.

2. If a project has specialized code related to certain aspects of security
or cryptography (e.g. consensus algorithms or cryptographic algorithms), then
a corresponding specialist should be on the response team (e.g. someone
knowledgeable in consensus or cryptography, respectively). If a specialist
is not on the team, then the individual who is responsible for contacting or
engaging the specialists should be designated in their stead. We emphasize
that projects should have access to specialists in an area for which they
maintain code while recognizing that it may not be practical for these experts
to be on the response team.

Each project/repository must have a table in the security document listing the
team members in the following format.

| Name             | Email ID           | Chat ID        | Area/Specialty  |
| ---------------- | ------------------ | -------------- | --------------- |
| Satoshi Nakamoto | satoshi@nsa.gov    | theREALsatoshi | Everything      |
| Hart Montgomery  | hart@donotmail.com | uselessIDIOT   | Nothing         |
| <>               | <>                 | <>             | (if applicable) |

**Discussion forum:**

Discussions about each reported vulnerability **SHOULD** be carried out in the
private GitHub security advisory about the vulnerability. If necessary, a private
channel specific to the issue **MAY** be created on the Hyperledger Discord server
with invited participants added to the discussion.

**Alternative:** Projects **MAY** document on their security policy that they use other forums for private discussion forums for approved maintainers and
security team participants to discuss vulnerabilities. If other forum(s) are used, details about them **MUST** be included.

## Report Intakes

Hyperledger projects offer the following ways to submit security
vulnerabilities. While the security team members will do their best to
respond to bugs disclosed in all possible ways, it is encouraged for bug
finders to report through the following approved channels:

- Email the [Hyperledger Foundation security
list]: To report a security issue, please
send an email with the name of the project/repository, a description of the issue, the
steps you took to create the issue, affected versions, and if known,
mitigations. If in triaging the email, the security team determines the issue may be
a security vulnerability, a [GitHub security vulnerability report] will be
opened.
- Open a [GitHub security vulnerability report]: Open a draft security advisory
on the "Security" tab of this GitHub repository. See [GitHub Security
Advisories](#github-security-advisories) to learn more about the security
infrastructure in GitHub.

[Hyperledger Foundation security list]: mailto:security@lists.hyperledger.org

[GitHub security vulnerability report]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability

**Alternative:** Projects **MAY** publish in their security policy that they accept
security vulnerability disclosures via other mechanism, such as using the
[HackerOne.com] service. The policy **MUST** document the necessary details in using
the alternate reporting mechanism(s). In addition, a project **MAY** publish that
they don't accept reports via the recommended GitHub security vulnerability
process. Projects **MUST** accept reports via the [Hyperledger Foundation
security list].

[HackerOne.com]: https://www.hackerone.com/

## CNA/CVE Reporting

Hyperledger projects maintain a list of **Common Vulnerabilities and Exposures
(CVE)** and use GitHub as its **CVE numbering authority (CNA)** for issuing
CVEs.

**Alternative:** A project **MAY** document in its security policy that it uses
a different CVE numbering authority. For example, the project might add the
following text to this section of their security policy document:

```
This project uses the following CNA(s) in the following situations:
1. `CNA_1`:  `situation_1, can just state “default” if only one CNA`
2. `CNA_2`:  `situation_2`
```

## Embargo List

An embargo list is a list of known, trusted entities that run
large deployments of a given Hyperledger project. These
entities are notified ahead of time when important security patches are
incoming to minimize potential security risks to large deployments of
projects. Embargo lists are maintained by the security team for a given project/repository.

Parties are on an embargo list for (usually) one of two reasons,
because they can either help fix the problem (perhaps through testing a fix at
scale) or they need extra time to help prepare their ecosystem to roll out
fixes quickly. Approval is not given lightly: project leadership
(maintainers) must be convinced that institutions on the list **“need to know"**
about issues in advance.

Participation in an embargo list should not be taken lightly. List members
are expected to respect the materials shared through it and not disclose any
information to unauthorized parties until the public disclosure date.
Institutions are on this list because their presence helps the project and its
users; if their actions do not help the project and its users, they can expect
to be removed from the list.

The list itself is private in order to make it slightly more difficult for
attackers with vulnerabilities to find systems to attack. Entities may be
added to the embargo list by a majority vote of the `project` security response
team and should request to join the embargo list by contacting one or more of
the members of the security response team. If there is an issue about embargo
list membership where an entity feels like they are being dealt with unfairly
by the security response team, then they are encouraged to bring up the issue
in front of the LF Decentralized Trust TAC, who can act as moderators.

Hyperledger projects maintain private embargo lists. If you wish to be added to
the embargo list for a project, please email the [Hyperledger Foundation
security list], including the
project name and reason for being added to the embargo list. Requests will be
assessed by the respective Hyperledger security team in conjunction with the
appropriate Hyperledger Staff, and a decision will be made to accommodate or not
the request.

**Alternative:** Projects **MAY** choose to document in their security document
that they do not have an embargo list. The reason for not having an embargo list
**SHOULD** be included when a project chooses not to have an embargo list.

## (GitHub) Security Advisories

Hyperledger Foundation projects use [GitHub
security advisories and the GitHub security process](https://docs.github.com/en/code-security/security-advisories) for
handling security vulnerabilities. In particular, this best practice is strongly recommended
for projects that do not have a large number of security experts as the
features serve as a nice set of **guardrails** to help make sure that things are
done correctly.

**Alternative:** Projects **MAY** document in their security policy document
that they use a security advisory mechanism other than GitHub to publish their
disclosures. The alternate mechanism **MUST** be documented sufficiently for users
to understand how to monitor the security advisories published by the project.

## Private Patch Deployment Infrastructure

Patches to fix Hyperledger project security vulnerabilities are typically
developed without public visibility by using the private development features of
GitHub. Projects with maintainers that are not familiar with these capabilities
are encouraged to contact the [Hyperledger Community Architects] to learn more.

[Hyperledger Community Architects]: community-architects@hyperledger.org

**Alternative:** Projects **MAY** document in their security policy document
that they do use a service other than GitHub for private patch deployment
infrastructure, or that they don't use any private patch deployment
infrastructure at all. In either case, the document **MUST** include the details
of what is used instead.
