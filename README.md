# BOB — The Project

## Run the website so the 3D viewer works

Keep `index.html`, `gallery.html`, and the `assets/` folder together. The 3D model is loaded from `assets/bob-3d-model.glb`.

**Do not double-click `index.html` to test the 3D viewer.** Browsers restrict JavaScript modules and model assets opened from `file://`, so the viewer may stay on its loading message.

### Option 1: VS Code Live Server
1. Extract the ZIP.
2. Open the extracted `BOB-Landing-Page-Optimized` folder in VS Code.
3. Install the **Live Server** extension if needed.
4. Right-click `index.html` and choose **Open with Live Server**.

### Option 2: Python local server
If Python is installed, open a terminal in the extracted website folder and run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

The model viewer script is loaded from jsDelivr, so an internet connection is required. Make sure your hosting upload includes `assets/bob-3d-model.glb` and preserves the `assets` folder path.
