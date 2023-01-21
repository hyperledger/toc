---
layout: default
title: 2022 Q4 Hyperledger Fabric
parent: 2022
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2022 Q4 Hyperledger Fabric

Created by David Enyeart, last modified by Danno Ferrin on Nov 04, 2022

# Project Health

<span style="color: rgb(23,43,77);">Hyperledger Fabric is fairly mature
and stable with a Long-term support (LTS) release and incremental new
features being added in minor releases. There is less churn and fewer
commits than in years past, with continued focus on quality and support.
New features get proposed, approved, and implemented based on a
community RFC process. Mailing list activity is down a bit compared to
prior years. PRs and mailing list questions are generally turned around
quickly. </span>

# Required Information

1.  <span style="color: rgb(68,68,68);"> <a href="https://wiki.hyperledger.org/display/TSC/Projects+have+two+quarters+to+comply+with+common+repo+structure?focusedCommentId=41591637#comment-41591637" rel="nofollow">Have you switched from master to main in all your
repos</a> </span> <span style="letter-spacing: 0.0px;">? YES </span>
2.  <span class="placeholder-inline-tasks" style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(68,68,68);">
<a href="https://tsc.hyperledger.org/repository-structure.html" class="external-link" rel="nofollow">Have you implemented the Common
Repository Structure in all your repos</a> </span> </span> <span style="color: rgb(23,43,77);text-decoration: none;">? YES </span>
3.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Has your project implemented these
inclusive language changes listed below to your repo? YES </span></span>
1.  master → main
2.  slave → replicas
3.  blacklist → denylist
4.  whitelist → allowlist
4.  <span style="color: rgb(23,43,77);text-decoration: none;"> <span style="color: rgb(23,43,77);">Have you added an <a href="https://wiki.hyperledger.org/display/TSC/Inclusive+Language+Example" rel="nofollow">Inclusive Language Statement</a> to your project's
documentation and/or Wiki pages? YES</span> </span>

# Questions/Issues for the TSC

None.

# Releases

v2.2 is the current LTS releases with patch releases approximately
quarterly.

Releases past quarter:

-   Fabric v2.2.8 - August 8, 2022
-   Fabric v2.4.6 - August 8, 2022

Fabric CA

-   v1.5.5 - July 8, 2022

Upcoming releases:

-   Fabric v2.5.0 - Expected to be next LTS release

# Overall Activity in the Past Quarter

The project delivered fixes to the Fabric v2.2 and v2.4 releases, as
well as Fabric CA v1.5 release.

Work is underway to implement the Purge Private Data History feature,
targeted for v2.5 later this year.

New RFCs under consideration:

-   <a href="https://github.com/hyperledger/fabric-rfcs/pull/52" class="external-link" rel="nofollow">BFT Ordering service</a>  (RFC
3 of 3)
-   <a href="https://github.com/hyperledger/fabric-rfcs/pull/53" class="external-link" rel="nofollow">New capability for updated Identity
Mixer</a>

Related projects

-   <a href="https://github.com/hyperledger-labs/fabric-operator" class="external-link" rel="nofollow">Fabric-operator Hyperledger lab</a>
** ** - IBM continued pushing features from IBM Blockchain Platform
to the open source operator.
-   <a href="https://github.com/hyperledgendary/full-stack-asset-transfer-guide" class="external-link" rel="nofollow">Fabric workshop from Global
Forum</a> **-** Developed a new workshop demonstrates good practices
for app development with gateway SDKs, chaincode-as-a-service for
chaincode debug, and deployment using fabric-operator.

# Current Plans

<span class="blob-code-inner blob-code-marker">The project is working on
a v2.5.0 release in the release-2.5 branch, with a feature to Purge the
history of private data. The feature may help organizations meet GDPR
requirements with the ability to delete private data while preserving a
hash of the data on the blockchain. The v2.5 release is expected around
end of 2022 and is expected to become the next long-term support
release.  </span>

<span class="blob-code-inner blob-code-marker">Fabric v3.0 release
development has started, primarily around refactoring the ordering
service for the upcoming BFT consensus integration. In the v3.0 release
we are considering deprecation and removal of some features that have
historically made deployment difficult, such as docker-in-docker
chaincode building. </span>

The project is investigating creation of ARM based binaries and docker
images, due to the M1 mac (ARM-based) gaining traction in the developer
community.

The project has started to shift CI from Azure Pipelines to Github
Actions across the various Fabric repositories.

More details can be found in the project <a href="https://app.zenhub.com/workspaces/fabric-57c43689b6f3d8060d082cf1/board" class="external-link" rel="nofollow">ZenHub board</a> , this board
provides a current priority view of the Github issues across the various
Fabric repositories.

# Maintainer Diversity

<span style="color: rgb(23,43,77);">6 of 8 maintainers from IBM. </span>

# Contributor Diversity

Year to year comparison, by commit:

-   Q3 2021 - 411 commits. 64% from IBM.
-   Q3 2022 - 305 commits. 73% from IBM.

Year to year comparison, by contributor:

-   Q3 2021 - 68 contributors. 37% from IBM.
-   Q3 2022 - 45 contributors. 36% from IBM.

# Additional Information

<a href="https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Ffabric/dashboard;subTab=technical?time=%7B%22from%22:%222021-07-01T04:00:00.000Z%22,%22type%22:%22absolute%22,%22to%22:%222021-10-01T04:00:00.000Z%22%7D&amp;filter=%23%2Fdashboard%2FGit%3Fembed%3Dtrue%26_g%3D(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:%272021-07-01T04:00:00.000Z%27,to:%272021-10-01T04:00:00.000Z%27))%26_a%3D(description:%27Git%2520Overview%2520panel%27,filters:!((%27$state%27:(store:appState),meta:(alias:%27Empty%2520Commits%27,disabled:!f,index:git,key:files,negate:!t,params:(query:%270%27),type:phrase),query:(match:(files:(query:%270%27,type:phrase)))),(%27$state%27:(store:appState),meta:(alias:Bots,disabled:!f,index:git,key:author_bot,negate:!t,params:(query:!t),type:phrase),query:(match:(author_bot:(query:!t,type:phrase)))),(%27$state%27:(store:appState),meta:(alias:%27Is%2520Commit%27,disabled:!f,index:git,key:type,negate:!f,params:(query:commit),type:phrase),query:(match_phrase:(type:commit))),(%27$state%27:(store:appState),meta:(alias:!n,disabled:!f,index:git,key:author_org_name,negate:!f,params:(query:%27International%2520Business%2520Machines%2520Corporation%27),type:phrase),query:(match_phrase:(author_org_name:%27International%2520Business%2520Machines%2520Corporation%27)))),fullScreenMode:!f,options:(darkTheme:!f,useMargins:!t),panels:!((embeddableConfig:(title:%27Commits%2520Percentage%2520By%2520Organization%27),gridData:(h:13,i:%271%27,w:13,x:22,y:0),id:git_commits_organizations,panelIndex:%271%27,title:%27Commits%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Filter),gridData:(h:16,i:%27788f235e-6d11-451b-ba12-50e7b8765e0f%27,w:13,x:0,y:0),id:%27985c11c0-a449-11ea-bb19-4b3cb1a7236f%27,panelIndex:%27788f235e-6d11-451b-ba12-50e7b8765e0f%27,title:Filter,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Summary),gridData:(h:11,i:d65f6177-a704-4194-861d-019efd71a00f,w:9,x:13,y:0),id:%2713de3220-1aaf-11eb-b81d-a32b9537df14%27,panelIndex:d65f6177-a704-4194-861d-019efd71a00f,title:Summary,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Lines%2520Changed%2520Percentage%2520By%2520Organization%27),gridData:(h:13,i:a8bec484-b99e-4cdc-96f2-722907cf4d00,w:13,x:35,y:0),id:e70ac370-b6f0-11ea-83d0-e156a256d6e6,panelIndex:a8bec484-b99e-4cdc-96f2-722907cf4d00,title:%27Lines%2520Changed%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Summary%27),gridData:(h:5,i:%270ba87e3a-a35b-4a3a-95bc-7572c0ecb90e%27,w:9,x:13,y:11),id:%2791b28510-ae4e-11eb-b42d-29bb7e46b0a1%27,panelIndex:%270ba87e3a-a35b-4a3a-95bc-7572c0ecb90e%27,title:%27About%2520Summary%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%2520Percentage%2520By%2520Organization%27),gridData:(h:3,i:%276680773a-5280-430b-9c7d-d03bca19518e%27,w:13,x:22,y:13),id:%279fdfe060-ae53-11eb-b42d-29bb7e46b0a1%27,panelIndex:%276680773a-5280-430b-9c7d-d03bca19518e%27,title:%27About%2520Commits%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Lines%2520Changed%2520Percentage%2520By%2520Organization%27),gridData:(h:3,i:b7cbfd88-6612-4a08-bd6c-c5430265494d,w:13,x:35,y:13),id:%27193917b0-ae54-11eb-b42d-29bb7e46b0a1%27,panelIndex:b7cbfd88-6612-4a08-bd6c-c5430265494d,title:%27About%2520Lines%2520Changed%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Active%2520Contributors%2520and%2520Organizations%27),gridData:(h:13,i:bdcfb437-9e3d-4418-94ce-5fa4a6362b78,w:23,x:0,y:16),id:%279d649f50-a0ee-11eb-9005-3930817a030d%27,panelIndex:bdcfb437-9e3d-4418-94ce-5fa4a6362b78,title:%27Active%2520Contributors%2520and%2520Organizations%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Commits),gridData:(h:13,i:%279167a0f4-2452-434f-b63a-2f4800b7fd30%27,w:25,x:23,y:16),id:%27572c48c0-a0ef-11eb-9005-3930817a030d%27,panelIndex:%279167a0f4-2452-434f-b63a-2f4800b7fd30%27,title:Commits,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Active%2520Contributors%2520and%2520Organizations%27),gridData:(h:3,i:%27223e1016-00a3-430d-841f-9f42b8032606%27,w:23,x:0,y:29),id:%27905a6060-ae54-11eb-b42d-29bb7e46b0a1%27,panelIndex:%27223e1016-00a3-430d-841f-9f42b8032606%27,title:%27About%2520Active%2520Contributors%2520and%2520Organizations%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%27),gridData:(h:3,i:dab778dc-7ac0-48fb-a178-f6333fabc1dd,w:25,x:23,y:29),id:ef34e880-ae54-11eb-b42d-29bb7e46b0a1,panelIndex:dab778dc-7ac0-48fb-a178-f6333fabc1dd,title:%27About%2520Commits%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Commits%2520By%2520Organization%27),gridData:(h:13,i:%273278fa75-0a7b-492b-9b8a-b866b45b3dc1%27,w:23,x:0,y:32),id:e2bb7d40-a0f2-11eb-94e8-4323c8335d1a,panelIndex:%273278fa75-0a7b-492b-9b8a-b866b45b3dc1%27,title:%27Commits%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27),gridData:(h:13,i:%2756561788-a72f-45b6-942d-b5b01a209d45%27,w:25,x:23,y:32),id:a78a02c0-a0fa-11eb-94e8-4323c8335d1a,panelIndex:%2756561788-a72f-45b6-942d-b5b01a209d45%27,title:%27Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%2520By%2520Organization%27),gridData:(h:3,i:%279b8b0c22-36c1-4d8f-86dd-841dfef2c6b1%27,w:23,x:0,y:45),id:%278e421240-ae55-11eb-b42d-29bb7e46b0a1%27,panelIndex:%279b8b0c22-36c1-4d8f-86dd-841dfef2c6b1%27,title:%27About%2520Commits%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27),gridData:(h:3,i:%271c5972b7-e4c0-4fb8-a042-cd6cc9f1fd94%27,w:25,x:23,y:45),id:%2751418140-ae56-11eb-b42d-29bb7e46b0a1%27,panelIndex:%271c5972b7-e4c0-4fb8-a042-cd6cc9f1fd94%27,title:%27About%2520Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Commits%2520by%2520Time%2520Zone%27),gridData:(h:14,i:%27632c77ff-eb61-40aa-b101-11e75f9f28f7%27,w:23,x:0,y:48),id:%277f4bed90-a0fb-11eb-94e8-4323c8335d1a%27,panelIndex:%27632c77ff-eb61-40aa-b101-11e75f9f28f7%27,title:%27Commits%2520by%2520Time%2520Zone%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Time%2520To%2520Commit%2520(Hrs)%27),gridData:(h:14,i:%274abc0674-24a1-459f-8310-d92c9f58e41e%27,w:25,x:23,y:48),id:ab467ee0-5756-11eb-bbd0-c758192c580e,panelIndex:%274abc0674-24a1-459f-8310-d92c9f58e41e%27,title:%27Time%2520To%2520Commit%2520(Hrs)%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Time%2520To%2520Commit%2520(Hrs)%27),gridData:(h:5,i:%27261503ca-d4cd-4990-a215-f630fdbb3037%27,w:25,x:23,y:62),id:b5fe1aa0-ae5e-11eb-b42d-29bb7e46b0a1,panelIndex:%27261503ca-d4cd-4990-a215-f630fdbb3037%27,title:%27About%2520Time%2520To%2520Commit%2520(Hrs)%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%2520by%2520Time%2520Zone%27),gridData:(h:5,i:%27129f247f-b4aa-464c-9112-c4a982f20f21%27,w:23,x:0,y:62),id:%2787e893d0-ae5d-11eb-b42d-29bb7e46b0a1%27,panelIndex:%27129f247f-b4aa-464c-9112-c4a982f20f21%27,title:%27About%2520Commits%2520by%2520Time%2520Zone%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Submitters),gridData:(h:19,i:%278cdb35b3-6f32-416f-956b-50f7b221e73e%27,w:21,x:0,y:67),id:%2731f04bd0-1ab0-11eb-b81d-a32b9537df14%27,panelIndex:%278cdb35b3-6f32-416f-956b-50f7b221e73e%27,title:Submitters,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Organizations),gridData:(h:19,i:d4d3ea5e-fedf-4818-bfe4-e6de2ab43a3c,w:27,x:21,y:67),id:ca6b1b90-1ab2-11eb-bbd0-c758192c580e,panelIndex:d4d3ea5e-fedf-4818-bfe4-e6de2ab43a3c,title:Organizations,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Repositories),gridData:(h:19,i:a476e04a-1dde-4bdc-98b6-8c6d16c30b46,w:29,x:0,y:86),id:de3203e0-1ab3-11eb-bbd0-c758192c580e,panelIndex:a476e04a-1dde-4bdc-98b6-8c6d16c30b46,title:Repositories,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Projects),gridData:(h:19,i:%27077e496f-d414-4840-a3b0-3bc9da32ddcc%27,w:19,x:29,y:86),id:%2770e5e750-1ab5-11eb-b81d-a32b9537df14%27,panelIndex:%27077e496f-d414-4840-a3b0-3bc9da32ddcc%27,title:Projects,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Organization%2520Commits%27),gridData:(h:18,i:c73b96e3-a6ec-4b4a-aa9f-7bd4b158c968,w:48,x:0,y:105),id:%273c6f01b0-f21e-11ea-ada8-692b75e53835%27,panelIndex:c73b96e3-a6ec-4b4a-aa9f-7bd4b158c968,title:%27Organization%2520Commits%27,type:visualization,version:%277.6.2%27)),query:(language:lucene,query:%27*%27),timeRestore:!f,title:Git,viewMode:view)" class="external-link" rel="nofollow">Insight Dashboards for Q3</a>

# Reviewed By

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
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~shemnon" class="confluence-userlink user-mention" data-username="shemnon" data-linked-resource-id="20022118" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Danno Ferrin</a>  </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~denyeart" class="confluence-userlink user-mention" data-username="denyeart" data-linked-resource-id="2392864" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">David Enyeart</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~grace.hartley" class="confluence-userlink user-mention" data-username="grace.hartley" data-linked-resource-id="16324128" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Grace Hartley</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~jimthematrix" class="confluence-userlink user-mention" data-username="jimthematrix" data-linked-resource-id="58854075" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Jim Zhang</a> </span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~knagware9" class="confluence-userlink user-mention" data-username="knagware9" data-linked-resource-id="2393468" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Kamlesh Nagware</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~nage" class="confluence-userlink user-mention" data-username="nage" data-linked-resource-id="2393038" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Nathan George</a></span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~gl7doqu97svck56tzyjzzhxj" class="confluence-userlink user-mention" data-username="gl7doqu97svck56tzyjzzhxj" data-linked-resource-id="24779271" data-linked-resource-version="1" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Peter Somogyvari</a></span>
-   ✅ <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~tkuhrt" class="confluence-userlink user-mention" data-username="tkuhrt" data-linked-resource-id="1180151" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Tracy Kuhrt</a> </span>
-   🔲 <span class="placeholder-inline-tasks">
<a href="https://wiki.hyperledger.org/display/~troyronda" class="confluence-userlink user-mention" data-username="troyronda" data-linked-resource-id="9110618" data-linked-resource-version="2" data-linked-resource-type="userinfo" data-base-url="https://wiki.hyperledger.org">Troy Ronda</a> </span>

# <span class="placeholder-inline-tasks">Submission date </span>

<span class="placeholder-inline-tasks"> 17-Oct-2022 </span>






