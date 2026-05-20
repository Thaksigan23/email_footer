# Techloom.ai Email Footer

HTML email signature footer for [Techloom.ai](https://www.techloom.ai).

**Live preview:** after GitHub Pages deploys → `https://thaksigan23.github.io/email_footer/preview.html`

**Repository:** [github.com/Thaksigan23/email_footer](https://github.com/Thaksigan23/email_footer)

## Files

| File | Use |
|------|-----|
| `email.html` | Default signature — background image, 600px, CDN assets |
| `email-outlook.html` | **Outlook desktop** — solid backgrounds, `<p>` layout, no CSS background image |
| `preview.html` | Browser preview with local `assets/` |
| `assets/` | Logo (PNG), background, icons (self-hosted) |

## Quick start

1. Open `preview.html` in a browser (or wait for GitHub Pages).
2. For your signature, open **`email.html`** (or **`email-outlook.html`** for Outlook).
3. Select the table → copy.
4. Paste into your email client signature settings (HTML / rich text mode).

## Client guide

### Gmail (web)

1. Settings → **See all settings** → **General** → **Signature**
2. Create signature → paste HTML (use **Insert signature** rich editor; paste from browser copy)
3. If images break, use **email-outlook.html** or ensure “Display external images” is allowed

### Outlook (Microsoft 365 / desktop)

1. File → Options → **Mail** → **Signatures**
2. Paste contents of **`email-outlook.html`** (recommended)
3. Use **Insert Picture** only if images still fail — CDN URLs should work after first push

### Apple Mail

1. Mail → Settings → **Signatures**
2. Paste `email.html`; works well with PNG logo and table layout

## Compatibility

| Feature | `email.html` | `email-outlook.html` |
|---------|--------------|----------------------|
| PNG logo | Yes | Yes |
| Background texture | Yes (`bgcolor` + CSS) | No (solid `#0f140e`) |
| Border radius | No | No |
| Stacked mobile layout | Yes | Yes |
| `mailto:` + labeled phones | Yes | Yes |
| Separate Colombo / Jaffna links | Yes | Yes |

**Tested targets:** Gmail web, Apple Mail, Outlook desktop (use `email-outlook.html`).

## Image URLs

Templates use jsDelivr (served from this repo):

```
https://cdn.jsdelivr.net/gh/Thaksigan23/email_footer@main/assets/...
```

For production, host `assets/` on `https://www.techloom.ai/` and replace URLs in both HTML files.

## Customize

- **Email address:** change `hello@techloom.ai` if your team uses another inbox
- **Colombo map link:** update the Google Maps query to your Colombo office address
- **Colors:** brand yellow `#FCEE21`, dark green `#0f140e` / `#161d15`

## Assets

See [assets/README.md](assets/README.md). Icons: [Icons8](https://icons8.com/) iOS Glyphs style (see license on Icons8 site).

## License

MIT — see [LICENSE](LICENSE). © Techloom.ai
