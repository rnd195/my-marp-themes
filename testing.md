---
marp: true
theme: border
paginate: true
size: 16:9
header: Marp custom themes
title: Marp custom themes

---
<!-- No page number and no header -->
<!-- _paginate: false -->
<!-- _header: "" -->


# My custom Marp themes
- `border`
- `gradient1`

---

# The `border` theme

- **A** *dark-grey* <u>border</u> is added
- The text is mostly black and white
- Based on the `default` theme

```
---
marp: true
theme: border
paginate: true
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

# Installation

- In VSCode, go to
  - Preferences: Open Settings (UI)
  - Search for "Marp: Themes"
  - Add either a local or a remote path
    - e.g.: https://raw.githubusercontent.com/rnd195/my-marp-themes/main/border.css
  - Try restaring VSCode if it doesn't work right away
