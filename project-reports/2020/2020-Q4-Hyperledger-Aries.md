---
layout: default
title: 2020 Q4 Hyperledger Aries
parent: 2020
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2020 Q4 Hyperledger Aries

Created by Stephen Curran, last modified by Gari Singh on Feb 05, 2021

<span style="letter-spacing: 0.0px;"> </span> <span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Aries

# Project Health

Project health is strong, getting stronger, and the community is
thriving. There are a number of significant projects going on within and
outside of Hyperledger related to Aries, and continuous progress is
being made across the community.

# Questions/Issues for the TSC

Given the nature of Hyperledger Aries as a set of protocols and a set of
implementations of those protocols versus a releasable artifact, how do
we declare Aries as "active" vs. the current "incubation"? A newcomer
arriving at Hyperledger knowing about Indy and Aries might see the
"incubation" status and shy away, even though <span class="inline-comment-marker" ref="399af380-478a-4b51-8d3e-35e900863cab">Aries </span> builds on Indy
and it has numerous production deployments?  IMHO, Aries is production
ready, but there has been little discussion about changing the status,
and it's not clear how the Hyperledger definition should apply to this
type of project.

A second question relates to the fact that a core element of Aries is
the protocols defined in the
<a href="https://github.com/hyperledger/aries-rfcs" class="external-link" rel="nofollow">Aries RFCs</a> repo. Does the TSC
have an opinion on whether Hyperledger Aries is the right, safe location
for those protocols?

# Releases

There are three major Frameworks in Aries – Aries Cloud Agent Python
(ACA-Py), Aries Framework Go (AFGo) and Aries Framework .NET (AFD), with
a fourth (aries-framework-vcx) being extracted from Indy into Aries. 
All are active, with ACA-Py and AFGo releasing regularly:

-   ACA-Py had 11 releases in 2020
-   Aries Framework Go has 5 releases in 2020

There are (at least) 14 active repos in Aries (per the metrics below –
although I think there might be a couple of others...to be verified),
including the major (and several less mature) frameworks, conformance
and interoperability test suites, and several tools and utilities. 
Added in early 2021 is an Aries-level secure storage component th"at replaces a comparable component in the indy-sdk and is available for use
across frameworks. It is the first "shared component" in Aries, with
more expected in the next year.

# Overall Activity in the Past Quarter

Per the  <a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Faries/dashboard;v=source-control%2Fcommits%2Foverview?filter=%23%2Fdashboard%2FGit%3Fembed%3Dtrue%26_g%3D(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:%272020-10-01T07:00:00.000Z%27,to:%272020-12-31T08:00:00.000Z%27))%26_a%3D(description:%27Git%2520Overview%2520panel%27,filters:!((%27$state%27:(store:appState),meta:(alias:%27Empty%2520Commits%27,disabled:!f,index:git,key:files,negate:!t,params:(query:%270%27),type:phrase),query:(match:(files:(query:%270%27,type:phrase)))),(%27$state%27:(store:appState),meta:(alias:Bots,disabled:!f,index:git,key:author_bot,negate:!t,params:(query:!t),type:phrase),query:(match:(author_bot:(query:!t,type:phrase))))),fullScreenMode:!f,options:(darkTheme:!f,useMargins:!t),panels:!((embeddableConfig:(title:%27Commits%2520Percentage%2520By%2520Organization%27),gridData:(h:16,i:%271%27,w:13,x:22,y:0),id:git_commits_organizations,panelIndex:%271%27,title:%27Commits%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Commits%2520by%2520Time%2520Zone%27),gridData:(h:9,i:%272%27,w:15,x:33,y:16),id:git_commits_timezone,panelIndex:%272%27,title:%27Commits%2520by%2520Time%2520Zone%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Active%2520Contributors%27),gridData:(h:9,i:%273%27,w:17,x:0,y:16),id:git_evolution_authors,panelIndex:%273%27,title:%27Active%2520Contributors%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Commits),gridData:(h:9,i:%274%27,w:16,x:17,y:16),id:git_evolution_commits,panelIndex:%274%27,title:Commits,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Commits%2520By%2520Organization%27),gridData:(h:15,i:%275%27,w:25,x:0,y:25),id:git_evolution_organizations,panelIndex:%275%27,title:%27Commits%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(),gridData:(h:16,i:%27788f235e-6d11-451b-ba12-50e7b8765e0f%27,w:13,x:0,y:0),id:%27985c11c0-a449-11ea-bb19-4b3cb1a7236f%27,panelIndex:%27788f235e-6d11-451b-ba12-50e7b8765e0f%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Lines%2520Changed%2520Percentage%2520By%2520Organization%27),gridData:(h:16,i:a8bec484-b99e-4cdc-96f2-722907cf4d00,w:13,x:35,y:0),id:e70ac370-b6f0-11ea-83d0-e156a256d6e6,panelIndex:a8bec484-b99e-4cdc-96f2-722907cf4d00,title:%27Lines%2520Changed%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27),gridData:(h:15,i:%271fc7bf78-a4e8-406b-86c5-8ac4eb3870f1%27,w:23,x:25,y:25),id:f39c7140-b7d3-11ea-a5b0-397acf9566c5,panelIndex:%271fc7bf78-a4e8-406b-86c5-8ac4eb3870f1%27,title:%27Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Organization%2520Commits%27),gridData:(h:18,i:c73b96e3-a6ec-4b4a-aa9f-7bd4b158c968,w:48,x:0,y:78),id:%273c6f01b0-f21e-11ea-ada8-692b75e53835%27,panelIndex:c73b96e3-a6ec-4b4a-aa9f-7bd4b158c968,title:%27Organization%2520Commits%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Summary),gridData:(h:16,i:d65f6177-a704-4194-861d-019efd71a00f,w:9,x:13,y:0),id:%2713de3220-1aaf-11eb-b81d-a32b9537df14%27,panelIndex:d65f6177-a704-4194-861d-019efd71a00f,title:Summary,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Authors),gridData:(h:19,i:%278cdb35b3-6f32-416f-956b-50f7b221e73e%27,w:19,x:0,y:40),id:%2731f04bd0-1ab0-11eb-b81d-a32b9537df14%27,panelIndex:%278cdb35b3-6f32-416f-956b-50f7b221e73e%27,title:Authors,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Organizations),gridData:(h:19,i:d4d3ea5e-fedf-4818-bfe4-e6de2ab43a3c,w:29,x:19,y:40),id:ca6b1b90-1ab2-11eb-bbd0-c758192c580e,panelIndex:d4d3ea5e-fedf-4818-bfe4-e6de2ab43a3c,title:Organizations,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Repositories),gridData:(h:19,i:a476e04a-1dde-4bdc-98b6-8c6d16c30b46,w:31,x:0,y:59),id:de3203e0-1ab3-11eb-bbd0-c758192c580e,panelIndex:a476e04a-1dde-4bdc-98b6-8c6d16c30b46,title:Repositories,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Projects),gridData:(h:19,i:%27077e496f-d414-4840-a3b0-3bc9da32ddcc%27,w:17,x:31,y:59),id:%2770e5e750-1ab5-11eb-b81d-a32b9537df14%27,panelIndex:%27077e496f-d414-4840-a3b0-3bc9da32ddcc%27,title:Projects,type:visualization,version:%277.6.2%27)),query:(language:lucene,query:%27*%27),timeRestore:!f,title:Git,viewMode:view)&amp;time=%7B%22from%22:%222020-10-01T07:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222020-12-31T08:00:00.000Z%22%7D" class="external-link" rel="nofollow">Aries Activity Dashboard</a> for
the last quarter of 2020, Aries codebases had 708 commits in 506 PRs
from 44 contributors.

Community participation is extremely active in rocketchat channels,
community calls, and repo PR reviews and issues. Email lists are less
frequently used.

Coordination with the DIF DIDComm working group is healthy, with regular
reports being shared.

Project work in main repos is healthy and active.

# Current Plans

-   Aries Interop Profile (AIP) 1.0 was accepted by the community in
January 2020 and has been successful in enabling multiple Aries
deployments to interoperate – especially ACA-Py (enterprise) and AFD
(enterprise and mobile) deployments.
-   AIP 2.0 is in draft at the Aries Working Group and is expected to be
completed in January 2021. AFGo skipped past AIP 1.0 and it is
expected that with AIP 2.0 we will achieve interoperability across
all major frameworks, which is great for the entire community.
-   Work is now active to extend Aries beyond support just Indy ledgers
and Indy AnonCred verifiable credentials to supporting other ledgers
and other verifiable credential formats – most notably BBS+
signatures, supporting ZKPs and selective disclosure.
-   AFGo chose not to use Indy as the underlying ledger or
verifiable credential model (although contributors have added
that), so the other frameworks so the Aries protocols have
implementations that other frameworks can follow.

# Maintainer Diversity

Aries is a multi-codebase effort, and each codebase has its own set of
maintainers. The diversity of maintainers closely matches contributors,
with notes below.  Cross framework collaboration is increasing. For
example, work is happening on interop testing capabilities across the
Python, Go, .NET and JavaScript frameworks.

As interest in verifiable credentials has increased with COVID-19 use
cases (proof of testing, proof of immunization and mobile medical
workforces), interest and attendance has increased, as have deployments
of Aries-based implementations.

# Contributor Diversity

We have not tracked meeting attendance, RFC contributions, and code
contributions in a way that makes it easy to quantify contributor
diversity. Here are a few indicators of our current diversity:

-   We hold two community calls: Weekly at Noon Pacific to cover US and
Pacific contributors, and every two weeks at 7am Pacific to cover US
and European contributors.
-   Call attendance for each call is typically in the 15-20 range.
-   Most organizations have only one attendee; it is rare for more than
3 to attend from the same organization.
-   Cross codebase interoperability efforts indicate cross-organization
cooperation.

# Additional Information

Please note the questions to the TSC raised at the top of the document.

# Reviewed by
-   ✅ <a href="https://wiki.hyperledger.org/display/~angelo.decaro" class="confluence-userlink user-mention" data-username="angelo.decaro" data-linked-resource-id="16327529" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Angelo De Caro</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~lehors" class="confluence-userlink user-mention" data-username="lehors" data-linked-resource-id="2394240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arnaud J Le Hors</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~arsulegai" class="confluence-userlink user-mention" data-username="arsulegai" data-linked-resource-id="6427759" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Arun S M</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~baohua" class="confluence-userlink user-mention" data-username="baohua" data-linked-resource-id="2393082" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Baohua Yang</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~Bobbijn" class="confluence-userlink user-mention" data-username="Bobbijn" data-linked-resource-id="2393198" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Bobbi Muscara</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mastersingh24" class="confluence-userlink user-mention" data-username="mastersingh24" data-linked-resource-id="16321659" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Gari Singh</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~8a9ebdad74c3ca030175df13fdb500d7" class="confluence-userlink user-mention" data-username="8a9ebdad74c3ca030175df13fdb500d7" data-linked-resource-id="62239223" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">user-74455</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~hartm" class="confluence-userlink user-mention" data-username="hartm" data-linked-resource-id="6422922" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Hart Montgomery</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mwagner" class="confluence-userlink user-mention" data-username="mwagner" data-linked-resource-id="5505170" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Mark Wagner</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~mtng" class="confluence-userlink user-mention" data-username="mtng" data-linked-resource-id="24779370" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Maria Teresa Nieto</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~tracy" class="confluence-userlink user-mention" data-username="tracy" data-linked-resource-id="2392240" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a>
-   ✅ <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>



## Comments:

<table data-border="0" width="100%">
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><span id="comment-41590473"></span>
<p><a href="https://wiki.hyperledger.org/display/~danielhardman" class="confluence-userlink user-mention" data-username="danielhardman" data-linked-resource-id="6428885" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Daniel Hardman</a> <a href="https://wiki.hyperledger.org/display/~TelegramSam" class="confluence-userlink user-mention" data-username="TelegramSam" data-linked-resource-id="6425292" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Sam Curren</a>   <a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a>   <a href="https://wiki.hyperledger.org/display/~tmarkovski" class="confluence-userlink user-mention" data-username="tmarkovski" data-linked-resource-id="13861106" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tomislav Markovski</a> <a href="https://wiki.hyperledger.org/display/~cywolf" class="confluence-userlink user-mention" data-username="cywolf" data-linked-resource-id="16323400" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Andrew Whitehead</a>  –
anything to add/modify/delete from this report?</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
 Posted by swcurran at Jan 15, 2021 01:18 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41590510"></span>
<p>Nothing to add from me. Wondeful report,  <a href="https://wiki.hyperledger.org/display/~swcurran" class="confluence-userlink user-mention" data-username="swcurran" data-linked-resource-id="5505331" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Stephen Curran</a></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by danielhardman
at Jan 15, 2021 07:03 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41590776"></span>
<p>I think the questions raised are important ones that ought to be
discussed by the TSC and that are relevant to the overall community
beyond Aries. So, I added them as discussion items for our next call: <a href="https://wiki.hyperledger.org/display/TSC/2021+01+21+TSC+Meeting+Record">2021
01 21 TSC Meeting Record</a> .</p>
<p>Thanks.</p>
<p><br />
</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by lehors at Jan
20, 2021 15:45 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41590795"></span>
<p>'H <span style="color: rgb(23,43,77);">ow do we declare Aries as
"active" vs. the current "incubation"?' </span></p>
<p><span style="color: rgb(23,43,77);">You should apply for active
status!  My personal opinion is that it seems like you all can more than
meet the criteria with a little bit of work (i.e. the CII badge needs
completion). </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jan
20, 2021 19:29 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41590797"></span>
<p>"Does the TSC have an opinion on whether Hyperledger Aries is the
right, safe location for those protocols?"</p>
<p>Questions about standards are always going to be complicated.  While
the majority opinion has always been that we don't want Hyperledger to
become a standards organization, it seems that de facto standards th"at come out of code have typically been accepted.  I'm guessing that no one
will have problems with what you are doing, but it is something worth
bringing up to the TSC.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by hartm at Jan
20, 2021 19:31 </div ></td>
</tr>
<tr class="even">
<td style="border-top: 1px dashed #666666"><span id="comment-41591724"></span>
<p>Here are my thoughts</p>
<p><span style="color: rgb(23,43,77);">Re: "A newcomer arriving at Hyperledger knowing about Indy and Aries might see the "incubation" status and shy away, even though <span>  </span>Aries <span> </span>builds on Indy and it has numerous production deployments? IMHO,
Aries is production ready, but there has been little discussion about
changing the status, and it's not clear how the Hyperledger definition
should apply to this type of project." </span></p>
<p><span style="color: rgb(23,43,77);">[Arun] Given the significance of
Aries and the adoption, it shall be made clear that there is no actual
tie-up with the Indy. In other words, Aries shall have a spec
repository. This shall serve as an entry point for somebody wanting to
begin their journey. Aries agent implementations (ACA-Py/Go/.Net etc)
can be spawned from here. </span></p>
<p><span style="color: rgb(23,43,77);">Re: " </span>A second question
relates to the fact that a core element of Aries is the protocols
defined in the <span>  </span> <a href="https://github.com/hyperledger/aries-rfcs" class="external-link" rel="nofollow" style="text-decoration: none;">Aries RFCs</a> <span> </span>repo. Does the TSC have an opinion on whether Hyperledger Aries
is the right, safe location for those protocols? <span style="color: rgb(23,43,77);">" </span></p>
<p><span style="color: rgb(23,43,77);">[Arun] These define one of the
way to achieve the goal. These define how an Aries agent out of box
behaves. They are not standards. If a standardization entity likes this
model, they could potential define one. </span></p>
<p><span style="color: rgb(23,43,77);">My proposal here is also to bring
up a specification repository, this does not necessarily mean a standard
definition. The specification repository serves as a main repository for
the Aries. As long as at least one agent implementation follows the
spec, Aries can be considered as an active project. Rest of the
documentation is left to the Aries community, i.e. for instance the
Aries community can define availability of agents in Go/.Net etc through
a table in README file in the spec repository. </span></p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Jan 31, 2021 08:49 </div ></td>
</tr>
<tr class="odd">
<td style="border-top: 1px dashed #666666"><span id="comment-41591725"></span>
<p>I understand that Aries has its own RFC repository, that is where the
spec is being tracked. This shall be made easily accessible. I am happy
to work with the community &amp;  <a href="https://wiki.hyperledger.org/display/~davidwboswell" class="confluence-userlink user-mention" data-username="davidwboswell" data-linked-resource-id="2392933" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Boswell</a> to define
a process/reuse the RFC as a specification repository or even setup a
website to serve these over there.</p>
<div class="smallfont" data-align="left" style="color: #666666; width: 98%; margin-bottom: 10px;">
Posted by arsulegai at Jan 31, 2021 08:50 </div ></td>
</tr>
</tbody>
</table>




