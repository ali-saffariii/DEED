# DEED

A camera, film-simulation and image-processing app with an educational, gamified layer: photographic history, light spectrum, pixel-level algorithms (pixelate, threshold, ordered dither, posterize, ASCII art) and small coding challenges.

No ads, no clutter. The camera is the first screen; everything else lives in a pull-down panel (drag the handle at the top).

## Layout

- index.html : the complete web app (single file, WebGL). Open it through GitHub Pages on a phone.
- native/ : experimental Expo / React Native project (not yet tested on devices).

## Run the web app

Camera access needs HTTPS or localhost. With GitHub Pages enabled (Settings, Pages, Deploy from a branch, main, / (root)) the app is served at https://USERNAME.github.io/REPO/.
Locally:

    python3 -m http.server 8000

## Features

- Live film simulations: Kodachrome, Portra, Velvia, Cinestill, Tri-X, Daguerreotype, Calotype, Polaroid, Cyanotype
- Adjustable exposure, contrast, saturation, temperature, tint, grain amount and size, sharpness, vignette, look strength
- Algorithms with parameters: pixelate, threshold, ordered dither (Bayer), posterize, ASCII (columns, charsets, invert)
- Histogram and rule-of-thirds overlays
- Output as JPEG, PNG or WEBP with quality, resolution scale, full-sensor photo where the browser supports it, self-timer
- Personal looks, XP, levels, badges, quiz and demosaic challenge (stored locally)

## Limitations

- Browser canvas limits output to about 16 MP; no RAW or EXIF output.
- ISO, shutter and focus are available only where the browser exposes them (mostly Android Chrome).

## License

MIT
