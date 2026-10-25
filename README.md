# kuatt.com

Personal site of Kuat Telegenov, served by GitHub Pages.

A single static page: no build step and no Jekyll (`.nojekyll` turns it off).

- `index.html`: the whole site (markup, styles and a small script)
- `assets/img/`: portrait (`kuat.jpg`) and social preview image (`og.jpg`)
- `favicon.svg`, `apple-touch-icon.png`: browser icons
- `sitemap.xml`, `robots.txt`: for search engines
- `CNAME`: custom domain

To preview locally:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
