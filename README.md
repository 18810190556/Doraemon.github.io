# Yu Shi — Academic website

A dependency-free, English-language static website for GitHub Pages.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish

1. Review all public content, especially unpublished figures, working manuscript titles and public CV/summary. Confirm you have permission to share project assets.
2. Create a public repository named `YOUR-GITHUB-USERNAME.github.io` (or use a new project repository if you already have a user site). Do not overwrite an existing site.
3. Upload the **contents** of this folder, including `index.html`, `style.css`, `projects/`, `assets/`, and `.nojekyll`, to the repository root on `main`.
4. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
5. Use **Visit site** when deployment finishes. Verify navigation, figures, and PDFs.

Official guide: https://docs.github.com/en/pages/quickstart

## Update

- `index.html`: biography, research cards, publications, education and links.
- `projects/*.html`: individual technical project pages.
- `assets/`: original figures and field photographs, public CV and summary PDFs.
- `style.css`: shared responsive design.

No Google Scholar or GitHub profile URL has been guessed. Add the verified Scholar profile URL to the header/contact links after creation. Add actual demonstration videos only once their public-sharing status and URLs are confirmed. The VLA and GeoManeuver manuscript descriptions on the site are not asserted as final submitted titles. The public CV uses working-title notes for these two entries.
