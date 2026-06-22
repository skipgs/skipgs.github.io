# Project page scaffold

Static, no-build page modeled on the standard Nerfies/3DGS-style academic project page template.

## Fill in
Search for `TODO` in `index.html` and replace:
- Title, authors, affiliations, venue
- Link buttons (Paper PDF, arXiv, Code, Video, Data) — drop the PDF in this folder or point to arXiv
- `static/images/teaser.png`, `pipeline.png`, `results.png` — add your real images
- YouTube `VIDEO_ID` in the embed
- Abstract text and BibTeX entry

## Preview locally
```
cd project_page
python3 -m http.server 8000
```
Open http://localhost:8000

## Deploy with GitHub Pages
1. Push this folder's contents to a repo (e.g. `<paper-name>.github.io`, or any repo + enable Pages on a `docs/` or `gh-pages` branch pointing at this directory).
2. Repo Settings → Pages → set source to the branch/folder containing `index.html`.
3. Page goes live at `https://<user>.github.io/<repo>/`.
