# ServTheHome Website

A basic static one-page site for ServTheHome (home networking / low voltage consulting).

## Structure

```
servthehome-website/
├── index.html
├── css/style.css
├── js/script.js
├── images/        (empty — drop real photos/logo here if you have them)
└── README.md
```

## Before going live

1. **Phone number**: `index.html` currently has a placeholder `(555) 555-0123` in the
   Contact section — replace it (and the matching `tel:` link) with your real number.
2. **Contact form**: The form posts to `https://formsubmit.co/info@servthehome.com`,
   a free service that emails form submissions without needing a backend server.
   The **first submission** will trigger a confirmation email to info@servthehome.com
   that you must click to activate the endpoint — do this once before relying on the form.
3. **Domain/hosting**: This is plain static HTML/CSS/JS, so it can be hosted anywhere
   (Netlify, Vercel, GitHub Pages, S3, or standard shared hosting) — just upload the
   folder contents.
4. **Images**: The hero and icons are inline SVG placeholders (no external image
   dependencies). Add real photos to `images/` and reference them in `index.html`
   whenever you have some.

## Local preview

Just open `index.html` in a browser, or serve it locally, e.g.:

```
npx serve .
```
