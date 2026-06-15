# UlarMark product site (mark.ular.io)

Static landing page + legal pages for the UlarMark macOS app, served via GitHub Pages.

## Stack
- HTML5 + Vuetify 3 (CDN), Google Fonts. No build step.
- Hosting: GitHub Pages (repo `ular-io/mark`), custom domain `mark.ular.io` (see `CNAME`).
- Deploy branch: `main` (push → Pages auto-build).

## Files
- `index.html` — landing page
- `privacy.html` — Privacy Policy (URL set in App Store Connect)
- `terms.html` — Terms of Service / EULA
- `open-source-licenses.html` — third-party notices (Material Design Icons, Apache 2.0)
- `assets/icon.svg` — app mark
- `CNAME` — `mark.ular.io`

## TODO before launch
- App Store badge links use the real app id (6780572862).
- Add real product screenshots (currently placeholder tiles).
- DNS: point `mark.ular.io` (CNAME → `ular-io.github.io`) — owner sets this in the DNS console.

## Local preview
```bash
python3 -m http.server 8000
```

## Notes
- Brand copyright spelling is **UlarioSoft** (not UlartioSoft).
- Support is handled in the `ular-io/ular-mark-support` repo (Discussions + Issues).
