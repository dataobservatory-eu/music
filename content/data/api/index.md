---
title: Data API
summary: Get data from the Competition Data Observatory via our API
tags:
- api
date: "2021-06-01T11:00:00Z"
lastmod: "2021-07-07T11:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

authors:
- daniel_antal
- botond_vitos

image:
  caption: 
  focal_point: Smart
  preview_only: true

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/EconDataObs
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Our observatory has a new data API which allows access to our daily refreshing open data. You can access the API via [api.economy.dataobservatory.eu](http://api.economy.dataobservatory.eu/) (*apologies for the ugly, temporary subdomain masking!*).

All the data and the metadata are available as open data, without database use restrictions, under the [ODbL](https://opendatacommons.org/licenses/odbl/) license. However, the metadata contents are not finalized yet. We are currently working on a solution that applies the [FAIR Guiding Principles for scientific data management and stewardship](http://www.nature.com/articles/sdata201618), and fulfills the mandatory requirements of the Dublic Core metadata standards and at the same time the [mandatory requirements](https://support.datacite.org/docs/datacite-metadata-schema-v44-mandatory-properties), and most of the [recommended requirements](https://support.datacite.org/docs/datacite-metadata-schema-v44-recommended-and-optional-properties) of DataCite. These changes will be effective before 1 July 2021.

The **Competition Data Observatory** temporarily shares an API with the [Economy Data Observatory](https://economy.dataobservatory.eu/), which serves as an incubator for similar economy-oriented reproducible research resources. 


## Indicator table {#indicator-table}

The indicator table contains the actual values, and the various estimated/imputed values of the indicator, clearly marking missing values, too.

{{< figure src="/screenshots/observatory/EDO_API_indicator_table.png" caption="api.economy.dataobservatory.eu: indicator retrieval" numbered="true" >}}

You can get the data in [CSV](http://52.4.54.69/database/indicator.csv?_size=max) or [json](http://52.4.54.69/database/indicator.json) format, or write SQL querries. (Tutorials in SQL, R, Python will be posted shortly.)

## Description metadata table {#description-table}



## Processing Metadata table {#metadata-table}

The [metadata table](http://52.4.54.69/database/metadata) contains various data processing information, such as the first and last actual observation of the indicator, the number of approximated, forecasted, backcasted values, last update at source and in our system, and so on. 

{{< figure src="/screenshots/observatory/EDO_API_metadata_table.png" caption="api.economy.dataobservatory.eu: processing metadata" numbered="true" >}}


## Authoritative Copies 

[Greendeal Data Observatory on Zenodo](https://zenodo.org/communities/greendeal_observatory/)