# Kine Memling

One-page website for Kine Memling, Rebecca Taillieu's physiotherapy practice in Overijse: https://kinememling.be

- `index.html`: the whole site (styles and scripts inline).
- `images/`: photos, compressed for the web.

## Languages

The site is in Dutch (default), French, English and Portuguese (PT). All texts live in the `I18N` object at the bottom of `index.html`. On a first visit the language follows the browser settings and falls back to Dutch; a choice made in the language menu is remembered.

## Adding a service photo

Add the photo to `images/` and add an entry to the `CARDS` list in `index.html`. Up to four cards show side by side on a wide screen; arrows appear automatically when there are more.
