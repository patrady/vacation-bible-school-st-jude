# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static single-page website for True North VBS 2026 at St. Jude Thaddeus Catholic Church. Live at https://www.stjudethaddeusvbs.com/

## Running Locally

Open `index.html` directly in a browser, or:

```bash
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Deployment

Push to `main` to automatically deploy via GitHub Pages.

## Architecture

- **Single file**: All HTML, CSS, and JS live in `index.html`
- **Tailwind CSS**: Loaded via CDN with custom color config (forest, sky, aurora-teal, aurora-purple)
- **Fonts**: Fredoka (headings) and Nunito (body) from Google Fonts
- **Images**: All in `assets/images/` (character PNGs, hero.jpg, logo.png)
- **No build step**: Ready to deploy as-is
