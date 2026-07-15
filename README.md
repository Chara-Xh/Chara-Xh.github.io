# Chara's Homepage

[![Build and Deploy](https://github.com/Chara-Xh/Chara-Xh.github.io/actions/workflows/pages-deploy.yml/badge.svg)](https://github.com/Chara-Xh/Chara-Xh.github.io/actions/workflows/pages-deploy.yml)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.4-CC0000?logo=jekyll&logoColor=white)](https://jekyllrb.com/)
[![Chirpy](https://img.shields.io/badge/theme-Chirpy-2f80ed)](https://github.com/cotes2020/jekyll-theme-chirpy)

Chara 的个人学术主页与技术博客，主要记录 **Machine Learning**、**通信工程**、课程学习和技术实践。

主页地址：<https://chara-xh.github.io/>

## 网站内容

- Machine Learning 学习笔记与实验记录
- 通信工程、信号处理相关内容
- 论文与技术资料阅读总结
- 课程记录、项目进展与阶段性思考

## 技术栈

- [Jekyll](https://jekyllrb.com/) 静态网站生成器
- [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 博客主题
- GitHub Actions 自动构建与部署
- GitHub Pages 网站托管

## 发布文章

在 `_posts` 目录创建 Markdown 文件，文件名格式为：

```text
YYYY-MM-DD-post-title.md
```

文章需要包含 Front Matter：

```yaml
---
title: 文章标题
date: 2026-07-15 12:00:00 +0800
categories: [Notes, Machine Learning]
tags: ["Machine Learning", "通信工程"]
description: 一句话介绍文章内容。
---
```

提交并推送到 `main` 分支后，GitHub Actions 会自动构建并更新主页。

## 本地预览

需要 Ruby 3.1 或更高版本：

```bash
bundle install
bundle exec jekyll serve
```

随后访问 <http://127.0.0.1:4000/>。

## 主要目录

```text
.
├── _config.yml       # 站点配置
├── _posts/           # 博客文章
├── _tabs/            # About、Categories、Tags、Archives
├── _data/            # 联系方式与分享配置
└── .github/workflows # 自动部署工作流
```

## License

站点框架基于 Chirpy 的 MIT License；文章内容版权归作者所有，除非文章中另有说明。
