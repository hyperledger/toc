---
layout: default
title: 2016 10 06 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
--- 
# 2016 10 06 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

October 6, 2016 (7:00am - 8:00am PT) via GoToMeeting

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
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Christopher Ferris</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Dan Middleton</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
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
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Murali Krishna
Katipalli</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Richard Brown</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Sheehan Anderson</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Tamas Blummer</span></p></td>
<td class="confluenceTd"><br />
</td>
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

- Action Item Review
- HIP:  Iroha (Makoto Takemiya)
- Java Chaincode demo (Satheesh Kathamuthu, DTCC)
- WG updates

  

**Action Item Review**

- Hackfest/Hackathon readout from EU (Chris) and ongoing planning (Todd)

- - Held a Hackathon (competition style with prizes) and a Hackfest
    (working on Hyperledger codebase, help onboard new people,
    architectural issues, etc.) in Amsterdam this last week, hosted by
    ABN AMRO

  - Hackathon -- 20 teams of 5-6 each.  12 “geniuses” from HLP technical
    community, judges including Brian/Chris.  36 hour event.

  - Applications ranging from mobile voting app, healthcare records,
    insurance for delayed flights, fintech,etc.

  - Use cases <a
    href="https://github.com/timblankers/hyperledger-hackathon/wiki/Use%20cases%20that%20the%20teams%20are%20working%20on"
    class="external-link" rel="nofollow"><span>here</span></a>

  - CF:  would be useful to develop “Hackathon in a box”

  - Mic:  talked about having a public test network up -- would be great
    to have a place to showcase the best applications that come out of
    these

  - Hackfest -- roughly 60 attended.  Saw some new participants F2F
    (SWIFT, Accenture, CLS, Santander, etc.), as well as some more
    people to STL

  - December -- hold a Hackfest?  Should it be in New York?

  - - General consensus was that New York on December 5th & 6th in
      advance of Members Summit is doable.  Todd to look for space and
      connect back up with TSC before confirming anything.

- Chris Ferris to pull together thoughts on snapshot release in
  Hyperledger Release Taxonomy<a
  href="https://docs.google.com/document/d/19hZBOj4QklSJa2Fj3kHEwx1_R1T1rdRTXBseF6mzCN0/edit"
  class="external-link" rel="nofollow"><span> v0.4</span></a> and
  circulate via email

- - VOTE:  Unanimously approved

- Finalize <a href="http://wiki.hyperledger.org/" class="external-link"
  rel="nofollow"><span>wiki.hyperledger.org</span></a> migration plan in
  10/6 TSC call

- - Update since TSC call:  plugins have been installed
  - No major objections at this point, start migration early next week. 
    Need to lock Github wiki prior to migration.
  - Plan to leave the pages that Georg has migrated to Dokuwiki and
    continue to build from there.
  - Todd to migrate TSC info, WG owners to migrate their own info.

- Communication Tools (Brian/Todd) - pushed to next week

- Numbering scheme for HIP (Vipin) - pushed to next week

  

**HIP:  Iroha (Makoto Takemiya)**

- <a
  href="https://docs.google.com/document/d/1sN-6mv-m85NlbI3ZjwFkDT0izTcxbUaZN9LjLEe045Y/edit"
  class="external-link" rel="nofollow"><span>Proposal</span></a>
- <a href="https://github.com/soramitsu" class="external-link"
  rel="nofollow"><span>Source</span></a>
- Discussion
  <a href="https://drive.google.com/open?id=0B42vMkapQi1MLUNlSHlzYkM0dmM"
  class="external-link" rel="nofollow"><span>recording</span></a>
- As we ran out of time on this call and several TSC members had to drop
  (no longer had quorum), please continue Q&A via mailing list and we
  will revisit this topic in next week’s TSC meeting.

  

**Java Chaincode demo (Satheesh Kathamuthu, DTCC)**

- Pushed to next week

  

**WG Updates**

\[please send over via email\]

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Oleg Abdrashitov)
- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Architecture-WG"
  class="external-link" rel="nofollow"><span>Architecture WG</span></a>
  (Ram Jagadeesan)
- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)
- <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar#hyperledger-identity-wg-biweekly-meeting"
  class="external-link" rel="nofollow"><span>Identity WG</span></a>
  (Christopher Allen)
- Collaborative Tools WG (Chris Ferris)
- Fabric SDK Projects (Java, Node.js, and Python)

  

**Actions**

- December Hackfest preparation

- <a href="http://wiki.hyperledger.org/" class="external-link"
  rel="nofollow"><span>wiki.hyperledger.org</span></a> migration

- Communication Tools (Brian/Todd)

- Agenda topics for next week:

- - Iroha proposal
  - Java Chaincode demo (Satheesh Kathamuthu, DTCC)
  - Numbering scheme for HIP (Vipin)
  - Incident procedure in code of conduct (Arnaud)

## Recording
* [https://youtu.be/mkTjf3WL4Yo](https://youtu.be/mkTjf3WL4Yo)
