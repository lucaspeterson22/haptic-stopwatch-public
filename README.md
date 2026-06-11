# haptic-stopwatch-public

A public repo for feature requests and bug reports for the Haptic Stopwatch app,
and the home of its public legal pages.

## Legal pages (GitHub Pages)

This repo hosts the app's **Privacy Policy** and **Terms of Use** via GitHub
Pages, linked from inside the app:

- [`index.html`](index.html) — landing page
- [`privacy.html`](privacy.html) — Privacy Policy
- [`terms.html`](terms.html) — Terms of Use
- [`assets/`](assets) — shared stylesheet and the app logo

Styling lives in [`assets/styles.css`](assets/styles.css) and follows the app's
brand: a bright cyan pulse on a near-black background, echoing the app icon.

### Enabling GitHub Pages

In the repo on GitHub: **Settings → Pages → Build and deployment**, set
**Source** to “Deploy from a branch”, branch `main`, folder `/ (root)`. The
pages will then be served at:

```
https://lucaspeterson22.github.io/haptic-stopwatch-public/
https://lucaspeterson22.github.io/haptic-stopwatch-public/privacy.html
https://lucaspeterson22.github.io/haptic-stopwatch-public/terms.html
```

The `.nojekyll` file tells Pages to serve the files as-is without Jekyll
processing.
