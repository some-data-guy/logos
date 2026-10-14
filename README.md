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
