# NELAR website starter

Static multi-page website: HTML, CSS and vanilla JavaScript. No paid builder, framework or build step.

## Pages
Home, Monitoring, Security, Infrastructure, Pricing, About and Contact.

## Before publishing
1. Edit `assets/config.js` and replace `REPLACE_WITH_YOUR_EMAIL`.
2. Confirm plan prices, billing terms and feature scope in `pricing.html`.
3. Review every product claim against what you currently deliver.
4. Test all pages and the contact flow on mobile and desktop.

The contact form opens the visitor's email application (`mailto:`). It does not submit data to a website backend. The homepage dashboard is an illustrative graphic, not a live product dashboard. There is no customer login, live telemetry or payment processing in this starter.

## Preview
Open `index.html`, or run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Free deployment
Cloudflare Pages is the recommended static host. Keep the domain registered at Namecheap and follow Cloudflare's current custom-domain instructions to connect `nelar.tech`.
