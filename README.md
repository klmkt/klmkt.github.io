# Fattah Kalamukti – Game Developer Portfolio

Static portfolio site for GitHub Pages. Games play in the page through an iframe.

## Structure
```
index.html        portfolio page
.nojekyll         keeps GitHub Pages from processing game folders
games/
  projectile/     Unity WebGL build (index.html, Build/, TemplateData/)
  azon-in-space/  Unity WebGL build
assets/covers/    cover art (on-point.png and tap-and-flow.png are used for the two titles without a playable build)
```

## Add the builds
1. Extract each build zip and copy its contents into the matching `games/<name>/` folder. `index.html` must sit directly inside that folder, not in a sub-folder.
2. Unity: set Compression Format to Disabled or Decompression Fallback before building.
3. Delete the placeholder `README.txt` in each games folder (optional).

## Publish
Push to GitHub (use Git or GitHub Desktop; the web uploader limits files to 25 MB), then go to Settings > Pages and select branch `main`, folder `/ (root)`.
