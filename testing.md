---
marp: true
theme: border
paginate: true
size: 16:9
header: Introducing Marp
title: Document title

---
<!-- No page number and no header -->
<!-- _paginate: false -->
<!-- _header: "" -->

<style>
:root {
    font-family: Inter, Helvetica, Arial;
    font-size: 1.9em
}
</style>

# Marp

A Markdown presentation ecosystem


---

# New slides

- a new slide is initiated using the divider

```
# One of these!
---

***

___
```

---

# Markdown syntax support

- make sure to enable `markdown.marp.enableHtml`
  - HTML stuff won't work in untrusted workspaces
- **bold**
- *italic*
- `code`
- <mark>html highlight</mark>
- <u>underscore</u>

---

# Marp actually works side by side with Typora

You just have to make sure to save to preview.

---

<!-- _backgroundImage: "linear-gradient(to bottom right, black, grey)" -->

# There's some wacky HTML magic

- The underscore means that it is meant only for this slide
- You can actually apply almost anything from the YAML this way\*

<!-- _footer: "*Like a footnote" -->

---

# Can it handle GIFs?

![w:50% right](https://i.imgur.com/fkXSquX.gif)

- this is the same for other image types
- in the image alt, you specify the width as `w:50%` or just `50%`

---

# Let's talk about the YAML

- Marp calls these settings directives
- You can take a peek at all of them in VSCode using CTRL + Space

```
---
marp: true
theme: uncover
paginate: true
header: Introducing Marp
---
```

More info here https://marpit.marp.app/directives

---

# On default themes

- `theme: uncover` with `class: invert` is pretty cool

- `theme: gaia` theme with `class: lead invert` is a nice left-aligned theme

---
<!-- The presenter view you know from PowerPoint actually exists here as well. The HTML presentation actually contains an option to use the presenter view. -->
# Presenter view

- Done using HTML comments
```html
<!-- This is an HTML comment, but in a codeblock. -->
```
---

# More to come

- Exporting takes place using the Marp CLI
- I guess this is built-into the VSCode extension
- In VSCode, `Ctrl+Shift+P` > Export Slide Deck
  - PDF, HTML, PPTX