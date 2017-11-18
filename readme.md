# labels

Collection of [GitHub labels][labels] so I can [“Automagically create
issue labels in my GitHub projects”][labeller].  They’re based on
[solarized][].

| label             | color     | color name |
| ----------------- | --------- | ---------- |
| priority          | `#859900` | green      |
| low priority      | `#cb4b16` | orange     |
| future            | `#b58900` | yellow     |
| bug               | `#dc322f` | red        |
| needs pr          | `#d33682` | magenta    |
| has pr            | `#6c71c4` | violet     |
| help wanted       | `#268bd2` | blue       |
| question          | `#2aa198` | cyan       |
| enhancement       | `#859900` | green      |
| good for beginner | `#b58900` | yellow     |
| concept           | `#657b83` | base00     |
| external          | `#586e75` | base01     |
| duplicate         | `#073642` | base02     |
| no                | `#002b36` | base03     |
| patch             | `#93a1a1` | base1      |
| minor             | `#eee8d5` | base2      |
| feature           | `#eee8d5` | base2      |
| major             | `#fdf6e3` | base3      |
| change            | `#fdf6e3` | base3      |

Use:

```sh
github-labeller -t 123123 -i wooorm/labels -r wooorm/new-project
```

Where `-t` is a [GitHub token][token].

<!-- Definitions -->

[labels]: https://github.com/wooorm/labels/labels

[labeller]: https://github.com/IonicaBizau/github-labeller

[solarized]: http://ethanschoonover.com/solarized

[token]: https://github.com/settings/tokens
