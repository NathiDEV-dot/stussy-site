# $tussy — Mfana ko West

Interactive artist desktop featuring music, artwork, biography, social links, release archive and opt-in fan camera.

## Hosting

Hosted with GitHub Pages from the root of `main`:
https://nathidev-dot.github.io/stussy-site/

The site is static HTML, CSS and JavaScript. No build step is required. `.nojekyll` disables Jekyll processing. Keep asset and data URLs relative so project Pages paths work.

To preview locally, serve this directory using a static web server, for example `python -m http.server 4173`, then open http://localhost:4173.

## Content

Edit `artist.json` for releases and artist links, `notes.json` for biography notes, `content.json` for gallery and release dates, and `projects.json` for the links app. Artwork is in `assets/`.

The portrait and release covers come from the artist's public Spotify profile. Spotify playback uses official embeds. Instagram and TikTok link to @stussydssr. Bookings link to @mdv.collective. Guestbook notes, favorites and camera photos save only in the visitor's browser.

GitHub is the publishing destination for this project. Push changes to `main` to update the Pages site.
