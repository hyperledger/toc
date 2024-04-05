---
layout: default
title: 2024 Annual Review Hyperledger Besu
parent: 2024
grand_parent: Project Updates
---

# Project Health
[LFX Insights for Besu](https://insights.lfx.linuxfoundation.org/foundation/hyp/overview?project=besu&bestPractice=false). 
The Hyperledger Besu project is quite healthy in terms of overall contributions. We have seen our unique contributor numbers creeping up over the last year and increase by over 200 unique contributors. Active contributor numbers have fluctuated, but the project has added new maintainers and new organizations of note, like Citi and Kaleido. Consensys Software makes up around 87% of the maintainer base, but is committed to the project. Other organizations make up 13% of maintainers/contributors and we hope to see this increase. Overall, the project maintains consistent releases, has multiple committed organizations, and is becoming more and more relevant in Ethereum and Ethereum-like infrastructure. We also saw the founding of the Hyperledger Besu for Financial Services Working Group to further localized goals around finance use-cases with the technology. 

# Maintainer Diversity

[Maintainers File.](https://github.com/hyperledger/besu/blob/main/MAINTAINERS.md) Consensys Software makes up around 87% of the maintainer base, but is committed to the project. Maintainer diversity increased this year by adding Kaleido as a contributing organization, alongside contributions from Web3Labs. Swirlds Labs also has new contributors moving toward maintainer status in 2024. We are committed to increasing the diversity on this list by encouraging more development on the private network code-base by those using the technology. Existing maintainers have given special attention to new pull requests and are very timely in moving those forward. 


# Project Adoption	

The Besu project has been adopted by Linea, a layer 2 network developed by Consensys. It is now powering the sequencer that is used to produce blocks and advance the network as critical infrastructure. Citi Bank has also joined the Hyperledger Foundation as a member organization using Hyperledger Besu. Several new institutional staking providers have adopted Besu in their tech stacks to support Ethereum client diversity on Mainnet. Besu sits in 3rd place alongside four other execution clients. It is also being forked for use in other layer 2 networks. 

# Goals

## Performance Against Prior Goals
The Besu maintainers successfully delivered the Cancun hard fork on Ethereum Mainnet and are looking forward to scoping the Prague fork. The Besu project has struggled to court sets of new maintainers from organizations building both public and private networks, but we are hopeful the new financial services working group may yield new interest and contributions. We have made some progress on standardizing features across both network types, like shipping snap-sync as a server. This means that, shortly, private networks and Mainnet can use the same sync methodology (and we may remove fast-sync). We are still working on Bonsai Archive and other feature consolidation efforts. 

The enterprise and public roadmaps were both delivered on the [wiki.](https://wiki.hyperledger.org/pages/viewpage.action?pageId=24781786). We are hopping this will help with adoption, clarity among developers and orgs using Besu, and will keep up the transparency efforts by Maintainers. 


## Next Year's Goals

This year the Maintainers are seeking to continue feature consolidation efforts as well as a testing overhaul to advance the quality of the code-base. This will also incorporate modularity efforts that were punted from last years roadmap. 

Modularity and feature consolidation efforts seek to increase code-base quality and encourage contributions by alleviating confusing and obfuscated code-paths for the various use-cases. [New testing efforts seek](https://wiki.hyperledger.org/display/BESU/Testing+Taskforce+Brainstorming) to keep the this code-base quality high, as there have been several release interventions over the last year due to late-introduced bugs that the team wants to desperately avoid to keep velocity high. There are also more upstream users of Besu that will be impacted than ever before (see above).

This year there is also a renewed push around revitalizing and modernizing the plug-in API. This includes efforts by the Consensys Documentation team and developers to revitalize the docs and add tutorials, templates, and much more information with the goal of encouraging the use of the API. As this API was used to build the Linea project's key components, the team hopes to capitalize on these examples to encourage the use of the plug-ins for more novel use-cases like other L2s, private networks, and more creativity that hasn't been given the proper chance quite yet. 

The Consensys team continues to focus its roadmap on performance, stability, modularity, and upcoming protocol changes like the Verkle Trie migration. The Besu Maintainers intend to support the Prague hard fork and take an active role in its delivery. 

## Help Required
None 

# Project Lifecycle Stage Recommendation
This report recommends continuing the graduated status. 
