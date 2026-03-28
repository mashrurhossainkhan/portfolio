# Mashrur Hossain Khan Portfolio

This repository contains a static personal portfolio website for Mashrur Hossain Khan. It includes a homepage, project highlights, resume and contact sections, a blog index page, and individual blog posts covering DevOps, AWS, Bash, backend engineering, and cloud learning.

## Overview

- `index.html` is the main landing page for the portfolio.
- `blog.html` lists all published blog posts.
- `blog1.html` to `blog17.html` are individual blog pages.
- `css/`, `js/`, `images/`, and `font/` contain the shared frontend assets.
- `sass/tooplate-style.scss` is the source stylesheet for the main theme.

## Tech Stack

- HTML5
- CSS3
- Bootstrap
- JavaScript
- Owl Carousel

## Running Locally

This is a static site, so there is no build step or package installation required.

Open `index.html` directly in a browser, or run a small local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Site Structure

The homepage includes:

- About
- Projects
- Technical Skills
- Experience
- Education & Skills
- Blogs
- Contact

The blog section is split across:

- `index.html` for featured blog cards on the homepage
- `blog.html` for the full blog archive
- `blog*.html` for individual post content

## Updating Content

### Edit portfolio content

Update `index.html` to change:

- intro/about text
- project entries
- experience and education
- contact information
- featured blog cards

### Add a new blog post

1. Create a new file such as `blog18.html` based on an existing blog page.
2. Add the new post card to `blog.html`.
3. Add it to the homepage blog section in `index.html` if it should be featured there.
4. Make sure the page title, meta description, and navigation links are updated.

## Notes

- The site is customized from a Tooplate HTML template.
- Template usage notes are included in `ABOUT THIS TEMPLATE.txt`.
- Because this is a static site, deployment is straightforward on platforms like Amazon S3, CloudFront, GitHub Pages, or Netlify.
