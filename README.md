# Flight Tracker custom-domain site

This version uses the supplied public myFlightradar24 profile:

https://my.flightradar24.com/felixthecatalt1

The Tracker page loads that exact page inside an iframe and also provides a direct-link fallback. The profile is currently publicly readable and shows the flight-log statistics on the supplied URL.

## Deployment

Upload the contents of this folder to Cloudflare Pages, GitHub Pages, Netlify, or another static host and attach your custom domain.

## Important

Whether the iframe renders depends on Flightradar24's current browser/security headers. If Flightradar24 prevents framing, the direct "Open Original" button still works. This site does not proxy or scrape the Flightradar24 page.

## Pages

- `index.html` — home
- `tracker.html` — your myFlightradar24 profile
- `about.html` — about page
- `assets/style.css` — styling
- `assets/app.js` — mobile menu and footer year
