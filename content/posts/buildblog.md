---
title: "搭建个人博客"
date: 2021-02-04T17:22:05+08:00
slug: "buildblog"
---

## 为什么要搭建个人博客

都 2021 年了，正经人谁搭建个人博客啊

## 用什么工具

> Github Page 做服务器
> Hugo 生成静态网页

这么弄有几层考虑吧：

1. 国内几家博客站点...广告多，界面陈旧，不可定制等等问题很多。特别是广告，CSDN 的广告让人觉得这就是个三流盗版电子书下载站。
2. 确定不用现成的就要自己搭，但如果从 0 开始建站太麻烦，且学习路径陡峭，既然有现成的个站 Github Page 没理由不用
3. Github Page 推荐用 Jekyll 生成站点，但学习 Jekyll 需要了解 gem 语法且在 Windows 支持并不好。干脆用更流行更快的 Hugo

综上暂定用 github page 写博客，以后买个域名 www.choi30.com 啥的

## 怎么搭建

### step1

生成个空的 Github Page 工程（看这儿 [Github Doc](https://docs.github.com/en/github/working-with-github-pages/getting-started-with-github-pages/)）

这时候只要往仓库里放个 index.html 其实就能用了

### step2

用 Hugo 生成静态网页（看这儿 [HUGO](https://gohugo.io/hosting-and-deployment/hosting-on-github/)）

注意最后只需要将 Hugo 生成的 `/public` 文件夹内容推送到 git 仓库，否则 github 那边认不到 index.html 文件

### step3

打开 [你的博客](https://TChoison.github.io/)

## Tips

1. 技术博客中不应涉及公司机密
2. Markdown 语法高亮/换行等在不同平台支持不同
    - 使用 `&nbsp;` 和 `<br/>` 换行
    - 避免引用太多图片。因为需要单独修改 html 中的 url
3. 美化博客站点本身也算一点技术，不必吝啬精力
