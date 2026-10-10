Sachin & Amrita — Claude design preserved

This package uses the uploaded Claude index.html as the source of truth.
The layout, styling, sections, gallery, videos, event cards, and RSVP form have
been preserved. Changes are limited to:
- Correcting the Google Apps Script RSVP endpoint to the recovered endpoint.
- Setting soundtrack volume to 55%.
- Keeping the existing autoplay + first-interaction fallback and loop behavior.

IMPORTANT:
Keep your existing image/video assets and soundtrack.mp3 in the same GitHub
repository folder as index.html. This ZIP contains the HTML and this README,
not those media assets.

Browser note: mobile browsers may block autoplay with sound until a visitor
interacts with the page. The HTML attempts playback on load and on the first
tap/click/key interaction, and loops the soundtrack after playback starts.
