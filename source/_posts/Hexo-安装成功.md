---
title: Hexo 安装成功
date: 2016-07-20 23:23:31
tags:
  - hexo
---

花了两个晚上，从知道Hexo到使用到部署到Github上中间遇到了一些坑，首先就是版本的问题。
<!-- more -->
+ nodejs
+ git

安装hexo

```bash
npm install -g hexo
```
```bash
 clean     Removed generated files and cache.
 config    Get or set configurations.
 deploy    Deploy your website.
 generate  Generate static files.
 help      Get help on a command.
 init      Create a new Hexo folder.
 list      List the information of the site
 migrate   Migrate your site from other system to Hexo.
 new       Create a new post.
 publish   Moves a draft post from _drafts to _posts folder.
 render    Render files with renderer plugins.
 server    Start the server.
 version   Display version information.
```

最后一步发布到github上，这个要参照[官方文档](https://hexo.io/docs/deployment.html)如下
```bash
deploy:
  type: git
  repo: <repository url>
  branch: [branch]
  message: [message]
```

Install hexo-deployer-git.

```bash
$ npm install hexo-deployer-git --save
```

就ok了
