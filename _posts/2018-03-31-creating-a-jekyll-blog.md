---
layout: single
title:  "Creating a Jekyll Blog"
date:   2018-03-31 22:00:00 -0700
categories: jekyll
---

Following are the steps to create this Jekyll blog.

1. Install Ruby
2. Choose one of the 3 options to host GitHub pages
3. Create a branch named `offline` in the desired repository
4. Create a basic Jekyll site using `jekyll new` in the correct folder
5. Clone minimal-mistakes outside the blog folder
5. Comment the line `gem "jekyll-feed", "~> 0.6"`
6. Modify Gemfile with `gem "minimal-mistakes-jekyll"`
7. Copy `_config.yml` from `minimal-mistakes/_config.yml`
8. Copy `index.html` from `minimal-mistakes/index.html`
9. Change to `layout: single` in `_posts/yyyy-mm-dd-welcome-to-jekyll.markdown`
10. Remove `404.html`, `about.md`, `index.md`
11. copy folders `_data`, `_drafts`, `_docs`, `_pages`, `_pets`, `_portfolio`, `_posts`, `_recipes`, and `assets`
12. Edit `_config.yml`
13. run `bundle install`
