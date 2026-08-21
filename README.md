# Whittle

Source for <https://108hertz.github.io/whittle-docs/> — the marketing landing page and the public
documents the app and the stores link to.

| File | Published as |
|---|---|
| `index.html` | `/` — marketing landing page (hand-written HTML) |
| `PRIVACY_POLICY.md` | `/PRIVACY_POLICY.html` |
| `TERMS_OF_USE.md` | `/TERMS_OF_USE.html` |
| `SUPPORT.md` | `/SUPPORT.html` |

## How it builds

A push to `main` runs `.github/workflows/deploy-pages.yml`, which converts every tracked Markdown
file (except this README) to HTML with pandoc and the `templates/page.html` shell, copies
`templates/assets/` to the site root, and publishes `index.html` as the landing page.

Adding a document is just adding a `.md` file — it is picked up automatically. Styling lives in
`templates/assets/css/style.css` (prose pages) and `landing.css` (landing page only); brand assets
in `templates/assets/img/` are copies of the originals in the app repo's `store/` directory.

The app links to these pages from **Settings** (see `ConfigLinks` in the app repo), so the published
paths above must not change without updating the app.
