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
