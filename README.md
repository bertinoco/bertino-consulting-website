# Bertino Consulting Website

This is a static website (vanilla HTML and CSS) for Bertino Consulting, a content systems practice that uses language to simplify complex products.

---


## Structure

```
bertino-consulting/
├── index.html       # Main website file
├── styles.css       # All styling and responsive design
├── robots.txt       # Crawler permissions (including AI bots)
├── sitemap.xml      # Single-page sitemap
├── llms.txt         # LLM visibility declaration (topical authority)
├── images/          # Hero photo, logo assets, OG image
├── .claude/         # Project slash commands (e.g. /design-review)
└── README.md        # This file
```

---

## Design

### Typography

- **All text:** Inter (Regular 400, Medium 500, Bold 700)
- Headings use tighter tracking (`letter-spacing: -0.02em`); body uses relaxed line height
- Section labels use uppercase 0.75rem with 0.1em letter spacing

### Spacing

Consistent 8px base unit: `8px, 16px, 24px, 32px, 48px, 64px, 96px`

### Motion

- **Durations:** `150ms` (fast), `200ms` (base), `300ms` (slow)
- **Easing:** `cubic-bezier(0.16, 1, 0.3, 1)` (ease-out spring)
- All animations respect `prefers-reduced-motion`

---

### Responsive

Fully responsive with breakpoints at:

- **Mobile:** < 768px
- **Tablet:** 768px – 1024px
- **Desktop:** > 1024px

---

## License

© 2026 Bertino Consulting AB. All rights reserved.

---

## Contact

Joe Bertino — [joe@bertino.co](mailto:joe@bertino.co)
