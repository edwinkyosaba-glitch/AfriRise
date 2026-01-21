# AfriRise — Static Website

This repository contains a small static website for AfriRise (landing + contact). It's ready to serve as static files (index.html, styles.css, script.js).

Quick start (no install)
- Open `index.html` in a browser to preview locally.
- For a better dev environment use a static server:
  - Python: `python3 -m http.server 8000` then visit `http://localhost:8000`.
  - Node (if you have Node.js): `npx serve .` or `npx http-server`.

Customize
- Replace `https://example.com/` in `index.html` (OG tags and structured data) with your live URL.
- Replace the Formspree endpoint in the form action with your Formspree ID: `https://formspree.io/f/{your-id}`, or plug in another form backend (Getform, Netlify forms, a server endpoint).
- Replace `support@example.com` with your support email.
- Add your favicon at `/favicon.ico`.

Deploy
- GitHub Pages:
  - Create a repo, push these files, enable Pages from `main` branch (root) or the `docs/` folder.
- Netlify / Vercel:
  - Drag & drop the site folder into Netlify or connect the Git repository — both will serve as static sites.
- Custom domain:
  - Add DNS records per provider instructions. For GitHub Pages, add a `CNAME` file containing your domain.

Extras I can add
- A GitHub Actions workflow to auto-deploy to GitHub Pages.
- A small admin dashboard or registration backend (Node/Express + DB).
- Analytics (privacy-respecting) and cookie-consent.
- React/Vite single-page build if you want a client app.

If you want me to push this to a GitHub repo and set up deployment, tell me:
- repo name (owner/repo),
- preferred deploy target (GitHub Pages / Netlify / Vercel),
- any placeholders to replace (form endpoint and OG URL).
