# Material Calculator PWA

Mobile-first Material 3-inspired calculator built with HTML, CSS, and vanilla JavaScript.

## Files
- `index.html` — semantic UI and metadata
- `style.css` — responsive light/dark styling
- `script.js` — calculator parser, keyboard support, theme toggle
- `manifest.json` — PWA manifest
- `sw.js` — offline service worker
- `icons/` — placeholder PNG icons

## Run locally
Service workers require HTTPS or localhost. From this directory run:
`python -m http.server 8000`
Then open `http://localhost:8000`.

## Deploy
Upload the folder to a GitHub repository and enable GitHub Pages. For PWABuilder, use the published HTTPS URL.

## Notes
The included icon PNGs are placeholders; replace them with your own branded artwork before publishing. Google Fonts are loaded online, so text icons may fall back while offline if the font has not been cached.
