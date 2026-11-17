# Yacht Fleet Accounting

A self-contained, single-file static prototype of a yacht fleet accounting dashboard (HTML, CSS, and JavaScript inline).

**Live site:** https://kadeemhaughton.github.io/Yatch-company/

## About

The entire application ships in one file. All styles and scripts are inline, so there is no build step and no framework. The only external dependency is Google Fonts loaded over HTTPS.

- `index.html` is the entry point served at the site root.
- `yacht_fleet_accounting.html` is the original prototype file (identical content).
- `.nojekyll` disables Jekyll processing so GitHub Pages serves the files as is.

## Running locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```
