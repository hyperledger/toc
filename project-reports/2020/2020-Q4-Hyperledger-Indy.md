---
layout: default
title: 2020 Q4 Hyperledger Indy
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Indy

Created by Stephen Curran, last modified by David Enyeart on Nov 19, 2020

# <span style="letter-spacing: 0.0px;">Projects </span>

##### **Distributed Ledger**

-   <a href="https://github.com/hyperledger/indy-node" class="external-link" rel="nofollow"><span>indy-node </span></a>
-   <a href="https://github.com/hyperledger/indy-plenum" class="external-link" rel="nofollow"><span>indy-plenum </span></a>

##### **Client Tool**

-   <a href="https://github.com/hyperledger/indy-sdk" class="external-link" rel="nofollow"><span>indy-sdk </span></a>
-
<a href="https://github.com/hyperledger/indy-vdr" class="external-link" rel="nofollow">indy-vdr</a>

##### **Shared Components**

-   <a href="https://github.com/hyperledger/indy-hipe" class="external-link" rel="nofollow"><span>indy-hipe </span></a>
-   <a href="https://github.com/hyperledger/indy-test-automation" class="external-link" rel="nofollow"><span>indy-test-automation</span></a>
-    <a href="https://github.com/hyperledger/indy-node-monitor" class="external-link" rel="nofollow">indy-node-monitor</a>

# Project Health

Indy is a healthy project, particularly at the deployments and business
interest level, but has a current lack of contributors.  The maintainers
are working to address that issue.

Per the
<a href="https://lfanalytics.io/projects/hyperledger%2Findy/dashboard" class="external-link" rel="nofollow">Indy Activity Dashboard</a>
, Indy’s codebase has 22,520 commits from 241 unique contributors (up
from 238 last report). This quarter there were 70 commits from 14
contributors, up from 8 in the previous report.

This quarter the [Indy
Interop-athon](https://wiki.hyperledger.org/display/II) was held th"at attracted more than a 100 attendees to a two-day virtual conference
about the future of Indy, and notably about creating interoperability
between independent deployments of Indy. At this time there are at least
6 independent implementations of Indy in production (Sovrin Foundation),
test (Indicio, IDUnion) or planning (Bedrock, CanCred and FIndy).

# Questions/Issues for the TSC

## Issues from previous reports:

### Incompatible agent implementations

**Update** : This is progressing well and is really being dealt with at the Aries level.  Closing this issue from an Indy perspective.

### Measuring the size and make-up of our user community

**Update** : The work of Ry Jones on the Indy Activity Dashboard has
resolved this issue. Closing.

### Build Pipelines

**Update** : Progress is being made on converting the CI/CD pipeline
from Jenkins to GitHub Actions, particularly for indy-node.

We had one minor release of indy-node in the last quarter. We are
currently preparing another release of indy-node that is largely focused
on the CI/CD pipelines to integrate and deliver the release,
transforming those pipelines from Jenkins (circa 2018) to GitHub
Actions. We have a small team that have agreed to do that with the
guidance of the early Indy developers from Evernym.

### **Diversity of Contributor Community**

Update: Progress was made with the Indy Interop-athon Conference
attracting a large audience that demonstrated there is strong interest
in the conference. Attendance at the regular Indy Contributors call has
been good, and work has (slowly) been starting.  A number of groups (BC
Gov, Sovrin) are looking at ways to create opportunities for
contributions, such as bringing together groups to fund capabilities. 

There two additional efforts in the community that will add
contributors – a specification effort related to a W3C standard DID
Method for Indy ("did:indy") to enable cross-deployment
interoperability, and changes to indy-node to support the new DID
Method.

# Releases

### **August 2020:**

##### Indy Node 1.12.4

-   A response to an identified security vulnerability that if exploited
could allow unauthorized updates to meta-data about DIDs published
on the ledger.

# Overall Activity in the Past Quarter

In the past quarter, ledger development has slowed as we focus on
upgrading the CI/CD pipeline and defining the Indy DID Method. Some work
has occurred in the indy-sdk and release planning has begun for that,
with resources committed to the work. In doing the indy-sdk release,
we'll work on (at least) documenting the process to enable modernizing
the CI/CD pipeline for the project.

# Current Plans

There is little ledger activity occurring, so the current plans have not
evolved significantly from the last report.

We've added a focus on interoperability across Indy deployments using
the Indy DID Method as the driver for that work.

Previous work on "rich schemas" to support W3C VCs has been put on hold
and will likely be replaced with a focus on BBS+ ZKPs, which likely has
the benefit of eliminating (well, deprecating) features from Indy vs.
adding.

Our focus for client libraries is to break LibIndy into separate
components that can be evolved to fit the proposed Aries architecture.
Isolated progress has been made on that effort, but the work is not had
a large audience as yet.  We hope that will occur this quarter.

Work on an improved revocation has progressed slowly, delayed within the
Ursa community.

# Maintainer Diversity

The weekly Indy Contributors call continues to be the medium by which
maintainers coordinate work, discuss critical issues to the Indy
codebase, and agree on HIPEs. Interest in and attendence at the Indy
Contributors meetings are rising.

# Contributor Diversity

We've had several organizations join the Indy Contributors call and some
are doing the work on the upcoming release (code changes) and the CI/CD
pipeline.

# Additional Information

-   Key channels on Hyperledger Rocket Chat: \#indy, \#indy-sdk,
\#indy-node, \#indy-maintainers
-   <span style="letter-spacing: 0.0px;">Join the Indy Mailing List:</span>
<a href="https://lists.hyperledger.org/g/indy" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://lists.hyperledger.org/g/indy</a>

# Reviewed by
-   🔲Angelo De Caro
-   ✅Arnaud J Le Hors
-   ✅Arun S M
-   ✅Baohua Yang
-   🔲 <span style="color: rgb(23,43,77);"> Bobbi Muscara  </span>
-   ✅Dave Enyeart
-   🔲Gari Singh
-   ✅Grace Hartley
-   ✅Danno Ferrin
-   ✅Hart Montgomery
-   ✅Mark Wagner
-   ✅María Teresa Nieto
-   ✅Nathan George
-   ✅Tracy Kuhrt
-   ✅Troy Ronda



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41586449"></span>
<p>The "Indy community" seems to often work on other projects outside of
core Indy (i.e. Aries and Ursa).  As such, would a better measure of
community health be the sum of contributions/progress/development across
all of these projects?  I'd be curious to hear what the maintainers had
to say about this.  Thanks!</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by hartm at Nov
19, 2020 02:26 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41586503"></span>
<p>I'd also love to hear more about how Indy has had success with
different organizations joining their contributor calls. I know other
projects, specifically Besu, have struggled to get engagement and
attendance for our contributor calls so would be curious what works well
for Indy.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by grace.hartley
at Nov 19, 2020 14:33 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41586540"></span>
<p>I’m not sure there is a secret to it.  Here is what we emphasize when
working with call coordinators:</p>
<ul class="incremental">
<li>Always make sure the call happens.  Consistent time and duration is
important to keeping your core audience.</li>
<li>Have content that creates discussion and fear of missing out.  Focus
time on those writing code or who need discussions to get more done, not
theory or speculation.  </li>
<li>Announce agendas early so that participants know in advance that it
will be worth their time.  </li>
<li>Post the recording </li>
<li>Encourage constructive debate and leverage calls for things that are
hard to do over text-mediums.</li>
<li>Invite everyone to share, ask questions and get involved.  Your best
contributors and participants will come from places that surprise
you.</li>
</ul>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by nage at Nov
19, 2020 15:17 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41586541"></span>
<p><a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>  – I
would agree with your assessment that the set of Hyperledger
identity-related projects is getting participation. However, the focus
is much more on Aries because that is where the use cases exist and
people are building apps and ecosystems around the use cases.  The
challenge is that Indy is to the level that it "just works", and
organizations can build their use cases and use Sovrin as a ledger. Wh"at they aren't doing is dropping down to add more to Indy itself.  For
example, something as mundane as upgrading the dependencies to support
Ubuntu 20.04 is not getting attention. Part of that is understanding
(and having to understand) the CI/CD pipeline, which we are fixing.  But
getting contributions has been difficult.</p>
<p><br />
</p>
<p><a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a>   – the
success of the contributor calls has been because there are a number of
groups building on Aries (and hence, Indy) and there is interest in the
topics we are talking about. But those discussions are not translating
enough into contributions – people spending time between calls writing
code and submitting PRs.  We're working on that, as the ecosystem is
reliant on it. The trick is to convey the urgency, without scaring
groups off.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by swcurran at Nov 19, 2020 15:18 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41586562"></span>
<p>Thanks, Nathan. This makes a lot of sense and is helpful feedback. I
definitely like the idea of making contributors feel FOMO. I think Besu
could also do better at announcing the agendas earlier. </p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by grace.hartley
at Nov 19, 2020 16:21 </div ></td>
</tr>
</tbody>
</table>




