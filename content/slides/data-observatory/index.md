---
title: Slides
summary: An introduction to using Wowchemy's Slides feature.
authors: [daniel_antal]
tags: [Digital Music Observatory]
categories: []
date: '2022-08-17T12:00:00Z'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: white
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Data Observatory 3.0

---

{{< slide background-image="dataobservatory-mission-statement.png" >}}


---

## Strategic objectives

- Develop our data observatories as [Open Scholarly Infrastructure](https://openscholarlyinfrastructure.org/posse/)
- Place our [Digital Music Observtory](https://music.dataobservatory.eu/), [Cultural and Creative Data Observatory](https://ccsi.dataobservatory.eu/), and [Green Deal Data Observaotry](https://greendeal.dataobservatory.eu/) on knowledge graphs of Europeana, Wikidata, and other open knowledge sytems
- Harmonize research artefacts with open repositories such as Zenodo and Figshare.
- Achieve EU/UNESCO/OECD recognition for our self-governing, triangular, science-policy-busines triangular data ecosystems as *data observatories*

---

{{< slide background-image="dataobservatory-mission-statement.png" >}}

---


## Digital Music Observatory

- `Listen Local` in Horizon Europe OpenMuse WP Diversity, Creative Europe MusicAIRE: connected and curated data on 10,000s of music works
- Our aim is to describe the entire, currently legally available music repertoire of Slovakia and Lithuania at first, and a large part of Ukraine.
- Connected with name authorities, web services.

---

## Possible Use Case

- Connect national collective management organization, national library, and various services (Spotify, YouTube) to make the national repertoire more visible
- Create use statistics for cultural diversity policies and monitoring local content regulations
- Provide best practice example and open source tools for replication

---
# Cultural Heritage Organizations



---


# Technical Features

[Reprex](https://reprex.nl/) | [Documentation](https://introduction.dataobservatory.eu/)



---

## FAIR

- [x] FAIR metadata: Dublin Core & DataCite referential metadata
- [x] Integration to FigShare and Zenodo for automated releases and publications

---

## Web 3.0

<small>&nbsp; 
-	[x] supported with optional, open source APIs to retrieve the data
-	[x] supported with RDF serialization

&nbsp; </small>

---

## Dissemination Support

-	[x] support automated publishing and releasing of data, visualizations, newsletters, and long-form documentation in auto-refreshing websites, blogposts, or articles, or even books.
-	[x] develop an ecosystem of open source software that helps the professional collection, processing, documentation of data conforming the Data Governance Act, and supporting data sharing and data altruism.

---

# Research Automation

---

## Research automation

- [x] support research automation 




---

# Controls


---
## Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://github.com/hakimel/reveal.js#pdf-export): `E`

---

## Code Highlighting

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}

- Only the speaker can read these notes
- Press `S` key to view
  {{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}

- Only the speaker can read these notes
- Press `S` key to view
  {{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/media/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://github.com/wowchemy/wowchemy-hugo-modules/discussions)

[Documentation](https://wowchemy.com/docs/managing-content/#create-slides)
