---
layout: default
title: 2016 03 25 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)
# 2016 03 25 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

**A recording of this meeting exists but the file has been moved and cannot be located by Cisco Webex.**

March 25, 2016 (8:00am - 9:00am PT)

F2F in Brooklyn & via WebEx

**TSC Members**

| Name                  | Company               | Status  |
|-----------------------|-----------------------|---------|
| Emmanuel Viale        | Accenture             | N/A |
| Stefan Teis           | Deutsche Boerse Group | Present |
| Pardha Vishnumolakala | DTCC                  | N/A |
| Chris Ferris          | IBM                   | Present |
| Mic Bowman            | Intel                 | Present |
| Richard G. Brown      | R3                    | N/A |
| Stan Liberman         | CME Group             | Present |
| Tamas Blummer         | DAH                   | Present |
| David Voell           | J.P. Morgan           | Present |
| Hart Montgomery       | Fujitsu               | Present |
| Satoshi Oshima        | Hitachi               | N/A     |

  

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

  

**Readouts from Technical F2F**

- <a
  href="https://meetings.webex.com/collabs/url/ycoK21F0wOFEukQpUNeOhD6UqRBC6lOTKh3s6Bl4zwW00000"
  class="external-link" rel="nofollow"><span>Recording</span></a>
  available of readouts from Technical F2F, which took place prior to
  TSC Meeting

  

**Getting to a Code Base**

- A team at the hackathon developed a PoC for a merged code base
- This team demonstrated their PoC work
- The team noted that they pivoted slightly from the original plans once
  the pulled code together and merged
- The net result is that they found a more elegant solution in the
  process

  

**Open Discussion**

- Comment about identity issues. Talking about federation and very
  different requirements... are we supporting multi-sig, what are wallet
  requirements, regulatory issues (hardware, tokens, etc.), privacy
  issues (i.e. Europe vs. US), This will affect all of our Federations.
  If we create a lot of different chaincodes with authority being
  granted by those chaincodes, how does that work? Suggested to TSC to
  determine where identity fits into the project.
- The TSC discussed general topics of the relationship of HLP protocols,
  code and architecture. There was interest in eventually creating a way
  to pass cryptographic proofs with a protocol for exchanging.

**Next Steps**

- Chris Ferris: recommend to merge the codebases to then start building
  and testing
  - <a href="https://docs.google.com/presentation/d/185C9JUICwJQFnf6vH2nOEBNATAVG1XBVY-e-EV6oRSQ/edit"
    class="external-link"
    rel="nofollow"><span>https://docs.google.com/presentation/d/185C9JUICwJQFnf6vH2nOEBNATAVG1XBVY-e-EV6oRSQ/edit</span></a>

- - Most TSC members favored moving forward with this proposal
  - A request was made to see the proposal documented with a few more
    specifics before casting a formal vote

- **ACTION:** Chris Ferris will formalize proposal and send out for
  review prior to a vote

  

**Future F2F**

- Plan to have another F2F in roughly 1 month's time.
- Preference for east coast -- though may want to move GEO around
