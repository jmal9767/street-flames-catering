# Street Flames Catering

The Street Flames website from ChatGPT Sites, with its original logo, fonts, responsive design, and mobile navigation. The website is at the repository root and requires no build step or package installation.

Original Sites publication: https://street-flames.jmal9767.chatgpt.site

## Run locally

From this repository, run:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/.

## GitHub Pages

Use the `main` branch and `/ (root)` publishing directory in the repository's Pages settings. The existing `.nojekyll` file is retained. Relative CSS, JavaScript, image, and font paths support both a custom domain and the `/street-flames-catering/` project path.

## Files

- `index.html`: the imported Sites homepage.
- `styles.css`: responsive layout and local font declarations.
- `script.js`: mobile navigation and copyright year.
- `assets/`: original logo, fonts, and font license.
- `legacy/`: an unchanged copy of the repository's previous website.
- `admin.html`: forwards existing bookmarks to the previous admin page in `legacy/`.

The imported homepage is a brand website; it does not accept bookings or payments. The legacy inquiry form saves requests only in the visitor's browser, and the legacy admin screen is a browser-local demo, not a secure customer inbox. Neither provides a working cross-device booking service.

## Source and updates

Imported from Sites source commit `3f309cdaeb4b56aecc59ce6acf0522f02e95ead9`. Only asset URLs were made relative for portable hosting. Business content and the design are unchanged.

This repository contains a copy of the Sites website. There is no automatic synchronization between GitHub and the separate Sites project. Future changes need to be applied to the intended hosting source explicitly.

Font licensing is included in `assets/font-license.txt`.
