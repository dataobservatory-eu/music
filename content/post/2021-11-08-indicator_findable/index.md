---
title: "How We Add Value to Public Data With Better Curation And Documentation?"
subtitle: ""
date: 2021-11-08T09:00:00
lastmod: 2021-11-10T09:19:00+01:00
draft: false

authors: ["daniel_antal"]

tags: ["Metadata", "FAIR principle", "Data curators"]

links:
- icon: twitter
  icon_pack: fab
  name: "@DigitalMusicObs"
  url: https://twitter.com/DigitalMusicObs
- icon: github
  icon_pack: fab
  name: Open Repositories & Code
  url: https://github.com/dataobservatory-eu
- icon: linkedin
  icon_pack: fab
  name: Digital Music Observatory
  url: https://www.linkedin.com/company/79286750/
- icon: mastodon
  icon_pack: fab
  name: "@digitalmusicobs@eupolicy.social"
  url: https://eupolicy.social/@digitalmusicobs/

summary: "Many people ask if we can really add value to free data that can be downloaded from the Internet by anybody. We do not only work with easy-to-download data, but we know that free, public data usually requires a lot of work to become really valuable. To start with, it is not always easy to find."

project: "OpenMuse"

# Featured image
image:
  # Caption (optional)
  caption: "Photo: [Jack Sloop](https://unsplash.com/photos/eYwn81sPkJ8)"


  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Center"


  preview_only: false

---

In this example, we show a simple indicator: the *Turnover in Radio Broadcasting Enterprises* in many European countries. This is an important demand driver in the [Music economy](https://music.dataobservatory.eu/#pillars) pillar of our Digital Music Observatory, and important indicator in our more general [Cultural & Creative Sectors and Industries Observatory](https://ccsi.dataobservatory.eu/).

This dataset comes from a public datasource, the data warehouse of the
European statistical agency, Eurostat. Yet it is not trivial to use:
unless you are familiar with national accounts, you will not find [this
dataset](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=sbs_na_1a_se_r2&lang=en) on the Eurostat website. 

<td style="text-align: center;">{{< figure src="/blogposts_2021/eurostat_radio_broadcasting_turnover.png" caption="The data can be retrieved from the Annual detailed enterprise statistics for services NACE Rev.2 H-N and S95 Eurostat folder." numbered="false" >}}</td>

Our version of this statistical indicator is documented following the [FAIR principles](https://www.go-fair.org/fair-principles/): our data assets
are findable, accessible, interoperable, and reusable. While the
Eurostat data warehouse partly fulfills these important data quality
expectations, we can improve them significantly. And we can also
improve the dataset, too, as we will show in the next blogpost.

## Findable Data

Our data observatories add value by curating the data – we bring this
indicator to light with a more descriptive name, and we place it in
context with our *Digital Music Observatory* and [Cultural & Creative Sectors and Industries Observatory](https://ccsi.dataobservatory.eu/).
While many people may need this dataset in the creative sectors, or
among cultural policy designers, most of them have no training in working with
national accounts, which imply scrutinizing accounting records that measure economic activity at a national level. Our curated data observatories bring together many available data around important domains. Our *Digital Music Observatory*, for example, aims to form an ecosystem of music data users and producers.


<td style="text-align: center;">{{< figure src="/blogposts_2021/zenodo_metadata_eurostat_radio_broadcasting_turnover.png" caption="We [added descriptive metadata](https://zenodo.org/record/5652113#.YYkVBWDMKUk) that help you find our data and match it with other relevant data sources." numbered="false" >}}</td>

We added descriptive metadata that help you find our data and match it
with other relevant data sources. For example, we add keywords and
standardized metadata identifiers from the Library of Congress Linked
Data Services, probably the world’s largest standardized knowledge
library description. This ensures that you can find relevant data
around the same key term ([radio broadcasting](https://id.loc.gov/authorities/subjects/sh85110448.html))
in addition to our turnover data. This allows connecting our dataset unambiguosly
with other information sources that use the same concept, but may be listed under
different keywords, such as *Radio–Broadcasting*, or *Radio industry and
trade*, or maybe *Hörfunkveranstalter* in German, or *Emitiranje
radijskog programa* in Croatian or *Actividades de radiodifusão* in
Portugese.

## Accessible Data

Our data is accessible in two forms: in csv tabular format (which can be
read with Excel, OpenOffice, Numbers, SPSS and many similar spreadsheet
or statistical applications) and in JSON for automated importing into
your databases. We can also provide our users with SQLite databases,
which are fully functional, single user relational databases.

Tidy datasets are easy to manipulate, model and visualize, and have a
specific structure: each variable is a column, each observation is a
row, and each type of observational unit is a table. This makes the data
easier to clean, and far more easier to use in a much wider range of
applications than the original data we used. In theory, this is a simple objective, 
yet we find that even governmental statistical agencies--and even scientific
publications--often publish untidy data. This poses a significant problem that implies
productivity loses: tidying data will require long hours of investment, and if 
a reproducible workflow is not used, data integrity can also be compromised: 
chances are that the process of tidying will overwrite, delete, or omit a data or a label.


<td style="text-align: center;">{{< figure src="/blogposts_2021/tidy-8.png" caption="[Tidy datasets](https://r4ds.had.co.nz/tidy-data.html) are easy to manipulate, model and visualize, and have a specific structure: each variable is a column, each observation is a row, and each type of observational unit is a table." numbered="false" >}}</td>


While the original data source, the Eurostat data warehouse is
accessible, too, we added value with bringing the data into a [tidy
format](https://www.jstatsoft.org/article/view/v059i10). Tidy data can
immediately be imported into a statistical application like SPSS or
STATA, or into your own database. It is immediately available for
plotting in Excel, OpenOffice or Numbers.

## Interoperability

Our data can be easily imported with, or joined with data from other internal or external sources.

<td style="text-align: center;">{{< figure src="/screenshots/observatory/DMO_API_metadata_table.png" caption="All our indicators come with standardized descriptive metadata, and statistical (processing) metadata. See our [API](https://api.music.dataobservatory.eu/database/metadata/) " numbered="false" >}}</td>

All our indicators come with standardized descriptive metadata,
following two important standards, the [Dublin Core](https://dublincore.org/) and
[DataCite](https://datacite.org/)–implementing not only the mandatory,
but the recommended descriptions, too. This will make it far easier to
connect the data with other data sources, e.g. turnover with the number of radio broadcasting enterprises or
radio stations within specific territories.

Our passion for documentation standards and best practices goes much further: our data uses [Statistical Data and Metadata eXchange](https://sdmx.org/?page_id=3215/) standardized codebooks, unit descriptions and other statistical and administrative metadata.


<td style="text-align: center;">{{< figure src="/img/reports/european_visbility_publication.png" caption="We participate in [scientific work](https://reprex.nl/publication/european_visibilitiy_2021/) related to data interoperability." numbered="false" >}}</td>

## Reuse

All our datasets come with standardized information about reusabililty.
We add citation, attribution data, and licensing terms. Most of our
datasets can be used without commercial restriction after acknowledging
the source, but we sometimes work with less permissible data licenses.

In the case presented here, we added further value to encourage re-use. In addition to tidying, we
significantly increased the usability of public data by handling
missing cases. This is the subject of our next blogpost.

{{% callout note %}}Are you a data user? Give us some feedback! Shall we do some further
automatic data enhancements with our datasets? Document with different
metadata? Link more information for business, policy, or academic use? Please 
give us any [feedback](https://reprex.nl/#contact)!{{% /callout %}}
