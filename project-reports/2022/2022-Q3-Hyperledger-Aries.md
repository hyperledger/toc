---
layout: default
title: 2022 Q3 Hyperledger Aries
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q3 Hyperledger Aries

Created by Stephen Curran, last modified by Artem Barger on Sep 01, 2022

# Project Health

Hyperledger Aries continues to grow stronger in terms of number of
contributors and in the interest from those using Aries in various use
cases. It has an extremely diverse and global community.

The following are the highlights from this past quarter:

-   The Aries Architecture is proving out as ledger agnostic
implementations are coming out with relatively little effort. For
some time, Aries Frameworks have supported pluggable DID resolvers,
allowing DIDs to be resolved on any ledger.  This quarter,
contributors are showing that AnonCreds ZKP-powered verifiable
credentials can easily be made ledger agnostic with Aries, with 3
demonstrations implemented using Hyperledger Fabric (see recording
of <a
href="https://wiki.hyperledger.org/download/attachments/71698768/video1974150021.mp4?api=v2"
rel="nofollow">presentation here</a> ),
<a href="https://cheqd.io" class="external-link"
rel="nofollow">cheqd</a> and a simple database (unpublished PoC at
this point) as the ledgers. This is a significant evolution as it
moves the use of AnonCreds beyond use only with Hyperledger Indy.
Expect that by the next report we will have support for this
capability in at least one Aries Framework.
-   Work in the community has begun on using
<a href="https://oca.colossi.network/" class="external-link"
rel="nofollow">Overlays Capture Architecture</a> (OCA) to power the
on-screen display of credentials. OCA allows a credential issuer to
define the semantics of credential attributes, such as language
translations for credential attribute labels and help text, what
attributes contain personally identifiable information (PII), the
data type and encoding of attributes, and the onscreen layout of
credentials, including support for issuer icons and background
images that can make a digital credential look like a physical
credential. This powerful capability is being enabled across Aries
frameworks, including in the Aries mobile wallet implementations.
-   An Aries "Interopathon" event is planned for the end of August 2022
with a goal of having all Aries implementers verify support for key
AIP 2.0 protocols – especially establishing connections.
-   Additional repos are being added to the Aries ecosystem to make
deployment easier, such as the
<a href="https://github.com/hyperledger/aries-mediator-service"
class="external-link" rel="nofollow">Aries Mediator Service</a> that
enables spinning up a fit-for-purpose Aries mediator based on
configured deployment Aries Cloud Agent Python. A similar Aries
Endorser Service is in the works for authorizing transactions for
writing to Hyperledger Indy network instances.
-   Rapid progress on Aries Framework JavaScript continues, with a
release (0.2.x) including some AIP 2.0 support, progress on
completing AIP 2.0 support (in upcoming release 0.3.x). PRs this
quarter added support for credentials in Aries Framework JavaScript
for using the W3C VC Data Model (issue in 0.20, presentation in
0.3.0) and an excellent new documentation site 
<a href="https://aries.js.org/" class="external-link"
rel="nofollow">https://aries.js.org/</a> .
-   <span style="letter-spacing: 0.0px;">Aries Framework Go's evolution
continues with updated support for the Sidetree protocol, DIDs, and
DIDComm. </span>
-   <span style="letter-spacing: 0.0px;">Both the  </span>
<a href="https://aries-interop.info/" class="external-link"
rel="nofollow" style="letter-spacing: 0.0px;">Aries Agent Test
Harness</a> <span style="letter-spacing: 0.0px;"> (AATH) and
especially the  </span>
<a href="https://github.com/hyperledger/aries-mobile-test-harness"
class="external-link" rel="nofollow"
style="letter-spacing: 0.0px;">Aries Mobile Test Harness</a> <span style="letter-spacing: 0.0px;"> continue to evolve. The
<a href="https://www.idlab.org/en/" class="external-link"
rel="nofollow">IDLab</a> presented ( <a
href="https://wiki.hyperledger.org/display/ARIES/2022-07-13+Aries+Working+Group+Call?preview=/71698196/71698287/20220713%20Aries%20Working%20Group%20Call%20Recording.mp4"
rel="nofollow">recording here</a> – starting at 8:28) on an
interesting tool they had developed on top of Aries Agent Test
Harness to make it easy for Aries Wallet developers to test their
app using the AATH tests. </span>
-   Attendance at the regular communities meetings is up across the
board.

There continues to be lots of delivered, verified code and increases in
participation and use of Aries.

As mentioned in the previous reports, the focus on making AnonCreds a
ledger agnostic standard vs. a de facto standard is gaining momentum.
The standard drafting process is going well, producing
<a href="https://anoncreds-wg.github.io/anoncreds-spec/"
class="external-link" rel="nofollow">this work in progress spec</a> ,
with a strong contingent working regularly to evolve it.

The Indy/Aries stack continues to be the global leader in SSI/verifiable
data solutions.

# Questions/Issues for the TSC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python – 0.7.4
-   Aries Framework JavaScript – 0.2.0
-   Aries Askar 0.2.6, 0.2.7
-   Aries VCX Releases 0.35.0, 036.0
-   Aries Framework Go 0.1.8

Interoperability status can be seen here: 
<a href="https://aries-interop.info" class="external-link"
rel="nofollow">https://aries-interop.info</a> . 

# Overall Activity in the Past Quarter

Per the  <a
href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222022-04-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-06-30T07:00:00.000Z%22%7D"
class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the second quarter of 2022 (April-June), Aries codebases had 463 PRs (up
about 12%) from 77 contributors (almost 30%).

Community participation is extremely active in Discord channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

# Current Plans

-   A continued focus on building common code for mobile wallet apps
using both Aries Framework JavaScript and Aries VCX.
-   A push to get AIP used – especially focused on establishing
connections.
-   Work on ledger agnostic AnonCreds support in Aries Frameworks and
the standardization of AnonCreds. 
-   Work on Overlays Capture Architecture (OCA) (see above) to enable
beautifully displayed credentials.
-   A split focus between deploying more production solutions and moving
the Aries frameworks forward to use new protocols – AIP 2.0 and
DIDComm v2.

# Maintainer Diversity

Aries is a multi-codebase effort, and each codebase has its own set of
maintainers. The diversity of maintainers closely matches contributors,
with notes below.  Cross framework collaboration continues to increase
through the use of the Aries Agent Test Harness. For example, interop
tests are executed daily across the Python, Go, .NET, Rust (VCX) and
JavaScript frameworks, plus two non-Hyperledger implementations of
Aries.

# Contributor Diversity

In addition to the code contribution statistics (above), here are a few
indicators of our current diversity:

-   We hold community calls each Wednesday at 7am Pacific to cover (the
mostly) US and European contributors.
-   Call attendance for each is typically in the 20-25 range, up
somewhat lately. 
-   Cross codebase interoperability efforts indicate cross-organization
cooperation.

# Additional Information

Nothing

# Submission date

04-Aug-2022

# Reviewed by

-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro"
class="confluence-userlink user-mention" data-username="angelo.decaro"
data-linked-resource-id="16327529" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
</span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors"
class="confluence-userlink user-mention" data-username="lehors"
data-linked-resource-id="2394240" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
</span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin"
class="confluence-userlink user-mention" data-username="C0rWin"
data-linked-resource-id="13865321" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Artem Barger</a>
</span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai"
class="confluence-userlink user-mention" data-username="arsulegai"
data-linked-resource-id="6427759" data-linked-resource-version="2"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn"
class="confluence-userlink user-mention" data-username="Bobbijn"
data-linked-resource-id="2393198" data-linked-resource-version="2"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a>
</span>
-   🔲 <span class="placeholder-inline-tasks"> <a
href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7"
class="confluence-userlink user-mention"
data-username="8a9ebdad74c3ca030175df13fdb500d7"
data-linked-resource-id="62239223" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">user-74455</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart"
class="confluence-userlink user-mention" data-username="denyeart"
data-linked-resource-id="2392864" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">David Enyeart</a>
</span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley"
class="confluence-userlink user-mention" data-username="grace.hartley"
data-linked-resource-id="16324128" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Grace Hartley</a>
</span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm"
class="confluence-userlink user-mention" data-username="hartm"
data-linked-resource-id="6422922" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
</span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix"
class="confluence-userlink user-mention" data-username="jimthematrix"
data-linked-resource-id="58854075" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware"
class="confluence-userlink user-mention" data-username="knagware"
data-linked-resource-id="41590145" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a>
</span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage"
class="confluence-userlink user-mention" data-username="nage"
data-linked-resource-id="2393038" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Nathan George</a>
</span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj"
class="confluence-userlink user-mention"
data-username="gl7doqu97svck56tzyjzzhxj"
data-linked-resource-id="24779271" data-linked-resource-version="1"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a>
</span>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt"
class="confluence-userlink user-mention" data-username="tkuhrt"
data-linked-resource-id="1180151" data-linked-resource-version="2"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda"
class="confluence-userlink user-mention" data-username="troyronda"
data-linked-resource-id="9110618" data-linked-resource-version="2"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>

## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-71699416"></span>
<p><a href="https://wiki.hyperledger.org/display/~swcurran"
class="confluence-userlink user-mention" data-username="swcurran"
data-linked-resource-id="5505331" data-linked-resource-version="2"
data-linked-resource-type="userinfo"
data-base-url="https://wiki.hyperledger.org">Stephen Curran</a> – I'm
glad to hear about the OCA and how this will allow for language
translations for credential attribute labels and help text.  I think we
can get a lot of people from the community involved in an Aries
translation effort.  For instance, there are active communities in
Brazil, Latin America and Japan who have done translations for Fabric
and have done other activities in Portuguese, Spanish and Japanese (and
community efforts in other languages too) who we could reach out to
about Aries translations.  It may be too early now if the OCA work is
still being put in place, but when you're ready to connect with people
interested in translations, let us know and we can come up with a plan
to reach out to those different community members who may want to
help.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by davidwboswell at Aug 04, 2022 18:52
</div></td>
</tr>
</tbody>
</table>




