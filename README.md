# Pagewise – Free PDF tools

Merge, split, rotate PDFs and turn images into PDF. Everything runs in your browser, so your files are never uploaded anywhere.

## Features
- **Merge PDF**: combine files, reorder, preview, rotate each file, and make all pages portrait or landscape
- **Split PDF**: extract pages such as `1-3, 5`
- **Rotate PDF**: rotate every page by 90°, 180° or 270°
- **Images to PDF**: JPG and PNG to one PDF

## Publish with GitHub Pages
1. Create a new **public** repository on GitHub.
2. Upload `index.html`, `README.md`, `LICENSE` and `.nojekyll` to the repository root.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Tech
A single HTML file using [pdf-lib](https://pdf-lib.js.org/) for editing and [pdf.js](https://mozilla.github.io/pdf.js/) for previews, both loaded from cdnjs. No build step and no server.

## License
MIT
