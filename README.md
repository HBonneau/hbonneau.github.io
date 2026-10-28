# Haggaï Bonneau — personal website

Research, scientific ML projects, publications, and CV.

Website: https://hbonneau.github.io/

## Pages

- `index.html` — biography, research illustration, and scientific ML project.
- `research.html` — research themes and figures.
- `publications.html` — publications with DOI links.
- `cv.html` — academic background, teaching, and downloadable CV.

## Editing

The website uses plain HTML and CSS. Edit the corresponding HTML page to update its content; styles are in `style.css`. Images and the academic CV PDF are stored in `assets/`. Research figure sources are documented in `assets/research/CREDITS.md`.

## Local preview

Run `python3 -m http.server 8765` from this directory, then open http://localhost:8765.

## Hosting

GitHub Pages publishes the `main` branch from the repository root. `.nojekyll` preserves the static files without a Jekyll build.
