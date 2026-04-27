# Umami Fest – Sushi Festival Landing Page

A modern, responsive landing page for **Umami Fest**, an international avant-garde sushi festival that brings together the world's most innovative *itamae* masters for an unforgettable culinary experience.

## Description

This project is a single-page frontend deliverable built with semantic HTML5 and advanced CSS3. It presents the festival's identity through a dark, elegant visual language inspired by Japanese aesthetics — combining deep blacks, crimson red, and warm gold tones to evoke luxury and artisanal craft.

## Technologies Used

- **HTML5** — Semantic structure (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`)
- **CSS3** — Custom properties, Flexbox, CSS Grid, media queries, keyframe animations
- **Google Fonts** — Shippori Mincho (display) + DM Sans (body)
- **Vanilla JavaScript** — Hamburger menu toggle for mobile navigation

## Project Structure

```
umami-fest/
├── index.html      # Main HTML file (all styles and scripts are embedded)
└── README.md       # Project documentation
```

## Sections Included

| Section | Description |
|---|---|
| `<header>` | Fixed navigation with logo and responsive hamburger menu |
| Hero | Full-viewport intro with CTA buttons |
| Catas (Events) | HTML table with full tasting schedule |
| Festival (About) | Two-column layout with philosophy list |
| Chefs | Three-column card grid |
| Multimedia | Asymmetric photo gallery + video thumbnails |
| Sponsors | Horizontal sponsor list |
| `<footer>` | Contact info, social links, and site navigation |

## CSS Features

- **Responsive design**: Adapts to mobile (`<640px`), tablet (`<1024px`), and desktop (`>1024px`)
- **Media queries**: Layout changes for all breakpoints
- **CSS Grid & Flexbox**: Used throughout for layout and alignment
- **Animations**: `fadeUp`, `float`, `shimmer`, `pulse-red` keyframe effects
- **CSS Variables**: Full design token system for colors, fonts, and transitions

## How to Run Locally

1. Clone or download this repository
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No build tools or dependencies required — it runs entirely in the browser

```bash
# Optional: serve with a local server
npx serve .
# or
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Extra Points Implemented

- ✅ HTML table with `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>` for the full event schedule
- ✅ CSS animations (fadeUp, floating badge, shimmer gold logo, pulse CTA button)
- ✅ Additional sections: **Nuestros Chefs** and **Multimedia** gallery
- ✅ Responsive hamburger navigation menu for mobile

---

*Built with 🍣 HTML5 + CSS3 — Umami Fest 2025*
