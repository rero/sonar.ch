+++
author = "Karsten Schuldt (FH Graubünden)"
date = 2020-03-25T10:00:00Z
draft = true
tags = ["openapc", "apc", "open access", "analytics"]
title = "On the problems of APC cost analysis"

+++
### What are we dealing with, when we talk about “costs of OA”?

It has become commonly accepted in the scientific community that Open Access comes with costs attached. Sustainable infrastructures, editorial work and other costs have to be financed somehow. But, as the concept of “Article Processing Charges” (APC) which have to be paid for the publication of OA-articles has taken root, it has also become commonplace to focus singularly on those costs when talking about the “costs of OA”.
<!--more-->
It is clear that this focus excludes other costs (e.g. for Open Journal System (OJS) instances run by libraries, OA offices), which should be kept in mind if somebody wants to determine the whole cost for OA. But in this post, we will focus on APCs.

### Data points for APCs

If one wishes to integrate the costs of APCs into the analysis of OA, one needs to have data of the actual APCs paid. This data is not openly available. (Otherwise, it would be solely a technical problem – one that has already been resolved; see below.)

There are basically two points from which this data could be harvested:

1. The institutions or persons that pay the APCs
2. The publishers that collect the APCs

Different strategies can be utilized to gather data at these points.

### Institutions and persons which pay for APCs

Who pays for APCs? This is not a trivial question. While literature on APCs often assumes that there are clear institutional procedures for their handling, in reality a plurality of possible “payers” exist:

* Libraries, either from their budget for collection development or using funds specifically allocated for APCs - or even other funds
* Science funders, either directly through offsetting and other agreements or through project funding
* Academic institutions on different levels (on a central level, on the level of institutes, on the level of researchers)
* Sometimes, APCs are not paid by the person or institution responsible for a publication (e.g. in a network of researchers, a researcher in a country / institution with an offsetting agreement “pays”, even though others have written the publication) or APCs are split between participating researchers
* Researchers themselves, using project grants, other funds or even their private money to pay for APCs

There are probably other instances of APC-payments, but the message is clear: There is no one institution that pays for APCs, but there is a fluid landscape of options. If one includes international research projects (that use different national structures of funding) or the different forms of “waiving” APCs, full or in part, by publishers, this only gets more complicated. There is also the problem of other fees, e.g. for “color publishing”, which are paid by researchers for OA and non-OA publications alike.

Keeping that in mind, it is clearly not possible to automatically gather all the payments for APCs at the point of payment itself. They have to be collected somehow with input from within institutions. There are approaches to this on an institutional level (see below), but other options would be thinkable as well (e.g. on a national level or field-specific levels for international research networks).

### The OpenAPC initiative

Today, the OpenAPC initiative is the most advanced infrastructure to collect data on APCs. (Pieper & Broschinski 2018; Jahn & Tullney 2016) It was set-up by the “Transparent Infrastructure for Article Charges” project that ran in Germany from 2015 to 2018. OpenAPC now consists of a growing dataset accessible on [Github](https://github.com/OpenAPC/openapc-de) , maintained by the University Library of Bielefeld.

Participating academic institutions contribute data about paid APCs, using a defined data structure. This data gets aggregated in the dataset. OpenAPC itself provides a [treemap server](https://treemaps.intact-project.org/apcdata/openapc/) for the analysis of this data, but the set is open and downloadable for other usages as well. For example, this data is used by the [Open Access Monitor Germany](https://open-access-monitor.de/#/publication-costs). Institutions which provide their data to OpenAPC get it analyzed by the OA monitor.

Participation in the OpenAPC initiative is voluntary. Its GitHub page provides a list of participating institutions. There is a strong focus on Germany, but institutions from Norway, Sweden, France, the United Kingdom and other countries provide data as well. Up until now, only the Swiss National Science Foundation and the Bern University of Applied Sciences have provided data from Switzerland.

Participating in the initiative leads to the establishment of internal structures to gather the APC costs by the institutions. Lisa Lovén (2019) from the Stockholm University Library describes this process for Swedish universities. All of them are now obligated to provide this data (in Swedish kronor), so every university set up their own infrastructure for reporting. While her text describes a centralized structure as the best approach, where theoretically every APC should go through the university library, this does not have to be the case in every institution. Other forms of reporting are possible (and probably more useful in less centralized systems like Swiss universities), as long as they end up with a single data point for each institution.

Lovén’s article gives an example for a national solution as well: all of the data from Sweden is collected, transformed into the data structure of OpenAPC (e.g. converted into Euro) and then pushed to the initiative. Such a system could also be established in other countries, in a form that is workable in the structure of scientific institutions of the respective country (e.g. by swissuniversities for Switzerland). This is a political question, rather than a technical one: Will Swiss academic institutions be willing to gather the data of the APCs they paid? Will there be a joint effort of all or most of those institutions to gather this data?

### Data from publishers

APCs are usually paid to established publishers (like Elsevier, Springer) or organizations (like PLOS), with which libraries and national structures for scientific services often negotiate and sign contracts for reading and increasingly for publishing (e.g. the aforementioned offsetting deals). Those entities could also provide data on APCs, but until now there seems to be no initiative to demand this data.

However, the COUNTER-project would provide a precedent of establishing a standard for the reporting of data to libraries. [COUNTER](https://www.projectcounter.org/) was implemented through a coordinated effort by libraries to persuade publishers to provide usage date for electronic documents in a consistent way, using arguments and their power as negotiating partners (e.g. the ones with the money). It could be theorized that such a persuasion could also be organized for data on APCs, in particular when libraries are not acting alone but in coordination with academic institutions and funders. That would need the political will to bring up this question in negotiations and the establishment of an infrastructure for the reporting of such data.

Yet, COUNTER also provides a precedent of problems to come, if this route is chosen: still today, data is reported differently and not always comprehensively. Especially smaller organizations and publishers sometimes seem to have problems in establishing this reporting, although the standard has achieved its 5th release.

## Literature

Jahn, Najko, and Marco Tullney. “A Study of Institutional Spending on Open Access Publication Fees in Germany.” _PeerJ_ 4 (August 9, 2016): e2323. [https://doi.org/10.7717/peerj.2323](https://doi.org/10.7717/peerj.2323 "https://doi.org/10.7717/peerj.2323").

Lovén, Lisa. “Monitoring Open Access Publishing Costs at Stockholm University.” _Insights_ 32, no. 1 (January 17, 2019): 3. [https://doi.org/10.1629/uksg.451](https://doi.org/10.1629/uksg.451 "https://doi.org/10.1629/uksg.451").

Pieper, Dirk, and Christoph Broschinski. “OpenAPC: A Contribution to a Transparent and Reproducible Monitoring of Fee-Based Open Access Publishing across Institutions and Nations.” _Insights_ 31, no. 0 (October 10, 2018): 39. [https://doi.org/10.1629/uksg.439](https://doi.org/10.1629/uksg.439 "https://doi.org/10.1629/uksg.439").