# Melanie Rebecca — Portfolio

Static portfolio for GitHub Pages. No build tools or dependencies are required.

## Publishing

Push these files to the branch configured in your repository’s **Settings → Pages**.
For **Deploy from a branch**, either `/ (root)` or `/docs` works: both contain
an identical `index.html` and a `.nojekyll` file to serve the site as static HTML.
Keep your existing publishing branch and folder if Pages is already enabled.

## Editing

Edit `docs/index.html`, then copy it to the root `index.html` so both publishing
locations stay in sync. The older `index.md` files are retained as source archives;
the homepage is now `index.html`.

## Local preview

Run `python3 -m http.server 8000 --directory docs`, then open
http://localhost:8000 in your browser.

Google Fonts are optional external resources; system fonts are used if they are
unavailable. All page styling is included in the HTML.
