# Colince Lupin — Portfolio

Personal portfolio site for Colince Lupin, developer and designer. A single static page — no build step, no framework, no dependencies to install.

**Live site:** https://lupin-lion.github.io/portfolio/

## Features

- Responsive layout with a dedicated mobile nav, tuned for small and short (landscape) screens
- Light/dark theme toggle, persisted in `localStorage`
- Scroll-spy navigation, scroll-triggered section reveals, and a scroll progress bar
- Typing-effect tagline in the hero section
- Accessibility touches: skip-to-content link, `prefers-reduced-motion` support, labeled icon links
- SEO/social metadata: Open Graph and Twitter Card tags, JSON-LD `Person` structured data, `robots.txt`, and `sitemap.xml`

## Tech stack

Plain HTML, CSS, and vanilla JavaScript — everything lives in `index.html`. Fonts (Space Grotesk, Inter) are loaded from Google Fonts; no other external scripts or libraries.

## Project structure

```
portfolio/
├── index.html          # entire live site: markup, styles, and script
├── profile.logo.jpg    # profile photo / favicon
├── github.png, whatsapp logo.png,
│   gmail-icon-logo.png, facebook logo.png   # social icons
├── Streamer.PNG, wolf lord md logo.jpg,
│   martsautomobile.PNG,
│   academic-case-studies.png                # project thumbnails
├── robots.txt
├── sitemap.xml
└── Untitled-1.html      # earlier draft of the site, kept for reference (not linked/deployed)
```

## Running locally

It's a static page, so just open `index.html` in a browser, or serve it so relative paths behave the same as on GitHub Pages:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Sections

- **About** — brief introduction
- **Skills** — core skill cards (coding, design, writing, digital marketing) plus a tag cloud of tools/technologies
- **Projects** — Streamer Website, Wolf-MD WhatsApp Bot, Marts Automobile Website, Academic Case Studies
- **Contact** — WhatsApp, email, Facebook, and GitHub links

## Deployment

The site is served directly from this repository via GitHub Pages, pointed at `index.html` on the default branch. Pushing to the default branch updates the live site.

## Contact

- WhatsApp: https://wa.me/254799582173
- Email: colincesibuor122@gmail.com
- Facebook: https://www.facebook.com/share/1EpCRS7kx4/
- GitHub: https://github.com/Lupin-lion

## License

© 2025 Colince Lupin. Feel free to use this as a reference for your own portfolio, with credit.
