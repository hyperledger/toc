---
layout: default
title: Project Annual Review
parent: Governing Documents
grand_parent: LF Decentralized Trust TAC
nav_order: 5
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Project Annual Review

## Overview

In addition to the [quarterly project updates](./project-updates.md), projects will undergo an annual review by the TAC. This annual review will replace one of the quarterly reports. Unlike the quarterly updates, the annual review process will be a "big picture" assessment of the project by reviewing the progress on goals from the prior year and goals for the next year. In addition, the annual review process will include a deep dive into the project health, including contributor and maintainer diversity and adoption metrics, and will include an assessment of the current [project lifecycle state](./project-lifecycle.md). The review will result in a set of recommendations for the project to improve and/or recommendation to move a project to another stage.

## Timeline

Annual reviews will replace the Q1 quarterly report.  **If a project's annual review is not submitted within two months of notification, the TAC will take this as a sign that the project is not under active maintenance and is likely to decide to archive the project and move it to End of Life status.**

**NOTE:** If a project has genuinely stalled the project's TSC can save everyone’s time and effort by archiving the project and moving it to `End of Life`.

## Process

The process for annual reviews is as follows:

- A TAC representative will be chosen on a round-robin basis to lead the review once the project files a PR. This representative should be someone that is not directly involved with the project.
- A secondary representative will be chosen on a round-robin basis to observe and corroborate the findings of the lead. This representative should be someone that is not directly involved with the project.
- The lead and secondary TAC members review the content of the PR, analyze the project for community health indicators, and place their findings into a thread in the TAC channel (**LINK TBD:** `#tac`) for discussion.
- The project's TSC and advocates are invited to the public TAC meeting to engage in a TAC-led discussion about the project. Project TSC members are not obligated to attend, but it is highly recommended.
- The lead TAC member provides a summary of the project and leverages the thread's content as the basis of discussion. The discussion typically focuses on what is going well with the project and areas to improve.
- The project's TSC and contributors are invited to use this time to voice any concerns and requests for help they may have that are not captured in the PR (or highlight asks within the PR).
- At the conclusion of the public meeting, the TAC votes to approve the annual review, including any change in the project's status. Should a concern be registered on a project, the vote will be held at a later date.
- After the meeting wraps up, the lead TAC member should summarize the discussion on the PR in the form of a comment to document information for the project and community.

### Filing an Annual Review

LF Decentralized Trust staff will notify the project TSC and copy the TAC when the project review is due.

Project TSC members are responsible for agreeing between them who will complete the annual review. One of the project's TSC members should create the review in GitHub under [lf-decentralized-trust/tac/project-reports/](https://github.com/lf-decentralized-trust/tac/tree/gh-pages/project-reports).

- Raise a PR titled *`[year] [Project Name] Annual Review`* (e.g., `2024 LFDT Amazing Annual Review`).
- The PR should include a file called `./<year>/<year>-annual-<Project-Name>.md` (e.g., `2024/2024-annual-lfdt-amazing.md`) using [the annual review template](../project-reports/0000-annual-review-template.md).
  - Update the information at the top of the file:
    - change the `title` line to `YYY Annual Review Project Name` (e.g., `title: 2024 Annual Review Hyperledger Amazing`)
    - change the `parent` line to `YYYY` (e.g., `parent: 2024`)
    - change the `grand_parent` to `Project Updates` (i.e., `grand_parent: Project Updates`)
    - remove the `nav_exclude` line
  - Text between `<mark></mark>` are instructions. Please remove when section has been completed.
- Send an email to the **LINK TBD** `TAC mailing list` so that the community knows the PR is there and can comment on it.

## Potential Outcomes

The outcome of the annual review is:

- A majority of the TAC members agree to continue the project at its current status, or
- A majority of the TAC members recommend that a project be moved to a new status, including `End of Life`, or
- If the TAC cannot come to a consensus, the project will remain at its current status.

NOTE: If the TAC members recommend moving to a new status, additional work may be required to provide details on how the project meets the new status's acceptance criteria.

## Roles and Responsibilities

### LF Decentralized Trust Staff

- Maintaining the calendar for the project annual reviews.
- Notifying the project TSC and copying the TAC when the project review is due.

### Project TSC

- Agreeing between themselves who will complete the annual review.
- Informing the community about the annual review and requesting input.
- Creating the annual review by filing a PR in GitHub under [lf-decentralized-trust/tac/project-reports/](https://github.com/lf-decentralized-trust/tac/tree/gh-pages/project-reports).
- Sending email to the [TAC mailing list](mailto:tac@lists.lf-decentralized-trust.org) and to the project community so that the community knows the PR is there and can comment on it.
- Optionally attending the public TAC meeting to engage in TAC-led discussion around the project. The project's TSC members are invited to use this time to voice any concerns and requests for help they may have that are not captured in the PR (or highlight asks within the PR).

### TAC Member Responsible for Project's Annual Review

- Reviewing the contents of the PR and analyzing the project's community health indicators.
- Coordinating with the secondary TAC member on their findings prior to the TAC meeting.
- Documenting their findings within a thread in the TAC channel (TBD `#tac`) for discussion. The thread should contain:
    1. Important facts about the project that could influence the TAC's decision around the future of the project, its current status, and paths to other statuses.
    2. Whether the project's view of themselves is accurate and the ask of the TAC is reasonable to assist the project moving forward.
- Lead the annual review discussion at the TAC meeting, providing a summary of the project by leveraging the private thread's content as the basis of discussion. The discussion typically focuses on what is going well with the project and areas to improve.
- After the public meeting wraps up, summarizing the discussion on the PR in the form of a comment to document information for the project and community.

### TAC Secondary Member

- Working closely with the lead TAC member to review thew project's annual report, and to corroborate and publish their findings.

### TAC Members

- Participating in the thread and asking questions that they might have.
- Participating in the TAC-led discussion of the project's annual review.
- Participating in the vote on the project's annual review.

## Credits

Ideas were taken from [CNCF's Sandbox Annual Review Process](https://github.com/cncf/toc/blob/main/process/) and the [OpenWallet Foundation's Annual Review Process](https://openwallet-foundation.github.io/tac/governance/project-annual-review-process/).
