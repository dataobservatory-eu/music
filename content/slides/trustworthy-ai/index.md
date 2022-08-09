---
title: Slides
summary: Turstworthy AI With Reprex
authors: []
tags: []
categories: []
date: "2020-01-21T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Trustworthy AI With Reprex

[Reprex](https://wowchemy.com/) | [Data Curation](https://owchemy.com/docs/managing-content/#create-slides)

---

## Presentation Controls

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

## Trustworthy AI

The European Union has adopted the [Ethics Guidelines for Trustworthy AI](https://ec.europa.eu/futurium/en/ai-alliance-consultation) with seven important principles:

1. Human agency and oversight
2. Technical robustness and safety
3. Privacy and Data governance
4. Transparency
5. Diversity, non-discrimination and fairness
6. Societal and environmental well-being
7. Accountability

In the EU, in the US or in the UK creative industries usually do not have access to trustworthy AI in 2021.

---

## Our Focus

Make content appear incrementally

{{% fragment %}} * Transparency: we use open data, open source software, and we make sure that our clients understand what is happening with their products {{% /fragment %}}
{{% fragment %}} * Diversity: we know that a Slovak, Hungarian or Estonian song has less chances than an American one.  We see that many corporate algorithms reinforce racism and patriarchy. {{% /fragment %}}
{{% fragment %}} * Societal well-being: we understand that the algorithm is maximizing the well-being and profit of the entity that trains it. {{% /fragment %}}
{{% fragment %}} * Accountability: algorithm-driven robotic sales must be held accountable, and must comply with consumer-protection, competition-protecion and non-discrimination rules. {{% /fragment %}}

<Press `Space` to play!>

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
