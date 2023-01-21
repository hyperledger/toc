---
layout: default
title: 2019 Q1 Hyperledger Iroha
parent: 2019
grand_parent: Project Updates
has_children: false
has_toc: false
---

# 2019 Q1 Hyperledger Iroha

Created by Nikolay Yushkevich, last modified on Jan 23, 2019

<span style="letter-spacing: 0.0px;font-size: 24.0px;">Project </span>

Hyperledger Iroha 
<a href="https://github.com/hyperledger/iroha" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha</a>

# Project Health

We released a couple of Release Candidate releases since the last
report. New features and improvements:

-   New component for YAC: BFT Ordering Service
-   Resistance to replay attacks
-   Stability improvements and error handling

In addition, several client libraries were updated: Javascript, Java,
Swift/Objective-C, Python. There was a contribution to Kubernetes-based
deployment and Ansible scripts. Also, iroha-testcontainers library was
contributed to Hyperledger for fast deployment of local peer network in
Java code for experimenting and testing purposes. 

Our chats are integrated now with the help of Nakayoshi bot 
<a href="https://github.com/soramitsu/nakayoshi" class="external-link" rel="nofollow">https://github.com/soramitsu/nakayoshi</a>  and soon we
are going to contribute to Hyperledger a bot capable of forwarding
GitHub issues to JIRA bugs/issues, written in Rust: 
<a href="https://github.com/soramitsu/yozhik" class="external-link" rel="nofollow">https://github.com/soramitsu/yozhik</a> .

In general, we would like to start a formal process of requesting TSC
for the release approval after we resolve some of the pending issues: 

# Issues

1.  Code contributions are not diverse enough. As the part of our
release plan, we are composing a contributors diversity plan in
order to present TSC a set of actions in order to strengthen the
involvement of outside contributors. 
2.  Also, we need to ensure that all of our code is licensed under the
Apache-2.0 license.
3.  Prior to requesting TSC or releasing the version of Hyperledger
Iroha 1.0 final, we will need to modify the history of commits and
fix DCO non-conformances.

# Releases

-   10 Jan 2019 
<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0_rc2" class="external-link" rel="nofollow">Hyperledger Iroha v1.0 Release
Candidate 2</a>
-   12 Dec 2018 
<a href="https://github.com/hyperledger/iroha/releases/tag/1.0.0_rc1" class="external-link" rel="nofollow">Hyperledger Iroha v1.0 Release
Candidate 1</a>

# Overall Activity in the Past Quarter

-   Met David Huseby in Innopolis, Russia for the purpose of process and
security audit
-   <span style="letter-spacing: 0.0px;">Improved involvement of
maintainers in Rocket.Chat and mailing list </span>
-   <span style="letter-spacing: 0.0px;">Transferred issue management to</span> <a href="http://jira.hyperledger.org" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">jira.hyperledger.org</a>
<span style="letter-spacing: 0.0px;"> and initiated process of
project design/process documentation transfer to </span>
<a href="http://wiki2.hyperledger.org" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">wiki2.hyperledger.org</a>
-   <span style="letter-spacing: 0.0px;">Started design discussions over
mailing lists and community meeting </span>
-   <span style="letter-spacing: 0.0px;">Reached sufficient test
coverage ( **78.1%**   <span style="color: rgb(40,79,168);">2018-12-05 17:11:35  </span>
<a href="https://out-8410xxpdz.now.sh" class="external-link" rel="nofollow">https://out-8410xxpdz.now.sh</a> ) </span>
-   <span style="letter-spacing: 0.0px;">We have updated the CII
certification, which can be viewed here  </span>
<a href="https://bestpractices.coreinfrastructure.org/ru/projects/960" class="external-link" rel="nofollow" style="letter-spacing: 0.0px;">https://bestpractices.coreinfrastructure.org/ru/projects/960</a>

# Current Plans

1.  Continue the development of contributors' diversity plan. 
2.  Ship remaining technical improvements. 
3.  Finish the activities, required in the quality gate for 1.0 final
release:  <a href="https://soramitsucoltd.aha.io/published/e9bce93777c2c4b2448e4e6e78e90b4f?page=1" class="external-link" rel="nofollow">https://soramitsucoltd.aha.io/published/e9bce93777c2c4b2448e4e6e78e90b4f</a>
4.  Request TSC to move to v1.0.
5.  Execute the diversity plan and provide support for v1.0 with the
help of maintainers and contributors.
6.  Release next version of Iroha with a customizable API.

# Maintainer Diversity

Number of active code maintainers: 12 (all currently represented by Soramitsu)

# Contributor Diversity

Coming closer to production version we see more and more activity in
chats. People come interested in Iroha's simplicity and client libraries
— we receive lots of feedback and feature requests that help us make a
plan for Iroha development. Based on that we can tell that Iroha has
many ways of development. Still, lack of production-ready version might
be an obstacle for some projects and we hope to gain more users after we
release v1.0. 

We receive around 10 messages a day from people using Iroha in their
projects and it is exciting to discuss the experience with them to see a
greater picture. At the moment there are several users/ use case
contributors that provided us with evaluation of Iroha for future
release and we continue to receive feedback. 

Currently, many issues in Jira are based on issue reports from outside
contributors. 



### Documentation and translation

New languages added: Dutch, Chinese (simplified), Spanish, French: 
<a href="https://poeditor.com/join/project/SFpZw7o33o" class="external-link" rel="nofollow">https://poeditor.com/join/project/SFpZw7o33o</a>

41 contributors in total for 2018, 7 contributors were most active since
the last report:

<table class="confluenceTable">
<tbody>
<tr class="header">
<th class="confluenceTh">Nickname</th>
<th class="confluenceTh">Email</th>
<th class="confluenceTh">Language</th>
</tr>

<tr class="odd">
<td class="confluenceTd">Frederik De Breuck</td>
<td class="confluenceTd">frederik.debreuck@ <a href="http://ts.fujitsu.com" class="external-link" rel="nofollow">ts.fujitsu.com</a></td>
<td class="confluenceTd">Dutch</td>
</tr>
<tr class="even">
<td class="confluenceTd">michael</td>
<td class="confluenceTd">tianya0yingzi@ <a href="http://gmail.com" class="external-link" rel="nofollow">gmail.com</a></td>
<td class="confluenceTd">Chinese (simplified)</td>
</tr>
<tr class="odd">
<td class="confluenceTd">Aleksander Fielek</td>
<td class="confluenceTd">aleksander.fielek@ <a href="http://outlook.com" class="external-link" rel="nofollow">outlook.com</a></td>
<td class="confluenceTd">French</td>
</tr>
<tr class="even">
<td class="confluenceTd">Yehua Chen</td>
<td class="confluenceTd">email@ <a href="http://krischen.ca" class="external-link" rel="nofollow">krischen.ca</a></td>
<td class="confluenceTd">Chinese (simplified)</td>
</tr>
<tr class="odd">
<td class="confluenceTd">熊超</td>
<td class="confluenceTd">xchtl@ <a href="http://qq.com" class="external-link" rel="nofollow">qq.com</a></td>
<td class="confluenceTd">Chinese (simplified)</td>
</tr>
<tr class="even">
<td class="confluenceTd">Mikhail</td>
<td class="confluenceTd">boldrev@ <a href="http://soramitsu.co.jp" class="external-link" rel="nofollow">soramitsu.co.jp</a></td>
<td class="confluenceTd">Spanish</td>
</tr>
<tr class="odd">
<td class="confluenceTd">Yang Gao</td>
<td class="confluenceTd">kingjiyang@ <a href="http://gmail.com" class="external-link" rel="nofollow">gmail.com</a></td>
<td class="confluenceTd">Chinese (simplified)</td>
</tr>
</tbody>
</table>

### Code contributions

#### Iroha

Number of active current code contributors since the last report: 7

Total number of code contributors since the last report: 19

Unique domains for the contributors since the last report: 12 (including
Soramitsu domain)

#### Client libraries 

Number of active code contributors: 8

New: since the last report 
<a href="https://github.com/hyperledger/iroha-java" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha-java</a>  has been
released to Hyperledger (from 
<a href="https://github.com/Warchant/iroha-pure-java" class="external-link" rel="nofollow">https://github.com/Warchant/iroha-pure-java</a> ) and 
<a href="https://github.com/hyperledger/iroha-testcontainers" class="external-link" rel="nofollow">https://github.com/hyperledger/iroha-testcontainers</a>
 (from  <a href="https://github.com/Warchant/testcontainers-iroha" class="external-link" rel="nofollow">https://github.com/Warchant/testcontainers-iroha</a> )

# Additional Information

It was a pleasure to meet the vast majority of TSC members in
Hyperledger Global Forum and discuss current issues. The topmost setback
was the diversity of community, which we are going to address in our
plan, along with TSC request for the release.




