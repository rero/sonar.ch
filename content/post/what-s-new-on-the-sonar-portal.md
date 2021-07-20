---
title: "What's new on the SONAR portal?"
date: 2021-07-10T12:00:00+02:00
draft: false
tags: ["features", "research projects", "collections", "persistent identifiers", "local fields"]
---

It's been some time since the last update about SONAR's new features. The main ones are: research project management, custom collections, persistent identifier assignment (ARK), custom local fields and an Open Access filter. Let's take a look at these new features in detail and in pictures.

<!--more-->

## Research project management

The promotion of research projects is becoming increasingly important in the age of open science. For that reason, research projects are now full-fledged entities in SONAR, with their own metadata and deposit workflow. It now enables to:

* Link a document to a research project
    * either by the researcher who creates the deposit or by the librarian/administrator who directly enters the document in the database
	* in the deposit, the researcher can link to an existing project or add a new one
	* it is possible to link a document to more than one project
* Export a list of projects in CSV
* Browse the public and professional interfaces by research projects, using:
	* the *Research projects* link in the document detailed view
	* the project detailed view, which includes a list of linked publications
	* the project search feature (currently available in the professional interface only)

{{< youtube id="2w-gLX1X_7s" title="Add research projects when depositing a document" >}}
Soon, it will also be possible to use a submission and validation workflow for research projects, as is the case for publications.
## Custom collections

A new resource called "Collection" allows documents to be grouped according to a criteria defined by the institution. Thus in the image below, one can gather everything concerning research tools in Geneva history.

Please note that:

* each collection has a dedicated URL
* from this view, its is possible to launch a search within the documents of the collection only
* for each collection, a title and a description (in all the languages of the interface) as well as an image can be defined
* the whole configuration is at your fingertips, from the administration interface

{{< figure src="/images/custom_collections.png" caption="A collection in the public interface" alt="Screenshot of the collection 'Research tools in Geneva history'" width="100%" >}}

## Persistent identifier assignment (ARK)

Each document automatically receives a persistent identifier from the [ARK (Archival Resource Key) system](https://en.wikipedia.org/wiki/Archival_Resource_Key). An ARK identifier is persistent, i.e. it always points to the resource in question, even if the latter changes location, for example if the platform changes.

SONAR has chosen to assign ARKs rather than DOIs in a first step for the following two reasons:

* DOIs are often already assigned by the publisher to documents deposited in SONAR, and having multiple DOIs for the same document can create confusion.
* DOIs are reserved for documents, usually scientific, whereas ARKs can be assigned more broadly (to projects, people, collections, etc.)

The best workflow for discoverability and monitoring, especially outside of SONAR, is to add the DOI created by the publisher when submitting the publication to SONAR.

DOI attribution is not excluded as a medium term new feature.

## Local fields

SONAR allows to define three fields specific to an institution. The label can be defined in all the languages of the interface and one can decide to have a facet (or not) for this field. Again, everything is configured from the professional interface.

This allows an institution to store information that does not fit into the standard SONAR data model, such as a category for statistics or a local classification.

{{< figure src="/images/local_fields.png" caption="How to configure a local field in an organisation" alt="Screenshot of the configuration of local fields" width="100%" >}}

## Settings of the landing page text

A WYSIWYG editor allows to write the description that will be displayed on the landing page of the institution. Administrators can quickly adapt this text, or insert temporary messages to users of their platform.

## Open Access filter

A switch button now enables to filter the search results to documents that are Open Access.

{{< figure src="/images/open_access_button.jpg" caption="Open Access filter" alt="Screenshot of the switch button in the interface" width="100%" >}}

## Other issues

Many other small improvements have been made, e.g. about changing the interface language, drop-down menus, etc. In particular, various details of the submission form have been adjusted according to feedback from professionals in the field who will soon be using SONAR in production.

## Next to come: what are we doing right now at RERO+ ?

One of the main features we are working on is *subdivisions*. They enable an institution to define faculties (or departments, sections...) and to assign submitters and moderators to them.
