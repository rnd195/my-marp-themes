# My custom Marp themes

[Marp](https://marp.app/) is used to create presentations in Markdown. In this repository, you may find simple CSS themes that I have created. Namely:

- `beamer`, inspired by LaTeX's Beamer class
  - download the [Computer Modern Unicode font family](https://ctan.org/pkg/cm-unicode?lang=en) for best results

![beamer sample](./samples/beamer.png)

- `border`, based on the `default` Marp theme

![border sample](./samples/border.png)

- `cobalt`, which is heavily based on [elitistsnob/typora-cobalt-theme](https://github.com/elitistsnob/typora-cobalt-theme) and the Cobalt2 theme by [Wes Bos](https://github.com/wesbos/cobalt2/).

![cobalt](samples/cobalt.png)


- `gradient`, also based on the `default` Marp theme

![gradient1 sample](./samples/gradient.png)

- `gradient`, class `blue`

![gradient-blue](samples/gradient-blue.png)



## Installation

Assuming you're using the VSCode Marp extension… In VSCode, open

- Preferences: Open Settings (UI)
- Search for "Marp: Themes"
- Add either a local or a remote path
  - e.g.: https://raw.githubusercontent.com/rnd195/my-marp-themes/main/border.css
- Try restaring VSCode if it doesn't work right away

- Then in the Markdown document, simply write, for instance, `theme: border` in the YAML



Some of the themes are intended to be used with the [Inter](https://github.com/rsms/inter) font by [rsms](https://github.com/rsms/), so check them out.



### License

The software is licensed under the [MIT License](https://github.com/rnd195/my-marp-themes/blob/main/LICENSE).



### Attribution

The `beamer`, `border`, `cobalt`, and `gradient` themes are based on the `default` Marp themes made by [yhatt](https://github.com/marp-team/marp-core/tree/main/themes). The `border` and `gradient` themes import the [Inter](https://fonts.google.com/specimen/Inter) font by [Rasmus Andersson](https://rsms.me/). The `cobalt` theme is based on the Cobalt Typora theme made by [elitistsnob](https://github.com/elitistsnob/typora-cobalt-theme), which was inspired by the Cobalt theme family made by [Wes Bos](https://github.com/wesbos).
