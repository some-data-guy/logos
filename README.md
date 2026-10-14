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

## ledger

The personal finance app. Its mark is a ruled ledger page on a green tile
(`#1d6b52`): a column of figures, the total in brass, and the double rule
under it. At 16 and 32 px it is drawn in a simpler form, with one figure,
the total and the double rule. In `ledger/`:

| File | Use |
| --- | --- |
| `logo.svg` | Master: the page on its green tile, readable on light and dark |
| `logo_light.svg` | The tile with a darker edge, for light backgrounds |
| `logo_dark.svg` | The tile with a lighter edge, for dark backgrounds |
| `mono.svg` | One colour, the simple form's page with its lines cut out, for pinned tabs and masks |
| `favicon.svg` | Favicon in the simple form, on the tile, so the same on light and dark |
| `favicon.ico` | 16, 32 and 48 px, in the simple form |
| `icon_180x180.png` | Apple touch icon, opaque |
| `icon_192x192.png`, `icon_512x512.png` | PWA icons, rounded tile |
| `icon_512x512_maskable.png` | PWA maskable icon, page inside the safe zone |
| `icon_256x256.png` | Rounded tile with transparent corners, for Unraid's Icon URL |
| `lockup_light.svg`, `lockup_dark.svg` | Mark and name, for light and dark backgrounds; the name is outlined from Inter (SIL Open Font License) |
