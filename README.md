# harsh.

Personal one-pager — a minimal, cartoon-style biography site.

## What's inside

- `index.html` — the whole site (HTML + CSS + JS, no build step)
- `assets/harsh-toon4.png` — cartoon portrait

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server
```

## Deploy on GitHub Pages

1. Push this folder to a repo (e.g. `reachharsh.github.io`).
2. Repo → Settings → Pages → Source: `main` branch, `/ (root)`.
3. Your site will be live at `https://<username>.github.io`.

## Editing content

Everything lives in `index.html`:

- **Shelf ("Things I've made & shared")** — edit the `READS` array near the bottom of the file.
  - `tag: "Note"` + `body: [...]` → opens in a popup reader
  - `tag: "Video" | "Code" | "Article"` + `url` → opens the link in a new tab
  - Each item gets a shareable link: `yoursite.com/#read-<id>`
- **Rexy the dino** — hobby animations are in the `P` object (`guitar`, `karate`, `car`, …). Titles and one-liners are the `t` and `l` fields.
- **Speech bubble lines** — the `lines` array.
- **Colors** — CSS variables at the top (`--paper`, `--ink`, `--accent`).

## Fonts

[Fredoka](https://fonts.google.com/specimen/Fredoka) and [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts.
