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
