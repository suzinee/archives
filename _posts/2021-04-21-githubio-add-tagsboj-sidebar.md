---
title:  "[Giuhub.io] solved.ac sidebar 추가하기"
excerpt: Sidebar 꾸며보자
toc: False
toc_sticky: False
toc_label: "Contents"
sidebar:
  nav: "docs"
categories:
  - blog
tags:
  - jekyll
---



[참고자료](https://mmistakes.github.io/minimal-mistakes/docs/layouts/)

### YAML Front Matter in this post
```yaml
sidebar:
  nav: "docs"
```


### /_data/navigation.yml
```yaml
docs:
  - title: algorithm
    children:
    - title: tags
      url: /tags/#boj
```