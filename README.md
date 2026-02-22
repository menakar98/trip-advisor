# TripAdvisor Clone

A responsive static clone of the TripAdvisor landing page built with **HTML** and **CSS** to practice layout, BEM methodology, and mobile-first design. No JavaScript — all interactions use pure CSS (accordions, form targeting, carousel).

![TripAdvisor Clone](https://static.tacdn.com/img2/brand_refresh_2025/vertical_lockups/vertical_lockup_primary.png)

## Key Highlights

- **Complete responsive page** — Optimized for mobile, tablet, and desktop
- **Animations via CSS only** — Carousel, hover effects, accordions — no JavaScript
- **Mobile-first development** — Base styles for mobile, enhanced with media queries for larger screens

## Features

- **Responsive layout** — Mobile-first design with breakpoints at 768px and 1024px
- **BEM naming** — Block-Element-Modifier convention for maintainable styles
- **CSS-only interactions** — Footer accordions (checkbox hack), search form switching via `:target`, image carousel with keyframe animations
- **Semantic HTML** — `header`, `main`, `section`, `article`, `footer`
- **Design tokens** — CSS variables for colors, spacing, and typography

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, animations, media queries)
- Custom font: Trip Sans (woff/woff2)

## Project Structure

```
tripadvisor-clone/
├── index.html          # Main markup
├── style.css           # All styles (BEM, organized by HTML order)
├── README.md
├── assets/
│   └── images/         # SVGs, explore cards, book slides, etc.
└── TripSans-*.woff2    # Custom fonts (root)
```

## Sections

| Section | Description |
|--------|-------------|
| **Header** | Sticky nav, burger menu (mobile), full menu (desktop) |
| **Categories** | Search All, Hotels, Things to Do, Restaurants — tab chips |
| **Search** | Category-targeted forms with pill layout on desktop |
| **Book** | CTA card with 4-slide CSS carousel |
| **Explore** | Horizontal card grids (by interest, recently viewed, iconic places, foundation blocks) |
| **Awards** | Travellers' Choice — dark full-width section |
| **Footer** | Accordion (mobile) / 4-column layout (desktop), selectors, social, legal |

## Getting Started

### Local

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/tripadvisor-clone.git
   cd tripadvisor-clone
   ```

2. Open `index.html` in a browser or use a local server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```

### Deploy to GitHub Pages

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / `master`, folder: **/ (root)**

## License

This project is for educational purposes. TripAdvisor is a trademark of Tripadvisor LLC.

---

**Author:** [Mohamed Asmaan](https://github.com/yourusername)
