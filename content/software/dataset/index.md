---
title: "dataset: Create Interoperable FAIR Datasets"
subtitle: "Publish your datasets with FAIR metadata in open science repositories and place them on knowledge graphs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Antal

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-08-11T00:00:00Z"
lastmod: "2022-08-11T09:00:00Z"
doi: "10.5281/zenodo.5006056"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: The Comprehensive R Archive Network
publication_short: In *CRAN*

abstract: The primary aim of dataset is create well-referenced, well-described, interoperable datasets from data.frames, tibbles or data.tables that translate well into the W3C DataSet definition within the Data Cube Vocabulary in a reproducible manner. The data cube model in itself is is originated in the Statistical Data and Metadata eXchange, and it is almost fully harmonzied with the Resource Description Framework (RDF), the standard model for data interchange on the web.

# Summary. An optional shortened abstract.
summary: Publish your datasets with FAIR metadata in open science repositories and place them on knowledge graphs

tags: 
 - Reproducible research
 - SDMX
 - W3C
 - semantic web

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/dataobservatory-eu/dataset/
- icon: book-open
  icon_pack: fas
  name: Documentation
  url: https://dataset.dataobservatory.eu/
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/DigitalMusicObs
- icon: linkedin
  icon_pack: fab
  name: Connect
  url: https://www.linkedin.com/company/79286750
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

doi: 10.5281/zenodo.6969683

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Digital Music Observatory

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## Interoperable, FAIR datasets

The primary aim of dataset is create well-referenced, well-described,
interoperable datasets from data.frames, tibbles or data.tables that
translate well into the W3C DataSet definition within the [Data Cube
Vocabulary](https://www.w3.org/TR/vocab-data-cube/) in a reproducible
manner. The data cube model in itself is is originated in the
[Statistical Data and Metadata eXchange](https://sdmx.org/), and it is
almost fully harmonzied with the Resource Description Framework (RDF),
the standard model for data interchange on the web[^1].

A mapping of R objects into these models has numerous advantages:

1.  Makes data importing easier and less error-prone;
2.  Leaves plenty of room for documentation automation, resulting in far
    better reusability and reproducability;
3.  The publication of results from R following the
    [FAIR](https://www.go-fair.org/fair-principles/) principles is far
    easier, making the work of the R user more findable, more
    accessible, more interoperable and more reusable by other users;
4.  Makes the placement into relational databases, semantic web
    applications, archives, repositories possible without time-consuming
    and costly data wrangling (See [From dataset To
    RDF](https://dataset.dataobservatory.eu/articles/RDF.html)).

Our package functions work with any structured R objects (data.fame,
data.table, tibble, or well-structured lists like json), however, the
best functionality is achieved by the (See [The dataset S3
Class](https://dataset.dataobservatory.eu/articles/dataset.html)), which
is inherited from `data.frame()`.

### Contact

For contact information, contributors, see the
[package](https://dataset.dataobservatory.eu/) homepage.

### Code of Conduct

Please note that the `dataset` project is released with a
[Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).
By contributing to this project, you agree to abide by its terms.


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

