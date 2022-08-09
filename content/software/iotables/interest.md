---
title: "iotables R package for working with symmetric input-output tables"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Antal

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-06-03"
lastmod: 2021-12-19T12:00:00
doi: "10.5281/zenodo.5791235"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: The Comprehensive R Archive Network
publication_short: In *CRAN*

abstract: The goal of iotables is to make allow a programmatic acces to the symmetric input-output tables of Eurostat. It creates multipliers, calculates direct, indirect and induced effects from European SIOT tables.

# Summary. An optional shortened abstract.
summary: The goal of iotables is to make allow a programmatic acces to the symmetric input-output tables of Eurostat. It creates multipliers, calculates direct, indirect and induced effects from European SIOT tables.

tags: []

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
  url: https://github.com/rOpenGov/iotables/
- icon: book-open
  icon_pack: fas
  name: Documentation
  url: https://iotables.dataobservatory.eu/
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/dataandlyrics
- icon: linkedin
  icon_pack: fab
  name: Connect
  url: https://www.linkedin.com/company/68855596/
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://iotables.dataobservatory.eu/'
url_slides: ''
url_source: 'http://rOpenGov/iotables/'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "iotables.dataobservatory.eu"
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<td style="text-align: center;">{{< figure src="/img/blogposts_2021/iotables_0_4_7.png" caption="Get started with  [iotables](https://iotables.dataobservatory.eu/index.html)." numbered="false" >}}</td>

[iotables](https://iotables.dataobservatory.eu/) processes all the symmetric input-output tables of the EU member states, and calculates direct, indirect and induced effects, multipliers for GVA, employment, taxation. These are important inputs into policy evaluation, business forecasting, or granting/development indicator design. 

Originally the package was developed to calculate the economic impact of the Hungarian film tax shelter and the impact of the music sector on the Slovak economy. (See [Slovak Music Industry Report](https://music.dataobservatory.eu/publication/slovak_music_industry_2019/)). From version 0.4.7. we include environmental impact assessment among the features, too.


{{% callout note %}}Do you want to develop input-output models for any European country to measure the direct and indirect green house gas impacts of policy actions?  Do you need well-formatted data on interindustry linkages or other relevant topics for sustainable economy or susitainable finance research?  Get in touch with us – we are happy to help and test our new software tool with data you need, and create high-quality, open datasets that are ready to use.{{% /callout %}}

## Get Started

* [Introduction to iotables](https://iotables.dataobservatory.eu/articles/intro.html) An overview of the reproducible workflow of importing data, preparing important analytical objects for input-output equations, and solving matrix equations. 

Introduction to iotables

## Use Case
Working with real-life Eurostat data - practical tips from downloading till analyzing input-output tables.
* [Working With Eurostat Data](https://iotables.dataobservatory.eu/articles/working_with_eurostat.html)
* [Environmental Impacts](https://iotables.dataobservatory.eu/articles/environmental_impact.html)

## Validation

Replication of known good input-output analysis for package testing and tutorials. See also Get Started.

* [United Kingdom Input-Output Analytical Tables](https://iotables.dataobservatory.eu/articles/united_kingdom_2010.html)
* [Eurostat Manual of Supply, Use and Input-Output Tables](https://iotables.dataobservatory.eu/articles/intro.html)


<td style="text-align: center;">{{< figure src="/img/blogposts_2021/iotables_0_4_7.png" caption="Get started with  [iotables](https://iotables.dataobservatory.eu/index.html)." numbered="false" >}}</td>

## Code of Conduct

Please note that the `iotables` project is released with a
[Contributor Code of
Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).
By contributing to this project, you agree to abide by its terms.


