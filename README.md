# Sachin & Amrita — Wedding Website V2

This is a local, mobile-first continuation build based on the public repository's documented Kashi design and the photos supplied in this conversation.

## Preview
Open `index.html` in a browser, or run `python -m http.server 8000` in this folder and open `http://localhost:8000`.

## Included
- 2021–2026 relationship timeline, using the five year-labeled photos and a 2026 Roka image.
- Four Roka images.
- Responsive Kashi-inspired editorial styling, polaroid cards, reveal motion, reduced-motion support.
- Event dates and a WhatsApp RSVP link.
- A restored “Moving memories” section with clear placeholders for the three existing reels.
- Background music button wired to `assets/soundtrack.mp3`.

## Media still needed
To restore the original project’s video and soundtrack playback, add:
- `assets/video/reel-stage.mp4`
- `assets/video/reel-walk.mp4`
- `assets/video/reel-traditional.mp4`
- `assets/soundtrack.mp3`

The Google Apps Script RSVP backend is not connected in this build. The RSVP button opens WhatsApp instead; connect and test the actual endpoint before treating this as a production RSVP system.

## Deploy
Upload the contents of this folder to the `main` branch/root of `raisachin/sachin-amrita-wedding`. Review the venue/address links and test the site after GitHub Pages redeploys. This package does not publish to GitHub automatically.
