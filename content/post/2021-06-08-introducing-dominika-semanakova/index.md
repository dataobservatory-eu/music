+++
title = "We Want Machine Learning Algorithms to Learn More About Slovak Music"
subtitle = "Introducing Our Data Curators"
date = 2021-06-08T08:00:00
lastmod = 2021-06-08T08:00:00
draft = false

authors = ["dominika_semanakova"]

tags = ["Open data", "Listen Local", "trustworthy AI", "culture policy",  "musicology", "Slovakia"]

summary = "The idea behind Listen Local is simple: we want machine learning Algorithms of Spotify, YouTube, or other services to learn more about Slovak music.  In order to make machines learn about Slovak music, we have to make machine-readable tables of Slovak music for AI learners"

projects = ["eu-datathon_2021", "Listen Local"]

# Featured image
[image]
  # Caption (optional)
  caption = "Dominika Semaňáková"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"

  # Show image only in page previews?
  preview_only = false

+++

**You were a member of the team that was behind the creation of the application Listen Local. Can you tell us more about this project?**

The goal of the Listen Local app is to recommend more local music of various genres like pop, rock, and jazz and classical music within the large digital platforms such as Spotify or YouTube. The current recommendation systems of these platforms never really take into account music that is coming from smaller countries like Slovakia. For example, Slovak musicians have to compete with the music from the whole world; therefore, Slovak music production does not have the opportunity to succeed in the competition of foreign music. Through the Listen Local application, listeners search for artists and bands based on their tastes and the city they are currently in. The demo version of the Listen Local connects to the listener's Spotify account, and based on the Listen Local Algorithms, it analyzes the listener's Spotify playlists and then recommends songs by local artists that he might like. It will help the listener to get to a broader range of Slovak music and at the same time has the potential to support local artists, bands, and ensembles to find audiences abroad.

**As a part of the Listen Local app, you helped curate the demo version of a comprehensive Slovak music database. What is its purpose, and what was the process of creation?** 

The idea behind Listen Local is simple: we want machine learning Algorithms of Spotify, YouTube, or other services to learn more about Slovak music.  In order to make machines learn about Slovak music, we have to make machine-readable tables of Slovak music for AI learners.

We decided to start building such a reference database and collect scattered data about artists to put them in one place for further analytical research. 

{{< figure src="/img/streaming/smdb_html_table.png" caption="See the first demo database [here](https://listenlocal.community/post/2020-12-17-demo-slovak-music-database/), and our earlier blogpost [here](/post/2021-04-27-smdb/)." numbered="true" >}}


We made this database by combining several steps. The first step was an online survey for individual artists, bands, and publishers. Through the form responses, we learned, for example, how artists identify their artwork, where they currently perform, or where they would like to perform in the future. 

The second step was to collect biographies of Czech, Slovak, and Czechoslovakian biographies programmatically from Wikipedia, together with some randomly selected artists from other countries, with a heavy emphasis on some small European nations, including the Visegrad countries, Belgium, Estonia, the Netherlands, and Switzerland, to see who is considered Slovak. 

**How do you attribute nationality or ethnicity to a song? And why do you do it?**

From a modern ethnomusicological point of view, defining “Slovakness” may seem elusive, but it is a very practical first step from a policy and regulatory point of view. If the legislation puts a mandatory “Slovak” radio quota in place, somebody has to know which music is “Slovak” and which is not.  Much of the data required to answer these questions is protected by GDPR data protection rules. For example, were they born in the territory of present Slovakia?  Do they live in Slovakia? Did they die in Slovakia?  The developer team used the Google Translate API to figure out if the Slovak language was used in the titles of the popular songs of these artists.

{{< figure src="/screenshots/listen_local/Youniverse_energy.png" caption="See the first version nof the [API](/post/2021-04-27-smdb/) can help detecting small country and gender biasis in Algorithms. See our blogpost on [what can go wrong with recommendations](post/2021-05-16-recommendation-outcomes/)." numbered="true" >}}

We eventually created two parts: in the opt-in, opt-out process, the artists freely choose their identity.  In the write-in process, where there is also an opt-out possibility for living artists, eventually, musicologists will have to decide whom the public, biographers, legislators subjectively believe to be Slovak. Eventually, as a Slovak musicologist and native speaker, I manually checked all entries of our demo database and tried to use my best intuition.

**What are the policy insights of the app?**

The original problem behind the Listen Local and the Feasibility study was a new law in Slovakia, which aims to promote “Slovak music” in the radio stations of the Slovak Republic. Many countries have such legislation in place, and they pose a lot of very difficult questions. What makes music Slovak? The artist who writes it or performs it? The place of release if it is recorded? The language of the lyrics? Some special music vibes? 

{{< figure src="/img/streaming/listen_local_SK_EN.png" caption="See our trustworthy AI-driven music export case study for [Slovakia](https://music.dataobservatory.eu/publication/listen_local_2020/)" numbered="true" >}}


And of course, how do we measure compliance with any mandatory targets set to reach a certain ‘ratio of Slovak content’?  We have shown that if we want to set market share targets, or we want to measure algorithmic biases; first we have to be able to define what we really want when we want more “Slovak music” in radio programs or streaming playlists.


**Can the app and the study contribute to the legislative process?**

The database and the Listen Local app offer several recommendations that can be useful within the legislative proposals and turn into meaningful actions to solve current  challenges in the music industry in various countries. 

Cultural policy makers or education policymakers may want to promote the values of cultural diversity and encourage young people to express themselves in their language of writing, composing, singing, and visual storytelling. 

{{< figure src="/img/streaming/listen_local_app_1.png" caption="Screenshot of the first verison of the demo app." numbered="true" >}}

In many European countries, education policies target young people to feel at home in the creative processes of their own culture. This is also the key to generate higher value-added jobs in culture, and to combat the effect of robotization, particularly in manufacturing industries such as car manufacturing or some mass retail services like banking. Competition authorities may also be concerned if a media platform or other entity uses its vertical power in the value chain to monopolize the end-market in radios or streaming platforms successfully and increase/decrease the competitiveness of certain types of music.

{{< figure src="/screenshots/observatory/dmo_and_zenodo.png" caption="Join our open collaboration Digital Music Observatory team as a [data curator](/authors/curator), [developer](/authors/developer) or [business developer](/authors/team), or share your data in our public repository [Digital Music Observatory on Zenodo](https://zenodo.org/communities/music_observatory/)" numbered="true" >}}

## Join us

*Join our open collaboration Music Data Observatory team as a [data curator](/authors/curator), [developer](/authors/developer) or [business developer](/authors/team). More interested in antitrust, innovation policy or economic impact analysis? Try our [Economy Data Observatory](https://economy.dataobservatory.eu/#contributors) team! Or your interest lies more in climate change, mitigation or climate action? Check out our [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/#contributors) team!*

## Read More on Data & Lyrics

- [Recommendation Systems: What can Go Wrong with the Algorithm?](https://dataandlyrics.com/post/2021-05-16-recommendation-outcomes/)
- [Upgrading the Slovak Music Database: New Data API, New Features](https://dataandlyrics.com/post/2021-04-27-smdb/)
- [Working With Localities and Location Tags](https://dataandlyrics.com/post/2021-04-14-bandcamp-librarian-2/)
- [Feasibility Study On Promoting Slovak Music In Slovakia & Abroad](https://dataandlyrics.com/post/2021-03-25-listen-slovak/)
- [Listen Local: Why We Need Alternative Recommendation Systems](https://dataandlyrics.com/post/2020-12-15-alternative-recommendations/)
- [The Racist Music Algorithm](https://dataandlyrics.com/post/2020-10-30-racist-algorithm/)
