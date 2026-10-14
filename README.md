# Hydra

> The persistence of evil and chaos. Cut one down, two take its place.

A one-page interactive piece. Every time **Behead** is pressed, the head crumbles to dust, the page shakes, the stone sigil turns a full revolution, and two new heads rise somewhere else on the page.

Personal Practice Ⓢ — Machine Cult × MI

## Run locally

It's a static page with no build step. Open `index.html` directly, or serve the folder:

```sh
npx serve .
# or
python3 -m http.server
```

## Deploy with GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)`.

## Structure

```
index.html                      markup, styles and interaction
assets/sigil.webp               stone hydra sigil
assets/stone-texture.jpg        grain overlay for the buttons
assets/fonts/…-subset.woff2     PP Fragment Glare Regular, subset to the characters used
```

## Font licence

PP Fragment is a commercial typeface by Pangram Pangram. The subset in `assets/fonts` is included for this project only; confirm your licence covers web embedding before publishing this repository publicly.
