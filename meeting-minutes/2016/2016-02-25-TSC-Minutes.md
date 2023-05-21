---
layout: default
title: 2016 02 25 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 02 25 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

February 25, 2016 (7:00am - 8:30am PT) via GoToMeeting

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

- Welcoming Chris Ferris as TSC Chair
- DAH/IBM Proposal

**TSC Chair**

- The election for the TSC Chair has concluded -- Chris Ferris has been
  elected as the TSC Chair

**DAH/IBM Proposal**

- Digital Assets-IBM <a
  href="https://docs.google.com/document/d/1XV6U3kgZ31vZOz2nBLGe3vJgoLTnmOwv5qf3wo4lI68/edit?usp=sharing"
  class="external-link" rel="nofollow"><span><span
  class="inline-comment-marker"
  data-ref="751a8d04-12d7-4299-836d-5a0fca3ea9e5">joint
  proposal</span></span></a> for initial starting point.

- Binh provided an overview of the DAH/IBM Joint Project Proposal

- Tamas noted that the 2 individual proposals have different origins

  - DAH - experience with bitcoin network (deploy apps in financial
    services domain, more limited set of functionality). This is
    sufficient for most of DAH's use cases.
  - IBM - rethink with benefit of how this network unlocks further
    possibilities (more flexible framework)

- Questions/Comments?

  - Richard: What is the argument for why we should be trying to bring
    these 2 code bases together? They seem to be designed to solve
    different problems and optimized for different scenarios -- are
    there use cases that require both?

    - Shaul -- Code bases are very complimentary. Flexible framework
      with composable architecture.
    - Getting first instantiation of a network up. Not the last... but
      just a start. Will allow this code to be useable in the near
      future. The merge allows the start of a discussion.

  - Kelly: How are malicious docker images are dealt with?

    - Binh -- talked with Docker about this at IBM Interconnect... current
      version of docker has capabilities to shut down all activities
      from container to host system. Should be no problem with
      sandboxing code to run in container.

  - David: Recognize the strength of smart contracts (security
    guarantees). But, also believe it is important to get something
    going this year to be demonstrated. Do DAH/IBM have a timeframe for
    conversion? What kind of framework?

    - Tamas -- we should organize a hackathon to speed up convergence.
      Do not want to define with a time point.
    - Binh -- clarify that base of OBC code is there to support smart
      contracts. People can still write this in golang, Java, and
      node.js. Smart contract is there, UTXO model is there.

  - Kelly: If the goal is to merge the security and "battle-testedness"
    of Bitcoin and the UTXO model, why go with DAH instead of
    Blockstream, which is the core codebase for Bitcoin?

    - Tamas -- DAH has an integration with Blockstream code.
      Combination of enterprise friendly architecture for application
      program and integration with Bitcoin-originated Blocksteam code
      makes sense to go forward. Integrating this with IBM's flexible
      framework enables a lot of new use cases. It can also be a
      template for similar integrations.

  - Kelly: Regarding privacy, how those need to move into an off-chain
    transaction?

    - Binh -- the model in OBC is similar to what is being used for
      bitcoin. The generation of public key to be used in transaction
      is different. This is described in whitepaper and protocol spec.
    - This is a permissioned network. Every member (including clients
      -- whether application or device) would have to have a membership
      registration with entity called "membership services" -- this will
      generate a certificate called "enrollment certificate"... a client
      would have this. Then a client can request a transaction
      certificate. This is what is being used to transact on network.
      Transaction certificate generated in a way that it contains
      various info in certificate to allow us with proper authority
      (auditor or regulator) to collaborate with member. This is
      anonymous, with the exception of counterparties and
      regulators/auditors.

  - Mic: Consensus mechanisms

    - Binh -- look at consensus a bit different in OBC. Our specific
      implementation of BFT is like transaction ordering (a time
      keeper). One could treat it as a black box. Send transactions to
      it. Output is a list of all transactions to execute or validate.
      Does not matter what is happening in there, the output is a list
      of transactions to validate in order.

    - Mic -- though Ripple model may be more obvious fit for state
      transition approach.

    - CF -- idea is to get things moving and provide Project with
      framework that can be evolved as appropriate and as the community
      chooses... this is not the end-all answer. This is a starting point
      to bring together pieces that have been proposed. This does not
      exclude other proposals. This is a foundation to build on as the
      community sees fit.

    - Dave -- this is important and we have technology we'd like to
      propose. May be able to talk about it next week. Like the idea of
      flexible framework. There are concerns around docker containers
      (VMs may answer some of that).

    - CF -- highly encourages proposals to come forward. People have
      different use cases.

    - Mic -- to evaluate if this is the right flexible architecture for
      diversity of group... can we determine specifics of what hyperledger
      project is solving that isn't already covered by Blockstream, for
      example.

    - CF -- worthwhile if community could pull together white paper
      addressing exactly this. Could harvest some thoughts from
      existing IBM white paper... or combine several existing white
      papers. Should be a collaboration. Does this work for people?
      Pulling together high level use cases?

      - David Voell, Stefan Teis, Igor, Ram, all happy to help.
      - **ACTION:** Chris Ferris to create a Google doc of white paper
        and link through wiki

  - Chris Ferris: Are people comfortable with the DAH/IBM proposal to
    move forward?

    - Pardha -- agree, some working on white paper, some working on code
      in tandem.

    - Mic -- generally in favor of moving ahead quickly. 2 concerns --
      would like to see what step 2 is to ensure flexibility and
      modularity (so isn't single solution). 2) moving fast is both
      good and bad. Let's move ahead, but ensure flexibility of
      architecture.

    - Stan -- 2nd what Mic says. Let's get started quickly... but, if we
      start before white paper, should focus that architecture is
      modular enough.

    - David Voell -- move quickly and check to make sure everyone is
      comfortable with flexibility. Test, fail, move on. Don't get
      stuck in analysis paralysis.

      - **CONSENSUS:** No objections to DAH/IBM proposal. Moving
        forward with starting on modular/extensible code base, and
        integrate UTXO transaction model into OBC. In parallel, white
        paper that outlines where we are going and identify use cases.
      - Mic -- emphasis that both are important. Requirements will set
        us up for evolution of project. CF agrees.

  

**Face-to-Face Technical Meeting**

- Week for 7th, 14th, 21st
- Poll:
  <a href="http://doodle.com/poll/syyqricigc2gaewq" class="external-link"
  rel="nofollow"><span>http://doodle.com/poll/syyqricigc2gaewq</span></a>
- David Voell / JPM has offered potential meeting space in Manhattan
- F2F is open to all in the technical community, not just the 11 TSC
  members

  

**On-going**

- Code of conduct

  - **ACTION:** Mic Bowman, Chris Ferris -- create a draft on
    github/wiki and then send to the TSC mailing list for review and
    approval.

- Project proposal template

  - **ACTION:** TSC to weigh in and provide guidance on what they
    expect to see. This is a project proposal template that will be
    used by the TSC to evaluate. Most projects have top-level projects,
    as well as sub-level projects. Note: may also want to add a project
    lifecycle. (i.e. incubation, core, mature, etc.)

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

## Recording
  * [Hyperledger Project - Technical Steering Committee (TSC) 02.25.16.mp4](https://youtu.be/V6ky1IV3lhs)
