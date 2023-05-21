---
layout: default
title: 2016 04 28 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 04 28 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

April 28, 2016 (7:00am - 8:30am PT) via GoToMeeting

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
- Wiki: <a href="https://github.com/hyperledger/hyperledger/wiki"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki</a>
- IRC: \#hyperledger on
  <a href="http://freenode.net" class="external-link"
  rel="nofollow">freenode.net</a> (has Meetbot)
- Public lists:
  <a href="http://lists.hyperledger.org" class="external-link"
  rel="nofollow">lists.hyperledger.org</a>
- Slack: <a href="https://slack.hyperledger.org/" class="external-link"
  rel="nofollow"><span>https://slack.hyperledger.org/</span></a> ← new,
  self-generated invites
- Information on the TSC Members can be found at
  <a href="https://www.hyperledger.org/about/tsc" class="external-link"
  rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>
- Meetings: <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar</a>

  

**Agenda**

- Ethereum technical stack and roadmap (Vitalik Buterin)
- Action Item Review (Chris Ferris)
- Technical F2F Agenda Planning (Chris Ferris)
- WG Updates (WG Leads)

  

**Ethereum** (Vitalik Buterin)

- Vitalik presented the
  <a href="https://drive.google.com/open?id=0B42vMkapQi1MeHh5OVg3bnpQTDg"
  class="external-link" rel="nofollow"><span>Ethereum Deck</span></a>

- Discussion

  - Q: Do contracts run on 1 EVM?

    - There is one EVM protocol. When an account sends a transaction to
      a contract that spins up an EVM execution instance. If in the
      middle of EVM execution instance, that contract sends a subcall to
      another contract, that spins up another execution instance.

  - Q: Does this model work the same in private chains, where you might
    not have same economics with ether?

    - The notion of gas is not dependent on the notion of ether. Gas is
      really a metering technique. On the public chain, a transaction
      may say "I will spend up to 1M gas, and will pay .0000005 ether
      per gas for that" and the miner can include or not include the
      transaction. Once it is established that transaction is included,
      there is no real link between gas and ether.
    - Gas limits in Ethereum is like bytes in Bitcoin.

  - Q: Within EVM, operation called EC Recover?

    - EC Recover is not an op code, it is a pre-compile.

  - CF: First stage would be to get EVM integrated into HLP, then could
    explore to get account model to achieve what was being discussed.
    Technical F2F next week, is there a possibility to do some
    experimentation during this?

    - AK: Yes. Vitalik is speaking at Consensus. ConsenSys is happy to
      help with integration as you see fit.
    - Vitalik: Will be at Consensus. In general, Ethereum Foundation
      is quite busy, cannot contribute FTEs to this. But, happy to
      participate as much as possible.
    - AK: have a few developers at ConsenSys that could likely help.

  - Ram: Archictecture WG next Friday -- would love Vitalik to attend.
    We are talking about evolving architecture moving forward.

    - Vitalik: send me an email offline.

  

**Action Item Review**

- TSC representation policy draft (Chris Ferris)

  - Will complete draft by next week

- Finalize Technical F2F date/venue (Todd)

  - Done
  - Please register at
    <a href="https://www.regonline.com/hyperledgertechf2may2016"
    class="external-link"
    rel="nofollow"><span>https://www.regonline.com/hyperledgertechf2may2016</span></a>

- Whitepaper draft to be complete by May 5th (Dave Voell)

  - Hopeful to have 1st draft by mid-next week for review in WG, hopeful
    to share this outside of WG at that point, but not guaranteed.

- Set up Sawtooth lake repo by April 28th (Patrick)

- Connect Patrick with Ry to figure out plan for Sawtooth Lake repo(s)
  (Todd)

- Create Fabric-API repo and annotate readme (Tamas)

  - Still working on this

- Doodle poll for 1 hour exit criteria call (Todd)

  - Plan to hold exit criteria discussion at F2F

**Techincal F2F Agenda Planning**

- CF: Plan for similar to what happened last time, hacking on various
  experiments, EVM exploration. Also, what can we hack on between
  Sawtooth Lake and Fabric. Hack on infrastructure (setting up bots to
  integrate Slack/Git, etc.). Starting transition from Travis to
  Jenkins. WG meetings could happen, too.
- ChristopherA: Would like Thursday 10:30am - 12:30pm for Identity WG
- Ram: Would like some time on Friday AM for Arch WG. 9am - noon.
- Dave: Haven't talked about F2F for whitepaper WG. Will reach out to members of WG and circle back.
- Any further ideas, please let Chris Ferris know.
- <a href="https://docs.google.com/document/d/1aBhacZvX64dJ6pms4ussxSMer9CPFAg-GHbU8XHDzSI/edit?usp=sharing">Draft agenda</a> --
  please add comments or suggestions

**WG Updates**

- <a href="https://github.com/hyperledger/hyperledger/wiki/Requirements-WG">Requirements WG</a> (Patrick Holmes)

- Architecture WG (Ram Jagadeesan)

  - Met on wednesday. Most of discussion was around consensus layer and
    how to isolate that to make it truly modular.

- <a href="https://github.com/hyperledger/hyperledger/wiki/Whitepaper-WG">Whitepaper WG</a> (Dave Voell)

- Identity Subgroup (Christopher Allen)

  - No updates (no meeting last week)

- CI WG (Chris Ferris)

  - Call with LF release engineering team, discussion captured in CI
    channel on Slack

    - Quality and security is paramount importance.
    - Clear that we likely want to use Gerrit for review process
    - If you adopt Gerrit, you are essentially turning off all commits
      to Github (as it goes through Gerrit)
    - Then can't do issue tracking using Github... in which case we adopt
      Jira or Bugzilla (but, preference was for Jira) -- LF team has
      great integration between all these tools.
    - Migrating issues out of Github into Jira? Full automation for
      this and should be painless.
    - LF team made strong recommendation for Jenkins (even though fabric
      team using Travis). Problem with Travis is that it is free and
      don't get support. LF can support Jenkins 24/7 -- operate, scale,
      etc. Also, Sawtooth Lake is already using Jenkins.
    - Because multiple repos... probably in best interest to start full
      release integration and release engineering and have FT LF person
      manning this formally.
    - Wiki -- continue to use Github wiki? May need to use mediawiki or
      some other tool. LF team has experience with this too.

## Attachments:

- [Ethereum Virtual Machine and Execution Environment Overview.pdf](../attachments/22380781/22380782.pdf)
- [Hyperledger Project - Technical Steering Committee (TSC)](https://youtu.be/gea-1OAKAZg)
