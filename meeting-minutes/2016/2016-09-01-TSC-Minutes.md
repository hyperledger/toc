---
layout: default
title: 2016 09 01 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 09 01 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

September 1, 2016 (7:00am - 8:30am PT) via GoToMeeting

**TSC Members**

<div class="table-wrap">

<table class="confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd"><p><span>Arnaud Le Hors</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Binh Nguyen</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Christopher Ferris</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Dan Middleton</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Greg Haskins</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Hart Montgomery</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Mic Bowman</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Murali Krishna
Katipalli</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Richard Brown</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Sheehan Anderson</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Tamas Blummer</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
</tbody>
</table>

</div>

  

**Resources:**

- Github: 
  <a href="http://www.github.com/hyperledger" class="external-link"
  rel="nofollow"><span>www.github.com/hyperledger</span></a>
- Wiki:  <a href="https://github.com/hyperledger/hyperledger/wiki"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki</a>
- IRC:  \#hyperledger on
  <a href="http://freenode.net" class="external-link"
  rel="nofollow">freenode.net</a> (has Meetbot)
- Public lists: 
  <a href="http://lists.hyperledger.org" class="external-link"
  rel="nofollow">lists.hyperledger.org</a>
- Slack:  <a href="https://slack.hyperledger.org/" class="external-link"
  rel="nofollow"><span>https://slack.hyperledger.org/</span></a>
  (self-generated invites)
- Information on the TSC Members can be found at
  <a href="https://www.hyperledger.org/about/tsc" class="external-link"
  rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>
- Meetings:  <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar</a>

  

**Agenda**

- Welcome the new TSC
- Action Item Review
- WG Updates

  

**Welcome the new TSC**

- The steady state TSC election has now concluded.  Please join me in
  welcoming the following new or returning members to the TSC (in
  alphabetical order):

- - Arnaud Le Hors
  - Binh Nguyen
  - Christopher Ferris
  - Dan Middleton
  - Greg Haskins
  - Hart Montgomery
  - Mic Bowman
  - Murali Krishna Katipalli
  - Richard Brown
  - Sheehan Anderson
  - Tamas Blummer

  

**TSC Chair**

- Chris Ferris ran unopposed in the TSC Chair election and has been
  reelected for a 1-year term -- thank you for all the hard work, Chris!

  

**Action Item Review**

- Hackfest preparation and updates (Todd)

- - Hackfest / October 3-4, Amsterdam (confirmed - details coming soon)
  - Also, there will be a Hackathon on October 1-2 hosted by ABN AMRO,
    Holland Fintech, and IBM NL.
  - Strongly encourage everyone to attend these technical events.

- Review Hyperledger Release Taxonomy <a
  href="https://docs.google.com/document/d/19hZBOj4QklSJa2Fj3kHEwx1_R1T1rdRTXBseF6mzCN0/edit"
  class="external-link" rel="nofollow"><span>v0.</span><span>3</span></a>
  and add semver versioning numbers (Brian and Chris)

- - Both Chris and Brian has made a few edits and updates, feel this is
    close to ready for adoption
  - CF:  Want to have a broader discussion around this to make sure
    everyone is on same page, especially feedback from the STL folks, as
    their approach is slightly different.
  - ACTION:  Chris to send out reminder to review, then next meet plan
    to vote.

- Review and comment on Hyperledger-py <a
  href="https://docs.google.com/document/d/1N-KbwlFb7Oo_pTG2NjjLTqwlhqp_kjyv5fco7VH8WrE/edit"
  class="external-link" rel="nofollow"><span>proposal</span></a>, Baohua
  to share proposal with Community to try to bring a few more project
  sponsors to it, as well as work on naming of the project. (Baohua
  Yang)

- - Skipped until next week, no quorum for a vote this week.

- Communication tools (Brian/Todd)

- - <a href="http://wiki.hyperledger.org" class="external-link"
    rel="nofollow">wiki.hyperledger.org</a> is now live; this is
    dokuwiki, supports markdown
  - Brian:  Anyone with an LFID can edit and create new pages. 
    Encourage everyone to test it out, kick the tires, and see if there
    are any major issues.  Otherwsie, we will start the process of
    migration.
  - CF:  Suggest to have a few editors that we can count on to keep
    tidy, highlight potential abuses, quality control, etc.
  - Arnaud:  Is migration automatic?  Brian: No, don’t believe so --
    we’ll engage with the Community and WG leads to map out a migration
    plan in 1 week.

  

**WG Updates**

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Oleg Abdrashitov)

- - Draft of the privacy section of the Requirements Document is on the
    wiki
  - Oleg is working on the collateral management use case

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Architecture-WG"
  class="external-link" rel="nofollow"><span>Architecture WG</span></a>
  (Ram Jagadeesan)

- - Progress on two tracks
  - Fleshing out Architecture doc, finding issues that need to be
    discussed further before moving forward
  - On security doc starting to identify functional requirements for
    identity and policy layers
  - Focusing on bootstrap and identity of system entities (validators,
    etc.)
  - Then, will move onto identity in general

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)

- - Next objective is to get paper ready for Sibos
  - Looking to schedule a call within the next week or so

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar#hyperledger-identity-wg-biweekly-meeting"
  class="external-link" rel="nofollow"><span>Identity WG</span></a>
  (Christopher Allen)

- - Update coming via email

- CI WG (Chris Ferris)

- - Made transition over to Gerrit -- a bit bumpy from a build
    perspective
  - Had some problems with mirrors (bad mirrors, or mirrors not
    reachable) -- but this has been worked through
  - Cut a new release from Fabric yesterday v0.6, working over next few
    weeks in prep for Sibos to harden this.

  

**Actions**

- ACTION:  Hackfest preparation and updates (Todd)
- ACTION:  Chris to send out reminder to review Hyperledger Release
  Taxonomy <a
  href="https://docs.google.com/document/d/19hZBOj4QklSJa2Fj3kHEwx1_R1T1rdRTXBseF6mzCN0/edit"
  class="external-link" rel="nofollow"><span>v0.</span><span>3</span></a>
  and plan for TSC to vote to adopt on 9/8 (Brian and Chris)
- ACTION:  Review and comment on Hyperledger-py <a
  href="https://docs.google.com/document/d/1N-KbwlFb7Oo_pTG2NjjLTqwlhqp_kjyv5fco7VH8WrE/edit"
  class="external-link" rel="nofollow"><span>proposal</span></a>, Baohua
  to share proposal with Community to try to bring a few more project
  sponsors to it, as well as work on naming of the project. (Baohua
  Yang)
- ACTION:  Discuss
  <a href="http://wiki.hyperledger.org" class="external-link"
  rel="nofollow">wiki.hyperledger.org</a> migration plan in 9/8 TSC call
  (Brian/Todd)
- ACTION:  Communication tools (Brian/Todd)

## Recording
* [https://youtu.be/KWwrKGV_E60](https://youtu.be/KWwrKGV_E60)
