# Shwe Taung Nyunt — Mineral Intelligence

A responsive high-tech mining landing page for `shwetaungnyunt.tech`, built as a lightweight static site with an interactive Three.js globe.

## Highlights

- Interactive, draggable 3D globe with mineral intelligence nodes
- Responsive hero, ticker, metrics, capabilities, manifesto and footer sections
- Self-contained HTML/CSS/JS; no build step or server runtime required
- Three.js is loaded from jsDelivr at runtime
- Accessible mailto CTAs and reduced-motion support

## Run locally

```bash
python3 -m http.server 4173
```

Then open <http://localhost:4173>.

## Hostinger VPS deployment

Upload `index.html` to the domain document root (commonly `/var/www/shwetaungnyunt.tech/public_html/` or the path configured by the VPS web server), configure Nginx/Apache for `shwetaungnyunt.tech` and `www.shwetaungnyunt.tech`, then issue a TLS certificate with Certbot. The page is static and does not require Node.js, a database, or a process manager.
