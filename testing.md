---
marp: true
theme: beamer
paginate: true
size: 4:3
header: This is a header
footer: This is a footer
title: Testing MD file
---
<!--- _class: title --->
# This is truly an extremely long title of my presentation

Author's name
University of XYZ
2022-26-03

---

# The `border` theme

```
---
marp: true
theme: border
---
```

---
# The `gradient` theme

- The default theme with a different background
- And some other tweaks

```
---
marp: true
theme: gradient
---
```
---

# The `beamer` theme

- Inspired by the Beamer LaTeX document class

```
---
marp: true
theme: beamer
---
```
- Supports title pages by calling `<!-- _class: title -->`
  - But make sure to only call this on the very first page
  - See `samples/beamer-template.md` for a template

---

# The `cobalt` theme

- Based on [elitistsnob/typora-cobalt-theme](https://github.com/elitistsnob/typora-cobalt-theme)

```
---
marp: true
theme: cobalt
---
```

---

# Installation

This assumes that you're using the VSCode extension...

- <mark>In VSCode, go to</mark>
  - Preferences: Open Settings (UI)
  - Search for "Marp: Themes"
  - Add either a local or a remote path
    - e.g.: https://raw.githubusercontent.com/rnd195/my-marp-themes/main/border.css
  - Try restaring VSCode if it doesn't work right away

---
<!-- _class: tinytext --->
# Tinytext class

Use `<!-- _class: tinytext --->` to make text in the slide tiny.

Might be useful for references.

---

# Table

| Customer ID    |  AA23   | BBTG   |
| ----  | ---- | ---- |
| 101   | 0    | 12    |
| 102   | 1    | 13    |
| 103   | 1    | 16    |

---

# Text decorations

- **Lorem ipsum** dolor sit amet, *consectetur adipiscing* elit. 

- <u>Cras rhoncus lacinia</u> ex non <mark>sagittis</mark>. Proin non nunc vel justo tincidunt egestas. 

> Lorem ipsum.