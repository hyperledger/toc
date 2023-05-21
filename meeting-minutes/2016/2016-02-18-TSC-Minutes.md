---
layout: default
title: 2016 02 18 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 02 18 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

February 18, 2016 (7:00am - 8:30am PT) via GoToMeeting

**TSC Members**

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
<td class="confluenceTd"><p><span>Present</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Shaul Kfir</span></p></td>
<td class="confluenceTd"><p><span>DAH</span></p></td>
<td class="confluenceTd"><p><span>Present</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Stefan Teis</span></p></td>
<td class="confluenceTd"><p><span>Deutsche Boerse Group</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Pardha Vishnumolakala</span></p></td>
<td class="confluenceTd"><p><span>DTCC</span></p></td>
<td class="confluenceTd"><p><span>Present</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>Kei Taniuchi</span></p></td>
<td class="confluenceTd"><p><span>Fujitsu</span></p></td>
<td class="confluenceTd"><p><span>Present</span></p></td>
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
<td class="confluenceTd"><p><span>Present</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Mic Bowman</span></p></td>
<td class="confluenceTd"><p><span>Intel</span></p></td>
<td class="confluenceTd"><p><span>Present</span></p></td>
</tr>
<tr class="even">
<td class="confluenceTd"><p><span>David Voell</span></p></td>
<td class="confluenceTd"><p><span>J.P. Morgan</span></p></td>
<td class="confluenceTd"><p><span>Present</span></p></td>
</tr>
<tr class="odd">
<td class="confluenceTd"><p><span>Richard G. Brown</span></p></td>
<td class="confluenceTd"><p><span>R3</span></p></td>
<td class="confluenceTd"><br />
</td>
</tr>
</tbody>
</table>

**Resources:**

- Github:
  <a href="http://www.github.com/hyperledger" class="external-link"
  rel="nofollow"><span>www.github.com/hyperledger</span></a>
- IRC: \#hyperledger on
  <a href="http://freenode.net" class="external-link"
  rel="nofollow">freenode.net</a> (has Meetbot)
- Public lists:
  <a href="http://lists.hyperledger.org" class="external-link"
  rel="nofollow">lists.hyperledger.org</a>
- Slack: <a href="http://hyperledgerproject.slack.com/signup"
  class="external-link"
  rel="nofollow">hyperledgerproject.slack.com/signup</a> (email
  <a href="mailto:tbenzies@linuxfoundation.org" class="external-link"
  rel="nofollow"><span>tbenzies@linuxfoundation.org</span></a> for
  access)
- Information on the TSC Members can be found at
  <a href="https://www.hyperledger.org/about/tsc" class="external-link"
  rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>

  

**Agenda:**

- 5-10 mins: Statement from each TSC Chair nominee (3-5 mins per
  nominee)
- 10 mins: Code of Conduct discussion (Chris Ferris)
- 10 mins: Intel contribution overview (Mic Bowman)
- 5 mins: Draft project proposal template (Stefan Buhrmester and Vipin
  Bharathan)
- 30 mins: Discussion on basic use cases to address
- 20 mins: Initial discussion on how proposed contributions could be
  converged

  

**TSC Chair Elections**

- Nominations for TSC Chair attached
  - Chris Ferris, IBM
  - Emmanuel Viale, Accenture

- Election

- **Begin nomination period:** Today, Feb 11th, nominations includes a
  short bio/pitch less than 1 page
- **End nomination period:** 9pm Pacific Time on Wednesday, Feb 17th
- **Send slate of respective nominees to TSC Members:** Thursday, Feb
  18th
- **Send TSC members voting instructions:** Thursday, Feb 18th
- **Voting period ends:** Tuesday, Feb 23rd at 9pm Pacific Time
- **Election winners announced:** Wednesday, Feb 24th

**Code of Conduct Discussion**

- Reference point to start:
  <a href="https://www.cloudfoundry.org/foundation/code-of-conduct"
  class="external-link"
  rel="nofollow"><span>https://www.cloudfoundry.org/foundation/code-of-conduct</span></a>

- Question: Materials looks great, but how has it been applied?

  - If there was someone that was misbehaving, there is a formal channel
    to send a complaint and someone in a leadership role can then step
    in to help coach and provide guidance to maintain a healthy and
    productive environment. Cloud Foundry uses a 3 strikes rule.

- Question: How do you determine if complaint is warranted? Also, some
  language could be overreaching -- i.e. silence is taken as assent (if
  you are silent, you are somehow agreeing with poor behavior).

  - Recommendation: Keep this doc more simple. Recommend the Community
    to speak up, as opposed to silence = assent.

- **ACTION:** Mic Bowman, Chris Ferris -- create a draft and then send
  to the TSC mailing list for review and approval.

  

**Intel Contribution Overview**

- Presentation deck is attached.

- This project is a complete ledger, being used for real applications.

- Principally architected as a research platform.

- Absolutely everything is plug and play.

- Extensibility focus.

- In process of hardening code.

- 3 basic layers: communication, journal, & ledger

- Intel focuses on open marketplaces and consumer marketplaces (both
  extrinsic and intrinsic)

- Built in a complete way with purpose to ensure we get right interfaces
  for APIs but also to ensure consensus algorithms were robust enough

- Testing via internal trial (Football Exchange) -- exchange shares of
  teams

  - Real workloads running in the wild on consumer applications

- Implemented in Python

- Unique aspect: looking for ways in which we can take advantage of the
  secureguard extensions

- Intel interested in evaluation platforms based on workloads so that
  requirements can get discussed

- Have a variety of suites of tests

- Finding ways to use crypto-acceleration that Intel uses

- Q: Testing -- way to simulate network partitions?

  - Partition tests are done by hand right now. So, yes, but not
    automated.
  - Largest test is ~2,000 validators running in a cloud.

- Q: Control over latency? Force some participants to be high and some
  low?
  - Yes.

- Q: How long until code will be ready?

  - Code ready in next 3-4 weeks (best estimate)

**DRAFT Project Proposal Template**

1.  The seeds of a new project proposal has to be vetted in a public
    forum like hyperledger-technical before creating a project proposal.
2.  It needs a technical champion who believes in the project and who
    should be the technical lead on the project. The project champion
    can change in the middle of the project.
3.  The proposal template for HyperLedger Improvement Proposal (HIP):

- Author(s) name and contact details including email address, a short
  name for the project (less than 10 words).

- Abstract (less than 50 word) description of the project.

- The description and need for this project, substantiated by:

- Technical details Effects on

  - Transactions- including confidentiality, signing, traceability,
    identity of participants, contracts (scripts)
  - Effects on User facing Clients that help with transaction formation
    (similar to Wallets in BTC)
  - Effects on the network, throughput, visibility to other
    participants, change in protocol if any, criteria for network
    participation
  - Block formation and ledger formation viz. Consensus algorithm, size
    overhead, effects on the throughput and rate
  - Cryptographic implications if any.
  - Backward compatibility (hard fork or updates by all network
    participants needed?)
  - Rough design and thought experiment (Gedanken Experiment) on the
    probable effects, if any
  - Address any possible objections and also support that came up during
    seed proposal from technical community on the lists.
  - Traceablity, testing criteria to gauge effects on installed base.
  - Any other technical details, including languages used, other
    technology needed and (preferably) public sources for additional
    tools and binaries
  - References and defense of why this is needed, especially if the same
    ideas have been already addressed in any other project.

- Rough gauge of effort and resources committed (coders and any other
  resources that are needed) and timeline if available.

- Readability which means following certain conventions. The style
  itself could be controlled by Chicago Manual Of Style say, explanation
  of abbreviations, references, diagrams. A proposal editor appointed
  from by the tsc could help with this. As technical people we often do
  not think about this aspect. This is extremely important as the clear
  statement of the problem and its technical details are helpful to
  elicit a solution in the community and prompt volunteers. This can be
  helped by having a proposal builder software or a template itself.

  

- **ACTION:** TSC to weigh in and provide guidance on what they expect
  to see. This is a project proposal template that will be used by the
  TSC to evaluate. Most projects have top-level projects, as well as
  sub-level projects. Note: may also want to add a project lifecycle.
  (i.e. incubation, core, mature, etc.)

- Points of reference

 - <a href="https://wiki.allseenalliance.org/develop/proposing_a_project"
    class="external-link"
    rel="nofollow"><span>https://wiki.allseenalliance.org/develop/proposing_a_project</span></a>

  - <a href="https://wiki.opendaylight.org/view/Project_Proposals:Main"
    class="external-link"
    rel="nofollow"><span>https://wiki.opendaylight.org/view/Project_Proposals:Main</span></a>

    - Lifecycle:
      <a href="https://www.opendaylight.org/project-lifecycle-releases"
      class="external-link"
      rel="nofollow">https://www.opendaylight.org/project-lifecycle-releases</a>

  - <a href="https://wiki.fd.io/view/Project_Proposals"
    class="external-link"
    rel="nofollow"><span>https://wiki.fd.io/view/Project_Proposals</span></a>

  

**Initial Discussion on How Proposed Contributions Could Be Converged**

- DAH/IBM to be on agenda next week to discuss proposal (information
  will be sent in advance).

  - Will talk about use cases trying to address as part of proposal.
  - Whitepaper represents IBM's thinking: <a
    href="https://github.com/openblockchain/obc-docs/blob/master/whitepaper.md"
    class="external-link"
    rel="nofollow"><span>https://github.com/openblockchain/obc-docs/blob/master/whitepaper.md</span></a>

  

**Face-to-Face Meeting**

- Chris Ferris: Yes, this would be good. Would like to get to
  consensus on initial starting point and a near term of proposed
  activities. Could then actually get everyone together from a dev
  perspective to get things started. Potential to host space in Raleigh
  for short period of time, to contribute to initial sprint.
- Suggestion: Would like to see a sufficiently diverse set of use cases
  covered to meet the needs of all participants.

**Agenda Draft for 2/25 TSC Meeting**

- DAH/IBM to discuss proposal which will be sent in advance of the call.

## Recording

[Hyperledger Project - Technical Steering Committee (TSC) 02.18.16.mp4](https://youtu.be/f7JPBUU14DI)
