# My custom Marp themes

[Marp](https://marp.app/) is used to create presentations in Markdown. In this repository, you may find simple CSS themes that I have created. Namely:

## `beam`

- inspired by / based on [LaTeX's beamer class](https://github.com/josephwright/beamer)

- download the [Computer Modern Unicode font family](https://ctan.org/pkg/cm-unicode?lang=en) for best results
- follow the [tutorial](how-to/beam_custom.md) to change the primary colors
- more screenshots on the [community themes website](https://rnd195.github.io/marp-community-themes/theme/beam.html)

*Download the CSS file:*

```
https://raw.githubusercontent.com/rnd195/my-marp-themes/live/beam.css
```

![beam sample](./samples/beam.jpg)

## `border`

- based on the `default` Marp theme

- find more screenshots on the [community themes website](https://rnd195.github.io/marp-community-themes/theme/border.html)

*Download the CSS file:*

```
https://raw.githubusercontent.com/rnd195/my-marp-themes/live/border.css
```

![border sample](./samples/border.png)

## `gradient`

- also based on the `default` Marp theme

- more screenshots available on the [community themes website](https://rnd195.github.io/marp-community-themes/theme/gradient.html)

*Download the CSS file:*

```
https://raw.githubusercontent.com/rnd195/my-marp-themes/live/gradient.css
```

![gradient1 sample](./samples/gradient.png)

- `gradient`, class `blue`

![gradient-blue](samples/gradient-blue.png)

## `graph_paper`

- click [here](https://rnd195.github.io/marp-community-themes/theme/graph_paper.html) to see more screenshots

*Download the CSS file:*

```
https://raw.githubusercontent.com/rnd195/my-marp-themes/live/graph_paper.css
```

![graph_paper](samples/graph_paper.png)



# Installation

Assuming you're using the VSCode Marp extension…

1. Open Settings in VSCode (`Ctrl + ,`)
2. Search for "Marp: Themes" or "markdown.marp.themes"
3. Add either a local (on your computer) or a remote path to the CSS file
   - Please, refer to [this discussion](https://stackoverflow.com/questions/17341122/link-and-execute-external-javascript-file-hosted-on-github/) about linking to files on GitHub
4. Enable the theme in the front-matter of the Markdown document, i.e., write the following at the very beginning of the Markdown document:

```
---
marp: true
theme: theme_name
---
```

5. Try restaring VSCode if it doesn't work right away

For additional settings (such as `size` or `paginate`), follow the [official documentation](https://github.com/marp-team/marp/blob/main/website/docs/guide/directives.md).

# License

The `beamer`-inspired `beam` theme is licensed under [GNU GPLv3](https://github.com/rnd195/my-marp-themes/blob/main/LICENSE_beamer). Parts of the `beamer` class are [dual-license](https://github.com/josephwright/beamer/blob/main/LICENSE.md) with one option being the [GNU GPLv2](https://github.com/rnd195/my-marp-themes/blob/live/LICENSE_GPLv2). The rest of the repository is licensed under the [MIT License](https://github.com/rnd195/my-marp-themes/blob/main/LICENSE).


# Attribution

The `beam`, `border`, `graph_paper`, and `gradient` themes are based on the `default` Marp themes made by [yhatt](https://github.com/marp-team/marp-core/tree/main/themes). The `border` and `gradient` themes import the [Inter](https://fonts.google.com/specimen/Inter) font by [Rasmus Andersson](https://rsms.me/). The `graph_paper` theme imports the [Work Sans](https://github.com/weiweihuanghuang/Work-Sans) font by [Wei Huang](https://github.com/weiweihuanghuang).

# Privacy notice

Please, be aware that some of the themes (`border`, `gradient`, and `graph_paper`) import fonts from the Google Fonts service. Refer to their [Privacy FAQ](https://developers.google.com/fonts/faq/privacy) for more information.