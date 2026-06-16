# Website media

This directory holds the **homepage screenshots and short demo loops**.

## Why this exists

The website is intentionally static (no build step). To keep edits simple, the homepage
references files from this directory directly.

## Structure

- `media/screenshots/`: static images used in sections (PNG/WebP/AVIF/SVG)
- `media/posters/`: posters for video blocks (lightweight images)
- `media/videos/`: short silent loops (WebM preferred, MP4 fallback)

## Recommended formats

- Screenshots: `webp` (good default), `avif` (smaller), or `png` (fallback)
- Videos: `webm` (primary) + `mp4` (fallback), **muted** 4–8s loops

## Filenames currently referenced by the site

Overwrite these with new captures (same filenames) and the site updates automatically.

### Hero

- `media/screenshots/hero_preview.svg` — **placeholder; no real capture yet** (drop in `hero_preview.png` to replace).

### Screenshot section (real captures)

- `media/screenshots/wysiwyg_edit.png`
- `media/screenshots/large_docs.png`
- `media/screenshots/math_mermaid.png`

### Video section (real captures)

- `media/posters/editing_loop.mp4` + `media/posters/editing_loop.poster.png`
- `media/posters/export_loop.mp4` + `media/posters/export_loop.poster.png`

The `.poster.png` files are the still frames shown before a loop plays (generated from the MP4s
with `ffmpeg`). The original `*.svg` placeholders remain in place but are no longer referenced.

