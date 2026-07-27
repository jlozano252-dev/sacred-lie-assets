# Sacred Lie — Assets

Art and reference assets for **Sacred Lie**, a webcomic/manga project. This
repository holds the finished comic pages, character art, and environment art,
plus reference material collected during production.

The tile sets and world maps are being prepared with a **possible game
adaptation** in mind, so they are kept modular and separate from the comic
pages themselves.

## Folder structure

```
pages/         Chapter 1 comic pages (the published/finished comic)
portraits/     Character portrait art + the group lineup
refs/          Character reference/model sheets (for drawing consistency)
tiles/         Modular environment tiles (for a possible game adaptation)
maps/          World / location maps (for a possible game adaptation)
backgrounds/   Scene background art
costumes/      Costume reference sheets
reference/     Inspiration screenshots (anime expressions & interactions)
```

All filenames are lowercase with underscores, extension `.png` (a few
reference screenshots are `.jpeg`).

## Characters

| Character | Portrait | Reference sheet |
|-----------|----------|-----------------|
| Cassian   | `portraits/portrait_cassian.png`   | `refs/ref_cassian.png`   |
| Elias     | `portraits/portrait_eliasv2.png`   | `refs/ref_elias.png`     |
| Kael      | `portraits/portrait_kael.png`      | `refs/ref_kael.png`      |
| Lucien    | `portraits/portrait_lucienv2.png`  | `refs/ref_lucien.png`    |
| Marcus    | `portraits/portrait_marcus.png`    | *(none yet — TODO)*      |
| Mira      | `portraits/portrait_mira.png`      | `refs/ref_mira.png`      |
| Selene    | `portraits/portrait_selenev2.png`  | `refs/ref_selenev2.png`  |
| Victor    | `portraits/portrait_victorv2.png`  | `refs/ref_victorv2.png`  |

- `portraits/lineup_4char.png` is a full-body group lineup showing four
  characters together.
- **Marcus** does not yet have a reference sheet — one still needs to be
  created.

## Tiles and maps

Both sets are intended for a **possible game adaptation** of the comic, not for
the comic pages themselves.

- **`tiles/`** — modular environment pieces used to assemble game scenes:
  `tile_forest`, `tile_fort`, `tile_pillar`, `tile_ruins`, `tile_stone`,
  `tile_wall`.
- **`maps/`** — world/location maps: `map_1.png`, `map_2.png`.

## Reference screenshots

`reference/` holds `img_6694`–`img_6701`: screenshots saved from the phone as
drawing reference (anime facial expressions such as anger/sadness/shock, and
character interactions like couple posing, slaps, and playful hits). These are
external inspiration images, **not** original project art, and may be subject
to third-party copyright — keep them out of anything published.

## Versioning convention

A `v2` / `v5` suffix marks the **current, canonical** version of a file
(e.g. `ch1_p04v5.png`, `portrait_selenev2.png`). Earlier versions have been
discarded; the highest-numbered file present is the one to use. Files with no
suffix are also current — the suffix only appears where the art was revised.

## Conventions

- Naming: `lowercase_with_underscores`, `.png` (reference images may be `.jpeg`).
- Comic pages: `ch<chapter>_p<page>[v<version>].png` (e.g. `ch1_p01_02.png`
  spans pages 1–2).
- Character art: `portrait_<name>[v<version>].png` and `ref_<name>[v<version>].png`.
- Environment tiles: `tile_<subject>.png`.
