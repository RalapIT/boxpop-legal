# Boxpop Public Site

Static files for the public App Store privacy policy and support URLs.

## Files

- `index.html` - lightweight landing page
- `privacy.html` - App Store privacy policy URL source
- `terms.html` - user agreement / terms of use URL source
- `support.html` - App Store support URL source
- `styles.css` - shared styling

## Publish

Run `AppStore/publish-site.sh` from the repository root to sync this directory to the GitHub Pages repository.

Use the final public URLs in App Store Connect:

These must remain public HTTPS URLs served by GitHub Pages.

- Privacy Policy URL: `https://ralapit.github.io/boxpop-legal/privacy.html`
- User Agreement URL: `https://ralapit.github.io/boxpop-legal/terms.html`
- Support URL: `https://ralapit.github.io/boxpop-legal/support.html`

Before publishing, run `AppStore/verify-local-release.sh`; it checks that the HTML pages, stylesheet references, internal links, and required privacy/support copy are present.
