---
title: "Creating mockups for SONAR"
date: 2019-07-14T18:00:00+02:00
draft: false
tags: ["mockups", "user interface", "user-centered design"]
---

The work on designing the user interface of SONAR is progressing. According to the adopted methodology (presented in the beginning of the [post about personas](/post/personas/)), we proceed in five layers: 1. Strategy, 2. Scope, 3. Structure, 4. Skeleton and 5. Surface.

Mockups belongs to layer 4, consisting in defining the *skeleton* of the system, or how it visually interacts with a user.

<!--more-->

### Mockup: definition

In user centered design and user interface design, mockups are visual simulations of the targeted software product. They are created in order to acquire feedback during the design process. There are some terminology debates about the difference between wireframes, mockups and prototypes[^1]: the main distinction criteria are the visual fidelity and the possibility to interact with the simulation.

In the project, we use the term "mockups": we consider them somewhere between low and high fidelity, with no interaction possible.

### The wider context of user-centered design

Prior to creating the mockups, a whole series of scenarios for SONAR have been identified and documented in detail (layer 2: *Scope*). Each scenario is attributed to one particular persona. Examples:

* Persona *Gordana* (researcher): upload a full-text publication, search publications using various criteria
* Persona *Gabriele* (librarian): create an account for a researcher, validate an uploaded file and add administrative data
* Etc.

Then we organised these scenarios logically, creating a tree for information architecture and a basic navigation map (layer 3: *Structure*).

For the layer 4 *Skeleton*, we started to create 3-4 mockups, each simulating one scenario.

### Example of a SONAR mockup

The mockup presented below addresses the workflow of uploading a full-text publication as a researcher (IR as a service feature).

<img class="image fit" src="/images/upload_publication.gif" alt="Mockups of uploading a full-text publication" title="Mockups of uploading a full-text publication" >

The corresponding scenarios is the following:

* `GORDANA` Signs in
* `SYSTEM` Displays options for authenticated users
* `GORDANA` Clicks on “Add publication(s)”
* `SYSTEM` Displays four options (“1. Upload full-text”, “2. Paste a DOI”, “3. Import records from file (BibTeX, RIS, ...)”, “4. Create record manually”)
* `GORDANA` Chooses “1. Upload full-text”
* `SYSTEM` Displays a space for uploading a document
* `GORDANA` Drags and drops her PDF
* `SYSTEM` Extracts available metadata from the PDF. Adds her as author of the document if this data is missing
* `GORDANA` Completes or corrects metadata, incl. diffusion rights, and save
* `SYSTEM` Adds document to the system

The mockup has already been improved based on feedback from project partners. For instance, we added a preview feature before publishing and a button to cancel the process.

The mockup can also be downloaded the mockup as a [PDF file](/documents/upload_publication.pdf), which includes in addition three snapshots of the mobile version as well as a few explaining comments (in pink boxes!).

For any suggestions or questions, don't hesitate to contact us via [Twitter](https://twitter.com/sonardotch), [e-mail](mailto:info.sonar@rero.ch) or [Github](https://github.com/rero/sonar)!

[^1]: MKRTCHYAN, Rafayel. Wireframe, mockup, prototype: what is what? UX Planet [online]. 26 June 2018. [Accessed 4 July 2019]. Available from: https://uxplanet.org/wireframe-mockup-prototype-what-is-what-8cf2966e5a8b