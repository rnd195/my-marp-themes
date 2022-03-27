---
marp: true
theme: beamer
paginate: true
size: 4:3
header: This is a header
footer: This is a footer
title: Marp custom themes
---
<!-- _class: title -->

# Title of my presentation

Author name
University of XYZ
2022-26-03

---

# The `border` theme

- **A** *dark-grey* <u>border</u> is added
- The text is mostly black and white
- Based on the `default` theme

```
---
marp: true
theme: border
---
```

---
# The `gradient1` theme

- The default theme with a different background

```
---
marp: true
theme: gradient1
---
```
---

# The `beamer` theme

- Inspired by the Beamer LaTeX document class
- Specifically the Copenhagen dolphin variant

```
---
marp: true
theme: beamer
---
```
- Supports title pages by calling `<!-- _class: title -->` (see `beamer-sample.md`)
  - But make sure to only call this on the very first page
  - And only use simple text (no bullet points) to further specify your name, institution, and date
    - Only the `<p>` element will be centered (this was the best I could do with my limited CSS knowledge, sorry)

---

# Installation

This assumes that you're using the VSCode extension...

- In VSCode, go to
  - Preferences: Open Settings (UI)
  - Search for "Marp: Themes"
  - Add either a local or a remote path
    - e.g.: https://raw.githubusercontent.com/rnd195/my-marp-themes/main/border.css
  - Try restaring VSCode if it doesn't work right away
