# Project Context for AI Agents

## Overview

Personal homepage for **albo.ar** — a minimalist, text-based single-page site. No build step, no JavaScript, pure semantic HTML with inline CSS.

## Project Structure

```
.
├── index.html   # Main page - single file with inline CSS
├── CNAME        # GitHub Pages custom domain config (albo.ar)
├── LICENSE      # Project license
└── README.md    # Human-readable project description
```

## Technology Stack

- **Pure HTML/CSS** - No frameworks, no build tools, no JavaScript
- **Inline styles only** - Everything in `<style>` inside `index.html`
- **Semantic HTML** - Uses `<h1>`, `<h2>`, `<ul>`, `<li>` appropriately
- **GitHub Pages hosting** - Static site deployment
- **Dark mode support** - Uses `color-scheme: light dark`

## Design Guidelines

- **Extreme minimalism** - Text-only aesthetic, no images except emoji favicon
- **Typography**: Monospace font (`14pt monospace`), generous letter-spacing
- **Layout**: Single column, max-width `80ch`, centered
- **Color scheme**: 
  - Respects system `light dark` preference
  - Links: default browser colors with `font-weight: 900`
  - No custom colors (removed the retro palette)
- **Responsive**: Works on all viewports via `clamp()` font sizing
- **No photos** - Emoji avatar (👨‍💻) maintains the text-based aesthetic

## Content Structure

The page is organized in sections:

1. **Header** (`<h1>`) - Name with emoji
2. **Acerca de mí** - Personal bio, blog link, config/dotfiles
3. **Proyectos** - Work, side projects, tools
4. **Redes** - Social links
5. **Libros** - Book recommendations

## Adding/Modifying Content

- Use semantic HTML: `<h2>` for sections, `<ul>` + `<li>` for lists
- Links: `<a href="//domain.com">text</a>` (protocol-relative URLs)
- Email: `<a href="mailto:albo@pragmore.com">albo@pragmore.com</a>`
- RSS: `<a href="//blog.albo.ar/rss.xml">rss</a>`
- Keep tone informal, in Argentinian Spanish (voseo)

## Key Links to Know

| Service | URL |
|---------|-----|
| Blog | blog.albo.ar (with /rss.xml) |
| Email | albo@pragmore.com |
| Config/dotfiles | github.com/4lb0/config |
| Work | pausaco.com |
| Freelance | pragmore.com |
| Domains | domains.pragmore.com |
| Framework | bialet.dev |
| CSS lib | pragmore.com/blouse.css |
| Mentor | mentor.dev.ar |
| PM Skill | loro.dev.ar |
| Subdomains | home.dev.ar |
| Podcast | youtube.com/@NoParamosDeHablar |

## Deployment

GitHub Pages with custom domain `albo.ar`. Push to main deploys automatically.

## Code Style

- No minification needed (small enough)
- Minimal CSS (dark mode, typography, spacing only)
- No JavaScript
- Single file, no external assets except favicon SVG
