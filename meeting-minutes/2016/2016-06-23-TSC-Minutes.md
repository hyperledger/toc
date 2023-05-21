---
layout: default
title: 2016 06 23 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 06 23 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

June 23, 2016 (7:00am - 8:30am PT) via GoToMeeting

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
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Tamas Blummer</span></p></td>
<td class="confluenceTd"><p><span>Digital Asset</span></p></td>
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
<td class="confluenceTd"><p><span>Yes</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Chris Ferris</span></p></td>
<td class="confluenceTd"><p><span>IBM</span></p></td>
<td class="confluenceTd"><br />
</td>
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
- TSC Composition (steady state) -- initial discussion
- Update on the Fabric v0.5 developer preview release (Binh)
- WG Updates

  

**Action Item Review**

- Hackathon Update

- - July 26-27, San Francisco,
    <a href="https://www.regonline.com/hyperledgerhackfestjuly2016"
    class="external-link" rel="nofollow"><span>REGISTER NOW</span></a>
  - **\[August, Virtual\]**
    <a href="http://doodle.com/poll/r4ftyyvshef2rn6z" class="external-link"
    rel="nofollow"><span>http://doodle.com/poll/r4ftyyvshef2rn6z</span></a>
  - **\[September/October, Amsterdam\]**
    <a href="http://doodle.com/poll/y9h2e497essf9pg9" class="external-link"
    rel="nofollow"><span>http://doodle.com/poll/y9h2e497essf9pg9</span></a>

- June 30th TSC meeting -- several have already indicated they will be
  out of office.

- - Consensus - CANCEL meeting

- <a
  href="https://docs.google.com/document/d/1hmZY5LnZydTiYmkbtwyEYEkHEsSedlUhJbnlXGFrEP0/edit"
  class="external-link" rel="nofollow"><span>Exit criteria</span></a>
  (Arnaud)

- - Discussion

  - - Brian:  On page 2, used HIP (means “improvement proposal”) tends
      to be about specific features or pull requests, as opposed to
      projects.  It is a codebase/community that goes through this
      lifecycle, so maybe reserve HIP for things more specifically
      inside of each project.
    - Arnaud:  You are talking about Jeremy’s table.  This has not been
      fully reviewed by group, trying to figure out how to factor in.
    - Brian:  Maybe just focus on first 2 pages for now.  Also, slight
      sense that “mature” may signal that innovation has ended.  For
      example, Apache calls them top-level projects (TLPs). Is there a
      better word to use?
    - Arnaud:  We have project lifecycle doc that was reviewed/approved
      and that uses “mature.”
    - Jeremy:  Concerns about “mature” and “project” too.
    - Brian:  Yes, need to get taxonomy down.
    - Arnaud:  We also have a proposal template that refers to these
      terms.  So, would need to change in multiple places if that
      decision is made.
    - Brian:   If people want to put together a proposal, please post to
      TSC list.
    - Jeremy:  Splitting out base vs. additional requirements is fine. 
      Seems to be consensus between project lifecycle and product
      lifecycle.  Where do we want to put this? In requirements? I.e.
      scalability, security, etc.
    - Arnaud:  First list has “sufficient test coverage” -- this is
      important, if you want to claim that you can graduate from
      incubation, you should have test coverage under control (not that
      you have achieved a certain level)... same for scalability.
    - Vipin:  The more you address in software and public release notes
      and documentation, the more people will be inclined to use it
      under the parameters you specify.
    - ACTION:  Arnaud to fine tune Exit Criteria.

- Hyperledger Release Taxonomy <a
  href="https://docs.google.com/document/d/1u9pt-bXeOXefYBB1uYE6M-D6CtmkC1lGCjmicSlZgVA/edit"
  class="external-link" rel="nofollow"><span>v0.1</span></a> (Brian)

- - Brian provided an overview of Hyperledger Release Taxonomy <a
    href="https://docs.google.com/document/d/1u9pt-bXeOXefYBB1uYE6M-D6CtmkC1lGCjmicSlZgVA/edit"
    class="external-link" rel="nofollow"><span>v0.1</span></a>
  - ACTION:  Technical Community to review, add comments, and iterate on
    the Hyperledger Release Taxonomy <a
    href="https://docs.google.com/document/d/1u9pt-bXeOXefYBB1uYE6M-D6CtmkC1lGCjmicSlZgVA/edit"
    class="external-link" rel="nofollow"><span>v0.1</span></a>.

  

**TSC Composition**

- Composition (per <a href="https://www.hyperledger.org/about/charter"
  class="external-link" rel="nofollow"><span>Charter</span></a>)

- - Startup Period: During the first six (6) months after project
    launch, the TSC voting members shall consist of one (1) appointed
    representative from each Premier Member and each Top Level Project
    Maintainer, provided that no company (including related companies or
    affiliates under common control) shall have more than three (3)
    votes on the TSC.
  - Steady State: After the Startup Period, there shall be a nomination
    and election period for electing Contributors or Maintainers to the
    TSC. The TSC voting members shall consist of eleven (11) elected
    Contributors or Maintainers chosen by the Active Contributors. An
    Active Contributor is defined as any Contributor who has had a
    contribution accepted into the codebase during the prior twelve (12)
    months. The TSC shall approve the process and timing for nominations
    and elections held on an annual basis.
  - Contributors: anyone in the technical community that contributes
    code, documentation or other technical artifacts to the HLP
    codebase.
  - Maintainers: Contributors who have the ability to commit code and
    contributions to a project’s main branch on an HLP project. A
    Contributor may become a Maintainer by a majority approval of the
    existing Maintainers.

- August 11th would be 6 months from the initial TSC meeting on February
  11th.

- ACTION:  Create initial draft to establish process, timeline, and
  criteria for electing the steady state TSC and TSC Chair.

**Update on the Fabric v0.5 developer preview release (Sheehan)**

- Main intended goals were to stabilize a set of capabilities out there
  so that devs can try it out.  Also, exercise the release process.
- Primary new feature is the client SDK written in Node.js
- <a href="https://github.com/hyperledger/fabric/wiki/Fabric-Releases"
  class="external-link"
  rel="nofollow"><span>https://github.com/hyperledger/fabric/wiki/Fabric-Releases</span></a>
- <a href="https://github.com/hyperledger/fabric/wiki/Release-Process"
  class="external-link"
  rel="nofollow"><span>https://github.com/hyperledger/fabric/wiki/Release-Process</span></a>

  

**WG Updates**

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Oleg Abdrashitov)

- - <a
    href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG-Status-2016-Jun-13"
    class="external-link"
    rel="nofollow"><span>https://github.com/hyperledger/hyperledger/wiki/Requirements-WG-Status-2016-Jun-13</span></a>
  - <a
    href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG-Status-2016-Jun-20"
    class="external-link"
    rel="nofollow">https://github.com/hyperledger/hyperledger/wiki/Requirements-WG-Status-2016-Jun-20</a>

- Architecture WG (Ram Jagadeesan, via email)

- - The Arch-WG met last Friday along with the vHack and again on our
    regular slot on Wed.
  - We seem to be converging on a common functional definition of the
    consensus and smart-contract layers, that will allow us to have a
    truly pluggable consensus layer that accommodates different
    consensus algorithms.
  - As we develop the common definition, both the new fabric consensus
    proposal and the POET teams are testing it bottom-up to see if their
    designs can fit or can be evolved to meet the common framework.
  - We will try to have another off-cycle meeting next week to see if we
    can reach a definitive point on this topic.

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)

- - Whitepaper <a
    href="https://docs.google.com/document/d/1Z4M_qwILLRehPbVRUsJ3OF8Iir-gqS-ZYe7W-LE9gnE/pub"
    class="external-link" rel="nofollow"><span>Draft v1.0.1</span></a>
    (published June 22, 2016)
  - Please provide feedback to the Whitepaper working group through our
    <a
    href="https://docs.google.com/forms/d/1giX0cCgW8xQxOHDNoDsCt4-2cI_rjJL00QQ2dJOvEYg/viewform"
    class="external-link" rel="nofollow"><span>Feedback Form</span></a>
  - Feedback submissions are available for view <a
    href="https://docs.google.com/spreadsheets/d/1xPGX2iH7AZ8RWasrBAGUMdSe6Bs8iNq2QirpPqkW1tg/edit#gid=802998142"
    class="external-link" rel="nofollow"><span>here</span></a>

- <a href="https://github.com/hyperledger/hyperledger/wiki/Identity-WG"
  class="external-link" rel="nofollow"><span>Identity WG</span></a>
  (Christopher Allen)

- - No update.

- CI WG (Chris Ferris)

- - Brian:  The Linux Foundation has access to a 1,000 node cluster for
    CNCF and have ability to deploy jobs to it -- idea is that it might
    help with testing.  Could wire into a regular process. Would like to
    turn performance testing into something we do for all projects.
    Anyone interested in working on performance testing? Please contact
    Brian or Chris directly.

  

**Action Items**

- ACTION:  Hackathon updates and planning
- ACTION:  Arnaud to fine tune Exit Criteria
- ACTION:  Create initial draft to establish process, timeline, and
  criteria for electing the steady state TSC and TSC Chair.
- ACTION:  Technical Community to review, add comments, and iterate on
  the Hyperledger Release Taxonomy <a
  href="https://docs.google.com/document/d/1u9pt-bXeOXefYBB1uYE6M-D6CtmkC1lGCjmicSlZgVA/edit"
  class="external-link" rel="nofollow"><span>v0.1</span></a>.

## Recording
* [https://youtu.be/tV_WLRsA6pk](https://youtu.be/tV_WLRsA6pk]
