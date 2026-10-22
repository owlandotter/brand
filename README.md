# Owl & Otter brand assets

Logos and mascot sprites for Owl & Otter. This repo holds finished assets only. There is no source code or build tooling here.

| Path | Contents |
|---|---|
| `logo/` | The logo in every size, as PNG and lossless WebP, plus `favicon.ico` |
| `characters/` | Pixel-art sprites of the owl and otter: single frames, sprite sheets with JSON maps, and animated GIFs |

## Logo files

Files are named `<type>_<variant>_<height>x<width>.<png|webp>`.

| Type | What it is | Sizes |
|---|---|---|
| `logo` | The badge with the "Owl & Otter" plank beside it | Heights 24 to 128 px, then 1× to 4× the master |
| `badge` | The owl and otter in a wooden ring | Squares, 16 to 1024 px |
| `wordmark` | The "Owl & Otter" plank on its own | Heights 24 to 128 px, then 1× to 4× the master |
| `icon` | The owl and otter on a full-bleed peach square, for app icons | Every size iOS, Android and the web ask for, 16 to 1024 px |

`colour` is the only variant so far. `favicon.ico` holds the icon at 16, 32 and 48 px.

Everything is pixel art. Scale it up with nearest-neighbour sampling (`image-rendering: pixelated` in CSS), or the pixels go soft. Use the size closest to what you need, rather than shrinking a larger file.
