# Portfolio — Abu Loman Hossain Shuvo

Interactive single-page portfolio site.

## Structure

```
.
└── portfolio/
    └── index.html   # self-contained site (HTML + CSS + JS, no build step)
```

## Run locally

Just open `portfolio/index.html` in a browser, or serve it:

```bash
cd portfolio
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy

Works as-is on GitHub Pages, Netlify, or Vercel — point the deploy root at `portfolio/`.
