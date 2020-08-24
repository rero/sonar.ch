---
title: "FAQ"
date: 2020-08-24
draft: false
---

### Categories {#categories}

* [Document upload: workflow and conditions](#upload)
* [Search and explore data](#search)
* [Data export and harvesting](#export)
* [User roles and permissions](#permissions)
* [General questions](#general)

__________


## Document upload: workflow and conditions {#upload}

#### It is possible to enter already existing DOIs?

Yes. When importing or manually depositing publications in SONAR, it is possible to include existing identifiers (DOI, PMID, etc.). The attribution of DOI/ARK by SONAR is mainly meant for resources without other persistent identifiers.

#### Which access options are possible to choose: open, embargoed, others?

Open and embargoed publications are available in the [Shared repository](/iraas/#shared_vs_dedicated). Closed access is also possible in [Dedicated repositories](/iraas/#shared_vs_dedicated). More details on the [IR hosting](/iraas/) page.

#### Which licencing models are admitted for deposited publications?

These are the currently available options, but this list can be extended according to client's needs:

* CC0
* CC BY
* CC BY-NC
* CC BY-NC-ND
* CC BY-NC-SA
* CC BY-ND
* CC BY-SA
* Other OA / licence undefined
* Not OA / Rights reserved

#### What about author's copyrights? Are they transferred to SONAR?

No. Currently, SONAR is a *deposit* facility; it retains no rights, apart from the (non-exclusive) right to store and index the contents and make them available online. Rights of use are determined by the depositing institution (see previous questions).

#### Which document types are accepted? Are datasets accepted?

Yes, datasets are accepted in two ways.

- For each record, a main file can be added, as well as additional files (annexes, figures, datasets).
- Datasets can also be deposited as independent objects with their own metadata record.

The exhaustive list of document types is available in the [SONAR documentation](https://sonar.test.rero.ch/help/document_types/).

#### Must a record entry contain a file or is it possible to only upload metadata?

It depends. In the [Shared repository](/iraas/#shared_vs_dedicated), only records containing an OA file are accepted. But in the [Dedicated repositories](/iraas/#shared_vs_dedicated), metadata-only records are admitted. It is up to the owning institution to define its deposit policies. More details about the conditions on the [IR hosting](/iraas/) page.

#### Which file formats are accepted?

All formats are accepted. Each institution defines its own acceptance policies.

#### What is the maximum file size accepted?

The limit for each file is currently set at 500 MB. Technically, we can set a higher limit, but we care about users who might find themselves downloading very large files without noticing it, for instance using a mobile terminal on a limited data plan, or in roaming.

#### Is the author charged a fee for publishing in SONAR?

No, not the authors directly. Institutions pay an annual fee for using the hosting service, which allows their authors to deposit. SONAR is not a publishing platform (maybe in the future!) but a deposit platform for publications.

#### Is the author able to deposit publications exclusively in his/her institution's repository or also into the global SONAR portal?

Both. The global SONAR portal is an aggregator - it gathers publications deposited in the IRs that it hosts ([Shared repository](/iraas/#shared_vs_dedicated) or [Dedicated repositories](/iraas/#shared_vs_dedicated)) as well as in other existing Swiss IRs (external to SONAR). Hence, in the end publications are made visible in the global SONAR portal.

#### Is SONAR responsible for data quality checking?

No. The data quality is always the responsibility of the depositing institution, be it the [Shared repository](/iraas/#shared_vs_dedicated) or in the [Dedicated repositories](/iraas/#shared_vs_dedicated). The web-based submission form already ensures a basic level of quality. A validation workflow can be used by the institution in order to handle data quality and licencing aspects.


## Search and explore data {#search}

[🔝 Back to top](#categories)

#### Are the full-text contents indexed, or only metadata?

Both. SONAR indexes all the full-text contents. By default, the search interface only provides results based on metadata search, for reasons of relevance. But a button easily allows the user to extend the search to the full-text contents.

#### Which searching facets/filters are available?

The facets below are available. Other can be added according to client's needs. The beta SONAR can be tested here: [sonar.test.rero.ch](https://sonar.test.rero.ch).

* Document type
* Swiss affiliation
* Year
* Specific collection
* Language
* Author
* Subject
* Organisation

#### Which sorting options are available?

For now, SONAR does not have sorting options, but it is on the roadmap: we intend to integrate a basic sort by date (ascending, descending) and title. Other are not excluded if there is a need.

#### In a [Dedicated repository](/iraas/#shared_vs_dedicated), are the search results coming from the global SONAR or only from that specific repo?

A [Dedicated repository](/iraas/#shared_vs_dedicated) is self-contained and has a specific independent search interface. Its content might also be displayed in the SONAR global interface.

The [Shared repository](/iraas/#shared_vs_dedicated) is searchable via the SONAR global interface and includes a landing page for each institution, with its logo and description.

#### What information is shown for each document, each search result?

The displayed information can be seen on [sonar.test.rero.ch](https://sonar.test.rero.ch). The following fields are displayed in the detailed view of a document (others can be added according to client's needs):

* Document type
* Title
* Contributors (name, ORCID, affiliation, Swiss controlled affiliation)
* Date (and full publication statement if applicable)
* Extent
* Journal (for an article)
* Dissertation note (for a thesis)
* Abstract/author
* Subjects
* Abstract
* Identifiers (DOI, PMID, ...)
* Other electronic version
* Language
* Classification


## Data export and harvesting {#export}

[🔝 Back to top](#categories)

#### Are the contents of SONAR searchable by search engines like Google Scholar?

Yes. The records are harvested by Google Scholar.

#### Is the OAI-PMH protocol available for 3rd party harvesting?

Yes. The OAI-PMH interface is available.

In the [Shared repository](/iraas/#shared_vs_dedicated), an [OAI-PMH *set*](http://www.openarchives.org/OAI/openarchivesprotocol.html#SelectiveHarvesting) exists for each institution.

In [Dedicated repositories](/iraas/#shared_vs_dedicated), custom [OAI-PMH *sets*](http://www.openarchives.org/OAI/openarchivesprotocol.html#SelectiveHarvesting) can be defined in order to allow selective harvesting of parts of the institution's documents (e.g. per document type, per custom collection).

#### Which metadata export formats are available?

Metadata export is possible in Dublin Core via OAI-PMH. Other export formats (RIS, BibTeX, MARC21/XML) can be added later according to client's needs.


## User roles and permissions {#permissions}

[🔝 Back to top](#categories)

#### What types of user groups and permissions exist in SONAR?

There are four different roles – basic user, submitter, moderator, admin – with increasing permissions. More details in the [SONAR documentation](https://sonar.test.rero.ch/help/user_roles/).

#### What are the policies concerning deleting documents?

Only persons with an "admin" role are allowed to delete documents. More details in the [SONAR documentation](https://sonar.test.rero.ch/help/user_roles/).


## General questions {#general}

[🔝 Back to top](#categories)


#### Is documentation available?

Yes. SONAR provides [help pages](https://sonar.test.rero.ch/help/). They currently exist only in English, but translations are being prepared.

#### Does SONAR provide a long-term archiving solution?

Not yet. Currently, SONAR includes basic archiving features, which means: backup and restore of metadata and files as well as version tracking. But that does not reach the high standard of formal long-term archiving (with preservation plans and metadata, recovery plans, auditing, etc.). We are considering outsourcing an OAIS-compliant archiving service and provide it as an option for interested clients.

#### Will SONAR move to the upcoming InvenioRDM platform?

Maybe. The timeline of InvenioRDM is a bit behind our project's deadlines, as SONAR must go live this year (2020). The good thing is that InvenioRDM is based on [Invenio 3](https://invenio-software.org), as is the case of SONAR, which means that common developments are possible. A complete move to InvenioRDM in the longer term is not to be excluded.

----------
