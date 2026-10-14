# logos

Public home for logos and icons used by my private projects, so they can be
referenced by URL from places like Unraid Docker templates.

## Usage

Reference a file by its raw URL:

```
https://raw.githubusercontent.com/some-data-guy/logos/main/<path-to-file>
```

For an Unraid container, paste that URL into the **Icon URL** field
(advanced view) of the container template.

## Tips

- PNG or SVG with a transparent background works best; square, around 256×256.
- One folder per app, with files named `icon_<width>x<height>.png`,
  e.g. `my-app/icon_192x192.png`.

## somedataguy

The sea chart's compass rose from somedataguy.com (an eight-point rose in a ring, the chart's red at its heart), on its parchment tile by day and the night chart in dark. The touch and maskable icons leave out the tile's edge and let the parchment be the tile. In `somedataguy/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the light version |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name (Inter Bold, as outlines), for light and dark backgrounds |

## beacon

The central logging and monitoring system. Its mark is a lighthouse, drawn
after the one on the somedataguy sea chart: an ink tower on its rock, the
lantern lit amber and its light drawn as rays.

| File | What it is |
| --- | --- |
| `beacon/logo.svg` | The master |
| `beacon/logo_light.svg`, `beacon/logo_dark.svg` | For light and dark backgrounds |
| `beacon/mono.svg` | One colour, for pinned tabs and masks |
| `beacon/favicon.svg` | Favicon, switching with `prefers-color-scheme` |
| `beacon/favicon.ico` | Favicon at 16, 32 and 48 px |
| `beacon/icon_180x180.png` | Apple touch icon, opaque |
| `beacon/icon_192x192.png`, `beacon/icon_512x512.png` | PWA icons |
| `beacon/icon_512x512_maskable.png` | PWA maskable icon, inside its safe zone |
| `beacon/icon_256x256.png` | Transparent, with a white edge so it reads on dark too, for Unraid's Icon URL |
| `beacon/lockup_light.svg`, `beacon/lockup_dark.svg` | Mark and name; the name is outlined from Inter (SIL Open Font License) |

## beacon-home

beacon's sender at home, one of beacon's family: beacon's lantern, dome and rays set on a house, in beacon's ink, white and amber. In `beacon-home/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the light version |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL; a thin light edge keeps its outline on a dark page |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name (Inter Bold, as outlines), for light and dark backgrounds |

## blender-tests

A print nozzle laying an amber bead on two printed layers, in deep teal
(`#041312`) with an amber filament accent. In `blender-tests/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, mid teal, readable on light and dark |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon drawn for 16 px, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name, for light and dark backgrounds |

## caddy

The web server in front of the sites: a fingerpost on its mound, one arm in the sea chart's red, in its ink and parchment. In `caddy/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the light version |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL; a thin light edge keeps its outline on a dark page |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name (Inter Bold, as outlines), for light and dark backgrounds |

## courier

The courier between services: a letter under a red wax seal, carried closed end to end, in the sea chart's ink and parchment. In `courier/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the light version |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL; a thin light edge keeps its outline on a dark page |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name (Inter Bold, as outlines), for light and dark backgrounds |

## door

somedataguy's sign-in front door: an arched door on its step, its keyhole in the sea chart's red, in sepia ink on parchment (the night chart in dark). In `door/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the light version |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL; a thin light edge keeps its outline on a dark page |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name (Inter Bold, as outlines), for light and dark backgrounds |

## mote

A world lit from beyond the frame: a dark disc with an amber crescent at
its limb, on a near-black rounded tile (`#0f0f12`). In `mote/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master: the mark on its tile, the source of `icon_512x512.png` |
| `logo_light.svg` | Mark without the tile, for light backgrounds |
| `logo_dark.svg` | Mark without the tile, for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon: a thicker crescent drawn for 32 px and under, on the tile, so it reads on light and dark |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent corners, for Unraid's Icon URL |
| `lockup_light.svg`, `lockup_dark.svg` | The mark above MOTE, the crescent as the O, for light and dark backgrounds |

## pawsy

Pawsy's paw in marigold (`#f3b84b`) on ink (`#1c2333`), as the app
installs with. In `pawsy/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master: the paw on its rounded ink square |
| `logo_light.svg` | The paw in ink, for light backgrounds |
| `logo_dark.svg` | The paw in marigold, for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon: the opaque square, the same on light and dark |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded square |
| `icon_512x512_maskable.png` | PWA maskable icon, paw inside the safe zone |
| `icon_256x256.png` | Rounded square with transparent corners, for Unraid's Icon URL |
| `lockup_light.svg`, `lockup_dark.svg` | Paw and name, for light and dark backgrounds |

## pwa

The offline-first base for the self-hosted web apps: a teal house with
sync arrows cut through it, on a rounded tile.

| File | Use |
| --- | --- |
| `pwa/logo.svg` | The logo, on its dark tile |
| `pwa/logo_light.svg` | Light tile, for light backgrounds |
| `pwa/logo_dark.svg` | Dark tile, for dark backgrounds |
| `pwa/mono.svg` | One colour (black), for pinned tabs and masks |
| `pwa/favicon.svg` | Favicon; light or dark tile with `prefers-color-scheme` |
| `pwa/favicon.ico` | Favicon at 16, 32 and 48 px |
| `pwa/icon_180x180.png` | Apple touch icon, opaque |
| `pwa/icon_192x192.png` | Web app manifest icon |
| `pwa/icon_512x512.png` | Web app manifest icon |
| `pwa/icon_512x512_maskable.png` | Maskable manifest icon, mark inside the safe zone |
| `pwa/icon_256x256.png` | Transparent, for Unraid's Icon URL |
| `pwa/lockup_light.svg` | Mark and name, for light backgrounds |
| `pwa/lockup_dark.svg` | Mark and name, for dark backgrounds |

The name in the lockups is drawn from Inter (SIL Open Font License).

## slate

A stack of three entries, the front one whole, on a dark rounded tile,
drawn on a 16-unit grid so every edge falls on a pixel at 16 px. Greys
only (`#22242a` to `#e6e7ea`). In `slate/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the dark tile, readable on light and dark |
| `logo_light.svg` | Pale tile, for light backgrounds |
| `logo_dark.svg` | Dark tile, for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon drawn for 16 px, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon (the original file, corners transparent) |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name, for light and dark backgrounds |

## somedataguy-db

somedataguy.com's Postgres: the database cylinder, its top marked in the sea chart's red, in its ink and parchment. In `somedataguy-db/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master mark, the light version |
| `logo_light.svg` | Mark for light backgrounds |
| `logo_dark.svg` | Mark for dark backgrounds |
| `mono.svg` | One colour, for pinned tabs and masks |
| `favicon.svg` | Favicon, switches with `prefers-color-scheme` |
| `favicon.ico` | 16, 32 and 48 px |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, mark inside the safe zone |
| `icon_256x256.png` | Transparent, for Unraid's Icon URL; a thin light edge keeps its outline on a dark page |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name (Inter Bold, as outlines), for light and dark backgrounds |
