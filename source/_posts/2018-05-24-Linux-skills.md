---
title: Linux skills
date: 2018-05-24 10:43:36
tags:
---

* 删除目录（及子目录）下某一类型的所有文件

`find . -name "*.root" -type f -print -exec rm -rf {} \;`
