---
title: "Acquisition of Swiss-affiliated research records: first evaluation from the field"
date: 2020-11-12T12:00:00+02:00
draft: false
tags: ["HEG Genève", "content tracking", "full-text recovering", "open access"]
---

One of the tasks of the SONAR project is to assess the feasibility of a pipeline for automatically retrieving publications of researchers affiliated to Swiss publicly funded institutions, from third-party international databases. Almost 500,000 candidate bibliographic records were collected from CrossRef, MEDLINE, and PubMed Central, for building the first version of the SONAR dataset.

See current result on <a href="http://candy.hesge.ch/SONAR/">candy.hesge.ch/SONAR/</a>.


<!--more-->

### Comparative analysis

We then requested, in May 2020, the cooperation of Swiss Institutional Repository (IR) managers, in order to perform a comparative analysis between the SONAR dataset and their own records, and to provide qualitative feedback.

The questions asked were the following:

* How many publications provided by the SONAR retrieval process are already registered in your institutional repository or in your internal publication database? (coverage rate)
* How many new publications does SONAR provide? (potential increase rate)
* How many are missing?
* What is the procedure you apply in order to perform the comparison?

We have collected 9 answers from different Swiss IR managers, including 3 universities. We would like to deeply thank all respondents for their highly valuable work.

### Coverage rate

We [previously reported](http://candy.hesge.ch/SONAR/SONAR%20D5.1.pdf) coverage rates ranging from 51% to 60% for our pipeline, evaluated on two benchmarks linked to the SNSF publication database. But the coverage rates reported by IR managers are lower (on average 47% for universities, and 21% for others). There are several reasons explaining this suboptimal coverage rate:

* First, we only consider publications (1) with a DOI in CrossRef (2) with the institution explicitly mentioned in the affiliation metadata. Some publications in Swiss IRs are thus not reachable via this approach.
* For example, some respondents mentioned missing publications that were written by authors before they joined their institution (thus with a different affiliation in the metadata), but that are nevertheless deposited in their IR. These are out of the scope of SONAR.
* Another strong limitation is the publication type. In particular with MEDLINE, we focus on scientific articles in peer-reviewed journals, which is just one of the publication types contained in Swiss IRs (we do not collect press articles or PhD theses, for instance). But we consider this as the most valuable type and the best starting point for such an evaluation.

The fact that the reported improvement is below previous estimates is a particular cause for concern for some respondents, in a scenario where the monitoring of Swiss publication production was to be done via SONAR. However, besides the above-mentioned reasons, it is important to keep in mind that the objective of SONAR is not to replace existing IRs, but to help fill up content gaps. And indeed, a SONAR-based publication monitoring process must rely on the conjunction between the set of publications gathered from external sources and those harvested from Swiss IRs.

### Potential increase rate

Beyond coverage rate, we were interested in the publications that are present in the SONAR dataset but not in Swiss IRs, which represents a potential improvement for IRs. We [previously reported](http://candy.hesge.ch/SONAR/SONAR%20D5.1.pdf) a potential increase of the IRs coverage by +30-40% for some universities. Once again, in the answers we collected, this potential increase was bigger for universities (on average +25%) than for others (+8%). There were some concerns about the quality of these data. For one university, a manual analysis of 100 potential new records (amongst 24,000) showed that more than 80% of them were candidates for populating the IR. This ratio can be improved, by correcting some pointed out errors (~bugs).

We cannot assume or expect that such an automatic pipeline collecting thousands of records can be perfect. At the same time, it cannot be expected that human validation provides better precision. Our opinion is that interested institutions should reflect on the cost/benefit ratio of our dataset. The fundamental question to be asked is: is it acceptable to tolerate a couple of false positives to (semi-)automatically acquire several thousands of valid DOIs automatically?
