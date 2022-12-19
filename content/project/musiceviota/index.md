---
# Project title.
title: "Music Eviota"
subtitle: "Sustainability reporting for music organizations" 

# Date this page was created.
date: 2022-06-09T09:40:00+01:00
lastmod: 2022-12-19T09:40:00+01:00

# Project summary to display on homepage.
summary: "We will help small music organizations in their sustainability reporting, where detail data and reporting standards are only available for greenhouse gas emissions."

# Tags: can be used for filtering projects.
tags: ["Music Eviota", "Eviota", "Sustainability", "European Green Deal", "MusicAIRE"]

# Optional external URL for project (replaces project detail page).
external_link: ""

# Special chars . . . —
# Slides (optional).
#   Otherwise, set `slides: ""`.
slides: ""

authors: ["admin", "musicaire", "greendeal", "music"]

links:
- icon: mastodon
  icon_pack: fab
  name: "@reprex@mastodon.nl"
  url: https://mastodon.nl/web/@reprex/
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/

# Links (optional).
url_pdf: ""
url_slides: ""
url_video: ""
url_code: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
image:
  caption: ""
  focal_point: "Center"
  preview_only: true
  
---
<td style="text-align: center;">{{< figure src="/img/eviota/Scope3_chart_16x9.jpg" caption="Reporting the impacts of the entire value chain." numbered="false" >}}</td>

The Eviota project aims to create sustainability reports connected to the financial accounts of companies, NGOs, and civil society actors.  The first phase concentrates on greenhouse gases and air pollutants.  We want to create reliable estimates of the carbon and other pollutants footprint of music-related (social) enterprises based on their spending (“connected financial and sustainability reporting”.)

Creating connected sustainability reports has many advantages.
- [x] It shows consumers, donors, and buyers that the company cares for sustainable growth.
- [x] The organization can ask for grants related to increasing sustainability.
- [x] In the EU, the company will be eligible for cheaper green loans, green insurance, and green investments.
- [x] Large corporations, including music event donors, may require their supply chain to produce credible sustainability metrics.

There are some difficulties that we want to overcome in this project.

- [ ] Connected financial and sustainability reports are complex, they require plenty of data, and mandatory only for 'large' corporations. Just like small companies can make 'simplified tax returns' and 'simplified financial reports', we aim to create a less complex and cheap `simplified, connected financial and sustainability report`.
- [ ] Due to the high complexity, they take a long time to create and are costly: the European Commission estimates their total cost at €10,000.

In Europe, there are a handful of large organizations present in the music industry. So, there is no regulatory push for music enterprises to engage in sustainability reporting. However, this means that they cannot benefit from the advantages above.

{{<toc>}}

## Our approach

Most sustainability calculators are very complex because they use many data inputs from the company. Our mission is to reduce the complexity; however, this would require plenty of experience to define the shortcuts.  We will compare all spending (upstream value chain or suppliers) and all income (downstream value chain or buyers) to the know spending of all similar organizations in your country in the comparison year. 

<td style="text-align: center;">{{< figure src="/img/eviota/supply_chain_comparison_barplot_roboto_16x9.png" caption="To reduce the data need, we only take into consideration cost/income groups that meet the _financial_ materiality treshold, i.e. 3% of your total costs or total business-to-business sales." numbered="false" >}}</td>

We offer free, manual calculation in the first phase to ensure we define these simplifications well. To reduce the time needed to collect data about your purchases and sales, we will rely on the "trial balance", because this is available in your accounting system (and can be exported by your accounting software.)

{{< spoiler text="Why the trial balance?" >}}

We start from a document that every company has, and does not require extra management time to prepare, the so-called `trial balance`. This is an accounting document that can be obtained from the company’s accountant.

- [x] No extra management time is needed: it is already recorded by every company's accountant. You or your accountant can export it and send it to us (or later upload it.)
- [x] It is not subjective.  It states exactly what you were spending on.
- [x] It is more or less standardized across Europe—and almost all countries of the world, with the exception of the U.S. and some other countries.
- [x] We need to use the same working document that your accountant uses to maintain an important objectivity criterion: connectivity. This way your annual report will be consistent, if you say in the financial part that you spend 1000 euro on energy, then we will calculate the greenhouse gas emissions based on KWh volume of the the energy that cost you 1000 euros.

{{< /spoiler >}}

This way we avoid a lot of data entry into the calculator. At this stage, you we do not offer an uploader, because we want to test manually different trial balances before automating the uploading process.

## How does it work?

In the future, we hope our calculator will ask the user to upload the trial balance to a secure location, answer a few questions, and get the sustainability report back. Because the trial balance has no strictly defined form (it differs between small, very small, and medium-sized companies, and country to country), we need to do some manual reporting to standardize this procedure.

We use the `trial balance` (see [examples](https://www.wallstreetmojo.com/trial-balance-examples/) of a trial balance), because that is a standard document that your accountant has about all your purchases and all your sales. 

<td style="text-align: center;">{{< figure src="/img/eviota/j58_comparison_treemap_alt_16x9.png" caption="We compare your company's supply purchases and sales with all similar companies in your country and industry for the comparison year. In this example, we compare the data of Hungarian publisher's GHG emissions using the purchases in its trial balance with the emissions of all Hungarian publishers (based on their data reported to the tax authorities) in 2020." numbered="false" >}}</td>

Currently your accountant creates two documents, which are binded together and published by law in one "book", your (Simplified) Annual Report. In Europe, all micro- and small companies create a Simplified Annual Report.
1. the annual (simplified) balance sheet
2. the annual (simplified) profit and loss statement

Using exactly the same data, i.e. the "trial balance", and adding sustainability data, we will create a third document:
3. The annual (simplified) sustainability report, which is a non-financial disclosure of the annual report.

{{< spoiler text="Process: From your data to the final report" >}}
1. We sign a non-disclosure agreement.
2. You send us your trial balance.
3. We create a first draft of your carbon footprint. We categorize your suppliers (costs) and buyers (income) into 64 categories for which we have reliable data. See [methodology](#methodology) below.
4. Most of our calculations are made with [iotables](https://iotables.dataobservatory.eu/), our scientific and open source software. We rely on open data from the [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/), which in turn processes reliable data of Eurostat and the European Environmental Agency in readily usable format. The use of open source reporting tools and open data helps keep our costs low.
4. We set up a short call with you and your accountant to make some clarifications.
5. We provide you the final report.
{{< /spoiler >}}

## What is the report?

The report is technically a non-financial disclosure (NFD) of your annual financial report, which currently consists of the balance sheet, the profit and loss statement. You can add an optional sustainability report as a third part. 

- [ ] The making of an NFD is not mandatory for small- and medium sized companies and NGOs that usually produce simplified financial reports. 
- [x] It is two paragraphs of factual text, accompanies with a table and chart about how much greenhouse gases (or other pollutants) are created by your activities. 
- [x] A sustainability report is a first step to factual sustainability management and avoiding greenwashing. When you know factually how your activities (including purchases from your suppliers) cause greenhouse gas emissions (or contribute to the gender paygap), you can devise steps to reduce your negative impact, or increase your positive impact.
- [x] We work with reliable expert advice so that you can act in a credible way, and make credible promises to your customers, your audience, your donors, granting agencies, bank, insurance, or investors.

## Methodology {#methodology}

- [x] We follow the CPA classification for your suppliers and corporate buyers. See [Statistical Classification of Products by Activity](https://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?TargetUrl=LST_NOM_DTL&StrNom=CPA_2008&StrLanguageCode=EN&IntPcKey=&StrLayoutCode=HIERARCHIC&IntCurrentPage=1) Some categories, like `B MINING AND QUARRYING` are aggregated, i.e. we cannot make a distintion among various mining activities.  In service industries this is not required.
   
- [x] We use the same data for comparators that states use to monitor the Paris Accord.  We use the categories of the System of National Accounts, which is harmonized on the level of the EU and the level of the UN. In 2022 we only work with EU and candidate countries that follow the EU version, and we'll adjust our software in 2023 for the rest of the world.

- [x] Our sustainability methodology is based on the [Global GHG Accounting & Reporting Standard for the Financial Industry](https://carbonaccountingfinancials.com/standard).

- [x] We follow the EFRAG’s Proposals for a Relevant and Dynamic EU Sustainability Reporting Standard Setting ([pdf download](https://www.efrag.org/Assets/Download?assetUrl=%2Fsites%2Fwebpublishing%2FSiteAssets%2FEFRAG%2520PTF-NFRS_MAIN_REPORT.pdf)) because this will be the basis of future, mandatory reporting standards in Europe. 

- [x] We will help small music organizations in their sustainability reporting, where detail data and reporting standards are only available for greenhouse gas emissions. 

The `Music Eviota` project is supported by the [MusicAIRE](https://musicaire.eu/).

## Open collaboration {#open-collaboration}
Our project is based on open collaboration.  Our proposal, provides us with resources to supply further music businesses, music civil society organizations and researchers with high-quality data (during the duration of the project for free.)  We are already looking for interested parties to put our data and research projects into use and validate their usability and quality in real-life policy or business development scenarios.

## Why are we developing this service? {#why}
The European Green Deal, which includes the proposed [Corporate Sustainability Reporting Directive](https://finance.ec.europa.eu/capital-markets-union-and-financial-markets/company-reporting-and-auditing/company-reporting/corporate-sustainability-reporting_en), and the sustainable finance package, aims to set the European economy on a permanent decarbonization and sustainability increasing path with adjusting the rules how economic activities are financed by bank loans, insurance, investments, and direct subsidies. From 2023, it will be cheaper to get loans, insurance, and other types of funding for organizations that can prove that they follow the environmental, social and
governance path set out in the Paris Agreement and other UN, OECD, and EU agreements.

<td style="text-align: center;">{{< figure src="/img/eviota/Eviota_EFRAG_requirements.jpg" caption="Requirements for connecting financial and sustainability reporting." numbered="false" >}}</td>

Correct and reliable sustainability management will come with many financial advantages and increased responsibility. The [European Financial Reporting Advisory Board](https://www.efrag.org/) is currently preparing the new combined financial and sustainability reporting standard that will be used in banks, insurance, investment, granting, and the large companies of Europe in their entire supply and purchaser chain. The European Commission estimates that compliance costs until the end of 2023 will amount to 4 billion euros, with reporting and auditing costs mounting 10,000 euros per organization. While music small and medium sized organizations (MSMEs) and limited liability civil society organizations (CSOs) will be exempted from mandatory sustainability management and audited reporting, they can still comply in a non-audited and voluntary way.

Our solution benefits the music MSMEs and CSOs in several ways:
- [x] It provides them with a size adequate sustainability management and reporting tool that helps first the management of greenhouse gas emissions, and later sustainable water use, pollution, biodiversity, and recycling in their entire value chain (for example, it flags environmental risks in the supply base of a festival including equipment rentals, transport, security firms, catering facilities, etc.) by connecting standard accounting documents of the MSME with SNA and EEA science based benchmarks.
- [x] Our system will be extendible to management of social sustainability. Our previous research shows that particularly the live music industry that needs a large workforce, suffers from underuse of, and discrimination of female workers in various technical and even managerial roles. Our system will be able to flag risks of gender paygap and related issues in the entire value chain and of course, provide good benchmarks for internal activities.

Our review of the environmental, social and governance risk management (ESG sustainability management) suggests that complying with ESG standards is not only a pre-requisite to get cheaper loans (less important) and cheaper insurance (very important in live music), but also a requirement by corporate sponsors of events, and even a large part of the audience. While some music organizations already provide sustainability reporting, they are not standardized and are less factual as they are not connected to accounting information at every point. Our solution aims to give much credibility to both the sustainability
reports and non-financial disclosures of the financial reports (which are not mandatory for MSMEs but increase their trustworthiness on an elective basis if they are included.)

<td style="text-align: center;">{{< figure src="/img/eviota/ESG_Google_Trends_16x9.jpg" caption="Growing interest for ESG in select countries." numbered="false" >}}</td>

## Future plans: Social Sustainability and Anti-Bribary {#future-plans}

<td style="text-align: center;">{{< figure src="/img/eviota/eviota_regulatory_goals.png" caption="In 2022/23 we focus on reporting GHG emissions and following the Paris Climate Agreement. We are making experiments on data sources to include other sustainability gols related to water use, biodiversity, social sustainability and anti-bribary." numbered="false" >}}</td>

## MusicAIRE Green Recovery in the Music Sector {#greenrecovery}
<td style="text-align: center;">{{< figure src="/img/logos/MusicAIRE_logo_black.png" caption="Co-funded by the European Union" numbered="false" >}}</td>

The objectives of the MusicAIRE GREEN recovery program is increasing the music sector’s environmental sustainability and ecological awareness with a view to greening the music industry, in particular live acts, festivals and touring, as well as supporting innovative start-ups aiming at decreasing the environmental footprint of online data storing and music distribution.

<td style="text-align: center;">{{< figure src="/img/logos/EN_Co-Funded_by_the_EU_POS.png" caption="Co-funded by the European Union" numbered="false" >}}</td>


