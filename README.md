# Solgaard Lab

Source of [lab.solgaard.uk](https://lab.solgaard.uk): my Home Assistant and Zigbee projects, and device reviews.

Plain static HTML, served by GitHub Pages from `main` (custom domain in `CNAME`).

## Adding a review

Reviews live here in full, so they don't depend on the forum (or anywhere else) keeping them online.

1. Copy `reviews/repenic-rd-250zg/` to `reviews/<make-model>/`.
2. Replace the text, the date, the "First published on…" link and the forum links, and the `canonical` and `og:` URLs at the top.
3. Put the images in the same folder (download the originals; don't link to the forum's copies).
4. Copy a `<li class="review">` block in `index.html` and point it at the new folder, with the forum thread as the second link.
5. Commit and push.
