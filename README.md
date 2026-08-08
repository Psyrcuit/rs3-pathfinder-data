# RS3 Pathfinder — public distribution

This repository hosts the public artifacts of **RS3 Pathfinder**, a free community
tool that computes RuneScape 3 money-making pathways from live Grand Exchange prices.

- **Web app / Alt1 app**: served via GitHub Pages from this repo.
  Install in Alt1: open `alt1://addapp/https://psyrcuit.github.io/rs3-pathfinder-data/appconfig.json`
- **`data/`**: the machine-generated dataset (items, recipes, gathering rates,
  monster drop tables) rebuilt nightly from the [RuneScape Wiki](https://runescape.wiki).
- Desktop and Android builds are published under Releases.

## Licensing

- The dataset in `data/` is derived from the RuneScape Wiki and is licensed
  [CC BY-NC-SA 3.0](https://meta.weirdgloop.org/w/Licensing). Per-record source
  attribution is in `data/attribution.json`.
- Live prices are provided by Jagex via the
  [wiki real-time prices API](https://runescape.wiki/w/RuneScape:Real-time_Prices).
- RuneScape is a trademark of Jagex Ltd. This project is not affiliated with or
  endorsed by Jagex.

Source code: [Psyrcuit/rs3-pathfinder](https://github.com/Psyrcuit/rs3-pathfinder) (private).
