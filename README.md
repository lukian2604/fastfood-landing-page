# FastFood Landing Page

🔗 Live Site: [fastfood-landing-page](https://lukian2604.github.io/fastfood-landing-page/)

## About

FastFood Landing Page is a responsive landing page for a fast food restaurant. The design focuses on a bold, dark aesthetic with accent colors and a clean layout — built entirely with HTML and CSS, no frameworks.

## Sections

- **Header** — logo, navigation menu with links, order button
- **Banner** — hero section with subtitle, title, description, and CTA button
- **Food List** — 4-card grid with image, title, and description
- **Order Section** — featured product with image, price, and order button
- **Product Grid** — 4 background-image cards with title, price, and order button
- **Feedback** — customer testimonial with user photo and quote
- **Download CTA** — full-width banner with download button
- **Footer** — logo, contact links, navigation lists, social media icons

## Tech Stack

| Technology | Details |
|---|---|
| HTML5 | Semantic markup |
| CSS3 | Custom properties, Flexbox, Grid |
| Fonts | Roboto Regular / Medium / Bold — self-hosted .woff2 |
| Icons | Custom SVG icons |
| Images | JPG / SVG assets |

## Project Structure

```
fastfood-landing-page/
├── index.html
├── fonts/
│   ├── Roboto-Regular.woff2
│   ├── Roboto-Medium.woff2
│   └── Roboto-Bold.woff2
├── icons/
│   ├── logo.svg
│   ├── email.svg
│   ├── global.svg
│   ├── feedback-icon.svg
│   ├── Feedback-users-foto.svg
│   └── social-media/
│       ├── facebook.svg
│       ├── instagram.svg
│       ├── twitter.svg
│       └── linkedin.svg
├── images/
│   ├── burger-banner-image.jpg
│   ├── burger-image.jpg
│   ├── food-list/          # 4 food category images
│   └── product-section-list/ # 4 product background images
└── styles/
    ├── normalize.css
    └── style.css
```

## Getting Started

No build step required — open `index.html` directly in a browser or serve with any static file server:

```bash
# Using VS Code Live Server, or:
npx serve .
```

## Deployment

This project is deployed via GitHub Pages from the `main` branch root.
