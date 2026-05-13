# BDO Barter Tracker

A simple, single-page web app to track your Black Desert Online sea-barter inventory. All 233 barter / material / special items with icons and official BDOCodex names. Stock is kept locally in your browser.

**Live site:** https://marcelonascimento-dev.github.io/bdo-barter-tracker/

## Features

- All barter trade goods from T1 to T7, plus barter materials, special items and Cox quest items (233 in total).
- Filter by tier/category, search by name, sort by quantity or name.
- Per-item stock indicator: **insufficient** (1–10 and 0), **low** (11–39), **sufficient** (40+).
- Tier-colored card backgrounds matching the in-game tier color.
- Bilingual UI: **Português** and **English**, with item names in the chosen language.
- Persistence: everything lives in `localStorage`. Export/Import JSON for backup.
- 100% static — no server, no tracking, no build step.

## Run locally

Just open `index.html` in your browser. That's it.

If your browser refuses to load the icons over `file://`, serve the folder with any static server, e.g.:

```sh
npx serve .
```

## Data source

Item names, tiers and icons come from [BDOCodex](https://bdocodex.com). Icons are hot-linked.

## License

MIT
