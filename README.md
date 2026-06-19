# Restaurant Zaraza — Presentation Website

Modern presentation website for a restaurant serving traditional Romanian cuisine. Built from scratch, focused on elegant design, performance, and an interactive experience for visitors.

## Demo

🔗 [View live](https://cristianilisei96.github.io/website-restaurant-zaraza/)

## Screenshot

![Restaurant Zaraza landing page](screenshots/landing-page.png)

## Features

- **Auto-rotating hero slider** — smooth crossfade between images, with progress indicators
- **Sticky navigation with scroll-spy** — the navbar stays fixed and automatically highlights the visible section
- **Photo gallery with lightbox** — click any image to view it full-size
- **Interactive table reservation modal** — the customer picks an available table from a visual floor map (10 tables, live availability status), fills in their details, and gets an instant confirmation
- **Contact form** — ready to be wired up to an email-sending endpoint
- **Embedded Google Maps** — location displayed directly on the contact page
- **Fully responsive design** — optimized for mobile, tablet, and desktop
- **Scroll animations** — elements fade/slide in smoothly as the visitor scrolls through the page

## Tech stack

- Semantic HTML5
- Tailwind CSS
- Vanilla JavaScript (no framework or external libraries)
- Google Fonts (Playfair Display, Inter, Yesteryear)

## Project structure

```
├── index.html
├── images/
│   ├── hero-1.jpg, hero-2.jpg, hero-3.jpg
│   ├── about.png
│   └── gallery-1.jpg ... gallery-4.jpg
└── screenshots/
    └── landing-page.png
```

## Running locally

No build step or dependencies required — it's a static site.

```bash
git clone https://github.com/cristianilisei96/website-restaurant-zaraza.git
cd website-restaurant-zaraza
```

Open `index.html` directly in your browser, or serve the folder with any static server (e.g. the Live Server extension in VS Code).

## Author

**Cristian Ilisei**
[GitHub](https://github.com/cristianilisei96)

## License

This project is available as a personal portfolio piece. The content (text, images) belongs to the restaurant featured.
