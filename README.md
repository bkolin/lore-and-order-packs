# Lore & Order — official knowledge packs

Static files served by GitHub Pages and downloaded on demand by the game (SPEC CONT-10).

- `catalog.json` — index of every pack: id, version, name, category, size, SHA-256.
- `packs/<id>.json` — one pack in the §2.15 format (v2). Media, if any, under `packs/<id>/`.

Packs are generated from the game repo with `npm run packs:publish`; don't edit them by hand.
Only packs the team has written or reviewed are published here.
