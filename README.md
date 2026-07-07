# Flip-Book-Template

A browser-based flip book template built on [turn.js](https://github.com/blasten/turn.js), used here for the **12th SSLSAS 2026 Abstract Book** (Faculty of Social Sciences and Languages, Sabaragamuwa University of Sri Lanka).

## Structure

- [index.html](index.html) — animated landing page with a launch button and countdown that redirects into the flip book.
- [2026/index.html](2026/index.html) — the flip book viewer (turn.js) that renders the abstract book pages.
- [2026/pages/](2026/pages/) — page images (`1.jpg` – `10.jpg`) displayed in the flip book.
- [2026/slider.html](2026/slider.html) — alternate slider view.
- [2026/js/](2026/js/), [2026/lib/](2026/lib/), [2026/extras/](2026/extras/), [2026/css/](2026/css/) — turn.js library, jQuery dependencies, and supporting scripts/styles.
- [2026/pics/](2026/pics/) — UI assets (zoom icons, loader, arrows).

## Usage

Open [index.html](index.html) in a browser, click **LAUNCH**, and the countdown will redirect to the flip book at `2026/index.html`. To go straight to the book, open `2026/index.html` directly.

To reuse this template for a new year/event:

1. Replace the images in `2026/pages/` with your own page scans (keep the numeric naming, e.g. `1.jpg`, `2.jpg`, …).
2. Update the title and copy in `index.html` and `2026/index.html`.
3. Adjust the page count/dimensions in `2026/js/magazine.js` if needed.

## License

See [LICENSE](LICENSE).
