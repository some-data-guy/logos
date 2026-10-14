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

## door

somedataguy's sign-in front door: an arched door on its step, its keyhole in the sea chart's red, in sepia ink on parchment (the night chart in dark). One logo for the door and its helper `door-store`. In `door/`:

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

The tunnel from home to pip: a letter under a red wax seal, carried closed end to end, in the sea chart's ink and parchment. One logo for `courier`, `courier-frpc`, `courier-log`, `relay` and `intake`. In `courier/`:

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

## beacon-home

TheAttic's beacon sender, one of beacon's family: beacon's lantern, dome and rays set on a house, in beacon's ink, white and amber. One logo for `beacon-home-sender`, `beacon-home-syslog` and `beacon-home-docker-proxy`. In `beacon-home/`:

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

## caddy

The web server in front of the sites on pip: a fingerpost on its mound, one arm in the sea chart's red, in its ink and parchment. In `caddy/`:

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
