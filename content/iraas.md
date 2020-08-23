---
title: "Institutional Repository as a Service"
date: 2020-05-26T11:07:00+01:00
draft: false
---

The SONAR team at RERO can host your institutional repository platform, using [Invenio 3](https://invenio-software.org) software technology and the IT infrastructure of RERO in Martigny, Switzerland.

Please contact us at [info.sonar@rero.ch](mailto:info.sonar@rero.ch) for pricing details or other information. 

## Two forms {#shared_vs_dedicated}

This service is provided in two distinct forms:

- **Shared repository**: a multi-institutional portal, with a single common search and navigation interface, as well as common deposit policies. The documents of each institution are contained in a dedicated collection, with a unique URL (permalink) and an entry in the "Institution" filter (facet). [currently in tests, opening planned for **September 2020**]
- **Dedicated repositories** are independent portals, each with its own distinct identity and policies, and other extended features. [planned for **late 2020**]


## Features common to both forms:

- The interface is available in English, German, French and Italian
- Allows direct depositing of documents by scholars or students, with a validation workflow
- Supports SWITCH edu-ID and ORCID authentication
- Every deposited document is assigned a persistent identifier (DOI or ARK)
- Access embargos can be defined
- Metadata associated with a document include:
    - DOI, ARK, PMID and other identifier schemes
    - ORCID identifiers for authors
    - funding information (research projects)
- RESTful APIs for dealing with public content
- and others


## Shared repository features

- Documents are searchable and accessible in the SONAR global portal https://sonar.ch [upcoming]
- The documents of each client institution are grouped within a dedicated collection, with the following features:
	- a permalink of the kind `https://sonar.ch/[institution]`
	- a landing page with a brief description
	- an entry in the "Institution" filter/facet
- An [OAI-PMH set](http://www.openarchives.org/OAI/openarchivesprotocol.html#SelectiveHarvesting) allows selective harvesting of all the documents of the institution
- Each deposited document:
	- is a scholarly publication
	- is "open access", i.e.  includes the full text (an embargo is admitted)
	- has an authorship link to the institution, meaning at least one of the authors is affiliated to the institution
- Basic support is provided


## Dedicated repositories features

- The documents are searchable and accessible in an independent portal behind a custom URL `https://[institution domain]`. Open access documents are visible in the SONAR global portal as well https://sonar.ch [upcoming]
- The portal has custom branding (logo, styles)
- Content and access statistics are available
- Account grouping: submission and validation accounts can be grouped by department or by any other institutional subdivision
- Each document:
	- can be of any kind, not necessarily scholarly - meaning that the portal can become a versatile "digital library"
	- can be entered without the full text (metadata only)
	- can be made private to the institution (hidden full text)
- Bulk document upload is possible 
- Custom collections
- Custom [OAI-PMH sets](http://www.openarchives.org/OAI/openarchivesprotocol.html#SelectiveHarvesting) allow selective harvesting of parts of the institution's documents (per document type, per custom collection)
- 3 custom metadata fields can be defined and associated with predefined value lists (e.g. list of faculties)
- 3 custom facets can be activated to exploit custom metadata fields
- RESTful APIs are provided for manipulating private content (using an API key)
- Extended support is provided
- Custom developments are possible (quote provided on request)
