# Jibclips

Landing page for Jibclips. Plain HTML and CSS — no build step, no dependencies.

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | The whole page |
| `styles.css` | All styling; colours are CSS variables at the top |
| `assets/` | Images and video |
| `.github/workflows/pages.yml` | Deploys to GitHub Pages on every push to `main` |

## Previewing locally

Open `index.html` in a browser, or serve it:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploying

Pushing to `main` deploys automatically. One-time setup: in the repo's
**Settings → Pages**, set **Source** to **GitHub Actions**.

The site then lives at `https://billdjohnson.github.io/jibclips/`.

## Still to fill in

- Real Etsy shop URL (every `data-etsy` link in `index.html`)
- Headline and body copy — the `PLACEHOLDER` strings
- Images and video into `assets/`, replacing the `.placeholder` divs
- `assets/social-card.jpg` for link previews (1200×630)
