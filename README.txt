CHILDWEI — Release v15 (Sleek-6 colors, v13 features)

Files:
- index.html (all interactions + dynamic theme-color + iOS orientation permission)
- manifest.json
- favicon-32.png, icon-192.png, icon-512.png, apple-touch-icon.png
- og-image.png

Deploy:
- Put files on any static host (e.g. GitHub Pages, Vercel, Netlify, or an Nginx directory).
- Ensure correct MIME types; no special server logic needed.
- For China mainland, consider hosting fonts locally to avoid Google Fonts blocking.

Tips:
- <meta name="theme-color"> updates live with the palette for nicer mobile UI.
- iOS will request device orientation permission on first tap if needed.
- If you prefer reduced motion, your OS setting will pause heavy animations.

