---
title: Hexo blog 配置
date: 2021-10-17 19:45:29
tags: hexo
---
## 配置文件
在 Hexo 中有两份主要的配置文件，其名称都是 _config.yml。 其中，一份位于站点根目录下，主要包含 Hexo 本身的站点配置；另一份位于主题目录下，这份配置由主题作者提供，主要用于配置主题相关的选项。
为了描述方便，在以下说明中，将前者称为 站点配置文件， 后者称为 主题配置文件。
```
./hexo/_config.yml
./hexo/themes/next/_config.yml
```
## 修改语言&站点
打开站点配置文件，搜索 language，找到如下代码：
```
# Site
title: Hexo
subtitle: ''
description: ''
keywords:
author: xx
language: en
timezone: ''
```