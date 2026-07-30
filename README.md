# SBD Simulator

A self-contained HTML, CSS, and JavaScript prototype for Seller Business Development HubSpot Deal training.

## Run locally

Copy the entire `SBD-Simulator` folder to any computer, then open `index.html` in a modern web browser. No installation, build process, server, or external dependency is required.

## Deploy to a static host

Upload the *contents* of this folder to the root of a static site (for example, a GitHub Pages repository). The site entry point is `index.html`.

The project uses only relative paths:

- `style.css`
- `app.js`

Keep `index.html`, `style.css`, and `app.js` together in the same folder after upload.

## SharePoint handoff

The SharePoint folder URL is configured in `app.js` as `sharePointFolderURL`. It can be changed there without modifying the application interface.

## Package contents

```text
SBD-Simulator/
  index.html
  README.md
  css/
    style.css
  js/
    app.js
```

