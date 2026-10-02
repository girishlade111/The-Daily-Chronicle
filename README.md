# The Daily Chronicle

A modern, responsive newspaper/news-website front page template — "up-to-the-minute news" style homepage with category navigation, featured stories, article grids, and a classic broadsheet aesthetic rebuilt with Tailwind CSS.

## Features

- **Newspaper-style homepage** — masthead, date line, mega-menu category navigation
- **Featured/hero story** layout plus multi-column article grids
- **Category sections** (e.g. World, Business, Technology) with hover mega-menus
- **Typography-led design** — heavy 900-weight brand title, Inter font family
- **Font Awesome icons** throughout
- **Fully responsive** — single column on mobile, 3-column grids on desktop

## Tech Stack

- **Single `index.html`** — HTML5, Tailwind CSS (CDN), vanilla JavaScript
- **Fonts:** Google Fonts (Inter)
- **Icons:** Font Awesome 6.4

No build step, no dependencies, no backend. Content is demo/sample articles baked into the markup — wire a news API or CMS in later if you want live headlines.

## Quick Start

1. Clone or download this repository.
2. Open `index.html` directly in a browser, **or** serve it locally:
   ```bash
   npx serve .
   ```
3. Edit `index.html` to swap in your own branding and stories.

## Project Structure

```
The-Daily-Chronicle/
├── index.html   # The entire news front page (layout + demo content)
├── LICENSE
└── README.md
```

## Deploy Notes

Pure static site — deploy anywhere static hosting works:
- **GitHub Pages:** branch `main`, path `/` → https://girishlade111.github.io/The-Daily-Chronicle/
- Any static host (Cloudflare Pages, Netlify, Vercel) — no build command needed.

## License

See `LICENSE`.

---

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
