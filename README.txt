SAMRITA — WEDDING WEBSITE UPDATE

Files included:
- index.html: full website with welcome intro, rope interaction, scratch-to-reveal golden invitation card, and main page
- soundtrack.mp3: existing soundtrack
- assets/: welcome intro artwork

Install:
1. Back up your GitHub Pages repository.
2. Replace index.html and soundtrack.mp3 in the repository root with the included files.
3. Upload the included assets/ folder to the repository root.
4. Keep your existing wedding photos, videos, and other media files in their original paths; this update does not replace them.
5. Commit and push to GitHub Pages.

Guest greeting: append ?guest=Chacha%20Chachi%20ji to the website URL. Missing guest names default to “Dear Family”.

Intro flow:
1. Welcome blessing — tap “Tap to begin”.
2. Pull the invitation rope.
3. Scratch the golden card to reveal the invitation details.
4. The intro closes and the main website opens.

Audio: soundtrack remains silent throughout the welcome, rope, and scratch-card stages. It starts only when the main page opens. Browser autoplay policies may still require a user interaction on some browsers; the guest has already interacted with the intro by this point.

The welcome intro appears once per browser session. “Replay welcome blessing” in the footer clears the session flag and reloads the intro. No Skip or separate Open Invitation button is included.
