---
title: "hello"
author: "nobuo"
date: "2021/3/22"
output: 
  html_document:
    keep_md: true
---
This is a paragraph in an R Markdown document.

Below is a code chunk:


```r
fit = lm(dist ~ speed, data = cars)
b   = coef(fit)
plot(cars)
abline(fit)
```

![](00hello_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

The slope of the regression is 3.9324088.
