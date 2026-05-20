# Assets

Bundled images for the Techloom.ai email footer.

| File | Purpose |
|------|---------|
| `logo.png` | PNG logo (220px source) — Outlook-safe |
| `logo.svg` | Source logo from [techloom.ai](https://www.techloom.ai) |
| `footer-bg.png` | Background texture |
| `icons/*.png` | Contact & social icons (iOS Glyphs style, `#FCEE21`) |

## Production hosting

Email clients load images from absolute URLs. By default, templates use jsDelivr:

`https://cdn.jsdelivr.net/gh/Thaksigan23/email_footer@main/assets/...`

For production, copy these files to `https://www.techloom.ai/` and update URLs in `email.html` / `email-outlook.html`.

## Icon attribution

Contact and social icons are based on [Icons8](https://icons8.com/) iOS Glyph style. See [Icons8 license](https://icons8.com/license) for usage terms.
