# Shimon Baron — Personal Website

A one-page professional profile / online CV for Shimon Baron, CMO | VP Marketing in fintech, trading & brokerage.

**Live URL:** https://shimonbaron.github.io/shimon-baron-site/ (placeholder)

## Run locally

No build step. Open `index.html` in any browser.

## Swap in a real photo

1. Add the photo as `assets/photo.jpg` (square, at least 336×336 px).
2. In `index.html`, find the `<div class="avatar" ...>SB</div>` line in the hero and replace it with:

   ```html
   <img class="avatar" src="assets/photo.jpg" alt="Shimon Baron" width="160" height="160">
   ```

The `.avatar` styles keep it circular.

## Tech

- Plain HTML5, CSS (custom properties, light/dark via `prefers-color-scheme`) and a few lines of vanilla JS for fade-in on scroll
- Inline SVG icons, SVG favicon and Open Graph image
- JSON-LD `Person` schema, Open Graph and Twitter card tags
- Ready for GitHub Pages

Built for the 10X course, lesson 7, with Claude Code.
