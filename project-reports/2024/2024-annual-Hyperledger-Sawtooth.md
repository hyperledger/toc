---
layout: default
title: 2024 Annual Review Hyperledger Sawtooth
parent: 2024
grand_parent: Project Updates
---

# Project Health

[Insights  2023](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=sawtooth&repository=all&dateFilters=Last%20Year&dateRange=2023-01-01%20to%202023-12-31&compare=PP&granularity=month&hideBots=true)

# Maintainer Diversity

The current list of maintainers is made of 8 people from Bitwise IO (some
formerly) and Intel. The maintainers have decreased over the last year as many
have moved on to other positions and projects. We expect that number to continue
to decrease.

[Current Maintainers] (https://github.com/hyperledger/sawtooth-core/blob/main/MAINTAINERS.md)

[Maintainers from last year](https://github.com/hyperledger/sawtooth-core/blob/afba99ae9712d8f14ab7505d6f2d23772970c1af/MAINTAINERS.md)

# Project Adoption

The project has not maintained a list of adopters.

# Goals

## Performance Against Prior Goals

The previous years goals had focused primarily on trying to increase
contributors to a level where a few contributors could become maintainers. While
there was an increase in the variety of contributors, especially earlier in 2023,
none of the contributors successfully transitioned to maintainers (due to
eventual inactivity). Feature-related goals included a returned focus to
Sawtooth 1.3 (unreleased branch) by backporting fixes from the current main
branch and reworking the current build system to make use of Github Actions
instead of Jenkins.

While minor progress was made on all goals, interest and work in these areas
mostly stalled the second half of 2023.

## Next Year's Goals

Please see Project Lifecycle Stage Recommendation

## Help Required

Please see Project Lifecycle Stage Recommendation

# Project Lifecycle Stage Recommendation

For reference, the recently revised TOC Project Lifecycle document is
at: https://toc.hyperledger.org/governing-documents/project-lifecycle.html

Hyperledger Sawtooth is currently in the Graduated state. The definition for
Graduated includes the statement that "The TOC may decide to move a Graduated
project that no longer meets the "Incubation Exit Criteria" back to Incubation
state". The intent is presumably a desire for Graduated projects to continually
meet the Incubation Exit Criteria. While 2023 contributions were diverse, the
criteria "must have an active and diverse set of contributing members" is likely
not met due to long periods of project inactivity. Of the criteria listed in
Incubation Exit Criteria, this is the only gap.

If the Graduated state is deemed inappropriate, there is not a suitable
replacement state. Moving the project back to Incubation would presume an
attempt to grow the project back to Graduated later; however, in 2023, we found
no real desire from contributors to advance the project forward--only infrequent
maintenance-level activities. Moving the project to Dormant may make sense
except that Dormant has a time horizon of 6 months, and is thus not appropriate
for long-term maintenance releases. Moving the project to Archived would make
maintenance releases impossible because the git repositories are made read-only
in that state.

Thus, we propose that the TOC move the project to Archived, with ongoing
maintenance releases handled in a community outside of Hyperledger. We feel
this would be best done within the context of the Splinter community, which is
also maintaining versions of former Hyperledger projects Transact and Grid. Pull
requests have been submitted to the various Sawtooth git repositories's
README.md files which reflect this transition should the proposal be accepted by
the TOC.
