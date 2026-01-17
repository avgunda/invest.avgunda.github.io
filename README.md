# Investment Research Blog

A minimalistic and modern blog for sharing investment research, stock analysis, and related articles.

## Built with Jekyll

This site uses Jekyll with the Minima theme for a clean, modern look.

## Adding Posts

To add a new article:

1. Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`
2. Add front matter:

```yaml
---
layout: post
title: "Your Article Title"
date: YYYY-MM-DD
categories: investment
---
```

3. Write your content in Markdown below the front matter.

## Local Development

To run locally (requires Ruby and Jekyll):

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Deployment

This is hosted on GitHub Pages. Push changes to the main branch to deploy automatically.
