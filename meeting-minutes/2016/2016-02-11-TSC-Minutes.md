---
layout: default
title: 2016 02 11 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 02 11 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

February 11, 2016 (7:00am - 8:30am PT) via GoToMeeting

**TSC Members**

| Name                  | Company               | Status  |
|-----------------------|-----------------------|---------|
| Emmanuel Viale        | Accenture             | Present |
| Kireeti Reddy         | CME Group             | N/A     |
| Shaul Kfir            | DAH                   | N/A     |
| Stefan Teis           | Deutsche Boerse Group | Present |
| Pardha Vishnumolakala | DTCC                  | Present |
| Kei Taniuchi          | Fujitsu               | N/A     |
| TBD                   | Hitachi               | N/A     |
| Chris Ferris          | IBM                   | Present |
| Mic Bowman            | Intel                 | Present |
| David Voell           | J.P. Morgan           | Present |
| Richard G. Brown      | R3                    | Present |


More information on the TSC Members can be found at
<a href="https://www.hyperledger.org/about/tsc" class="external-link"
rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>

**TSC Chair Elections**

- Note: if you are a Premier member and have not yet notified
  <a href="mailto:tbenzies@linuxfoundation.org" class="external-link"
  rel="nofollow"><span>tbenzies@linuxfoundation.org</span></a> of your
  TSC representative, please do so ASAP.

- Process for electing a TSC Chair (from the 11 TSC members)

  - **Begin nomination period:** Today, Feb 11th, nominations includes a
    short bio/pitch less than 1 page
  - **End nomination period:** 9pm Pacific Time on Wednesday, Feb 17th
  - **Send slate of respective nominees to TSC Members:** Thursday, Feb
    18th
  - **Send TSC members the ballot link to electronic voting:** Thursday,
    Feb 18th using Condorcet voting
    (http://<a href="http://civs.cs.cornell.edu/" class="external-link"
    rel="nofollow"><span>civs.cs.cornell.edu/</span></a>)
  - **Voting period ends:** Tuesday, Feb 23rd at 9pm Pacific Time
  - **Election winners announced:** Wednesday, Feb 24th

- The TSC operates in the open (open calls, public list)

- Startup Period: During the first six (6) months after project launch,
  the TSC voting members shall consist of one (1) appointed
  representative from each Premier Member and each Top Level Project
  Maintainer, provided that no company (including related companies or
  affiliates under common control) shall have more than three (3) votes
  on the TSC.

- Steady State: After the Startup Period, there shall be a nomination
  and election period for electing Contributors or Maintainers to the
  TSC. The TSC voting members shall consist of eleven (11) elected
  Contributors or Maintainers chosen by the Active Contributors. An
  Active Contributor is defined as any Contributor who has had a
  contribution accepted into the codebase during the prior twelve (12)
  months. The TSC shall approve the process and timing for nominations
  and elections held on an annual basis.

**Tools/Services**

- IRC: \#hyperledger on
  <a href="http://freenode.net" class="external-link"
  rel="nofollow">freenode.net</a> (has Meetbot)
- Public lists:
  <a href="http://lists.hyperledger.org" class="external-link"
  rel="nofollow">lists.hyperledger.org</a>
- Slack:
  <a href="http://hyperledgerproject.slack.com" class="external-link"
  rel="nofollow">hyperledgerproject.slack.com</a> (it was noted that it
  is possible to bridge IRC w/ Slack)
- Wiki would be useful -- Linux Foundation to set up

**Meeting Cadence**

- Consensus: \[weekly\] Thursdays, 7:00am - 8:30am PT
	- Evaluate after 1 month if any changes to cadence or timing are necessary
  
**Code**

- Discussion on where and how to land code -- getting proposed code into
  public review.

- Should code under review remain on
  [http://www.github.com/staging-blockchain](www.github.com/staging-blockchain)
  or be moved to the formal org
  [http://www.github.com/hyperledger](www.github.com/hyperledger)?

  - Consensus: use
    [http://www.github.com/hyperledger](www.github.com/hyperledger),
    companies with proposed code can point to their repos from the
    readme, and note whether those linked repos are either "snapshot" or
    "ongoing development"

**Template for Proposal Evaluation**

- Stefan Buhrmester and Vipin Bharathan have volunteered to help edit an
  initial template for TSC review

**Proposals for Common Starting Points**

- Previous discussion

  - Networking
  - BFT
  - Storage
  - Cryptographic libraries
  - Member services

- Consensus: start lower down the stack where people are much closer in
  agreement, and then slowly work up the stack.

- Needed: create a github markdown doc for documenting use cases

  

**Agenda Draft for 2/18 TSC Meeting**

- Discussion on basic use cases to address
- High-level thoughts on how proposed contributions could be converged
- Walk-through of project proposal template (Stefan Buhrmester and Vipin
  Bharathan)

  

**Previous Discussions from Formation Meetings**

- Evaluation Criteria

  - Security
  - Interoperability
  - Scalability
  - Extensibility
  - Deployment Environment
  - Ecosystem
  - Change Management
  - Resilience

  

- Functional Requirements

  - Contract Execution Environment
  - Transaction
  - Block of Transactions
  - Network
  - Consensus/Validation
  - Authentication & Entitlements
  - Reference Data
