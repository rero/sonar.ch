---
title: "FAQ"
date: 2022-07-06
draft: false
---

### Categories {#categories}

* [Document upload: workflow and conditions](#upload)
* [Search and explore data](#search)
* [Persistent identifiers](#persistent)
* [Data export and harvesting](#export)
* [User roles and permissions](#permissions)
* [Transition from RERO DOC](#rerodoc)
* [General questions](#general)

__________


## Document upload: workflow and conditions {#upload}

#### It is possible to enter already existing DOIs?

Yes. When importing or manually depositing publications in SONAR, it is possible to include existing identifiers (DOI, PMID, etc.).

#### Which access options are possible to choose: open, embargoed, others?

Open and embargoed publications are available in the [Shared repository](/iraas/#shared_vs_dedicated). Closed access is also possible in [Dedicated repositories](/iraas/#shared_vs_dedicated). For the technical possibilities, see the [SONAR documentation](https://sonar.ch/help/file_management_en/).

#### Which licencing models are admitted for deposited publications?

SONAR does not decide which licences are allowed: this is a task of the institutions using the platform. The metadata allows to indicate a usage and access policy and/or select one of the following options:

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

All document types are accepted, including datasets. The latters can be referenced in two ways:

- For each record, a main file can be added, as well as additional files (annexes, figures, datasets).
- Datasets can also be deposited as independent objects with their own metadata record, which can be linked to another record.

The exhaustive list of document types is available in the [SONAR documentation](https://sonar.ch/help/document_types/).

#### Must a record entry contain a file or is it possible to only upload metadata?

It depends. In the [Shared repository](/iraas/#shared_vs_dedicated), only records containing an OA file are accepted. But in the [Dedicated repositories](/iraas/#shared_vs_dedicated), metadata-only records are admitted. It is up to the owning institution to define its deposit policies. More details about the conditions on the [IR hosting](/iraas/) page.

#### Which file formats are accepted?

All formats are accepted. Each institution defines its own acceptance policies.

#### What is the maximum file size accepted?

There is no file size limit.

#### Is the author charged a fee for publishing in SONAR?

No, not the authors directly. Institutions pay an annual fee for using the hosting service, which allows their authors to deposit.

#### Is the author able to deposit publications exclusively in his/her institution's repository or also into the global SONAR portal?

Both. The global SONAR portal is an aggregator - it gathers publications deposited in the IRs that it hosts ([Shared repository](/iraas/#shared_vs_dedicated) or [Dedicated repositories](/iraas/#shared_vs_dedicated)) as well as in other existing Swiss IRs (external to SONAR). Hence, in the end publications are made visible in the global SONAR portal.

#### Is SONAR responsible for data quality checking?

No. The data quality is always the responsibility of the depositing institution, be it the [Shared repository](/iraas/#shared_vs_dedicated) or in the [Dedicated repositories](/iraas/#shared_vs_dedicated). The web-based submission form already ensures a basic level of quality. A validation workflow can be used by the institution in order to handle data quality and licencing aspects.


## Search and explore data {#search}

[🔝 Back to top](#categories)

#### Are the full-text contents indexed, or only metadata?

Both. SONAR indexes all the full-text contents. By default, the search interface only provides results based on metadata search, for reasons of relevance. But a button easily allows the user to extend the search to the full-text contents.

#### Which sorting options are available?

By default, document search results are sorted by relevance. But it is possible to change this and sort them by title and by date (ascending, descending).

#### In a [Dedicated repository](/iraas/#shared_vs_dedicated), are the search results coming from the global SONAR or only from that specific repo?

A [Dedicated repository](/iraas/#shared_vs_dedicated) is self-contained and has a specific independent search interface. Its content might also be displayed in the SONAR global interface.

The [Shared repository](/iraas/#shared_vs_dedicated) is searchable via the SONAR global interface and includes a landing page for each institution, with its logo and description.

#### What information is shown for each document, each search result?

The displayed information can be seen on [sonar.ch](https://sonar.ch). All the main fields are shown to the user.

## Persistent identifiers {#persistent}

[🔝 Back to top](#categories)

#### SONAR assigns ARKs, but what are they?

ARK means Archival Resource Key. An ARK is a persistent identifier. It looks like this `ark:/53355/cl010066723` but can also be expressed as an URL.

#### What is the difference between ARK and DOI?

Both are persistent identifiers. The ARK solution is managed in a more decentralised way: each organisation can run its own ARK server. While DOIs are meant for publications, ARKs can be assigned to any type of web resources like persons or places.

#### Why doesn't SONAR assign DOIs? Is this planned for the future?

DOIs are key identifiers for scientific publications, but in most of the cases, these publications already receive a DOI from a commercial publisher. More than one DOI should ideally not be assigned to the same document. This could have a negative impact, for instance for OA monitoring where they play a key role. This is why SONAR assigns ARKs and has a dedicated field for storing existing DOIs.

In the future, it is not excluded to implement DOI assignment, as an option. As the DOI price model is different, this option might increase the costs of SONAR.

## Data export and harvesting {#export}

[🔝 Back to top](#categories)

#### Are the contents of SONAR searchable by search engines like Google Scholar?

Yes. The records are harvested by Google Scholar.

#### Is the OAI-PMH protocol available for 3rd party harvesting?

Yes. An OAI-PMH interface is available, see [the documentation](https://sonar.ch/help/oai-pmh/).

In the [Shared repository](/iraas/#shared_vs_dedicated), an [OAI-PMH *set*](http://www.openarchives.org/OAI/openarchivesprotocol.html#SelectiveHarvesting) exists for each institution.

In [Dedicated repositories](/iraas/#shared_vs_dedicated), custom [OAI-PMH *sets*](http://www.openarchives.org/OAI/openarchivesprotocol.html#SelectiveHarvesting) can be defined in order to allow selective harvesting of parts of the institution's documents (e.g. per document type, per custom collection).

#### Which metadata export formats are available?

Metadata export is possible in [native Bibframe/JSON via the REST API](https://sonar.ch/help/rest_api_endpoints/) or in [Dublin Core via OAI-PMH](https://sonar.ch/help/oai-pmh/). Other export formats (RIS, BibTeX, MARC21/XML) can be added later according to client's needs.


## User roles and permissions {#permissions}

[🔝 Back to top](#categories)

#### What types of user groups and permissions exist in SONAR?

There are four different roles – basic user, submitter, moderator, admin – with increasing permissions. More details in the [SONAR documentation](https://sonar.ch/help/user_roles/).

#### What are the policies concerning deleting documents?

Only persons with an "admin" role are allowed to delete documents. More details in the [SONAR documentation](https://sonar.ch/help/user_roles/).


## Transition from RERO DOC {#rerodoc}

[🔝 Back to top](#categories)

#### How long does RERO DOC remain in service?

RERO DOC remains online exclusively for libraries using RERO ILS. All other contents are progressively removed and transferred to another service. RERO+ is not deleting any data without confirmation of the owning institution.

#### Are RERO DOC publications automatically transferred to SONAR?

No. As the price model changes, institutions must adhere to the new service. They have been contacted by RERO+.

#### When can institutions migrate from RERO DOC to SONAR?

The migration process is taking place since January 2021.

#### Are RERO DOC links redirected to SONAR?

Yes, they are. Of course, this is only the case for publications migrated to SONAR.

## General questions {#general}

[🔝 Back to top](#categories)

#### What is the price of the Institutional Repository as a Service?

It is determined on the basis of two criteria: an annual fee per document and an annual participation fee. The amount depends on the [type of service](/iraas/) (shared or dedicated). A fixed price for migration and set up must be included in the calculations. For pricing details, please contact us at info.sonar@rero.ch.

#### Is documentation available?

Yes. SONAR provides [help pages](https://sonar.ch/help/). The help for the administration currently only exists in English, but translations are being prepared.

#### Does SONAR provide a long-term archiving solution?

Not yet. Currently, SONAR includes basic archiving features, which means: backup and restore of metadata and files as well as version tracking. But that does not reach the high standard of formal long-term archiving (with preservation plans and metadata, recovery plans, auditing, etc.). We are considering outsourcing an OAIS-compliant archiving service and provide it as an option for interested clients.

#### Will SONAR move to the upcoming InvenioRDM platform?

Maybe in the future. The good thing is that InvenioRDM is based on [Invenio 3](https://invenio-software.org), as is the case of SONAR, which means that common developments are possible. A complete move to InvenioRDM in the longer term is not to be excluded.

----------
