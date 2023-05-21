---
layout: default
title: 2016 09 08 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 09 08 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

September 8, 2016 (7:00am - 8:30am PT) via GoToMeeting


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

- Action Item Review
- WG Updates

  

**Action Item Review**

- Hyperledger Release Taxonomy <a
  href="https://docs.google.com/document/d/19hZBOj4QklSJa2Fj3kHEwx1_R1T1rdRTXBseF6mzCN0/edit"
  class="external-link" rel="nofollow"><span>v0.3</span></a> -- TSC to
  review and vote (Brian and Chris)

- - Walked through document comments and resolved inside of google doc
    during the call
  - ACTION:  Chris Ferris to pull together thoughts on snapshot release
    and circulate via email

- Hyperledger-py <a
  href="https://docs.google.com/document/d/1N-KbwlFb7Oo_pTG2NjjLTqwlhqp_kjyv5fco7VH8WrE/edit"
  class="external-link" rel="nofollow"><span>proposal</span></a>, Baohua
  to share proposal with Community to try to bring a few more project
  sponsors to it, as well as work on naming of the project. (Baohua
  Yang)

- - CF:  Hopefully people have had a chance to look, review, comment --
    ready for approval, or do people want more time to review?  Any
    concerns?
  - Baohua:  Have added 4 more sponsors to this proposal.
  - ACTION:  Baohua to update the proposal to replace the discussion of
    REST/gRPC with language along the lines of “this SDK will follow the
    guidance of the SDK WG.”.
  - ACTION:  Naming should be Fabric-sdk-py, not Hyperledger-py
  - VOTE:  Unanimous approval.

- EU Hackathon/Hackfest preparation and updates (Todd)

- - Hackfest, October 3-4:
    <a href="https://www.regonline.com/hyperledgerhackfestoctober2016"
    class="external-link" rel="nofollow"><span>register now</span></a>
    (<a
    href="https://docs.google.com/document/d/1zOkbVMbC3cdnStan4BAvufA9zpFyua_vJN6z8XxGq-Y/edit"
    class="external-link" rel="nofollow"><span>agenda</span></a> draft)
  - Hackathon, October 1-2: <a
    href="https://www.eventbrite.com/e/hyperledger-hackathon-tickets-26798489002"
    class="external-link" rel="nofollow"><span>register now</span></a>

- <a href="http://wiki.hyperledger.org/" class="external-link"
  rel="nofollow"><span>wiki.hyperledger.org</span></a> migration plan
  (Brian/Todd)

- - Consensus was to test the wiki further over the next week and
    discussion migration in 9/15 call.

- Communication tools (Brian/Todd)

- - Discourse instance is now up -- doing some final configuration and
    then will share with this group.
  - Brian:  suggest people also take a look at
    <a href="https://demo.rocket.chat/home" class="external-link"
    rel="nofollow"><span>https://demo.rocket.chat/home</span></a> to see
    if this would be a suitable Slack-alternative.

  

**Reminder/Update on Collaboration around Blockchain Explorer**

- CF:  Blockchain Explorer project is up, added 3 maintainers; also put
  2+2 rule on there.  Asked Ry to reduce to non-author core review
  (which means only 1 of maintainers needs to review and approve to
  merge) -- had to make this change, otherwise, we will wait forever to
  get code merged, instead of making progress.

  

**WG Updates**

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Oleg Abdrashitov)

- - Handling most financial use cases, need help on supply chain use
    cases
  - Started discussion on privacy

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Architecture-WG"
  class="external-link" rel="nofollow"><span>Architecture WG</span></a>
  (Ram Jagadeesan)

- - No update

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)

- - Met yesterday -- key thing was walkthrough, goal is to remove
    “DRAFT” in time for Sibos

  - Meeting scheduled for next week:

  - - Hyperledger - Whitepaper WG Wed, Sep 14, 1:00 pm ET
    - When it's time, start the meeting from here:
    - <a
      href="https://meetings.webex.com/collabs/meetings/join?uuid=M62ZSDWWKTRWZDR3RLKWZ8I1IG-9VIB"
      class="external-link"
      rel="nofollow"><span>https://meetings.webex.com/collabs/meetings/join?uuid=M62ZSDWWKTRWZDR3RLKWZ8I1IG-9VIB</span></a>
    - Audio Connection +1-415-655-0001 US TOLL
    - Access code: 197 291 274

  - Can do follow-up work in TSC meeting next week.

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar#hyperledger-identity-wg-biweekly-meeting"
  class="external-link" rel="nofollow"><span>Identity WG</span></a>
  (Christopher Allen)

- - No update.

- CI WG (Chris Ferris)

- - Behave tests are still having some problems in Fabric (both Jenkins
    and locally) -- maybe we remove until they can be stabilized.
  - Binh: Let’s disable in meantime
  - CF:  Will have Ramesh turn this off.

  

**Actions**

- ACTION:  Hackfest preparation and updates (Todd)
- ACTION:  Chris Ferris to pull together thoughts on snapshot release in
  Hyperledger Release Taxonomy <a
  href="https://docs.google.com/document/d/19hZBOj4QklSJa2Fj3kHEwx1_R1T1rdRTXBseF6mzCN0/edit"
  class="external-link" rel="nofollow"><span>v0.</span><span>3</span></a>
  and circulate via email (Chris)
- ACTION:  Discuss
  <a href="http://wiki.hyperledger.org" class="external-link"
  rel="nofollow">wiki.hyperledger.org</a> migration plan in 9/15 TSC
  call (Brian/Todd)
- ACTION:  Communication tools (Brian/Todd)
- ACTION:  Follow up on Whitepaper WG progress to get document ready in
  time for Sibos

## Recording
* [https://youtu.be/UARJrixWf_s](https://youtu.be/UARJrixWf_s)
