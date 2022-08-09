+++
title = "Feasibility Study On Promoting Slovak Music In Slovakia & Abroad"
date = '2021-03-25T11:00:00'
doi =  '10.5281/zenodo.6427514'
draft = false

authors = ["Daniel Antal", "Dáša Bulíková (translator)"]

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent

publication_types = ["4"]

# Abstract and optional shortened version.
abstract = "Why are the total market shares of Slovak music relatively low both on the domestic and the foreign markets? How can we measure the market share of the Slovak music in the domestic and foreign markets? We offer some answers and solution based on empirical research and with the creation of a database and an AI application."

# Is this a selected publication? (true/false)
featured = true

# Projects (optional).
projects = ["Listen Local"]

# Slides (optional).
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
tags = ["Slovakia", "Trustworthy AI", "Music recommender systems", "Music distribution", "Local content regulation"]

# Links (optional).
url_pdf =  "https://music.dataobservatory.eu/media/reports/Listen_Local_Feasibility_Study_2020_EN.pdf"
url_code = ''
url_dataset = ''
url_poster = ''
url_project = '/project/listen-local'
url_slides = ''
url_source = ''
url_video =  ''

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"
+++

Download the study {{% staticref "/media/reports/Listen_Local_Feasibility_Study_2020_SK.pdf" "newtab" %}}in Slovak{{% /staticref %}} or {{% staticref "/media/reports/Listen_Local_Feasibility_Study_2020_EN.pdf" "newtab" %}}in English{{% /staticref %}}.

In 2015, realizing the low visibility and income-generating potential of Slovak music, the legislation introduced an amendment to the broadcasting act to regulate local content in radiostreams. The Slovak content promoting policy was well-intended but not based on any impact assessment, and it reached its goal only partially.

The Slovak broadcasting quotas in comparison with other national quotas a very simple, and they are impossible to measure, which makes both compliance and enforcement very difficult. Radio editors do not get any help to find music that fits into the playlists and fulfill the quota obligations – in many cases, it is impossible for them to find out if a song actually meets the quota requirements. For the same reason, neither is enforcement possible.

Another deficiency of the broadcasting quotas is that because of its fuzzy target, it is not clear whom it tries to help, and it has few friends. It is unclear how performers, composers or Slovak music producers can benefit from the system. Furthermore, it only helps a few genres, and it decreases the chances of other Slovak music in instrumental and non-Slovak language genres (for example, classical, jazz, rock) to be heard.

{{< figure src="/img/streaming/mind_map_goal_setting.jpg" caption="What should a good local content policy (radio quota, recommendation system, streaming quota) achieve?" numbered="true" >}}

And at last, radio is losing its importance in music discovery. New generation find the music during their music discovery age on YouTube and digital streaming platforms. A Slovak content promoting policy that does not work on digital streaming platforms will be obsolete when radio content providers will switch to digital streaming in the foreseeable future.

**Our Feasibility Study follows the following logic:**
In the first chapter we introduce various music recommendation systems in the context of local content promotion polices, like local mandatory content quota regulations.

{{< figure src="/img/streaming/mind_map_recommendations.jpg" caption="We aimed to create a demo version of a utility-based, transparent, accountable recommendation system." numbered="true" >}}

In the second chapter, we consider the market-based or creative industry economy supporting policy goals, measurements, and potential support given to artists and producers.

We then turn in the third chapter to content-based local regulations promoting the use of the Slovak language or Slovak music content, irrespective of the performers and producers nationality, residence or ethnicity.

We introduce the idea of the **Slovak Music Database**, a comprehensive, mainly opt-in, opt-out database that of Slovak artists and Slovak music that should be supported by the local content regulation and other policies. We also create a Demo Slovak Music Database to understand the problem and scope of the creation of the comprehensive version.

The project website contains the [Demo Slovak Music Database](https://listenlocal.dataobservatory.eu/project/demo-sk-music-db/).

We also created a [Demo Recommendation System](https://listenlocal.dataobservatory.eu/project/demo-app/) *which is currently not online*. We explain here [why](https://listenlocal.dataobservatory.eu/post/2020-11-23-alternative-recommendations/).

{{< figure src="/img/streaming/listen_local_app_1.png" caption="Screenshot of the first verison of the demo app." numbered="true" >}}

## Research questions

* Why are the total market shares of Slovak music relatively low both on the domestic and the foreign markets?
* How can we measure the market share of the Slovak music in the domestic and foreign markets?
* How can we measure the value gap between what some media platforms, most particularly the biggest YouTube, does not pay out to the Slovak stakeholders within Slovakia?
* What is the interplay of the various definitions on market share and national quota targets?
* How ‘shadow-markets’ of home copying and unlicensed media platforms, such as YouTube impact market shares directly and national quotas indirectly?
* How can modern data science, predictive microeconomics and statistics help increase the market share of Slovak music in Slovakia and abroad?

We would like to continue this work in more depth in Slovakia, and include new countries and regions, for example, Estonia, Hungary, the Netherlands, Flanders and Wales in the next versions. We are also planning city-version. 

Thanks for the entire Reprex team who contributed to the English version:

- **Budai, Sándor**, programming and deployment
- **Dr. Emily H. Clarke**, musicologist
- **Stef Koenis**, musicologist, musician
- **Dr. Andrés Garcia Molina**, data scientist, musicologist, editor
- **Kátya Nagy**, music journalist, research assistant; 

and the Slovak version:
- **Dáša Bulíková**, musician, translator
- **Dominika Semaňáková**, musicologist, editor, layout.

Special thanks to [Tammy Nižňanska](https://dataandlyrics.com/post/2020-11-30-youniverse/).

## Project Website, Demo App

[Listen Local](https://listenlocal.dataobservatory.eu/#about) is an open initiative for musicians and music organizations to create new, open AI applications that make locally relevant music visible online and offline. Listen Slovak is our first demonstration project, accompanied with a Feasibility Study. It was created jointly with the Slovak Performing Rights Society, and with the support of the Slovak Arts Council and Consolidated Independent, a music distributor company for independent labels and artist. Our aim was to understand why some Slovak music cannot be heard on radio and on streaming platforms, and to create a database and a demo application that makes that music discoverable.
