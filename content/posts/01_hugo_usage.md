+++
title = '使用 Hugo 搭建个人博客'
date = 2024-10-02T00:01:11+08:00
draft = true
+++

## 介绍

https://gohugo.io/


## 设置主题

https://adityatelange.github.io/hugo-PaperMod/

```
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/papermod
echo "theme = 'papermod'" >> hugo.toml
```

## 启动服务

```
hugo server
hugo server --buildDrafts
hugo server -D
```

## 添加内容

```
hugo new content content/posts/my-first-post.md
```

draft=true 才会发布出去

## 打包

```
hugo
```