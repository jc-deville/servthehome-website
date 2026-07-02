# ServTheHome Website

A basic static one-page site for ServTheHome (home networking / low voltage consulting).

## Structure

```
servthehome-website/
├── index.html
├── css/style.css
├── js/script.js
├── images/        (empty — drop real photos/logo here if you have them)
├── CNAME          (custom domain for GitHub Pages)
└── README.md
```

## Before going live

1. **Contact form**: The form posts to `https://formsubmit.co/info@servthehome.com`,
   a free service that emails form submissions without needing a backend server.
   The **first submission** will trigger a confirmation email to info@servthehome.com
   that you must click to activate the endpoint — do this once before relying on the form.
2. **Images**: The hero and icons are inline SVG placeholders (no external image
   dependencies). Add real photos to `images/` and reference them in `index.html`
   whenever you have some.

## Local preview

Just open `index.html` in a browser, or serve it locally, e.g.:

```
npx serve .
```
