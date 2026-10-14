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
