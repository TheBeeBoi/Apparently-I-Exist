---
layout: title
title: Finished working on the blog post site
date: 2022-06-19 21:35:44
tags:
---

So, I made a new shell script

```shell
#!/bin/sh
hexo new title $1 && \ # Make empty markdown file
marktext source/_posts/$1.md && \ # Open in markdown editor
hexo generate && \ # build
git add . && \ # stage
git commit Added $1 && \ #  commit
git push # push
```

Nice, right?
