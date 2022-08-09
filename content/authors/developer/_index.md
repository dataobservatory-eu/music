---
# Display name
title: New Developers
name: New Developers

# Username (this should match the folder name)
authors:
  - developer

# Is this the primary user of the site?
superuser: false

# Role/position
role: Future co-developer

# Organizations/Affiliations
organizations:
  - name: Your Affiliation
    url: ""

# Short bio (displayed in user profile at end of posts)
bio: We are looking for (open-source) collaborators that want to use their technical skillset to further our open data and reproducible research-based approach.

topics:
  - R programming language
  - Shiny applications
  - Open-source software
  - Open Data

education:
  courses:
    - course: MSc in Public Administration
      institution: Sample University University
      year: 2015
    - course: BSc in International Relations
      institution: Other University
      year: 2010

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: "#contact" # For a direct email link, use "mailto:test@example.org".
- icon: keybase
  icon_pack: fab
  link: https://keybase.io/team/reprexcommunity
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/DigitalMusicObs
- icon: github
  icon_pack: fab
  link: https://github.com/dataobservatory-eu

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - join us
  - developers
---

*Our observatory is currently technically maintained by [Reprex BV](https://reprex.nl/), an early stage Dutch-American data science startup specialized on open collaborations with open data and open-source data solutions.  We are looking for contributor, either as recognized, unpaid, open-source contributors, or as granted and paid contributors when funding available.*

## R developer(s) {#r-developer}

We are looking for intermediate or advanced R users with a passion for open data and open science for the maintenance of our CRAN-released R packages and the development of further packages. We are pursuing a hybrid model, providing the R community with open-source packages, and engaging in paid work that utilizes this software in commercial or academic environments.

Our ideal candidate(s) are

a) at least intermediate-level R programmers or possess domain-specific knowledge relevant to our packages, or

b) advanced in R programming and agnostic to actual packages

c) excited to maintain and develop one or more of our packages

All of our packages follow the modernization of the R language and are built on rlang and vctrs. All the packages use the tidyverse as a dependency, which creates a consistent user interface (i.e. dplyr, tidyr, tidyselect.)

### Packages

-[iotables](https://iotables.dataobservatory.eu/): an R package for reproducible input-output analysis, economic, and environmental impact assessment. The domain specific knowledge is input-output economics, multiplier analysis, and environmental impact analysis. A working knowledge of SNA or an interest in macro-finance is a plus. We develop this application within the rOpenGov community and the rOpenSci community. The application has various uses in banking, insurance, music industry, and policy design.

- [retroharmonize](https://retroharmonize.dataobservatory.eu/): an R package for retrospective survey harmonization and survey recycling. The domain specific knowledge is an interest in international, multi-language surveys, longitudinal surveys, and the reuse of survey data. We develop this application within the rOpenGov community and the rOpenSci community. The application has various uses in survey harmonization, data integration, and survey design. 

- [regions](https://regions.dataobservatory.eu/): an R package for adjusting sub-national boundaries for the making of regional statistics.  While the U.S. has relatively stable sub-national boundaries (the US postal codes), most nations change their internal boundaries very frequently. Currently, regions tracks these changes in Europe, but our package could and should be extended to all ISO-conforming sub-national boundaries globally.  An ideal domain-specific interest is geography, cartography, and/or small-area statistics. The package is currently not developed actively, but we expect it to be developed in a small-area statistics context, or for surveying withing a regional component.  

We are also contributing to a range of packages relevant for music analysis, open data access and open science data access and we are planning the release of new open source and non-open-source products.

We are looking for individual(s) who can resolve issues via Github. Time commitments are flexible and compensation is commensurate with experience and skill.

## Shiny developer {#shiny-developer}

We are looking for a contract-based Shiny developer who can create engaging, user-friendly multi-language Shiny interfaces to our R products. We are interested in working with candidates with experience in Shiny development and/or deployment skills, in particular, the ability to dockerize and deploy in the cloud. Currently we deploy on AWS and Netlify, but potentially we may need to deploy on other cloud servers.

Our Shiny applications have multiple users: 
- Music organizations and music researchers connected to our [Digital Music Observatory](https://music.dataobservatory.eu/)
- Sustainable finance, sustainable reporting, and climate mitigation policy experts related to our [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/)
- Antitrust experts, antitrust authorities, and merger analysts associated with our [Competition Data Observatory](https://competition.dataobservatory.eu/)
- Various creative industry stakeholders related to our [Cultural and Creative Sectors Industries Data Observatory](https://ccsi.dataobservatory.eu/), mainly related to book publishing and film production.
- Some of our applications are expected to be able to communicate with various Rest APIs, e.g.: the Eurostat and Spotify Rest APIs.

Our applications must work with several language; buttons, alternate texts, and descriptions must be parameterized and available for localization. The visual elements must follow simple visual structures and a unified colour palette.

Get in touch with us on [Keybase](https://keybase.io/team/reprexcommunity) or in [email](https://reprex.nl/#contact).
