---
title: Open Data
summary: Many countries in the world allow access to a vast array of information,
    such as documents under freedom of information requests, statistics,
    datasets. In the European Union, most taxpayer financed data in
    government administration, transport, or meteorology, for example, can
    be usually re-used. More and more scientific output is expected to be
    reviewable and reproducible, which implies open access.

tags:
- open-data
- FOI
- PSI

date: "2021-05-16T00:00:00Z"
lastmod: "2021-06-25T15:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart
  preview_only: true


links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/EconDataObs
- icon: linkedin
  icon_pack: fab
  name: Connect
  url: https://www.linkedin.com/company/78562153/

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

Many countries in the world allow access to a vast array of information,
such as documents under freedom of information requests, statistics,
datasets. In the European Union, most taxpayer financed data in
government administration, transport, or meteorology, for example, can
be usually re-used. More and more scientific output is expected to be
reviewable and reproducible, which implies open access.

<table>
<tbody>
<tr class="odd">
<td style="text-align: center;">{{< figure src="/blogposts_2021/photo-1490004047268-5259045aa2b4.jpg" caption="[What’s the Problem with Open Data?](/data/open-gov/#open-data-problems)" numbered="false" >}}</td>
<td style="text-align: center;">{{< figure src="/blogposts_2021/photo-1590247813693-5541d1c609fd.jpg" caption="[How We Add Value?](/data/open-gov/#open-data-value-added)" numbered="false" >}}</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="even">
<td style="text-align: center;">{{< figure src="/blogposts_2021/photo-1533580909002-a2f298d005eb.jpg" caption="[Is There Value in It?](/data/open-gov/#is-there-value-left-in-open-data) </br>If it’s money on the street, why nobody’s picking it up?" numbered="false" >}}</td>
<td style="text-align: center;">{{< figure src="/blogposts_2021/photo-1605143185650-77944b152643.jpg" caption="[Datasets Should Work Together to Give Information](/data/open-gov/#data-integration)</br>Data is only potential information, raw and unprocessed." numbered="false" >}}</td>
</tr>
</tbody>
</table>

## What’s the Problem with Open Data? {#open-data-problems}

*“Data is stuff. It is raw, unprocessed, possibly even untouched by human
hands, unviewed by human eyes, un-thought-about by human minds.”* [1]

- Most open data cannot be just ["downloaded."](#open-data-faq)
- Often, you need to put more than \$100 value of [work](#is-there-value-left-in-open-data) into processing, validating, documenting a dataset that is worth \$100. But you can share this investment with our data observatories.
- Open data is almost always lacking of documentation, and no clear references to validate if the data is reliable or not corrupted. This is why we always [start](#open-data-value-added) with reprocessing and redocumenting. 

{{< figure src="/screenshots/observatory/observatory_collage_16x9_800.png" caption="Our review of about 80 EU, UN and OECD data observatories reveals that most of them do not use these organizations's open data - instead they use various, and often not well processed proprietary sources." numbered="false" >}}

Read more: [Open Data - The New Gold Without the
Rush](https://dataandlyrics.com/post/2021-06-18-gold-without-rush/)

## How We Add Value? {#open-data-value-added}

-   We believe that even such generally trusted data sources as Eurostat
    often need to be reprocessed, because various legal and political
    constraints do not allow the common European statistical services to
    provide optimal quality data – for example, on the regional and city
    levels.
-   With
    [rOpenGov](https://greendeal.dataobservatory.eu/authors/ropengov/)
    and other partners, we are creating open-source statistical software
    in R to re-process these heterogenous and low-quality data into tidy
    statistical indicators to automatically validate and document it.
-   Metadata is a potentially informative data record about a
    potentially informative dataset. We are carefully documenting and
    releasing administrative, processing, and descriptive metadata,
    following international metadata standards, to make our data easy to
    find and easy to use for data analysts.
-   We are automatically creating depositions and authoritative copies
    marked with an individual digital object identifier (DOI) to
    maintain data integrity.

## Is There Value in Open Data? {#is-there-value-left-in-open-data}

*A well-known story tells of a finance professor and a student who come across a $100 bill lying on the ground. As the student stops to pick it up, the professor says, “Don’t bother—if it were really a \$100 bill, it wouldn’t be there.”*

But this is not the case with open data.  Often, you need to put more than \$100 into processing, validating, documenting a dataset that is worth \$100.

In the EU, open data is governed by the [Directive on open data and the re-use of public sector information - in short: Open Data Directive (EU) 2019 / 1024](https://eur-lex.europa.eu/legal-content/EN/TXT/?qid=1561563110433&uri=CELEX:32019L1024). It entered into force on 16 July 2019. It replaces the [Public Sector Information Directive](https://eur-lex.europa.eu/legal-content/en/ALL/?uri=CELEX:32003L0098), also known as the *PSI Directive* which dated from 2003 and was subsequently amended in 2013.

**Open Data** is *potentially* useful data that can *potentially* replace costlier or hard to get data sources to build information. It is analogous to potential energy: work is required to release it. We build automated systems that reduce this work and increase the likelihood that open data will offer the *best value for money*.

-   Most open data is not publicy accessible, and available upon request. Our real curatorial advantage is that we know where it is and how to get this request processed.
-   Most European open data comes from tax authorities, meteorological
    offices, managers of transport infrastructure, and other
    governmental bodies whose data needs are very different from yours.
    Their data must be carefully evaluated, re-processed, and if
    necessary, imputed to be usable for your scientific, business or
    policy goals.
-   The use of open science data is problematic in different ways:
    usually understanding the data documentation requires
    domain-specific specialist knowledge. [Open science
    data](/data/open-science/) is even more scattered and difficult to
    access than technically open, but not public governmental data.

## From Datasets to Data Integration, Data to Information {#data-integration}

“Data is only potential information, raw and unprocessed, prior to
anyone actually being informed by it.” ^[2]

-   We are building simple databases and supporting APIs that release
    the data without restrictions, in a tidy format that is easy to join
    with other data, or easy to join into databases, together with
    standardized metadata.
    
{{< figure src="/slides/img/automated_observatory_value_chain.jpg" caption="Our service flow and value chain" numbered="false" >}}

## FAQ {#open-data-faq}

### Why Downloading Does Not Work?

-  Most open data is not available on the internet. 
- If it is available, it is not in a form that you can easily import into a spreadsheet application like Excel or OpenOffice, or into a statistical application like SPSS or STATA.
- Even the data quality of trusted web sources, like the Eurostat website, can be very low. Eurostat just publishes what it gets from governments, and often has no mandate to fix errors.  The data is full with missing information, and in the case of regional statistics, faulty region codes and region names that make matching your data or placing them on a map impossible.
- Adjusting euros with millions of euros, correctly translating dollars to euros, pounds to kilograms requires plenty of work. This is a very error-prone process when done by humans.

### Can Open Data be Used in Machine Learning and AI?

- Most public and open data sources have many missing observations; machine learning models usually cannot hanlde missingness. These points must be carefully imputed with approximations, which can be very challenging when the data has geographical dimension.
- Removing missing values makes samples extremely biased and your model will learn from omissions, not information.


## Photo Credits
*What's the Problem with Open Data?* illustration is a photo by [Cristina Gottardi](https://unsplash.com/photos/8hJQKRIQZMY)
*How We Add Value?* illustration is a photo by [Nana Smirnova](https://unsplash.com/photos/IEiAmhXehwE).
*Is There Value Left in It?* is a photo by [Imelda](https://unsplash.com/photos/GcnPjvqRL18)
*Datasets Should Work Together to Give Information* is a photo by [Lucas Santos](https://unsplash.com/photos/huRn8ECqADI)

## Footnote References

[1] Pomerantz, Jeffrey. 2021. “Metadata.” MIT Press essential knowledge
series. MIT Press. Cambridge, Massachusetts ; London, England : The MIT
Press, \[2015\]

[2] Pomerantz, Jeffrey. 2021. “Metadata.” MIT Press essential knowledge
series. MIT Press. Cambridge, Massachusetts ; London, England : The MIT
Press, \[2015\]


