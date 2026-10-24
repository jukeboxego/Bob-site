# BOB — Official Project Website

BOB is an independent creative project presented through a horror-inspired landing page with a sandy, gritty visual style. The website introduces the project and its creators, showcases selected artwork in a dedicated gallery, highlights games and inspirations, and features an interactive 3D preview of BOB.

## What's included

- **Main landing page (`index.html`)** — project introduction, creator information, social links, game tiles, and the interactive 3D model preview.
- **Art gallery (`gallery.html`)** — a separate page for viewing project imagery.
- **`assets/` folder** — website images, creator cards, and other visual assets.
- **`Bob/` folder** — the 3D model used by the preview (`Bob/bob-3d-model.glb`). Keep this folder and its path unchanged so the viewer can find the model.

## Copyright and asset ownership

**© 2026 Juke Box Ego and Buvl. All rights reserved.**

The original creative work and project assets included with this website are claimed by **Juke Box Ego and Buvl**, including original project artwork, creator graphics, website design, and the BOB model as applicable. Do not copy, redistribute, modify, or use these original materials without permission from their owners.

Any third-party names, trademarks, game titles, or third-party materials remain the property of their respective owners. Their appearance on this website does not imply sponsorship or endorsement.

## Run the website locally

For the 3D viewer to work reliably, run the site through a local web server rather than opening `index.html` directly as a `file://` URL.

### Option 1: VS Code Live Server

1. Extract the ZIP file.
2. Open the `BOB-Landing-Page-Optimized` folder in Visual Studio Code.
3. Install the **Live Server** extension if needed.
4. Right-click `index.html` and select **Open with Live Server**.

### Option 2: Python

1. Open a terminal in the extracted website folder.
2. Run:

   ```bash
   python -m http.server 8000
   ```

3. Visit `http://localhost:8000` in your browser.

The model-viewer script is loaded from jsDelivr, so an internet connection is required. When uploading to a host, include both the `assets/` and `Bob/` folders and preserve their names and paths.
