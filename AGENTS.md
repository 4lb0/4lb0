# Project Context for AI Agents

## Overview

This is a simple, minimal personal link tree website for **albo.ar**. It's a
single-page HTML site with no build step or dependencies.

## Project Structure

```
.
├── index.html   # Main page - single file with inline CSS/JS
├── CNAME        # GitHub Pages custom domain config (albo.ar)
├── LICENSE      # Project license
└── README.md    # Human-readable project description
```

## Technology Stack

- **Pure HTML/CSS/JavaScript** - No frameworks, no build tools
- **Inline styles and scripts** - Everything is self-contained in `index.html`
- **GitHub Pages hosting** - Static site deployment

## Design Guidelines

- **Minimalist aesthetic** - Clean, simple design
- **Color scheme**:
  - Background: `#9cd` (light blue)
  - Buttons: `#fbe` (light pink) with `#420` (dark brown) borders
  - Accent: `#ccc` with `#999` (for main branding link)
  - Footer: `#420` (dark brown) background
- **Responsive**: Uses flexbox with a media query for portrait/mobile
  orientation
- **Retro feel**: Uses box shadows for 3D button effect (`4px 4px 0 0`)

## Adding/Modifying Links

Links are added as `<a>` tags in `index.html`. Each link should have:

- `href` attribute with the URL
- `data-t` attribute with a short description (shown in footer on hover)
- Optional inline styles for custom colors

## Deployment

The site is deployed via GitHub Pages. Pushing to the main branch automatically
deploys.

## Code Style

- Minified inline CSS and JavaScript (minimal whitespace)
- Single-letter variable names in JS (minified style)
- No external dependencies
