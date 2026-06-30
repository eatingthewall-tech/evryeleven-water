# evryeleven — water landing page

A single static landing page: a glass/water "evryeleven" wordmark (rendered in Blender)
over a stormy-blue cloud backdrop, with a top navigation bar and a scroll cue.

## Structure
```
index.html        markup (header nav, hero image, scroll cue)
styles.css        layout + type, full-bleed background, responsive
assets/
  background.png  stormy cloud / wet-floor backdrop
  evryeleven.png  transparent glass wordmark (Blender / Cycles render)
```

## Run locally
Any static server works, e.g.:
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy (GitHub Pages)
Settings → Pages → Build from branch → `main` / root. The site is fully static.
