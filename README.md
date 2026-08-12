# jordanalegant.music

Personal site for Jordan Alegant — multi-instrumentalist, teacher, producer, and web audio developer based in northeast Ohio.

**Live at [jordanalegant.music](https://jordanalegant.music)**

## What this is

A hand-built static site. No frameworks, no build step, no dependencies — one HTML file, a handful of images, and the platform doing what it does best.

- **Dual theme** — Warm Linen (light) and Midnight Studio (dark), with a toggle that respects `prefers-color-scheme` and persists via `localStorage`
- **Typography** — Cormorant Garamond · DM Sans · JetBrains Mono
- **Streaming embeds** — Spotify / Apple Music toggle for featured tracks
- **Zero JS dependencies** — vanilla everything

## Structure

```
index.html              — the entire site (markup, styles, scripts)
jordan-photo.jpeg       — About section photo
jordan-performing.jpeg  — spare performance shot
favicon.svg             — JA monogram favicon (+ PNG sizes)
```

## Deployment

Deployed on [Netlify](https://netlify.com). Pushes to `main` deploy automatically.

To update the site: edit `index.html`, commit, done.

### Common edits

- **Gig bar** — search for `GIG BAR` in `index.html`; edit the one line, or delete the block to hide it
- **Tracks** — search for `PLAY` section; each track card has its streaming links and embed URLs together

## Related projects

The Build section links to live web audio apps:

- **Marionette** — resonance instrument with Csound physical modeling
- **WeatherGen** — generative ambient music driven by live weather
- **Arco** — string tuner with YIN pitch detection and instrument learning
- **ROOMTONE** — room acoustics analysis and EQ correction

---

Built by hand. 🎻
