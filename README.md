# sam-yu-personal-website

Samuel Yu's personal site: an interactive 3D "action figure" résumé built with Three.js.

- `index.html` — the whole site (HTML, CSS and JS inline; Three.js loads from a CDN).
- `public/figure.glb` — the figure model (meshopt-compressed, WebP texture).
- `public/Samuel-Yu-Resume.pdf` — the résumé behind the "Download resume" button.

Edit résumé text in the `CONTENT` array at the top of the script in `index.html`.

## Run locally

The model is fetched at runtime, so open the site through a web server rather than double-clicking the file:

```bash
python3 -m http.server 8765
```

Then visit http://localhost:8765/.
