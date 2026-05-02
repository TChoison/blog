+++
date = '2026-05-02T20:11:25+08:00'
draft = false
title = '测试新文章'
slug = 'test-post'
+++

这是一篇测试文章，验证 CI/CD 自动部署流程是否正常工作。

## 环境

- Hugo 0.161.1
- GitHub Actions
- Ananke 主题

## 测试项

1. 本地 `hugo new` 创建文章
2. Git push 触发 Actions
3. 自动构建并部署到 TChoison.github.io
