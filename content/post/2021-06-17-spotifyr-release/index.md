---
title: "New spotifyr R Package Release"
subtitle: "2.2.1: Thoroughly modernized exception handling, documentation, and some bug fixes"
date: 2021-06-17T08:10:00
lastmod: 2021-06-17T08:10:00
draft: false

authors: ["Daniel Antal"]

project:
 - Listen Local
 - OpenMuse

tags: ["Algorithms", "Digital Music Observatory", "Trustworthy AI", "Music recommendations", "Listen Local", "Spotify", "R"]

summary: "After a very thorough modernization of the package’s exception handling, documentation, and code dependencies that I did in the last week, the spotifyr package has passed again the peer-review standards and it is back on CRAN. The package is an excellent starting to point for R newbies to try their hands on musicology analysis with a few keystrokes. And of course, it is an essential part of the research infrastructure of musicology worldwide in far more advanced applications."

# Featured image
image:
  # Caption (optional)
  caption: ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Right"
  preview_only: true
  
categories:
- R-bloggers
---

{{< figure src="/screenshots/package/spotifyr_221.png" caption="The package is an excellent starting to point for R newbies to try their hands on musicology analysis with a few keystrokes. And of course, it is an essential part of the research infrastructure of musicology worldwide in far more advanced applications." numbered="true" >}}



_Engage with us on {{< staticref "https://www.linkedin.com/company/79286750/" "newtab" >}}{{< icon name="linkedin" pack="fab" >}}LinkedIn{{< /staticref >}} {{< staticref "https://twitter.com/DigitalMusicObs/" "newtab" >}}{{< icon name="twitter" pack="fab" >}}@DigitalMusicObs{{< /staticref >}} or check out our {{< staticref "https://zenodo.org/communities/music_observatory/" "newtab" >}}{{< icon name="database" pack="fas" >}}open data{{< /staticref >}} and {{< staticref "https://github.com/dataobservatory-eu/" "newtab" >}} {{< icon name="code" pack="fas" >}} open repositories, code, tutorials{{< /staticref >}}!_


I have been a very long-time user of Charlie Thomson’s [spotifyr R package](https://github.com/charlie86/spotifyr), which is probably the most used open-source music analytics software in the world.  It provides programmatic access to the Spotify Web API, which contains access to the former Echo Nest quantitative musicology engine.  

It is an essential part of the [Digital Music Observatory’s](https://music.dataobservatory.eu/) streaming analysis and our [Listen Local](https://listenlocal.community/) apps designed for our trustworthy AI experiments and independent artist services.  I am extremely proud to announce that after a very thorough modernization of the package’s exception handling, documentation, and code dependencies that I did in the last week, the package has passed again the peer-review standards and it is back on CRAN.

The package is an excellent starting to point for R newbies to try their hands on musicology analysis with a few keystrokes. And of course, it is an essential part of the research infrastructure of musicology worldwide in far more advanced applications.

{{< spoiler text="Contents of this blogpost" >}}
{{<toc>}}
{{< /spoiler >}}

## Getting Started

You should start with the [README](https://github.com/charlie86/spotifyr) and get your Spotify Web API access tokens to get started. 


### What Was the Beatles' Favorite Key?

``` r
library(spotifyr)
beatles <- get_artist_audio_features('the beatles')
```

``` r
library(dplyr)
library(purrr)
library(knitr)

beatles %>% 
    count(key_mode, sort: TRUE) %>% 
    head(5) %>% 
    kable()
```

| key\_mode |   n |
|:----------|----:|
| C major   | 104 |
| D major   |  98 |
| G major   |  82 |
| A major   |  76 |
| E major   |  62 |

### Get your most recently played tracks

``` r
library(lubridate)

get_my_recently_played(limit: 5) %>% 
    mutate(
        artist.name: map_chr(track.artists, function(x) x$name[1]),
        played_at: as_datetime(played_at)
        ) %>% 
    select(
      all_of(c("track.name", "artist.name", "track.album.name", "played_at"))
      ) %>% 
    kable()
```

| track.name           | artist.name | track.album.name     | played\_at          |
|:---------------------|:------------|:---------------------|:--------------------|
| A Case of You        | Tristen     | A Case of You        | 2021-06-14 09:54:44 |
| Paper Cup            | Real Estate | Paper Cup            | 2021-06-10 20:20:11 |
| Wrong with You       | Tristen     | Wrong with You       | 2021-06-10 20:17:24 |
| Animal - Edit        | LUMP        | Animal               | 2021-06-10 20:13:21 |
| Streets Of Your Town | DOPE LEMON  | Streets Of Your Town | 2021-06-10 18:23:00 |

That's about right...

### Find Your All Time Favorite Artists

``` r
get_my_top_artists_or_tracks(type: 'artists', 
                             time_range: 'long_term', 
                             limit: 5) %>% 
    select(.data$name, .data$genres) %>% 
    rowwise %>% 
    mutate(genres: paste(.data$genres, collapse: ', ')) %>% 
    ungroup %>% 
    kable()
```

| name                | genres                                                                   |
|:--------------------|:-------------------------------------------------------------------------|
| Japanese Breakfast  | art pop, bubblegrunge, eugene indie, indie pop, indie rock, philly indie |
| Haley Bonar         | melancholia, stomp and holler                                            |
| Balthazar           | belgian indie, belgian rock, dutch indie, dutch rock, ghent indie        |
| Buildings Breeding  | indie fuzzpop                                                            |
| Angus & Julia Stone | australian indie folk, indie folk, stomp and holler                      |

What could I say?  I travelled Australia listening only to Angus & Julia Stone, the Buildings Breeding have been with me since I discovered them on my first iPod, in one of the first podcasts, the Indiefeed. I created my Kickstarter account back in 2010 to support Haley Bonar's third album. And the year before I was very much into Japanese Breakfast and Balthazar. 

### Find your favorite tracks at the moment

``` r
get_my_top_artists_or_tracks(type: 'tracks', 
                             time_range: 'short_term', 
                             limit: 5) %>% 
    mutate(
        artist.name: map_chr(artists, function(x) x$name[1])
        ) %>% 
    select(name, artist.name, album.name) %>% 
    kable()
```

| name          | artist.name   | album.name  |
|:--------------|:--------------|:------------|
| Hot & Heavy   | Lucy Dacus    | Hot & Heavy |
| Sea Urchin    | Mystic Braves | Sea Urchin  |
| Human         | Freedom Fry   | Human       |
| Hot Motion    | Temples       | Hot Motion  |
| Animal - Edit | LUMP          | Animal      |


### What's the most joyful Joy Division song?

Let's take a look at the audio feature has to be `valence`, a measure of musical
positivity.

``` r
joy <- get_artist_audio_features('joy division')
```

``` r
joy %>% 
    arrange(-valence) %>% 
    select(.data$track_name, .data$valence) %>% 
    head(5) %>% 
    kable()
```

| track\_name                               | valence |
|:------------------------------------------|--------:|
| Passover - 2020 Digital Master            |   0.946 |
| Passover - 2007 Remaster                  |   0.941 |
| Colony - 2020 Digital Master              |   0.829 |
| Colony - 2007 Remaster                    |   0.808 |
| Atrocity Exhibition - 2020 Digital Master |   0.790 |

Now if only there was some way to plot joy…

### Joyplot of the emotional rollercoasters that are Joy Division's albums


{{< figure src="/blogposts_2021/README-joyplot-1.png" caption="Joyplot of the emotional rollercoasters that are Joy Division's albums" numbered="true" >}}

## Sentify: A Shiny app

This [app](http://rcharlie.net/sentify/), powered by spotifyr, allows
you to visualize the energy and valence (musical positivity) of all of
Spotify's artists and playlists.

## Dope Stuff Other People Have Done with spotifyr

The coolest thing about making this package has definitely been seeing
all the awesome stuff other people have done with it. Here are a few
examples:

[Exploring the Spotify API with R: A tutorial for beginners, by a beginner](https://msmith7161.github.io/what-is-speechiness/), Mia Smith

[Blue Christmas: A data-driven search for the most depressing Christmas song](https://caitlinhudon.com/2017/12/22/blue-christmas/), Caitlin
Hudon

[Sente-se triste quando ouve “Amar pelos dois”? Não é o único (Do you feel sad when you hear “Love for both?” You’re not alone)](https://rr.sapo.pt/especial/112355/sente-se-triste-quando-ouve-amar-pelos-dois-nao-e-o-unico),
Rui Barros, Rádio Renascença

[Using Data to Find the Angriest Death Grips Song](https://towardsdatascience.com/angriest-death-grips-data-anger-502168c1c2f0),
Evan Oppenheimer

[Hierarchical clustering of David Bowie records](https://twitter.com/WireMonkey/status/1009915034246565891?s=19),
Alyssa Goldberg

[tayloR](https://medium.com/@simranvatsa5/taylor-f656e2a09cc3), Simran
Vatsa

## Our Work with spotifyR

- [Trustworthy AI: Check Where the Machine Learning Algorithm is Learning From](https://dataandlyrics.com/post/2021-06-08-teach-learning-machines/)
- [Recommendation Systems: What can Go Wrong with the Algorithm?](https://dataandlyrics.com/post/2021-05-16-recommendation-outcomes/)
- [Feasibility Study On Promoting Slovak Music In Slovakia & Abroad](https://dataandlyrics.com/post/2021-03-25-listen-slovak/)
- [Forgetify: Popular Music That Nobody Listens To](https://dataandlyrics.com/post/2020-10-24-forgetify_pop_october/)

A key mission of our [Digital Music Observatory](https://music.dataobservatory.eu/), which is our modern, subjective approach on how the future European Music Observatory should look like, is to not only to provide high-quality data on the music economy, the diversity of music, and the audience of music, but also on metadata.  The quality and availability, interoperability of metadata (information about how the data should be used) is key to build trustworthy AI systems. We rely on [spotifyr](https://github.com/charlie86/spotifyr) to fulfil this mission.


{{< spoiler text="Join our Digital Music Observatory collaboration!" >}}
Join our open collaboration Digital Music  Observatory team as a [data curator](https://music.dataobservatory.eu/author/new-curators/), [developer](https://music.dataobservatory.eu/author/new-developers/) or [business developer](https://music.dataobservatory.eu/author/observatory-business-associate/).
{{< /spoiler >}}


