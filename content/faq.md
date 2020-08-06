---
title: "FAQ"
date: 2020-07-28
draft: false
---

Categories

* [General questions](#general)
* [Document upload: workflow and conditions](#upload)
* [Search and explore data](#search)
* [Data export and harvesting](#export)
* [User roles and permissions](#permissions)

## General questions {#general}

[🔝 Back to top](#top)


**(!) Is there a documentation or a help?**

Yes, SONAR includes [help pages](https://sonar.test.rero.ch/help/). They exist currently only in English and are progressively completed.

**Does SONAR provide a long term archiving solution?**

Currently, SONAR does not provide such a service. We may outsource an OAIS-compliant archiving service and provide it as an option for interested clients.

Basic archiving is provided for all of RERO services, however, which means: backup and restore of metadata and files as well as version tracking, but that does not reach the high standard of formal long term archiving (with preservation plans and metadata, recovery plans, auditing, etc.).

**Will Sonar stick to Invenio 3 or move to the upcoming InvenioRDM platform?**

The timeline of InvenioRDM is a bit behind our deadlines, as we have to go live with SONAR this year. The good thing is that InvenioRDM is based on Invenio 3, as is the case of SONAR, which means that SONAR might benefit from their developments. A complete move to Invenio RDM in the medium term is not to be excluded, bit it’s too soon now to consider that option.

## Document upload: workflow and conditions {#upload}

[🔝 Back to top](#top)

**It is possible to enter already existing DOIs?**

The processes of import or manual cataloguing allows to enter into SONAR already existing identifiers (DOI, PMID, etc.). The attribution of DOI/ARK by SONAR is only meant to resources without identifiers.

**Which access options are possible to choose (open/embargoed/further more)?**

Open and embargoed are available in the shared portal. Closed access is also possible in the Dedicated version. More details on the [IR hosting](/iraas/) page.

**(!) Which licencing models are integrated?  Creative commons?**

The following list is available and can be extended according to user needs:

* CC0
* CC BY
* CC BY-NC
* CC BY-NC-ND
* CC BY-NC-SA
* CC BY-ND
* CC BY-SA
* Other OA / licence undefined
* Not OA / Rights reserved

**What about the copyrights of the author(s)? Are they transfered to SONAR?**

SONAR is only a deposit facility, it retains no rights, apart from the (non-exclusive) right to store the contents and make them available online. Rights of use are determined by the depositing institution (see previous questions).

**Which document types are accepted? Are datasets accepted?**

Datasets are accepted. For each record, a main file can be added, as well as additional files (annexes, figures, datasets).

The exhaustive list of document types is available in the [SONAR documentation](https://sonar.test.rero.ch/help/document_types/).

**Must a record entry contain a file or is it possible to only upload metadata?**

In the shared portal, only records with OA file are accepted. In the dedicated portal, metadata records are possible; it is up to the owning institution to define its deposit policies. More details about the conditions on the [IR hosting](/iraas/) page.

**(!) Which file formats are accepted?**

To be completed

**(!) What is the maximum file size accepted?**

To be completed

**Is the author charged a fee for publishing in SONAR?**

Institutions pay an annual fee for using the hosting service, which allows their authors to deposit. SONAR is not a publishing platform (maybe in the future!) but a deposit platform for publications.

**Is the author able to upload files exclusively into the institutional repo or also into SONAR itself?**

The global SONAR portal is only an aggregator - it gathers publications deposited either in hosted IRs (shared or dedicated) or in other existing Swiss IRs (external to SONAR). Hence, every scientific publication published in the SONAR shared repo or in any SONAR dedicated repo will be made visible on the global SONAR portal.

**Is SONAR responsible for data quality checking?**

The data quality is always a responsibility of the submitting institution, be it the SONAR shared repo or a SONAR dedicated repo. The web based submission form already ensures a basic level of quality. A validation workflow can be used by the institution to check it, as well as licencing and diffusion aspects.

## Search and explore data {#search}

[🔝 Back to top](#top)

**(!) Are the full texts indexed, or only the metadata?**

By default, SONAR searches only in metadata for reasons of results relevance. But a button enables to extend search to full texts.

**Which searching facets/filters are available?**

The facets below are available. Other can be added according to user needs. You can test the bêta SONAR here: [sonar.test.rero.ch](https://sonar.test.rero.ch).

* Document type
* Swiss affiliation
* Year
* Specific collection
* Language
* Author
* Subject
* Organisation

**Which sorting options are available?**

For now, SONAR does not have sorting options, but it is on the roadmap: we intend to integrate a basic sort by date (ascending, descending) and title. Other are not excluded if there is a need.

**(!) In a private repo, are the search results from all over SONAR or only from the institional repo?**

A private repo is isolated and self-contained, hence search results are limited to it. The shared repo is searchable via the SONAR global interface and includes a landing page for each of its institutions, with the logo and a brief description.

**What information is shown for each document, each search result?**

You can see the currently displayed information on [sonar.test.rero.ch](https://sonar.test.rero.ch). The following fields are displayed in the detailed view of a document (other can be added according to user needs):

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


## Data export and havesting {#export}

[🔝 Back to top](#top)

**(!) In which formats metadata can be exported?**

Metadata export is possible in Dublin Core/XML via OAI-PMH. Other export formats (RIS, Bibtex, MARC21/XML) can be added later according to user needs.

**(!) Are the records in SONAR searchable by search engines like Google Scholar or by other repositories?**

Yes, the records are harvested by Google Scholar. An OAI-PMH interface is available for other repositories to harvest the data. One OAI-set is automatically defined for each institution.

## User roles and permissions {#permissions}

[🔝 Back to top](#top)

**What types of user groups and permissions exist in SONAR?**

There are three different roles – submitter, moderator, admin – with increasing permissions. More details in the [SONAR documentation](https://sonar.test.rero.ch/help/user_roles/).

**What are the policies concerning deleting documents?**

Only to the person with an "admin" role are able to delete documents. More details in the [SONAR documentation](https://sonar.test.rero.ch/help/user_roles/).

