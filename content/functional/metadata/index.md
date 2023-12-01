---
title: Metadata
summary: Adding metadata exponentially increases the value of data. Did somebody already adjust old data to conform to constantly changing geographic boundaries? What are some practical ways of combining satellite sensory data with my organization's records? And do I have the right to do so? Metadata logs the history of data, providing instructions on how to reuse it, also setting the terms of use. We automate this labor-intensive process applying the FAIR data concept.
tags:
- metadata

date: "2021-07-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Diamond Polisher, ©[Andere Andre](https://commons.wikimedia.org/w/index.php?curid=4770037)"
  focal_point: Center

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/EconDataObs
- icon: linkedin
  icon_pack: fab
  name: Connect
  url: https://www.linkedin.com/company/78562153/
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/dataobservatory-eu/dataobservatory/
- icon: book-open
  icon_pack: fas
  name: Documentation
  url: https://r.dataobservatory.eu/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: Trustworthy AI
---

*Adding metadata exponentially increases the value of data. Did your region add a new town to its boundaries? How do you adjust old data to conform to constantly changing geographic boundaries? What are some practical ways of combining satellite sensory data with my organization's records? And do I have the right to do so? Metadata logs the history of data, providing instructions on how to reuse it, also setting the terms of use. We automate this labor-intensive process applying the FAIR data concept.*

In our observatory we apply the concept of [FAIR](#FAIR) (**f**indable, **a**ccessibe, **i**nteroperable, and **r**eusable digital assets) in our APIs and in our open-source statistical software packages. 

## The hidden cost item

Metadata gets less attention than data, because it is never acquired separately, it is not on the invoice, and therefore it remains an a hidden cost, and it is more important from a budgeting and a usability point of view than the data itself. Metadata is responsible for industry non-billable hours or uncredited working hours in academia. Poor data documentation, lack of reproducible processing and testing logs, inconsistent use of currencies, keywords, and storing [messy data](#messy-data) make reusability and interoperability, integration with other information impossible. 

[FAIR Data and the Added Value of Rich Metadata](#FAIR-data) we introduce how we apply the concept of [FAIR](#FAIR) (**f**indable, **a**ccessibe, **i**nteroperable, and **r**eusable digital assets) in our APIs. 

Organizations pay many times for the same, repeated work, because these boring tasks, which often comprise of tens of thousands of microtasks, are neglected. Our solution creates automatic documentation and metadata for your own historical internal data or for acquisitions from data vendors. We apply the more general [Dublin Core](#Dublin-Core) and the more specific, mandatory and recommended values of [DataCite](#DataCite) for datasets -- these are new requirements in EU-funded research from 2021. But they are just the minimal steps, and there is a lot more to do to create a diamond ring from an uncut gem.

## Map your data: bibliographis, catalogues, codebooks, versioning

Updating descriptive metadata, such as bibliographic citation files, descriptions and sources to data files downloaded from the internet, versioning spreadsheet documents and presentations is usually a hated and often neglected task withing organization, and rightly so: these boring and error-prone tasks are best left to computers. 

{{< figure src="/img/gems/n-RFId0_7kep4-unsplash.jpg" caption="Already adjusted spreadsheets are re-adjusted and re-checked. Hours are spent on looking for the right document with the rigth version. Duplicates multiply. Already downloaded data is downloaded again, and miscategorized, again. Finding the data without map is a treasure hunt. Photo: © [N.](https://unsplash.com/photos/RFId0_7kep4?utm_source=unsplash)" numbered="false" >}}

The lack of time and resources spend on documentation over time reduces reusability and significantly increases data processing and supervision or auditing costs. 

- [x] Our observatory metadata is compliant with the [Dublin Core Cross-Domain Attribute Set](https://www.dublincore.org/specifications/dublin-core/cross-domain-attribute/) metadata standard, but we use different formatting. We offer simple re-formatting from the richer DataCite to Dublin Core for interoperability with a wider set of data sources.
- [x] We use all [mandatory](https://support.datacite.org/docs/datacite-metadata-schema-v44-mandatory-properties) DataCite metadata fields, all the [the recommended and optional](https://support.datacite.org/docs/datacite-metadata-schema-v44-recommended-and-optional-properties) ones. 
- [x] It complies with the tidy data principles.  

In other words: very easy to import into your databases, or join with other databases, and the information is easy to find.  Corrections, updates can automatically managed.


## What happened with the data before?


- [x] We are creating Codebooks that are following the SDMX statistical metadata codelists, and resemble the SMDX concepts used by international statistical agencies. (See more technical information [here](https://r.dataobservatory.eu/articles/codebook.html).)

Small organizations often cannot afford to have data engineers and data scientists on staff, and they employ analysts who work with Excel, OpenOffice, PowerBI, SPSS or Stata.  The problem with these applications is that they often require the user to manually adjust the data, with keyboard entries or mouse clicks.  Furthermore, they do not provide a precise logging of the data processing, manipulation history.
The manual data processing and manipulation is very error prone and makes the use of complex and high value resources, such as harmonized surveys or symmetric input-output tables, to name two important source we deal with, impossible to use.  The use of these high-value data sources often requires tens of thousands of data processing steps: no human can do it faultlessly.

What is even more problematic that simple applications for analysis do not provide a log of these manipulations’ steps: pulling over a column with the mouse, renaming a row, adding a zero to an empty cell. This makes senior supervisory oversight and external audit very costly. 

Our data comes with full history: all changes are visible, and we even open the code or algorithm that processed the raw data.  Your analysts can still use their favourite spreadsheet or statistical software application, but they can start from a clean, tidy dataset, with all data wrangling, currency and unit conversion, imputation and other low-priority but important tasks done and logged.
