---
layout: default
title: Maintainer and Repository Inactivity
parent: Governing Documents
grand_parent: LF Decentralized Trust TAC
nav_order: 8
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Inactivity Policies

As part of the normal lifecycle of a project codebases and maintainers come and go. This document formalizes a Hyperledger wide policy for moving maintainers to emeritus status when a project does not have an explicit policy of their own, and the responsibilities of the Technical Advisory Council (TAC), Hyperledger Foundation staff, and maintainers in this process.

## Maintainer Inactivity

This policy applies to projects that do not have an explicit maintainer inactivity policy. Where a project has an established and functioning policy, only that project's policy will apply.

Hyperledger very much appreciates the contributions of all maintainers but removing write privileges is in the interest of an orderly and secure project.

Activity can be code contributions, code reviews, issue reporting, or any other such activity trackable by GitHub attributed to a Hyperledger repository.

When a maintainer has not had any activity in a particular project for three months they will receive a notification informing them of the inactivity policies. The means and manner of notification (email, github mentions, etc.) will be at the discretion of the TAC Chair or who the TAC Chair designates. 

When a maintainer has not had any activity in a particular project for six months a proposal will be opened up to move the maintainer from active status to emeritus status. A member of the TAC or a Hyperledger staff member will open this proposal. Any permissions to approve pull requests or commit code and any other such privileges associated with maintainer status will be removed.

The proposal will be in the form of a pull request (PR) to the relevant project repositories updating their maintainer lists. The inactive maintainer will be notified of this via an "at" @ mention in the PR. The PR will be open for at least one week to allow time for the project and maintainer to comment.

Inactive maintainers who express an intent to continue contributing may request a three-month extension. This request shall be made in the pull request updating their active maintainer status. Typically, only one such extension will be granted.

Maintainers who have been moved to emeritus status may return to active status when their activity within the project resumes and the current maintainers of the project approve their reactivation.

A Hyperledger Foundation staff member will provide a report (or maintain an automated means to generate a report) of the most recent GitHub tracked actions for contributors at regular intervals to the TAC.  It will be the TAC's responsibility to act on the data.
