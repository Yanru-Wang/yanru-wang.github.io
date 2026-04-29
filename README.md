# Wei-Kun Chen Homepage

This repository contains a small Jekyll site for Wei-Kun Chen's academic homepage.

## Main Files

- `_pages/about.md`: homepage content
- `_pages/publications.html`: publication list page
- `_publications/`: publication metadata
- `_data/navigation.yml`: top navigation
- `_sass/layout/_google_sites_profile.scss`: custom visual styling

## Local Preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.

## Add a Publication

Create a new Markdown file in `_publications/` with front matter like:

```yaml
---
title: "Paper Title"
collection: publications
category: journal
date: 2026-01-01
authors: "A. Author, W.-K. Chen, and B. Author"
publication: "Journal Name, volume(issue), pages, 2026."
paperurl: "https://doi.org/..."
---
```

Use `category: conference`, `category: journal`, or `category: online` to choose the section on the Publication page.
