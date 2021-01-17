---
title: Notes for Hexo
date: 2021-01-04 21:51:41
tags: note
---

# Background
这个博客内容将会长期被维护

# Tricks
1. hexo deploy 只会把 **/public** 里面的内容发布到相应的branch，这样没办法维护笔记的源文件

    solution: 使用 *main* 分支维护笔记源文件及Hexo配置，使用 *hexo_display* 分支维护 **/public** 内容（即真正显示在页面上的内容）

1. Suuuuuper recommand tool: [*Travis CI(Continuous Integration)*](https://travis-ci.com/dashboard) 持续集成工具，这东西帮助把 *main* 分支上的东西自动 *generate && deploy* 到 *hexo_display* 分支