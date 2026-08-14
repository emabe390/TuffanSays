# Tuffan Says

A static website that shows random cat pictures with a speech bubble pointing at the cat's mouth, as if the cat is speaking.

## How it works

On every page load a random cat photo and a random speech are chosen. A speech bubble is placed exactly at the annotated mouth position of the selected cat.

## Files

- `index.html` — the main website.
- `cat_photos.json` — list of cat images and their mouth coordinates.
- `speeches.json` — list of possible phrases.
- `annotate.html` — simple tool to annotate mouth coordinates on new photos.
- `source_img/` — original cat photos.

## Adding your own cats

1. Put your photos in `source_img/`.
2. Add entries to `cat_photos.json` with `"mouth": null`.
3. Open `annotate.html` in a browser, click on each mouth, and download the updated JSON.
4. Replace `cat_photos.json` with the downloaded file.
5. Commit and push.

## GitHub Pages

This site is ready for static hosting. Enable GitHub Pages in your repository settings and point it to the `main` branch.
