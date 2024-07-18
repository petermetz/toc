---
layout: default
title: 2024 Q3 Hyperledger Cacti
parent: 2024
grand_parent: Project Updates
---


# Project Health

- The project is in good health!
- Multiple mentorship projects are underway.
- `v2.0.0-rc.2` was released a couple weeks ago and `v2.0.0-rc.3` is not far behind (hopefully next week)!
- Major efforts are underway to integrate the codebase further and we also continue the interoperability protocol 
standardization by implementing the candidate IETF SATP specification using different combinations of Cacti modules.

LFX Insights (Beta) Link:
https://insights.lfx.linuxfoundation.org/foundation/hyp/overview/github?project=cacti&routedFrom=Github&bestPractice=false

# Questions/Issues for the TOC

No questions for the TOC.

# Releases

- v2.0.0-rc.2 - issued
- v2.0.0-rc.3 - upcoming

# Overall Activity in the Past Quarter

- Most of our activity comes from the Discord channel. The daily pair programming calls are well
attended by mentees, existing contributors and would-be contributors alike.
- Questions are answered in a mostly timely fashion though it's not perfect we do make a conscious effort to respond quickly.
- The CI performance optimizations are still on-going, but we are close to having a solution to dynamic diff analysis
which makes it so that our CI jobs only run tests of a package that had changes in itself or its dependency tree of packages.
- We now have more than 60 packages in the monorepo total.
- The release automation that published packages to npmjs.com and ghcr.io has been fixed, we no longer have to manually run publishing scripts.
- New features are being worked on as we speak. Most of the development here focuses on IETF-SATP


# Current Plans

1. Work is being done on a Cacti example that combines the Harmonia Lab smart contracts and the Cacti Corda JVM connector plugin together. Once this is ready, we hope to show it off to the Harmonia Lab maintainers and seek further partnership and collaboration between the two groups.
2. Cactus & Weaver Integration - we work on this ourselves and also have a mentorship project underway for the same.
3. Documentation revamp and updating process
4. There are dozens of branches with build process improvements and test stability fixes (we have flaky tests that are 
too resource intensive for the free tier GitHub runners but we can't move to the paid tier due to our CI taking 8 to 10 hours of compute time to run)

# Maintainer Diversity

We have 8 active maintainers from 4 different organizations total:

- Izuru Sato 
- Michal Bajer 
- Peter Somogyvari 
- Takuma TAKEUCHI 
- Jagpreet Singh Sasan 
- Venkatraman Ramakrishna 
- Sandeep Nishad 
- Rafael Belchior 

# Contributor Diversity

Source: https://insights.lfx.linuxfoundation.org/foundation/hyp/reports/organizations?project=cacti&routedFrom=Github&bestPractice=false

|name                                       |Active Days|Activities count|Activities percent|
|-------------------------------------------|-----------|----------------|------------------|
|Accenture Global Solutions Limited         |277        |3.45K           |64.08%            |
|Ework Group                                |162        |821             |15.21%            |
|International Business Machines Corporation|101        |434             |8.04%             |
|Fujitsu Limited                            |90         |233             |4.32%             |
|Blockdaemon                                |63         |269             |4.99%             |
|INESC-ID                                   |34         |62              |1.15%             |
|ZAUBAR                                     |14         |52              |0.96%             |
|Hex Trust                                  |13         |20              |0.37%             |
|Blazpay                                    |13         |18              |0.33%             |
|Hyperledger                                |11         |49              |0.91%             |
|Cheesecake Labs                            |9          |19              |0.35%             |
|Reliance Jio Infocomm Limited              |8          |15              |0.28%             |
|Infosys Limited                            |7          |8               |0.15%             |
|TUBITAK UEKAE                              |4          |7               |0.13%             |
|Foogle Tech Software                       |3          |5               |0.09%             |
|SAITM22                                    |3          |4               |0.07%             |
|Samsung Electronics Co. Ltd.               |2          |4               |0.07%             |
|SeeWise.AI                                 |2          |2               |0.04%             |
|Rapid Innovation                           |2          |2               |0.04%             |
|GitHub                                     |1          |2               |0.04%             |
|Signify Holding                            |1          |1               |0.02%             |
|Individual - No Account                    |1          |1               |0.02%             |
|Bank of New York Mellon                    |1          |1               |0.02%             |
|Texas A And M University                   |1          |1               |0.02%             |
|Zeeve Inc                                  |1          |1               |0.02%             |



# Additional Information

