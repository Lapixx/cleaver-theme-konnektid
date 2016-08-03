# cleaver-theme-konnektid

Cleaver theme in Konnektid style

## Installation

In the header of your [Cleaver](https://github.com/jdan/cleaver) presentation, add the theme:

```yml
theme: Lapixx/cleaver-theme-konnektid
```

## Title slide

This theme applies some extra styles to the first slide of your presentation, which is assumed to be your title slide:
- The background colour is different (green instead of light grey)
- The `H1` and `H2` tags are white and receive a subtle drop shadow
- The background can be customized with an image

In order to add a (faded) background image to your title slide, simply add an image with the `alt` set to `"background"`:

```markdown
# Title
## Subtitle
![background](imgs/background.png)
```

## Figure captions

All `em` tags directly following an `img` are seen as the caption for the image. Captions are displayed smaller than
regular texts and are aligned to the center (like images).

```markdown
![example](img/graph.png)
*Figure 1: An example graph*
```
