# Colince Lupin — Portfolio

Personal portfolio site for Colince Lupin, developer and designer. Built as a single static page — no build step, no dependencies.

**Live site:** https://lupin-lion.github.io/portfolio/

## Features

- Responsive layout with a dedicated mobile nav and tuned spacing for small/short screens
- Light/dark theme toggle (persisted in `localStorage`)
- Scroll-spy navigation, scroll-triggered section reveals, and a scroll progress bar
- Typing-effect tagline in the hero section

## Tech stack

Plain HTML, CSS, and vanilla JavaScript — no frameworks or build tooling. Fonts are loaded from Google Fonts (Space Grotesk, Inter).

## Project structure

```
portfolio/
├── index.html          # entire site: markup, styles, and script
├── profile.logo.jpg    # profile photo / favicon
├── *.png, *.PNG, *.jpg # project thumbnails and social icons
├── robots.txt
└── sitemap.xml
```

## Running locally

Since it's a static page, just open `index.html` in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Sections

- **About** — brief introduction
- **Skills** — core skills and a tag cloud of tools/technologies
- **Projects** — Streamer Website, Wolf-MD WhatsApp Bot, Marts Automobile Website, Academic Case Studies
- **Contact** — WhatsApp, email, Facebook, and GitHub links

## Contact

- WhatsApp: https://wa.me/254799582173
- Email: colincesibuor122@gmail.com
- Facebook: https://www.facebook.com/share/1EpCRS7kx4/
- GitHub: https://github.com/Lupin-lion

## License

© 2025 Colince Lupin. Feel free to use this as a reference for your own portfolio, with credit.
