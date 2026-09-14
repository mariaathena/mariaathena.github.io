# mariaathena.com

Website for Maria Athena's fractional product management business (health-tech focus). Static HTML/CSS/JS, deployed via GitHub Pages to www.mariaathena.com.

## Structure

- `index.html` — home: hero, problem, what I do, who it's for / isn't for, how I work, testimonials, about, selected work, contact
- `css/style.css` — design tokens and component styles
- `js/main.js` — scroll-reveal animation, contact form confirmation
- `assets/athena-mark.png` — brand mark, used as favicon

The contact form has no backend yet — wire it to a form service (e.g. Formspree) before relying on it, or direct people to the mailto link.

## Not yet live

These exist locally but are intentionally **not committed** until the client signs off, since a push to this repo deploys straight to production:

- `case-studies.html` — index of engagements
- `case-study-ivf.html` — detailed case study (fertility/IVF client — needs their approval before publishing)
- `styleguide.html` — internal design reference; also quotes the same pending case study, so held back with it

Once approved: re-add the "Case studies" nav link in `index.html`, restore the case study summary section on the homepage (see git history for the previous version), and commit these three files.

## Local preview

No build step — open `index.html` directly in a browser, or serve the folder with any static file server.
