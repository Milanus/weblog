# weblog

A personal blog for posting thoughts and ideas, built with [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com).

## Writing a new post

Add a file named `YYYY-MM-DD-title.md` to the `_posts/` directory with the following front matter:

```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS +0000
categories: general
---

Your post content here.
```

## Local development

1. Install Ruby and Bundler.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve` and open `http://localhost:4000`.