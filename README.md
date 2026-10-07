# Willard-Monograph

A single-file editorial microsite: an illustrated "monograph" (travel guide) for Willard Peak and Box Elder County, Utah. Also carries unconfigured stock GitHub workflow templates.

## Features

- Editorial single-page site covering "the mountain," day trips near the peak (Ben Lomond connector, Antelope Island views), field notes, an insider's protocol "from locals," and a table of local places (Maddox, Gray's, paddleboard rentals, Cache National Forest)
- Interactive-map notes (pan/zoom/click pins; tiles credit Meta; static poster fallback if WebGL unavailable)
- Sunrise-light / elevation / range thematic sections

## Tech stack

- One bundled `Willard-Monograph.html`: React (compiled in-page) + Tailwind styles in a single file
- `.github/workflows/` — stock GitHub Actions templates (`terraform.yml`, `rust-clippy.yml`, `generator-generic-ossf-slsa3-publish.yml`); unconfigured (the Terraform one needs a `main.tf` and secrets that don't exist here)

## Getting started

No build step — open `Willard-Monograph.html` directly in a browser.

## Project structure

- `Willard-Monograph.html` — the entire site (markup, styles, logic)
- `.github/workflows/` — CI templates (unused)

## Status

Content-complete static page. Judgment call: the repo's value is the editorial page itself; the workflow templates add nothing and are disconnected from it.
