--- 
layout: default
title: 2016 06 09 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 06 09 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

June 9, 2016 (7:00am - 8:30am PT) via GoToMeeting

**TSC Members**

<div class="table-wrap">

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd"><p><span>Emmanuel Viale</span></p></td>
<td class="confluenceTd"><p><span>Accenture</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Stan Liberman</span></p></td>
<td class="confluenceTd"><p><span>CME Group</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Tamas Blummer</span></p></td>
<td class="confluenceTd"><p><span>Digital Asset</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Fouad Aberkane (proxy)</span></p></td>
<td class="confluenceTd"><p><span>Deutsche Boerse Group</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Pardha Vishnumolakala</span></p></td>
<td class="confluenceTd"><p><span>DTCC</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Hart Montgomery</span></p></td>
<td class="confluenceTd"><p><span>Fujitsu</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Satoshi Oshima</span></p></td>
<td class="confluenceTd"><p><span>Hitachi</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Chris Ferris</span></p></td>
<td class="confluenceTd"><p><span>IBM</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Mic Bowman</span></p></td>
<td class="confluenceTd"><p><span>Intel</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>David Voell</span></p></td>
<td class="confluenceTd"><p><span>J.P. Morgan</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Richard G. Brown</span></p></td>
<td class="confluenceTd"><p><span>R3</span></p></td>
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

- Action Item review
- WG Updates

  

**Action Item Review**

- Exit criteria summary (Arnaud Le Hors)

- - <a
    href="https://docs.google.com/document/d/1hmZY5LnZydTiYmkbtwyEYEkHEsSedlUhJbnlXGFrEP0/edit#heading=h.f4lv7usw6jp5"
    class="external-link"
    rel="nofollow"><span>https://docs.google.com/document/d/1hmZY5LnZydTiYmkbtwyEYEkHEsSedlUhJbnlXGFrEP0/edit#heading=h.f4lv7usw6jp5</span></a>

  - Discussion

  - - Mic:  Consider having project proposals start articulating
      project-specific exit criteria as part of proposal (also, go back
      to previously accepted projects and include this).  This gives TSC
      option to evaluate project, as well as project’s notion of
      graduation. Some community activity and engagement are universal,
      however each project should have some specific things that they
      are held accountable for maturation.

    - Hart:  Consider having some concept of “production ready.”  It
      seems like a project may be mature, but may not be ready to move
      lots of money (i.e. needs a security review).

    - - CF:  Agree -- but, this is a different conversation from whether
        it is still incubating or not.  This is more along the lines of
        steady release cadence, and whether you have an LTS release.  As
        a community, the HLP would anoint something as production ready.
        Take Docker for example, they had a number of dot release before
        1.0.
      - Hart:  Agree -- however, this is probably the next discussion
        then, after incubation and maturation.

    - Ram:  Given importance of security in this space, probably think
      through early security-related criteria and should be added to
      this process.

    - - CF:  Important to do this, but to Mic’s point, this may be best
        suited on a project-by-project basis.  If something is
        permissionless, for example, the blockchain itself needs to be
        hardened and secured, but anyone can join.  That example is a
        different function of security. Nonetheless, agree this should
        be top of mind.

    - Mic:  Possibly, at end of maturity, need to have an evaluation
      plan (i.e. security evaluation plan).  Execution of that plan gets
      you out of maturity into production ready.

    - Dave V:  Like the idea of a set of questions associated with
      different pieces.  From Whitepaper WG point of view, something
      around how well the platform meets the vision and criteria of
      premise, as well.  It may do a couple things well, but, if it
      misses something from the overall vision, that should be
      considered.

    - Oshima:  Depending on use cases, should have some guidelines. 
      Agree with the other feedback.

    - Arnaud:  Will this be two docs?  One doc for exit criteria and a
      reference to proposal template?  ...or are we creating one output?

    - - CF:  suggest integrating this into the proposal template.  As
        people present proposal, they can fill out criteria needed to be
        met for when they are done.
      - Murali:  previously talked about a test network, think that is a
        good idea to be part of criteria for maturity.
      - CF:  so that would be for top-level project, not subordinate,
        but great idea.

    - ACTION:  Arnaud to refine Exit Criteria for next week.

- Hackathons

- - June - week of 6/15 - 6/17 (virtual) \[<a
    href="https://docs.google.com/document/d/1ROq44KpxuelkOp8GpceFNcv8K6XfWdaOnknzBk73OMc/edit"
    class="external-link" rel="nofollow"><span>draft agenda</span></a>
    for iteration on TSC call\]

  - - Need volunteers to lead some of the kick-off and recap meetings
    - Also, would like to see office hours for the Maintainers and WGs

  - July - week of 7/25 (Bay Area, TBD)

  - August - gauging interest for week of 8/22 (co-located with LinuxCon
    North America, Toronto)

  - - Preference for a virtual Hackathon, instead, to reduce so much
      travel… and then consider holding a F2F in September/October in
      Europe

    - - September - Sibos (Geneva)
      - October - LinuxCon EU (Berlin)

    - ACTION:  Todd to provide some potential recommendations for an EU
      F2F

  

**WG Updates**

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Oleg Abdrashitov)

- - <a
    href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG-Status-2016-Jun-06"
    class="external-link" rel="nofollow"><span>Minutes</span></a>

- Architecture WG (Ram Jagadeesan)

- - IBM team put together a thorough doc for next generation of
    consensus, still continuing this discussion into next meeting,
    likely will hold an off-cycle meeting during vHack next week

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)

- - Whitepaper <a
    href="https://docs.google.com/document/d/1Z4M_qwILLRehPbVRUsJ3OF8Iir-gqS-ZYe7W-LE9gnE/pub"
    class="external-link" rel="nofollow"><span>Draft v1.0.0</span></a>
    (published June 9, 2016)
  - Please provide feedback to the Whitepaper working group through our
    <a
    href="https://docs.google.com/forms/d/1giX0cCgW8xQxOHDNoDsCt4-2cI_rjJL00QQ2dJOvEYg/viewform"
    class="external-link" rel="nofollow"><span>Feedback Form</span></a>
  - Feedback submissions are available for view <a
    href="https://docs.google.com/spreadsheets/d/1xPGX2iH7AZ8RWasrBAGUMdSe6Bs8iNq2QirpPqkW1tg/edit#gid=802998142"
    class="external-link" rel="nofollow"><span>here</span></a>
  - Comment:  may be good to find a different term than “fabric” as to
    not cause confusion
  - Recommendation for Whitepaper WG to hold office hours durign vHack
    next week

- <a href="https://github.com/hyperledger/hyperledger/wiki/Identity-WG"
  class="external-link" rel="nofollow"><span>Identity WG</span></a>
  (Christopher Allen)

- CI WG (Chris Ferris)

- - Jenkins is now working for Fabric
  - FYI --
    <a href="https://drive.google.com/open?id=0B42vMkapQi1MSzRjYlhfSkFRSzA"
    class="external-link" rel="nofollow"><span>Immersion into
    Gerrit</span></a>
  - CF:  Both TLPs let’s work with Maintainers to transition over to
    Gerrit… get really precise about reviews, and enforce a number of
    other checks using Gerrit in connection with Jenkins (i.e. ensure
    sign of for DCO, break off testing into multiple checks, enforce
    multiple reviews)

  

**Discussion**

- Tamas:  would like a meeting with Maintainers, as TSC is more
  high-level governance.  Need to find a forum for decisions on very
  technical matters, going through pull requests, etc.
- CF:  Fabric has this on Mondays (<a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar</a>)

  

**Action Items**

- ACTION:  Arnaud to refine Exit Criteria for next week.
- ACTION:  Technical Community -- continue to flesh out <a
  href="https://docs.google.com/document/d/1ROq44KpxuelkOp8GpceFNcv8K6XfWdaOnknzBk73OMc/edit"
  class="external-link" rel="nofollow"><span>draft agenda</span></a> for
  virtual Hackathon next week
- ACTION:  Todd to finalize plan proposal for next several Hackathons: 
  July (west coast), August (virtual), September/October (EU)

## Recording
* [https://youtu.be/xFCaQu9hYA0](https://youtu.be/xFCaQu9hYA0)
