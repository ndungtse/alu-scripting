# Responsive design

Makes the Techium homepage responsive. Starting from the starter HTML/CSS,
each task builds on the previous one: a flexible container, media queries for
tablet and mobile (`992px`, `767px`, `480px`), images in several resolutions
(`srcset` / `sizes`), a pure HTML/CSS hamburger menu driven by a checkbox,
responsive typography through the root `font-size`, and mobile tweaks for the
Works, Footer and Hero sections.

## Breakpoints

| Device | Media query |
|--------|-------------|
| Extra large | none |
| Desktop / large | `max-width: 992px` |
| Tablet / medium | `max-width: 767px` |
| Mobile | `max-width: 480px` |

## Tasks

| Files | Description |
|-------|-------------|
| `01-index.html`, `01-styles.css` | Fix the hero banner (`background-position`, `background-size`, `min-height`) |
| `02-index.html`, `02-styles.css` | Make `.container` flexible with `max-width` |
| `02-1-index.html`, `02-1-styles.css` | Fluid images; stack grid, latest news and hide the navbar under `767px` |
| `03-index.html`, `03-styles.css` | About and Latest News images with `srcset` / `sizes` |
| `04-index.html`, `04-styles.css` | Hidden checkbox + label icon; collapsible mobile menu |
| `05-index.html`, `05-styles.css` | CSS-only hamburger icon |
| `06-index.html`, `06-styles.css` | Open/close the menu from the checkbox state; mobile header and hero |
| `07-index.html`, `07-styles.css` | Responsive typography (`57%` / `60%` root font size) |
| `08-index.html`, `08-styles.css` | Always-visible Works card titles on mobile |
| `09-index.html`, `09-styles.css` | Centered footer navigation on mobile |
| `10-index.html`, `10-styles.css` | Fix the top header background with `.article-page` |

Images live in `images/` at the root of this directory.
