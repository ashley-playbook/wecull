# wecull.com

Marketing site and legal pages for the **Wecull** app — where parents share YouTube
and TikTok videos to a safe, curated feed their kids can watch without the apps.

Static site, no build step. Hosted on Cloudflare Pages at `wecull.com`.

## Pages

| File | URL |
|------|-----|
| `index.html` | `wecull.com` — landing page |
| `privacy.html` | `wecull.com/privacy` — Privacy Policy |
| `terms.html` | `wecull.com/terms` — Terms of Service / EULA |
| `APP-ICON.png` | favicon + social share image |

> Cloudflare Pages serves `privacy.html` at `/privacy` and `terms.html` at `/terms`
> automatically. Locally, open the `.html` files directly.

## Deploy

Upload the contents of this repo to the Cloudflare Pages project, and point
`wecull.com` + `www.wecull.com` at it. Keep `APP-ICON.png` in the upload (used for
the browser tab icon and link previews; the on-page logo is inline SVG).
