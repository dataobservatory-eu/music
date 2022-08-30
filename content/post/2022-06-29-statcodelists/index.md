---
title:  "stacodelists: use standard, language-independent variable codes to help international data interoperability and machine reuse in R"
subtitle:  "An R data package with all the SDMX standard codelists"
date:  2022-06-29T08:12:00+01:00
lastmod:  2022-06-29T08:12:00+01:00
draft:  false

authors:  ["daniel_antal"]

doi: 10.5281/zenodo.6751783

tags:  
 - R
 - Metadata
 - SDMX
 - Codelists

summary:  "A new building block of our observatories went through code peer review and was released yesterday. The statcodelists R package aim to promote the  reuse and exchange of statistical information and related metadata with making the internationally standardized SDMX code lists available for the R user."

image:
  caption:  "Visit the documentation website of statcodelists on [statcodelists.dataobservatory.eu/](https://statcodelists.dataobservatory.eu/)."
  focal_point:  "Center"
  preview_only:  true

categories:
- R-bloggers
---
<td style="text-align: center;">{{< figure src="/img/blogposts_2022/statcodelists_website.png" caption="Visit the documentation website of statcodelists on [statcodelists.dataobservatory.eu/](https://statcodelists.dataobservatory.eu/)." numbered="false" >}}</td>

<!-- badges: start -->
[![dataobservatory](https://img.shields.io/badge/ecosystem-dataobservatory.eu-3EA135.svg)](https://dataobservatory.eu/)
<!-- badges: end -->

The goal of `statcodelists` is to promote the reuse and exchange of statistical information and related metadata with making the internationally standardized SDMX code lists available for the R user. SDMX – the [Statistical Data and Metadata eXchange](https://sdmx.org/) has been published as an ISO International Standard (ISO 17369). The metadata definitions, including the codelists are updated regularly according to the standard. The authoritative version of the code lists made available in this package is <https://sdmx.org/?page_id=3215/>. 

{{< spoiler text="Click to expand table of contents of the post" >}}
{{<toc>}}
{{< /spoiler >}}



## Purpose

Cross-domain concepts in the SDMX framework describe concepts relevant to many, if not all, statistical domains. SDMX recommends using these concepts whenever feasible in SDMX structures and messages to promote the reuse and exchange of statistical information and related metadata between organisations. 

Code lists are predefined sets of terms from which some statistical coded concepts take their values. SDMX cross-domain code lists are used to support cross-domain concepts. What are these cross-domain coded concepts?  

- Geographical codes, like `NL`:  the Netherlands in the [CL_AREA](https://statcodelists.dataobservatory.eu/reference/CL_AREA.html) code list.
- Standard industry codes `J631` for Data processing, hosting and related activities in Europe. ([NACE Rev 2](https://statcodelists.dataobservatory.eu/reference/CL_ACTIVITY_NACE2.html) in Europe, beware, it is `J592`in Australia and New Zealand, see [CL_ACTIVITY_ANZSIC06](https://statcodelists.dataobservatory.eu/reference/CL_ACTIVITY_ANZSIC06.html).)
- Occupations, like `OC2521` for `Database designers and administrators` in [CL_OCCUPATIONS](https://statcodelists.dataobservatory.eu/reference/CL_OCCUPATION.html)
- Time fomatting standards, like `CCYY` for annual data series in [CL_TIME_FORMAT](https://statcodelists.dataobservatory.eu/reference/CL_TIME_FORMAT.html).

Check out the available codlists on the [package homepage](https://statcodelists.dataobservatory.eu/reference/index.html).

The use of common code lists will help users to work even more efficiently, easing the maintenance of and reducing the need for mapping systems and interfaces delivering data and metadata to them. A very obvious advantage of using the code systems is that you can retrieve data from national sources indifferent of the natural language used in North Macedonia, Japan, the U.S. or the Netherlands. While the data labels may change to be locally human-readable, computers and geeks can read the codes and understand them immediately. Provided that they use the standard codes. 

Our data observatories are rolling out SDMX coding across all datasets to help data ingestion and interoperability, data findability and data reuse. `statcodelists` can help the use of standard SDMX codes in your R workflow--both for downloading data from statistical agencies and to produce publication-ready datasets that the rest of the world (and even APIs) will understand.

## Installation

You can install `statcodelists` from CRAN:

```
install.packages("statcodelists")
```

Further recommended code values for expressing general statistical concepts like `not applicable`, etc., can be found in section `Generic codes` of the [Guidelines for the creation and management of SDMX Cross-Domain Code Lists](https://sdmx.org/?page_id=4345).

For further codelists used by reliable statistical agency but not harmonized on SDMX level please consult the [SDMX Global Registry](https://registry.sdmx.org/) [Codelists](https://registry.sdmx.org/items/codelist.html) page.

The creator of this package is not affiliated with SDMX, and this package was has not been endorsed by SDMX.

## Code of Conduct

Please note that the `statcodelists` project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

