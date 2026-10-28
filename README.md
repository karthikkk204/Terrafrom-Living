# TerraForm Living — React + JavaScript

A responsive furniture catalogue website built with React, JavaScript (JSX), CSS and Vite.

## Requirements
- Node.js 20.19+ or 22.12+ (Vite 7/8 compatible runtime)
- npm

## Run locally
1. Extract the ZIP.
2. Open the project folder in VS Code.
3. Open a terminal in the project folder.
4. Run `npm install`.
5. Run `npm run dev`.
6. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Create a production build
Run `npm run build`. The static site output is created in `dist/`. To preview it locally, run `npm run preview`.

## Pages and features
- `/` — homepage, materials, sustainability, manufacturing and export sections.
- `/collections` — product catalogue with category and material filters.
- `/products/cane-lounge-chair` — individual product detail pages (the final URL segment is the product slug).
- `/quote` — quote list, product finish and quantity selection, and a demo enquiry form.

Quote selections are saved in `sessionStorage` for the current browser tab. The enquiry form is a front-end demo and does not send an email or save enquiries to a server.

## Main source files
- `src/main.jsx` — application, page rendering, components, filters and quote interactions.
- `src/products.js` — product data and category/material options.
- `src/styles.css` — design tokens, Tailwind CSS utilities and reusable button/form styles.
- `public/images/` — original website images, including the hero and product photography.
- `vite.config.js` — standard Vite, React and Tailwind plugin configuration.

