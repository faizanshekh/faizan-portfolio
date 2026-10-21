# Faizan Shaikh — Portfolio Website

A multi-page, static portfolio website for presenting Faizan Shaikh's profile, articles, projects, and contact information.

**Live portfolio:** https://faizanshaikh.vercel.app/

## Pages in this repository

The source files are in `Myportfolio/`:

- `index.html` — home page
- `about.html` — profile/about page
- `project.html` and `project-details.html` — project pages
- `offering.html` — services/offering page
- `article.html` and `article-details.html` — article pages
- `contact.html` — contact page
- `error.html` — error page

## Built with

- HTML
- CSS
- JavaScript and jQuery
- AOS animation library and supporting frontend plugins

The interface includes responsive navigation, theme and text-direction toggles, scroll interactions, animated sections, and image/video popup behavior supplied by the included scripts and assets.

## Run locally

This is a static site; it does not require a Node.js build step.

1. Clone this repository.
2. Open `Myportfolio/index.html` in a browser, or serve the repository with any static-file server.
3. Keep the `Myportfolio/assets/` directory alongside the HTML files so styles, scripts, fonts, and images load.

For example, from the repository root:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/Myportfolio/.

## Project notes

- This repository contains a static multi-page portfolio source. The live portfolio URL above may be deployed separately from this repository.
- The current home-page navigation sends “Projects” to `error.html`; update that link if you want it to open the project listing.
- Review template text, links, and contact details before reusing or publishing the source.
