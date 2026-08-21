# Pantri — public documents

The privacy policy, terms of use, and support page for the [Pantri](https://apps.apple.com/app/pantri) iOS app,
published so App Store Connect has public URLs to point at.

| Page | URL |
|---|---|
| Support | https://aerologefb.github.io/pantri-app/ |
| Privacy policy | https://aerologefb.github.io/pantri-app/privacy.html |
| Terms of use | https://aerologefb.github.io/pantri-app/terms.html |

## Do not edit the legal pages here

`privacy.html` and `terms.html` are **generated** from `Pantri/Views/Settings/LegalContent.swift`
in the private app repository, which is what a user reads inside the app. Editing them here would
let the hosted text drift from the in-app text.

To change them: edit `LegalContent.swift`, run `python3 scripts/build-docs.py` in the app repo,
then copy the rendered files here and push.

`index.html` (support) is hand-written and can be edited directly.
