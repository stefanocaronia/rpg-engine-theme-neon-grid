# Neon Grid

A theme for the dashboard of [rpg-engine](https://github.com/stefanocaronia/rpg-engine), for any game system: cyan and magenta light on a midnight grid, a pale terminal by day. Wide geometric titles in capitals, a clean sans for the text, faint scanlines on the top bar and a bracket in the corner of the cards. Light and dark, both checked for contrast by the engine.

| | Light | Dark |
|---|---|---|
| Page | `#eef0fa` pale grid | `#07061a` midnight |
| Text | `#12102b` | `#eaf2ff` |
| Accent | `#0a6580` deep cyan | `#35e3ff` cyan |
| Strong | `#a8126a` magenta | `#ff3fa4` neon magenta |

## Its shapes

Panels with cut corners and a dot grid under their words, buttons and tabs cut the same, the tab chosen on a tint of cyan; a glow instead of shadows, violet by day and cyan by night; portraits cut to octagons in a thin cyan frame; a striped sun over a grid in perspective at the head of the page, beside the campaign's name; cool white paper for the documents and the maps. All of it from `theme.yaml`, no style sheet of its own. Needs rpg-engine 0.22 or later.

## Install

- In the dashboard: **Packages › Add**, paste `https://github.com/stefanocaronia/rpg-engine-theme-neon-grid`, or find it in the catalog under Themes.
- Or from a terminal: `rpg package install https://github.com/stefanocaronia/rpg-engine-theme-neon-grid`.

Then choose it in **Settings › This page › Game style**. It is installed for every campaign on this computer; `rpg package uninstall neon-grid` takes it away.

## Fonts

| Face | Used for | Licence |
|---|---|---|
| [Orbitron](https://github.com/theleagueof/orbitron), The League of Moveable Type | titles, big numbers | SIL Open Font License 1.1, `fonts/orbitron/OFL.txt` |
| [Exo 2](https://github.com/googlefonts/Exo-2.0), Natanael Gama | text, story | SIL Open Font License 1.1, `fonts/exo-2/OFL.txt` |

Both come unchanged from [google/fonts](https://github.com/google/fonts).

## Licence

The theme, `theme.yaml` and `images/`, is © 2026 Stefano Caronia under [CC BY 4.0](LICENSE). The fonts stay under their own SIL Open Font License, beside each one.
