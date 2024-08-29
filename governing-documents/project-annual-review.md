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
Annual reviews will replace the Q1 quarterly report.  **If your annual review is not submitted within two months of notification, we will take this as a sign that the project is not under active maintenance and the TAC is likely to decide to archive the project and move it to End of Life status.**

**NOTE:** If a project has genuinely stalled we can save everyone’s time and effort by archiving the project and moving it to `End of Life`.

## Process
The process for annual reviews is as follows:

* A TAC representative will be chosen on a round-robin basis to lead the review once the project files a PR. This representative should be someone that is not directly involved with the project.
* A secondary representative will be chosen on a round-robin basis to observe and corroborate the findings of the lead. This representative should be someone that is not directly involved with the project.
* The lead TAC member reviews the content of the PR and analyzes the project for community health indicators, their findings are placed within a thread in the TAC channel ([#toc](https://discord.com/channels/905194001349627914/941384040316018790)) for discussion. The thread should contain:
    1. important facts about the project that could influence the TACs decision around the future of the project, its current stage, and path to other stages.
    2. whether the project's view of themselves is accurate and the ask of the TAC is reasonable to assist the project moving forward.
* The lead TAC member will work closely with the secondary TAC member to review their findings prior to the TAC meeting.
* The project's maintainers are invited to the public TAC meeting to engage in TAC-led discussion around the project. Project maintainers are not obligated to attend, but it is highly recommended.
* The lead TAC member provides a summary of the project and leverages the thread's content as the basis of discussion. The discussion typically focuses on what is going well with the project and areas to improve.
* The project's maintainers are invited to use this time to voice any concerns and requests for help they may have that are not captured in the PR (or highlight asks within the PR).
* At the conclusion of the public meeting, the TAC votes to approve the annual review. Should a concern be registered on a project, the vote will be held separately.
* After the meeting wraps up, the lead TAC member should summarize the discussion on the PR in the form of a comment to document information for the project and community.

### Filing an Annual Review
Hyperledger Foundation staff will notify the project maintainers and copy the TAC when the project review is due. 

Project maintainers are responsible for agreeing between them who will complete the annual review. One of the maintainers should create the review in GitHub under [hyperledger/toc/project-reports/](https://github.com/hyperledger/toc/tree/gh-pages/project-reports).

* Raise a PR titled *[year] [Project Name] Annual Review* (e.g., 2024 Hyperledger Amazing Annual Review)
* The PR should include a file called `./<year>/<year>-annual-<Project-Name>.md` (e.g., `2024/2024-annual-Hyperledger-Amazing.md`) using [the annual review template](../project-reports/0000-annual-review-template.md)
    - Update the information at the top of the file:
        - change the `title` line to `YYY Annual Review Project Name` (e.g., `title: 2024 Annual Review Hyperledger Amazing`)
        - change the `parent` line to `YYYY` (e.g., `parent: 2024`)
        - change the `grand_parent` to `Project Updates` (i.e., `grand_parent: Project Updates`)
        - remove the `nav_exclude` line
    - Text between `<mark></mark>` are instructions. Please remove when section has been completed.
* Send an email to the [TAC mailing list](mailto:toc@lists.hyperledger.org) so that the community knows the PR is there and can comment on it.

## Potential Outcomes
The outcome of the annual review is:

* A majority of the TAC members agree to continue the project at its current stage, or
* A majority of the TAC members recommend that a project be moved to a new stage, including `End of Life`, or
* If the TAC cannot come to a consensus, the project will remain at its current stage.

NOTE: If the TAC members recommend moving to a new stage, additional work may be required to provide details on how the project meets the new stage's acceptance criteria.

## Roles and Responsibilities

### Hyperledger Staff

- Maintaining the calendar for the project annual reviews
- Notifying the project maintainers and copying the TAC when the project review is due

### Project Maintainers
- Agreeing between themselves who will complete the annual review and informing the TAC of who will be completing the report
- Creating the annual review by filing a PR in GitHub under [hyperledger/toc/project-reports/](https://github.com/hyperledger/toc/tree/gh-pages/project-reports)
- Sending email to the [TAC mailing list](mailto:toc@lists.hyperledger.org) so that the community knows the PR is there and can comment on it
- Optionally attending the public TAC meeting to engage in TAC-led discussion around the project. The project's maintainers are invited to use this time to voice any concerns and requests for help they may have that are not captured in the PR (or highlight asks within the PR)

### TAC Member Responsible for Project's Annual Review
- Reviewing the contents of the PR and analyzing the project's community health indicators
- Documenting findings within a thread in the TAC channel ([#toc](https://discord.com/channels/905194001349627914/941384040316018790)) for discussion. The thread should contain:
    1. Highlight important facts about the project that could influence the TAC's decision around the future of the project, its current stage, and paths to other stages
    2. Whether the project's view of themselves is accurate and the ask of the TAC is reasonable to assist the project moving forward
- Working closely with the secondary TAC member to review their findings prior to the TAC meeting
- During the TAC-led discussion, providing a summary of the project and leverages the private thread's content as the basis of discussion. The discussion typically focuses on what is going well with the project and areas to improve
- After the public meeting wraps up, summarizing the discussion on the PR in the form of a comment to document information for the project and community

### TAC Secondary Member
- Working closely with the lead TAC member to review and corroborate their findings

### TAC Members
- Participating in the thread and asking questions that they might have
- Participating in the TAC-led discussion of the project's annual review
- Participating in the vote on the project's annual review

## Credits
Ideas were taken from [CNCF's Sandbox Annual Review Process](https://github.com/cncf/toc/blob/main/process/) and the [OpenWallet Foundation's Annual Review Process](https://openwallet-foundation.github.io/tac/governance/project-annual-review-process/).
