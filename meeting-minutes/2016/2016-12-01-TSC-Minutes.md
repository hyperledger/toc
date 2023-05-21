---
layout: default
title: 2016 12 01 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 12 01 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

December 1, 2016 (7:00am - 8:00am PT) via GoToMeeting

**TSC Members**

<div class="table-wrap">

<table class="wrapped confluenceTable">
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
<td class="confluenceTd"><br />
</td>
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
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Tamas Blummer</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
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

- Action Item Review
- WG Charter discussion

  

**Action Item Review**

- NYC Hackfest
  <a href="https://www.regonline.com/hyperledgerhackfestdecember2016"
  class="external-link" rel="nofollow"><span>register</span></a> / <a
  href="https://docs.google.com/document/d/1iokahBpG7U8TuYn-HmAUCfzLsbq-5L1zW6oWe1ymuv4/edit"
  class="external-link" rel="nofollow"><span>agenda</span></a>

- - CF:  Suggest adding a session on Tuesday  “where do we go from
    here?” with the various top-level projects and potentially Corda. 
    (i.e. consolidation, component swapping, sharing functionality,
    working more collaboratively, etc.)

- FYI:  Hart Montgomery is the new Whitepaper WG lead (thank you to Dave
  Voell for all of his hard work!)

- <a
  href="https://wiki.hyperledger.org/community/project-incubation-exit-criteria"
  rel="nofollow"><span>Project Incubation Exit Criteria</span></a>
  \[vote needed\]

- - CF:  Requirements as stated for minimum requires was good, but
    additional requirements seemed more about “product” as opposed to
    “project.”  While it is obviously important, the additional
    requirements seem less about exiting incubation from a “project’
    perspective.

  - Discussion ensued, leading to the outcome that updating “additional
    requirements” to “additional considerations” is a sufficient change
    to be able to move forward with the Project Incubation Exit
    Criteria.

  - - \[vote\] <a
      href="https://wiki.hyperledger.org/community/project-incubation-exit-criteria"
      rel="nofollow"><span>Project Incubation Exit Criteria</span></a>
    - Passed unanimously

  - Brian:  With concerns about security and code scanning, making the
    suggestion that projects aim to get CII badge.

  - - Discussion thread:  <a
      href="https://lists.hyperledger.org/pipermail/hyperledger-tsc/2016-December/000500.html"
      class="external-link"
      rel="nofollow"><span>https://lists.hyperledger.org/pipermail/hyperledger-tsc/2016-December/000500.html</span></a>

- HIP:  Cello (Baohua Yang) \[vote needed\]

- - <a
    href="https://docs.google.com/document/d/1E2i5GRqWsIag7KTxjQ_jQdDiWcuikv3KqXeuw7NaceM"
    class="external-link" rel="nofollow"><span>proposal</span></a> &
    <a href="https://github.com/yeasy/cello" class="external-link"
    rel="nofollow"><span>existing code</span></a>
  - There was previous discussion as to whether Cello would have a
    better chance of success being merged in with Explorer, as opposed
    to independent… but those two groups have not had a chance to
    connect.
  - Voting deferred until those two groups are able to discuss.

- China Technical WG planning

- - <a
    href="https://wiki.hyperledger.org/groups/tsc/technical-working-group-china"
    rel="nofollow"><span>Proposed Charter</span></a>

  - Brian:  I'd like to propose that we begin with three members of the
    working group.  I'd like to nominate the following individuals,
    based on some prior conversations, but of course depending upon
    their willingness to do this:

  - - Baohua Yang
      \<yangbaohua@<a href="http://gmail.com" class="external-link"
      rel="nofollow">gmail.com</a>\>
    - CHARLES Cai (蔡栋)
      \<charlescai@<a href="http://wanda.cn" class="external-link"
      rel="nofollow">wanda.cn</a>\>
    - 胡瑞丰(Victor)
      \<huruifeng@<a href="http://huawei.com" class="external-link"
      rel="nofollow">huawei.com</a>\>

  - Of course more participants will be able to get involved in the
    forums that the WG decide are their officially supported forums - be
    it a mailing list, a WeChat group, or some other tool.  The point is
    that these three represent the bridge between both worlds.

  - \[vote\] Proposed Charter and 3 initial members (Baohua, Charles,
    and Victor)

  - - Passed unanimously.

  

**WG Charter Discussion**

- In the context of the Whitepaper WG, work underway for 10 months. 
  Have had 2 complete drafts, but in each case, there was such an
  incredibly diverse set of reactions, it is challenging to be succesful
  when trying to meet the requirements of everyone.
- Hart is now driving towards clarity and agreement on an outline.
- Need to determine what is the TSC and Foundation’s expected outcome
  from the WGs.  Need to hold the WGs to a level of rigor that is
  applied to the projects in incubation.
- ACTION:  Each WG to document their purpose, objectives, and/or
  deliverables through a Charter that is brought back to the TSC by or
  before January 12th.

  

**Actions/On-going**

- Cello and Explorer teams to connect, bring suggested path forward back
  to the TSC
- Each WG to document their purpose, objectives, and/or deliverables
  through a Charter that is brought back to the TSC by or before January
  12th.
- China Technical WG updates
- CII Security Badge <a
  href="https://lists.hyperledger.org/pipermail/hyperledger-tsc/2016-December/000500.html"
  class="external-link" rel="nofollow"><span>discussion</span></a>
- Internship Program -- if you are interested in being a mentor for an
  intern, please let us know (this will launch sometime next year)


## Recording
* [https://youtu.be/pLvjFqZszaU](https://youtu.be/pLvjFqZszaU)
