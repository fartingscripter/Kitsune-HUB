# Kitsune Hub — assets

Files the hub downloads once and then loads from the executor's workspace (`kitsune/` folder).

- `windui/main.lua` — [WindUI](https://github.com/Footagesus/WindUI) 1.6.66 by Footagesus, MIT (`windui/LICENSE-WindUI.txt`).
  One change: the icon loader is taken from the hub's cache instead of being fetched on every start.
- `windui/icons.lua` — icon loader from [Footagesus/Icons](https://github.com/Footagesus/Icons), MIT (`windui/LICENSE-Icons.txt`).
  One change: only the lucide pack is loaded (the hub uses no other).
- `windui/lucide.lua` — lucide icon pack from Footagesus/Icons (MIT). Lucide icons: ISC, https://lucide.dev.
- `assets/` — Kitsune Hub logos, wallpapers, tab icons and interface sounds (sounds are CC0, by Kenney).
