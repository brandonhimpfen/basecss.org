# base.css Jekyll Site

This is the Jekyll version of the base.css website. It preserves the original Bootstrap-based design and adds a blog powered by Jekyll posts.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`.

## Blog posts

Add new posts to `_posts` using the filename format:

```text
YYYY-MM-DD-post-title.md
```

Each post should include front matter:

```yaml
---
layout: post
title: "Post Title"
description: "Short post description."
author: Brandon Himpfen
---
```

## Structure

- `_layouts/default.html` controls the base HTML shell.
- `_layouts/page.html` controls standard pages.
- `_layouts/post.html` controls blog posts.
- `_includes/nav.html` controls navigation.
- `_includes/footer.html` controls the footer.
- `blog/index.html` lists all posts.
- `assets/css/base.css` contains the existing site styling.
