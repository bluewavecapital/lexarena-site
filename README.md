# LexArena placeholder site

One-page "coming soon" site for lexarena-us.com. Plain HTML and CSS, no build step.

- `index.html`: the page. From top to bottom: scale logo, "LexArena", "The arena opens in 2027.", globe logo.
- `assets/scale.png`, `assets/globe.png`: the two logos, white on transparent.
- `assets/favicon.png`, `assets/apple-touch-icon.png`: browser and phone icons made from the scale logo.

Colors: navy `#1E2761`, gold `#C9A227`. Headings use bold Cambria, with Caladea from Google Fonts on devices without Cambria.

## Preview

Open `index.html` in a browser.

## Deploy

GitHub Pages serves the `main` branch. To use lexarena-us.com, point the domain's DNS at GitHub Pages (A records for the apex domain, a CNAME record for www), then set the custom domain in the repository's Pages settings.
