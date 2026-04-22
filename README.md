# Harshit Raheja — Portfolio

A motion-rich, single-page portfolio built with plain HTML / CSS / JS. No build step required.

## Quick start

1. **Add your photo**: drop a square or portrait-oriented image at `assets/profile.jpg`.
   Until you do, the portrait area shows an animated "HR" monogram fallback.
2. **Preview locally** — either open `index.html` directly in a browser, or for best results serve it:
   ```bash
   cd Portfolio
   python3 -m http.server 8000
   # then visit http://localhost:8000
   ```

## Deploy (free)

**Vercel** — easiest:
1. Push this folder to a GitHub repo.
2. Import the repo at [vercel.com/new](https://vercel.com/new).
3. Vercel auto-detects it as a static site. Deploy.

**GitHub Pages**:
1. Push to a repo named `Harshit50.github.io` (or enable Pages on any repo).
2. Done — it'll be live at `https://harshit50.github.io/<repo>`.

**Netlify** — drag-and-drop the `Portfolio` folder at [app.netlify.com/drop](https://app.netlify.com/drop).

## Structure

```
Portfolio/
├── index.html     # all sections
├── styles.css     # design system + animations
├── script.js      # cursor, scroll reveal, parallax
└── assets/
    └── profile.jpg  # (you add this)
```

## Editing content

Every section lives in `index.html` with clear comments (`<!-- HERO -->`, `<!-- PROJECTS -->`, etc). To update:
- **Projects** — edit the `.proj-card` blocks in the Projects section
- **Experience** — edit the `.tl-item` block in the Experience section
- **Skills** — edit the `.skill-col` blocks in the Skills section

## Design notes

- **Fonts**: Space Grotesk (headings), Inter (body), JetBrains Mono (code/meta)
- **Palette**: purple → pink → orange gradient on dark backdrop
- **Motion**: custom cursor, scroll-reveal, parallax portrait, marquee ticker, floating blobs, animated badges
