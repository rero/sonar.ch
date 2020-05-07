---
title: "On the color schemes of Open Access"
date: 2020-05-19T08:00:00+02:00
author: "Karsten Schuldt (FH Graubünden)"
draft: false
tags: ["open access", " analytics"]
---

A problem one encounters with Open Access (OA) is the wide range of understandings of different OA types and classifications. What started as a classification of two "colors" (gold and green, see Harnad et al. 2008[^2]) has evolved into a plethora of possible classifications. Right at the outset of the OA movement the SHERPA/RoMEO-project (2002-2006) proposed an enhanced four color scheme (green, blue, yellow, white; see Jenkis et al. 2007[^3]). Since then, the number of colors meaning different classifications of OA, have grown rapidly. E.g. one LiBGuide of the De Paul-University, Chicago, now lists seven types of OA (green, blue, yellow, gold, white, black and hybrid; see Lucic (n.d.)[^4]). Taubert et al. (2019: 3[^6]; further discussion see below) count 14 different colors used in different studies on OA.

<!--more-->

There are always good reasons to enhance, expand or rebuilt OA classifications. But at the same time, these constant changes create new problems as well. Van Leeuwen et al. (2017[^7]) discuss those problems for the research and analysis of OA when combining different data sources. They introduce a method to label OA publications automatically, but note limitations of this method as well. Merging data from resources with different color schemes, or just comparing them, always imposes decisions on which color schemes to follow. This holds true for repositories like SONAR, which harvest other repositories, as well as for every form of OA analysis. As is so often the case with classifications, there seems to be no perfect single one for all use cases. As a rule of thumb, the classification which suits the data model of one specific repository or which contributes the most to the concrete questions of a specific analysis should be chosen.

Today, most of the analyses of OA use the color scheme of the unpaywall-project (gold, green, hybrid, bronze, closed; introduced in Piwowar et al. 2018[^5]), because most analyses use the data sets of unpaywall. (E.g. the [German OA-monitor](https://open-access-monitor.de/#/open-access)) For now, this scheme seems to have the upper-hand, but is far from perfect. In this blog post, I summarize the discussions of two recent proposals, both published just last year, which both give arguments for a more granular classification of OA. The fact that there are two different proposals only shows that the discussion about all the different colors of OA is far from over.

### An Austrian proposal

Danowski (2019)[^1] states that the murky definitions of the colors of OA become a problem when one starts to monitor OA, which the author does in his organization (Institute of Science and Technology Austria) and in the ["Austrian Transition to Open Access" project (AT2OA)](https://at2oa.at/en/home.html). He states that for the questions raised in the monitoring for the AT2OA project, specific criteria are necessary, naming (a) place of OA, (2) licence, (3) publication version, (4) embargo period, and (5) conditions of OA. Those are not covered by the different color schemes in use.

Instead, he – for the working group in AT2OA – proposes another classification, called tuples, where all of the five criteria are coded with the numbers 1-4 (e.g. the criteria "license": 1 – open license like CC BY, 2 – free license, 3 – proprietary license, 4 – no license or license unknown). Therefore, the OA status of every document should by describable in a string of five numbers. In his article he provides some helpful mapping of other OA definitions to his own (Danowski 2019: 63[^1]). His proposal is driven by the practical necessities of OA monitoring in Austria.

### A German proposal

A working group at the university libraries in Bielefeld and Göttingen presented another critique and proposal for different classification. (Taubert et al. 2019[^6]) The group argues that the definition of OA is loaded with political and "non-normative" meanings, which makes the different definitions, classifications and color schemes unusable for bibliometrics and other scientific studies.

> "OA does not only refer to a publication practice but also implies that free digital access to research results is an objective worth pursuing. The term has thus developed a normative tongue, and the search for a precise definition has become a battlefield between OA proponents, publishers and other stakeholders that each try to push a specific understanding, sometimes also linked to a business model." (Taubert et al. 2019: 1[^6])

Therefore, they present another definition, which they call "non-normative", that should be used in scientific inquiries. After discussing the different arguments and ideas which inform definitions of OA they propose an own classification which, as they argue, is based solely on objective data points (Taubert et al. 2019: 12[^6]), including sources of those data. Their discussion and definition are driven by concerns for objectivity necessary for scientific inquiries.

### Pragmatic solutions, further discussions

Projects in the OA field like SONAR have to make decisions on the classification of OA which they will use. OA obviously means different things and as such, OA publications have to be classified to handle and analyze them. As mentioned above, this started early on. Even such groundbreaking early projects like SHERPA/RoMEO provided such an enhanced classification.

Most of those decisions are pragmatic solutions, using already established color schemes like the one introduced by the unpaywall project. But at same time, those color schemes seem not enough for all use cases and not specific enough for scientific inquiries on the nature and development of OA. The two papers discussed here are just two recent examples of an ongoing discussion which will not be resolved in the near future.

[^1]: Danowski, P. (2019). An Austrian proposal for the Classification of Open Access Tuples (COAT) – Distinguish different Open Access types beyond colors. *Mitteilungen Der Vereinigung Österreichischer Bibliothekarinnen Und Bibliothekare*, 72(1), 59–65. https://doi.org/10.31263/voebm.v72i1.2276
[^2]: Harnad, S., Brody, T., Vallières, F., Carr, L., Hitchcock, S., Gingras, Y., Oppenheim, C., Hajjem, C., & Hilf, E. R. (2008). The Access/Impact Problem and the Green and Gold Roads to Open Access: An Update. *Serials Review*, 34(1), 36–40. https://doi.org/10.1016/j.serrev.2007.12.005
[^3]: Jenkins, C., Probets, S., Oppenheim, C., & Hubbard, B. (2007). RoMEO Studies 8: Self‐archiving: The logic behind the colour‐coding used in the Copyright Knowledge Bank. *Program*, 41(2), 124–133. https://doi.org/10.1108/00330330710742908
[^4]: Lucic, A. (n.d.). *Guides: Open Access: Many Colors of Open Access*. Retrieved May 5, 2020, from https://libguides.depaul.edu/c.php?g=844896&p=6039089
[^5]: Piwowar, H., Priem, J., Larivière, V., Alperin, J. P., Matthias, L., Norlander, B., Farley, A., West, J., & Haustein, S. (2018). The state of OA: A large-scale analysis of the prevalence and impact of Open Access articles. *PeerJ*, 6, e4375. https://doi.org/10.7717/peerj.4375
[^6]: Taubert, N., Hobert, A., Fraser, N., Jahn, N., & Iravani, E. (2019). Open Access—Towards a non-normative and systematic understanding. *ArXiv:1910.11568 [Cs]*. http://arxiv.org/abs/1910.11568
[^7]: van Leeuwen, T., Meijer, I., Yegros-Yegros, A., & Costas, R. (2017). Developing indicators on Open Access by combining evidence from diverse data sources. *Proceedings of the 2017 STI Conference*, 8. https://arxiv.org/abs/1802.02827