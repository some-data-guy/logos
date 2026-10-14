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
