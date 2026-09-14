# Preggrs — public pages

The privacy policy, terms and support pages for the **Preggrs** iOS app, served
by GitHub Pages so they resolve at a public URL. Both the App Store and Google
Play reject a submission whose privacy-policy URL does not load, which is the
only reason this repository is separate and public — the app itself is private.

| Page | URL |
|---|---|
| Home | `/` |
| Privacy Policy | `/privacy.html` |
| Terms of Use | `/terms.html` |
| Support | `/support.html` |

## Editing

`privacy.html` and `terms.html` are generated from `docs/privacy.md` and
`docs/terms.md` in the app repository, so the published text and the text the
app ships against cannot drift. **Edit the markdown there**, then regenerate —
do not hand-edit the HTML here.

`index.html`, `support.html` and `style.css` are authored here directly.

## Not in this repository

Deliberately: the release runbook, the design specs and anything else from the
app's `docs/` directory. This repository is public, and only the pages a user
or a store reviewer needs belong in it.
