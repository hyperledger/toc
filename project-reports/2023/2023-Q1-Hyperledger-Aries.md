---
layout: default
title: 2023 Q1 Hyperledger Aries
parent: 2023
grand_parent: Project Updates
has_children: false
has_toc: false
nav_exclude: true
---

# Project Health

Hyperledger Aries has seen a lot of activity overall, and especially in
the [Aries Framework JavaScript](https://github.com/hyperledger/aries-framework-javascript),
[Aries Bifold](https://github.com/hyperledger/aries-mobile-agent-react-native) (mobile wallet) and [Aries VCX](https://github.com/hyperledger/aries-vcx) communities. Lots of progress being made in those
projects!

The following are the highlights from this past quarter:

-   Work on Hyperledger AnonCreds is increasing with the goal of moving
    to all of the Aries Frameworks moving towards being ledger-agnostic.
    Lots of progress in the AnonCreds repository and particularly in
    Aries Framework JavaScript. Issue created in ACA-Py to start the
    work of switching to use the AnonCreds Rust implementation.
-   The Aries projects that have a dependency on the Indy SDK are making
    a concerted effort towards moving off of that and onto the \"Shared
    Components\" -- [Aries
    Askar](https://github.com/hyperledger/aries-askar) (secure storage and key management),
    [anoncreds-rs](https://github.com/hyperledger/anoncreds-rs), or its predecessor --
    [indy-shared-rs](https://github.com/hyperledger/indy-shared-rs) (AnonCreds implementation) and [Indy
    VDR](https://github.com/hyperledger/indy-vdr) (integration with Indy Node).
    -   BC Gov posted 5 separate \"Code With Us\" funded opportunities
        for deliverables around the elimination of the Indy SDK in favor
        of the Shared Components.
    -   [Animo](https://animo.id), [Indicio](https://indicio.tech) and [DSR](https://dsr-corporation.com) (x3) were awarded the opportunities and are all  making progress.
-   Discussions began on Aries Interop Profile (AIP) v3.0, which extend
    AIP 2.0 to be based on DIDComm V2.
-   Improvements in the ACA-Py pipelines for producing both artifacts
    supporting multiple versions of Python and container images with
    Python and ACA-Py included.
    -   Looking to see if there are tools available to Hyperledger
        projects for container vulnerability scanning.
-   Important releases from the AFJ team to enable AIP 2.0 support for
    W3C Format verifiable credential using LD-Signature and BBS+
    Signature for JSON-LD and DIF\'s presentation exchange. 
-   Lots of work in Aries VCX in moving to AIP 2.0 and moving away from
    an Indy SDK basis.
-   Continued good progress was made in the community on the use of
    [Overlays Capture
    Architecture](https://oca.colossi.network/) (OCA) to power the
    on-screen display of credentials, as mentioned in the previous
    report. An Aries RFC has been proposed and gone through a couple of
    iterations, with good feedback -- [OCA for Aries RFC
    PR](https://github.com/hyperledger/aries-rfcs/pull/755), [OCA for Aries RFC
    (proposed)](https://github.com/swcurran/aries-rfcs/tree/oca4aries/features/0755-oca-for-aries) and [OCA for Aries Style Guide
    (proposed)](https://github.com/swcurran/aries-rfcs/tree/oca4aries/features/0756-oca-for-aries-style-guide).
    -   OCA allows a credential issuer to define the semantics of
        credential attributes, such as language translations for
        credential attribute labels and help text, what attributes
        contain personally identifiable information (PII), the data type
        and encoding of attributes, and the onscreen layout of
        credentials, including support for issuer icons and background
        images that can make a digital credential look like a physical
        credential.
-   Continued progress on Aries Bifold, with support for OCA added, a
    number of iterations on the functionality, and a substantial build
    out on the [Aries Mobile Test
    Harness](https://github.com/hyperledger/aries-mobile-test-harness).
-   Attendance at the regular communities meetings is high across the
    board.

There continues to be lots of delivered, verified code and increases in
participation and use of Aries.

The Indy/Aries stack continues to be the global leader in SSI/verifiable
data solutions, with AnonCreds the most used credential format.

# Questions/Issues for the TSC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python -- 0.7.5-rc0, 0.7.5-rc1, 0.7.5, 1.0.0-rc1
-   Aries Framework JavaScript -- 0.2.5, 0.3.0, 0.3.1, 0.3.2, 0.3.3
-   Aries Askar
-   Aries VCX Releases 0.43.0, 0.44.0, 0.45.0, 0.46.0, 0.47.0, 0.48.0,
    0.49.0, 0.50.0
-   Aries Framework Go

Interoperability status can be seen
here: [https://aries-interop.info](https://aries-interop.info).

# Overall Activity in the Past Quarter

Per the [Aries Activity Dashboard](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222022-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-12-31T07:00:00.000Z%22%7D) for the fourth quarter of 2022 (October-December), Aries
codebases had 397 PRs (down slightly) from 67 contributors (down
slightly).

Community participation is extremely active in Discord channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

# Current Plans

-   Aggressive work on eliminating the use of the Indy SDK in favor of
    the Aries Askar/Indy VDR/anoncreds-rs.
-   Expanding features in mobile wallet apps, including adding support
    for OCA to enable beautifully displayed credentials.
-   Work on ledger agnostic AnonCreds support in Aries Frameworks and
    the standardization of AnonCreds.
-   Work on Overlays Capture Architecture (OCA) published by issuers.

# Maintainer Diversity

Aries is a multi-codebase effort, and each codebase has its own set of
maintainers. The diversity of maintainers closely matches contributors,
with notes below. Cross framework collaboration continues to increase
through the replacement of the Indy SDK/use of the Shared Components,
and in the work on ledger agnostic AnonCreds.

# Contributor Diversity

In addition to the code contribution statistics (above), here are a few
indicators of our current diversity:

-   We hold community calls each Wednesday at 7am Pacific to cover (the
    mostly) US and European contributors.
-   Call attendance for each is typically in the 20-25 range, up
    somewhat lately.
-   Cross codebase interoperability efforts indicate cross-organization
    cooperation.

# Additional Information

Nothing

# Submission date

23-Jan-2023

# Reviewed by

-   ✅ Arnaud J Le Hors
-   🔲 Arun S M
-   ✅ Bobbi Muscara
-   🔲 David Enyeart
-   ✅ Jim Zhang
-   ✅ Marcus Brandenburger
-   ✅ Peter Somogyvari
-   🔲 Stephen Curran
-   🔲 Timo Glastra
-   ✅ Tracy Kuhrt
-   ✅ Ramakrishna V


## 7 Comments

*  David Boswell

   Stephen Curran -- It\'s great to see all of the great activity happening around
   Aries. The Hyperledger marketing team is planning to do a push
   around identity in Q3 and the focus for the quarter will be
   \#HyperledgerIdentity.  If you\'d like to have anything related to
   Aries, AnonCreds or Indy be a part of that, let us know and we\'re
   happy to help. It could be good to time some developer focused
   activities, such as workshops, during that quarter since there will
   be increased attention on our channels about these projects.
    
   Jan 25, 2023 15:47


    *  Stephen Curran

       Sounds good. I'll consult with the community on this. I'm on
       vacay this week, but perhaps we can have a chat about the
       steps/models to follow in the next week or so to go over this.

       Jan 31, 2023 15:34

*  Arnaud J Le Hors

   This ought to be 2023 Q1, right?

   Jan 26, 2023 14:00
    
    *  Arnaud J Le Hors

       I fixed the title and moved the page to the right section.

       Jan 26, 2023 14:08
        
    *  Marcus Brandenburger

       I believe the \"Overall Activity in the Past Quarter\" and \"Submission date\" sections are not updated correctly.
        
       Jan 26, 2023 14:53

       *  Jim Zhang

          I noticed that too. The link to insight dashboard is still
          pointing to the 3rd quarter date range, which should\'ve
          been Oct-Dec.
            
          Jan 26, 2023 14:59
            
*   Stephen Curran

    Sorry about the date misses -- the Linux Insights overall activity
    dates have been corrected. The submission date is a macro.

    Jan 26, 2023 17:11
