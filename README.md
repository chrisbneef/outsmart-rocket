# Outsmart Rocket

The outsmartrocket.com website for Pre-Approve Me: a white-label mortgage app
that keeps independent loan officers on the buyer's phone from the first
daydream, through the loan, and for years after closing.

## Structure

- `index.html` - homepage (the solo loan officer's story)
- `enterprise/` - for mortgage companies
- `power-user/` - for power users
- `assets/` - app screenshots (Renegade Home Mortgage, Michael's own instance)
  and UI detail crops; `assets/full/` holds full-resolution sources

Static HTML/CSS, no build step. Serve the directory root with any static
server, e.g. `python3 -m http.server 8899`.

Messaging follows the StoryBrand package in the Pre-Approve Me project
(`storybrand/`); design system recorded in that project's `DESIGN.md`.

## Deploy

Auto-deployed by Vercel from `main`. `robots.txt` welcomes all crawlers
including AI answer engines; `sitemap.xml` lists the three pages.
