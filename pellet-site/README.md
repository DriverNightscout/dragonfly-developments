# Pellet Usage Monitor – Static Site

This repository contains the static marketing and support site for the Pellet Usage Monitor iOS app.

## File structure

```
pellet-site/
├── assets/
│   ├── logo-horizontal.svg
│   └── logo-square.svg
├── index.html
├── support.html
├── privacy.html
├── terms.html
├── styles.css
└── netlify.toml
```

## Local preview

You can preview the site locally with any static server. For example:

```
cd pellet-site
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` in your browser.

## Netlify deployment

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site** → **Import from Git**.
3. Select the GitHub repo and set:
   - **Base directory:** `pellet-site`
   - **Publish directory:** `.`
4. Deploy. Netlify will serve the site at `pellet.dragonflydevelopments.com` once the domain is connected.

## Notes

- Update the App Store link (`https://apps.apple.com/app/idXXXXXXXXXX`) when the app is live.
- The logo SVGs are simplified vector versions intended for web use.
