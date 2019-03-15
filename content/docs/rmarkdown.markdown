---
title: R Markdown Page

date: 2018-09-09T00:00:00.000Z
lastmod: 2018-09-09T00:00:00.000Z

draft: false
toc: true
type: docs

linktitle: R Markdown Example
menu:
  docs:
    parent: Example Topic
    weight: 2
---

This page provides an example of using R Markdown.

## Code block


```r
x <- 1:10
y <- round(rnorm(10, x, 1), 2)
df <- data.frame(x, y)
df
```

```
##     x     y
## 1   1  0.48
## 2   2  2.38
## 3   3  1.39
## 4   4  5.02
## 5   5  3.75
## 6   6  5.89
## 7   7  6.21
## 8   8  7.79
## 9   9  9.28
## 10 10 10.55
```
