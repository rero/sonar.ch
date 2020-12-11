---
title: "Autumn tests and new features"
date: 2020-12-01T12:00:00+02:00
draft: false
tags: ["features", "licence", "file management", "file formats", "oai-pmh", "tests"]
---

The SONAR project ends soon and the system is getting closer and closer to going into production. Tests have been realised by various Swiss institutions. This article provides an update on the project progress.

<!--more-->

### Autumn tests

This autumn, 18 Swiss Higher Education Institutions have been testing (and some of them still are) SONAR on the [public demo site](https://sonar.test.rero.ch/). These consist mainly of universities of applied sciences (HES/FH) and universities of teacher education (HEP/PH).

We received some very useful feedback which led to enhancements and bug corrections. Other improvements are in the "waiting queue", documented in our publicly available [GitHub kanban](https://github.com/orgs/rero/projects/4).

In the meantime, we have also been working on the implementation of missing functionalities. A new version has been published on the [public test portal](https://sonar.test.rero.ch/) by the end of November.

### New features

4 important new features have been deployed.

**1. OAI-PMH**

This protocol is a *must* in the small world of institutional repositories, as it enables to harvest the metadata in order to reference it in another search portal. The most common use case is probably to integrate an institutional repository into the institution's library discovery tool.

In SONAR, one set is automatically generated for each member institution. The export format is currently Dublin Core and its 10 base elements. We tried to stay as close as possible to the [OpenAIRE guidelines, v3](https://guidelines.readthedocs.io/en/latest/literature/application_profile.html). We are already considering the addition of other more granular export formats.

To have a look, try to add `/oai2d?verb=ListRecords&metadataPrefix=oai_dc` to the base URL of the public test portal: [link to try!](https://sonar.test.rero.ch/oai2d?verb=ListRecords&metadataPrefix=oai_dc)

**2. Licence**

It is now possible to specify a licence, from a closed list that was intentionally kept generic so that it can be understood and used by the majority of people.

<img class="image fit" src="/images/licence.png" alt="Licence choice in SONAR" title="Licence choice in SONAR" >

**3. File management**

Until now, it was possible to deposit a main file and to attach additional annexes. From now on, a manager can see the list of files and, for each one, modify its position, displayed label and access rights. The latter can be one of *open access*, *under embargo*, or *restricted access*. It is also possible to enable access only from the organisation's IP addresses.

**4. Support of all file formats**

SONAR is now able to receive any file formats. A preview is available for PDF and some image formats. The other file types must be downloaded to be visualised.

### Small corrections

We could already correct some small things pointed out by the test institutions, for instance:

* ORCID supports X as last character.
* Bookmarks are better displayed in PDF previews.

### Next to come

The integration of **research project and funding information** in the document's metadata is under development. This will enable to navigate in the SONAR interface between documents through research projects.
