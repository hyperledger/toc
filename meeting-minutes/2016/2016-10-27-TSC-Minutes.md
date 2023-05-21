---
layout: default
title: 2016 10 27 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 10 27 TSC Minutes
  
**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

October 27, 2016 (7:00am - 8:00am PT) via GoToMeeting

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

**Resources:**

- Discourse: 
  <a href="http://discuss.hyperledger.org" class="external-link"
  rel="nofollow">discuss.hyperledger.org</a>
- Github: 
  <a href="http://www.github.com/hyperledger" class="external-link"
  rel="nofollow"><span>www.github.com/hyperledger</span></a>
- Wiki:  <a href="https://wiki.hyperledger.org/"
  rel="nofollow">https://wiki.hyperledger.org/</a>
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
- Meetings: 
  <a href="http://wiki.hyperledger.org/community/calendar-public-meetings"
  class="external-link"
  rel="nofollow">wiki.hyperledger.org/community/calendar-public-meetings</a>

**Agenda**

- WG Discussion
- New project repo for fabric membership services called CAF (Keith
  Smith)

**WG Updates**

- Requesting for all WG leads (or WGs) to provide more frequent updates
  back to the TSC (via email/wiki/Discourse) so that the progress is
  transparent and accessible to the broader technical community.
- If there are more pressing updates, those can be put onto the TSC
  agenda for discussion, otherwise more frequent updates via
  email/Discourse and posting minutes to wiki will really help the
  entire technical community.
- Not trying to create extra work, really just want  the TSC to take a
  look at charter and distro of WGs to make sure it is working for
  everyone and folks have a pathway to engage.
- There were no objections.

  

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

**New project repo for fabric membership services called CAF (Keith
Smith)**

- <a href="https://drive.google.com/open?id=0B42vMkapQi1MZTFydTdMSzdXMWc"
  class="external-link" rel="nofollow"><span>recording</span></a>
- A question was raised as to why this is being proposed as a standalone
  proposal for incubation, as opposed to repo that is Fabric-specific.
- Discussion ensued leading to the outcome that this can be put into a
  separate repo while things progress with Fabric, and once it pivots to
  being more generally useful (i.e. STL, Iroha, etc.) then it could come
  back to the TSC as a proposal for incubation.
- No objections.

  

**Sawtooth Lake update (Dan Middleton)**

- Validator registry or endpoint registry work -- specifically towards
  adding validator nodes and permissioning policies to grant another
  system into the network.
- Started a significant redesign of how handling transaction families,
  both from client-side submission of transactions as well as how those
  are handled under hood.  Got Python SDK project underway.
- This is allowing us to carve out better process boundaries, can
  actually operate separate processes within validator, allow us to also
  support creating transaction families in other languages.
- Creating Java-SDK
- Once patterns established, can try to set up more separate projects to
  address some of the languages that are also popular
- Continuing to work with Explorer project

  

**Actions/On-going**

- December Hackfest preparation
- Communication Tools

## Recording
 * [https://youtu.be/CTKsyquRddE](https://youtu.be/CTKsyquRddE)
