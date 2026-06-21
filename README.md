# Gavin Wyatt — Brisbane SEO Consultant Website

A single-page static website. No build step, no framework, no dependencies — just HTML
and CSS with two Google Fonts loaded from a CDN. It runs by opening the file in a browser.

## Files
- `index.html` — the entire website (HTML + CSS in one file)
- `assets/gw-logo.png` — the GW logo used in the nav
- `assets/gavin-about.jpg` — headshot used in the About section

## How to run it locally
Just open `index.html` in any browser. Or, from this folder, run a tiny local server:

    # Python (already on most Macs)
    python3 -m server.http 8000
    # then visit http://localhost:8000

(or use the VS Code "Live Server" extension and click "Go Live".)

## Editing with Claude Code
1. Download this project (see the chat for the download link) and unzip it.
2. Open the folder in your terminal and run `claude` (Claude Code).
3. Ask it for changes in plain English, e.g.
   - "Change the hero headline to …"
   - "Add a testimonials section under Services"
   - "Update the page title and meta description for Brisbane local SEO"
   - "Add a mobile hamburger menu for the nav links"

Everything lives in `index.html`, so Claude Code only has one file to edit for copy,
layout, and styling. Images are in `assets/`.

## Putting it online
It's a plain static site, so any static host works — Netlify, Vercel, Cloudflare Pages,
or GitHub Pages. Drag the folder into Netlify Drop, or point any host at this folder.
Set `index.html` as the entry page.

## Notes
- All "Email Me" buttons link to `hello@gavinwyatt.com` (4 places: nav, hero, contact CTA, footer).
- The single `<h1>` is "Brisbane SEO Consultant" (styled small, in the hero eyebrow) for local SEO.
- Fonts: Schibsted Grotesk (display), Hanken Grotesk (body), Spline Sans Mono (labels) — loaded from Google Fonts.
- Colors: ink `#0C0D12`, blue accent `#2417CE`, deep blue `#14123F`, paper `#FFFFFF`.
- To-do you may still want: update `<title>` / meta description to mention Brisbane, and add a mobile nav menu.
