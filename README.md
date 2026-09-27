# Cositas

Static landing page for "Cositas", a kids' baking/craft workshop business: hero section, photo gallery, activities list, embedded Google Maps location, and a WhatsApp contact link.

> Learning project built between October and November 2023 while practicing plain HTML/CSS layout, a scroll-based parallax effect and embedding third-party content (Google Maps, WhatsApp links). Kept public as part of my learning history.

Live: https://cristopherreyesp.github.io/Cositas/Cositas/

## What it does

The site (`Cositas/index.html` + `Cositas/style.css`) has a header with a checkbox-driven mobile menu, a hero section whose decorative background images move on scroll (a small inline `<script>` translates `.image__foregound` based on `window.pageYOffset`), a CSS grid photo gallery (`#G`), an "activities" section describing workshops (crafts, cupcake and cookie decorating) with alternating image/text blocks, an embedded Google Maps iframe for the location, and a footer with a WhatsApp link and address. There is no JavaScript framework and no backend — everything is static markup plus one inline scroll listener.

## Tech Stack

- Plain HTML5 and CSS (CSS custom properties used for per-box background images in the gallery)
- No build tooling or JS framework

## Running Locally

Open `Cositas/index.html` directly in a browser, or serve the `Cositas/` folder with any static file server. The page is also published via GitHub Pages at the live URL above.

## What I practiced

- CSS Grid for a photo gallery layout
- A scroll event listener driving a simple parallax-style transform
- Embedding third-party content (Google Maps iframe, WhatsApp `wa.me` links)
- Structuring a small marketing/landing page with header, hero, content sections and footer
