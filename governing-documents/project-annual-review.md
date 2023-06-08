---
layout: default
title: Project Lifecycle
parent: Governing Documents
grand_parent: Hyperledger TOC
nav_order: 5
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Project Annual Review

## Overview
In addition to the [quarterly project updates](./project-updates.md), projects will undergo an annual review by the TOC. Unlike the quarterly updates, the annual review process will include a deep dive into the project health, including contributor and maintainer diversity and adoption metrics. The annual review will also include an assessment of the current [project lifecycle state](./project-lifecycle.md). The review will result in a set of recommendations for the project to improve and/or recommendation to move a project to another stage.

## Timeline
Reviews will start on the yearly anniversary of the project being accepted or moving to a new stage.  **If your annual review is not submitted within two months of notification, we will take this as a sign that the project is not under active maintenance and the TOC is likely to decide to archive the project and move it to End of Life status.**

**NOTE:** If a project has genuinely stalled we can save everyone’s time and effort by archiving it.

## Process
The process for annual reviews is as follows:

* A TOC representative will be chosen to lead the review once the project files a PR.
* The assigned TOC member reviews the content of the PR and analyzes the project for community health indicators, their findings are placed within a thread in the private TOC channel ([#toc-only](https://discord.com/login?redirect_to=%2Fchannels%2F905194001349627914%2F945035770954141796)) for discussion. The thread should contain:
    1. important facts about the project that could influence the TOCs decision around the future of the project, its current stage, and path to other stages.
    2. whether the project's view of themselves is accurate and the ask of the TOC is reasonable to assist the project moving forward.
* The project's maintainers are invited to the public TOC meeting to engage in TOC-led discussion around the project. Project maintainers are not obligated to attend, but it is recommended.
* The assigned TOC member provides a summary of the project and leverages the thread's content as the basis of discussion. The discussion typically focuses on what is going well with the project and areas to improve.
* The project's maintainers are invited to use this time to voice any concerns and requests for help they may have that are not captured in the PR (or highlight asks within the PR).
* At the conclusion of the public meeting, the TOC votes to approve the annual review. Should a concern be registered on a project, the vote will be held separately.
* After the meeting wraps up, the assigned TOC member should summarize the discussion on the PR in the form of a comment to document information for the project and community.

### Filing an Annual Review
Hyperledger Foundation staff will notify the project maintainers and copy the TOC when the project review is due. 

Project maintainers are responsible for agreeing between them who will complete the annual review. One of the maintainers should create the review in GitHub under [hyperledger-foundation/toc/project-updates/](https://github.com/hyperledger-foundation/toc/tree/main/project-updates). 

* Raise a PR titled *[Project name] [year] Annual Review* (e.g., Amazing Project 2024 Annual Review)
* The PR should include a file called `./<year>/<year>-<project name>-annual.md` (e.g., `2024/2024-amazingproj-annual.md`) with the [contents described below](#annual-review-contents)
* Send an email to the [TOC mailing list](mailto:toc@lists.hyperledger.org) so that the community knows the PR is there and can comment on it.

**If your annual review is not submitted within two months of notification, we will take this as a sign that the project is not under active maintenance and the TOC is likely to decide to archive the project and move it to End of Life status.**

**NOTE:** If a project has genuinely stalled we can save everyone’s time and effort by archiving it.

### Annual Review Contents
Your annual review should answer the following questions: 

* Include a link to your project’s [LFX Insights page](https://insights-v2.lfx.linuxfoundation.org/projects). We will be looking for signs of consistent or increasing contribution activity. Please feel free to add commentary to add color to the numbers and graphs we will see on Insights.
* How many maintainers do you have, and which organisations are they from? (Feel free to link to an existing [MAINTAINERS file](../guidelines/MAINTAINERS-guidelines.md) if appropriate.)
* What do you know about adoption, and how has this changed since your last review or since being accepted into Hyperledger Foundation? If you can list companies that are adopters of your project, please do so. Feel free to link to an existing ADOPTERS file if appropriate.
* How has the project performed against its goals since the last review? (We won't penalize you if your goals changed for good reasons.)
* What are the goals for the next year of the project? For example, are you working on major new features? Or are you concentrating on adoption or documentation? 
* How can the Hyperledger Foundation help you achieve your upcoming goals? 
* Do you think that your project meets the criteria for another stage (see [Project Lifecycle](./project-lifecycle.md))?

## Potential Outcomes
The outcome of the annual review is either:

* At least two-thirds of the TOC members agree to continue the project at its current stage, or
* If enough TOC members do not agree to continue the project at its current stage, we will discuss with you what stage might be the appropriate next stage, including End of Life stage.

NOTE: If the TOC members recommend moving to a new stage, additional work may be required to provide details on how the project meets the new stage's acceptance criteria.

## Roles and Responsibilities

### Hyperledger Staff

- Maintaining the calendar for the project annual reviews
- Notifying the project maintainers and copy the TOC when the project review is due

### Project Maintainers
- Agreeing between themselves who will complete the annual review
- Creating the annual review by filing a PR in GitHub under [hyperledger-foundation/toc/project-updates/](https://github.com/hyperledger-foundation/toc/tree/main/project-updates)
- Sending email to the [TOC mailing list](mailto:toc@lists.hyperledger.org) so that the community knows the PR is there and can comment on it
- Optionally attending the public TOC meeting to engage in TOC-led discussion around the project. The project's maintainers are invited to use this time to voice any concerns and requests for help they may have that are not captured in the PR (or highlight asks within the PR)

### TOC Member Responsible for Project's Annual Review
- Reviewing the contents of the PR and analyzing the project's community health indicators
- Documenting findings within a thread in the private TOC channel ([#toc-only](https://discord.com/login?redirect_to=%2Fchannels%2F905194001349627914%2F945035770954141796)) for discussion. The thread should contain:
    1. Highlight important facts about the project that could influence the TOC's decision around the future of the project, its current stage, and paths to other stages
    2. Whether the project's view of themselves is accurate and the ask of the TOC is reasonable to assiste the prjoect moving forward
- During the TOC-led discussion, providing a summary of the project and leverages the private thread's content as the basis of discussion. The discussion typically focuses on what is going well with the project and areas to improve
- After the public meeting wraps up, summarizing the discussion on the PR in the form of a comment to document information for the project and community

### TOC Members
- Participating in the private thread and ask questions that they might have
- Participating in the TOC-led discussion of the project's annual review
- Participating in the vote on the project's annual review

## Credits
Ideas were taken from [CNCF's Sandbox Annual Review Process](https://github.com/cncf/toc/blob/main/process/) and the [OpenWallet Foundation's Annual Review Process](https://openwallet-foundation.github.io/tac/governance/project-annual-review-process/).
