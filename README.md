# konstfed.github.io

Personal site of Konstantin Fedorov. Plain HTML and one stylesheet, no build step and no JavaScript, so it loads fast on a phone. GitHub Pages serves `main` as is (`.nojekyll`).

| To change | Edit |
|---|---|
| Home page (about, news, publications, talks, CV summary) | `index.html` |
| Paper pages | `diffie/index.html`, `gracg/index.html` |
| Styles (light and dark) | `style.css` |
| CV PDF, slides | `files/` |

To add a paper page, copy `gracg/index.html` into a new folder, edit it, link it from `index.html` and add it to `sitemap.xml`.

Local preview: `python3 -m http.server 8000`, then open <http://localhost:8000>.
