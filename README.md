# BIO UNIT 1 — 60HR ATLAS

A cinematic, single-file study tracker for **Class 11 NCERT Biology** — built entirely in vanilla HTML, CSS, and JavaScript. No frameworks. No dependencies. Just one `.html` file you open in a browser.

🌐 **Live Site → [astroxhype.github.io/UNIT-1-BIOCLASSXI](https://astroxhype.github.io/UNIT-1-BIOCLASSXI)**

---

## What it is

An immersive visual study dashboard that maps out all 60 hours of Class 11 Biology across 4 chapters, their topics, and every subtopic — with progress tracking, done states, and a beautiful UI that makes studying feel less like a chore.

---

## Features

- **Cinematic Hero Screen** — split-layout hero with animated orbs, scan line, noise grain, vertical timeline bar, staggered title animation, and a giant rotated *BIOLOGY* watermark
- **Animated Ticker** — scrolling marquee of chapter and topic names
- **Chapter Cards** — glowing Bodoni italic titles, chapter-color orb bloom, diagonal texture, glowing hour counters, pill tags, hover CTA
- **Topic Cards** — per-chapter topic grid with progress bars, difficulty label, and ghost number watermark
- **Subtopic Bento View** — full-page cinematic detail view with hero header, progress bar, stats, and a bento grid of subtopic cards
- **Subtopic Cards** — square cards with giant italic center word, glowing accent bar, chapter-colored glow fill on completion, ghost number, keyword pill, read-time estimate
- **Done State Tracking** — mark any subtopic done; card fills with a glowing color animation; progress bars update live
- **Ripple + Stamp Animation** — click-origin ripple rings and stamp overlay on done toggle
- **Persistent Progress** — all done states saved to `localStorage`, survive page reloads
- **60-Hour Distribution Bar** — segmented progress bar showing time allocation across chapters
- **20-Day Timetable** — day-by-day study plan grid
- **Fully Responsive** — adapts from desktop to mobile

---

## Chapters Covered

| # | Chapter | Hours |
|---|---------|-------|
| 01 | The Living World | 6h |
| 02 | Biological Classification | 12h |
| 03 | Plant Kingdom | 18h |
| 04 | Animal Kingdom | 20h |
| — | Revision | 4h |

**Total: 60 hours · 4 chapters · 40+ topics · 300+ subtopics**

---

## How to Use

1. Download or clone this repo
2. Open `60hrs study.html` in any modern browser
3. Click a chapter card → explore topics
4. Click a topic card → open the subtopic bento view
5. Click any subtopic card to mark it **DONE**
6. Progress is saved automatically in your browser

```bash
git clone https://github.com/astroxhype/UNIT-1-BIOCLASSXI.git
cd UNIT-1-BIOCLASSXI
open "60hrs study.html"
```

> No build step. No npm install. Just open the file.

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Structure | Vanilla HTML5 |
| Styling | Vanilla CSS3 (variables, grid, animations, `color-mix`, `clip-path`) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Clash Display · Bodoni Moda · Chivo Mono · Cabinet Grotesk · Space Grotesk |
| Storage | `localStorage` for progress persistence |
| Dependencies | **None** |

---

## Design Highlights

- Dark `#070707` base with multi-layered atmospheric backgrounds
- Chapter accent colors: `#c8ff00` · `#ff6b35` · `#00d4ff` · `#ff3d9a`
- `color-mix()` for dynamic tinted UI elements
- `@keyframes` animations: orb float, scan line, text reveal, ripple, card pop, glow pulse
- `CSS custom properties` (`--bn-color`, `--tp-badge-color`) for per-card theming
- Bodoni Moda italic for editorial typographic hierarchy
- Clash Display for large-scale display numerics

---

## License

MIT — use it, fork it, study with it.

---

*Built for one purpose: making 60 hours of biology actually feel worth it.*