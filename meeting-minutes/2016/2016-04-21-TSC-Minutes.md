---
layout: default
title: 2016 04 21 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 04 21 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

April 21, 2016 (7:00am - 8:30am PT) via GoToMeeting

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
<td class="confluenceTd"><p><span>DAH</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Stefan Teis</span></p></td>
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
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Chris Ferris</span></p></td>
<td class="confluenceTd"><p><span>IBM</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Patrick Holmes (proxy)</span></p></td>
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
  rel="nofollow"><span>https://slack.hyperledger.org/</span></a> ← new,
  self-generated invites
- Information on the TSC Members can be found at
  <a href="https://www.hyperledger.org/about/tsc" class="external-link"
  rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>
- Meetings:  <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar</a>

  

**Agenda**

- Action Item Review (Chris Ferris)

- WG Updates

- - <a
    href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
    class="external-link" rel="nofollow"><span>Requirements WG</span></a>
    (Patrick Holmes)
  - Architecture WG (Ram Jagadeesan)
  - <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
    class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
    (Dave Voell)
  - Identity WG (Christopher Allen)
  - CI WG (Chris Ferris)

- Discussion re: Tamas' request for repo

- Discuss exit criteria

- TSC Representation Policy

  
  

**TSC Representation Policy**

- CF:  Have not settled on a formal proxy representation policy

- MD:  Not typical to have voting alternates (sometimes TSC will use
  email for voting if coordinating calls for quorum becomes a
  challenge).  Call is open to all, not just TSC members -- anyone can
  participate. In terms of voting, preference is to have people at
  meeting.

- - TSC needs to agree on a representation policy for:

  - - First 6 months startup phase (when TSC is populated by Platinum
      members)
    - Beyond 6 months (elected contributors or maintainers)

  - For example, someone is lead of a Project, what happens if they
    can’t make meeting, should they be able to send someone from their
    company?  ...or should they come from Project they are involved
    with?

  - - In Standards body, typically send from Company
    - In OSS, the norm is that it should be someone else from Project

- MD:  Many TSCs have a no-alternate policy, and votes are taken via
  email

- CF:  Can coach people to get back to participation, or have them
  gracefully step aside

- ChristopherA:  Will it always be weekly meetings?

- - CF:  Not likely, just during this startup phase.  Then should move
    to bi-weekly or less frequent.

- **ACTION:**  Chris Ferris to draft policy for review

  

**Action Item Review**

- Action Item Review (Chris Ferris)

- - LF Tooling meeting (Todd)

  - - This will be held directly following the TSC meeting at 8:30am PT
      for 90 minutes.
    - Details at <a
      href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar"
      class="external-link"
      rel="nofollow"><span>https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar</span></a>

  - Technical F2F update (Todd)

  - - Likely for 5/5 & 5/6 after the Consenus event
    - Hopeful to have identified venue space by EOD today

  - Dave to finalize wording of whitepaper to get in from of Board to
    review

  - - Likely a few more weeks until first draft done

    - - One section discussing public vs. private (want to get everyone
        on same page)

    - ACTION:  Dave to complete draft with group by May 5th

  - Patrick to setup Sawtooth Lake repo

  - - ACTION:  Will complete by 4/28

  - Chris to start discussion on exit criteria

  - - Slack channel has been created and discussion has begun

  

**WG Updates**

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Patrick Holmes)

<!-- -->

- First regular meeting happened on Monday
- Primrose walked through counterfeit drugs use case
- Next meeting to walk through requirements discussion
- If you have requirements or use cases, please send to Patrick.

  

- Architecture WG (Ram Jagadeesan)

- - Initial kick off last Friday
  - Regular meetings biweekly starting next Wednesday at 9am PT
  - Discussed tools (primarily will use Slack)
  - Built out list of issues to discuss (8 topics) while the group waits
    for requirements WG to come through
  - <a
    href="https://docs.google.com/document/d/1N8FUyWQJ-y6dqMApxNUCwxBGwiadomILoDtasoIvVRE/edit?usp=sharing"
    class="external-link"
    rel="nofollow">https://docs.google.com/document/d/1N8FUyWQJ-y6dqMApxNUCwxBGwiadomILoDtasoIvVRE/edit?usp=sharing</a>

  

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)

<!-- -->

- Reviewing Renat’s proposal for feedback -- put together right
  process/procedures form.  This was all accepted.
- When the WG posts first draft, will include link (google form) for
  people to provide feedback, each meeting we’ll review for updates into
  paper

  

- Identity WG (Christopher Allen)

<!-- -->

- <a
  href="https://docs.google.com/document/d/1fLqOQcOxpbNQfjgHioV02lbR53XFzKwqUrv-4goN_sA/edit?usp=sharing"
  class="external-link"
  rel="nofollow">https://docs.google.com/document/d/1fLqOQcOxpbNQfjgHioV02lbR53XFzKwqUrv-4goN_sA/edit?usp=sharing</a>
- Kick off last week, 32 people showed up
- Determining where identity fits into things
- Decided that there are some independent goals (as opposed to just
  being part of Architecture WG or Requirements WG)
- Meeting biweekly (staggered with Architecture WG)
- Primarily using Slack

  

- CI WG (Chris Ferris)

- - Meeting in 1 hour, will give update next week

  

**Discussion re: Tamas' request for repo**

- Original request via TSC mailing list

- - I'd like to create a github repository within
    <a href="http://github.com/hyperledger" class="external-link"
    rel="nofollow"><span>github.com/hyperledger</span></a> to give home
    to a subset of the Digital Asset proposed code
    (<a href="https://github.com/DigitalAssetCom/hlp-candidate"
    class="external-link"
    rel="nofollow"><span>https://github.com/DigitalAssetCom/hlp-candidate</span></a>)
    so our earlier proposal <a
    href="https://docs.google.com/document/d/1XECRVN9hXGrjAjysrnuNSdggzAKYm6XESR6KmABwhkE/pub"
    class="external-link"
    rel="nofollow"><span>https://docs.google.com/document/d/1XECRVN9hXGrjAjysrnuNSdggzAKYm6XESR6KmABwhkE/pub</span></a>
    can be built only using Hyperledger Foundation github repositories.
  - The code I would move into this repository defines a generic data
    access interface to the block chain, implements key generation,
    transaction composition and account level aggregation of UTXO. This
    is the code that we connected with IBM's OBC during the hackathon in
    NYC to demonstrate the joint proposal. The repo would come with its
    own build script to create an artefact (a java jar) to be further
    used with the fabric.
  - The code is used by our higher level stack at Digital Asset and I am
    sure will be helpful to others to build on, it could be best
    described as api or client library, hence I suggest the name api or
    java-api for the repository.

- Discussion

- - PH:  Does the fabric repo in HLP today include this code?

  - - TB:  No, it doesn’t.
    - PH:  I thought purpose of “fabric” was to include this.
    - TB:  Two distinct repos and connecting resulting services with
      each other

  - ST:  How would code act with current code in fabric?  Via interface
    or would you code it in directly?

  - - TB:  Code would be connected to fabric through an implementation
      of a gRPC connection between the two -- they are two distinct
      technology; connection between services.
    - ST:  Is it interaction between 2 independent blockchains?
    - TB:  No, the code is not an implementation of a blockchain.  It is
      an implementation of an application development API and utility
      functions to use a blockchain.
    - Stefan:  It’s a client layer?
    - TB:  yes.

  - CF:  Concern was too generic of a name and also was complexity of
    build (dealing with submodules, etc.).  More difficult CI pipeline
    to manage.

  - CF:  Start with this approach, and then merge into fabric
    repository?

  - - TB:  There are different technical motivations for this setup. 
      These are distinct technologies. While it might look more
      optically related, the technical process would not change at all. 
      This piece of code is part of internal DAH stack, this is simplest
      way to separate and maintain both code bases.

  - TB:  Regarding naming, could call it Java API or Fabric API (to make
    it less generic)

  - - ChristopherA:  Currently, does it only work with fabric repo? 
      ...or would it be useful to Sawtooth Lake or some other incubation
      moves forward?
    - TB:  Currently aim to support joint proposal.  However, it is an
      open source project, people can use it as they see fit.
    - RGB:  Just needs to be clear from name to people that surf to
      project what the repo is

  - CF:  For Patrick, do you transfer ownership of Sawtooth Lake
    collection of repos to LF?

  - - PH:  Doesn’t make sense to move multiple repos to Hyperledger. 
      Would create a single repo in Hyperledger, but wouldn’t have more
      than readme file pointing to other location for Sawtooth Lake.
    - MD:  Let’s pull in LF Infra team, they can help determine the best
      long term solution.

- Revised proposed name:  Fabric-API

- - TB:  This works for us.

  - CF:  This is still a merge, the code bases are built independently
    and compliment each other.  This is not a new or different proposal…
    just dealing with the naming.

  - No objections.

  - - Annotate readme to be clear what the repo is

  

**Discuss exit criteria**

  

- **CF:  had some discussion on slack**

  

- Need to start making this more real and actually getting concrete
  discussion
- Get people together on a call to discuss this to put together
  beginning of proposal, need deeper engagement separate from TSC call
- Action:  Todd to create Doodle poll for exit criteria (1 hour call)

  

**Actions:**

- TSC representation policy draft (Chris Ferris)
- Finalize Technical F2F date/venue (Todd)
- Whitepaper draft complete by May 5th (Dave Voell)
- Set up Sawtooth lake repo by April 28th (Patrick)
- Connect Patrick with Ry to figure out plan for Sawtooth Lake repo(s)
  (Todd)
- Create Fabric-API repo and annotate readme (Tamas)
- Doodle poll for 1 hour exit criteria call (Todd)

## Recording

* [https://youtu.be/WszoukGApo8](https://youtu.be/WszoukGApo8)
