# Chara's Homepage

[![Build and Deploy](https://github.com/Chara-Xh/Chara-Xh.github.io/actions/workflows/pages-deploy.yml/badge.svg)](https://github.com/Chara-Xh/Chara-Xh.github.io/actions/workflows/pages-deploy.yml)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.4-CC0000?logo=jekyll&logoColor=white)](https://jekyllrb.com/)
[![Chirpy](https://img.shields.io/badge/theme-Chirpy-2f80ed)](https://github.com/cotes2020/jekyll-theme-chirpy)

Chara's personal academic homepage and technical blog, focused on **Machine Learning**, **Communications Engineering**, coursework, and technical experiments.

Live site: <https://chara-xh.github.io/>

## Contents

- Machine Learning notes and experiments
- Communications Engineering and signal-processing topics
- Paper and technical-book reading notes
- Course records, project updates, and study reflections

## Technology

- [Jekyll](https://jekyllrb.com/) for static-site generation
- [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) as the blog theme
- GitHub Actions for automated builds and deployment
- GitHub Pages for hosting

## Publishing a Post

Create a Markdown file in `_posts` using this filename format:

```text
YYYY-MM-DD-post-title.md
```

Each post begins with Front Matter:

```yaml
---
title: Post title
date: 2026-07-15 12:00:00 +0800
categories: [Notes, Machine Learning]
tags: ["Machine Learning", "Communications Engineering"]
description: A concise description of the post.
---
```

Commit and push the file to `main`. GitHub Actions will build and deploy the updated site automatically.

## Local Preview

Ruby 3.1 or later is required:

```bash
bundle install
bundle exec jekyll serve
```

Open <http://127.0.0.1:4000/> after the server starts.

## Project Structure

```text
.
├── _config.yml       # Site configuration
├── _posts/           # Blog posts
├── _tabs/            # About, Categories, Tags, and Archives
├── _data/            # Contact and sharing configuration
└── .github/workflows # Automated deployment workflow
```

## License

The site framework is based on Chirpy and distributed under the MIT License. Unless otherwise stated, the written content remains the property of its author.
