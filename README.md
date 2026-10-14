# Vibhor Chaudhary · Personal site

A single-page portfolio built with plain HTML, CSS and JavaScript. No build step and no dependencies, so it can be hosted as-is on GitHub Pages.

## Files

- `index.html` holds all page content (edit text here)
- `styles.css` holds the design: colors are tokens at the top, with a dark theme
- `script.js` handles the theme toggle, mobile menu, scroll reveals and count-up numbers
- `.nojekyll` tells GitHub Pages to serve the files untouched

## Run it locally

Opening `index.html` directly in a browser works. To serve it the way GitHub Pages will, run one of these from this folder and visit http://localhost:8000:

```bash
python -m http.server 8000
```

```bash
npx serve -l 8000
```

## Publish on GitHub Pages (later)

1. Create a repository (name it `<username>.github.io` for a root URL) and push these files to `main`.
2. In the repository, open Settings → Pages, set Source to "Deploy from a branch", and pick `main` / root.
3. The site goes live at `https://<username>.github.io/` (or `/<repo-name>/` for other repo names).
