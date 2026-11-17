# GGibbson_exe — public website

Static, bilingual (DE/EN) informational website for GitHub Pages. **This repository must never contain the local GGibbson_exe application, secrets, OAuth credentials, databases, or video assets.**

## Deployment
Upload only the website files to the separate public `ggibbson-exe-website` repository. GitHub repository **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.

## Public URLs
- Home: `https://erikgrotelueschen.github.io/ggibbson-exe-website/`
- Privacy (EN): `https://erikgrotelueschen.github.io/ggibbson-exe-website/privacy.html`
- Terms (EN): `https://erikgrotelueschen.github.io/ggibbson-exe-website/terms.html`
- Legal notice: `https://erikgrotelueschen.github.io/ggibbson-exe-website/impressum.html`

## Before publishing
- Review the legal pages and verify provider details, hosting/privacy statements and the actual platform OAuth data flows.
- The legal texts are drafts for an informational website, **not a completed TikTok/Instagram production integration privacy policy**.
- This website does **not** implement OAuth callback endpoints. TikTok may require a separately approved HTTPS redirect/domain.
- No external scripts, tracking pixels, forms, or backend are included. GitHub Pages hosting still involves provider-side technical processing.
