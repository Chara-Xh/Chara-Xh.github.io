# Xiaohan Zhang's Homepage

Personal academic homepage and technical blog, built with Jekyll and the
[Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme.

Live site: <https://chara-xh.github.io>

## Writing a Post

Create a Markdown file under `_posts` using the filename format:

```text
YYYY-MM-DD-post-title.md
```

Each post starts with front matter such as:

```yaml
---
title: Post title
date: 2026-07-15 12:00:00 +0800
categories: [Notes, Communications]
tags: [signal-processing, learning]
---
```

Pushing to `main` triggers the included GitHub Actions workflow and deploys the
site to GitHub Pages.
