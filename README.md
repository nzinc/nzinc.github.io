# NZINC Website — editable static package

A responsive multi-page website built with plain HTML, CSS and JavaScript.

## Pages
- `index.html` — homepage
- `about.html` — about and approach
- `projects.html` — project portfolio with the two supplied initiatives
- `team.html` — team directory table
- `contact.html` — contact details and email-launch form

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. For local development, you may also run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Editing
- Replace the sample NZINC wordmark and tagline in each HTML page with the approved organisation identity.
- Update the sample contact email and location in the footer and `contact.html`.
- Edit project descriptions and project links in `projects.html` and the featured cards in `index.html`.
- Update names and roles in the table in `team.html`.
- Change visual styling in `assets/css/style.css`.
- Change mobile navigation and contact form behaviour in `assets/js/main.js`.

## Images and fonts
Images are loaded from Unsplash image URLs and fonts from Google Fonts. An internet connection is required for those remote assets. Replace image URLs with your own licensed photographs before launch if preferred.

## Important content notes
- The two project descriptions are based on the text supplied in the request.
- The team names and positions are included as supplied.
- The organisation name is represented as **NZINC** based on the supplied project domain. Confirm the exact registered/public-facing name before publishing.
- `hello@nzinc.org.np` is a sample contact address, not a verified address. Replace it with the official contact email.
- The contact form opens the visitor's email application; it does not submit to a server.
- No heavy animation libraries or backend dependencies are used.
