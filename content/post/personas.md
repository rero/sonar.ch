---
title: "Who is the typical user of SONAR?"
date: 2019-05-05T11:33:58+02:00
draft: false
tags: ["personas", "user interface", "user-centered design"]
---

An important task of the SONAR project is to conceive a user-friendly interface. We decided to structure this process according to the [five elements](http://www.jjg.net/elements/pdf/elements_ch02.pdf) of J.J. Garrett[^1]. Firstly, define the strategy of your product, and then its scope, its structure, its skeleton and finally its surface.

<!--more-->

Defining the typical user of SONAR is part of the element *scope* (user needs). To this aim, we adopted a method based on personas.

### What is a persona?

The *persona* is a well-known concept in the interaction design community. It was introduced 1999 by Alan Cooper[^2], who defines it as follows:

> We make up pretend users and design for them. We call these pretend users personas and they are the necessary foundation of good interaction design. Personas are not real people, but they represent them throughout the design process. They are hypothetical archetypes of actual users. Although they are imaginary, they are defined with significant rigor and  precision. Actually, we don't so much "make up" our personas as discover them as a byproduct of the investigation process. We do, however, make up their names and personal details.

### The 3 main SONAR personas

Each persona is presented below with an image, a name, some minimal context information and the tasks he/she performs on SONAR. Some institutions are mentioned, but only as examples, to make the personas more concrete. The tasks are listed for both services: the shared and the dedicated portals (as described in the [Service](/service) section).

|   |   |
| ------ | ----------- |
| <img class="image" src="/images/persona1.svg" alt="Population persona" title="Population persona" style="vertical-align:top;"><br/>**Fabrice**<br/>*Student (University of Kinshasa)* | **Shared or dedicated portal**<ul><li>access full text of publications for free so that I can keep up to date with scientific news</li><li>access publication metadata so that I can include references in my own publications</li><li>search publications using various criteria (author, project, institution, document type, etc.)</li></ul> |
| <img class="image" src="/images/persona2.svg" alt="Researcher persona" title="Researcher persona" style="vertical-align:top;"><br/>**Gordana**<br/>*Post-doctoral researcher (University of Fribourg - with dedicated SONAR portal)* | **Shared portal**<ul><li>publicly display a list of all my Swiss OA publications so that I can show my scholarly records</li><li>... plus the same tasks as Fabrice</li></ul>**Dedicated portal**<ul><li>publicly display a list of all my publications (OA or not) related to my institution so that I can show my scholarly records</li><li>upload full-texts of my pre-prints and post-prints so that I comply with the OA policy of my institution</li><li>enter and edit metadata about my publications so that they are searchable</li><li>export a list of all my publications (OA or not) related to my institution or to a specific project so that I can reuse the data</li><li>link my profile to standard identifiers (ORCID) so that my publications' metadata is more accurate</li><li>import metadata from other platforms (ORCID, Google Scholar, etc.) so that I don't have to enter it manually</li><li>edit my personal profile</li><li>... plus the same tasks as Fabrice</li></ul> |
| <img class="image" src="/images/persona3.svg" alt="Librarian persona" title="Librarian persona" style="vertical-align:top;"><br/>**Gabriele**<br/>*Librarian (Università della Svizzera italiana - with dedicated SONAR portal)* | **Shared portal**<ul><li>export metadata of publications according to various criteria (author, project, institution, document type, etc.) so that I can reuse the data (showcase, report, FNS, etc.)</li></ul>**Dedicated portal**<ul><li>upload PDF of pre-prints and post-prints (OA or not) of my institution's researchers so that they comply with the OA policy</li><li>indicate for each full-text the OA status (incl. embargo periods) so that they are publicly available or not accordingly.</li><li>enter metadata about publications (typology, rights, access, etc.) so that they are searchable</li><li>create user accounts for researchers, with specific rights</li><li>import metadata from other platforms (ORCID, Google Scholar, etc.) so that I don't have to enter it manually</li><li>validate full-text inputs of the researchers so that they comply with legal restrictions</li><li>validate and ev. complete metadata entered by researchers so that it complies with standards</li><li>export metadata of publications according to various criteria (author, project, institution, document type, …) so that I can reuse the data (showcase, report, etc.)</li><li>request or harvest publications according to various criteria (author, project, institution, document type, …) so that I can integrate them into other platforms (website, etc.)</li><li>ensure data integrity, readability and access so that we can access it in the long term</li></ul> |

3 other personas, not detailed in this blog post, complete the scope of user needs:

* Corinna, professor and researcher at University of Basel (without dedicated SONAR portal)
* Gaston, information specialist at SNSF
* Ruth, journalist at Neue Zürcher Zeitung

### And now what?

This work is still in progress and we are improving iteratively the personas. Based on this, we defined the functional specifications, with various detailed scenarios for each persona. We are currently working on the structure of the portal and conceiving the mockups of the interface.

We are also using this approach for the sister project [RERO ILS](https://rero21.ch/about/).


### References

[^1]: GARRETT, Jesse James. *[The elements of user experience: user-centered design for the web](https://explore.rero.ch/fr_CH/rero/result?se=The%20elements%20of%20user%20experience%20garrett&submit=&fd=any&pr=contains&ex=0&so=rank&fct%5Bi%5D%5Bcreator%5D%5B0%5D=Garrett%252C%2520Jesse%2520James)*. Berkeley CA : New Riders, 2003. ISBN 978-0-7357-1202-7.

[^2]: COOPER, Alan. *[The inmates are running the asylum: why high-tech products drive us crazy and how to restore the sanity](http://data.rero.ch/01-R006346412)*. Indianapolis, In : Macmillan, 1999. ISBN 978-0-672-31649-4.

Icons made by [Freepik](https://www.freepik.com/) from [Flaticon](https://www.flaticon.com/), licensed by [CC-BY 3.0](http://creativecommons.org/licenses/by/3.0/), modified by SONAR team