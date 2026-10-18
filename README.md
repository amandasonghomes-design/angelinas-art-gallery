# Angelina’s Art Gallery

A responsive midnight-blue and champagne-gold gallery built with HTML, CSS, and JavaScript. Includes artwork filters, zoomable artwork and publication viewers, five matching Christmas pictures with the outer margins hidden, a page-turning comic, and the Breakfast Dragon video.

## Run locally

Install Python 3, open a terminal in this folder, and run:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. There are no package dependencies, API keys, or build steps.

## Edit the gallery

- `dist/index.html`: page sections, artist biography, publications, and awards.
- `dist/style.css`: colors, typography, layout, mobile styling, and Christmas frame cropping.
- `dist/app.js`: artwork catalog, filters, modal viewer, and image zoom.
- `dist/assets/`: all runtime artwork, documents, comic reader, and video.

The comic reader is self-contained. Christmas images retain their original image bytes and use the website’s existing CSS crop. Publication images are the privacy-edited copies used on the website.

## Upload to GitHub

After creating an empty repository on GitHub, run these commands from this folder:

```sh
git init -b main
git add .
git commit -m "Add Angelina art gallery"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the example URL with your repository URL. Authenticate through GitHub’s supported login flow; do not put passwords or tokens in source files.

## Optional: publish with GitHub Pages

Publishing is separate from uploading the source. The included workflow runs only when manually requested.

1. In the GitHub repository, open Settings → Pages and select **GitHub Actions** as the source.
2. Open Actions → Deploy gallery to GitHub Pages → Run workflow.
3. Open the URL shown by the deployment job.

All asset paths are relative, so the gallery supports GitHub Pages project URLs. GitHub Pages availability depends on repository visibility and your plan. A Pages deployment may be public even if its repository is private; review the GitHub Pages settings before publishing. This does not change the existing ChatGPT-hosted gallery or its access settings.

## Rights

Artwork and writing belong to their respective creators. No open-source license or permission to reuse the artwork is granted by this repository. AI-assisted story illustrations and restored display images are identified in the gallery.
