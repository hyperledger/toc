
Created by Stephen Curran, last modified by Jim Zhang on Dec 01, 2022

<span style="letter-spacing: 0.0px;"> </span> <span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Aries

# Project Health

Hyperledger Aries continues to grow stronger in terms of number of
contributors and in the interest from those using Aries in various use
cases. It has an extremely diverse and global community. The Aries
"Interopathon" held at the end of August 2022 and the Hyperledger Global
Forum were very successful in both getting developers from different
Aries Frameworks together and in introducing new developers to the
Frameworks, increasing the contributor community.

The following are the highlights from this past quarter:

-   Continued progress on ledger agnosticism in Aries, and a significant
focus on ledger-agnostic AnonCreds, culminating in the proposal
(later accepted) to create the Hyperledger AnonCreds project. This
change, along with an ongoing investigation into changing the data
format of AnonCreds into alignment with the W3C Verifiable
Credentials Standard data model will expand both the AnonCreds and
Aries communities. There will be a lot more to cover on that in the
next Hyperledger Aries and Hyperledger AnonCreds reports.
-   <span style="letter-spacing: 0.0px;">As expected, support for
AnonCreds on ledgers other than Indy is at the proof-of-concept
level within Aries Framework JavaScript, and that work will be the
basis for transitioning all of the Aries Frameworks to support
AnonCreds on ledgers other than Indy. We expect some interest as
AnonCreds becomes ledger-agnostic from the other Hyperledger
communities like Fabric and Besu in supporting the storage of
AnonCreds objects on those platforms. </span>
-   Significant moves have been made in the three most active Aries
Frameworks (ACA-Py, AFJ and Aries VCX) in completing all of AIP 2.0
and enabling key user experience features, such as OCA (below).
-   <span style="letter-spacing: 0.0px;">Progress was made in the
community on the use of  </span>
<a href="https://oca.colossi.network/" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">Overlays Capture
Architecture</a> <span style="letter-spacing: 0.0px;"> (OCA) to
power the on-screen display of credentials, as mentioned in the
previous report. Within Aries Bifold (open source wallet), OCA has
been implemented and deployed in the newly launched BC Wallet
(available on app stores now). </span>
-   <span style="letter-spacing: 0.0px;">OCA allows a credential
issuer to define the semantics of credential attributes, such as
language translations for credential attribute labels and help
text, what attributes contain personally identifiable
information (PII), the data type and encoding of attributes, and
the onscreen layout of credentials, including support for issuer
icons and background images that can make a digital credential
look like a physical credential. </span>
-   <span style="letter-spacing: 0.0px;">Speaking of Aries Bifold,
substantial progress has been made. Perhaps the most significant
advance of the quarter was the creation by the Wallet Team at BC Gov
to make a pipeline that allows for the publication of fully
customized Aries Bifold wallet via a patching process that minimizes
the code outside of Aries Bifold. This has allowed that team to do
~90% of their code at the Aries Bifold level for the benefit of the
entire community, while still producing a fully custom BC Wallet for
publication to app stores. This is a FAR, FAR better model than a
team forking Aries Bifold and then developing on the fork, with
painful effort to give back contributions. This approach needs to be
promoted and replicated by others wanting a publishable, high
quality wallet. Key features added to Aries Bifold: </span>
-   <span style="letter-spacing: 0.0px;">Wallet security features –
PIN and Biometrics </span>
-   <span style="letter-spacing: 0.0px;">Wallet initialization
actions and screens easily customized for a specific deployment.</span>
-   Configurable settings.
-   The addition of OCA handling for a better user experience.
-   Must work was done on the Aries Endorser Service, a service that is
commonly needed in Indy deployments of Aries agents, where a
permissioned agent signs transactions to be written to an Indy
ledger on behalf of an author.
-   Rapid progress on Aries Framework JavaScript continues, with a
release of several 0.2.x (current), and release 0.3.x (future)
versions.
-   <span style="letter-spacing: 0.0px;">Aries Framework Go's evolution
continues with updated support for the Sidetree protocol, DIDs, and
DIDComm. </span>
-   <span style="letter-spacing: 0.0px;">Both the  </span>
<a href="https://aries-interop.info/" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">Aries Agent Test
Harness</a> <span style="letter-spacing: 0.0px;"> (AATH) and
especially the  </span>
<a href="https://github.com/hyperledger/aries-mobile-test-harness" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">Aries Mobile Test Harness</a> <span style="letter-spacing: 0.0px;"> continue to evolve. AATH and AAMH
were covered and used at the Aries Interopathon in August, and tests
and test wrappers for Aries Agents continue to be expanded. The only
concern in that area is that the Aries Framework Go team seems to no
longer be using AATH. </span>
-   Attendance at the regular communities meetings is high across the
board.

There continues to be lots of delivered, verified code and increases in
participation and use of Aries.

The Indy/Aries stack continues to be the global leader in SSI/verifiable
data solutions, with AnonCreds the most used credential format.

# Questions/Issues for the TSC

None.

# Releases

The following Aries releases occurred in the last quarter:

-   Aries Cloud Agent Python – 1.0.0-rc0
-   Aries Framework JavaScript – 0.2.2, 0.2.3 and 0.2.4
-   Aries Askar
-   Aries VCX Releases 0.37.0, 0.38.0, 0.39.0, 0.40.0, 0.41.0, 0.42.0
-   Aries Framework Go

Interoperability status can be seen here: 
<a href="https://aries-interop.info" class="external-link" rel="nofollow">https://aries-interop.info</a> . 

# Overall Activity in the Past Quarter

Per the  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;subTab=technical?time=%7B%22from%22:%222022-07-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222022-09-30T07:00:00.000Z%22%7D" class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the third quarter of 2022 (July-September), Aries codebases had 412 PRs
(down slightly) from 69 contributors (down slightly). Impressive, given
this is over the summer holiday months in the northern hemisphere.

Community participation is extremely active in Discord channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

# Current Plans

-   A continued focus on building common code for mobile wallet apps
using both Aries Framework JavaScript and Aries VCX.
-   Continuing the push to get AIP used – especially focused on
establishing connections.
-   Work on ledger agnostic AnonCreds support in Aries Frameworks and
the standardization of AnonCreds. 
-   Work on Overlays Capture Architecture (OCA) (see above) to enable
beautifully displayed credentials.
-   A split focus between deploying more production solutions and moving
the Aries frameworks forward to use new protocols – AIP 2.0 and
DIDComm v2.

# Maintainer Diversity

Aries is a multi-codebase effort, and each codebase has its own set of
maintainers. The diversity of maintainers closely matches contributors,
with notes below.  Cross framework collaboration continues to increase
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

03-Nov-2022

# Reviewed by
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~C0rWin" class="confluence-userlink user-mention" data-username="C0rWin" data-linked-resource-id="13865321" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Artem Barger</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a></span>
-   🔲 <span class="placeholder-inline-tasks"> <a href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7" class="confluence-userlink user-mention" data-username="8a9ebdad74c3ca030175df13fdb500d7" data-linked-resource-id="62239223" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">user-74455</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware" class="confluence-userlink user-mention" data-username="knagware" data-linked-resource-id="41590145" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   🔲 <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>




