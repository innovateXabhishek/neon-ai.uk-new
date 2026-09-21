# Neon AI — Command WALL

Production-ready static marketing site for **Neon AI** and the Command WALL product experience.

## Stack

- Semantic HTML5
- CSS (embedded for zero-build deployment)
- Vanilla JavaScript
- Responsive single-page hash routing
- Render Static Site hosting

## Local preview

Open `index.html` directly in a browser, or run a local static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deployment

The `main` branch is connected to Render with automatic deploys enabled. Every push to `main` publishes the latest site.

## Repository structure

```text
.
├── index.html
├── README.md
└── .gitignore
```

## Notes

The site is intentionally zero-build so it can be served directly from a CDN. Large embedded favicon data from the source export is replaced with a lightweight SVG favicon during repository preparation; page content and primary visual assets are retained.
