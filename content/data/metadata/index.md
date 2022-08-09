---
title: Metadata
summary: Uncut diamonds need to be cut, polished, and you have to make sure that they come from a legal source.
tags:
- metadata

date: "2021-06-01T11:00:00Z"
lastmod: "2021-07-08T09:10:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

authors:
- daniel_antal

image:
  caption: 
  focal_point: Smart
  preview_only: true

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


{{< figure src="/screenshots/observatory/EDO_API_metadata_table.png" caption="api.economy.dataobservatory.eu: processing metadata" numbered="true" >}}

## Descriptive Metadata

|   |   |   
|:--|:-:|
|Identifier | An unambiguous reference to the resource within a given context. (Dublin Core item), but several identifiders allowed, and we will use several of them.|
|Creator | The main researchers involved in producing the data, or the authors of the publication, in priority order. To supply multiple creators, repeat this property. (Extends the Dublin Core with multiple authors, and legal persons, and adds affiliation data.) |
|Title |A name given to the resource. Extends Dublin Core with alternative title, subtitle, translated Title, and other title(s). |
|Publisher | The name of the entity that holds, archives, publishes prints, distributes, releases, issues, or produces the resource. This property will be used to formulate the citation, so consider the prominence of the role. For software, use Publisher for the code repository. (Dublin Core item.) |
|Publication Year | The year when the data was or will be made publicly available. |
|Resource Type |We publish Datasets, Images, Report, and Data Papers. (Dublin Core item with controlled vocabulary.)|

### Recommended for discovery

The **Recommended** (R) properties are optional, but strongly recommended for interoperability.

|   |   |   
|:--|:-:|
|Subject| The topic of the resource. (Dublin Core item.)|
|Contributor | The institution or person responsible for collecting, managing, distributing, or otherwise contributing to the development of the resource. (Extends the Dublin Core with multiple authors, and legal persons, and adds affiliation data.) When applicable, we add Distributor (of the datasets and images), Contact Person, Data Collector, Data Curator, Data Manager, Hosting Institution, Producer (for images), Project Manager, Researcher, Research Group, Rightsholder, Sponsor, Supervisor |
|Date | A point or period of time associated with an event in the lifecycle of the resource, besides the Dublin Core minimum we add Collected, Created, Issued, Updated, and if necessary, Withdrawn dates to our datasets.|
|Related Identifier |An identifier or identifiers other than the primary Identifier applied to the resource being registered. |
|Rights | We give [SPDX License List](https://spdx.org/licenses/) standards rights description with URLs to the actual license. (Dublin Core item: Rights Management)|
|Description | Recommended for discovery.(Dublin Core item.) |
|GeoLocation | Similar to Dublin Core item Coverage |

- The `Subject` property: we need to set standard coding schemas for each observatory. 
- `Contributor` property:
     - `DataCurator` the curator of the dataset, who sets the mandatory properties.
     - `DataManager` the person who keeps the dataset up-to-date.
     - `ContactPerson` the person who can be contacted for reuse requests or bug reports.
- The `Date` property contains the following dates, which are set automatically by the [dataobservatory R package](https://r.dataobservatory.eu/):
     - `Updated` when the dataset was updated;
     - `EarliestObservation`, which the earliest, not backcasted, estimated or imputed observation. 
     - `LatestObservation`, which the earliest, not backcasted, estimated or imputed observation. 
     - `UpdatedatSource`, when the raw data source was last updated.
- The `GeoLocation` is automatically created by the [dataobservatory R package](https://r.dataobservatory.eu/).
- The `Description` property optional elements, and we adopted them as follows for the observatories:
    - The `Abstract` is a short, textual description; we try to automate its creation as much as a possible, but some curatorial input is necessary.
    - In the `TechnicalInfo` sub-field, we record automatically the `utils::sessionInfo()` for computational reproducability. This is automatically created by the [dataobservatory R package](https://r.dataobservatory.eu/).
    - In the `Other` sub-field, we record the keywords for structuring the observatory.

### Optional

The **Optional** (O) properties are optional and provide richer description. For findability they are not so important, but to create a web service, they are essential. In the mandatory and recommended fields, we are following other metadata standards and codelists, but in the optional fields we have to build up our own system for the observatories.

|   |   |   
|:--|:-:|
|Language | A language of the resource. (Dublin Core item.)|
|Alternative Identifier |An identifier or identifiers other than the primary Identifier applied to the resource being registered. |
|Size |We give the CSV, downloadable dataset size in bytes. |
|Format |We give file format information. We mainly use CSV and JSON, and occasionally rds and SPSS types. (Dublin Core item.) |
|Version | The version number of the resource.|
|Rights | We give [SPDX License List](https://spdx.org/licenses/) standards rights description with URLs to the actual license. (Dublin Core item: Rights Management)|
|Funding Reference |We provide the funding reference information when applicable. This is usually mandatory with public funds. |
|Related Item |We give information about our observatory partners' related research products, awards, grants (also Dublin Core item as Relation.) We particularly include source information when the dataset is derived from another resource (which is a Dublin Core item.)|

- In the `Language` we only use English (eng) at the moment.
- By default We do not use the `Alternative Identifier` property. We will do this when the same dataset will be used in several observatories.
- The `Size` property is measured in bytes for the CSV representation of the dataset. During creations, the software creates a temporary CSV file to check if the dataset has no writing problems, and measures the dataset size.
- The `Version` property needs further work. For a daily re-freshing API we need to find an applicable versioning system.
- The `Funding reference` will contain information for donors, sponsors, and co-financing partners.
- Our default setting for `Rights` is the [CC-BY-NC-SA-4.0](https://spdx.org/licenses/CC-BY-NC-SA-4.0.html) license and we provide an URI for the license document.
- In the `RelatedItem` we give information about:
     - The original (raw) data source.
     - Methodological bibilography reference, when needed.
     - The open-source statistical software code that processed the data.


## Administrative (Processing) Metadata


## Administrative Metadata

Like with diamonds, it is better to know the history of a dataset, too. Our administrative metadata contains codelists that follow the SXDX statistical metadata standards, and similarly strucutred information about the processing history of the dataset.

See for further reference [The codebook Class](https://r.dataobservatory.eu/articles/codebook.html).

|   |   |   
|:--|:-:|
|Observation Status| SDMX Code list for [Observation Status 2.2](https://sdmx.org/?sdmx_news=new-version-of-code-list-for-observation-status-version-2-2) (CL_OBS_STATUS), such as actual, missing, imputed, etc. values. |
|Method| If the value is estimated, we provide modelling information.|
|Unit| We provide the measurement unit of the data (when applicable.)|
|Frequency| [SDMX Code list for Frequency 2.1 (CL_FREQ)](https://sdmx.org/?page_id=3215/) frequency values |
|Codelist| Euros-SDMX Codelist entries for the observational units, such as sex, etc. |
|Imputation| SDMX Code list for Frequency 2.1 (CL_IMPUT_METH) imputation values |
|Estimation| The estimation methodology of data that we calculated, together with citation information and URI to the actual processing code |
|Related Item |We give information about the software code that processed the data (both Dublin Core and DataCite compliant.)|

See an example in the [The codebook Class](https://r.dataobservatory.eu/articles/codebook.html) article of the [dataobservatory R package](https://r.dataobservatory.eu/).
