# Website media (placeholders)

This directory is for **homepage screenshots and short demo loops**.

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

You can overwrite these with real assets (same filenames) and the site will update:

### Hero

- `media/screenshots/hero_preview.svg`

### Screenshot section

- `media/screenshots/wysiwyg_edit.svg`
- `media/screenshots/large_docs.svg`
- `media/screenshots/math_mermaid.svg`

### Video section

- `media/posters/editing_loop.svg`
- `media/posters/export_loop.svg`
- `media/videos/editing_loop.webm` (optional, add later)
- `media/videos/editing_loop.mp4` (optional, add later)
- `media/videos/export_loop.webm` (optional, add later)
- `media/videos/export_loop.mp4` (optional, add later)

