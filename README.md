# Minghao Ning academic website

This repository hosts Minghao Ning's academic personal website at:

https://ningminghao.github.io

The site is built with Jekyll using the Academic Pages / Minimal Mistakes theme structure.

## Content

Primary editable content lives in:

* `_pages/about.md` - homepage and research overview
* `_pages/cv.md` - Markdown CV
* `_publications/` - publication entries used by both the Publications page and CV
* `_config.yml` - site metadata, sidebar profile, and social/academic links
* `_data/navigation.yml` - header navigation

## Local preview

Install Ruby dependencies, then run:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The site will be available at http://localhost:4000.
