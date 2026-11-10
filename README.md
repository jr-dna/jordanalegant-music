# jordanalegant.music

Personal site for Jordan Alegant — multi-instrumentalist, teacher, producer, and web audio developer based in northeast Ohio.

**Live at [jordanalegant.music](https://jordanalegant.music)**

## What this is

A hand-built static site. No frameworks, no build step, no dependencies — one HTML file, a handful of images and audio clips, and the platform doing what it does best.

- **Dual theme** — Warm Linen (light) and Midnight Studio (dark), with a toggle that respects `prefers-color-scheme` and persists via `localStorage`
- **Typography** — Cormorant Garamond · DM Sans · JetBrains Mono
- **Song previews** — self-hosted 30-second clips with a waveform player, beside each track's streaming links
- **Zero JS dependencies** — vanilla everything

## Structure

```
index.html              — the entire site (markup, styles, scripts)
404.html                — the not-found page (self-contained)
previews/               — 30-second song clips for the Play section
app-*.jpg               — screenshots for the Build cards
jordan-photo.jpeg       — About section photo
jordan-performing.jpeg  — spare performance shot
og-image.jpg            — link-preview image
favicon.svg             — JA monogram favicon (+ PNG sizes)
```

## Deployment

Deployed on [Netlify](https://netlify.com). Pushes to `main` deploy automatically.

To update the site: edit `index.html`, commit, done.

### Common edits

- **Gig bar** — search for `GIG BAR` in `index.html`; edit the one line and set `data-until` to the last day it should show (the bar removes itself after that), or delete the block to hide it
- **Tracks** — search for the `PLAY` section; each track card has its streaming links and, where there is one, a preview clip in `previews/`

## Related projects

The Build section links to four web apps and one Mac utility:

- **Marionette** — resonance instrument with Csound physical modeling
- **WeatherGen** — generative ambient music driven by live weather
- **Arco** — string tuner with YIN pitch detection and instrument learning
- **ROOMTONE** — room acoustics analysis and EQ correction
- **Vigil** — macOS menu bar app that shows what's keeping a Mac awake, and stops it

---

Built by hand. 🎻
