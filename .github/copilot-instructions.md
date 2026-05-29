# Copilot Instructions

## Architecture

This is a static personal academic homepage deployed via GitHub Pages. The entire site is a single `index.html` file (no build step, no framework, no bundler). Styles are inlined in a `<style>` block; there is no external CSS or JavaScript.

The `.nojekyll` file disables Jekyll processing — the HTML is served as-is.

## Design System ("kami")

The page uses a custom design system with these characteristics:

- **Color palette**: Warm parchment background (`#f5f4ed`), ink-blue brand accent (`#1B365D`), ivory sidebar (`#faf9f5`)
- **Typography**: Charter (serif) for body text, JetBrains Mono for labels and metadata
- **Layout**: Sticky sidebar (272px) + scrollable main content, using CSS Grid
- **Responsive**: Single-column layout below 900px with the sidebar becoming a top header

CSS custom properties are defined in `:root` — always use variables (e.g., `var(--brand)`, `var(--serif)`) rather than hardcoded values.

## Content Conventions

- **Sections**: Hero → Research Focus → Selected Work → Trajectory → Recognition → Contact
- **Publications**: Each item uses `.pub-item` with title, description, venue tags (`.pub-badge`), and links
- **Mono labels**: Section metadata and small labels use `font-family: var(--mono)` with uppercase + letter-spacing
- **Links**: External links open in `_blank` with `rel="noopener"`

## Deployment

Push to `main` branch triggers GitHub Pages deployment automatically. No CI/CD pipeline or build commands exist.
