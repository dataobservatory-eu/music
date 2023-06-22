---
# Project title.
title: "Open Policy Analysis"
subtitle: "Towards a competitive, fair and sustainable European music ecosystem"

# Date this page was created.
date: 2022-02-06T14:00:00
lastmod: 2024-03-25T08:41:00

# Project summary to display on homepage.
summary: "Open Policy Analysis is an approach to policy analysis wherein data, code, materials, and clear accounts of methodological decisions are made freely available to facilitate collaboration, discussion, and reuse."

# Tags: can be used for filtering projects.
tags: ["Open Policy Analysis", "Open Science", "Open Government"]

# Optional external URL for project (replaces project detail page).
external_link: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   E.g. `slides: "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides: ""`.
slides: ""

# Links (optional).
url_pdf: ""
url_slides: ""
url_video: ""
url_code: ""

# Custom links (optional).

links:
- icon: database
  icon_pack: fas
  name: Digital Music Observatory
  url: https://music.dataobservatory.eu/
- icon: database
  icon_pack: fas
  name: Digital Music Observatory
  url: 

# To use, add an image named `featured.jpg/png` to your project's folder. 
image:
  # Caption (optional)
  caption: ""
  focal_point: "Center"
---

Our ambition is to truly maximize transparency, (re)usability, scientific, policy, and business impact while embracing the best practices laid out in the the recommendations of the *Reproducibility of scientific results scoping report*, and the *Progress on Open Science: Towards a Shared Research Knowledge System* policy documents of the European Commission's DG Research & Innovation, as well as the best practices outlined  in the evidence-based *Knowledge4Policy* [K4P](https://knowledge4policy.ec.europa.eu/home_en) platform of the European Commission. For the first time in Europe, we will apply and contextualize the [Open Policy Analysis Guidelines](/resources/opa/), which grew out of several initiatives in research transparency with the aim of maximizing benefits in the context of the [Foundations for Evidence-based Policy Making Act of 2018](https://www.congress.gov/bill/115th-congress/house-bill/4174) initiative in the United States. We want to ensure that by relying not only on the best European practices, but considering trans-Atlantic experiences, we will make the most out of the opportunities offered by the European [Open Data Directive of 2019]((https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32019L1024)). This will not only mean rendering a dramatically increased data availability for our partners, as well as increased quality assurance and transparency in our work, but also immediate data access. Following the EU & US best practices we have already placed _before submitting our proposal_ our important software tools, methodologies, and sample data in the [Zenodo](https://zenodo.org/communities/music_observatory/) repository.

{{< spoiler text="What we promise in the Open Music Europe grant agreement?" >}}
The OPA guidelines go farther than current Horizon Europe recommendations, subjecting policy research and deliberation to standards as rigorous as those used in e.g. open-source software development and open science peer review. 

The guidelines consist of three layers: 
- [x] open materials (i.e., the evidence considered in policy)
- [x] open analysis (the analytical procedures to which the evidence is subject)
- [x] and open output (the indicators, recommendations, etc. derived from the analysis) 

Each level must be fully replicable: e.g., 
- [x] all file structures must be standardised, 
- [x] all data rendered open and labelled, 
- [x] all methods and code open-source, 
- [x] and all outputs traceable to the materials and methods used to reach them.

Establishing a clear link between input and output by displaying how the output changes under

{{< /spoiler >}}

## Open Materials (Level 3) {#open-materials}

{{< spoiler text="Compliance in practice" >}}
See the [Open materials](/post/2023-03-27_open_music_europe_opa/#open-materials)  part of our introductory blogpost.
{{< /spoiler >}}


6. **Standardise the file structure so that materials are organized in a way that is accessible to an informed reader**: all project components are organized in a selfcontained folder using a Standard File Structure (SFS), and a readme file is included.  See examples: 

7. **Label and document each input, including data, research, and guesswork**: list all inputs, and their sources, and provide links or detailed references. In practice, all our inputs are uploaded into the repositories, and they have included in the standard bibliography (.bib) files which make their citation automatic in use. 

8. **Ensure that code/spreadsheets are reproducible**: For code: Code is easily readable and possible to run with just one click. For spreadsheets, this level of compliance is not applicable. The Turku Data Science team and Reprex will assist all our research teams in making their data outputs reproducible.

9. **Use a version control strategy**: All team members use version control software and track changes in a shared project repository. All our deliverables are delivered in a version-controlled repository. 

Our commitment to the OPA is on level 3; WP leaders are requested to enforce compliance on this level. Reprex, Synyo and the Turku Data Science team will provide to WP teams assistance to make them compliant with level 3 if they can start working only on level 2 or level 1 based on bilateral agreements and training programs. 

## Open Analysis (Level 3) {#open-analysis}

{{< spoiler text="Compliance in practice" >}}
See the [Open analysis](/post/2023-03-27_open_music_europe_opa/#open-analysis)  part of our introductory blogpost.
{{< /spoiler >}}

**Provide clear accounts of all methodological procedures in a way that is easily interpreted by an informed reader**: Code is clearly documented into a dynamic document, or open notebook. No spreadsheets. [Synyo](/authors/synyo/) is tasked to make document templates that help compliance with this principle, and are integrated with popular word processors or presentation templates--see [Open Materials]() above. [Reprex](/authors/reprex/) and [Turku](/authors/utu/) assist all work package leaders to comply in content with this requirement.

**Share raw (or analytic) data and materials in a way that the analysis is reproducible with minimal effort.**  Analytic and raw data are made available through a trusted repository. We chose GitHub as a temporary repository where all our changes can be traced; and periodically we place these materials on Zenodo, where they are stored independently from our Consortium for a very long period. Detailed instructions are provided for accessing raw data that is proprietary or contains sensitive information.


Share an open report that includes clear accounts of all methodological procedures, data, and assumptions.





## Open Outputs

**Ensure unified output by defining the most appropriate format for the report before publishing, and justifying changes to format output across reports**: A detailed description of output is provided, including a sample output published pre-release of final results, using version control within and across reports.

[Synyo](/author/synyo) as an expert in scientific dissemination is in charge for making sure that you have all the templates, and materials that ensure compliance.  This is an iterative process: our work package researchers will try out their templates in practice with the 8 other principles, and ask for refinements for better compliance [here]().

**Establish a clear link between input and output by displaying how the output
changes under different assumptions.** An interactive tool allowing  for adjusted inputs is provided, and its underlying code shares the same key sections of code behind the analysis section.  [Reprex]() as an expert on reproducible research is assisting our research teams in the work packages to create these interactive policy reports. 


Our new software will continue to run in the cloud, depositing all of our findings---*Findable*, *Accessible*, *Interoperable* and *Reuseable* digital assets, including our well-designed and user-tested indicators in 41 data gap fields---into our [Digital Music Observatory](https://music.dataobservatory.eu/), which already hosts a [modern REST API](https://api.music.dataobservatory.eu/) similar to the Eurostat Rest API. *We are still adjusting this service in order to find a way to best implement SDMx and other data standards while maintaining ease of use. We anticipate enhanced usability by April 2022.*


<table class="table table-hover table-condensed" style="margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;">
Layer
</th>
<th style="text-align:left;">
Goal
</th>
<th style="text-align:left;">
Target
</th>
<th style="text-align:left;">
Example
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Open Output
</td>
<td style="text-align:left;">
Ensure unified output
</td>
<td style="text-align:left;">
We comply with the level 3 requirements and we will create a showcase
how to do this best following EU open science recommendations.
</td>
<td style="text-align:left;">
<a href="https://zenodo.org/record/5917742#.YflAK-rMLIU" style="     ">See
our example.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Output
</td>
<td style="text-align:left;">
Establish a clear link between input and output
</td>
<td style="text-align:left;">
We will produce more than 100 outputs, some only as indicators, and
others in form of policy analysis, we will comply with level 1,2,3 as
necessary.
</td>
<td style="text-align:left;">
<a href="https://music.dataobservatory.eu/publication/listen_local_2020/" style="     ">Our
affiliated music industry partners will create cases studies with
interactive tools (level 3). See our Slovak case study which came with a
Shiny App that analyzed music recommendations.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Analysis
</td>
<td style="text-align:left;">
Provide clear accounts of all methodological procedures in a way that is
easily interpreted by an informed reader.
</td>
<td style="text-align:left;">
We accomplish level 3 with placing the code in clearly documented. into
a dynamic document, or open notebook
</td>
<td style="text-align:left;">
<a href="https://music.dataobservatory.eu/post/2021-11-06-indicator_value_added/" style="     ">See
for example our blogpost on automatic forecasting for the music
industry.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Analysis
</td>
<td style="text-align:left;">
Share raw (or analytic) data and materials in a way that the analysis is
reproducible with minimal effort.
</td>
<td style="text-align:left;">
We will accomplish level 3 through trusted repositories following EU
recommendations. We will use the Zenodo repository developed by CERN and
the EU’s OpenAIRE project.
</td>
<td style="text-align:left;">
<a href="https://zenodo.org/communities/music_observatory/" style="     ">See
our solution on Zenodo.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Analysis
</td>
<td style="text-align:left;">
Share an open report that includes clear accounts of all methodological
procedures, data, and assumptions.
</td>
<td style="text-align:left;">
We would like to go beyond the level 3 requirements of the OPA with
using standardized documentation languages, such as SDMX statistical
metadata and its standardized codebooks, and comply with both Dublin
Core and DataCite extended, recommended standarized reporing.
</td>
<td style="text-align:left;">
<a href="https://music.dataobservatory.eu/publication/mce_empirical_streaming_2021/" style="     ">See
our example An Empirical Analysis of Music Streaming Revenues and Their
Distribution created for the UK Intellectual Property Office’s
evidence-based policy effort in music streaming.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Materials
</td>
<td style="text-align:left;">
Standardize the file structure so that materials are organized in a way
that is accessible to an informed reader.
</td>
<td style="text-align:left;">
We comply with the level 3 requirements. Our versioned controled output
is on Github.
</td>
<td style="text-align:left;">
<a href="https://github.com/dataobservatory-eu/music-competition" style="     ">See
an example on Github.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Materials
</td>
<td style="text-align:left;">
Label and document each input, including data, research, and guesswork.
</td>
<td style="text-align:left;">
We will go beyond level 3 requirements, because we want to make sure
that our labelling and documentation is interopreable, and we apply
various metadata standards for this purpose.
</td>
<td style="text-align:left;">
<a href="https://music.dataobservatory.eu/post/2021-11-08-indicator_findable/" style="     ">See
our example explaining how we document our datasets in our API.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Materials
</td>
<td style="text-align:left;">
Ensure that code/spreadsheets are reproducible.
</td>
<td style="text-align:left;">
All our spreadsheets are machine generated for the convenience of the
user who uses spreadsheet applications, but everything can be run with a
click, which accomplishes level 3, and maintains the convenience of
level 1-2 for the user. We go further with creating authoritative copies
of each dataset and visualization with DOIs. We also produce an API
which gives programatic or single table access to both the data and
standardized codebooks.
</td>
<td style="text-align:left;">
<a href="https://api.music.dataobservatory.eu/" style="     ">See our
API. All our datasets are described in detail on Zenodo and Figshare,
too.</a>
</td>
</tr>
<tr>
<td style="text-align:left;">
Open Materials
</td>
<td style="text-align:left;">
Use a version control strategy.
</td>
<td style="text-align:left;">
We use Git version control, and we employ various repositories and
project documentation tools on Github. These are linked with the Zenodo
EU open repository and our data API.
</td>
<td style="text-align:left;">
<a href="https://retroharmonize.dataobservatory.eu/articles/cap.html" style="     ">See
our example intergration.</a>
</td>
</tr>
</tbody>
</table>
