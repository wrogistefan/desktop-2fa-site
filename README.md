# desktop-2fa-site

Astro-based landing page for [desktop-2fa](https://github.com/wrogistefan/desktop-2fa).

## Development

```bash
npm install
npm run dev
```

The changelog page fetches `CHANGELOG.md` from the
[desktop-2fa repository](https://github.com/wrogistefan/desktop-2fa) during
`npm run build`, so a build requires network access to GitHub.

## Content baseline

The site describes Desktop-2FA 0.11.0 (v0.11.0, commit
6457b420213f9bdc11fa5902b3bad5dc1792a75d) and Watch 0.3.0 (v0.3.0,
commit 187f8216510f6ebbb7806fe74db171d3f75975fe).

The desktop Textual UI is available now. Watch is a standalone development MVP;
selected-account transfer has a proposed contract but no transport/receiver/UI.
Its interoperability evidence pins Desktop 0.10.0, not 0.11.0. Paid Watch
positioning is planned, with no store-launch claim.

Selected synthetic terminal captures are in public/screenshots/textual-ui/;
Watch emulator images are in public/screenshots/watch-0.3.0/. Each directory
includes provenance notes. Historical CLI 0.10.0 assets remain unchanged.
Run npm run check and npm run build before reviewing the generated dist/.
This update does not deploy to Cloudflare.
