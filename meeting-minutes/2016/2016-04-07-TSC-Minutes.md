---
layout: default
title: 2016 04 07 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 04 07 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

April 7, 2016 (7:00am - 8:30am PT) via GoToMeeting

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
<td class="confluenceTd"><br />
</td>
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
- Slack:  <a href="http://hyperledgerproject.slack.com/signup"
  class="external-link"
  rel="nofollow">hyperledgerproject.slack.com/signup</a> (email
  <a href="mailto:tbenzies@linuxfoundation.org" class="external-link"
  rel="nofollow"><span>tbenzies@linuxfoundation.org</span></a> for
  access)
- Information on the TSC Members can be found at
  <a href="https://www.hyperledger.org/about/tsc" class="external-link"
  rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>

  

**Agenda**

- Action Item Review

- Intel - proposed contribution (Patrick Holmes)

- Discuss and Finalize

- - <a
    href="https://docs.google.com/document/d/1asqGu-6xlldY4uwmnkgJs3uhqUDa_wCdv9-cGUEEIOY/edit"
    class="external-link" rel="nofollow"><span>Project Lifecycle</span></a>
    template (Arnaud Le Hors)
  - <a
    href="https://docs.google.com/document/d/1J4d_Mwq-qhP07LZw2buPlALoxdMpW926xePCH_Avw6c/edit"
    class="external-link" rel="nofollow"><span>Project Proposal</span></a>
    template (Vipin Bharathan)

- Updates

- - <a
    href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
    class="external-link" rel="nofollow"><span>Requirements WG</span></a>
    (Patrick Holmes)
  - Architecture WG (Ram Jagadeesan)
  - <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
    class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
    (Dave Voell)
  - Identity Subgroup (Christopher Allen)

- Tooling F2F

- Next Technical F2F

  

**Action Item Review**

- Chris sent request to call for CI volunteers and created slack channel
- ChristopherA and Mic are having discussions to complete the readme for
  the merged code proposal that was approved

  
  

**Intel - proposed contribution (Patrick Holmes)**

- Open sourcing project “distributed ledger”

- Highly modular and extensible

- - Gossip topology:  Random walk and Barabasi-Albert
  - Consensus: PoET and Quorum voting
  - Solution domains:  Transaction Families

- Transaction Families

- - Provide data model, transaction semantics and validation

- Proof of Elapsed Time (PoET) Consensus

- - A power-efficient replacement for proof-of-work
  - Each node delays a random duration before claiming leadership
  - Trusted Execution Environment provides attestation

- <a href="http://github.com/intelledger" class="external-link"
  rel="nofollow">github.com/intelledger</a>

- - Internal name “Sawtooth”
  - Sawtooth core is the fundamental component
  - Sawtooth validator is the validator process (startup, configuration
    settings, etc.)
  - Sawtooth marketplace is more complex marketplace
  - Sawtooth dev tools is the vagrant environment
  - Documentation on <a href="http://github.io" class="external-link"
    rel="nofollow">github.io</a> 
  - Developer’s guide with API documentation
  - Marketplace Developer’s guide to use marketplace code

- <a href="http://intelledger.github.io/" class="external-link"
  rel="nofollow"><span>http://intelledger.github.io/</span></a>

- <a href="https://inteldl.slack.com/" class="external-link"
  rel="nofollow"><span>https://inteldl.slack.com/</span></a> 

- Q:  Going to make a formal proposal?

- - Patrick -- hoping people go study, do tutorial, give us feedback. 
    Then we come back in a week with further proposal of what we’d like
    to do.

- Q:  Is it possible to use SGX with this code?

- - SGX is on some processors, but not all.  We’ve created a PoET
    simulator. Simulates it running inside SGX, but not actually running
    inside SGX.  So, it is not secure implementation -- only simulating
    trusted execution environment. Working on plans now for final
    implementation using a trusted environment.

  - DM:  Algorithm there is algorithm that would run inside of trusted
    environment.  Important aspects is brings consensus back to 1 CPU 1
    vote.

  - - There is a slack channel in documentation -- would love to get
      feedback.

- Q:  Is there a whitepaper or something on this?

- - Patrick:   No. But, introduction in documentation is what is
    available.

- Q:  How does validation work?  Is there an execution engine or
  scripting engine?

- - PH:  Blocks are made up of transaction identifiers (hashes of
    transactions)… transactions are distributed through gossip network.

  - Q:  Transaction family is part of distributed ledger?

  - - It is running on each node.  The validators is a composition of
      business logic which is abstracted from consensus mechanism, the
      selections of the consensus and peer protocols.

- Q:  Business use cases?  Have you implement like IoT for example?  Or
  other business cases?

- - Mic:  a couple -- used endpoint registry (IoT)... also participated
    in R3 projects, financial services uses cases.  Have tested
    consensus mechanism with up to 1000 participating validators. 2,000
    was highest it was pushed (on VMs).

- Q:  What language support for smart contract development?

- - PH:  validator and code is Python.

- Q:  Transaction families support Turing complete language?  Or is it
  more deterministic?

- - DM:  Author transaction family that has whatever orthogonality you
    want.  Could be fully Turing complete. Attach an Ethereum-style
    execution model as a transaction family.  Example transaction
    families written have restricted verbiage to them right now.

- Q:  Privacy achieved in executing through SGX environment?

- - DM:  Anticipate doing some unique things in SGX enclaves to support
    privacy in transaction models.
  - DV:  So wouldn’t be able to implement with current code base?
  - DM:  There isn’t a private facility within this code.  Transactions
    are fairly open. But, nothing restricts you from layering privacy
    model into it.
  - Mic:  in this release, does not provide some of the fundamental
    capabilities of doing peer to peer private transactions at this
    point.

- Q:  1 vote / 1 CPU -- how is permission identified?

- - Mic:  All of validators register themselves.  That can be used as
    point of restriction for identity access.  SGX signing allows us to
    identify the fact two certificates originated from the same
    location.

  

**Discuss and Finalize**

- <a
  href="https://docs.google.com/document/d/1asqGu-6xlldY4uwmnkgJs3uhqUDa_wCdv9-cGUEEIOY/edit"
  class="external-link" rel="nofollow"><span>Project Lifecycle</span></a>
  template (Arnaud Le Hors)

- - Looked at draft a few weeks ago, have factored in edits and
    comments.

  - Clarified what incubation entails -- incubation should be fairly
    easy to get into… want people to bring ideas to explore.  We don’t
    want to preclude things at this level.

  - Question about different stages and how to progress -- is it
    linear?  Text has been clarified.

  - Just because things are easy to get into incubation, does not mean
    there is a guarantee that you will progress beyond incubation or
    that it will be easy.

  - Need to define criteria to get to incubation and the to go to mature
    stage.  Christopher Allen is working on this.

  - Can iterate and make changes as we move forward.

  - Q:  Are there particular reviews for going state to state?

  - - Idea that within each project people are labeled as leaders.  They
      decide when they want to go to mature, they have own internal
      decision making process.  From there, they would need to bring it
      to the TSC to decide if it goes to maturation.

  - **VOTE:**  This Project LIfecycle as a starting point.  We can amend
    over time.

  - - 7 of 8 present in favor (Richard abstained).  Approved.

  - **ACTION:**  Chris to move it on wiki.

  

- <a
  href="https://docs.google.com/document/d/1J4d_Mwq-qhP07LZw2buPlALoxdMpW926xePCH_Avw6c/edit"
  class="external-link" rel="nofollow"><span>Project Proposal</span></a>
  template (Vipin Bharathan)

- - Nothing has come up except for Chris’ comment that something should
    say “sponsor” instead of “author”
  - **VOTE:**  8 of 8 present - unanimous.  Approved.
  - **ACTION:**  Chris to move this on wiki.

  

**Updates**

- <a
  href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG"
  class="external-link" rel="nofollow"><span>Requirements WG</span></a>
  (Patrick Holmes)

<!-- -->

- Meeting was announced on slack requirements channel
- Goal of group is to create system requirements… best way to do that is
  through use cases.
- Next meeting will take use case through entire process.  Primrose
  (Accenture) will do work with counterfeit drugs use case.
- Will continue to use wiki.
- Next meeting time not yet set -- but will be announced on TSC list.
- Semi-active slack channel -- please join us.

  

- Architecture WG (Ram Jagadeesan)

<!-- -->

- n/a today -- updates coming next week

  

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG"
  class="external-link" rel="nofollow"><span>Whitepaper WG</span></a>
  (Dave Voell)

<!-- -->

- First meeting post-F2F yesterday
- Noam, Murali, and Mic are new participants (now there are 9)
- Reviewed why the group is starting with OBC article?  Reiterated that
  it wasn’t rubber stamping OBC… it was really taking it from
  perspective that whitepaper was a good start in technical journalistic
  rigor.  Set a good baseline to start developing and modifying from, to
  reflect what is different.
- Talked about logistics of whitepaper.
- Every 2 weeks we’ll publish new version of the draft.  Want broad
  community feedback. We’ll define process on how people can submit
  comments on wiki, as well as slack and tech mailing list.
- Google docs is good for now… but will probably migrate later.
- Should we have a whitepaper for each code stack?  Consensus was “no”
  -- this should not have any implementation details or specifics to any
  fabric under hyperledger banner.
- Actual edits -- accepted a bunch of earlier suggestions.
- Background section of paper -- OBC was originally designed to be
  permission only.  However, we will modify paper to envision scope of
  other use cases for public permissionless type mechanism.  But, this
  would be a later focus. Have not yet phrased this how we want. From
  there, it would be valuable to get Board review and agreement.
- **ACTION:**  Finalize wording to get in front of Board to review and
  opine on.
- **ACTION:**  Dave to update minutes on wiki

  

- Identity Subgroup (Christopher Allen)

<!-- -->

- Reached out on mailing list -- has a starting list of people that are
  interested in the discussion

- Determining how to meet, how to have discussion

- Identity is an important part of a permissioned system

- - Identity at the blockchain level is very different than identity
    from business logic level and how to handle
  - May feed into requirements working group

- **ACTION:**  Christopher Allen to canvass everyone that expressed
  interest, determine if they prefer a list created or just using slack.

  

**Tooling F2F**

- Steve Westmoreland  suggested everyone get together for .5 day or 1
  day to run through tooling needs, driving integration, Gerrit,
  integrate with Slack and Travis, Jenkins, etc. or whatever for build
  orchestration.
- **ACTION:**  Todd to create Doodle poll -- sometime during next few
  weeks.
- Location:  possibly New York or East Coast?

  

**Next Technical F2F**

- Next Technical F2F.  Possibly 1st week of May during Consensus event?
- **ACTION:**  Todd to send Doodle poll -- 2 days would be good.  Will
  start soliciting space, as well.

  

**Actions:**

  

- **ChristopherA and Mic to complete the readme for the merged code
  proposal that was approved**

  

- Chris Ferris to move <a
  href="https://docs.google.com/document/d/1asqGu-6xlldY4uwmnkgJs3uhqUDa_wCdv9-cGUEEIOY/edit"
  class="external-link" rel="nofollow"><span>Project Lifecycle</span></a>
  on wiki (no longer under proposals)
- Chris Ferris to move <a
  href="https://docs.google.com/document/d/1J4d_Mwq-qhP07LZw2buPlALoxdMpW926xePCH_Avw6c/edit"
  class="external-link" rel="nofollow"><span>Project Proposal</span></a>
  on wiki (no longer under proposals)
- Dave to finalize wording of whitepaper to get in from of Board to
  review and opine on.
- Dave to update minutes for whitepaper WG
- Christopher Allen to canvass everyone that expressed interest in
  Identity subgroup, determine if they prefer a list created or just
  using slack.
- Todd to create Doodle poll for Tooling F2F
- Todd to create Doodle poll for Technical F2F

## Recording

* [https://youtu.be/Du34y8u-WKM](https://youtu.be/Du34y8u-WKM)
