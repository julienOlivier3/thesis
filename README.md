# Essays on the Application of Statistical Learning in Empirical Economic Research

This is my PhD thesis, conducted between 2020 and 2022, at the Chair of Statistics and Econometrics at the Justus Liebig University Giessen (JLU). At
the time of writing, I was employed as researcher at ZEW - Leibniz Centre for European Economic Research in the department of Economics of Innovation and
Industrial Dynamics.

## Contents

Chapter 1 gives an introduction to the rise of statistical learning methods in economic research. Inspired by the significant advances of these methods in recent years and their potential to open new avenues in economic research, this dissertation contributes in the form of three papers that use statistical learning methods to answer open research questions about the behavior of firms and economic policymakers under dynamic market conditions. Chapter 1 briefly introduces these research articles and provides a brief discussion on how statistical learning was used to answer the papers’ scope of research.

Chapter 2 consists of two articles whose common linkage is the dynamics triggered by the unprecedented economic shock of COVID-19. Statistical learning methods were used to guide policymakers in their response measures and to evaluate the effect of policy interventions on firm closure dynamics. The second article in Chapter 2 already foreshadows the following work in Chapter 3, as the methodological focus is on the analysis of textual data and its application as a policy tool. The third paper presented in Chapter 3 introduces a novel text modeling approach to map technologies to business models, opening up a new possibility to evaluate technology profiles of market entrants.

Article 1 (Chapter 2) empirically analyzes whether government support for ailing firms in the wake of the first COVID-19 induced lockdown led to a backlog of
corporate insolvencies and, should this be the case, whether this backlog is disproportionally characterized by firms that were already in distress before COVID-19 hit.

This might hint at the unwanted side-effect of interfering with Schumpeter’s natural market cleansing dynamics. For the estimation strategy, the paper makes use of a matching approach that builds on the $k$ Nearest Neighbor ($k$-NN) algorithm. This method of supervised learning allows for a comparison of companies with similar characteristics that have experienced almost the same updates to their credit ratings under different policy regimes, i.e., before and after the pandemic outbreak. 

Article 2 (Chapter 2) proposes a data framework that allows to assess the impact of an unforeseen economic shock at firm level and at near real-time. It shows that different sources of impact data can be integrated into a policy tool to overcome information deficits that policymakers typically face in highly dynamic situations such as at the beginning of the COVID-19 pandemic. Moreover, the framework shows that businesses’ communication patterns concerning the pandemic serve to forecast deterioration in their financial standing over the course of the crisis.

In Article 3 (Chapter 3), I develop an approach to map technologies to business models based on a topic model architecture and text embedding models. In the paper,
I show how patent texts and business descriptions can be transferred in a common vector space to measure companies’ technological orientation. The theoretical
contribution of the paper is concerned with the role of market entrants in the diffusion and development of environmentally sound technologies. 

Chapter 4 concludes and suggests avenues for further research that could benefit from the work presented in this thesis.

## Code

Detail code files can be found in the following paper-specific repositories:
* [Small Firms and the COVID-19 Insolvency Gap](https://github.com/julienOlivier3/insolvencygap)
* [An integrated data framework for policy guidance during the coronavirus pandemic: Towards real-time decision support for economic policymakers](https://github.com/julienOlivier3/DataFramework_EconomicCrises)
* [Mapping Technologies to Business Models: An Application to Clean Technologies and Entrepreneurship](https://github.com/julienOlivier3/cleantech)
