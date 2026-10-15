# jeanfraga.github.io

Personal site and blog of Jean Fraga, built with [Jekyll](https://jekyllrb.com) 4 and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme. It deploys to GitHub Pages through GitHub Actions (`.github/workflows/pages-deploy.yml`). Pull requests only build and link-check the site and upload a `site-preview` artifact. Pushes to `main` deploy.

## Local preview

Requires Ruby ≥ 3.1. This clone lives in Google Drive, so keep gems and caches **outside** Drive:

```bash
bundle config set --local path ~/.bundle/jeanfraga-site
bundle install
bundle exec jekyll serve --livereload
```

`_site/`, `.jekyll-cache/` and `vendor/` are gitignored.

## Writing a post

Add `_posts/YYYY-MM-DD-slug.md` with front matter:

```yaml
---
title: "…"
description: "…"            # used for SEO and social previews
date: 2026-10-15 09:00:00 -0400
categories: [Projects, Data Engineering]
tags: [gcp, dbt]
mermaid: true              # only if the post has Mermaid diagrams
image:
  path: /assets/img/posts/cover.png
  alt: "…"
---
```
