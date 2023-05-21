---
layout: default
title: 2016 03 03 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 03 03 TSC Minutes


**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

March 3, 2016 (7:00am - 8:30am PT) via GoToMeeting

**TSC Members**

<div class="table-wrap">

<table class="wrapped confluenceTable">
<tbody>
<tr class="odd">
<td class="confluenceTd"><p><span>Emmanuel Viale</span></p></td>
<td class="confluenceTd"><p><span>Accenture</span></p></td>
<td class="confluenceTd"><p><span>Yes</span></p></td>
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
<td class="confluenceTd"><p><span>Kei Taniuchi</span></p></td>
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
- Wiki: <a href="https://github.com/hyperledger/hyperledger/wiki"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki</a>
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

- F2F Discussion (Todd Benzies)

- JP Morgan / overview of proposed contribution (Dave Voell)

- Project Proposal Template (Vipin Bharathan)

- On-going (Chris Ferris)

  - Requirements
  - White paper
  - Code of Conduct

**Face-to-Face Technical Meeting**

- Tentative for 3/22 - 3/25 (with 3/25 being a half-day concluding
  around 1pm ET)
- JP Morgan has space available in Brooklyn, NY
- Capacity of roughly 100 people in cluster format (could go up to 150
  classroom style, but not ideal)
- ACTION: Todd to finalize details with Dave and share registration
  details with the TSC list in the coming days
- CF: This is a working meeting, there is a lot of code to be written.
  The attendees should be the engineers who are actually working on
  code. Can also spend time on requirements, white paper, etc.
  Encourage people on this call to think about what their role is and
  how they'd like to engage.
- Finalize agenda for F2F on next week's TSC call

  

**JP Morgan's Proposed Contribution**

- Will Martino presented JPM's proposed contribution
 [NPD Juno Distributed Cryptoledger.pdf](https://github.com/hyperledger/toc-docs/blob/main/2016/03/03/2016%2B03%2B03%2BTSC%2BMinutes-attachment-JPMC_Juno_Distributed_Cryptoledger.pdf)

- Discussion/Questions
  - JPM has bright Haskell devs
  - Other work was paired with a Haskell implementation, able to get off
    the ground quickly
  - Also, for language engineering, Haskell is really great
  - Security is strong

  - Local, on a single system. Should be getting on AWS in the near
    term, now that it is open source.

  - Everything is in Haskell.
  - Juno is designed for enterprise apps that are not on publicly facing
    internet.
  - Wanted higher performance... really to be run on intranet or
    intrafirm setup
  - Want higher performance, but don't need all the features of Bitcoin

  - Replacing messaging substructure for higher protection, though not
    done yet
  - Only need to be robust against some of the set of what Byzantine
    fault tolerance covers
  - In an enterprise deployment companies are going to want a button to
    set the system to read only if something of concern is happening

  - To a certain extent. This is a chain of blockchain blocks where
    there is a single transaction in each block, instead of a group.
    Raft orders messages.

  - It is for a while. Everything is bounded. It is verified at
    compile time. All computations are finite.

  - Hopper is still in its early stages.
  - This will have a few primitives to compose on top of each other,
    should model any type of ownership situation. Domain specific
    language assets that you don't want to create or destroy, but
    instead transfer ownership, track, escrow, etc.
  - Internal use case only required a single, primitive command.

  - Not too familiar with UTXO model.
  - Hopper doesn't have ability for I/O.
  - Every point there is a diff of the state that comes out that you can
    look at.
  - Soon we will add snapshotting.

  - Raft -- only bring up or down, add or remove, etc. at the consensus
    level one at a time. Tested pretty heavily -- to see how it handles
    faults, partitions. In terms of node count? ...don't know yet. Need
    to start hammering 1000 nodes. Need to geo distribute. Any trading
    partner would have 3-7 local nodes.
  - Topology -- pretty flexible still at this point.

  - Smart contract language should not do I/O. I/O is inherently
    nondeterministic.

  - Need to finish enhancements, in heads down mode for production
    pilot.
  - Re: integration -- need to look at API. Tried making general
    purpose API, but haven't had a lot of success with it yet.
  - Use cases that involve high transaction volumes -- this is
    interesting technology that could be plugged into the open,
    extensible architecture as an option.
  - First and foremost, want everyone to take a look at this
    technology. Can discuss and experiment with it further at the F2F
    in a few weeks.

  - Q: Why are you using Haskell as the programming language?
  - Q: Characteristics in terms of deployments and test -- high number
    of transactions. Local or global deployment?
  - Q: What language is juno implemented in? Also, elaborate on Raft?
  - Q: PBFT, assumption of Byzantine conditions. When nodes in
    different networks, collaboration between different companies, if
    you are in a well protected area, might not have the security
    assumptions.
  - Q: Do you still have concept of blocks?
  - Q: Is the contract language Turing complete?
  - Q: Is primary scenario surrounding asset transfer? Are there other
    scenarios this environment could address?
  - Q: On transactions, since you have a back-end interpreter or a VM
    to execute things like ethereum programming model, is your
    transaction a UTXO model like Bitcoin, or is it like state
    transition model?
  - Q: Topology -- number of trading partners, number of servers, how
    often servers join and leave?
  - Q: Do you plan to have contracts be able to get/post data from
    contracts to outside of the blockchain?
  - Q: Specifically, what are your thoughts on next steps? Looking at
    integrating the consensus capabilities? Hopper seems to naturally
    fit into smart contracts execution capabilities in OBC.

**Project Proposal Template**

- [Proposal Template for a Hyperledger Improvement Project (HIP).pdf](https://github.com/hyperledger/toc-docs/blob/main/2016/03/03/2016%2B03%2B03%2BTSC%2BMinutes-attachment-Proposal%2BTemplate%2Bfor%2Ba%2BHyperledger%2BImprovement%2BProject%2B%2528HIP%2529.pdf)

- ACTION: open for feedback and comment -- please take time during this
  coming week to review and provide feedback

- Points of reference

  - <a href="https://wiki.allseenalliance.org/develop/proposing_a_project"
    class="external-link"
    rel="nofollow"><span>https://wiki.allseenalliance.org/develop/proposing_a_project</span></a>
  - <a href="https://wiki.opendaylight.org/view/Project_Proposals:Main"
    class="external-link"
    rel="nofollow"><span>https://wiki.opendaylight.org/view/Project_Proposals:Main</span></a>
  - <a href="https://wiki.fd.io/view/Project_Proposals"
    class="external-link"
    rel="nofollow"><span>https://wiki.fd.io/view/Project_Proposals</span></a>

**Project LIfecycle**

- Point of reference:
  <a href="https://www.opendaylight.org/project-lifecycle-releases"
  class="external-link"
  rel="nofollow">https://www.opendaylight.org/project-lifecycle-releases</a>

- CF: Would like to see this in place for Hyperledger Project

- DV: This looks like a great start -- a good portion of this could be
  directly adopted.

- MB: Want a little bit of time to look through -- however, it is
  pretty generic and looks fine.

- ACTION: TSC to review and provide comments.

- RB: What is a Hyperledger project or sub-project? Is IBM/DAH a
  project?

  - CF: Working through experiment right now (IBM/DAH). Out of that,
    we are able to graduate whatever we come up with. There will be a
    number of different components that could be independently managed
    as a project (smart contracts component, ledger component, etc.) may
    make sense to manage them independently, may not.

  

**On-going**

- White Paper
- Code of Conduct
- Requirements

**Agenda for 3/10**

- Plan agenda for F2F
- Please send other topics for agenda

## Attachments:
* [NPD Juno Distributed Cryptoledger.pdf](https://github.com/hyperledger/toc-docs/blob/main/2016/03/03/2016%2B03%2B03%2BTSC%2BMinutes-attachment-JPMC_Juno_Distributed_Cryptoledger.pdf)
* [Proposal Template for a Hyperledger Improvement Project (HIP).pdf](https://github.com/hyperledger/toc-docs/blob/main/2016/03/03/2016%2B03%2B03%2BTSC%2BMinutes-attachment-Proposal%2BTemplate%2Bfor%2Ba%2BHyperledger%2BImprovement%2BProject%2B%2528HIP%2529.pdf)
* [JPMC Juno Distributed_Cryptoledger.pdf](https://github.com/hyperledger/toc-docs/blob/main/2016/03/03/2016%2B03%2B03%2BTSC%2BMinutes-attachment-JPMC_Juno_Distributed_Cryptoledger.pdf)
* [Hyperledger Project - Technical Steering Committee (TSC) 03.03.16.mp4](https://youtu.be/wicE1g2xB4g)
