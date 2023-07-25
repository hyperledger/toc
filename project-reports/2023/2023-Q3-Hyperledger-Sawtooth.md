---
layout: default
title: 2023 Q3 Hyperledger Sawtooth
parent: 2023
grand_parent: Project Updates
---

# Project Health

Project activity has increased this month with contributors fixing documentation 
and general linting issues. Analysis and discussion continues on unifying main 
and 1-3 branches. A maintainer page has been added to the documentation, 
clarifying (and simplifying) the process for adding and removing maintainers. 
Community meetings continue.

# Questions/Issues for the TOC

The previous quarter's report was written by a contributor and long-time 
community member, in good faith, but caused some level of confusion. Our goal is 
to involve more contributors, including distributing the work of writing 
quarterly reports, as we attempt to expand our contributor base. Patience 
requested.

# Releases

There have been no releases since the last report.

# Overall Activity in the Past Quarter

The #sawtooth channel has continued to have user-level questions, many of which 
are the result of documentation issues (thus the on-going effort to 
enhance/correct documentation). The #sawtooth-contributors channel had some 
technical discussion on transaction processing.

Most PRs focused on documentation, bug fixes, linting, or minor enhancements.

# Current Plans

Analysis of the 1-3 and main branches occurred and discussion continues on 
whether/how to unify them. In particular, investigation into backporting from 
main to 1-3 is in progress, as is verifying that all 1-3 changes have been 
reflected in main. A possible next step is adopting the sawtooth-lib crate in 
1-3.

At least one commercial fork of 1.2 contains features which the community as a 
whole would like to see merged into the 1-3 development branch. This is driving 
the branch unification discussions. If major features make it into 1-3, then it 
is very likely that we will merge 1-3 back into main in the future. If the 
features remain minimal, we may just forward-port the features to main. The 
ideal guiding principle is to all work in the same direction.

Work to clarify the expectations and process for becoming a maintainer is 
intended to make it easier, and work will continue on enabling contributors 
toward that milestone.

# Maintainer Diversity

The current list of Maintainers can be found in the
[docs](https://github.com/hyperledger/sawtooth-docs/blob/main/community/maintainership.md)

Note some of these maintainers have been inactive for some time. They will be 
moved to emeritus through the new processes soon, including updates to the
MAINTAINERS.md files.

Several maintainers have been moved to retired (emeritus) status. Many of these 
maintainers had been partially retired in the past but not removed from all 
repositories. These Maintainers include:

- Anne Chenette
- Boyd Johnson
- Darian Plumb
- Eloá França Verona
- Logan Seeley

The Sawtooth maintainer rules have been revamped to make it easier to add/remove 
maintainers and provide clear guidelines for those seeking maintainership. This 
should make it easier to add new maintainers from Taekion and BlockchainTP.

# Contributor Diversity

Commits from 2023-03-31 to 2023-07-28 :  41

Committers from 2023-03-31 to 2023-07-28 :  5

Domains from 2023-03-31 to 2023-07-28 :  2

# Additional Information
