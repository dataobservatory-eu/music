---
title: "Another Step to bring our Digital Music Observatory Closer To Your Metropolitan Area"
subtitle: "Maping Regional Data, Maping Metadata Problems"
date:  2021-06-16T12:00:00
lastmod:  2021-06-16T12:00:00
doi: doi.org/10.5281

authors:  ["daniel_antal", "rOpenGov", "leo_lahti", "kasia_kulma"]

tags:  
 - Open data
 - Open science
 - Regional data
 - R
 - Small area statistics
 
links:
- icon: twitter
  icon_pack: fab
  name: "@DigitalMusicObs"
  url: https://twitter.com/DigitalMusicObs
- icon: code
  icon_pack: fas
  name: Code & Tutorials
  url: https://regions.dataobservatory.eu/
- icon: linkedin
  icon_pack: fab
  name: Digital Music Observatory
  url: https://www.linkedin.com/company/79286750/
- icon: mastodon
  icon_pack: fab
  name: "@digitalmusicobs@eupolicy.social"
  url: https://eupolicy.social/@digitalmusicobs/
- icon: person-booth
  icon_pack: fas
  name: Vote for The Hague Innovators Award Audience Prize
  url: ../post/2022-10-29_reprex-talk-to-all/
 
summary:  "Live music is the breadwinner of most music professionals, artists, technicians, and managers alike, and it is a very local business. To analyze the live music economy, and its connection with the recorded music business, we need to create indicators on regional, provincial, or metropolitan area level.  We just made another step to localize our Digital Music Observatory."

projects:  
 - OpenMuse

# Featured image
image:
  caption:  ""
  focal_point:  "Center"
  preview_only:  true

categories:
- R-bloggers

---

{{< figure src="/img/package_screenshots/regions_017_169.png" numbered="false" >}}

The new version of our [rOpenGov](https://ropengov.org/) R package
[regions](https://regions.dataobservatory.eu/) was released today on
CRAN. This package is one of the engines of our experimental open
data-as-service [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/), [Economy Data Observatory](https://economy.dataobservatory.eu/), [Digital Music Observatory](https://music.dataobservatory.eu/) prototypes, which aim to
place open data packages into open-source applications.

{{< spoiler text="Click to expand table of contents of the post" >}}
{{<toc>}}
{{< /spoiler >}}

In international comparison the use of nationally aggregated indicators
often have many disadvantages: they inhibit very different levels of
homogeneity, and data is often very limited in number of observations
for a cross-sectional analysis. When comparing European countries, a few
missing cases can limit the cross-section of countries to around 20
cases which disallows the use of many analytical methods. Working with
sub-national statistics has many advantages: the similarity of the
aggregation level and high number of observations can allow more precise
control of model parameters and errors, and the number of observations
grows from 20 to 200-300.


{{< figure src="/img/blogposts_2021/indicator_with_map.png" caption="The change from national to sub-national level comes with a huge data processing price: internal administrative boundaries, their names, codes codes change very frequently." numbered="true" >}}

Yet the change from national to sub-national level comes with a huge
data processing price. While national boundaries are relatively stable,
with only a handful of changes in each recent decade. The change of
national boundaries requires a more-or-less global consensus. But states
are free to change their internal administrative boundaries, and they do
it with large frequency. This means that the names, identification codes
and boundary definitions of sub-national regions change very frequently.
Joining data from different sources and different years can be very
difficult.

{{< figure src="/img/blogposts_2021/recoded_indicator_with_map.png" caption="Our [regions R package](https://regions.dataobservatory.eu/) helps the data processing, validation and imputation of sub-national, regional datasets and their coding." numbered="true" >}}

There are numerous advantages of switching from a national level of the
analysis to a sub-national level comes with a huge price in data
processing, validation and imputation, and the
[regions](https://regions.dataobservatory.eu/) package aims to help this
process.

You can review the problem, and the code that created the two map
comparisons, in the [Maping Regional Data, Maping Metadata
Problems](https://regions.dataobservatory.eu/articles/maping.html)
vignette article of the package. A more detailed problem description can
be found in [Working With Regional, Sub-National Statistical
Products](https://regions.dataobservatory.eu/articles/Regional_stats.html).

This package is an offspring of the
[eurostat](https://ropengov.github.io/eurostat/) package on
[rOpenGov](https://ropengov.github.io/). It started as a tool to
validate and re-code regional Eurostat statistics, but it aims to be a
general solution for all sub-national statistics. It will be developed
parallel with other rOpenGov packages.

## Get the Package

You can install the development version from
[GitHub](https://github.com/) with:

    devtools::install_github("rOpenGov/regions")

or the released version from CRAN:

    install.packages("regions")

You can review the complete package documentation on
[regions.dataobservaotry.eu](https://regions.dataobservatory.eu/). If
you find any problems with the code, please raise an issue on
[Github](https://github.com/rOpenGov/regions). Pull requests are welcome
if you agree with the [Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html)

If you use `regions` in your work, please cite the
package as:
Daniel Antal. (2021, June 16). regions (Version 0.1.7). CRAN. [http://doi.org/10.5281/zenodo.4965909]((https://doi.org/10.5281/zenodo.4965909))

Download the {{< staticref "/media/bibliography/cite-regions.bib" "newtab" >}}BibLaTeX entry{{< /staticref >}}.

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/regions)](https://cran.r-project.org/package=regions) 

## Join us

*Join our open collaboration Music Data Observatory team as a [data curator](/authors/curator), [developer](/authors/developer) or [business developer](/authors/team). More interested in antitrust, innovation policy or economic impact analysis? Try our [Economy Data Observatory](https://economy.dataobservatory.eu/#contributors) team! Or your interest lies more in climate change, mitigation or climate action? Check out our [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/#contributors) team!*

[![Follow DigitalMusicObs](https://img.shields.io/twitter/follow/DigitalMusicObs.svg?style=social)](https://twitter.com/intent/follow?screen_name=DigitalMusicObs)
