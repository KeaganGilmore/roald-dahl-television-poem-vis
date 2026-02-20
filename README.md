# Television — Roald Dahl (visual poem)

A small single-file static webpage that presents Roald Dahl's poem "Television" with a vintage/print-inspired layout and subtle animations.

> Note: This repository contains the full poem text inside `index.html`. Make sure you have permission to redistribute or publish the poem if you plan to host this project publicly — the poem is credited to Roald Dahl (from *Charlie and the Chocolate Factory*, 1964).

Contents
- `index.html` — the complete static page (HTML + embedded CSS) that renders the poem and visuals.
- `LICENSE` — repository license (see file for details).
- `DONATIONS.md` — donation information.

Quick start (view locally)

You can open the page directly in a browser by double-clicking `index.html`, or run a tiny local HTTP server from the project root to serve it:

For macOS / Linux / Windows (Python 3):

```bash
# from the project root
python3 -m http.server 8000
# then open http://localhost:8000/ in your browser
```

Or, simply open the file directly in your browser:

```bash
open index.html
```

What you'll see
- A typographic layout using Google Fonts (Playfair Display + Courier Prime).
- A stylized retro television graphic with animated scanlines/static.
- Staggered stanza reveal animations and themed sections (TV, shout, reading/book list, finale).

Development notes
- All styles are embedded in `index.html` inside a <style> block; there are CSS variables at the top for easy color tweaks.
- Key animations:
  - `flicker` — subtle TV body flicker
  - `scanlines` — moving scanlines over the TV screen
  - `staticMove` — simulated static movement
  - `fadeUp` / `popIn` — stanza reveal animations
- Fonts are loaded from Google Fonts via a link in the document head.

Suggested next steps
- If you plan to publish, check copyright/permissions for the poem text and either obtain permission or replace the text with a public-domain or original poem.
- Extract CSS to a separate file (e.g., `styles.css`) if you want to expand the project.
- Add responsive tweaks or print styles if you want to distribute printable versions.

Contributing
- Small tweaks and visual improvements welcome. Open a PR with changes.

Credits
- Poem: Roald Dahl — credited in the footer of `index.html`.
- Design & implementation: repository author.

License
See the `LICENSE` file in the repo for license details.

Donations
See `DONATIONS.md` for donation details maintained in the project.

If you want, I can:
- extract the styles into `styles.css` and update `index.html` to reference it,
- add a small preview script or GitHub Pages workflow,
- or add a permissive README excerpt that omits the poem text for public hosting guidance.

Tell me which of those (if any) you'd like next.
