# LolaRyanLCSW.com

Website for Lola Ryan, LCSW — private practice therapist serving clients in Oregon.

## Tech Stack

- [Hugo](https://gohugo.io/) static site generator
- Hosted on GitHub Pages
- Deployed automatically via GitHub Actions on push to `main`

## Structure

```
content/        # Page content in Markdown
themes/lolaryan/ # Custom theme (layouts, CSS)
static/         # Images and other static assets
.github/        # GitHub Actions deploy workflow
```

## Scheduling Embed

The Contact page includes a placeholder for the booking scheduler. To activate, replace the placeholder div in `layouts/contact/single.html` with the embed code from SimplePractice or Calendly.
