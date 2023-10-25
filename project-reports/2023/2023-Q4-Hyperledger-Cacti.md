---
layout: default
title: 2023 Q4 Hyperledger Cacti
parent: 2023
grand_parent: Project Updates
---

# Project Health

- The project is in great shape! We have just made it out of `Incubation` into `Graduated`!
- There is a workshop coming up on the November of 16th in the year 2023 which we 
are planning on co-hosting with some R3 folks from the Harmonia Lab project.

# Questions/Issues for the TOC

Just a random one (from Peter): Do we promote/raise awareness of `Hacktoberfest`
among the Hyperledger maintainers at all?
It's something that the Cacti maintainers have been doing for years and it's 
always a great source of some (mostly drive-by) contributions!

# Releases

We've come out with `v2.0.0-alpha.2` which features numerous big-fixes and
some breaking changes (since we are in the final stretch for `v2.0.0` we've started
adding breaking changes to the `main` branch.

# Overall Activity in the Past Quarter

- We've started planning the workshop in November.
- We've reduced the backlog of open PRs from 50 on average to 20 on average which is great for everyone (contributions go through faster and reviews are less tedious due to not as frequent merge conflicts as well.)
- We've graduated!
- Major refactor of the documentation (special thanks to Rama for this!)
- Simplified the `cmd-api-server` configuration (these were breaking changes so we had to wait until the finish line of the `v2.0.0` release to make them.)

# Current Plans

- We are hard at work on making the `v2.0.0` release happen.
- Plans to support artifact signing through CoSign ASAP.
- Plans to adapt the new security policy (the template that the TOC approved recently.)
- Very hopeful that the v2.0.0 release will happen in the next few weeks (same thing we estimated a few weeks ago... :-) .)


# Maintainer Diversity

No new maintainers. We have 3 organizations maintaining the project: Fujitsu, IBM, Accenture.

# Contributor Diversity

- We've had 11 new contributors this quarter according to LFX!
- There were 7 organizations contributing in the past quarter, the table is pasted below. Source: [LFX Hyperledger Cacti](https://insights.lfx.linuxfoundation.org/projects/hyperledger%2Fcactus/dashboard;subTab=technical;v=source-control%2Fcommits%2Foverview?filter=%23%2Fdashboard%2FGit%3Fembed%3Dtrue%26_g%3D(filters:!(),refreshInterval:(pause:!t,value:0),time:(from:%27now-90d%27,to:%27now%27))%26_a%3D(description:%27Git%2520Overview%2520panel%27,filters:!((%27$state%27:(store:appState),meta:(alias:%27Empty%2520Commits%27,disabled:!f,index:git,key:files,negate:!t,params:(query:%270%27),type:phrase),query:(match:(files:(query:%270%27,type:phrase)))),(%27$state%27:(store:appState),meta:(alias:Bots,disabled:!f,index:git,key:author_bot,negate:!t,params:(query:!t),type:phrase),query:(match:(author_bot:(query:!t,type:phrase)))),(%27$state%27:(store:appState),meta:(alias:%27Is%2520Commit%27,disabled:!f,index:git,key:type,negate:!f,params:(query:commit),type:phrase),query:(match_phrase:(type:commit)))),fullScreenMode:!f,options:(darkTheme:!f,useMargins:!t),panels:!((embeddableConfig:(title:%27Commits%2520Percentage%2520By%2520Organization%27),gridData:(h:13,i:%271%27,w:13,x:22,y:0),id:git_commits_organizations,panelIndex:%271%27,title:%27Commits%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Filter),gridData:(h:16,i:%27788f235e-6d11-451b-ba12-50e7b8765e0f%27,w:13,x:0,y:0),id:%27985c11c0-a449-11ea-bb19-4b3cb1a7236f%27,panelIndex:%27788f235e-6d11-451b-ba12-50e7b8765e0f%27,title:Filter,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Summary),gridData:(h:11,i:d65f6177-a704-4194-861d-019efd71a00f,w:9,x:13,y:0),id:%2713de3220-1aaf-11eb-b81d-a32b9537df14%27,panelIndex:d65f6177-a704-4194-861d-019efd71a00f,title:Summary,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Lines%2520Changed%2520Percentage%2520By%2520Organization%27),gridData:(h:13,i:a8bec484-b99e-4cdc-96f2-722907cf4d00,w:13,x:35,y:0),id:e70ac370-b6f0-11ea-83d0-e156a256d6e6,panelIndex:a8bec484-b99e-4cdc-96f2-722907cf4d00,title:%27Lines%2520Changed%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Summary%27),gridData:(h:5,i:%270ba87e3a-a35b-4a3a-95bc-7572c0ecb90e%27,w:9,x:13,y:11),id:%2791b28510-ae4e-11eb-b42d-29bb7e46b0a1%27,panelIndex:%270ba87e3a-a35b-4a3a-95bc-7572c0ecb90e%27,title:%27About%2520Summary%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%2520Percentage%2520By%2520Organization%27),gridData:(h:3,i:%276680773a-5280-430b-9c7d-d03bca19518e%27,w:13,x:22,y:13),id:%279fdfe060-ae53-11eb-b42d-29bb7e46b0a1%27,panelIndex:%276680773a-5280-430b-9c7d-d03bca19518e%27,title:%27About%2520Commits%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Lines%2520Changed%2520Percentage%2520By%2520Organization%27),gridData:(h:3,i:b7cbfd88-6612-4a08-bd6c-c5430265494d,w:13,x:35,y:13),id:%27193917b0-ae54-11eb-b42d-29bb7e46b0a1%27,panelIndex:b7cbfd88-6612-4a08-bd6c-c5430265494d,title:%27About%2520Lines%2520Changed%2520Percentage%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Active%2520Contributors%2520and%2520Organizations%27),gridData:(h:13,i:bdcfb437-9e3d-4418-94ce-5fa4a6362b78,w:23,x:0,y:16),id:%279d649f50-a0ee-11eb-9005-3930817a030d%27,panelIndex:bdcfb437-9e3d-4418-94ce-5fa4a6362b78,title:%27Active%2520Contributors%2520and%2520Organizations%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Commits),gridData:(h:13,i:%279167a0f4-2452-434f-b63a-2f4800b7fd30%27,w:25,x:23,y:16),id:%27572c48c0-a0ef-11eb-9005-3930817a030d%27,panelIndex:%279167a0f4-2452-434f-b63a-2f4800b7fd30%27,title:Commits,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Active%2520Contributors%2520and%2520Organizations%27),gridData:(h:3,i:%27223e1016-00a3-430d-841f-9f42b8032606%27,w:23,x:0,y:29),id:%27905a6060-ae54-11eb-b42d-29bb7e46b0a1%27,panelIndex:%27223e1016-00a3-430d-841f-9f42b8032606%27,title:%27About%2520Active%2520Contributors%2520and%2520Organizations%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%27),gridData:(h:3,i:dab778dc-7ac0-48fb-a178-f6333fabc1dd,w:25,x:23,y:29),id:ef34e880-ae54-11eb-b42d-29bb7e46b0a1,panelIndex:dab778dc-7ac0-48fb-a178-f6333fabc1dd,title:%27About%2520Commits%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Commits%2520By%2520Organization%27),gridData:(h:13,i:%273278fa75-0a7b-492b-9b8a-b866b45b3dc1%27,w:23,x:0,y:32),id:e2bb7d40-a0f2-11eb-94e8-4323c8335d1a,panelIndex:%273278fa75-0a7b-492b-9b8a-b866b45b3dc1%27,title:%27Commits%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27),gridData:(h:13,i:%2756561788-a72f-45b6-942d-b5b01a209d45%27,w:25,x:23,y:32),id:a78a02c0-a0fa-11eb-94e8-4323c8335d1a,panelIndex:%2756561788-a72f-45b6-942d-b5b01a209d45%27,title:%27Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%2520By%2520Organization%27),gridData:(h:3,i:%279b8b0c22-36c1-4d8f-86dd-841dfef2c6b1%27,w:23,x:0,y:45),id:%278e421240-ae55-11eb-b42d-29bb7e46b0a1%27,panelIndex:%279b8b0c22-36c1-4d8f-86dd-841dfef2c6b1%27,title:%27About%2520Commits%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27),gridData:(h:3,i:%271c5972b7-e4c0-4fb8-a042-cd6cc9f1fd94%27,w:25,x:23,y:45),id:%2751418140-ae56-11eb-b42d-29bb7e46b0a1%27,panelIndex:%271c5972b7-e4c0-4fb8-a042-cd6cc9f1fd94%27,title:%27About%2520Lines%2520Of%2520Code%2520Changed%2520By%2520Organization%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Commits%2520by%2520Time%2520Zone%27),gridData:(h:14,i:%27632c77ff-eb61-40aa-b101-11e75f9f28f7%27,w:23,x:0,y:48),id:%277f4bed90-a0fb-11eb-94e8-4323c8335d1a%27,panelIndex:%27632c77ff-eb61-40aa-b101-11e75f9f28f7%27,title:%27Commits%2520by%2520Time%2520Zone%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Time%2520To%2520Commit%2520(Hrs)%27),gridData:(h:14,i:%274abc0674-24a1-459f-8310-d92c9f58e41e%27,w:25,x:23,y:48),id:ab467ee0-5756-11eb-bbd0-c758192c580e,panelIndex:%274abc0674-24a1-459f-8310-d92c9f58e41e%27,title:%27Time%2520To%2520Commit%2520(Hrs)%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Time%2520To%2520Commit%2520(Hrs)%27),gridData:(h:5,i:%27261503ca-d4cd-4990-a215-f630fdbb3037%27,w:25,x:23,y:62),id:b5fe1aa0-ae5e-11eb-b42d-29bb7e46b0a1,panelIndex:%27261503ca-d4cd-4990-a215-f630fdbb3037%27,title:%27About%2520Time%2520To%2520Commit%2520(Hrs)%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27About%2520Commits%2520by%2520Time%2520Zone%27),gridData:(h:5,i:%27129f247f-b4aa-464c-9112-c4a982f20f21%27,w:23,x:0,y:62),id:%2787e893d0-ae5d-11eb-b42d-29bb7e46b0a1%27,panelIndex:%27129f247f-b4aa-464c-9112-c4a982f20f21%27,title:%27About%2520Commits%2520by%2520Time%2520Zone%27,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Submitters),gridData:(h:19,i:%278cdb35b3-6f32-416f-956b-50f7b221e73e%27,w:21,x:0,y:67),id:%2731f04bd0-1ab0-11eb-b81d-a32b9537df14%27,panelIndex:%278cdb35b3-6f32-416f-956b-50f7b221e73e%27,title:Submitters,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Organizations),gridData:(h:19,i:d4d3ea5e-fedf-4818-bfe4-e6de2ab43a3c,w:27,x:21,y:67),id:ca6b1b90-1ab2-11eb-bbd0-c758192c580e,panelIndex:d4d3ea5e-fedf-4818-bfe4-e6de2ab43a3c,title:Organizations,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Repositories),gridData:(h:19,i:a476e04a-1dde-4bdc-98b6-8c6d16c30b46,w:29,x:0,y:86),id:de3203e0-1ab3-11eb-bbd0-c758192c580e,panelIndex:a476e04a-1dde-4bdc-98b6-8c6d16c30b46,title:Repositories,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:Projects),gridData:(h:19,i:%27077e496f-d414-4840-a3b0-3bc9da32ddcc%27,w:19,x:29,y:86),id:%2770e5e750-1ab5-11eb-b81d-a32b9537df14%27,panelIndex:%27077e496f-d414-4840-a3b0-3bc9da32ddcc%27,title:Projects,type:visualization,version:%277.6.2%27),(embeddableConfig:(title:%27Organization%2520Commits%27),gridData:(h:18,i:c73b96e3-a6ec-4b4a-aa9f-7bd4b158c968,w:48,x:0,y:105),id:%273c6f01b0-f21e-11ea-ada8-692b75e53835%27,panelIndex:c73b96e3-a6ec-4b4a-aa9f-7bd4b158c968,title:%27Organization%2520Commits%27,type:visualization,version:%277.6.2%27)),query:(language:lucene,query:%27*%27),timeRestore:!f,title:Git,viewMode:view)&time=%7B%22from%22:%22now-90d%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D)


|Organization                               |Commits|Document Commits|Submitters|Edited Files|Added Lines|Removed Lines|Projects|Repositories|Avg. Time To Commit (Hrs)|Last Commit Date (GMT)|
|-------------------------------------------|-------|----------------|----------|------------|-----------|-------------|--------|------------|-------------------------|----------------|
|Accenture Global Solutions Limited         |63     |11              |7         |1633        |87668      |665683       |1       |1           |1539.1587301587301       |October 4, 2023 12:06:35 PM   |
|Microsoft Corporation                      |17     |7               |1         |440         |14049      |1065         |1       |1           |95.41176470588235        |October 3, 2023 10:40:35 PM   |
|Unknown                                    |14     |3               |8         |418         |378694     |847          |1       |2           |336                      |October 4, 2023 5:48:49 AM   |
|International Business Machines Corporation|11     |5               |1         |946         |7364       |4023         |1       |1           |126.36363636363636       |September 29, 2023 2:30:53 PM   |
|Fujitsu Limited                            |9      |8               |1         |253         |21162      |7675         |1       |1           |588.1111111111111        |October 4, 2023 2:26:09 PM   |
|Individual - No Account                    |3      |1               |1         |69          |17621      |228          |1       |1           |5029.333333333333        |August 16, 2023 7:22:05 PM   |
|Walmart Inc.                               |3      |0               |1         |11          |111        |22           |1       |1           |0                        |October 3, 2023 7:39:24 PM   |
|University of Lisbon                       |1      |0               |1         |21          |18887      |50425        |1       |1           |435                      |July 24, 2023 2:06:14 AM   |


# Additional Information

N/A
