# Inventory Automate (Web UI)

A single-file HTML mock for an AR-powered bar inventory app.  
Open `index.html` directly in your browser or serve it with a simple static server.

## Run locally

**Option A — double-click**
- Open `index.html` in Chrome/Edge/Safari/Firefox.

**Option B — dev server**
```bash
# from this folder
python3 -m http.server 5500
# then visit http://localhost:5500
```

## Deploy

- **GitHub Pages**: push this repo, then in *Settings → Pages* enable *Deploy from a branch* on `main` (root).
- **Netlify**: drag-and-drop this folder onto Netlify.

## Project structure

```
inventory-automate-web/
├─ index.html      # UI mock
├─ README.md
├─ .gitignore
└─ LICENSE
```

## Customize

- Edit text labels (brand name, buttons) in `index.html`.
- Wire the `startScan()` function to your AR capture flow (WebXR/model-viewer/native bridge).
