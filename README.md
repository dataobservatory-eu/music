[![dataobservatory](https://img.shields.io/badge/ecosystem-dataobservatory.eu-3EA135.svg)](https://dataobservatory.eu/)
[![dataobservatory on
Github](https://img.shields.io/badge/github-dataobservatory.eu-6e5494.svg)](https://github.com/dataobservatory-eu/)
[![R package
iotables](https://img.shields.io/badge/R-iotables-4EC0E4.svg)](https://iotables.dataobservatory.eu)
[![R package
retroharmonize](https://img.shields.io/badge/R-retroharmonize-007CBB.svg)](https://iotables.dataobservatory.eu)
[![R package
regions](https://img.shields.io/badge/R-regions-00843A.svg)](https://regions.dataobservatory.eu)
[![R package
dataset](https://img.shields.io/badge/R-dataset-E4007F.svg)](https://dataset.dataobservatory.eu)
[![R package
spotifyr](https://img.shields.io/badge/R-spotifyr-1db954.svg)](https://www.rcharlie.com/spotifyr)
[![R package
statcodelists](https://img.shields.io/badge/R-statcodelists-lightgrey.svg)](https://statcodelists.dataobservatory.eu)
[![Contributor
Covenant](https://img.shields.io/badge/ethics-Contributor%20Covenant-680171.svg)](https://dataobservatory.eu/)

## Welcome 👋

🙋‍♀️ Creating an ecosystem of open data and open knowledge sharing in R, hugo, and open science repositories.

🌈 Contribution guidelines - you must abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct.

This is the repository of the [music.dataobservatory.eu](https://music.dataobservatory.eu/) website. This repository belongs to [Reprex](https://reprex.nl/), a Netherlands-based reproducible research startup.  We created this website, along with many others, using an open source Hugo template. And we create many [open-source software solutions](https://reprex.nl/software/) ourselves.

## Folders

### Text assets and pages 
The `content` folders usually contain an `index.md` file with text and a `featured.jpg` or `featured.png` image that is the thumbnail index or opening visual image of the page.

- `content/events`:  The `index.md` contains the description and various details (time, venue location) of the events. The thumbnail image and opening image is the `featured.png` or `featured.jpg`. 

- `content/authors/<post_2022-10-01>`: The `index.md` contains the blogpost with metadata (publication time, author, tags).  The thumbnail image and opening image is the `featured.png` or `featured.jpg`. 

- `content/authors/<name>`:  The `index.md` contains the biography and avatar of our contributors as natural persons or as institutions. The <name> part is the snake_case version of person's or company's name that creates the permanent url, for example, `content/authors/reprex` creates the page `https://music.dataobservatory.eu/authors/reprex/`. In this case, there is no featured.png, instead, the main image (which will be placed behind a cirucal mask for identical layout on the [contributors]() page) is called `avatar.png`.  The `content/authors/reprex/avatar.png` is the Reprex logo. The `content/authors/reprex/daniel_antal.png` is Daniel's portrait.

The `featured.png` or `featured.jpg` and the `avatar.png` or `avatar.jpg` are usually replicated from the media library. They are special files, because the hugo engine will create multiple versions of these images for thumbnails, collection pages, etc. Other images that are only displayed in a post or a page once as normal, embedded images can be found in the 'assets' library.

### Media assets and files

Hugo optmizes all assets that are used, and will create a [webp file](https://developers.google.com/speed/webp) from the .jpg or .png images.  "WebP is a modern image format that provides superior lossless and lossy compression for images on the web. Using WebP, webmasters and web developers can create smaller, richer images that make the web faster." The creation of the `.webp` files is automatic and remains behind the scenes: any `.jpg` or `.png` file that is used from the `assets/media/` folder and its subfolders will be automatically converted to `.webp`.

- `assets/media/img/`: contains subfolders with png or jpg images. For example, all images that were used in blog posts in the year 2022 (so far) can be found in `assets/media/img/blogposts_2022/`. The screenshots or cover images of reports created with the Digital Music Observatory are in `assets/media/img/reports/`

- `assets/media/img/logos/` contain logos.  Please do not use bigger than about 2000x2000 pixel versions.  When needed, a copy of the logo can be saved as `avatar.png` or `avatar.jpg` [see text files above].

- `assets/media/albums/` contain image albums that should be viewed together in as an image gallery.

- `assets/documents/` can be used to upload downloadable articles, PDF files, or anything that is not an image. 


## [Hugo Academic Theme](https://github.com/wowchemy/starter-hugo-academic)

Our work relies on commissioned work, grants, sponsorship, and the same goes to our friends at Wowchemy.  When you use our free products, please give us proper attribution, and if you can, contribute with work or money to keep our products going. 

The Reprex website is built with the Hugo **Academic Resumé Template** empowers you to easily create your job-winning online resumé, showcase your academic publications, and create online courses or knowledge bases to grow your audience.

️**Trusted by 250,000+ researchers, educators, and students.** Highly customizable via the integrated **no-code, widget-based Wowchemy page builder**, making every site truly personalized ⭐⭐⭐⭐⭐
- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
## We ask you, humbly, to support this open source movement

Reprex builds open source products, and our friends at Wowchemy do so, too.  You can use Reprex's website, or our observatory websites, such as this one, as a template based on their work.  But we have both worked a lot with it, and therefore, if you use the Wowchemy template, we would like to emphasises the request of the Wowchemy team:

Today we ask you to defend the open source independence of the Wowchemy website builder and themes 🐧

We're an open source movement that depends on your support to stay online and thriving, but 99.9% of our creators don't give; they simply look the other way. [❤️ Click here to become a Wowchemy GitHub Sponsor, unlocking awesome perks such as _exclusive academic templates and widgets_](https://github.com/sponsors/gcushen)



