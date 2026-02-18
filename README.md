# LolaRyanLCSW.com

Website for Lola Ryan, LCSW — private practice therapist serving clients in Oregon.

## Tech Stack

- [Hugo](https://gohugo.io/) static site generator
- Hosted on GitHub Pages
- Deployed automatically via GitHub Actions on push to `main`

## Local Development

**Prerequisites**: Hugo installed ([installation guide](https://gohugo.io/installation/))

```bash
git clone git@github.com:lolaryan-lcsw/lolaryan-lcsw.github.io.git
cd lolaryan-lcsw.github.io
hugo server
```

Site will be available at `http://localhost:1313`

## Deployment

Pushing to `main` triggers the GitHub Actions workflow, which builds the site and deploys to GitHub Pages. No manual steps required.

The custom domain (`LolaRyanLCSW.com`) is configured via `static/CNAME`.

## Structure

```
content/        # Page content in Markdown
themes/lolaryan/ # Custom theme (layouts, CSS)
static/         # Images and other static assets
.github/        # GitHub Actions deploy workflow
```

## Scheduling Embed

The Contact page includes a placeholder for the booking scheduler. To activate, replace the placeholder div in `layouts/contact/single.html` with the embed code from SimplePractice or Calendly.
