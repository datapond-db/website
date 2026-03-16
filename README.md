# datapond website

Static site for [datapond](https://github.com/datapond-db), deployed via GitHub Pages.

Single-page HTML site that fetches the database registry and renders it dynamically. No build step or framework required.

## Local development

Open `index.html` in a browser. The page fetches `registry.json` from the registry repo at load time.

## Deployment

Push to the branch configured for GitHub Pages. The site consists of a single `index.html` with inline CSS and JS.
