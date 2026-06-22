# Kids Wear

A responsive landing page for a children's fashion and care e-commerce store, built with pure HTML5 and CSS3 — no frameworks, no JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-none-lightgrey)

## Overview

Kids Wear is a full-page e-commerce landing page covering hero, product collections, new arrivals, baby care & toys, sneakers, trust badges, and a footer with newsletter signup. The project was built as an exercise in writing clean, maintainable, framework-free front-end code, with particular attention to fluid responsive design and CSS architecture.

## Features

- **Responsive across all breakpoints** — mobile, tablet, and desktop, using `clamp()` for fluid typography and spacing instead of fixed breakpoint jumps
- **Pure CSS mobile navigation** — a slide-in drawer triggered by a checkbox input, no JavaScript required
- **Facebook-style mobile shell** — fixed top bar and fixed bottom tab bar with scrollable content in between
- **3D flip product cards** — hover-triggered flip animation revealing a back face with quick-action icons (cart, wishlist, zoom)
- **3D flip social icons** — header social icons rotate on hover using a fully threaded `preserve-3d` transform chain
- **Hover-reveal image swap** — baby care & toys section swaps in a secondary image on hover using a single pseudo-element, no extra markup
- **Accessible by default** — every icon button has an `aria-label`, decorative icons use `aria-hidden`, and the newsletter form has a visually hidden but properly associated label
- **CSS custom properties** — shared values (brand color, section padding, link padding, header height) defined once in `:root` and reused throughout

## Sections

| Section | Description |
| --- | --- |
| Header | Sticky navigation with dropdown menus, social icons, search/account/cart |
| Hero | Promotional banner + main hero with fluid typography and CTA button |
| Collection | Three-card grid showcasing newborn and baby fashion collections |
| New Arrivals | Flip-card product grid with pricing, filterable by category nav |
| Offers | Promotional banner with gift highlights |
| Baby Care & Toys | Hover-swap product grid with carousel-style arrows |
| Sneakers | Product grid with descriptive copy for each shoe style |
| Trust Badges | Delivery, payment, quality, and gifting highlights |
| Footer | Newsletter signup, multi-column site links, social media, copyright |

## Tech stack

- **HTML5** — semantic markup
- **CSS3** — Flexbox, CSS Grid, custom properties, `clamp()`, pseudo-elements, 3D transforms
- **Font Awesome** — icon set
- **Google Fonts** — Great Vibes (display font)

## Project structure

```plaint text
├── index.html
├── css/
│   ├── style.css      # project styles
│   └── all.css         # Font Awesome
├── images/              # product and hero imagery
└── README.md
```

## Browser support

Built using modern CSS (`clamp()`, CSS Grid, `aspect-ratio`, `object-fit`, custom properties) — works in current versions of Chrome, Firefox, Safari, and Edge.

## Author

Built by Hayam Karam — frontend developer.

## Contributors

- Mohamed Ebrahim

## License

This project is for portfolio and demonstration purposes.
