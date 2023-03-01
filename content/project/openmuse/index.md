---
title: OpenMuse Consortium
subtitle: We are looking for end-users and dissemination partners to test our data and visualization products
summary: "OpenMuse brings together music industry stakeholders and researchers from 12 European countries. Our partners represent the diversity of the industry, as well as the shared need to find financially, socially, and environmentally sustainable policy and business models in multiple, sometimes-fragmented streams (e.g., live music, composers/publishers, and recordings with producers and performers)."
date: 2021-05-06T17:52:00
lastmod: 2021-08-21T18:52:00

external_link: ""
image:
  caption: ""
  focal_point: Center
  preview_only:  true
  
links:
- icon: twitter
  icon_pack: fab
  name: OpenMuse on "@DigitalMusicObs"
  url: https://twitter.com/DigitalMusicObs
slides: ""

tags:
- OpenMuse
- Digital Music Observatory

url_code: ""
url_pdf: "https://reprex.nl/documnets/DMO_Horizon_Europe_Invitation_2022_03_20.pdf"
url_slides: ""
url_video: ""
---


**OpenMuse** brings together music industry stakeholders and researchers from 12 European countries. Our partners represent the diversity of the industry, as well as the shared need to find financially, socially, and environmentally sustainable policy and business models in multiple, sometimes-fragmented streams (e.g., live music, composers/publishers, and recordings with producers and performers). 


<td style="text-align: center;">{{< figure src="/blogposts_2022/OpenMuse_logos_20220921.png" caption="" numbered="false" >}}</td>

Good policies require supporting evidence, and good business planning and copyright exploitation require high-quality data. `OpenMuse` will provide such data through novel, open-source tools that leverage automation to enable transfer to nearly any European market. We will disseminate our data via “live policy documents” and visualisations hosted on our Open Music Observatory, which automatically update when data sources are refreshed. This will set a concrete precedent and a clear path towards a more competitive, fair, and sustainable European music ecosystem.

## Open collaboration
Our project is based on open collaboration.  Our Horizon Europe grant will provide us with resources to supply further music businesses, music civil society organizations and researchers with high-quality data (during the duration of the project for free.)  We are already looking for interested parties to put our data and research projects into use and validate their usability and quality in real-life policy or business development scenarios.

{{< toc >}}

## Ambition

OpenMuse aims to contribute to the aim of creating a decentralised European intelligence hub where centralised data collection and analysis have failed in the music industry during the past 20 years. 

We envision the Open Data Observatory as a decentralised, complementary service to the ESSnet system (Eurostat and the national statistics offices) and the planned, centralised European Music Observatory (EMO). The Open Data Observatory will be an important supplier of the planned EMO, furnishing it with statistical products (datasets, visualisations), employing similar quality controls (though replacing official quality control with scientific quality control) and providing a high level of service where official and centralised solutions have failed. We plan to implement the Open Data Observatory as an open-source, public-facing solution working in synergy with the EMO. In the event that the EMO does not get created, or it fails, the Open Data Observatory will be positioned to serve many of the same needs.

Our ambition is to create [an ecosystem of statistical software](/#releases) that is interoperable with the systems of ESSnet via the widely-used R statistical environment. On the basis of this ecosystem, we are planning a complementary, decentralised music data and intelligence hub that is complementary to both the centralised functions of the future EMO and the ESSnet. 

This intelligence hub, the Open Data Observatory, has a service level similar to that of the Eurostat Rest API (high-quality data and visualisation products with various statistical quality control available in a Rest API meeting Dublin Core, DataCite, and SDMX interoperability standards). Furthermore, to syncronize real time with the worlds knowledge hubs, we want to offer web 3.0 (semantic web) capabilities and place our resources on music knowledge graphs.

In addition, the Open Data Observatory will fill the gaps in the offering provided by Eurostat and the ESSnet network,due to their non-music specific mandate and cost/benefit analysis.

The Open Data Observatory is partly a statistical software service provider that maintains a software ecosystem (developed in WP4), and partly a solution provider that makes the reproducible open policy analysis method available for various end-user groups represented in our Consortium and beyond. It will create reproducible “[smart policy documents](/apps/smart-policy-documents/)” that can be transferred from one country to another, or scaled up from one country to a group of countries or even the entire European Union, and recast with little effort after the inception of new data every year, due to their very high level of data/output standardisation and interoperability. Instead of creating large budget, ad-hoc valuation reports, these reports, with their automatic data harvesting and processing, can be recast annually with little further investment, or they can be transferred from Hungary to Bulgaria, from Slovakia to Lithuania or even Ukraine, as we plan to showcase.

Having reviewed more than 60 data observatories (in domains such as the audiovisual industry, research on homelessness, alternative fuels, etc.), Reprex started the validation of such a decentralised observatory in the Yes!Deflt AI+Blockchain Lab, the world’s 2nd ranked university-backed incubator. Reprex identified a competetive advantage in leveragingopen knowledge management—distinguishing it from most existing data observatories—and further developed this approach into a working prototype in the [JUMP European Music Market Accelerator](https://reprex.nl/post/2021-12-02-dmo-jump/). Building on the assets and know-how acquired through the geographically-limited results of [CEEMID](/project/ceemid/), Reprex has proven to be able to provide high value services in new areas and territories, one example being the recast of the UK’s streaming policy (Hesmondhalgh et al., 2021).

<td style="text-align: center;">{{< figure src="reports/ceereport_2020/frontcover_wide.jpg" caption="A 12-country [comparative study](/publication/ceereport_2020/) created with survey recycling, data harmonization and other advanced techniques." numbered="false" >}}</td>


## Methodological innovation

The Level 3 version of the Open Policy Analysis (OPA) Guidelines gives practical guidance on how to improve the transparency and replicability of policy-making work with a scientific underpinning (BITSS, 2019).

<td style="text-align: center;">{{< figure src="/blogposts_2022/OPA_main_figure_with_source.png" caption="" numbered="false" >}}</td>

The OPA guidelines go farther than current Horizon Europe recommendations, subjecting policy research and deliberation to standards as rigorous as those used in e.g. open-source software development and open science peer review. The guidelines consist of three layers: open materials (i.e., the evidence considered in policy); open analysis (the analytical procedures to which the evidence is subject), and open output (the indicators, recommendations, etc. derived from the analysis). Each level must be fully replicable: e.g., all file structures must be standardized, all data rendered open and labelled, all methods and code open-source, and all outputs traceable to the materials and methods used to reach them. Establishing a clear link between input and output by displaying how the output changes under different assumptions is a key methodological challenge.

<td style="text-align: center;">{{< figure src="/blogposts_2022/Eurostat_using_indicators_way_communicating_captioned.jpg" caption="We will bring novelty into the best practices of statistical indicator development laid out by Eurostat" numbered="false" >}}</td>


OpenMuse uses Open Policy Analysis in its creation of policy-relevant indicators. This entails the development of indicator candidates through workshops with stakeholders and the selection of viable indicators through the unit-testing of data science and computer science, the peer-review of open-source scientific algorithm/software development, the methodological peer-review of science, and eventually user verification from music industry users. Because for each indicator we not only collect data, but write an open-source data collection program, our work is fully transparent and replicable. This means, for example, that beyond the project lifespan, policy researchers could run our open-source software and refresh our indicators automatically. We aim to meet or exceed Eurostat standards around data quality and usability. Our data are documented with SDMX compatible codebooks, and DublinCore and DataCite metadata, ensuring full interoperability. They are available in tidy format for easy importing, and in our Eurostat-like Rest API. Authoritative copies are furthermore placed automatically on Zenodo and OpenAIRE. The data analysis (statistical procedures, etc.) also remains open, per OPA, and goes through scientific peer review.

OpenMuse furthermore ensures that all materials, analyses, and outputs meet the FAIR principles enshrined in Horizon Europe and the EU’s open science agenda, and will be submitted as best practices to the Knowledge4Policy Portal horizontal knowledge areas on Evidence-Informed Policy Making, Composite Indicators, Modelling, and AI Watch. These efforts toward radical transparency will help ensure open deliberation and consensus-forming among stakeholders. Putting evidence-based policymaking into practice in music research, we will establish a precedent for its incorporation as a keystone of the social sciences and digital humanities more broadly.

**Open science and scientific software development**

Open Policy Analysis interlinks with the OpenMuse commitment to reproducible science and open scientific software, which are seen as cornerstones of evidence-based policymaking – and which are increasingly becoming not only best practices but requirements in EU-funded research and innovation actions. At the heart of open science are replicability and reproducibility. Whilst replicability (as new evidence comes to the surface, it corroborates earlier statements) has always been a requirement of scientific results, reproducibility is relatively novel in practice: it refers to the ability of an entire research process to be re-run easily by an independent auditor. This increases transparency and quality control.

This revolutionary functionality is made available through the iterative development of the UTU project rOpenGov, a sophisticated set of open-source data collection and analysis tools written in the programming language R (Lahti et al. 2017). Several rOpenGov tools were co-developed with REPREX specifically for use in the music industry. The current toolkit includes:

* [eurostat](https://ropengov.github.io/eurostat/), the headline product of rOpenGov, which provides reproducible access to the Eurostat data warehouse, containing more than 3000 users.
* [iotables](https://iotables.dataobservatory.eu/), which produces GVA, employment, tax, and greenhouse gas emissions indicators for the music industry and other industries using data from Eurostat and the European Environmental Agency, counting with several hundred users globally.
* [regions](https://regions.dataobservatory.eu/), which corrects NUTS boundary information and automatically corrects regional datasets, with more than 500 global users.
* [retroharmonize](https://retroharmonize.dataobservatory.eu/), which allows the recycling of surveys, and the execution of more efficient new surveys, has about 200 users globally.
* [spotifyr](https://www.rcharlie.com/spotifyr/), which wraps the Spotify API and allows access to streaming data, and is maintained by our Consortium members since mid-2021 (after the original developer joined Spotify); it has about 1500 music research users.
* [statcodelists](https://statcodelists.dataobservatory.eu/) will help your use of standardized statistical codelists, which allows to share or syncronize data in a natural language independent way.
* [dataset](https://dataset.dataobservatory.eu/) will create interoperable FAIR datasets that conform with the Statistical Data and Metadata Exchange and the W3C web standards, release your data in in open science repositories and place them on knowledge graphs.

Unlike Eurostat and many other open and proprietary databases, the [rOpenGov](/authors/ropengov/) tools use tidy data principles. It is often said that about 80% of data analysis is spent on the process of cleaning and preparing the data; the tidy principles are established to standardize, simplify, and speed up this process. Using rOpenGov tools allows difficult-to-read data to be reformatted as clean tables that can be imported with a click to Excel for business analysis, statistical software packages for scientific analysis and data visualization, and databases for automated display and uses. The tools have a proven record in CCSI research: _iotables_, for instance, was used by REPREX to calculate the direct and indirect gross-value added, employment, and effect of the Hungarian tax shelter for film production. _iotables_ were also used by [SOZA](/authors/soza/) and [Reprex](/authors/reprex/) to investigate various policy scenarios for the [Slovak music industry](/publication/slovak_music_industry_2019/). _regions_ were used by UVA in an analysis of regional patterns in [piracy](/publication/scholarly_pirate_libraries_2020/).

OpenMuse will further develop the rOpenGov tools into an open music data software ecosystem that does not require extensive programming skills to use. This software ecosystem will allow the creation of evidence-based “[live policy documents](apps/smart-policy-documents/)” that update automatically as the data sources they are based on are refreshed. It will also make the transfer of research to new sites or topics extremely efficient. For instance: if one were to create a live policy document for Hungary (as in our pilot project), one could reproduce the live policy document in Bulgaria with the same quality and format simply by running Bulgarian data through the backend code. This triple benefit of excellent quality control, comparability, and much-improved time and cost efficiency makes reproducibility a key element in our design for a highly scalable data-to-policy pipeline for European music ecosystems.

**Advanced data science and statistics**

OpenMuse uses advanced data science, and production-side statistical know-how, to access data that are currently unusable by the music industry. We focus on two sources: legally open, but hard-to-access data sources, and big data produced by streaming services.

With regard to legally open data: the price of music goods and services is surveyed by national statistical offices monthly (as components of calculating national inflation rates). Furthermore, high-quality and expensive survey data already exist on music participation (attendance, amateur practices, listening, etc.) via various pan-European surveys such as EU-SILC, ESS, Eurobarometer, and AES. It is possible to secure these datasets using the Open Data Directive; however, they are not often known to the music industry or even music researchers. 

<td style="text-align: center;">{{< figure src="/blogposts_2022/Eurostat_using_indicators_way_communicating_captioned.jpg" caption="We will bring novelty into the best practices of statistical indicator development laid out by Eurostat" numbered="false" >}}</td>

With regard to streaming data:  Our approach draws on SSSA and REPREX competence in quantitative finance methodology. The selectivity bias in streaming data accessible by EU music stakeholders is a problem analogous to the statistical characterization of the price movements, volumes, and return of illiquid, infrequently traded securities, or, symmetrically, in estimating duration models of high-frequency arrival process in discretized continuous time models (Bottazzi et al. 2020). A common-sense example of the application of finance methodology to track price and volume in complex markets with imperfect information is the Dow Jones Industrial Average, which gives accurate guidance on price movements and risk for an entire market, using special averaging and periodical rebalancing of only 30 share prices. Using similar statistical methods, we will identify and track the domestic and international performance of limited baskets of recordings/works that are representative of particular streaming market segments: e.g., Italian emerging artists or Slovak classical performers. This approach was piloted in CEEMID, which created price and volume indexes for 20 European countries to reveal why streaming revenue growth concentrates around the top ca. 1% of rights-holders (Antal, 2020a), and further used in UK policy work related to the parliamentary inquiry into streaming economics (Hesmondhalgh et al., 2021).

**Survey recycling**

National statistical offices currently collect the price of music goods and services monthly. Additionally, high-quality survey data exist on many aspects of cultural access and participation, including music use in general, and even zero-price use – which has no accounting trail, and is thus otherwise difficult to measure. However, these datasets generally require specialist software and competence to access and analyse. They also use numerous formats and labelling strategies. This means that a typical music industry business analyst without data science training cannot integrate them into a meaningful report. Finally, the use of different variables, surveying methods, question phrasings, and response options, among other factors across multiple surveys make comparative interpretations a challenging task. Lack of coordination often leads to redundancy and waste: for example, different entities conducting surveys on overlapping topics, but with incommensurable outputs. This means that despite spending hundreds of thousands of EUR on surveys, national and EU-level policymakers often lack access to reliable and consistent comparative data.

<td style="text-align: center;">{{< figure src="/blogposts_2022/difficulty_bills_levels.jpg" caption="OpenMuse refers to “survey recycling” to describe various practices related to the harmonisation of surveys with different formats and outputs; the statistical matching, integration, or fusion of survey-based data; and the re-use of effective prior survey methods and questions in new surveys." numbered="false" >}}</td>


The ability to “recycle” surveys is a crucial and often missing skill for music market, policy, and scientific research. An important contribution of CEEMID was the successful reuse of open cultural access and participation survey data for all European countries, leading to the creation of ex-ante harmonised, detailed cultural access and participation (CAP) surveys in Hungary, Slovakia, and Croatia. This will allow, for instance, the comparison of cultural access and participation live vs. online before, during, and after the COVID-19 pandemic, including differences between socio-demographic and values-based segments of the population.



## Data that we can offer
By providing continually updated data on five industry pillars – innovation, music and society, music economy, music diversity and circulation, and music policy – we will accurately capture the economic and social value created by the sector, as well as providing stakeholders with data-driven means of maximizing this value.
- [x] **For copyright and neighbouring rights-holders and their organizations**: Value of music, euro value of the value gap, private copying, privacy---we have data and make estimates with all known music value estimation techniques.
- [x]	**For live music organizations**: Pan-European audience surveys; demographic comparisons of all European audiences; attendance predictions, attendance profiling.
- [x] **For granting authorities**: we have the world's largest survey-based dataset on how musicians work and live; we create ex ante needs assessment and grants evaluation indicators and ex-post grant evaluation indicators.
- [x] **For labels and music publishers**: we make big data understandable; we create price and volume indexes of streaming markets; we tell you about price developments and selection probabilities in different cities and countries; we understand the biases of the Spotify and YouTube Algorithms; and we measure (meta)data problems and offer scalable solutions.
- [x] **For music export offices**: we measure domestic and foreign market shares in streaming; we create actionable key performance indicators; and we do geographical targeting.


The **OpenMuse** Consortium

## Service Development, Project Management, Coordination and Dissemination 

- [Reprex](/author/reprex/) is the originator of the `OpenMuse` project which builds on the achievements of the former CEEMID project, and provides leadership in WP Dissemination with building the Open Music Observatory, a full-fledged, open science-based statistical service that can complement the Eurostat Rest API and the future European Music Observatory on the basis of the Digital Music Observatory prototype validated in Yes!Delft AI+Blockchain Lab and the JUMP European Music Market Accelerator.
- [Sinus-Institut](/author/sinus-institute/), (DE) an innovative market- and policy research SME is the coordinator of the project, and provides leadership on WP Music, Society and Citizenship with promoting best, harmonized practices of the measurement of cultural access and participation.
- [Synyo](https://www.synyo.com/), (AT) an innovative research company is participating in the coordination and dissemination of the project.

## Business partners {#business-partners}
- [SOZA](https://music.dataobservatory.eu/author/soza/) (SK), the representative organization of Slovak composers and lyricists, and the global composer community within Slovakia, will develop an impact assessment with us on the promotion of the Slovak music in radios (with local content quotas) and streaming platforms, and assist partners in various diversity related actions. SOZA is a founding partner of the [CEEMID](https://music.dataobservatory.eu/usecase/ceemid/) project.
- [HearDis!](https://www.heardis.com/en/) (DE), a German innovative music tech company is participating in building uses case of uses of music that harmoniously fit into the local music ecosystems and do not colonize lucrative uses of in-store and other public performance.
- [Aloaded](https://music.dataobservatory.eu/author/aloaded/) (SE), a 100% independent Stockholm-based digital distributor is participating in the development of new streaming market transparency indexes. We will create stock-exchange like streaming price, volume indexes to increase the transparency and business development of small labels and self-released artists.
- [Artisjus](https://www.artisjus.hu/) (HU), the representative organization of Hungarian composers and lyricists, and the initiator of the [CEEMID](https://music.dataobservatory.eu/usecase/ceemid/) project, together with SOZA, will assist Musicautor to re-valuate the use of music in Bulgaria in a way that can be scaled to any European country, and try to improve probably the poorest markets revenues similarly to the good results of the former CEEMID in Hungary and Slovakia. 
- [Musicautor](https://music.dataobservatory.eu/author/musicautor-%D0%BC%D1%83%D0%B7%D0%B8%D0%BA%D0%B0%D1%83%D1%82%D0%BE%D1%80/) (BG), the representative sister organization of Bulgarian rightsholders,  will validate the valuation methodologies of our projects with putting them in use, trying to replicate the double-digit growth from Hungary and Slovakia.

## Civil Society & Social Enterprise partners

- [ICMP](https://music.us/supporters/icmp/) (Global, EU), the “global voice for music publishing,”, will be our partner to fill the data gaps identified by Feasibility Study on the Establishment of the European Music Observatory related to the publishing revenue stream of the European music business.
- [Music Innovation Hub](https://music.dataobservatory.eu/author/music-innovation-hub/) (IT), an Italian social enterprise, is validating our sustainability reporting tool.
- [Music Exchange Fund](https://music.dataobservatory.eu/author/mxf-muzikos-eksporto-fondas/) (LT), a Lithuanian NGO that helps the promotion of Lithuanian artists abroad, will utilize the trustworthy AI and data management system originally developed by SOZA and Reprex to build a similar system in Lithuania and Ukraine.
- [Music Export Ukraine](https://music.dataobservatory.eu/author/music-export-ukraine/) (UA), a Ukrainian NGO promoting the music export of Ukraine, will further develop the Ukraine Music Industry Databases and build a similar application to the Music Exchange Fund.

## Academic partners {#academic-partners}

- [Turku Data Science Group](https://datascience.utu.fi/) (FI)at the University of Turku will lead the WP Innovation and build an ecosystem of open source applications within the [rOpenGov](https://music.dataobservatory.eu/author/ropengov/) open collaboration platform with Reprex that enable the music industry to create a self-service, Open Music Observatory that will produce statistical products in a similar quality, form, and service level like the Eurostat Rest API. 
- [Institute for Information Law](https://music.dataobservatory.eu/author/institute-for-information-law/) (IViR) of the University of Amsterdam, will lead the WP Economy of Consortium, including scaleable, standardized valuations that can be placed in use anywhere in Europe, conduct research in the market value of metadata, and provide leadership in economic methodologies.
- [Sant'Anna School of Advanced Studies](https://music.dataobservatory.eu/author/scuola-superiore-santanna/) (IT) of the University of Pisa will lead the WP Diversity and provide leadership in creating methodologies, indicators and open policy recommendations that can support the circulation of European music and the measurement and promotion of local and national repertoires in broadcasting, streaming and retransmission.
- [University of Economics in  Bratislava](https://music.dataobservatory.eu/author/university-of-economics-in-bratislava/) (SK) will develop indicators and validate our results in a national policy setting.

## What Do We Offer To Scientific Partners? {#horizon-scientific-partners}

We provide exclusive scientific access to highly valuable quantitative datasets in music, particularly nationally representative audience surveys, nationally representative music creator surveys, and large music streaming data. We provide know-how and data science infrastructure that facilitates data collection via surveys or big data by utilizing pre-existing open science or open government sources.

<td style="text-align: center;">{{< figure src="/blogposts_2021/difficulty_bills_levels.jpg" caption="Compare nationally representative music audience, general population and music creator data." numbered="false" >}}</td>

We will provide researchers with data according to their needs, and make sure that their quantitative research will have the best scientific and policy impact. Our goal is to ensure our datasets meet higher quality standards than governmental statistics, and that they are the most findable open science resources in music globally.

{{% callout note %}}
See [Ensuring the Visibility and Accessibility of European Creative Content on the World Market](https://music.dataobservatory.eu/publication/european_visibilitiy_2021/) - [Music Streaming: Is It a Level Playing Field?](https://music.dataobservatory.eu/publication/music_level_playing_field_2021/) - [The Growth of the Hungarian Popular Music Repertoire](https://music.dataobservatory.eu/publication/made_in_hungary/) - [Can scholarly pirate libraries bridge the knowledge access gap?](https://reprex.nl/publication/scholarly_pirate_libraries_2020/) {{% /callout %}}

## What Do We Offer To Policy Partners? {#horizon-policy-partners}

We want to demonstrate that we apply world-class research and the best and most data available to solve policy problems. If you bring your policy problem into an open collaboration with our Digital Music Observatory, you can rely on the expertise of eminent researchers in the field of economics, law, royalty finance, statistics, and valuable data. We want to demonstrate that we can offer the best value for money in data. 

We believe that our offering is particularly valuable for music policy organizations who would like to be actively involved in the shaping of the future [Feasibility Study For The Establishment Of A European Music Observatory](https://music.dataobservatory.eu/post/2020-11-16-european-music-observatory-feasibility/). Our Digital Music Observatory already contains much of the data gaps identified by stakeholders.  We have 7 years of working experience in the music industry, and we are familiar with data sharing and data governance solutions that manage well the conflicts of interests and strategic worries of the industry.

For copyright and neighbouring rights-holders and their organizations we can create music (royalty/tariff) valuations, euro value of the value gap, private copying, privacy – we have data and make estimates with all known music value estimation techniques. For live music organizations: Pan-European audience surveys; demographic comparisons of all European audiences; attendance predictions, attendance profiling. For granting authorities ---we have the world's largest survey-based dataset on how musicians work and live; we create ex ante needs assessment and grants evaluation indicators and ex-post grant evaluation indicators. For music export offices we can measure domestic and foreign market shares in streaming; we create actionable key performance indicators; and we do geographical targeting.

<td style="text-align: center;">{{< figure src="/blogposts_2021/2021_10_18_MaMA_Pitch.jpg" caption="[Pitching](https://reprex.nl/talk/digital-music-observatory-on-the-mama-convention-2021/) for partnership with French stakeholders within the [JUMP European Music Market Accelerator](https://music.dataobservatory.eu/post/2021-12-02-dmo-jump/), where our Digital Music Observatory was further developed to meet the needs of European partners." numbered="false" >}} </td>

{{% callout note %}} See [Digital Creators' Earnings in the UK - An Empirical Analysis of Music Streaming Revenues and Their Distribution](https://music.dataobservatory.eu/publication/mce_empirical_streaming_2021/) - [Slovak Music Indsutry Report](https://music.dataobservatory.eu/publication/slovak_music_industry_2019/) - [Private Copying in Croatia](https://music.dataobservatory.eu/publication/private_copying_croatia_2019/) - [Hungarian Music Industry Report](https://music.dataobservatory.eu/post/2015-04-27-proart_report_15/)
{{% /callout %}}


## What Do We Offer To Industry Partners? {#horizon-business-partners}

Our observatory follows the agile open collaboration method from open-source software development, and it has a triangular approach.  We believe that data which is created by peer-reviewed, open Algorithms, and thus open for review from the business, policy and scientific community is the best addition to your business proprietary data.  By sharing data with us, we can build world-class KPIs that give you a competitive edge in the data-driven music industry.

For labels and music publishers: we make big data understandable; we create price and volume indexes of streaming markets; we tell you about price developments and selection probabilities in different cities and countries; we understand the biases of the Spotify and YouTube Algorithms; and we measure (meta)data problems and offer scalable solutions.

{{% callout note %}} See [Feasibility Study On Promoting Slovak Music In Slovakia & Abroad](https://music.dataobservatory.eu/publication/listen_local_2020/) - [Central European Music Industry Rerpot](https://music.dataobservatory.eu/publication/ceereport_2020/) - business confidential repertoire valuations - predictive modelling.
{{% /callout %}}

<td style="text-align: center;">{{< figure src="/blogposts_2021/medianvalue-1.png" caption="Our pioneering streaming volume and price [indexes](https://ceereport2020.ceemid.eu/market.html#ceemid-ci-volume-indexes) are similar in design to bond- and stock market indexes." numbered="false" >}}</td>

## Data Coverage {#data-coverage}

Our research project contributes to all of the expected outcomes of the
call. Our ambition is to develop an open science and open data service
which complements the existing statistical service of Eurostat. In
partnership with key music industry and policy partners, we are going to
fill approximately 41 data gaps within the policy context of *Music
Moves Europe*, as identified by the *Feasibility Study for a European
Music Observatory*, with about 120 high-value indicators. We will
**develop key performance indicators** for music businesses and **policy
indicators** to “better detect the performance of the European music
sector and its contribution to economic and social development, as well
as to sustainability.”

We believe that existing data availability is better than that described
in the *Feasibility study*. As stated in this final report, the 2019
Open Data Directive further extended the availability of re-usable
public sector information (PSI) with open science data. In PSI, open
government data, and open science data, there is a huge potential to
fill in the data gaps without new data collection—the fact that data can
be reused instead of being recollected is the main aim of the directive.
These open data sources are legally open but are not accessible without
further investment; our Consortium wants to make this investment, and
produce about 50% of all the data needs of the future European Music
Observatory.

The [Digital Music Observatory](https://music.dataobservatory.eu/),
which was called [CEEMID](https://reprex.nl/project/ceemid/) at the time
of the creation of the *Feasiblity Study*, has 7 years of experience in
filling in data gaps with open data. It has created metadata maps to
more than 1000 indicators, covering almost all of the data gaps in the
*Feasiblity Study*. We know where to locate data, and now we have to
invest in processing, validating, documenting, and making it available
for the European music sector.

## Pillar 1: Music Economy

In the case of `Pillar 1 – Music & Economy`, we are usually able to
locate the source of the data, and we have some experience in processing
the data and bringing it to light. We have mapped many perceived data
gaps to the various data harmonization projects of GESAC and CISAC, and
we will seek cooperation with these organizations and their members to
find a secure and voluntary way to retrieve the data.

In other cases, we will rely on on the 2019/1024/EU [Open Data
Directive]((https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32019L1024))
to access, process, document, and disseminate the data.

The only data gap that we do not intent do address is the “impact of the
non-profit sector”.

<table class=" lightable-classic lightable-striped" style="font-size: 14px; font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; font-weight: bold; font-size: 24px;" colspan="4">

## Pillar 1 - Music Economy 

</th>
</tr>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Topic

</th>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Description

</th>
</tr>
<tr>
<th style="text-align:center;">
pillar
</th>
<th style="text-align:center;">
problem
</th>
<th style="text-align:center;">
availability
</th>
<th style="text-align:center;">
feasibility
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Value of music sector
</td>
<td style="text-align:center;width: 20em; ">
One-off
</td>
<td style="text-align:center;width: 60em; ">
EY study on the cultural and creative industries (2015)
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Value of music sector
</td>
<td style="text-align:center;width: 20em; ">
One-off or one recast
</td>
<td style="text-align:center;width: 60em; ">
CEEMID studies on national music economies
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Employment
</td>
<td style="text-align:center;width: 20em; ">
One-off
</td>
<td style="text-align:center;width: 60em; ">
EY study on the cultural and creative industries (2015)
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Employment
</td>
<td style="text-align:center;width: 20em; ">
One-off or one recast
</td>
<td style="text-align:center;width: 60em; ">
CEEMID national music industry reports
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Employment
</td>
<td style="text-align:center;width: 20em; ">
Annual
</td>
<td style="text-align:center;width: 60em; ">
Eurostat, lacking granularity
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Employment
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Absence of granularity on the employment of the various sub-sectors, in
particular in defining the roles of the various sub-sectors and the
importance of the not-for-profit sector in terms of employment.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Employment
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
HU, SK pilot successful to add granularity.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Value of music sector
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No EU-level assessment since 2015
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Strucutre of the market
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Absence of pan-European data detailing the number of companies,
employees, revenues for the sector and the subsectors.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #007CBB !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
The impact of the not-forprofit sector on the overall economy of the
music sector
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No data available on the specific impact of the not-for-profit sector,
especially in the live music sub-sector
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Recorded music
</td>
<td style="text-align:center;width: 20em; ">
Subject to partnership with IFPI
</td>
<td style="text-align:center;width: 60em; ">
IFPI
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Authors and publisher’s stream
</td>
<td style="text-align:center;width: 20em; ">
CISAC partnership
</td>
<td style="text-align:center;width: 60em; ">
CISAC
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Authors and publisher’s stream
</td>
<td style="text-align:center;width: 20em; ">
GESAC
</td>
<td style="text-align:center;width: 60em; ">
GESAC
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Recorded music stream - performer rights
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No aggregated data on neighbouring rights collections Partner with
AEPO-ARTIS and SCAP.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music publishing
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No aggregated data on the music European music publishing business
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Synchronisation rights
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
IFPI data available on the recorded music side but not on the publishing
side.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Independent music companies
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No aggregated data on the independent music sector (value, number of
companies, employees, etc.)
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Live music
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Some data is compiled by Live DMA, ETEP or Yourope, but there is no
aggregated data on the pan-European live music sector listing the value
of the market, the number and size of venues and shows, number of
festivals, share of European artists, among other data points.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Exports
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No pan-European data on the export flows between EU countries and
outside the EU.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Exports
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Embedded cultural tourism export.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music retail
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Granular data on some countries via retail associations (UK, France,
Germany) but no pan-European aggregated data.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Financing of the music sector
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No aggregated data on how the sector is financed (from investment fund
to bank loans and subsidies).
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Live music regulation
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No aggregated information available on the various legal and tax systems
within the EU applied to the live music sector.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
1</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Copyright regulations and evolution of copyright regimes
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Although many copyright laws applicable in Europe originate from the
Commission, there are few instruments available to monitor the state of
copyright regulation across the EU
</td>
</tr>
</tbody>
</table>

## Pillar 2: Music Circulation & Diversity

We will address the music circulation problems with our WP big data.
Together with our leading statistical experts, data scientists, and
reproducible research experts we will create sampling techniques that
allow to make representative indicators from streaming data. Streaming
data is largely accessible, but not in a representative manner. Using
advanced statistical methodologies like inverse reverse sampling—which
is often used in quantitative finance to analyze large problems—we will
create representative data following our pioneering work made in the
Central European Music Industry Report and later the Digital Music
Creators’ Project initiated by the UK Intellectual Property Office.

{{< figure src="/blogposts_2022/mean_price_plot.png" caption="" numbered="false" >}}

<table class=" lightable-classic lightable-striped" style="font-size: 14px; font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; font-weight: bold; font-size: 24px;" colspan="4">

Pillar 2 - Circulation & Diversity {#pillar2}

</th>
</tr>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Topic

</th>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Description

</th>
</tr>
<tr>
<th style="text-align:center;">
pillar
</th>
<th style="text-align:center;">
problem
</th>
<th style="text-align:center;">
availability
</th>
<th style="text-align:center;">
feasibility
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
2</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Streaming activity - volumes
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Due to the huge volumes of streaming data and the difficulties of
accessing this data, monitoring streaming activity could be a challenge.
However, the recent announcement by ielsen that they are now providing a
global streaming chart, but also national streaming charts, should
provide EMO with a potential tool to monitor this activity.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
2</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Live music cross-border activity
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
At this stage there are no pan-European tools that allow for analysis of
the cross-border activity of European artists. Listings from Liveurope,
ETEP and other exchange programmes will be a good place to start, but
these are far from geographically comprehensive and it will be necessary
to build a tool to monitor the circulation of European artists.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
2</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Streaming activity - prices
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Due to the huge volumes of streaming data and the difficulties of
accessing this data, monitoring streaming activity could be a challenge.
However, the recent announcement by ielsen that they are now providing a
global streaming chart, but also national streaming charts, should
provide EMO with a potential tool to monitor this activity.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
2</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Streaming activity - exports
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Due to the huge volumes of streaming data and the difficulties of
accessing this data, monitoring streaming activity could be a challenge.
However, the recent announcement by ielsen that they are now providing a
global streaming chart, but also national streaming charts, should
provide EMO with a potential tool to monitor this activity.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
2</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Live music cross-border audiences
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
At this stage there are no pan-European tools that allow for analysis of
the cross-border activity of European artists. Listings from Liveurope,
ETEP and other exchange programmes will be a good place to start, but
these are far from geographically comprehensive and it will be necessary
to build a tool to monitor the circulation of European artists.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
2</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Live music cross-border revenues
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
At this stage there are no pan-European tools that allow for analysis of
the cross-border activity of European artists. Listings from Liveurope,
ETEP and other exchange programmes will be a good place to start, but
these are far from geographically comprehensive and it will be necessary
to build a tool to monitor the circulation of European artists.
</td>
</tr>
</tbody>
</table>

We will address diversity issues with recycled and harmonized surveys.

## Pillar 3: Music & Society

We will mainly rely on the integration of existing, but fragmented and
not well-formatted data, and existing, but not processed and not
published data to create pan-European indicators for the music and
society section.

<table class=" lightable-classic lightable-striped" style="font-size: 14px; font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; font-weight: bold; font-size: 24px;" colspan="4">

Pillar 3 - Music & Society

</th>
</tr>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Topic

</th>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Description

</th>
</tr>
<tr>
<th style="text-align:center;">
pillar
</th>
<th style="text-align:center;">
problem
</th>
<th style="text-align:center;">
availability
</th>
<th style="text-align:center;">
feasibility
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music schools and conservatories
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
National statistical institutes, government data
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music education - formal practices
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
National statistical institutes, government data, European Association
for Music in Schools.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music education - informal practices
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
The Feasibility Study did not address this, but in popular music,
informal learning practices are far-far more important. We will address
this issues.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Training schemes for music professionals
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Lack of European data on the state of training for music professionals
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Training schemes for artist
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Lack of European data on the state of training for artists.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music education
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Lack of European data on the state of music education.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Consumer patterns regarding piracy and its impact on the music sector
</td>
<td style="text-align:center;width: 20em; ">
Available
</td>
<td style="text-align:center;width: 60em; ">
Some countries like France with Hadopi have attempted to evaluate the
way consumers access illegally music while setting up educational
campaigns on piracy, similar to the UK initiative Get It Right.
Materials/studies are also provided by EUIPO.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
EU consumers and music
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No authoritative assessment of the relationship between consumers and
music at pan-European level
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Social networks and music
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No authoritative assessment of how European consumers interact with
music on social networks
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Consumer patterns regarding piracy and its impact on the music sector
</td>
<td style="text-align:center;width: 20em; ">
Available
</td>
<td style="text-align:center;width: 60em; ">
Limited pan-European data on the impact of piracy but also on the
motivations to consumer music content via illegal sources. EUIPO does
have some data on the economic cost of IPR infringement in the recorded
music industry.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #DB001C !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Scope of the not-for-profit sector in Europe
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No mapping of the not-for-profit music sector in Europe, in particular
in exposing new talent and forging social cohesion.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #FAE000 !important;font-size: 16px;">Pillar
3</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Social impact of music in communities
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Although there is some academic research available, there is no
co-ordination of research on the social impact of music in Europe.
</td>
</tr>
</tbody>
</table>


## Pillar 4: Music & Innovation 

1.  We will connect to several innovation topics in music by providing
    research, data, and evidence. Building on the work of the
    [Blockchain & Society](https://www.ivir.nl/projects/blockchain-society/) research
    project of our Consortium member, the Institute for Information Law
    [IViR](https://www.ivir.nl/) at the University of Amsterdam, we will
    address issues related to NFT and blockchain technologies in music.

2.  Connecting to the work of various music stakeholders in Finland, we
    will experiment with the safe data sharing of confidential data,
    avoiding the extreme pitfalls of ‘radical openness’ and ‘closed
    data’. With the University of Bologna, and eight years of experience
    in sensitive data sharing with the [Digital Music
    Observatory](https://music.dataobservatory.eu/) (formerly:
    [CEEMID](https://reprex.nl/project/ceemid/)), we will create various
    statistical methods to create anonymized and synthetic datasets that
    do not endanger business or private data.

3.  We are going to design indicators and carry out a landscape mapping
    with [Music Tech Europe](https://www.musictecheuropeacademy.eu/), a
    new organization that aims to become the representative of music
    startups and music ecosystems in the European Union.

<table class=" lightable-classic lightable-striped" style="font-size: 14px; font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; font-weight: bold; font-size: 24px;" colspan="4">

Pillar 4 - Music & Innovation

</th>
</tr>
<tr>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Topic

</th>
<th style="padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; text-decoration: underline; font-size: 18px;" colspan="2">

Description

</th>
</tr>
<tr>
<th style="text-align:center;">
pillar
</th>
<th style="text-align:center;">
problem
</th>
<th style="text-align:center;">
availability
</th>
<th style="text-align:center;">
feasibility
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #007CBB !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Several reports cover the evolution of music and tec
</td>
<td style="text-align:center;width: 20em; ">
Available
</td>
<td style="text-align:center;width: 60em; ">
Music Ally, Midia Research…
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Blockchain and music
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No authoritative assessment of the impact of Blockchain on the music
sector and of the EU-powered initiatives linking Blockchain and music.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #BAC615 !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Artificial intelligence, machine learning and music
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No authoritative assessment of the impact of AI and machine learning on
the music sector and of the EUpowered initiatives linking AI and music.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #00843A !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Future of streaming
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No authoritative assessment of the future development of streaming and
its impact on the EU music sector
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Digital revenues in the music sector and the relevant business models
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
In the UK the report ‘Dissecting the digital dollar’ commission by the
MMF to CMU, but no similar European study.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Mapping the flow of digital revenues in the music sector and the
relevant business models in Europe
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Digital distribution of music has introduced new complex business models
that are not always transparent.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #007CBB !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Music start-ups in the EU
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No authoritative mapping of start-ups involved in music at EU level.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #3EA135 !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
The impact of artists’ ‘do it yourself’ culture on the economy of the
sector
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
Although more artists are going to market with their music without the
traditional support of labels, there is no overview of how deep the
trend is, how it affects the music ecosystem or what policy frameworks
can or should support such activity.
</td>
</tr>
<tr>
<td style="text-align:center;width: 10em; font-family: monospace;">
<span
style="     color: white !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #DB001C !important;font-size: 16px;">Pillar
4</span>
</td>
<td style="text-align:center;width: 15em; font-family: monospace;">
Funding mechanisms for music
</td>
<td style="text-align:center;width: 20em; ">
Data gap
</td>
<td style="text-align:center;width: 60em; ">
No regular overview of the funding schemes in Europe relevant to the
music business.
</td>
</tr>
</tbody>
</table>





