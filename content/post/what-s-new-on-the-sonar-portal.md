---
title: "What's new on the SONAR portal?"
date: 2021-07-10T12:00:00+02:00
draft: false
tags: ["features", "research projects", "collections", "persistent identifiers", "local fields"]
---

It's been some time since the last update about the SONAR features. The main ones are: research projects, custom collections, persistent identifiers (ARK), custom local fields and Open Access button. Let's take a look at these new features in detail and in pictures.

<!--more-->

## Research projects

The promotion of research projects is becoming increasingly important in the age of open science. SONAR enables now to:

* Link a document to a research project
    * either by the research who creates the deposit or by the librarian/administrator who directly enter the document in the database
	* in the deposit, the researcher can link to an existing project or add a new one
	* it is possible to link to more than one project
* Export a list of projects in CSV
* Browse the public and professional interfaces by research projects
	* Project link on the document detailed view
	* Project detailed view with the list of linked publications
	* Search of projects (only in the professional interface)

{{< youtube id="2w-gLX1X_7s" title="Add research projects when depositing a document" >}}

## Custom collections

A new resource called "Collection" allows documents to be grouped according to a criteria defined by the institution. Thus in the image below, one can gather everything concerning research tools in Geneva history.

Please note that:

* each collection receives an identifier in the form of a URL
* from this view, all corresponding documents are displayed and can be searched
* for each collection, a title and a description (in all the languages of the interface) as well as an image can be defined
* the configuration is at your fingertips from the administration interface

{{< figure src="/images/custom_collections.png" caption="A collection in the public interface" alt="Screenshot of the collection 'Research tools in Geneva history'" width="100%" >}}

## Persistent identifiers (ARK)

Each document automatically receives a persistent identifier from the [ARK (Archival Resource Key) system](https://en.wikipedia.org/wiki/Archival_Resource_Key). An ARK identifier is persistent, i.e. it always points to the resource in question, even if the latter changes location, for example if the platform changes.

SONAR has chosen to assign ARKs rather than DOIs in a first step for the following two reasons:

* DOIs are often already assigned by the publisher to documents deposited in SONAR, and duplicate DOIs are thus avoided.
* DOIs are reserved for documents, usually scientific, whereas ARKs can be assigned more broadly (to projects, people, collections, etc.)

The best workflow for discoverability and monitoring, especially outside of SONAR, is to add the DOI created by the publisher when submitting the publication to SONAR.

DOI attribution is not excluded as a medium term new feature.

## Local fields

SONAR allows to define three fields specific to an institution. The label can be defined in all the languages of the interface and one can decide to have a facet (or not) for this field. Again, everything is configured from the professional interface.

This allows an institution to store information that does not fit into the standard SONAR data model, such as a category for statistics or a local classification.

{{< figure src="/images/local_fields.png" caption="How to configure a local field in an organisation" alt="Screenshot of the configuration of local fields" width="100%" >}}

## Settings of the landing page text

A WYSIWYG editor allows to write the description that will be displayed on the landing page of the institution. Administrators can quickly adapt this text, or insert temporary messages to users of their platform.

## Open Access button

A button now enable to filter in one click the documents that are Open Access.

{{< figure src="/images/open_access_button.jpg" caption="Open Access button" alt="Screenshot of the button in the interface" width="100%" >}}

## Other issues

Many other small improvements have been made, e.g. about changing the interface language, drop-down menus, etc. In particular, various details of the submission form have been adjusted according to feedback from professionals in the field who will soon be using SONAR in production.

## Next to come: what are we doing right now at RERO+ ?

The main feature we are working one consists in the subdivisions. This will enable an institution to configure departments and to assign submitters and moderators to them.