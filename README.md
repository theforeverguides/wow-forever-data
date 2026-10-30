# wow-forever-data

Free, open JSON data for **World of Warcraft: Forever**, maintained by **[Forever Guides (theforeverguides.com)](https://theforeverguides.com/)**, an unofficial fan site. Not affiliated with Blizzard Entertainment.

| File | What it is | Live page |
|---|---|---|
| `data/launch-time.json` | Global launch (4 Nov 2026, 3:00 p.m. PST = 23:00 UTC) converted to 15 time zones, with IANA zone names and abbreviations | https://theforeverguides.com/launch-time/ |
| `data/talents.json` | Talent tree layout for all 9 classes: talent name, max rank, 1-based row/col, prerequisite, total points | https://theforeverguides.com/tools/talents/ |

Source for the launch time: [Blizzard announcement](https://news.blizzard.com/en-us/article/24302093/carve-a-new-path-with-world-of-warcraft-forever). The talent layout reflects the WoW Forever beta client and may change at launch. Tooltip and rank text is left out on purpose.

## Licence
Code and data: MIT (see `LICENSE`). Credit with a link to https://theforeverguides.com/ is appreciated. World of Warcraft names are trademarks of Blizzard Entertainment.

Corrections: please open an issue.

## Credits

Talent tree layout in `data/talents.json` is derived from WoW Forever beta client data via [foreverdiff.com](https://foreverdiff.com). Beta data may change at launch.
