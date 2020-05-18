---
title: "Choosing a document typology is always a conundrum"
date: 2020-02-19T08:00:00+01:00
draft: false
tags: ["document types", "vocabulary", "coar", "metadata"]
---

As reflected in the title, it is not a simple job to define a document typology for a library platform. This article gives a very brief overview of the problem and the choices made for SONAR.

<!--more-->

### Why a document typology

As always, we have to start the analysis with the end users ([back to our personas!](https://sonar.ch/post/personas/)), in order to define the objectives of the typology.

* All user groups, but especially students and researchers, will use types for discovery, for example to refine search results or identify with precision a specific document.
* Librarians and more broadly information specialists will use a typology to monitor a repository (OA rate, content and consultation statistics, etc.)

Monitoring purposes become more and more important, particularly with the Swiss national strategy on Open Access and its [action plan](https://www.swissuniversities.ch/fileadmin/swissuniversities/Dokumente/Hochschulpolitik/Open_Access/Plan_d_action-f.pdf). This document states that at least books, book parts and articles should be monitored.

### Comparing uses and standards

As good professionals of the library domain, we analysed existing standards.

Having a look at the sister project [RERO ILS](https://ils.test.rero.ch/) using RDA (Resource Description and Framework), we observed that this standard recommends to use and combine 4 different typologies to determine a document type:

* [content types](http://www.rdaregistry.info/termList/RDAContentType/): 23 values possible
* [media types](http://www.rdaregistry.info/termList/RDAMediaType/): 8 values possible
* [carrier types](http://rdaregistry.info/termList/RDACarrierType): 56 values possible
* [mode of issuance](http://www.rdaregistry.info/termList/ModeIssue/): 4 values possible

Theoretically, 5'152 possible document types can be defined with RDA (not considering that multiple values can be used per category!), but this doesn't even allow to identify a thesis or to distinguish a book chapter from a journal article. RDA is therefore not adequate to the target audience.

Another standard typology, this one specifically dedicated to institutional repositories, is proposed by the OA repository association [COAR](https://www.coar-repositories.org). This [vocabulary](http://vocabularies.coar-repositories.org/documentation/resource_types/) is proposed in RDF with persistent identifiers, mappings to other vocabularies and labels in about 15 languages, including the three official Swiss idioms. It includes a list of 71 controlled values, designed in the form of a small thesaurus (hierarchy with broader and narrower terms as well as synonyms).

The COAR vocabulary has a good coverage of our needs. To be sure of that, we established a comparison with the document types used in some of the Swiss OA repositories (Arodes, BORIS, EDOC, EPFL, ETH, RERO DOC, UNIGE, Zora and of course COAR). You have an overview of it in the picture below. Please note that this is a working document!

{{< figure src="/images/doc_typology_comparison.svg" caption="Typology of Swiss IR (working document)" alt="Table: typology of Swiss IR (working document)" width="100%" >}}

You can also [download this comparison in PDF](/documents/doc_typology_comparison.pdf).

### Planned typology for SONAR (at this stage of the project)

Below is represented the typology adopted for SONAR, inspired from the [COAR vocabulary](http://vocabularies.coar-repositories.org/documentation/resource_types/) and consisting of 14 main types. At the metadata creation, the user selects a type and, where applicable, a subtype. In the discovery interface, a facet can display the types either in two levels (as currently in [RERO DOC](http://doc.rero.ch/)) or also in a simplified way all in one level (as in [RERO Explore](https://explore.rero.ch/)).

From the COAR vocabulary, only a subset of the types have been selected, on the one hand to have a simplified and only two levels typology, and on the other hand to use only relevant types. Some values, marked with a "(S)" for "SONAR", are not part of COAR but can be easily mapped to a corresponding COAR broader value.

| Type | Subtype |
| ------ | ----------- |
| 1. book |  |
| 2. book part |  |
| 3. conference object | conference paper<br />conference paper not in proceedings<br />conference poster<br />conference poster not in proceedings<br />conference proceedings<br />other (S) |
| 4. contribution to journal | data paper<br />journal article (default)<br />review article<br />other (S) |
| 5. dataset |  |
| 6. lecture |  |
| 7. non-textual object (S) | moving image<br />still image<br />cartographic material<br />sound<br />musical notation<br />software |
| 8. patent |  |
| 9. periodical | journal<br />magazine<br />newspaper |
| 10. preprint |  |
| 11. report | internal report<br />memorandum<br />other type of report<br />policy report<br />project deliverable<br />report part<br />report to funding agency<br />research report (default)<br />technical report<br />other (S) |
| 12. thesis | bachelor thesis<br />doctoral thesis<br />master thesis<br />habilitation thesis (S)<br />advanced studies thesis (S)<br />other (S) |
| 13. working paper |  |
| 14. other |  |