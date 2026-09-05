# Copilot Instructions

## Architecture

This is a static personal academic homepage deployed via GitHub Pages. The entire site is a single `index.html` file (no build step, no framework, no bundler). Styles are inlined in a `<style>` block; Google Fonts supplies JetBrains Mono. There is no executable JavaScript; the only script is JSON-LD structured data.

The `.nojekyll` file disables Jekyll processing — the HTML is served as-is.

## Design System ("kami")

The page uses a custom design system with these characteristics:

- **Color palette**: Warm parchment background (`#f5f4ed`), ink-blue brand accent (`#1B365D`), ivory sidebar (`#faf9f5`)
- **Typography**: Charter (serif) for body text, JetBrains Mono for labels and metadata
- **Layout**: Sticky sidebar (272px) + scrollable main content, using CSS Grid
- **Responsive**: Single-column layout below 900px with the sidebar becoming a top header

CSS custom properties are defined in `:root` — always use variables (e.g., `var(--brand)`, `var(--serif)`) rather than hardcoded values.

## Content Conventions

- **Sections**: About (including hero) → Research interests → Selected publications & reports → Research background → Recognition → Contact & profiles. Preserve the existing `hero`, `about`, `focus`, `work`, `trajectory`, `recognition`, and `contact` anchor IDs.
- **Publications**: Separate peer-reviewed publications from technical reports and model releases. Each paper uses `.pub-item` with its full title, author list in published order, venue/year (`.pub-badge`), a factual description, resource links, and native `<details>` for BibTeX. Match bibliographic metadata to the official proceedings.
- **Presentation**: Keep navigation and content usable without JavaScript. Avoid scroll-reveal effects, promotional badges, and undated citation counts.
- **Mono labels**: Section metadata and small labels use `font-family: var(--mono)` with uppercase + letter-spacing
- **Links**: External links open in `_blank` with `rel="noopener"`

## Deployment

Push to `main` branch triggers GitHub Pages deployment automatically. No CI/CD pipeline or build commands exist.
