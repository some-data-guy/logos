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

## walter

Claude for the apps at home: a mole coming up out of the ground,
traced from its first favicon and drawn to its full-size drawing, with a
round nose and fine whiskers that contrast with what is behind them.

| File | Use |
| --- | --- |
| `walter/logo.svg` | The mole; ink on light, white on dark with `prefers-color-scheme` |
| `walter/logo_light.svg` | Ink (#1c1f24), for light backgrounds |
| `walter/logo_dark.svg` | White, for dark backgrounds |
| `walter/mono.svg` | One colour (black), for pinned tabs and masks |
| `walter/favicon.svg` | Favicon, without whiskers; ink or white with `prefers-color-scheme` |
| `walter/favicon.ico` | Favicon at 16, 32 and 48 px, on the dark tile |
| `walter/icon_180x180.png` | Apple touch icon, opaque |
| `walter/icon_192x192.png` | Web app manifest icon |
| `walter/icon_512x512.png` | Web app manifest icon |
| `walter/icon_512x512_maskable.png` | Maskable manifest icon, mark inside the safe zone |
| `walter/icon_256x256.png` | Transparent, for Unraid's Icon URL |
| `walter/lockup_light.svg` | Mark and name, for light backgrounds |
| `walter/lockup_dark.svg` | Mark and name, for dark backgrounds |

The name in the lockups is drawn from Roboto (Apache License 2.0).
