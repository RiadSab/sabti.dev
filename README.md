# sabti.dev

Riad Sabti's portfolio. Plain HTML and CSS: no framework, no build step,
no backend. The blog lives at [blog.sabti.dev](https://blog.sabti.dev/).

## Files

- `index.html`: the whole page.
- `style.css`: colors, fonts and layout. The blog uses a copy of this file
  (`sabti-blog/static/style.css`), so copy it there after changing it.
- `theme.js`: the light/dark switch, also shared with the blog.
- `fonts/`: self-hosted WOFF2 subsets, with their licenses.
- `img/`, `favicon.svg`, `apple-touch-icon.png`, `og.png`: logo, icons and
  the link-preview image. `ristretto.png` is the original logo.
- `404.html`: the not-found page.

## Run locally

```sh
python3 -m http.server 4180
```

Then open http://localhost:4180.

## Deploy (Cloudflare Pages)

- Framework preset: None
- Build command: leave empty
- Build output directory: `/`
- Custom domain: `sabti.dev`
