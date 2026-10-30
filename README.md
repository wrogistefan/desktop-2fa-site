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

The site describes Desktop-2FA 0.10.0 (released 2026-10-30). The D2FA Watch
section is a development announcement: desktop-to-watch transfer is still
being designed, and Watch is planned as a separate paid app.

Release screenshots in `public/screenshots/release-0.10.0/` were downloaded
from upstream commit `7d1089d6bee0f3f82678ca8a13988c742840fba0`.
The included upstream README and report describe synthetic data, capture
methods, and test limitations. Refresh images and captions together when
updating the release baseline.
