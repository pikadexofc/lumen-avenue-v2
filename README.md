# Lumen Avenue — Premium Static Website

This package contains a cinematic, responsive static rebuild of the Lumen Avenue landing page.

## Files

- `index.html` — production version using local assets.
- `preview-standalone.html` — single-file preview with images embedded.
- `assets/projects/01/cover.webp` through `assets/projects/04/cover.webp` — project section covers.

## Project cover replacement rule

The card system is mapped to your requested folder order:

1. `assets/projects/01/cover.webp`
2. `assets/projects/02/cover.webp`
3. `assets/projects/03/cover.webp`
4. `assets/projects/04/cover.webp`

Replace any cover image with the same filename and the card will automatically preserve the image ratio. No CSS change is required.

## Design notes

- Colors follow the original Lumen Avenue palette: obsidian black, wine red, cinematic maroon gradients, warm gold, and cream typography.
- Cards use natural image height, not forced distortion.
- Animations are built with vanilla JavaScript and CSS. No external runtime is required.
- Smooth scrolling is enabled on desktop and disabled on small mobile screens for stability.
